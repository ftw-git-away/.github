# GitAway

**FTW Data Engineering Capstone, Batch 12 (LT3)**

We are five data engineering learners from For The Women (FTW) Foundation: Cole, Nella, Cha, Gab, and Haze.

## Our project: ProvInsights

**ProvInsights is a Philippine province-level tourism, recovery and economic analytics project.** It was built for a fictional client, the Tourism-Economy Convergence Task Force (TECTF), which asks whether tourism growth is reaching beyond the usual strong destinations.

It answers two business questions:

1. **Which provinces stand out in tourism activity and recovery, and which appear to be lagging?**
2. **How are changes in tourism associated with changes in local tourism-related economic activity?**

We bring together Department of Tourism (DOT), Philippine Statistics Authority (PSA) and Philippine Standard Geographic Code (PSGC) data. We compare 2022 and 2023 against a 2019 baseline.

> Tourism activity means reported overnight travelers. Findings support descriptive comparisons and further investigation, not causal or investment-return claims.

## How it is built

Source files → Bronze → Silver → Gold → Analytics → Dashboard, running as a Databricks job with data-quality checks at every layer, and CI/CD through GitHub Actions.

## Repository

| Repository | What is in it |
| --- | --- |
| [provinsights-ph-tourism](https://github.com/ftw-git-away/provinsights-ph-tourism) | Pipeline notebooks, Databricks job, documentation, decision log, dashboard |

Start with the repository README, then the [business and analytical questions](https://github.com/ftw-git-away/provinsights-ph-tourism/blob/main/docs/business-and-analytical-questions.md).
