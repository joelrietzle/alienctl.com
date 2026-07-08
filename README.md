# alienctl.com Landing Page

This directory contains a minimal static landing-page package for
`alienctl.com`.

## Purpose

The page supports external buyer/operator validation for the design-partner
pilot. It positions alienctl as AI-agent change control before code review and
uses the wedge:

```text
No valid Run Control Receipt, no AI-agent PR review.
```

## Deployment Shape

The package is static HTML and CSS:

```text
landing/alienctl.com/.nojekyll
landing/alienctl.com/index.html
landing/alienctl.com/styles.css
```

There is no JavaScript, backend, hosted app behavior, auth, database,
credentials, analytics, payments, SDK, dashboard, GitHub integration, or Slack
integration.

All calls to action use the placeholder link:

```text
mailto:hello@alienctl.com
```

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
