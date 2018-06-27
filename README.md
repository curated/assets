# Curated

Curated is an indexed dataset of popular GitHub comments ranked by user reactions. It's written in Golang and React and it's composed by the following systems:

- Octograph - Go worker - fetches GitHub issues via GraphQL and indexes them into Elasticsearch.
- Elastic - Go http server - search interface consumed by the UI relaying requests to Elasticsearch.
- Web - React responsive web app - UI static assets deployed to GitHub pages at curated.github.io.
