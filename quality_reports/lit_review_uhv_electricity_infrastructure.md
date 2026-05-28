# Literature Review: UHV Transmission & Electricity Infrastructure Economics

**Date:** 2026-05-28
**Query:** UHV transmission lines and electricity infrastructure — economic effects on firms, labour, households, environment. English and Chinese literature. Stata-based empirical approach. Chinese micro data context.

## Summary

The literature on UHV (ultra-high voltage) transmission economics has grown rapidly since 2023, with staggered DID as the dominant identification strategy. The core UHV literature now covers pollution (SO₂), energy efficiency, TFP, employment, and corporate innovation — all using China's phased UHV rollout as a quasi-natural experiment. The broader electricity infrastructure literature (Dinkelman 2011; Lipscomb et al. 2013; Allcott et al. 2016) provides complementary evidence from other developing countries, primarily using IV strategies based on terrain and engineering cost shifters. A key gap: no existing UHV paper studies firm entry/exit dynamics, markup behaviour, or resource misallocation at the firm level. The employment paper (Zhao, Gao & Ren 2024, Energy Economics) is the closest to a labour-market angle but focuses on aggregate employment counts rather than firm-level margins.

---

## Key Papers

### UHV-Specific Literature (China)

#### Ren, Bai et al. (2026) — Pollution Reduction Effects of UHV — *Journal of Development Economics*, Vol. 179
- **Main contribution:** First UHV paper in a top-5 economics journal. Studies firm-level SO₂ emissions.
- **Method:** Staggered DID, 43,458 firms (2007–2014), treatment heterogeneity by electricity-importing vs exporting regions. Authors: Ren, Zhao, Zhang & Bai.
- **Key finding:** UHV reduces firm SO₂ emissions by 16.8%, emission intensity by 17.1%. Environmental benefits shorten payback from 28 to 5 years.
- **Mechanisms:** Electrification in importing areas (+16.5% electricity, -18.3% coal); hydropower displacement in exporting areas (+34.8% hydro generation).
- **Relevance:** Benchmark paper for identification strategy and data sources (CNTSD + CESD).

#### Duan & Zhao (2025) — UHV and Industrial Layout Reshaping — *经济理论与经济管理*, Vol. 45, No. 11, pp. 47–68
- **Main contribution:** **Closest existing paper to firm dynamics.** Studies how UHV reshapes industrial spatial distribution.
- **Method:** Synthetic control method (SCM) + three-region new economic geography model. 2005–2020 UHV data + industrial/commercial registration data (工商企业注册数据).
- **Key finding:** UHV increases industrial agglomeration in energy-importing regions but **decreases** it in energy-exporting regions — a "resource curse" effect. Power-intensive industries shift toward importing regions. Clean-energy endowment partially offsets the curse. AC-UHV effects stronger than DC-UHV. Manufacturing (high trade-cost sensitivity) most affected.
- **Relevance:** **Directly shows firm location/entry responds to UHV.** Uses 工商注册 data rather than the standard CNTSD/CESD. But studies aggregate agglomeration indices, not individual firm entry/exit decisions or post-entry dynamics (markup, productivity distribution).

#### Zhao, Gao & Ren (2024) — Employment Effects of UHV — *Energy Economics*, Article 107850
- **Main contribution:** Only existing UHV paper directly studying labour market outcomes.
- **Method:** Quasi-experimental staggered DID, ~1.96 million firm-year observations.
- **Key finding:** UHV increases firm labour demand by 2.3% on average.
- **Mechanisms:** Firm entry promotion + expansion of existing firm production scale. Stronger effects in provinces with high grid reliability and capacity.
- **Relevance:** Closest to our interest area, but studies aggregate employment — not firm dynamics (entry/exit, markup, misallocation).

#### Sun & Min (2024) — Dynamic Trends of UHV Economic Effects — *Energy Economics*, Vol. 138
- **Main contribution:** County-level analysis distinguishing short-term vs long-term effects.
- **Method:** Quasi-natural experiment with counterfactual control group, county panel (2000–2013).
- **Key finding:** Employment and investment effects significant only in the short term. Long-term growth depends on industrial structure upgrading. UHV may crowd out private investment and exacerbate regional imbalances.
- **Relevance:** Important caution — employment effects may not persist without complementary structural change.

