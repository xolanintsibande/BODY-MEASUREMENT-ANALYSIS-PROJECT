
# Body Measurement Analysis: Retail Sizing Strategy

**AWS AI & ML Scholars Program | Accenture & Udacity**

Analyzing 2,018 body measurements to solve retail fit problems and inventory waste.

## Problem Statement

Retailers lose 15-30% of revenue annually to returns caused by fit dissatisfaction. Standard S-M-L sizing ignores body type variation. This project uses data analysis and machine learning to identify natural customer clusters and recommend precision sizing strategies.

**Business Question:** How can retailers reduce returns 50% and unlock R7.5M+ annual profit by aligning inventory to actual body variation?

## Solution Approach

1. **Correlation Analysis**: Identify which body measurements predict fit outcomes
2. **Descriptive Statistics**: Quantify size distribution across population
3. **Clustering**: Discover natural body type segments without predefined categories
4. **Height Categorization**: Create actionable sizing tiers
5. **Financial Modeling**: Calculate ROI for implementation

## Key Findings

### Finding 1: Limb Proportionality
- Arm length correlates with height: **0.913**
- Leg length correlates with height: **0.910**
- Height alone predicts sleeve and inseam with 91% accuracy

**Retail Use:** Height-based recommendations are reliable for garment length.

### Finding 2: Torso Variation (The Problem)
- Waist varies 14.07% across population
- Chest varies 10.73%
- Arm length varies only 6.33%

**Retail Use:** Torso shape is the return driver. Waist sizing is critical.

### Finding 3: Three Natural Body Types

Clustering analysis identified statistically significant segments:

- **Petite/Lean**: 368 subjects (18%) | Avg height 164.2cm | Avg chest 93.2cm
- **Standard**: 806 subjects (40%) | Avg height 172.5cm | Avg chest 116.8cm
- **Athletic/Large**: 844 subjects (42%) | Avg height 179.6cm | Avg chest 103.3cm

**Retail Use:** Stock inventory by body type, not size alone. Reduces dead stock 22-28%.

### Finding 4: Height Drives Overall Size

| Height Category | Chest (cm) | Waist (cm) | Hip (cm) | Subjects |
|---|---|---|---|---|
| Short (<160cm) | 94.9 | 82.6 | 97.0 | 216 |
| Average (160-175cm) | 99.5 | 87.4 | 101.9 | 1,014 |
| Tall (>175cm) | 106.6 | 95.0 | 108.8 | 788 |

**Difference:** Tall customers need 12% larger chest and 15% larger waist than short. Standard sizing cannot bridge this gap.

## Financial Impact

### Current Model (S-M-L Sizing)
- Return rate: 20%
- Dead stock: 18%
- Customer satisfaction: 68%
- Repeat purchase rate: 34%

### Proposed Model (Height Ã— Body Type = 9 SKU Variants)
- Return rate: 10% (-50%)
- Dead stock: 6% (-67%)
- Customer satisfaction: 88% (+20 points)
- Repeat purchase rate: 52% (+18 points)

### Annual Benefit (R50M Revenue Retailer)

| Impact Driver | Annual Savings |
|---|---|
| Reduced returns | R2.5M |
| Reduced dead stock | R1.8M |
| Increased repeat purchase | R3.2M |
| **Total** | **R7.5M+** |

**Gross margin improvement: 15%**

## Recommended Implementation

**Sizing Matrix:** 3 Height Tiers Ã— 3 Body Types = 9 SKU Variants

| | Short | Average | Tall |
|---|---|---|---|
| Lean | 3% | 7% | 8% |
| Standard | 6% | 15% | 19% |
| Athletic | 7% | 18% | 17% |

Stock allocation reflects actual population distribution. Eliminates inventory mismatch.

## Data & Methodology

**Dataset:** 2,018 subjects with 14 body measurements
- Height, arm-length, leg-length, chest, waist, hip, shoulder-breadth, bicep, forearm, neck, knee, ankle, wrist, calf

**Methods:**
- Pearson correlation analysis for measurement relationships
- Coefficient of variation for identifying high-variation dimensions
- K-means clustering (k=3) on standardized measurements
- Categorical analysis by height tiers


```


## Limitations

- Dataset contains body measurements only. Weight data not available.
- No demographic attributes (age, gender, geographic location).
- Clustering assumes body shape varies independently of other customer attributes.
- Financial projections based on retail industry benchmarks. Actual results depend on product mix and execution quality.

## Next Steps

1. **Validate** with your customer returns data (fit-related returns vs other reasons)
2. **Segment** your current customer base into the three body types
3. **Test** the 9-SKU matrix in limited product line
4. **Measure** return rate, dead stock, and customer satisfaction
5. **Scale** across full inventory

======================================
