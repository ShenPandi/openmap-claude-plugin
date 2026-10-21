# OpenMap plugin for Claude

Find local services and look up UK companies with [OpenMap](https://openmap.ai).

## What it adds
- **The OpenMap connector** (`https://openmap.ai/api/mcp`): read-only and public, with no sign-in. Its tools are:
  - search local services;
  - get a service;
  - search UK companies (Companies House);
  - get a UK company.
- **The skill "Find UK local help"**: tells Claude when and how to use OpenMap, with safety checks (Gas Safe, NICEIC, DBS) and honest labelling of results not on OpenMap.

## Install
In Claude, open Customize → Plugins → Add from a marketplace, and enter this repository.

## Privacy
The tools receive only the words and area you search for. See https://openmap.ai/privacy.

Built by OpenMap.AI LTD (company number 17493031), Clubhouse Holborn, 20 St Andrew Street, London EC4A 3AG. Support: support@openmap.ai
