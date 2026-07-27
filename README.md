# alienctl.com Landing Page

This directory contains a minimal static landing-page package for
`alienctl.com`.

## Purpose

The page supports external buyer/operator validation for the design-partner
pilot. It positions alienctl as Swedish-built, customer-owned AI software
change control and
uses the wedge:

```text
No valid Run Control Receipt, no AI-agent PR review.
```

## Deployment Shape

The package is static HTML, CSS, and crawl-control metadata:

```text
landing/alienctl.com/.nojekyll
landing/alienctl.com/index.html
landing/alienctl.com/robots.txt
landing/alienctl.com/sitemap.xml
landing/alienctl.com/styles.css
```

There is no JavaScript, backend, hosted app behavior, auth, database,
credentials, analytics, payments, SDK, dashboard, GitHub integration, or Slack
integration.

The primary call to action opens a structured email application:

```text
mailto:joel.rietz.le@gmail.com
```

This records a qualified response in the buyer-controlled mailbox without
adding analytics, cookies, a form backend, credentials, or a third-party
processor. It does not provide page-view attribution or automated conversion
analytics. Each editorial landing page uses a distinct email subject so Joel
can record the originating content theme without cookies, browser storage,
analytics scripts, or a form processor.

## Search And Answer Metadata

The page includes:

- one canonical URL for `https://alienctl.com/`;
- unique title and meta description;
- Open Graph and Twitter summary metadata;
- Organization, SoftwareApplication, and FAQPage JSON-LD;
- matching visible FAQ answers;
- `robots.txt` and `sitemap.xml`;
- semantic headings, landmarks, skip navigation, and keyboard-visible focus.
- reciprocal English/Swedish `hreflang` metadata and sitemap alternates.

The canonical URL, sitemap, and structured data assume the intended
`alienctl.com` custom domain. They do not configure DNS, verify domain
ownership, submit the sitemap, or guarantee ranking or answer-engine citation.

## Content Boundary

The page may claim that alienctl currently supports local/BYOC receipt-gate
validation for observed AI-agent repo sessions and reviewer-ready workflow
decisions.

The page must not claim code correctness, production safety, compliance, ROI,
hosted behavior, or mature enterprise platform readiness.

## GitHub Pages Deployment

For free static hosting, publish the contents of this directory from a public
GitHub Pages repository. Keep the package root as the Pages source and include
`.nojekyll` so GitHub Pages serves the static files without Jekyll processing.

Do not add analytics, forms, secrets, backend routes, auth, dashboards, SDKs,
or provider integrations as part of the landing-page deployment.

Current deployment:

```text
Repository: https://github.com/joelrietzle/alienctl.com
URL: https://joelrietzle.github.io/alienctl.com/
Source: public GitHub Pages repository, main branch, repository root
```

This is the free GitHub Pages URL. Serving the page at `alienctl.com` still
requires a DNS/custom-domain step owned outside this repository.
