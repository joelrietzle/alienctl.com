# alienctl.com

[alienctl.com](https://alienctl.com/) is the public website for alienctl:
Swedish-built, customer-owned control and evidence for AI-produced software
changes.

## Purpose

The website supports external buyer and operator validation for a bounded
design-partner pilot. Its product boundary is the decision before human review:
whether an observed AI-agent repository session has enough evidence and
approval to proceed.

The current wedge is:

```text
No valid Run Control Receipt, no AI-agent PR review.
```

## Deployment Shape

The package is static HTML, CSS, and crawl-control metadata:

```text
.nojekyll
index.html
robots.txt
sitemap.xml
styles.css
```

There is no JavaScript, backend, hosted app behavior, auth, database,
credentials, analytics, payments, SDK, dashboard, GitHub integration, or Slack
integration.

The primary call to action opens a structured email application:

```text
mailto:hello@alienctl.com
```

This records a qualified response in the buyer-controlled mailbox without
adding analytics, cookies, a form backend, credentials, or a third-party
processor. It does not provide page-view attribution or automated conversion
analytics. Each editorial landing page uses a distinct email subject so Joel
can record the originating content theme without cookies, browser storage,
analytics scripts, or a form processor.

## Search And Answer Metadata

The website includes:

- one canonical URL for `https://alienctl.com/`;
- unique title and meta description;
- Open Graph and Twitter summary metadata;
- Organization, SoftwareApplication, and FAQPage JSON-LD;
- matching visible FAQ answers;
- `robots.txt` and `sitemap.xml`;
- semantic headings, landmarks, skip navigation, and keyboard-visible focus.
- reciprocal English/Swedish `hreflang` metadata and sitemap alternates.

The canonical URL, sitemap, and structured data use the verified
`https://alienctl.com/` custom domain. Search-engine discovery remains external
state: valid metadata and sitemap submission do not guarantee crawling,
indexing, ranking, or answer-engine citation.

## Content Boundary

The page may claim that alienctl currently supports local/BYOC receipt-gate
validation for observed AI-agent repo sessions and reviewer-ready workflow
decisions.

The page must not claim code correctness, production safety, compliance, ROI,
hosted behavior, or mature enterprise platform readiness.

## GitHub Pages Deployment

The repository root is published from the `main` branch through GitHub Pages.
The `.nojekyll` marker keeps the deployment on the static-file path.

Do not add analytics, forms, secrets, backend routes, auth, dashboards, SDKs,
or provider integrations as part of the landing-page deployment.

Current deployment:

```text
Repository: https://github.com/joelrietzle/alienctl.com
Canonical URL: https://alienctl.com/
Source: public GitHub Pages repository, main branch, repository root
```
