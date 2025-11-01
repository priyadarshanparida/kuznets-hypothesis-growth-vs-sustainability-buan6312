# Research Proposal: Economic Growth and Sustainability

### Research Question

Do countries’ economic growth and structural change explain variation in carbon dioxide emissions per capita? Does an increase in GDP per capita result in higher level of emissions?

### Motivation

While rapid industrial expansion and urbanization have boosted the global economy, they have introduced significant sustainability risks. Furthermore, as emerging factors like Digital and AI waste pose unprecedented risks, finding the balance between growth and sustainability is central to today’s economic policy debate. The subject of this research links macroeconomic performance and environmental outcomes while associating structural shifts for explainability.

### Background and Existing Findings

Simon Kuznets researched the relationship between a nation’s growth and its environmental effect, popularly known as the Environmental Kuznets Curve (EKC). Numerous studies in Environmental Economics have established an inverted-U relationship between GDP and emissions. However, results can vary depending on the class of pollutants, time periods, and country groups. Recent studies suggest that structural variables and energy composition may alter the growth-emission relationship, hence the scope for an updated assessment.

### Proposed Contribution

Many early analyses relied on limited cross-sections and omitted emerging, relevant factors such as renewable energy adoption or changing energy mixes. This research will extend the EKC framework by incorporating both structural and energy-mix variables. In addition to GDP per capita, the model will also include energy use, trade volume, urbanization, renewable energy share, fossil fuel consumption, industrial value added, and population density, and test the validity of the Kuznets hypothesis once these contemporary factors are accounted for. By accounting for these emerging factors and recent data in the analysis, the research findings aim to contribute to the broader discussion on sustainable growth and environmental policy design.

### Data Plan

We plan to assemble a balanced panel from the World Bank’s World Development Indicators database for all available countries between 2000 and 2022. The dataset will combine measures of CO₂ emissions, GDP per capita, trade, industrial value added (as a percentage of GDP), energy use, shares of renewable and fossil-fuel energy, urban population, and population density.

### Hypothesis and Econometric Model

We hypothesize CO₂ emissions per capita to initially rise with income and later decline as economies diversify and adopt cleaner energy sources – a pattern consistent with the Environmental Kuznets Curve. The economic research will estimate a linear model including income and emissions to capture the EKC shape. Panel fixed-effects estimation will be used to control for unobserved, time-invariant country characteristics.

$ln(CO_{2it}) = β_0  + β_1ln(GDP_{it}) + β_2ln(GDP_{it})^2  + β_3ln(Energy_{it}) + β_4ln(Urban_{it}) + β_5ln(Trade_{it}) + β_6Renewable_{it} + β_7FossilFuel_{it} + β_8ln(PopulationDensity_{it}) + μ_i  + ν_t + u_{it}$
