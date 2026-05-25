# Sendmux — Email infrastructure for AI agents

Sendmux is an email API that lets AI agents send, receive, and route email from a single platform. One platform. Your providers. Your mailboxes. No glue code.

## What is Sendmux?

Sendmux is a multi-provider email API built for AI email agents and the developers building them. Connect your own SMTP providers — Gmail, Outlook, SendGrid, Mailgun, Resend, Amazon SES, or any SMTP-compatible service — and manage outbound routing, inbound mailboxes, and delivery monitoring from one team workspace.

We also give you a managed Amazon SES account to start sending immediately. No provider setup required.

## The problem we solve

Email tools weren't built for agents.

Outbound platforms handle delivery. Inbox providers handle receiving. You glue them together with custom code, manage separate APIs, and pay separate bills. When an email arrives, your agent gets a raw HTML blob that burns thousands of LLM tokens just to understand what happened.

Here's the thing: it doesn't have to be this way.

Sendmux gives you one API for sending and receiving. Structured JSON instead of raw MIME. Up to 80% fewer tokens consumed per message.

## What you can do with Sendmux

**Send email via API or SMTP**
Queue single or batch messages with JSON requests. Or connect any existing mail client with standard SMTP on port 587. Weighted distribution across providers with automatic failover. Quotas at four levels: per-second, minute, hour, and day.

**Receive and parse email**
Set up mailboxes with custom domains. Incoming email is parsed into clean JSON — subject, body, attachments, headers — so your agent can act on it immediately. No HTML parsing. No token waste.

**Monitor everything**
Real-time dashboards, delivery logs, bounce and complaint tracking, and webhook notifications. Health monitoring that disables failing providers automatically.

## By the numbers

- 50M+ emails sent through the platform
- 100+ teams building with Sendmux
- All major SMTP providers supported
- Up to 80% token savings vs raw email parsing

## Repositories

### [docs](https://github.com/sendmux/docs)
Guides and API references for sending, receiving, and monitoring email with Sendmux. Built on Mintlify.

Coming soon:
- **MCP server** — connect Sendmux to any Model Context Protocol client
- **CLI** — manage teams, mailboxes, and providers from the terminal
- **Agent framework integrations** — plug-and-play connectors for popular agent building platforms

## Get started

- **Website:** [sendmux.ai](https://sendmux.ai)
- **Docs:** [docs.sendmux.ai](https://docs.sendmux.ai)
- **App:** [app.sendmux.ai](https://app.sendmux.ai)
- **Support:** contact@sendmux.ai

## FAQ

**What is an agent inbox?**
An agent inbox is a programmable email mailbox — also called a programmatic inbox — designed for AI agents rather than humans. It receives email, parses it into structured data, and makes it available via API so agents can read and respond programmatically.

**Is Sendmux a transactional email API?**
Yes. Sendmux handles transactional, triggered, and application email for AI agents and their human teams. You can also use it for inbound email parsing and routing.

**Can I bring my own SMTP provider?**
Absolutely. Connect Gmail, Microsoft 365, SendGrid, Mailgun, Resend, Amazon SES, or any SMTP-compatible provider. Sendmux routes across them with weighted distribution and automatic failover.

**Do you offer a free email sending API?**
Yes. Every team starts free. We also provide a managed Amazon SES account for immediate sending without provider configuration.

**What is a multi-provider email API?**
A multi-provider email API lets you connect multiple sending services and route traffic across them intelligently. If one provider has deliverability issues, traffic fails over automatically.
