### HTTP AnonCreds Method

The HTTP AnonCreds method uses HTTP URLs as AnonCreds object
identifiers. For this method, the resolution is simple: dereference the URL
to retrieve the published object. While this approach is fairly simple, it
is not recommended for production use for a number of reasons:

- the lack of proof of immutability in the approach (although this could be
  alleviated through the use of hashlinks),
- the lack of a forced relationship between the issuer entity and the AnonCreds
  objects (such as a DID),
- the centralization of the Verifiable Data Registry and hence the possibility of
  surveillance by the web service operator,
- the possibility of rendering the issued credentials useless because the web
  service is removed by its operator, making the AnonCreds objects unresolvable.

The simplicity of this AnonCreds method may make it useful for testing.
Those considering using a web server as a Verifiable Data Registry would likely
be better to use an AnonCreds method based on
[`did:web`](https://w3c-ccg.github.io/did-method-web/).

- Status: In Development
- Verifiable Data Registry: HTTP Web Servers
- Contact Name: Stephen Curran
- Contact Email: swcurran@cloudcompass.ca
- Contact Website: To Be Added
- Specification: To Be Added