#### Feng et al. (2025) — UHV and Industrial TFP — *Energy*, Vol. 320
- **Main contribution:** Uses machine learning (DML + random forest) for causal inference.
- **Method:** Double Machine Learning with staggered UHV adoption.
- **Key finding:** UHV significantly promotes industrial TFP. Mechanisms: cost reduction + capacity stimulation.
- **Relevance:** Shows UHV affects firm productivity margins, not just environmental outcomes. Methodological innovation in UHV literature.

#### Chen & Cheng (2026) — UHV and Corporate Innovation — *Journal of Innovation & Knowledge*
- **Main contribution:** Links UHV to firm innovation outcomes.
- **Method:** Staggered DID, Chinese listed firms (2007–2023).
- **Key finding:** UHV boosts patent applications by 13.1%. Mechanisms: alleviating financing constraints + facilitating digital transformation.
- **Relevance:** Shows UHV affects firm behaviour beyond production — innovation, financing, digital adoption.

#### Yu & Ma (2023) — UHV and Regional Economic Development (特高压输电与区域经济发展) — *数量经济技术经济研究*, 2023(10)
- **Main contribution:** Early Chinese-top-journal UHV paper using night-light GDP.
- **Method:** County-level panel, quasi-experimental.
- **Key finding:** UHV significantly promotes county economic development (night-light intensity).
- **Relevance:** Macro-level evidence; important for framing micro mechanisms.

#### 经济学(季刊) (2024) — Energy Saving Effects of UHV — Ren, Pan, Wang & Zhang, *经济学(季刊)*, 2024, 24(3): 978–994
- **Main contribution:** Firm-level energy consumption study in top Chinese journal.
- **Method:** Staggered DID with CNTSD firm data.
- **Key finding:** UHV reduces firm energy consumption by 5.8% and energy intensity by 9.0%. Mechanisms: scale economy effect + structural optimisation effect.
- **Relevance:** Establishes the cost-reduction channel we would build on for firm dynamics.

#### Xie et al. (2025) — Grid Firm Performance — *Socio-Economic Planning Sciences*, Vol. 102
- **Main contribution:** Studies UHV effects on grid firms themselves (supply side).
- **Method:** Multi-period DID + NDDF, province panel (2005–2022).
- **Key finding:** UHV improves grid firm TFP by 1.07%. Resource allocation + energy substitution mechanisms.
- **Relevance:** Supply-side perspective; less relevant for our firm dynamics focus.

#### UHV-Specific Additions (post-initial-search)

**Ren, Bao & Gao (2025) — UHV and Energy Structure Transformation — *Energy*, Vol. 316**
- **Method:** Staggered DID.
- **Key finding:** UHV reduced thermal power share by 2.18 pp, increased renewable generation by 2.04 pp, raised end-use electricity share by 0.86 pp. Mechanism: shift from "coal transport on the ground" to "electricity transmission in the sky."

**Cheng & Cai (2026) — UHV and Household Energy Poverty — *Technological Forecasting and Social Change*, Vol. 224**
- **Method:** DID using CFPS household panel.
- **Key finding:** UHV significantly reduces household energy poverty via improved electricity access, supply stability, electrification, and income. Stronger in rural areas and unstable-grid regions.
- **Relevance:** Extends UHV effects to the household level — complementary to our firm-level focus.

**KEER (2025) — UHV and Corporate Operational Risk — *Korean Energy Economic Review*, 24(2): 223–253**
- **Method:** Callaway-Sant'Anna staggered DID, A-share listed firms 2007–2016.
- **Key finding:** UHV reduces corporate earnings volatility by ~33%. Mechanisms: green innovation + increased financial leverage. Stronger for non-SOEs and energy-intensive industries.

---

### Broad Electricity Infrastructure Literature (Developing Countries)

#### Dinkelman (2011) — Rural Electrification and Employment — *American Economic Review*, 101(7): 3078–3108
- **Main contribution:** Landmark causal study of electrification in South Africa.
- **Method:** IV — community land gradient instruments for electrification (flatter = cheaper to connect). 1996–2001 census data.
- **Key finding:** Female employment rose ~9.5 pp; mechanism is release from home production (wood collection, cooking), not labour demand shock. Male employment unaffected. Significant in-migration effects.
- **Relevance:** Classic benchmark. Key insight: labour supply channel (home production → market work) may be as important as labour demand channel (firms expand). Congestion externalities from in-migration partially offset welfare gains.

