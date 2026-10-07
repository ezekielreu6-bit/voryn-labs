# Voryn Labs

Voryn Labs builds small internet tools for people who make things and need one clear place to send someone.

This repository is the company directory. It does not run the products. Each product has its own site and codebase.

- Company: [voryn.xyz](https://voryn.xyz)
- Directory: [github.com/ezekielreu6-bit/voryn-labs](https://github.com/ezekielreu6-bit/voryn-labs)

## Products

### Profyl

One professional page. Built around how you work.

[getprofyl.cv](https://getprofyl.cv)

Profyl is a single public page for a person who does more than one kind of work. You claim `getprofyl.cv/yourname`, pick a Profyl Type, and publish. Switching type does not delete the other type's content. Blocks that do not belong to the current type stay saved and hidden until you switch back.

The three types:

- Creator: links, socials, and drops. Use this when the page is for an audience.
- Professional: about, skills, experience, and contact. Use this when the page should read like an interactive resume.
- Portfolio: projects and case studies first. Use this when the work should lead.

What it includes:

- A public page at a Profyl URL, with custom domains on Pro.
- A Lead Inbox, so messages from the page land inside Profyl instead of a separate form tool.
- An opt-in Explore directory for finished pages. Unfinished pages stay reachable at their URL and are not listed.
- Free to publish. Pro adds custom domains, analytics, link icons, and removal of the Profyl footer.

Code: [ezekielreu6-bit/Profyl](https://github.com/ezekielreu6-bit/Profyl) (private)

Profyl is not Profyl.io, Profyl.net, or Profyl.app. Those are different products.

### FORX

Forms without the backend.

[forx.voryn.xyz](https://forx.voryn.xyz)

FORX is a form endpoint. You create an endpoint in the dashboard, point an HTML form, `fetch`, or cURL request at it, and FORX validates, stores, and delivers the submission. There is no SDK.

What it includes:

- Endpoints such as `forx.voryn.xyz/f/your-id`.
- Delivery by email, signed webhook, or your own API.
- Honeypot and domain lock, so an endpoint can reject bots and requests from other sites.
- A consistent payload with a request id, so a submission can be replayed and checked.
- Free, Starter, and Pro plans. Free is for testing. Starter is the plan for a live form.

Code: [ezekielreu6-bit/forx](https://github.com/ezekielreu6-bit/forx) (private)

### vendX

A digital storefront for independent creators.

[vendx.voryn.xyz](https://vendx.voryn.xyz)

vendX is a shop for digital products. A creator gets a shareable store, checkout, file delivery, and a sales dashboard without joining those pieces from separate tools.

What it includes:

- A store at `vendx.voryn.xyz/yourname`.
- USD and Naira checkout through Bachs.
- A secure, time-limited download link after a completed payment.
- A dashboard for sales, the platform fee, and creator earnings.
- No monthly subscription. vendX takes 5% of a completed sale. Payment-provider charges, refunds, and taxes are separate.

Code: [ezekielreu6-bit/vend-x](https://github.com/ezekielreu6-bit/vend-x) (private)

## How they fit

Use Profyl when the goal is a public identity page. Use FORX when a site already exists and only needs a form endpoint. Use vendX when the thing being shared is a digital product for sale.

A Profyl page can link to a vendX store. A FORX endpoint can receive a contact form from either.
