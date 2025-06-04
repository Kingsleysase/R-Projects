# Crimes Against Women in India Project (2022). 

---

## Table of Contents
1. [Project Overview & Methodology](#project-overview--methodology)  
2. [Data Analysis & Key Discoveries](#data-analysis--key-discoveries)  
3. [Critical Insights & Business Impact](#critical-insights--business-impact)  
4. [Recommendations](#recommendations)  
5. [Technical Notes](#technical-notes)

---

## Project Overview & Methodology

### Objective

To analyze patterns of crimes against women and girl children across Indian states in 2022, identifying high-risk regions, prevalent crime types, and actionable insights for policy intervention.

### Data Sources

- **Primary Dataset**: National Crime Records Bureau – Crimes Against Women in India (2022)  
- **Supplementary Data**: Female population statistics scraped from StatisticsTimes.com  
- **Coverage**: 36 Indian states and union territories

### Technical Approach

**Tools & Libraries**:  
- Microsoft Excel
- R Studio with the tidyverse ecosystem  
- Data manipulation: `dplyr`, `tidyr`  
- Visualization: `ggplot2`  
- Web scraping: `rvest`  
- Text processing: `tidytext`

**Methodology**:
1. Data import & validation  
2. Exploratory data analysis  
3. Web scraping integration for female population data  
4. Statistical computations: correlations, ratios, comparative metrics  
5. Visual storytelling: over 6 charts generated

---

## Data Analysis & Key Discoveries

### Dataset Characteristics

- **Total Records**: 36 states/UTs  
- **Crime Categories**: Over 18 types  
- **Total Cases**: 445,256 crimes against women  
- **Population Context**: Affects ~0.07% of India’s female population

### Key Findings

#### 1. Crime Distribution Hierarchy

**Top 5 Crimes**:
- Cruelty by husband/relatives: 140,000+ cases (31%)  
- Kidnapping/Abduction: 85,306 cases (19%)  
- Assault to outrage modesty: 83,343 cases (19%)  
- Sexual violence against girl children: 62,063 cases (14%)  
- Rape: 31,518 cases (7%)

#### 2. Geographic Risk Assessment

**High-Risk States**:
- **Uttar Pradesh**: Leads in overall crimes  
- **Bihar**: High in trafficking cases (10,277)  
- **Maharashtra**: High across multiple crime types  
- **West Bengal**: Notable in kidnapping & trafficking

#### 3. Child vs. Adult Vulnerability

10 states reported **more sexual violence against girls than rape cases** involving adult women:
- **Tamil Nadu**: +4,485 cases  
- **Maharashtra**: +4,563 cases  
- **Uttar Pradesh**: +4,265 cases

#### 4. Emerging Crime Trends

- **Cyber Crimes**: 2,340 reported – digital harassment rise  
- **Attempted Crimes**: Rajasthan leads (1,054 cases)  
- **Trafficking**: High concentration in UP–Bihar corridor

---

## Critical Insights & Business Impact

### Policy Implications

#### 1. Domestic Violence Crisis

Cruelty by husbands/relatives accounts for 31% of cases – 383 cases per day. Indicates systemic socio-cultural issues.

#### 2. Child Protection Emergency

Multiple states show more abuse of girl children than adult women, indicating severe risks for minors and urgent need for protective services.

#### 3. Interstate Crime Networks

Trafficking patterns suggest organized networks across state borders (notably UP–Bihar–WB). Cross-border coordination is critical.

#### 4. Myth-Busting With Data

No statistical link found between "indecent representation" and rape cases. Refutes common societal misconceptions and victim-blaming.

### Resource Allocation Priorities

- **Top Priority**: Domestic violence response systems  
- **Urgent Need**: Child protection and anti-trafficking  
- **Emerging Threat**: Digital violence (cyber crimes)  

### Risk Tier Classification

- **Critical**: Uttar Pradesh, Bihar, Maharashtra  
- **High Risk**: West Bengal, Rajasthan, Madhya Pradesh  
- **Special Focus**: Kerala (domestic violence), Tamil Nadu (child abuse)

---

## Recommendations

### Immediate Actions (0–6 Months)

**1. Improve Data Infrastructure**
- Deploy real-time crime dashboards  
- Standardize crime classification  
- Enable digital case tracking  

**2. Strengthen Child Protection**
- Deploy child safety units in 10+ high-risk states  
- Mandatory background checks in child-centered professions  
- Introduce tougher sentencing laws  

**3. Enable Inter-State Coordination**
- Establish anti-trafficking task forces  
- Share real-time intelligence between UP, Bihar, and Maharashtra  
- Introduce geo-fenced alert systems

### Medium-Term Strategies (6–18 Months)

**4. Integrate Smart Tech**
- AI for early pattern detection  
- Crime reporting apps  
- State-level cyber units  

**5. Launch Community Prevention Initiatives**
- Awareness campaigns in top-risk districts  
- Village-level women’s safety committees  
- Economic empowerment for vulnerable groups  

**6. Upgrade Legal & Support Systems**
- Gender-based violence training for police  
- Fast-track courts in major cities  
- Victim support centers and protection programs

### Long-Term Impact (18+ Months)

**7. Policy & Legal Reforms**
- Update penal codes to address new crime trends  
- Mandate institutional crime reporting  
- Launch victim compensation initiatives

**8. Monitor & Evaluate Progress**
- Annual reports on crime trends  
- Predictive modeling to prevent spikes  
- Intervention effectiveness scorecards

### Success Metrics

- **25% reduction in repeat offenses** (2-year goal)  
- **Higher victim satisfaction rates with law enforcement**  
- **Improved inter-state coordination scores**

---

## Technical Notes

- **Reproducibility**: All code written in R/RMarkdown  
- **Update-ready**: Framework supports yearly data integration  
- **Scalable**: Can expand to district-level analysis  

**Limitation**: Based on reported data only, real crime rates are likely higher due to underreporting.

---

_This documentation is intended as both a technical reference and a strategic roadmap for government bodies, NGOs, and development organizations working on women’s safety in India._

---

Thanks for reading!  
**Author:** Kingsley Sase  
**GitHub:** [@Kingsleysase](https://github.com/Kingsleysase)


