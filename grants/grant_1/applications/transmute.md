# Name of DIF member (organization or individual)
* Transmute

### Are you a member of DIF?
* Yes

### Are you now a member of the C&C WG? If not, would you be willing to join if chosen for this grant? 
* Yes

## The selection criteria for the work item lead is as follows:

* familiarity with JWS mechanics and common JOSE libraries/best-practices
* experience with automated testing, vector design, and test scripts/suites
* familiarity with LD Proofs and signature suites generally
* familiarity with JSON/JSON-LD interop problems, at the semantic, signature-verification, and representation/parsing levels

### Qualifications as per the criteria above
Transmute has experience with the selection criteria, our VC implementation supports both JWT and LD Proofs

### Relevant links you'd like to share (i.e. repositories, test suites, or specifications)
https://github.com/OR13/GNARLY (example API with tests supporting both VC-JWT and JsonWebSignature2020)

### Could you commit to this work being done by the end of 2021?
- Yes

## Additional Submission Details
### Note in the initial call for submissions the identified medium was slack

As Per https://difdn.slack.com/archives/C4X50SNUX/p1626973031179000?thread_ts=1626972131.178500&cid=C4X50SNUX

• https://github.com/w3c-ccg/lds-jws2020
Registered the did key test vectors associated with it here:
• https://github.com/w3c/did-test-suite/blob/main/packages/did-core-test-server/suites/implementations/did-key-transmute.json#L26
• http://did.key.transmute.industries/ (generate / resolve application/did+json for examples)
Updating VC-JWT implementation to use that suite directly for the cases where RDF DataSet normalization is not used (VC-JWT):
• https://github.com/transmute-industries/verifiable-data/pull/71
here is an example of the new top level API for issuing from the same key, both a VC-JWT and an LD Proof using that suite:
````
const result = await verifiable.credential.create({
    credential: {
      ...fixtures.credential,
      issuer: { id: fixtures.key.controller }, // make sure issuer is set correctly
    },
    format: ["vc", "vc-jwt"],
    documentLoader: fixtures.documentLoader,
    suite: new JsonWebSignature({
      key: await JsonWebKey.from(fixtures.key as JsonWebKey2020),
      date: fixtures.credential.issuanceDate, // make signature stable
    }),
  });
```