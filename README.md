# Upanga Social Media Mirror

Public, read-only media mirror for approved Upanga: The Soul Blade social
assets. The source library remains outside Git at
`D:\Projects\upanga-media\social`.

Files are addressed by the same deterministic path used by Upanga Social
Manager:

```text
media/<sha256>/<file-name>
```

This repository is published with GitHub Pages so Cloudflare Worker provider
adapters can fetch approved media over HTTPS. Do not commit passwords, tokens,
private data, or unapproved source material here.
