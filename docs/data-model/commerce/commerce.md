---
title: "Commerce data types"
sidebar_label: Data types
description: "Connect to your SMB customers' eCommerce, PoS and payment data sources"
createdAt: "2020-10-01T13:56:59.781Z"
updatedAt: "2022-11-23T14:24:21.457Z"
---

The data model for commerce data sources includes all the data types that you can pull, or retrieve, from the Codat API.

## Supported commerce data types

:::note Data coverage explorer

View the full details of the data types that Codat supports for each commerce platform in the <a className="external" href="https://knowledge.codat.io/supported-features/commerce?view=tab-by-data-type" target="_blank">Data coverage explorer</a>.
:::

The following commerce data types are available via Codat's API:

- [Company info](/data-model/commerce/-companyinfo) – details of a linked company, such as their address, phone number, and company registration.
- [Customers](/data-model/commerce/-customers) – details of customers who have placed orders with the company.
- [Disputes](/data-model/commerce/-disputes) – details of all transactions that customers have challenged.
- [Locations](/data-model/commerce/-locations) – details of geographic locations where [product variant inventory](/data-model/commerce/-products#product-variant-inventory) is held.
- [Orders](/data-model/commerce/-orders) – details of all orders received by a company, including payments, service charges, and refunds.
- [Payments ](/data-model/commerce/-payments) – amounts reserved against the customer's funding source.
- [Payment Methods ](/data-model/commerce/-paymentmethods) – represents the payment methods used by customers to make payments.
- [Products](/data-model/commerce/-products) – details of the products a company has available on the system, including the price and quantity of those products, and product variants (where available).
- [Transactions](/data-model/commerce/-transactions) – details of all financial transactions recorded in the system.

## Integrations setup

For full instructions on how to set up an integration for a specific commerce platform see the [Commerce integrations](/commerce-api/overview) section.
