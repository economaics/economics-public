# The Scout — Skill Card

**Agent:** The Scout
**System:** The Transport Brain (economAIcs)
**Role:** Continuous Signal Intelligence

## One-line

Continuous monitoring of Find a Tender and Contracts Finder for UK transport opportunities, scored against the client's ICP before a human looks at it.

## What it does

The Scout consumes the public OCDS feeds from Find a Tender and Contracts Finder, filters against transport CPV codes 60000000 to 63700000, scores every notice against the client's Ideal Client Profile, and ranks by evidence-backed bid-strength with stated error bars. Prior Information Notice monitoring surfaces opportunities 90 or more days before formal release.

## Inputs

- Client ICP profile (sector, region, contract value range)
- Find a Tender OCDS feed (live)
- Contracts Finder OCDS feed (live)
- Historical authority and competitor data

## Outputs

- Ranked pipeline of qualified opportunities
- Early-signal alerts from PIN monitoring
- Procurement Act 2023 alignment flag per tender
- Bid-strength score with stated error bars on every notice before human review

## Compliance properties

- Public OCDS data only
- Audit-grade by default
- No private or scraped sources

## Best for

Any UK public transport organisation that needs to see opportunities earlier than its competitors and score them before committing bid resource.

## Public URL

https://economaicsgroup.com/agents#scout

## Pricing surface

Included in Brain Deployment monthly operate fee. See `/pricing#brain-deployment`.

## Tags

`tender-monitoring` · `OCDS` · `PIN` · `CPV` · `bid-strength` · `Procurement-Act-2023` · `Find-a-Tender` · `Contracts-Finder`