#### Lipscomb, Mobarak & Barham (2013) — Hydropower Grid Expansion in Brazil — *AEJ: Applied Economics*, 5(2): 200–231
- **Main contribution:** Long-run (40-year) study of grid expansion in Brazil.
- **Method:** IV exploiting hydropower potential and engineering cost.
- **Key finding:** Substantial positive development impacts over the long run. Time horizon matters critically.
- **Relevance:** Contrasts with short-run null results in Kenya/India. Suggests complementary investments and time are necessary for grid benefits to materialise.

#### Allcott, Collard-Wexler & O'Connell (2016) — Electricity Shortages and Indian Manufacturing — *American Economic Review*, 106(3)
- **Main contribution:** Measures productivity losses from electricity shortages.
- **Method:** IV using hydro availability and transmission constraints as supply shifters.
- **Key finding:** Shortages reduce firm revenue by 5–10%; plants with generators partially insulated but at higher cost. Significant misallocation from input distortions.
- **Relevance:** Directly relevant to our misallocation angle. Shows that electricity reliability affects firm productivity through input choice distortions.

#### Kassem (2024) — Electrification and Firm Turnover in Indonesia — *Journal of Development Economics*, Vol. 167
- **Main contribution:** **The closest paper to our proposed firm dynamics approach.** Studies how grid expansion affects firm entry, exit, and industrial composition.
- **Method:** IV — colonial-era electric infrastructure + interconnected-grid need. Matched PLN electrification data with manufacturing census (1990–2000, Java).
- **Key finding:** Electrification increases manufacturing firm count, workers, and output. **Both entry and exit rates rise.** Entry accounts for most of the output increase. Consistent with electrification lowering entry costs → increased competition → exit of unproductive firms.
- **Relevance:** Directly demonstrates that electricity infrastructure affects firm turnover margins, not just average outcomes of survivors. Key distinction: studies *initial electrification* (connection to grid), not *grid upgrade* (UHV on already-electrified regions).

#### Fiszbein, Lafortune, Lewis & Tessada (2020) — Electrification and US Manufacturing — NBER Working Paper No. 28076
- **Main contribution:** Historical study of electrification in US manufacturing (1890–1940) with key heterogeneity result relevant to markup/market structure.
- **Method:** Cross-industry × cross-county — pre-electricity energy intensity interacted with proximity to early hydropower.
- **Key finding:** Electrification caused immediate and lasting productivity gains (~10% for energy-intensive industries near hydropower). **Critical heterogeneity: in large-firm markets, productivity rose without employment expansion (firms raised markups); in small-firm markets, both output and employment increased.** Labor-saving, capital-deepening, and hollowing out of middle-skill workers.
- **Relevance:** The markup vs. output-expansion heterogeneity is directly relevant — UHV may similarly have different effects depending on local market structure.

#### Fried & Lagakos (2020) — Electricity and Firm Productivity: A General-Equilibrium Approach — NBER Working Paper No. 27081
- **Main contribution:** Provides the macro-to-micro bridge: why firm entry and reallocation matter for electricity infrastructure.
- **Key finding:** Short-run partial-equilibrium effects of eliminating outages are small (matching micro-empirical findings). **Long-run general-equilibrium effects are ~5× larger (~25% productivity gain)** — operating through firm entry, capital deepening, and resource reallocation.
- **Relevance:** **Theoretical motivation for studying firm dynamics.** Shows that if one looks only at surviving firms, one misses the main channel (entry/exit and reallocation). This is exactly why UHV papers that study only surviving firms may understate total effects.

#### Apeti & Ly (2024) — Power Constraints and Firm-Level TFP in Developing Countries — *Energy*, Vol. 310
- **Main contribution:** Large cross-country evidence on electricity constraints and firm productivity.
- **Method:** Fixed effects + entropy balancing, 84 developing countries, WBES firm data.
- **Key finding:** Firms exposed to outages have 9–11% lower revenue-based TFP. Effect via capacity utilisation and sales losses. R&D and backup generators partially mitigate.
- **Relevance:** Establishes cross-country baseline: electricity reliability → firm productivity. UHV is the reverse shock (improving reliability in China).

