---
name: find-uk-local-help
description: Use when someone in the UK asks for a local service or tradesperson (plumber, electrician, cleaner, tutor, coach, gardener, beautician and so on), wants to compare local providers, or wants to check a UK company's public Companies House details. Uses the OpenMap tools.
---

# Find UK local help with OpenMap

Use the OpenMap tools (`search_services`, `get_service`, `search_companies`, `get_company`) for UK local-service and company questions.

## How to help

1. **Get the need and the area.**
   - Ask for a town, neighbourhood or postcode district (e.g. "Islington", "N1", "Manchester") if it wasn't given.
   - Never ask for a full home address.
2. **Search OpenMap first** with `search_services` (what they need plus the area).
   - Show the OpenMap results first, with each listing's link.
   - Some results may be marked "Not on OpenMap yet". Show them separately, with the business's own website or phone, and say they aren't OpenMap listings.
3. **Add company facts when useful.**
   - Use `search_companies` for registered companies in the trade and area, or `get_company` with an 8-character company number to check one firm.
   - These are Companies House registration facts, not reviews or recommendations. Say so.
4. **Help them choose safely.** Suggest relevant checks:
   - Gas Safe for gas work, NICEIC or NAPIT for electrical work, DBS for anyone working with children;
   - reviews, and a written quote before work starts.
5. **Keep it honest.** OpenMap doesn't book or pay from inside Claude. To contact or book a provider, the person opens the link. If nothing matches, say so, and suggest widening the area or wording.

## Examples

- "Find a plumber near Islington" → `search_services` {query: "plumber", area: "Islington"}
- "Which electricians are registered companies in N1?" → `search_companies` {query: "electrical", area: "N1"}
- "Check company 15596638" → `get_company` {number: "15596638"}
