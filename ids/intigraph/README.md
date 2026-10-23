# /intigraph/

Persistent identifiers for the [Intigraph](https://intigraph.ai) knowledge-graph stack.
The namespace root redirects to the project homepage. Other paths redirect to
`https://intigraph.ai/ids/<path>` with HTTP 303.

For a vocabulary IRI such as `https://w3id.org/intigraph/quechua/ns#`, request
`text/turtle` for `ns.ttl`, `application/ld+json` for `ns.jsonld`, or HTML for
`ns` (the website redirects that page to `ns/`). Fragments identify terms
within the vocabulary and are not sent in HTTP requests. A trailing slash is
optional for the RDF requests. Turtle takes precedence if both RDF media types
appear in the Accept header; these rules do not rank quality values.

The published catalogue currently lists `quechua/ns`, `quipu/ns`, `seeds/ns`,
and the following `camayoc/` namespaces: `code-entities/ns`, `core/ns`,
`delivery/ns`, `homelab-infra/ns`, `personal-media/ns`, `session-transcript/ns`,
`software-factory/ns`, and `usage-breakdown/ns`.

The wildcard preserves existing paths; it does not guarantee that every path
has a published document. In particular, an entity path needs its own published
target before RDF dereferencing can succeed. These redirects do not rename
existing IRIs or migrate data that uses older namespace IRIs.

## Maintainers

- Steve Brown ([@scbrown](https://github.com/scbrown)), steve@intigraph.ai