#### Fisher-Vanden et al. (2015) — Electricity Shortages and Firm Costs in China
- **Main contribution:** Direct China evidence on power outages and firm costs.
- **Key finding:** Power outages increased per-unit production costs by ~8% across 23,000 Chinese firms. Firms re-optimise by purchasing intermediates rather than producing in-house.

#### Additional Broad Literature
- **Burlig & Preonas (2016):** RDD study of India's grid expansion — negligible short-run economic impacts.
- **Lee, Miguel & Wolfram (forthcoming):** RCT of last-mile connection subsidies in Kenya — no meaningful impacts at 18 months.
- **Abeberese (2017, WBER):** Electricity rationing in Ghana — firm productivity losses from outages.

---

## Thematic Organization

### Identification Strategies

| Strategy | Papers | Key Instrument / Design |
|----------|--------|------------------------|
| Staggered DID | All UHV papers (2023–2026) | UHV line commissioning dates as treatment |
| IV (terrain cost) | Dinkelman (2011), Lipscomb et al. (2013) | Land gradient, hydropower potential, distance to least-cost grid |
| IV (supply shifter) | Allcott et al. (2016) | Hydro availability, transmission constraints |
| RDD | Burlig & Preonas (2016) | Population threshold for electrification |
| RCT | Lee, Miguel & Wolfram | Randomised last-mile connection subsidies |
| DML | Feng et al. (2025) | Double Machine Learning + random forest |

**Key insight for our work:** The UHV literature exclusively uses staggered DID. No UHV paper uses terrain/engineering-cost IV despite this being standard in the broader electrification literature. This is a potential methodological contribution — combining the UHV setting with terrain-based instruments would strengthen causal claims given the well-known issues with staggered DID (heterogeneous treatment effects, negative weights).

### Outcome Variables

| Outcome | UHV Papers | Broad Literature |
|---------|------------|------------------|
| Pollution (SO₂, PM2.5, CO₂) | Ren et al. (2026), 钱&魏 (2025), 张&马 (2026), Duman et al. (2025) | — |
| Firm TFP / efficiency | Feng et al. (2025), Xie et al. (2025) | Allcott et al. (2016), Kassem (2018) |
| Employment | Zhao, Gao & Ren (2024), Sun & Min (2024) | Dinkelman (2011) |
| Innovation | Chen & Cheng (2026), Han et al. (2025) | — |
| Energy consumption | 经济学(季刊) (2024) | — |
| Health | Gao & Zhao (2025) | — |
| Regional GDP / night-light | Yu & Ma (2023), Sun & Min (2024) | Lipscomb et al. (2013), Burlig & Preonas (2016) |

### Data Sources in UHV Literature

| Dataset | Coverage | Papers Using |
|---------|----------|--------------|
| CNTSD (税收调查) | 2007–2016, firm-level, energy + financials | Ren et al. (2026), Feng et al. (2025), 经济学(季刊) (2024) |
| CESD (环境统计) | Firm-level pollutants | Ren et al. (2026) |
| Listed firms (A-shares) | 2007–2023, CSMAR/Wind | Chen & Cheng (2026), KEER (2025) |
| County/year panel | 2000–2013/2020 | Sun & Min (2024), Yu & Ma (2023) |
| CFPS (家庭追踪) | Household micro | Gao & Zhao (2025) |
| UHV line data | Route, commissioning date, voltage | All UHV papers (primary source: NEA/State Grid) |

---

## Gaps and Opportunities

### 1. Firm Dynamics (Entry/Exit, Markup, Misallocation) — Most Promising Gap

**Two papers provide direct motivation:**

- **Kassem (2024, JDE)** shows electrification in Indonesia causes firm turnover (entry + exit), with entry driving most output gains. But she studies *initial electrification* — the UHV context is different: these are already-electrified regions receiving cheaper/more stable power.
- **Fried & Lagakos (2020, NBER)** provides the theoretical foundation: short-run effects on surviving firms are small, but long-run GE effects via entry, capital deepening, and reallocation are ~5× larger. This directly implies that the existing UHV literature (which studies only surviving firms) may substantially understate total welfare effects.

**Duan & Zhao (2025) is the closest UHV paper** — shows UHV reshapes industrial spatial layout using 工商注册 data and SCM. But it studies *aggregate agglomeration indices*, not individual firm-level entry/exit decisions, post-entry dynamics, or within-industry resource reallocation.

