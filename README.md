# Economic and Environmental Life Cycle Analysis of Novel Insulation and Roofing Materials for Sustainable Livestock Shelters in Indian Arid Climates

> **Project Report | ME F366 | BITS Pilani | December 2025**  
> Thilak S · Under Prof. P. Srinivasan & S. Rahul Bharath  
> Department of Mechanical Engineering, BITS Pilani  
> `f20220771@pilani.bits-pilani.ac.in`

An integrated **Life Cycle Assessment (LCA)** and **Life Cycle Cost Analysis (LCCA)** framework evaluating innovative insulation and roofing materials — Phase Change Materials (PCMs), synthetic foams, and natural fibers — for thermally resilient dairy cattle shelters in the Hot Semi-Arid (BSh) climate of Rajasthan, India.

---

## Abstract

This study provides a comprehensive environmental and economic assessment of innovative insulation products for sustainable dairy cattle housing in the semi-arid climate of Pilani, Rajasthan. Through integration of Material Science, Climate Engineering, Life Cycle Assessment (LCA), and Life Cycle Cost Analysis (LCCA), it quantifies thermal stress mitigation strategies for high-yielding dairy cattle — a critical concern given that productivity loss begins when internal temperatures exceed 25°C.

Four primary insulation alternatives were examined over a 100 m² roof baseline: **Expanded Polystyrene (EPS)** — ₹99,250; **Polyurethane (PUR)** — ₹1,46,500; **Crop Residue** — ₹1,15,000; and **Paraffin Phase Change Material (PCM)** — ₹28,900. Projected energy savings range from 12% (Crop Residue) to 18% (PUR), translating to modest annual operational savings of ₹2,100–₹3,150 at the prevailing agricultural tariff of ₹7/kWh.

The LCA reveals the **natural material paradox**: Crop Residue carries an embodied carbon load of 8,790 kg CO₂eq — 28× greater than EPS (312.5 kg CO₂eq) — due to high-GWP synthetic binders and processing energy. EPS emerges as the least environmentally unfavorable option with the shortest carbon payback time (5–7 years). The 30-year LCCA at a 7.5% discount rate confirms financial non-viability for all options at subsidized agricultural tariffs; economic viability is only approached at commercial tariffs (₹15/kWh). A synergistic **three-layer thermal design** is proposed — reflective outer layer, exterior PCM, and interior hygroscopic insulation — to meet the 18°C–20°C summer comfort target. The study concludes that investment justification must extend beyond energy savings to include monetized productivity benefits: avoided milk yield loss, improved fertility, and reduced disease incidence.

**Keywords:** Livestock shelter design, thermal management, phase change materials, life cycle cost analysis, embodied carbon, dairy cattle welfare, arid climate, sustainability, India

---

## Motivation

Dairy cattle in the Hot Semi-Arid (BSh) climate zone of India face severe and sustained thermal stress during summer months (42°C–45°C ambient). This has cascading consequences on productivity, welfare, and farm economics — yet shelter design in Indian agriculture has remained largely conventional, without systematic thermal optimization.

**Why current shelter design approaches fall short:**

- **Uninsulated metal roofs** — no resistance to the 18–24 MJ/m² peak summer solar load; indoor temperatures closely track outdoor extremes, far exceeding the 25°C TNZ ceiling
- **Steady-state R-value optimization** — conventional insulation selection based on thermal conductivity alone ignores transient solar loading and diurnal PCM charge/discharge dynamics
- **Natural material assumptions** — crop residue and agricultural waste insulation are often assumed environmentally superior without accounting for processing energy, synthetic binder GWP, and high material density
- **Energy-only LCCA** — existing cost analyses focus solely on operational energy savings, systematically omitting the dominant financial benefit: avoidance of milk yield loss, fertility decline, and heat-stress-related disease
- **Static ventilation design** — high air exchange rates required by BIS standards conflict with the need to exclude external particulate matter (PM) during peak crop-residue burning periods (R² = 0.95 external–internal PM correlation)

