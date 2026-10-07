# Voryn Labs

Voryn Labs is an independent software studio. It builds small internet tools for people who make things and need one clear place to send someone.

This repository is the company directory. It does not run the products. Each product has its own site, database, and codebase.

- Studio: [voryn.xyz](https://voryn.xyz)
- Directory: [github.com/ezekielreu6-bit/voryn-labs](https://github.com/ezekielreu6-bit/voryn-labs)
- Built by Ezekiel Reuben, in Nigeria

## Products

| Product | Job | Live site |
| --- | --- | --- |
| Profyl | One public professional page | [getprofyl.cv](https://getprofyl.cv) |
| FORX | A form endpoint, no SDK | [forx.voryn.xyz](https://forx.voryn.xyz) |
| vendX | A shop for digital products | [vendx.voryn.xyz](https://vendx.voryn.xyz) |

## Profyl

One professional page for multi-hyphenates. One profile, built around how you work.

[getprofyl.cv](https://getprofyl.cv)

Profyl is a single public page for a person who does more than one kind of work. You claim `getprofyl.cv/yourname`, pick a Profyl Type, and publish. No code is required. A page can be live in a few minutes.

Switching type does not wipe the page. Blocks that do not belong to the current type stay saved and hidden until you switch back.

### Types

- Creator. Social channels, media drops, community links, and a direct inquiry inbox. The public page shows an avatar, bio, socials, links, and contact.
- Professional. Skills, experience, credentials, and client services. The public page shows about, skills, experience, contact, and selected links.
- Portfolio. Projects, case studies, visual client work, and featured galleries. The public page shows featured projects, case studies, and a hire or contact path.

### What a published page includes

- A public URL at `getprofyl.cv/yourname`. Pro can connect a custom domain.
- A Lead Inbox. Inquiries from the page land inside Profyl instead of disappearing in DMs.
- Basic insights on the free plan. Full analytics on Pro.
- An opt-in Explore directory for finished pages. An unfinished page stays reachable at its URL and is not listed.
- Free to publish. Pro adds unlimited links and projects, a custom domain, full analytics, link icons, and removal of the Profyl footer.

Code: [ezekielreu6-bit/Profyl](https://github.com/ezekielreu6-bit/Profyl) (private)

Profyl is not Profyl.io, Profyl.net, or Profyl.app. Those are different products. Profyl is also not a freeform tile grid. Bento.me shut down on 13 February 2026. Profyl is a typed-page alternative, not a copy of that layout.

## FORX

Forms without the backend.

[forx.voryn.xyz](https://forx.voryn.xyz)

FORX is the missing backend for a frontend form. You create an endpoint in the dashboard, then point an HTML form, a `fetch` call, or a cURL request at it. FORX validates, stores, and delivers the submission. There is no SDK. HTML, fetch, or cURL is the integration.

### How a submission moves

1. Create an endpoint and copy a URL like `forx.voryn.xyz/f/your-id`.
2. Point the form at that URL.
3. FORX delivers the same payload by email, a signed webhook, or your own API.

Every submission keeps a consistent shape, a timestamp, and a request id, so it can be checked and replayed.

### Controls

- Signed webhooks, so the receiver can verify the payload came from FORX.
- Honeypot and domain lock, to drop bots and reject requests from other sites.
- Delivery retries on paid plans.

### Plans

- Free, $0. For testing a personal project. 50 submissions a month, 2 active endpoints, 30-day history, email notifications.
- Starter, $4 a month. The plan for a live form. 1,000 submissions a month, 10 active endpoints, 1-year history, webhooks and delivery retries.
- Pro, $10 a month. More room and API access. 10,000 submissions a month, 50 active endpoints, unlimited history, API access, and priority support.

Code: [ezekielreu6-bit/forx](https://github.com/ezekielreu6-bit/forx) (private)

## vendX

A digital storefront for independent creators.

[vendx.voryn.xyz](https://vendx.voryn.xyz)

vendX gives a creator the storefront, payments, delivery, and numbers to sell digital products without stitching five tools together. A store lives at `vendx.voryn.xyz/yourname`.

### What a sale includes

- A shareable shop for the products you make.
- Checkout in USD and Naira through Bachs.
- A secure, time-limited download link after a completed payment.
- A dashboard for sales, the platform fee, and creator earnings.

### Price

There is no monthly subscription. vendX takes 5% of a completed sale, so the creator keeps 95%. Payment-provider charges, refunds, and taxes are separate and depend on the account and the transaction.

A ₦100,000 sale is a ₦5,000 vendX fee and ₦95,000 in creator earnings, before those separate charges.

Code: [ezekielreu6-bit/vend-x](https://github.com/ezekielreu6-bit/vend-x) (private)

## How they fit

Use Profyl when the goal is a public identity page. Use FORX when a site already exists and only needs a form endpoint. Use vendX when the thing being shared is a digital product for sale.

A Profyl page can link to a vendX store. A FORX endpoint can receive a contact form from a site that is not built on either of the other two.

## What this repo is not

This repo is not the source for Profyl, FORX, or vendX. Product code stays in those private repositories. Issues about a product belong on that product, not here.
