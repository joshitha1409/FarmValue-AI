# 📚 FarmValue AI – Research References & Data Sources

## 1. Introduction

FarmValue AI proposes an agricultural market intelligence platform that uses market-price information, buyer requirements and logistics estimates to support informed selling decisions.

The following resources have been identified as potential research and data sources for the proposed system.

## 2. Agricultural Market Data Sources

### A. AGMARKNET – Government Mandi Price Data

**Source:** Government of India – Open Government Data Platform

**Link:** https://www.data.gov.in/catalog/current-daily-price-various-commodities-various-markets-mandi

**Relevance to FarmValue AI:**
- Daily wholesale minimum, maximum and modal prices.
- Commodity-wise and market-wise price information.
- Useful for historical price analysis and market comparisons.
- Potential input for the Market Intelligence Agent.

**Proposed application:** Analyse available commodity prices across different mandis to identify potentially favourable selling opportunities.

### B. CEDA Agri-Market Data Portal

**Source:** Centre for Economic Data and Analysis (CEDA), Ashoka University

**Link:** https://agmarknet.ceda.ashoka.edu.in/

**Relevance to FarmValue AI:**
- Agricultural commodity prices and quantity arrivals.
- Historical market information across Indian mandis.
- Useful for studying price movements and market trends.
- Supports research and exploration of agricultural market data.

**Proposed application:** Explore historical price and arrival patterns to support market analysis.

### C. CEDA Data Portal API

**Documentation:** https://api.ceda.ashoka.edu.in/documentation/

**Relevance to FarmValue AI:**
- Provides documented API endpoints for Agmarknet data.
- Includes commodity and geographical information.
- Provides endpoints for market prices and quantities.

**Proposed application:** Investigate programmatic data retrieval for the Market Intelligence Agent, subject to API access, usage conditions and validation.

## 3. Agricultural Market Ecosystem References

### D. e-NAM – National Agriculture Market

**Source:** Government of India

**Link:** https://www.enam.gov.in/web/

**Relevance to FarmValue AI:**
- Provides a national electronic agricultural trading platform.
- Connects participating APMC mandis.
- Supports agricultural market access and price discovery.
- Provides useful context for understanding buyers, sellers and agricultural trading.

**Proposed application:** Study existing agricultural trading workflows and explore potential integration opportunities, subject to access and permissions.

## 4. Mapping Research Sources to FarmValue AI Agents

| Agent | Relevant Research Source |
|---|---|
| Market Intelligence | AGMARKNET, CEDA |
| Buyer Discovery | e-NAM ecosystem and future verified buyer information |
| Logistics Estimation | Location and transportation information to be evaluated |
| Recommendation | Combined outputs of all four agents |

## 5. Data Considerations and Limitations

- Historical market prices do not guarantee future selling prices.
- Market data availability and reporting frequency may vary.
- Buyer requirements and availability need independent validation.
- Transportation costs require suitable distance and cost information.
- Predictions and recommendations must communicate uncertainty.
- External API access and integration permissions must be verified before implementation.

## 6. Research Objective

These references provide a starting point for developing and validating FarmValue AI's proposed market intelligence and agricultural decision-support capabilities.

The project aims to combine available market information with buyer matching and logistics estimation to provide more meaningful selling recommendations.

---

**FarmValue AI – AI informs; farmers make the final call.**

*Research status: Initial source identification for the proposed CJ100 project. Listing a source does not imply an established partnership or completed integration.*
