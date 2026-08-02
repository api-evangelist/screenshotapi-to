# ScreenshotAPI (screenshotapi.to)

API Evangelist catalog entry for [ScreenshotAPI](https://screenshotapi.to) — a hosted screenshot
and PDF capture API. Send a URL or raw HTML, get back a PNG, JPEG, WebP or PDF without running
browser infrastructure.

> **Not ScreenshotAPI.net.** A different company operates [screenshotapi.net](https://screenshotapi.net)
> in the same category, catalogued separately as `screenshotapi-net`. The names are near-identical;
> the companies are not related.

## The API

| | |
|---|---|
| Spec | OpenAPI 3.1.0 |
| Paths / operations | 2 / 3 |
| Schemas | 2 |
| Auth | API key in `x-api-key`, or a bearer token |
| Base | `https://screenshotapi.to` |

`GET` and `POST` on `/api/v1/screenshot`, plus `GET /api/health`. A small contract on purpose —
it does one thing.

## Agent-readable surface

Unusually thorough for the size of the API: [`llms.txt`](https://screenshotapi.to/llms.txt) on the
root, a 302KB [`llms-full.txt`](https://screenshotapi.to/llms-full.txt), a separate docs
`llms.txt`, an [agent install guide](https://screenshotapi.to/llms-install.md), a dedicated
[AI-agents page](https://screenshotapi.to/ai-agents), and per-page markdown by appending `.md` to
any `/docs/*` URL.

An MCP server is documented with four tools, but it runs locally over stdio and is not yet
published to npm — so it is noted here rather than listed as a hosted endpoint.

## This is a catalog entry, not ScreenshotAPI

This repo is API Evangelist's profile *about* ScreenshotAPI, not operated by them. For the product,
an API key, or support, go to [screenshotapi.to](https://screenshotapi.to).

If something in this profile is wrong, an issue here is the right place, and so is the
[APIs.io Inbox](https://github.com/api-search/inbox).
