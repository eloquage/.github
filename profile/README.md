<div align="center">

# Eloquage

**Local-first AI & search infrastructure for PHP.**

Small, sharp, composable packages — vector math, embeddings, lexical search,
tokenizers, chunking, scoring, and ONNX inference — that run in-process,
with optional native extensions when you need the speed.

</div>

---

## The PHP RAG stack

| Package | What it does |
|---|---|
| [`vector`](https://github.com/eloquage/vector) | In-process vector math: cosine, dot, L2, top-k, batch similarity |
| [`embed`](https://github.com/eloquage/embed) | Embedding helpers: normalize, chunk metadata, cache keys, provider-agnostic DTOs |
| [`beacon`](https://github.com/eloquage/beacon) | Local semantic search: store embeddings, query top-k, filter by metadata |
| [`lex`](https://github.com/eloquage/lex) | Lexical search toolkit: tokenization, n-grams, BM25, inverted indexes |
| [`tokens`](https://github.com/eloquage/tokens) | Fast tokenizers: BPE/WordPiece encode/decode, batch tokenization |
| [`chunk`](https://github.com/eloquage/chunk) | Document chunking: overlapping windows, markdown/code-aware splits, token budgets |
| [`score`](https://github.com/eloquage/score) | In-request ML scoring: exported linear/tree models for ranking & pricing |
| [`onnx`](https://github.com/eloquage/onnx) | Thin ONNX Runtime bindings — portable models, no Python sidecar |
| [`rerank`](https://github.com/eloquage/rerank) | Cross-encoder & feature-based reranking for lexical + vector pipelines |

Every package ships as a pure-PHP implementation with an optional
PIE-compatible native extension (`*-ext`) built with
[`typephp-builder`](https://github.com/eloquage/typephp-builder).

## Laravel tooling

| Package | What it does |
|---|---|
| [`docker-php`](https://github.com/eloquage/docker-php) | Docker Engine API client for Laravel with a Livewire management UI |
| [`laravel-cloudflare`](https://github.com/eloquage/laravel-cloudflare) | Run Laravel natively on the Cloudflare Developer Platform |
| [`cloudflare-filament`](https://github.com/eloquage/cloudflare-filament) | Filament v5 dashboard for the Cloudflare ecosystem |
| [`filament-horizon`](https://github.com/eloquage/filament-horizon) | Horizon integration for Filament |
| [`laravel-mcp-fetch`](https://github.com/eloquage/laravel-mcp-fetch) · [`laravel-mcp-ops`](https://github.com/eloquage/laravel-mcp-ops) | MCP servers: fetching & ops health |
| [`laravel-google-workspace`](https://github.com/eloquage/laravel-google-workspace) · [`laravel-notebooklm`](https://github.com/eloquage/laravel-notebooklm) | Google integrations |

## License

All packages are MIT-licensed. Built by [Miguel Enes](https://github.com/miguelenes).