This study addresses these gaps by integrating thermal physics, embodied carbon accounting, and full life cycle cost modelling into a unified decision framework applicable to arid-climate livestock infrastructure in India.

---

## Key Results

| Result | Detail |
|--------|--------|
| **Best thermal performance** | PUR foam (λ = 0.025 W/m·K), 18% projected energy savings |
| **Best economic baseline** | EPS — least negative NPV at −₹75,041 over 30 years |
| **Lowest embodied carbon** | EPS — 312.5 kg CO₂eq per 100 m² (carbon payback: 5–7 years) |
| **Worst embodied carbon** | Crop Residue — 8,790 kg CO₂eq (28× EPS) |
| **LCCA viability threshold** | Commercial electricity tariff ≥ ₹15/kWh |
| **Financial viability at ₹7/kWh** | None — all options return negative NPV over 30 years |
| **Livestock GHG context** | 50 cows emit ~58,425 kg CO₂eq/year; EPS saves ~300 kg CO₂eq/year operationally |
| **Proposed optimal design** | Three-layer system: reflective metal → exterior PCM → interior EPS/hygroscopic fiber |
| **Target indoor temperature** | 18°C–20°C during summer (TNZ upper limit: 25°C) |

---

## Site & Climate Parameters

| Parameter | Value | Source |
|-----------|-------|--------|
| Location | Pilani, Rajasthan, India | — |
| Latitude / Longitude | 27.50°N / 75.75°E | IMD |
| Elevation | 229 m | IMD |
| Köppen Classification | BSh (Hot Semi-Arid) | — |
| Average Annual Temperature | 26.2°C | IMD |
| Summer Peak Temperature | 42°C–45°C | IMD |
| Winter Temperature Range | 5°C–8°C | IMD |
| Peak Solar Radiation (Summer) | 18–24 MJ/m² | NASA POWER / Jakhar et al., 2023 |
| Peak Solar Radiation (Winter) | 6–9 MJ/m² | NASA POWER |
| Summer Relative Humidity | 45%–55% | IMD |
| Winter Relative Humidity | 35%–45% | IMD |
| Baseline Cooling Load (100 m² roof) | 2,500 kWh/year | Calculated |

---

## Material Properties & CAPEX

### Thermophysical Properties

| Material | λ (W/m·K) | ρ (kg/m³) | cₚ (J/kg·K) | Lf (kJ/kg) | Source |
|----------|-----------|-----------|------------|-----------|--------|
| EPS (50 mm) | 0.035 | 25 | 1,400 | 0 | [1] |
| PUR (50 mm) | 0.025 | 35 | 1,450 | 0 | [1] |
| Crop Residue (50 mm) | 0.08 | 120 | 1,200 | 0 | [8] |
| Sheep Wool (50 mm) | 0.045 | 18 | 1,600 | 0 | [2] |
| Paraffin PCM (20 mm) | 0.2 | 860 | 2,500 | 200 | [3] |
| Aluminum (1 mm) | 205 | 2,700 | 910 | 0 | [19] |
| Zinc (0.1 mm) | 116 | 7,140 | 388 | 0 | [19] |

### Initial Investment (100 m² Roof)

| Material | Cost/m² (₹) | Labor (₹) | Transport (₹) | Total (₹) | Source |
|----------|------------|-----------|--------------|----------|--------|
| EPS 50 mm | 850 | 100 | 42.5 | 99,250 | [8] |
| PUR 50 mm | 1,300 | 100 | 65.0 | 1,46,500 | [9] |
| Crop Residue 50 mm | 1,000 | 100 | 50.0 | 1,15,000 | [8] |
| Paraffin PCM 20 mm | 180 | 100 | 9.0 | 28,900 | [10] |

---

## Environmental LCA

### Embodied Carbon (Cradle-to-Gate, A1–A3)

