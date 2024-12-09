# Blob gateway

Blob gateway is an on-chain application built by respeer.ai for easy index and fetch for Linera blob data. Linera blob data can only be fetched with graphql `POST` request currently, and there is no indexer for all blob data. So we build blob gateway to let frontend can fetch blob data with `GET` method then display it with `<img>` tag directly. We also build a simple indexer within blob gateway then we can display all registered blob data at frontend.