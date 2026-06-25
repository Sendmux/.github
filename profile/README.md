# Sendmux

Sendmux is an email platform for sending, receiving, and automating product email workflows. AI Agents can sign up for a free email address at [myagent.mx](https://myagent.mx)

## TL;DR

| Need | Link |
| --- | --- |
| Learn about Sendmux | [sendmux.ai](https://sendmux.ai) |
| Use the product | [app.sendmux.ai](https://app.sendmux.ai) |
| Read the docs | [sendmux.ai/docs](https://sendmux.ai/docs) |
| Install the CLI | [Homebrew tap](https://github.com/Sendmux/homebrew-tap) (`brew install sendmux/tap/sendmux`) |
| Use SDKs, CLI, or MCP | [Sendmux SDK monorepo](https://github.com/Sendmux/sendmux-sdk) |
| Report a docs issue | [Sendmux docs issues](https://github.com/Sendmux/sendmux-docs/issues) |
| Get support | [Support policy](https://github.com/Sendmux/.github/blob/main/SUPPORT.md) |
| Report a vulnerability | [Security policy](https://github.com/Sendmux/.github/blob/main/SECURITY.md) |

## SDKs

| Surface | Package |
| --- | --- |
| TypeScript SDK | [`@sendmux/sdk`](https://www.npmjs.com/package/@sendmux/sdk) |
| Python SDK | [`sendmux-sdk`](https://pypi.org/project/sendmux-sdk/) |
| Go SDK | [`sendmux.ai/go`](https://pkg.go.dev/sendmux.ai/go) |
| PHP SDK | [`sendmux/sdk`](https://packagist.org/packages/sendmux/sdk) |
| Ruby SDK | [`sendmux-sdk`](https://rubygems.org/gems/sendmux-sdk) |
| CLI | [Homebrew](https://github.com/Sendmux/homebrew-tap) or [`@sendmux/cli`](https://www.npmjs.com/package/@sendmux/cli) |
| MCP servers | [`sendmux-mcp`](https://pypi.org/project/sendmux-mcp/) |

The SDK monorepo also contains surface packages for sending, mailbox, and management workflows where those packages are published separately.

## Contributing

Organisation defaults live in this repository and apply to Sendmux repositories that do not define their own files.

- Read [contributing guidelines](https://github.com/Sendmux/.github/blob/main/CONTRIBUTING.md) before opening a pull request.
- Use the issue templates so maintainers receive the details needed to triage quickly.
- Never paste API keys, passwords, tokens, webhook secrets, customer data, or private account details into GitHub.
- Report vulnerabilities through the [security policy](https://github.com/Sendmux/.github/blob/main/SECURITY.md), not public issues.

## Why Sendmux

Email platforms were built for people clicking send, not agents and product workflows that need to send, receive, route, and react to email from code.

Sendmux gives teams one email platform for outbound delivery, programmable inboxes, provider routing, delivery monitoring, and workflow automation.

- **Send and receive from one place.** Send through API or SMTP, receive into programmable mailboxes, and manage product email workflows from the same workspace.
- **Bring your providers.** Connect Gmail, Outlook, SendGrid, Mailgun, Resend, Amazon SES, or any SMTP-compatible provider; Sendmux handles routing, failover, monitoring, and quota guardrails.
- **Agent-ready inboxes.** Incoming email is parsed into structured JSON so agents can work with subject, body, attachments, headers, and metadata without custom email parsing.
- **Production visibility.** Delivery logs, bounces, complaints, webhooks, and provider health monitoring help teams see what happened and respond quickly.
- **Proven at scale.** 50M+ emails sent, 100+ teams building with Sendmux, and up to 80% fewer tokens consumed per message compared with raw email parsing.