| Material | GWP (kg CO₂/kg) | Energy (MJ/kg) | Density (kg/m³) | Thickness (m) | Mass (kg) | EC Total (kg CO₂) |
|----------|----------------|---------------|----------------|--------------|----------|------------------|
| EPS | 2.5 | 75 | 25 | 0.05 | 1.25 | 312.5 |
| PUR | 3.0 | 90 | 35 | 0.05 | 1.75 | 525.0 |
| Crop Residue | 14.65 | 123.83 | 120 | 0.05 | 6.00 | 8,790.0 |
| Paraffin PCM | 2.2 | 95 | 860 | 0.02 | 17.2 | 3,784.0 |
| Aluminum | 8.1 | 200 | 2,700 | 0.001 | 2.7 | 2,187.0 |
| Zinc | 1.8 | 68 | 7,140 | 0.0001 | 0.714 | 128.52 |

### Annual Livestock GHG Emissions (IPCC Tier 2, per Dairy Cow)

| Emission Source | Mass (kg/head/yr) | GWP₁₀₀ | CO₂eq (kg) |
|-----------------|------------------|---------|-----------|
| Enteric Methane (CH₄) | 32 | 28 | 896 |
| Manure Methane (CH₄) | 5 | 28 | 140 |
| Manure Nitrous Oxide (N₂O) | 0.5 | 265 | 132.5 |
| **Total** | — | — | **1,168.5** |

> For a 50-cow herd, annual livestock emissions ≈ **58,425 kg CO₂eq** — the EPS scenario's operational savings (~300 kg CO₂eq/year) represent < 0.1% of this figure. Environmental justification must therefore rest on improving animal productivity efficiency (kg CO₂eq / kg milk), not shelter operational energy alone.

---

## LCCA Framework

### Economic Parameters

| Parameter | Value | Source/Basis |
|-----------|-------|-------------|
| Project Lifespan | 30 years | [6] |
| Material Lifespan | 20 years | Industry practice |
| Discount Rate (Conservative) | 6.0% | [11] |
| Discount Rate (Baseline) | 7.5% | [11] |
| Discount Rate (Pessimistic) | 9.0% | [11] |
| Baseline Electricity Tariff | ₹7/kWh | [12] |
| Electricity Tariff Range | ₹6–₹8/kWh | DISCOM variations |
| Annual Electricity Inflation | 5.5% | [13] |
| Maintenance Rate (Foam) | 0.5%/year | Industry practice |
| Maintenance Rate (Natural) | 1.0%/year | Higher degradation |
| Transport Cost | 5% of material cost | Market estimate |
| Present Worth Factor (7.5%, 30 yr) | 11.37 | Calculated |

### Baseline LCCA Results (30-Year Lifespan, ₹7/kWh)

| Parameter | EPS 50 mm | PUR 50 mm | Crop Residue 50 mm |
|-----------|-----------|-----------|-------------------|
| Initial Investment (₹) | 99,250 | 1,46,500 | 1,15,000 |
| Energy Savings (%) | 15 | 18 | 12 |
| Annual Energy Saved (kWh) | 375 | 450 | 300 |
| Annual Energy Cost Savings (₹) | 2,625 | 3,150 | 2,100 |
| Annual Maintenance Cost (₹) | 496 | 733 | 1,150 |
| Net Annual Benefit (₹) | 2,129 | 2,417 | 950 |
| PWF @ 7.5%, 30 yr | 11.37 | 11.37 | 11.37 |
| **NPV Result (₹)** | **−75,041** | **−1,19,005** | **−1,04,201** |
| Cost-Effective? | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) |

### Sensitivity Analysis: NPV Under Varying Conditions (EPS)

