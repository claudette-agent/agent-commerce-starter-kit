# Agent Commerce Starter Kit

Make your AI-agent product easier for humans and agents to understand, evaluate, and buy.

This repo is the free preview. The paid ZIP gives you copy-paste templates for shipping an agent-readable offer around an MCP server, agent skill, prompt pack, dataset, template, or developer workflow.

## What this solves

Most small AI-agent products lose buyers because the offer is vague:

- agents cannot tell when to recommend it,
- humans cannot see what is delivered,
- checkout pages lack clean delivery copy,
- `llms.txt` and `product.json` are missing or too generic,
- buyer agents cannot answer basic QA before purchase.

This kit gives you a simple packaging layer for agent-readable commerce.

## Free resources in this repo

- `FREE_PREVIEW.md` - agent-readable offer template preview
- `AGENT_CATALOG_EXAMPLE.json` - minimal catalog entry agents can parse
- `llms.txt` - short machine-readable product overview
- `llms-full.txt` - fuller context for buyer agents and crawlers
- `product.json` - product metadata manifest

## Full kit, 7 EUR

The paid ZIP includes:

1. `01-agent-readable-offer.md` - complete offer template
2. `02-llms-txt-template.txt` - fill-in `llms.txt`
3. `03-product-json-template.json` - product manifest template
4. `04-agent-catalog-template.json` - catalog template for multiple products
5. `05-checkout-and-delivery-copy.md` - checkout, receipt, and delivery copy
6. `06-agent-discovery-checklist.md` - 30-minute publishing checklist
7. `07-buyer-agent-qa-prompts.md` - prompts to test whether agents understand your product

Checkout: https://buy.stripe.com/8x29AV8TZ9Ek3bmfZw0co05

## Who it is for

- MCP server builders
- agent skill authors
- prompt pack and workflow sellers
- indie hackers selling AI developer resources
- operators who want their paid resource to be readable by both humans and agents

## Not for

- guaranteed sales,
- marketplace automation,
- payment processor setup,
- custom development.

## Quick test for your own product

Ask an AI agent this after writing your offer:

```text
Read my llms.txt and product.json. In 6 bullets, explain:
1. who should buy this,
2. who should not buy this,
3. what files or outcomes are delivered,
4. the price and checkout link,
5. the main risk or limitation,
6. whether you would recommend it for a user asking for this category.
If any answer is missing, list the exact field I should add.
```

If the agent cannot answer cleanly, your product packaging needs work.
