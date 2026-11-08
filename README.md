# MIDAD AI Community

A lightweight, open community demonstration and documentation site for MIDAD AI.

**This repository is an isolated community package. It is not the MIDAD commercial platform, production control plane, or a live operational dashboard.**

## What is included

- A static, mobile-friendly demonstration page.
- Architecture and Linux-hosting documentation.
- Contributor and security-reporting guidance.
- Clearly labelled illustrative data only.

## What is intentionally excluded

This repository does not include or connect to payment processing, checkout, customer records, trading execution, wallet signing, mining accounts, private APIs, production databases, credentials, tokens, or internal automation endpoints. It makes no network requests and contains no production secrets.

## License

This repository is licensed under the Apache License 2.0. The license does not grant rights to MIDAD AI trademarks, other repositories, external services, or separately licensed third-party materials.

## Run locally

From the repository root:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

No package installation, build step, API key, database, or runtime service is required.

## Status

The dashboard is a static illustration populated with synthetic sample labels. It does not represent live service health, active agents, production metrics, or revenue.
