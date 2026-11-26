# <picture><source media="(prefers-color-scheme: dark)" srcset="public/assets/mark-dark.svg"><img src="public/assets/logo.svg" alt="" height="64" /></picture> Bold Performance

<img src="public/assets/og-image.png" alt="Bold Performance — Personal training with Brock Jones" width="1280" />

[![CI](https://img.shields.io/github/actions/workflow/status/nicholasadamou/bold-performance/ci.yml?branch=main&label=CI&labelColor=161C1D)](https://github.com/nicholasadamou/bold-performance/actions/workflows/ci.yml)
![Astro](https://img.shields.io/badge/Astro-1E7184?labelColor=161C1D&logoColor=F6F6F1&logo=astro)
![React](https://img.shields.io/badge/React-1E7184?labelColor=161C1D&logoColor=F6F6F1&logo=react)
![Bun](https://img.shields.io/badge/Bun-1E7184?labelColor=161C1D&logoColor=F6F6F1&logo=bun)
![Flox](https://img.shields.io/badge/Flox-1E7184?labelColor=161C1D&logoColor=F6F6F1&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNjAgMjYwIj48cGF0aCBkPSJNMjE1LjQ5OCAxNkgxMDAuMjczTDQ0IDczLjE2NjZWMTMwLjMzM0gxMDEuMTY2TDIxNS40OTggNzMuMTY2NlYxNlpNMTAxLjE2NyAxMzAuMzM0SDIxNS40OTlWMTg3LjUwMUgxMDEuMTY3VjEzMC4zMzRaTTQ0IDE4Ny41MTNIMTAxLjE2NlYyNDQuNjc5SDQ0VjE4Ny41MTNaIiBmaWxsPSIjRjZGNkYxIi8%2BPC9zdmc%2B)
[![License](https://img.shields.io/badge/License-PolyForm_Shield_1.0.0-1E7184?labelColor=161C1D)](LICENSE)

Brock Jones’s personal training and performance coaching website in Scottsdale,
Arizona. Visitors can explore coaching services, use twenty training tools, and
prepare a detailed introduction. The intake creates an email draft or sends
through Formspree when configured.

[Visit Bold Performance](https://bold-performance.vercel.app)

## Getting started

```sh
flox activate
bun install --frozen-lockfile
bun run dev
```

## Documentation

- [Visitor guide](docs/visitor-guide.md): coaching pages, FAQs, and the intake form.
- [Getting started and local verification](docs/development.md): Flox, previews, and the shared quality gate.
- [Training tools](docs/tools.md): calculator behavior and planning guides.
- [Contact setup](docs/contact.md): email drafts and optional form delivery.
- [Brand assets and content](docs/content.md): logos, photography, and editing guidance.
- [Deployment](docs/deployment.md): Vercel hosting and automatic releases.

## Local verification

Run `./scripts/check.sh` inside Flox. It checks formatting, Markdown and Mermaid,
links, source budgets, types, unit tests, the production build, and workflow
syntax. The pre-commit hook and GitHub Actions run the same gate.

See [development](docs/development.md) for browser QA and preview commands.

## License

Copyright © 2026 Nicholas Adamou.

The project is licensed under [PolyForm Shield License 1.0.0](LICENSE).
