# Embroker GraphQL Schema

## Overview

Embroker is a San Francisco-based digital business insurance broker and insurtech platform that enables businesses to compare, quote, purchase, and manage commercial insurance policies. This conceptual GraphQL schema models the core domain of Embroker's commercial insurance platform, covering policies, quotes, applications, claims, agents, brokers, and the risk assessment infrastructure that powers Embroker One.

Embroker serves funded startups, tech companies, law firms, venture capital and private equity firms, financial services professionals, consultants, real estate agents, and small businesses with coverage types including Business Owners Policy (BOP), commercial general liability, professional liability, technology E&O, cyber insurance, D&O, EPLI, commercial crime, key person, workers compensation, and lawyers professional liability.

## Schema Design

The schema is organized around the following primary domain areas:

- **Policies** — active insurance contracts with coverage details, limits, deductibles, and endorsements
- **Quotes** — pricing and coverage proposals generated from applications
- **Applications** — structured intake of business information including risk factors and exposures
- **Businesses** — the insured entities with industry classification, revenue, employees, and locations
- **Claims** — loss events reported against active policies with reserves and status tracking
- **Agents and Brokers** — distribution channel participants and their commission structures
- **Insurers and Carriers** — underwriting entities and the markets they serve
- **Authentication** — API keys, tokens, and webhook event delivery

## Source

- Provider: Embroker
- Website: https://www.embroker.com
- Platform: https://app.embroker.com
- Broker Access: https://access.embroker.com
- Schema Type: Conceptual (no public API documented)
- Schema File: embroker-schema.graphql