The UHV literature has studied firm pollution, TFP, innovation, and employment — but always treating the set of surviving firms as fixed. **No paper studies how UHV changes the composition of firms:** who enters, who exits, how markups adjust, and whether resources flow from low- to high-productivity firms.

- **Entry/exit:** Zhao, Gao & Ren (2024) mention firm entry as a mechanism for employment growth but do not study entry/exit directly. Sun & Min (2024) find employment effects are short-term, which could be because firm churn is the real adjustment margin.
- **Markup:** No UHV paper estimates firm-level markups. **Fiszbein et al. (2020)** shows that in the historical US, electrification's effect on markups vs. output depended on local market structure — this heterogeneity has not been tested for UHV.
- **Misallocation:** Allcott et al. (2016) and Kassem (2024) establish that electricity reliability affects allocative efficiency. This has not been tested in the UHV context.

**Why this matters:** If UHV primarily helps low-productivity firms survive (reducing exit) rather than enabling high-productivity firms to expand, the net welfare effect could be negative despite positive average effects on surviving firms.

### 2. Labour Market Mechanisms Beyond Aggregate Employment

Zhao, Gao & Ren (2024) study aggregate employment. No UHV paper studies:
- Skill composition and wage premia
- Labour reallocation across firms and industries
- Indirect labour effects through supply chains

### 3. Methodological Gap — IV Using Terrain / Engineering Cost

The UHV literature exclusively uses staggered DID. The broader electrification literature (Dinkelman, Lipscomb et al., Kassem) uses terrain and engineering-cost IVs. Combining these approaches would provide methodological triangulation.

### 4. Consumer Welfare / Pass-Through

No UHV paper estimates how much of the electricity cost reduction passes through to consumers via lower output prices. The markup angle remains entirely unexplored.

---

## Suggested Next Steps

1. **Read the 3 most directly relevant papers in full:**
   - Ren, Bai et al. (2026, JDE) — identification benchmark
   - Zhao, Gao & Ren (2024, Energy Economics) — closest to our labour angle
   - Feng et al. (2025, Energy) — TFP and firm productivity margins

2. **Read Kassem (2018)** for the firm dynamics approach (entry/exit, allocative efficiency) in the electrification context — directly transferable to UHV.

3. **Formalise the research design:** Use `/interview-me` to specify which firm-dynamics margin (entry/exit vs markup vs misallocation) to attack first, and what data is accessible (CNTSD vs listed firms vs industrial firm DB).

4. **Data reconnaissance:** Verify CNTSD access (the core dataset for all top UHV papers), and check whether firm entry/exit can be identified in the available data.

---

## BibTeX Entries

