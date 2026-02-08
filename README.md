# ESG Environmental Scores: Signals vs Substance
This project examines whether improvements in ESG Environmental scores reflect genuine environmental performance or are driven by disclosure effects. Using firm-level panel data, ESG score changes are analyzed alongside carbon intensity dynamics while controlling for industry and time effects. The focus is on interpretability and economic reasoning rather than complex black-box models.

## Research Questions
1. Do changes in ESG scores matter more than absolute levels?
2. Are ESG improvements aligned with reductions in carbon intensity?
3. How much of ESG movement is explained by observable environmental and financial factors?
4. Can unexplained ESG improvements indicate potential greenwashing?
5. Does this behavior differ across industries?

## Data & Feature Construction
Key features include:
1. Lagged ESG Environmental scores
2. Log-compressed carbon intensity shocks
3. Industry- and year-adjusted ESG and carbon changes
4. Carbon consistency and volatility measures
5. Basic financial controls and industry dummies
Industry heterogeneity is addressed through both adjusted variables and dummy controls.

## Methodology
1. EDA grounded in economic intuition to study ESG dynamics and industry differences
2. Elastic Net regression to predict ESG Environmental score changes
3. Residual-based greenwashing flag for firms with ESG improvements unexplained by carbon performance
4. Robustness checks, including out-of-industry testing and feature stress tests

## Key Insights
1. ESG changes show persistence and mean reversion.
2. Carbon dynamics are highly skewed and industry-specific.
3. Carbon features materially improve model performance.
4. Potential greenwashing flags cluster in carbon-intensive industries.

## Notes
Greenwashing indicators are suggestive rather than causal proof. The project is intended as an applied ESG analytics exercise for sustainability and climate-focused data science roles.
