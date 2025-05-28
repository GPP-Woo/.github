# GPP-Woo

This repository serves two purposes:

* Applying some (Github) organisation wide configuration and content
* Keeping configuration in version control that's shared by multiple components

## Shared file types configuration

`fileTypes.json` is a list of accepted file types. Only files of these file types can
be uploaded and added to the search index. Additionally, for each file type we keep
track whether it's suitable for full-text search indexing in Elastic Search.

Used by:

* https://github.com/GPP-Woo/GPP-app
* https://github.com/GPP-Woo/GPP-zoeken