```bibtex
@article{ren2026pollution,
  title={Pollution reduction effects of new transregional power transmission systems: Evidence from ultra-high-voltage projects of China},
  author={Ren, Shenggang and Zhao, Li and Zhang, Peng and Bai, Caiquan},
  journal={Journal of Development Economics},
  volume={179},
  year={2026},
  doi={10.1016/j.jdeveco.2025.103641}
}

@article{zhao2024employment,
  title={The effects of long-distance power transmission on employment growth: Empirical evidence from ultra-high voltage projects of China},
  author={Zhao, L. and Gao, Z. and Ren, S.},
  journal={Energy Economics},
  pages={107850},
  year={2024},
  doi={10.1016/j.eneco.2024.107850}
}

@article{sun2024dynamic,
  title={Dynamic trends and regional differences of economic effects of ultra-high-voltage transmission projects},
  author={Sun, C. and Min, J.},
  journal={Energy Economics},
  volume={138},
  pages={107871},
  year={2024},
  doi={10.1016/j.eneco.2024.107871}
}

@article{feng2025uhv,
  title={Identifying the new momentum from the instrumental substitution of energy industry in China: Empirical evidence from the ultra-high voltage transmission projects},
  author={Feng, X. and others},
  journal={Energy},
  volume={320},
  year={2025},
  doi={10.1016/j.energy.2025.134613}
}

@article{chen2026innovation,
  title={How does energy infrastructure affect corporate innovation? Evidence from ultra-high voltage transmission projects in China},
  author={Chen, J. and Cheng, Y.},
  journal={Journal of Innovation & Knowledge},
  year={2026},
  doi={10.1016/j.jik.2025.100674}
}

@article{xie2025performance,
  title={Performance evaluation of emerging grid infrastructure operations: Evidence from ultra-high-voltage transmission lines in China},
  author={Xie, B.-C. and Wu, Q.-X. and Qin, Y.-Y. and Zhang, C.},
  journal={Socio-Economic Planning Sciences},
  volume={102},
  year={2025},
  doi={10.1016/j.seps.2025.102162}
}

@article{yu2023uhv,
  title={特高压输电与区域经济发展——来自特高压工程的经验证据},
  author={于 and 马},
  journal={数量经济技术经济研究},
  volume={2023},
  number={10},
  year={2023}
}

@article{dinkelman2011electrification,
  title={The effects of rural electrification on employment: New evidence from South Africa},
  author={Dinkelman, Taryn},
  journal={American Economic Review},
  volume={101},
  number={7},
  pages={3078--3108},
  year={2011},
  doi={10.1257/aer.101.7.3078}
}

@article{lipscomb2013development,
  title={Development effects of electrification: Evidence from the topographic placement of hydropower plants in Brazil},
  author={Lipscomb, Molly and Mobarak, A. Mushfiq and Barham, Tania},
  journal={American Economic Journal: Applied Economics},
  volume={5},
  number={2},
  pages={200--231},
  year={2013},
  doi={10.1257/app.5.2.200}
}

@article{allcott2016electricity,
  title={How do electricity shortages affect industry? Evidence from India},
  author={Allcott, Hunt and Collard-Wexler, Allan and O'Connell, Stephen D.},
  journal={American Economic Review},
  volume={106},
  number={3},
  year={2016}
}

@article{duan2025uhv,
  title={中国特高压输电工程建设与产业布局重塑},
  author={段巍 and 赵瀚林},
  journal={经济理论与经济管理},
  volume={45},
  number={11},
  pages={47--68},
  year={2025}
}

@article{kassem2024electrification,
  title={Does electrification cause industrial development? Grid expansion and firm turnover in Indonesia},
  author={Kassem, Dana},
  journal={Journal of Development Economics},
  volume={167},
  year={2024},
  doi={10.1016/j.jdeveco.2023.103234}
}

@techreport{fiszbein2020electrification,
  title={Powering Up Productivity: The Effects of Electrification on U.S. Manufacturing},
  author={Fiszbein, Martin and Lafortune, Jeanne and Lewis, Ethan G. and Tessada, Jos{\'e}},
  institution={NBER},
  number={w28076},
  year={2020}
}

@techreport{fried2020electricity,
  title={Electricity and Firm Productivity: A General-Equilibrium Approach},
  author={Fried, Stephie and Lagakos, David},
  institution={NBER},
  number={w27081},
  year={2020}
}

@article{apeti2024power,
  title={Power constraints and firm-level total factor productivity in developing countries},
  author={Apeti, Ablam Estel and Ly, Tidiane},
  journal={Energy},
  volume={310},
  year={2024}
}

@article{fishervanden2015electricity,
  title={Electricity shortages and firm productivity in China},
  author={Fisher-Vanden, Karen and Mansur, Erin T. and Wang, Qiong},
  journal={Journal of Development Economics},
  volume={114},
  pages={172--188},
  year={2015}
}

@article{ren2025arrival,
  title={Arrival of distant power: The impact of ultra-high voltage transmission projects on energy structure in China},
  author={Ren, Shenggang and Bao, Y. and Gao, Z.},
  journal={Energy},
  volume={316},
  year={2025}
}

@article{cheng2026new,
  title={New energy infrastructure and household energy poverty: Insights from ultra-high voltage technology},
  author={Cheng, Y. and Cai, Y.},
  journal={Technological Forecasting and Social Change},
  volume={224},
  year={2026}
}

@article{burlig2016grid,
  title={Grid Expansion and Development: Evidence from India},
  author={Burlig, Fiona and Preonas, Louis},
  journal={Working Paper},
  year={2016}
}

@article{gao2025health,
  title={UHV and resident health: Evidence from CFPS},
  author={Gao, Z. and Zhao, L.},
  journal={Energy Economics},
  year={2025}
}
```
