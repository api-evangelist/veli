# Veli (veli)
Veli provides crypto investment strategies via API, enabling platforms to offer smart investment solutions while handling running investment strategies, buying, selling, rebalancing, and fee collection behind the scenes. Partners retain custody and execution while Veli manages the strategy logic.

**URL:** [https://veli.io/](https://veli.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/crypto-investment?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Crypto, DeFi, Finance, Investment, Portfolio Management

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## APIs

### Veli API
The Veli API enables financial platforms and crypto exchanges to integrate automated investment strategies for their users. Partners keep custody and execution while Veli handles the strategy engine: portfolio creation, automated rebalancing, buy/sell execution signals, fee collection, and performance reporting. Supports index-based, theme-based, and custom strategy portfolios.

**Human URL:** [https://veli.io/](https://veli.io/)

#### Tags:

 - Crypto, DeFi, Finance, Investment, Portfolio Management

#### Properties

- [Documentation](https://veli.io/)
- [Portal](https://veli.io/)
- [OpenAPI](openapi/veli-openapi.yml)
- [JSONSchema - Portfolio Schema](json-schema/veli-portfolio-schema.json)
- [JSONSchema - Strategy Schema](json-schema/veli-strategy-schema.json)
- [JSONSchema - Position Schema](json-schema/veli-position-schema.json)
- [JSONSchema - Order Schema](json-schema/veli-order-schema.json)
- [JSONSchema - Asset Allocation Schema](json-schema/veli-asset-allocation-schema.json)
- [JSONSchema - Performance Response Schema](json-schema/veli-performance-response-schema.json)
- [JSONSchema - Create Portfolio Request Schema](json-schema/veli-create-portfolio-request-schema.json)
- [JSONStructure - Portfolio Structure](json-structure/veli-portfolio-structure.json)
- [JSONStructure - Strategy Structure](json-structure/veli-strategy-structure.json)
- [JSONStructure - Position Structure](json-structure/veli-position-structure.json)
- [JSONStructure - Order Structure](json-structure/veli-order-structure.json)
- [JSONStructure - Asset Allocation Structure](json-structure/veli-asset-allocation-structure.json)
- [JSONStructure - Performance Response Structure](json-structure/veli-performance-response-structure.json)
- [JSONStructure - Create Portfolio Request Structure](json-structure/veli-create-portfolio-request-structure.json)
- [Example - Portfolio Example](examples/veli-portfolio-example.json)
- [Example - Strategy Example](examples/veli-strategy-example.json)
- [Example - Position Example](examples/veli-position-example.json)
- [Example - Order Example](examples/veli-order-example.json)
- [Example - Asset Allocation Example](examples/veli-asset-allocation-example.json)
- [Example - Performance Response Example](examples/veli-performance-response-example.json)
- [Example - Create Portfolio Request Example](examples/veli-create-portfolio-request-example.json)

## Common Properties

- [Website](https://veli.io/)
- [Portal](https://veli.io/)
- [Documentation](https://veli.io/)
- [SpectralRules - Veli API Spectral Rules](rules/veli-spectral-rules.yml)
- [Vocabulary - Veli Vocabulary](vocabulary/veli-vocabulary.yml)
- [NaftikoCapability - Crypto Investment](capabilities/crypto-investment.yaml)

## Features

| Name | Description |
|------|-------------|
| Automated Investment Strategies | Deploy pre-built or custom crypto investment strategies including index tracking, theme portfolios, and algorithmic rebalancing. |
| Portfolio Rebalancing | Automatic portfolio rebalancing to maintain target allocations as market prices shift, with configurable rebalancing thresholds. |
| Partner Custody | Partners retain full custody and execution of assets while Veli provides the strategy logic, signals, and portfolio management. |
| Fee Collection | Built-in fee management for partner platforms to charge management fees on invested assets with automated collection workflows. |
| Performance Reporting | Portfolio performance metrics, returns, allocation breakdowns, and transaction history for investor reporting and dashboards. |

## Use Cases

| Name | Description |
|------|-------------|
| Crypto Exchange Investment Products | Exchanges integrate Veli to offer automated investment portfolios (crypto index funds, theme portfolios) to their retail user base. |
| Neobank Wealth Features | Neobanks and fintech apps add crypto investment strategy features powered by Veli while maintaining regulatory compliance and custody. |
| Robo-Advisor for Crypto | Build automated crypto wealth management products with goal-based portfolio construction, risk profiling, and rebalancing automation. |
| White-Label Investment Platform | Launch branded crypto investment products using Veli's strategy engine without building portfolio management infrastructure. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Veli API](openapi/veli-openapi.yml)

### JSON Schema

- [veli-asset-allocation-schema.json](json-schema/veli-asset-allocation-schema.json)
- [veli-create-portfolio-request-schema.json](json-schema/veli-create-portfolio-request-schema.json)
- [veli-order-schema.json](json-schema/veli-order-schema.json)
- [veli-performance-response-schema.json](json-schema/veli-performance-response-schema.json)
- [veli-portfolio-schema.json](json-schema/veli-portfolio-schema.json)
- [veli-position-schema.json](json-schema/veli-position-schema.json)
- [veli-strategy-schema.json](json-schema/veli-strategy-schema.json)

### JSON Structure

- [veli-asset-allocation-structure.json](json-structure/veli-asset-allocation-structure.json)
- [veli-create-portfolio-request-structure.json](json-structure/veli-create-portfolio-request-structure.json)
- [veli-order-structure.json](json-structure/veli-order-structure.json)
- [veli-performance-response-structure.json](json-structure/veli-performance-response-structure.json)
- [veli-portfolio-structure.json](json-structure/veli-portfolio-structure.json)
- [veli-position-structure.json](json-structure/veli-position-structure.json)
- [veli-strategy-structure.json](json-structure/veli-strategy-structure.json)

### Examples

- [veli-asset-allocation-example.json](examples/veli-asset-allocation-example.json)
- [veli-create-portfolio-request-example.json](examples/veli-create-portfolio-request-example.json)
- [veli-order-example.json](examples/veli-order-example.json)
- [veli-performance-response-example.json](examples/veli-performance-response-example.json)
- [veli-portfolio-example.json](examples/veli-portfolio-example.json)
- [veli-position-example.json](examples/veli-position-example.json)
- [veli-strategy-example.json](examples/veli-strategy-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Veli API](capabilities/shared/veli.yaml) — 9 operations for strategy listing, strategy detail, portfolio management, positions, rebalancing, and performance

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Crypto Investment](capabilities/crypto-investment.yaml) | veli | 8 | Fintech Platform Developer, End Investor, Portfolio Manager |

## Vocabulary

- [Veli Vocabulary](vocabulary/veli-vocabulary.yml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflow, and 3 personas across strategy discovery, portfolio management, and performance reporting dimensions

## Rules

- [Veli API Spectral Rules](rules/veli-spectral-rules.yml) — 32 rules across 10 categories enforcing Veli API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
