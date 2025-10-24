# Real Estate Pricing Analysis: Factors Influencing Home Sale Prices

## Project Overview
Comprehensive statistical analysis of 522 home sales in a Midwestern city to identify key factors influencing property values. This applied linear models project demonstrates advanced regression techniques, model selection, and interaction analysis in real estate analytics.

### Research Questions
1. Does architectural style significantly impact home sale prices?
2. How does construction quality affect property values?
3. What other factors (home size, location, amenities) drive pricing decisions?

## Key Findings
- **Construction Quality** explains 66% of price variability (F=503.87, p<0.0001)
- **Architectural Style** accounts for 17.4% of price differences (F=11.99, p<0.0001)
- **Quality-Style Interaction** significantly impacts prices (p=0.0002)
- **Final Model** explains 84.6% of price variance using stepwise selection

## Statistical Methods

### Analysis Techniques
1. **Descriptive Statistics**: Data exploration and variable distribution analysis
2. **One-Way ANOVA**: Testing style and quality effects on sale prices
3. **Two-Way ANOVA**: Joint effects of style × quality interactions
4. **Multiple Linear Regression**: Comprehensive modeling with interaction terms
5. **Stepwise Selection**: AIC-based model refinement (optimal at Step 6)

### Key Models
- **Initial Model**: R² = 0.848 with all predictors and interactions
- **Refined Model**: R² = 0.846 with significant terms only
- **Final Model**: Parsimonious selection via stepwise procedure

## Significant Predictors


### Categorical Variables
- **Quality Level 1**: +$149,409 vs lower quality (p < 0.0001)
- **Highway Proximity**: -$35,088 for adjacent homes (p = 0.0417)
- **Style 1 × Quality 1**: +$277,312 interaction effect

## Key Insights

### For Real Estate Professionals
- High-quality construction (Quality 1) commands premium prices
- Architectural styles 7, 9, and 10 show highest value potential
- Highway adjacency decreases values by approximately $35,000

### For Home Developers
- Focus on Quality 1 construction with popular styles (1, 7, 10)
- Each additional bathroom adds ~$8,500 to home value
- Newer construction years significantly increase property values

## Skills Demonstrated
- **Statistical Modeling**: ANOVA, multiple regression, interaction analysis
- **Model Selection**: Stepwise procedures, AIC criterion, parsimonious modeling
- **Data Analysis**: SAS programming, hypothesis testing, diagnostic validation
- **Business Insight**: Real estate market analysis, pricing strategy development
- **Technical Communication**: Professional reporting, result interpretation
