---
title: "Simplify Your SOQL Queries Using SOQL FORMULA() in WHERE"
url: "https://developer.salesforce.com/blogs/2026/06/simplify-your-soql-queries-using-soql-formula-in-where"
date: "2026-06-04"
author: "Dikshita Patel"
feed_url: "https://developer.salesforce.com/blogs/feed"
---
Salesforce's new FORMULA() function in SOQL WHERE clauses allows developers to filter records using computed expressions directly in queries rather than creating formula fields or post-processing data in code. This pilot feature in Summer '26 supports arithmetic operations on currency, datetime, and numeric fields, enabling more efficient queries for use cases like identifying high-profit orders, detecting late shipments, and finding premium customers. The capability particularly benefits ISV developers and teams managing multiple customer schemas who want to keep filtering logic visible and maintainable within SOQL.
