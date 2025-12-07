# CBDT Framework Calculator

**Consumer-Driven Black Market Displacement Framework: Interactive Policy Analysis Tool**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Research](https://img.shields.io/badge/research-Harvard_Dataverse-red)](https://dataverse.harvard.edu/)

## Overview

The CBDT Framework Calculator is an interactive web-based tool for predicting legal cannabis market outcomes based on empirically validated policy levers. This framework achieves **5% mean absolute error** across 24 U.S. cannabis markets.

**Live Demo:** [https://dankreports.github.io/cbdt-calculator/](https://dankreports.github.io/cbdt-calculator/)

## What is the CBDT Framework?

The **Consumer-Driven Black Market Displacement (CBDT) Framework** is a predictive model that forecasts legal cannabis market share based on five policy levers:

1. **Price Gap** - Legal vs. black market price differential
2. **Access Density** - Dispensaries per 100,000 residents  
3. **Safety/Quality Premium** - Regulatory advantages (testing, labeling)
4. **Convenience Factor** - Hours, delivery, payment options
5. **Enforcement Intensity** - Black market prosecution efforts

## Validation & Research

- **Mean Absolute Error:** 5% across 24 U.S. markets
- **Dataset:** Published via [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MDVDTQ)
- **Methodology:** Peer-reviewed research available at [dankreports.com](https://www.dankreports.com)
- **Author:** Daniel Kief

## Features

- ✅ Real-time market share predictions
- ✅ Interactive policy lever adjustments
- ✅ State-by-state analysis dropdown (50 states)
- ✅ Direct links to comprehensive state analyses
- ✅ Policy recommendations based on inputs
- ✅ Mobile-responsive design
- ✅ No dependencies - runs entirely in browser
- ✅ Educational tooltips and context

## Use Cases

### For Policymakers
- Model the impact of tax changes on legal market capture
- Evaluate licensing density requirements
- Assess enforcement strategy effectiveness
- Compare policy scenarios before implementation

### For Researchers
- Validate hypotheses about market dynamics
- Explore policy lever interactions
- Generate predictions for academic analysis
- Access validated coefficients

### For Industry Analysts
- Forecast market maturity timelines
- Evaluate competitive positioning
- Assess regulatory risk factors
- Model market entry strategies

### For Investors
- Evaluate state market potential
- Assess policy risk in MSO analysis
- Model total addressable market expansion
- Compare regulatory environments

## Quick Start

### View Online
Visit: [https://dankreports.github.io/cbdt-calculator/](https://dankreports.github.io/cbdt-calculator/)

### Run Locally
```bash
# Clone the repository
git clone https://github.com/DanKReports/cbdt-calculator.git

# Open in browser
cd cbdt-calculator
open cbdt-calculator.html
```

### Deploy to Your Own GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch as source
4. Access at `https://[your-username].github.io/cbdt-calculator/`

## How It Works

The calculator implements the validated CBDT formula:

```
Market Share = Base + (Price Impact) + (Access Impact) + 
               (Safety Impact) + (Convenience Impact) + 
               (Enforcement Impact)
```

Where:
- **Price Impact** = -0.35 × Price Gap (most significant factor)
- **Access Impact** = +1.8 × Dispensaries per 100K
- **Safety Impact** = +0.15 × Safety Premium %
- **Convenience Impact** = +0.12 × Convenience Factor %
- **Enforcement Impact** = +0.08 × Enforcement Intensity %

Results are capped between 0-100% market share.

## Real-World Examples

The calculator includes validated examples from actual markets:

- **Colorado:** 75% legal share (mature market, competitive pricing)
- **Michigan:** 60% legal share (good access, moderate price gap)
- **California:** 45% legal share (high taxes, access limitations)
- **New York:** 20% legal share (limited licenses, price disadvantage)

## Technical Details

- **Technology:** Pure HTML/CSS/JavaScript (no dependencies)
- **Compatibility:** All modern browsers
- **Mobile:** Fully responsive design
- **Performance:** <50KB total page weight
- **Accessibility:** WCAG 2.1 AA compliant

## Research Foundation

This calculator is based on comprehensive state-by-state cannabis policy analysis:

- **Dataset:** 24 U.S. legal cannabis markets (2018-2024)
- **Variables:** 50+ policy and market metrics per state
- **Validation:** Cross-validated predictions vs. actual outcomes
- **Publication:** Harvard Dataverse + SSRN working paper

**Full Research:** [dankreports.com](https://www.dankreports.com)

## Key Findings

1. **Price is paramount:** Price gap accounts for ~40% of market share variance
2. **Access matters:** Each additional dispensary per 100K increases legal share ~1.8%
3. **Quality compounds:** Safety/testing standards provide sustained competitive advantage
4. **Convenience counts:** Delivery and hours significantly impact consumer choice
5. **Enforcement enables:** Black market prosecution amplifies other policy effects

## Policy Implications

### For High-Tax States (CA, IL, WA)
- Reduce excise taxes to close price gap
- Increase license density to improve access
- Maintain quality standards as differentiator

### For Limited-License States (NY, NJ, CT)  
- Expand licensing to increase access
- Prevent price gaps before they form
- Prioritize enforcement during buildup

### For Mature Markets (CO, OR, NV)
- Maintain competitive pricing
- Focus on quality and convenience
- Monitor market saturation

## Contributing

Contributions welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add improvement'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open a Pull Request

## Citation

If you use this calculator or framework in research, please cite:

```
Kief, Daniel. (2025). Consumer-Driven Black Market Displacement (CBDT) 
Framework: A Validated Predictive Model for Cannabis Market Outcomes. 
Harvard Dataverse. https://doi.org/10.7910/DVN/MDVDTQ
```

## License

MIT License - see [LICENSE](LICENSE) file for details.

## About the Author

**Daniel Kief** is a cannabis policy analyst with 25 years of market experience. The CBDT Framework represents the synthesis of empirical research, statistical modeling, and real-world market observation.

**Website:** [dankreports.com](https://www.dankreports.com)  
**Email:** [danielkreports@gmail.com](mailto:danielkreports@gmail.com)  
**Research:** State-by-state cannabis policy analysis and federal reform advocacy

## Acknowledgments

- Harvard Dataverse for dataset hosting
- State regulatory agencies for public data
- Cannabis industry participants for ground-truth validation

- **Cannabis Consumption Research:** [Consumption Baseline Study](https://www.dankreports.com/cannabis-consumption-phantom-demand)
- **Research Datasets:** [Harvard Dataverse](https://dataverse.harvard.edu/)
