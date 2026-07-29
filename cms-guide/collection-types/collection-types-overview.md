---
title: "Collection Types"
sidebarTitle: "Overview"
description: "Collection Types in Strapi are used to manage repetitive master data with the same structure."
---

<CardGroup cols={3}>
  <Card title="Multiple Entries" icon="files">
    Store and manage thousands of data entries under a single schema.
  </Card>

  <Card title="Unified Structure" icon="sitemap">
    Ensure all entries follow the same field definitions and validation rules.
  </Card>

  <Card title="Use Cases" icon="layer-group">
    Ideal for repetitive data like articles, products, events, and pages.
  </Card>
</CardGroup>

<Note>
  This page preserves the original wording from `[EN] Tempe Park Doc-part-3.pdf` and organizes it into clear step-by-step guidelines for easier navigation.
</Note>

## What are Collection Types?

Collection Types in Strapi are content types used to manage master data that is repetitive (multiple entries) and has the same structure. Collection Types allow the system to store multiple data entries within a single content schema, making them ideal for data such as articles, products, news, landing pages, events, or other master data.

---

## How to Work with Collection Types

Follow this step-by-step workflow to understand and manage Collection Types in the CMS:

<Steps>
  <Step title="Define the Schema Structure">
    Identify the repetitive data requirements for your module (e.g., fields like `Title`, `Slug`, `Description`, `Publish Date`).
  </Step>
  <Step title="Create the Collection Type">
    Build the schema under Strapi's Content-Type Builder. This schema serves as the single blueprint for all future data entries of this type.
  </Step>
  <Step title="Add and Manage Repetitive Entries">
    Navigate to the Content Manager to add multiple independent records under the created Collection Type (e.g., adding multiple individual Articles or Products).
  </Step>
  <Step title="Publish and Serve Content">
    Manage entry statuses (`Draft` or `Published`) and expose the collected data via API endpoints to be rendered on the frontend.
  </Step>
</Steps>