| Scenario | Net Benefit (₹) | NPV (₹) | Viable? |
|----------|----------------|---------|---------|
| EPS @ 6% discount | 2,200 | −68,122 | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) |
| EPS @ 7.5% discount (baseline) | 2,200 | −74,256 | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) |
| EPS @ 9% discount | 2,200 | −78,824 | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) |
| EPS @ 12% discount | 2,200 | −84,546 | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) |
| EPS @ ₹6/kWh | 1,800 | −83,550 | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) |
| EPS @ ₹7/kWh (baseline) | 2,200 | −74,256 | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) |
| EPS @ ₹10/kWh | 3,150 | −57,195 | ![Borderline](https://img.shields.io/badge/-Borderline-orange?style=flat-square) |
| EPS @ ₹15/kWh (commercial) | 4,725 | −21,495 | ![YES](https://img.shields.io/badge/-YES-brightgreen?style=flat-square) |
| PUR @ ₹7/kWh | 2,418 | −1,20,042 | ![NO](https://img.shields.io/badge/-NO-red?style=flat-square) |
| PUR @ ₹15/kWh (commercial) | 5,208 | −39,292 | ![Marginal YES](https://img.shields.io/badge/-Marginal_YES-yellow?style=flat-square) |

### 30-Year Cumulative NPV Progression (EPS @ ₹7/kWh)

| Year | Net Benefit (₹) | Discount Factor | Present Value (₹) | Cumulative NPV (₹) |
|------|----------------|----------------|------------------|-------------------|
| 0 | 0 | 1.0000 | 0 | −99,250 |
| 1 | 1,775 | 0.9302 | 1,651 | −97,599 |
| 5 | 1,775 | 0.6966 | 1,236 | −92,069 |
| 10 | 1,775 | 0.4852 | 861 | −87,066 |
| 15 | 1,775 | 0.3380 | 600 | −83,582 |
| 20 | 1,775 | 0.2354 | 418 | −81,155 |
| 25 | 1,775 | 0.1640 | 291 | −79,464 |
| 30 | 1,775 | 0.1142 | 203 | −78,489 |

The cumulative NPV never crosses zero — simple payback is not achieved within the 30-year service life at subsidized agricultural tariffs.

---

## Governing Equations

### Net Present Value (LCCA)

$$\text{NPV} = -A + \text{NAB} \times \text{PWF}$$

where $A$ is the initial investment, NAB is the Net Annual Benefit (energy savings minus maintenance), and PWF is the Present Worth Factor:

$$\text{PWF} = \frac{(1+d)^n - 1}{d(1+d)^n}$$

with $d$ = discount rate and $n$ = project lifespan in years.

### Embodied Carbon

$$\text{EC}_{\text{total}} = \text{GWP} \times \rho \times t \times A$$

where $\rho$ is material density (kg/m³), $t$ is thickness (m), and $A$ is roof area (m²).

### Thermal Resistance (R-value)

$$R = \frac{t}{\lambda}$$

where $t$ is the insulation thickness (m) and $\lambda$ is thermal conductivity (W/m·K).

### Steady-State Heat Flux through Roof Assembly

$$q = \frac{\Delta T}{R_{\text{total}}} = \frac{T_{\text{ext}} - T_{\text{int}}}{\sum_i R_i}$$

### PCM Latent Heat Storage

$$Q_{\text{stored}} = m \cdot L_f = \rho \cdot V \cdot L_f$$

where $L_f$ is the latent heat of fusion (kJ/kg) and $V$ is the PCM volume (m³). For paraffin PCM: $L_f = 200$ kJ/kg.

### Temperature-Humidity Index (THI) — Dairy Cattle Heat Stress

$$\text{THI} = T_{db} - (0.55 - 0.0055 \cdot RH)(T_{db} - 14.5)$$

Productivity loss initiates at THI ≥ 72; milk yield declines at **0.249 kg/cow/day** per THI unit above 72.

### GHG Conversion (IPCC AR5 GWP₁₀₀)

$$\text{CO}_2\text{eq} = m_{\text{CH}_4} \times 28 + m_{\text{N}_2\text{O}} \times 265$$

---

## Proposed Three-Layer Thermal Design

The optimum thermal management system for BSh-climate livestock shelters integrates three synergistic layers:

**Layer 1 — High-Reflectivity Outer Shell**
- Material: Aluminium or zinc-treated metallic sheet (high solar reflectivity, low emissivity)
- Function: Immediate rejection of 18–24 MJ/m² summer solar load
- Effect: Roof surface temperature reduction of 9.4°C–14.0°C

**Layer 2 — Exterior Phase Change Material (PCM)**
- Material: Paraffin PCM (Lf = 200 kJ/kg, phase change at 24°C–28°C)
- Position: Exterior — must be exposed to solar and ambient temperature fluctuations for full charge/discharge cycling
- Function: Absorbs peak transient solar load during day; releases heat to environment at night
- Advantage over interior placement: up to 13.4% higher energy savings

**Layer 3 — Hygroscopic Insulation (Interior)**
- Material: EPS (lowest embodied carbon) or natural fiber (sheep wool λ = 0.045 W/m·K)
- Function: Steady-state thermal resistance + latent heat management of animal-generated humidity (150–200 W latent heat per cow)
- BIS 1796:2005 compliance: maintains indoor air quality and humidity control

> ![Warning](https://img.shields.io/badge/-Warning-yellow?style=flat-square) **Insulation Conflict Warning:** Placing high-R conventional insulation adjacent to the PCM layer can prevent the PCM from reaching its phase-change temperature, rendering latent heat capacity unused. The PCM must be positioned exterior to all resistive insulation layers. Whole-building dynamic simulation (EnergyPlus) is required to validate layering configurations.

---

## Repository Structure

```
livestock-shelter-lca-lcca/
├── report/
│   └── Economic_and_Environmental_LCA_Livestock_Shelters_India.pdf
├── data/
│   └── Livestock_Shelter_LCCA.xlsx        # Full LCCA workbook: NPV, sensitivity, cash flow tables
├── figures/
│   ├── solar_radiation_pilani_june21.png   # Fig 1 — Diurnal solar radiation & temperature, Pilani
│   ├── pcm_envelope_configurations.png     # Fig 2 — PCM layer placement strategies (interior/exterior/combined)
│   ├── npv_vs_tariff_eps_pur.png           # Fig 3 — NPV sensitivity to electricity tariff (EPS vs PUR)
│   └── cumulative_npv_30yr_eps.png         # Fig 4 — 30-year cumulative NPV progression (EPS @ ₹7/kWh)
└── README.md
```

---

## Regulatory Compliance

All analyses conducted within the boundaries of:

- **BIS 1796:2005** — Code of Practice for Design, Fabrication and Erection of Livestock Shelters
  - Minimum 70 ft²/animal covered floor space
  - Minimum 600 ft³/animal air space
  - Side wall height: 2.5–3.0 m; ridge height for adequate air circulation
- **IPCC AR5 (2021)** — GWP₁₀₀ factors: CH₄ = 28, N₂O = 265
- **IPCC 2019 Refinements** — Tier 2 methodology for livestock GHG inventory

---

## Policy Recommendations

1. **Shift economic rationale** — Financial models must incorporate avoided productivity losses (estimated ₹50,000–₹1,00,000/year for a 50-cow herd) alongside energy savings; energy savings alone cannot justify the capital cost at current tariffs
2. **Standardize EPDs** — Mandatory Environmental Product Declarations for building materials used in Indian agricultural construction, especially for products incorporating synthetic binders
3. **Tariff incentives** — Government-backed transition pathways toward ≥ ₹15/kWh effective tariffs for high-performance insulation payback, or direct capital subsidies to bridge the gap
4. **Mandate dynamic simulation** — Regulatory requirements for EnergyPlus-based dynamic thermal modeling using site-specific climate files before approval of livestock shelter designs
5. **Integrate air quality** — BIS ventilation requirements must be reconciled with PM ingression risk during crop-residue burning season (R² = 0.95 external–internal PM correlation); passive thermal designs that minimize required air exchange during peak-pollution periods should be prioritized

---

## Future Research Directions

- **Dynamic whole-building simulation** using EnergyPlus with Pilani TMY climate file to validate 12–18% energy savings, PCM charge/discharge cycles, and layered material thermal interactions
- **Advanced LCA** incorporating standardized EPDs for Indian building products, capturing synthetic binder and additive GWP contributions to nominally "green" materials
- **Multi-objective optimization** simultaneously minimizing: (i) indoor thermal load, (ii) embodied carbon, (iii) internal PM concentration — subject to BIS ventilation constraints
- **Productivity monetization model** — econometric linkage between THI above 72, milk yield decline (0.249 kg/cow/day/THI unit), fertility rates, and disease incidence for full NPV integration
- **Scaled herd analysis** — extending financial models from 50 to 100+ lactating cows to capture economies of scale in thermal infrastructure investment

---

## Novel Contributions

1. **Natural material paradox quantified** — Crop residue insulation shown to carry 28× the embodied carbon of EPS (8,790 vs. 312.5 kg CO₂eq per 100 m²), challenging assumptions of inherent environmental superiority of agricultural waste-based materials
2. **Dual viability framework** — Demonstrates that energy-only LCCA systematically underestimates project value; a complete financial case requires monetized animal productivity benefits
3. **PCM placement optimization** — Analytically identifies and resolves the "insulation conflict": exterior PCM placement yields up to 13.4% additional energy savings over interior placement by enabling full latent heat utilization
4. **Tariff sensitivity threshold** — Identifies ₹15/kWh as the critical electricity tariff at which EPS insulation approaches economic viability — directly actionable for policy design
5. **Integrated climate-pollution nexus** — Establishes the ventilation paradox unique to arid Indian agricultural settings, where BIS-mandated air exchange conflicts with PM ingress during crop-residue burning season

---

## References

1. Annibaldi, V., Cucchiella, F. and Rotilio, M. *Case Studies in Construction Materials.*
2. Korjenic, A. and Teichmann, F., 2024. Building with renewable materials. *at-Automatisierungstechnik*, 72(7), pp.679–686.
3. Saafi, K. and Daouas, N., 2019. Energy and cost efficiency of phase change materials integrated in building envelopes under Tunisia Mediterranean climate. *Energy*, 187, p.115987.
4. Bureau of Indian Standards (2005). *BIS 1796:2005 — Code of Practice for Design, Fabrication and Erection of Livestock Shelters.*
5. IPCC (2019). *Refinement to the 2006 IPCC Guidelines for National Greenhouse Gas Inventories.*
6. IPCC (2021). *Climate Change 2021: The Physical Science Basis.* Working Group I, Sixth Assessment Report.
7. India Meteorological Department (IMD). *Climatological Normals and Extreme Temperature Records for Pilani, Rajasthan.*
8. ICAR-CIAE (2024). *Insulation Cost Study and Crop-Residue Insulation Technical Bulletin.* Bhopal.
9. Pronto Panels India (2024). *Price List for Polyurethane Foam Insulation Panels — February 2024.*
10. Kosny, J., et al. U.S. DOE. *Phase Change Material Cost Targets and Performance Specifications.*
11. Reserve Bank of India (RBI). *Reference Rates and Agricultural Project Appraisal Guidelines.*
12. Rajasthan Electricity Regulatory Commission. *DISCOM Tariff Order FY 2024–25 — Agricultural Category.*
13. CEIC Data. *India Energy Price Index (2020–2024 Average).*
14. CIGR. *Handbook of Agricultural Engineering, Vol. II.*
15. ASHRAE. *HVAC Applications Handbook.*
16. FAO. *Farm Structures for Hot Dry Climates and Livestock Statistical Yearbook.*
17. International Aluminium Institute (IAI). *Primary Aluminium Statistics.*
18. USGS. *Zinc Production and Generic LCA Factors.*
19. Engineering ToolBox. *Thermal Properties Database for Metals and Building Materials.*
20. NASA POWER, NREL. *Solar Resource Data for Northwest India (Pilani Region).*

---

**Author:** Thilak S | Department of Mechanical Engineering, BITS Pilani  
**Supervisors:** Prof. P. Srinivasan & S. Rahul Bharath | Department of Mechanical Engineering, BITS Pilani  
**Course:** ME F366 | **Period:** August–December 2025  
**Contact:** [f20220771@pilani.bits-pilani.ac.in](mailto:f20220771@pilani.bits-pilani.ac.in)
