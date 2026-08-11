# Daily Intelligence Automation Blueprint

## Collection
RSS reader: Inoreader preferred.

## Processing stages
1. Collect new items from the 12 RSS folders.
2. Deduplicate and filter using `19_RSS_INTELLIGENCE/filters.md`.
3. Classify into Strategy, Enterprise, Transformation, Operations, Agents, Governance, Responsible AI, Security, Regulation, Research, Industry, Market.
4. Rank by enterprise relevance, source quality, freshness, novelty, and actionability.
5. Generate the daily brief from `90_TEMPLATES/daily-intelligence.md`.
6. Store the final brief under `20_DAILY_INTELLIGENCE/daily/`.
7. Promote durable insights into the relevant AI Leadership OS folder.
8. Generate candidate LinkedIn ideas only from evidence-backed insights.

## Recommended automation stack

- RSS collection: Inoreader or Feedly
- Workflow orchestration: n8n or Zapier
- LLM analysis: your preferred enterprise-safe model/API
- Knowledge store: this GitHub repository
- Optional delivery: email, Slack, Teams, or scheduled ChatGPT task

## Human-in-the-loop gates

Do not automatically publish or treat generated analysis as authoritative. Rahul reviews:

- Strategic conclusions
- Regulatory interpretations
- Architecture recommendations
- Governance/control decisions
- Public thought-leadership content

## Target operating cost

Daily human effort: 15–30 minutes.
Weekly review: 45–60 minutes.
Monthly review: 60–90 minutes.
