
# 📡 Telco Go-To-Market: LGA Potential Analyzer & Forecasting System

<img width="1580" height="841" alt="image" src="https://github.com/user-attachments/assets/c3c9bf73-a8de-4791-b67f-38a92408e787" />

## Introduction
In Nigeria’s rapidly expanding telecommunications industry, growth is often concentrated in major urban centers, leaving many rural and semi-rural regions under connected and commercially unexplored. Yet, these areas hold significant potential for network expansion, agent deployment, and digital inclusion. Telecom providers often lack clear, data-driven insights into which Local Government Areas (LGAs) are most viable for investment, leading to uneven coverage and missed opportunities.
This project, Telco Go-To-Market: LGA Potential Analyzer and Forecasting System seeks to close that gap by using automation and artificial intelligence to identify viable but underserved LGAs across Nigeria. The system integrates multiple data sources such as population statistics, income estimates, network coverage, and competition presence, and processes them through an automated workflow built with n8n, analyzed using Cerebras AI, and stored in PostgreSQL for real-time visualization on Streamlit + Plotly dashboards.
The study covers six states, each representing one of Nigeria’s six geopolitical zones, with ten rural LGAs per state selected for analysis. By excluding major urban LGAs, the project focuses on discovering new areas of opportunity places where population and economic potential exist but telecom presence remains limited.
Ultimately, this solution provides telecom stakeholders with clear, AI-powered insights into where expansion efforts will deliver the highest impact, supporting smarter decision-making, efficient resource allocation, and inclusive network development across Nigeria’s diverse regions.

## Statement of the Problem
Telecommunication growth in Nigeria has been largely urban-centric, with major investments concentrated in state capitals and commercial hubs. However, millions of people living in rural and semi-rural Local Government Areas (LGAs) remain underserved despite having strong population presence, emerging economic activities, and increasing demand for digital connectivity.
Currently, telecom operators lack a unified, data-driven system that can highlight where true market opportunities exist outside major cities. Decision-making often relies on fragmented reports, outdated surveys, or intuition, which fails to capture the dynamic relationship between population density, income levels, network coverage, and competition presence.
This gap results in misdirected investments, underutilized infrastructure, and missed opportunities in regions that could yield high returns if properly understood. There is therefore a need for an automated, AI-powered analytical system that can gather data from multiple sources, analyze it intelligently, and pinpoint the most viable rural LGAs for telecom expansion and agent deployment.

## Objectives of the Project

i. To develop an automated data pipeline using n8n that collects, cleans, and integrates data from telecom, population, and economic sources into a unified PostgreSQL database.

ii. To implement an AI analysis module that processes collected data and generates intelligent insights such as telecom viability scores, coverage gaps, and opportunity rankings for each LGA.

iii. To identify and rank ten (10) rural LGAs per state (across six geopolitical zones) based on their population strength, income potential, and telecom under-service level.

iv. To design a real-time visualization dashboard in Streamlit + Plotly that presents AI-generated insights in clear visual formats, including maps, rankings, and comparative charts across states.

v. To provide a decision-support framework that helps telecom operators and policymakers prioritize rural LGAs for network investment, kiosk deployment, and digital inclusion initiatives.

## Business Implications of the Telco Go-To-Market Analyzer

The Telco Go-To-Market: LGA Potential Analyzer & Forecasting System is a strategic asset designed to transform the investment and expansion strategy of telecommunication operators in Nigeria. Its core business implication lies in shifting resource allocation from reactive, high-competition urban markets to proactive, high-potential underserved rural markets, thereby securing long-term, profitable growth.

1. Optimized Capital Expenditure (CAPEX)
   
This system provides a data-driven mechanism to ensure that expensive infrastructure investments are targeted for maximum return.
  - CAPEX Efficiency: Instead of broad-stroke expansion, the AI-generated Viability Score and Opportunity Score allow operators to pinpoint the top 10-20 most commercially viable LGAs nationwide. This minimizes the risk of deploying Base Transceiver Stations (BTS) in low-demand, low-income areas.
    
  - Reduced Time-to-Market: By replacing lengthy, manual market surveys with a real-time, automated dashboard, the time required to approve and initiate expansion projects is drastically reduced. This allows the operator to capture market share before competition moves in.
  
  - Smarter Agent and Kiosk Deployment (OPEX): The system's insights into Digital Potential and Telecom Readiness directly guide the operational planning (OPEX). It ensures that sales agents, distribution channels, and retail kiosks are placed in LGAs with the highest projected mobile adoption rates, maximizing sales efficiency and minimizing operational waste.

    
2. Accelerated Subscriber Growth and Market Share
   
The project's focus on underserved, rural LGAs unlocks entirely new customer bases that are less saturated by competitors.

  - First-Mover Advantage: Identifying and prioritizing LGAs with high Population and strong Economic Strength but low current network presence grants the operator a critical first-mover advantage, leading to high market share capture and brand loyalty in these developing markets.
  - Increased Revenue Per User (ARPU): LGAs prioritized by the Digital Potential score indicate areas with high readiness for data services (3G/4G/5G). Targeting these areas leads to higher adoption of data plans and value-added services, thereby increasing the Average Revenue Per User (ARPU).
  - Data-Driven Targeting: The LGA-specific AI summaries allow marketing teams to tailor expansion campaigns (e.g., offering agricultural information services in farming LGAs or mobile money solutions in high-commerce LGAs), leading to higher conversion rates than generic, national marketing pushes.
    
3. Enhanced Risk Management and Strategy Formulation
   
The system provides a clear, objective view of strategic risks and competitive dynamics.

  - Risk Mitigation: The AI Risk Analysis provides early warnings regarding potential challenges like security, infrastructure constraints, or regulatory hurdles unique to an LGA, enabling pre-emptive planning and cost reduction before ground operations begin.
  - Inclusive Development Reporting: The system serves as a powerful tool for reporting compliance with digital inclusion mandates by demonstrating that investment decisions are being made systematically to bridge the urban-rural connectivity divide.
  - Scenario Planning: By easily filtering and comparing LGAs by various metrics (e.g., high economic strength vs. high opportunity score), executive leadership can conduct rapid scenario analysis to determine the optimal strategic approach (e.g., maximizing immediate revenue versus investing for long-term growth).


The SmartGuard AI System transforms the go-to-market strategy from a static, fragmented process into a dynamic, AI-powered intelligence function, making it essential for any telecom operator focused on inclusive and profitable expansion across Nigeria.

## Scope of Study (Geographical Scope)
This study will cover six (6) selected states in Nigeria, one from each of the six geopolitical zones and focusing on ten (10) rural or semi-rural Local Government Areas (LGAs) per state that are not major commercial or capital LGAs. The selected states and LGAs are as follows:
#### North Central (Benue State): Logo, Ukum, Guma, Agatu, Katsina-Ala, Oju, Apa, Konshisha, Obi, Tarka.
#### North East (Taraba State): Donga, Karim-Lamido, Ussa, Lau, Zing, Yorro, Gashaka, Kurmi, Takum, Ardo-Kola.
#### North West (Kebbi State): Bagudo, Koko/Besse, Danko-Wasagu, Fakai, Dandi, Augie, Arewa-Dandi, Ngaski, Sakaba, Shanga.
#### South East (Ebonyi State): Afikpo North, Afikpo South, Ivo, Onicha, Ohaozara, Ishielu, Ikwo, Ezza South, Izzi, Ohaukwu.
#### South South (Akwa Ibom State): Ini, Oruk Anam, Eastern Obolo, Mkpat Enin, Mbo, Udung Uko, Ukanafun, Ika, Ibiono Ibom, Okobo.
#### South West (Ekiti State): Ise/Orun, Ikole, Ijero, Moba, Efon, Ekiti East, Ekiti West, Irepodun/Ifelodun, Ilejemeje, Oye.

Altogether, the project will analyze 60 LGAs across 6 states, representing Nigeria’s full geopolitical diversity. The focus is on understanding rural telecom viability by combining population data, income estimates, network coverage, and AI-driven insights to highlight areas most suitable for telecom expansion and investment.




## Tech Stack

i. n8n (Automation & API Engine)
Used to collect data from all external sources such as OpenSignal, Ookla, population, and economic APIs.
It also creates internal APIs, schedules data updates, cleans incoming data, and sends it for AI analysis.

ii. Cerebras (AI Analysis Engine)
Serves as the main artificial intelligence component.
It receives cleaned data from n8n, performs analysis, scoring, and forecasting, then sends structured insights back to PostgreSQL.
This replaces heavy local models and ensures faster, API-based intelligence.

iii. PostgreSQL (Central Database)
Stores everything — raw data, cleaned datasets, and AI-generated insights.
Acts as the main data warehouse and connects directly to Grafana for visualization.

iv. Streamlit + Plotly (Visualization Layer)
Reads all processed data and AI results directly from PostgreSQL.
Displays real-time dashboards, LGA rankings, growth trends, and geo-mapped insights for decision-makers.

v. External Data Sources (APIs and Feeds)
Includes telecom coverage APIs population and economic APIs, and any local datasets related to LGA demographics, income, and competition presence.

### Project Steps and Implementation
#### Phase 1: Database Setup (PostgreSQL)
Step 1: Create a single, well-structured PostgreSQL database that will hold all data for the system.

•	Log into postgre. Run these two commands one after the other;
```
sudo -i -u postgres
psql
```

•	Create your database. Run;
```
CREATE DATABASE telco_db;
```

•	Create a PostgreSQL User
```
CREATE USER telco_user WITH PASSWORD 'password';
 ```
<img width="734" height="191" alt="image" src="https://github.com/user-attachments/assets/c42f3a0c-433b-491e-a635-a800ab8bf57b" />


•	Grant all privileges on the database. Run;
```
GRANT ALL PRIVILEGES ON DATABASE telco_db TO telco_user;
```

•	Connect to the database. Run;
```
\c telco_db
```

•	Run the below one after another
```
GRANT ALL PRIVILEGES ON ALL TABLES IN SCHEMA public TO telco_user;
GRANT ALL PRIVILEGES ON ALL SEQUENCES IN SCHEMA public TO telco_user;
```
<img width="975" height="323" alt="image" src="https://github.com/user-attachments/assets/a3683b13-386e-45e8-a90d-9c0514e973a8" />


•	Make new tables automatically inherit permissions. Run;
```
ALTER DEFAULT PRIVILEGES IN SCHEMA public
GRANT ALL PRIVILEGES ON TABLES TO telco_user;
```

Step 2: Prepare tables for economic and income, mobile and internet penetration per LGA

•	Create the MASTER LGA TABLE (very important). This is the backbone that all other tables will link to. Run;
```
CREATE TABLE lga_master (
    lga_id SERIAL PRIMARY KEY,
    state_name VARCHAR(100) NOT NULL,
    lga_name VARCHAR(100) NOT NULL,
    geo_zone VARCHAR(50) NOT NULL
);
```
<img width="553" height="211" alt="image" src="https://github.com/user-attachments/assets/9003dec8-e3b4-4d65-8c05-778113dc19e0" />

  - This table holds the 60 LGAs
  - Everything else will connect to this table
  - It ensures clean JOINs and consistency






•	Create ECONOMIC & INCOME Table. Run;
```
CREATE TABLE lga_economic_income (
    id SERIAL PRIMARY KEY,
    lga_id INT NOT NULL REFERENCES lga_master(lga_id),
    year INT NOT NULL,
    gdp_per_capita_usd NUMERIC(14,2),
    gni_per_capita_usd NUMERIC(14,2),
    income_estimate_usd NUMERIC(18,2),
    spending_power_usd NUMERIC(18,2),
    economic_score NUMERIC(5,2)
);
``` 
<img width="775" height="290" alt="image" src="https://github.com/user-attachments/assets/9ee8c448-e028-47d3-b6d6-f17f75540f63" />

This table will hold:
  - GDP per capita
  - GNI per capita
  - Estimated income
  - Spending power
  - Economic score (later computed by AI)

•	Create MOBILE & INTERNET PENETRATION Table. Run;
```
CREATE TABLE lga_mobile_internet (
    id SERIAL PRIMARY KEY,
    lga_id INT NOT NULL REFERENCES lga_master(lga_id),
    year INT NOT NULL,
    population INT,
    phone_ownership_rate_pct NUMERIC(5,2),
    estimated_phone_users INT,
    mobile_penetration_pct NUMERIC(5,2),
    estimated_mobile_users INT,
    internet_penetration_pct NUMERIC(5,2),
    estimated_internet_users INT,
    telecom_demand_score NUMERIC(5,2)
);
```


This table will hold:
  - Population
  - Phone ownership
  - Mobile penetration
  - Internet penetration
  - Calculated mobile/internet users
  - Telecom demand score


Step 3: Add tables for AI analysis results and other computed insights.
These tables will store:
- AI-generated summaries
- Viability scores
- Opportunity rankings
- Risk analysis
- Any future metrics you compute in n8n or Groq


We will create three clean tables:

i.	Insights (Summaries & Recommendations)

ii.	AI Scores (Numeric scoring breakdown)

iii.	Computed Indicators (Any extra metrics you calculate manually or in n8n)

•	This table stores the AI-generated English explanations, what n8n sends to Groq. Run;
CREATE TABLE lga_ai_insights (
    id SERIAL PRIMARY KEY,
    lga_id INT NOT NULL REFERENCES lga_master(lga_id),
    year INT NOT NULL,
    ai_summary TEXT,                -- Full text summary from AI
    ai_recommendation TEXT,         -- AI suggestions
    ai_risk_analysis TEXT,          -- Weaknesses, threats, risks
    created_at TIMESTAMP DEFAULT NOW()
);
 



This table will hold:
	“This LGA shows strong telecom opportunity…”
	“Population is high, income moderate…”
	AI reasoning
	AI advice

•	AI Scores Table (Numeric values). Run;
CREATE TABLE lga_ai_scores (
    id SERIAL PRIMARY KEY,
    lga_id INT NOT NULL REFERENCES lga_master(lga_id),
    year INT NOT NULL,

    viability_score NUMERIC(5,2),        -- 0–100
    opportunity_score NUMERIC(5,2),      -- 0–100
    risk_score NUMERIC(5,2),             -- 0–100
    economic_strength NUMERIC(5,2),      -- 0–100
    telecom_readiness NUMERIC(5,2),      -- 0–100
    digital_potential NUMERIC(5,2),      -- 0–100

    created_at TIMESTAMP DEFAULT NOW()
);

This table will hold all numeric metrics such as:
	AI Viability Score
	Growth Potential Score
	Demand Score
	Risk Score

•	Computed Insights Table (your custom formulas). Run
CREATE TABLE lga_computed_indicators (
    id SERIAL PRIMARY KEY,
    lga_id INT NOT NULL REFERENCES lga_master(lga_id),
    year INT NOT NULL,

    market_size INT,                -- estimated_phone_users
    data_user_estimate INT,         -- estimated_internet_users
    telecom_opportunity_index NUMERIC(5,2),
    economic_category VARCHAR(50),  -- high / medium / low
    demand_category VARCHAR(50),    -- high / medium / low

    created_at TIMESTAMP DEFAULT NOW()
);



Step 4: Link all tables with a unique LGA ID for consistency across datasets.
•	Insert All 60 LGAs into lga_master Table. Run the following one by one
BENUE — NORTH CENTRAL
INSERT INTO lga_master (state_name, lga_name, geo_zone) VALUES
('Benue', 'Logo', 'North Central'),
('Benue', 'Ukum', 'North Central'),
('Benue', 'Guma', 'North Central'),
('Benue', 'Agatu', 'North Central'),
('Benue', 'Katsina-Ala', 'North Central'),
('Benue', 'Oju', 'North Central'),
('Benue', 'Apa', 'North Central'),
('Benue', 'Konshisha', 'North Central'),
('Benue', 'Obi', 'North Central'),
('Benue', 'Tarka', 'North Central');

TARABA — NORTH EAST
INSERT INTO lga_master (state_name, lga_name, geo_zone) VALUES
('Taraba', 'Donga', 'North East'),
('Taraba', 'Karim-Lamido', 'North East'),
('Taraba', 'Ussa', 'North East'),
('Taraba', 'Lau', 'North East'),
('Taraba', 'Zing', 'North East'),
('Taraba', 'Yorro', 'North East'),
('Taraba', 'Gashaka', 'North East'),
('Taraba', 'Kurmi', 'North East'),
('Taraba', 'Takum', 'North East'),
('Taraba', 'Ardo-Kola', 'North East');

KEBBI — NORTH WEST
INSERT INTO lga_master (state_name, lga_name, geo_zone) VALUES
('Kebbi', 'Bagudo', 'North West'),
('Kebbi', 'Koko/Besse', 'North West'),
('Kebbi', 'Danko-Wasagu', 'North West'),
('Kebbi', 'Fakai', 'North West'),
('Kebbi', 'Dandi', 'North West'),
('Kebbi', 'Augie', 'North West'),
('Kebbi', 'Arewa-Dandi', 'North West'),
('Kebbi', 'Ngaski', 'North West'),
('Kebbi', 'Sakaba', 'North West'),
('Kebbi', 'Shanga', 'North West');







EBONYI — SOUTH EAST
INSERT INTO lga_master (state_name, lga_name, geo_zone) VALUES
('Ebonyi', 'Afikpo North', 'South East'),
('Ebonyi', 'Afikpo South', 'South East'),
('Ebonyi', 'Ivo', 'South East'),
('Ebonyi', 'Onicha', 'South East'),
('Ebonyi', 'Ohaozara', 'South East'),
('Ebonyi', 'Ishielu', 'South East'),
('Ebonyi', 'Ikwo', 'South East'),
('Ebonyi', 'Ezza South', 'South East'),
('Ebonyi', 'Izzi', 'South East'),
('Ebonyi', 'Ohaukwu', 'South East');

AKWA IBOM — SOUTH SOUTH
INSERT INTO lga_master (state_name, lga_name, geo_zone) VALUES
('Akwa Ibom', 'Ini', 'South South'),
('Akwa Ibom', 'Oruk Anam', 'South South'),
('Akwa Ibom', 'Eastern Obolo', 'South South'),
('Akwa Ibom', 'Mkpat Enin', 'South South'),
('Akwa Ibom', 'Mbo', 'South South'),
('Akwa Ibom', 'Udung Uko', 'South South'),
('Akwa Ibom', 'Ukanafun', 'South South'),
('Akwa Ibom', 'Ika', 'South South'),
('Akwa Ibom', 'Ibiono Ibom', 'South South'),
('Akwa Ibom', 'Okobo', 'South South');

EKITI — SOUTH WEST
INSERT INTO lga_master (state_name, lga_name, geo_zone) VALUES
('Ekiti', 'Ise/Orun', 'South West'),
('Ekiti', 'Ikole', 'South West'),
('Ekiti', 'Ijero', 'South West'),
('Ekiti', 'Moba', 'South West'),
('Ekiti', 'Efon', 'South West'),
('Ekiti', 'Ekiti East', 'South West'),
('Ekiti', 'Ekiti West', 'South West'),
('Ekiti', 'Irepodun/Ifelodun', 'South West'),
('Ekiti', 'Ilejemeje', 'South West'),
('Ekiti', 'Oye', 'South West');






Phase 2: Data Collection, Automation, and AI Analysis (n8n + Groq API)
Automate the full process of data gathering, cleaning, and analysis using n8n.
Step 1: Schedule workflows to pull new data automatically (daily or weekly).
•	Open n8n
•	Add a Cron Trigger Node
•	Set the frequency depending on your preference:
 
Step 2: Connect n8n to all external data sources such to pull Economic and Income Estimate and Mobile and Internet Penetration
Add Population HTTP node
•	In n8n, create a new workflow (or open existing one).
•	Add HTTP Request node.
•	Rename it: WB_Population.
•	Method: GET
URL: https://api.worldbank.org/v2/country/NG/indicator/SP.POP.TOTL?format=json
•	Response Format: JSON
•	Click Execute Node.
 

Connect GDP per Capita API in n8n
•	Add HTTP Request node.
•	Rename it: WB_GDP_PerCapita
•	Method: GET
URL: https://api.worldbank.org/v2/country/NG/indicator/NY.GDP.PCAP.CD?format=json
•	Response Format: JSON
•	Click Execute Node.
 



Connect GNI per Capita API in n8n
•	In n8n, create a new workflow 
•	Add HTTP Request node.
•	Rename it: WB_GNI_PerCapita
•	Method: GET
URL: https://api.worldbank.org/v2/country/NG/indicator/NY.GNP.PCAP.CD?format=json
•	Response Format: JSON
•	Click Execute Node.
 
Connect World Bank Mobile Penetration API
•	In n8n, create a new workflow
•	Add HTTP Request node.
•	Rename it: WB_Mobile_Penetration
•	Method: GET
URL: https://api.worldbank.org/v2/country/NG/indicator/IT.CEL.SETS.P2?format=json
•	Response Format: JSON
•	Click Execute Node
 
Connect World Bank Internet Penetration API
•	In n8n, create a new workflow
•	Add HTTP Request node.
•	Rename it: WB_Internet_Penetration
•	Method: GET
URL: https://api.worldbank.org/v2/country/NG/indicator/IT.NET.USER.ZS?format=json
•	Response Format: JSON
•	Click Execute Node.
 

Step 3: Clean and merge all incoming data using Python or Set Nodes inside n8n.

MERGE NATIONAL DATA
•	Search for "Merge" node type
•	Set Mode to: "Append and set it to 5
•	Add a Code node
•	Rename it: Merge_National_Data
•	Paste this EXACT code 
const items = $input.all();

function findIndicator(indicatorId) {
  for (let item of items) {
    if (item.json && Array.isArray(item.json)) {
      for (let dataPoint of item.json) {
        if (dataPoint.indicator && dataPoint.indicator.id === indicatorId && dataPoint.value !== null) {
          return {
            value: dataPoint.value,
            year: dataPoint.date,
            indicator: dataPoint.indicator.value
          };
        }
      }
    }
  }
  return { value: null, year: 'N/A', indicator: 'Not found' };
}

const population = findIndicator('SP.POP.TOTL');
const gdp = findIndicator('NY.GDP.PCAP.CD');
const gni = findIndicator('NY.GNP.PCAP.CD');
const mobile = findIndicator('IT.CEL.SETS.P2');
const internet = findIndicator('IT.NET.USER.ZS');

return [{
  json: {
    country: 'Nigeria',
    country_code: 'NGA',
    fetched_at: new Date().toISOString(),
    
    population_total: population.value,
    gdp_per_capita: gdp.value,
    gni_per_capita: gni.value,
    mobile_penetration: mobile.value,
    internet_penetration: internet.value,
    
    data_year: population.year,
    
    metadata: {
      population_year: population.year,
      gdp_year: gdp.year,
      gni_year: gni.year,
      mobile_year: mobile.year,
      internet_year: internet.year
    }
  }
}];

•	Click Execute
 

Local Government Calculations
•	Add a Code node
•	Rename it: LGA_Distribution
•	Paste this EXACT code 
// CORRECTED CODE - Using Naira GDP directly
const nationalData = $input.first().json;

// Nigeria's GDP in NAIRA (not converted from USD)
// Estimated 2024: ₦250-300 trillion for 233M people
const NAIRA_GDP_TOTAL = 275000000000000; // ₦275 trillion (conservative estimate)
const NAIRA_POPULATION = nationalData.population_total;
const NAIRA_GDP_PER_CAPITA = NAIRA_GDP_TOTAL / NAIRA_POPULATION; // ~₦1,180,000

// Or use historical naira GDP growth rate
// 2023: GDP per capita was $1,597 at ₦750 = ₦1,197,750 naira
// 2024: Apply ~5% naira inflation = ₦1,257,638 naira per capita

// BETTER: Use actual naira income data
const REALISTIC_NAIRA_GDP_PER_CAPITA = 450000; // ₦450k per person (more realistic)
const REALISTIC_NAIRA_GNI_PER_CAPITA = 420000; // ₦420k per person

// State populations
const statePopulations = {
  'Benue': 6540000,
  'Taraba': 3498000,
  'Kebbi': 4620000,
  'Ebonyi': 3497000,
  'Akwa Ibom': 5542000,
  'Ekiti': 3565000
};

const stateEconomicFactors = {
  'Benue': 0.75,
  'Taraba': 0.70,
  'Kebbi': 0.65,
  'Ebonyi': 0.72,
  'Akwa Ibom': 1.15,
  'Ekiti': 0.85
};

const lgaStateShares = {
  // [Same as before - your population shares]
  'Logo': 0.0163, 'Ukum': 0.0380, 'Guma': 0.0452, 'Agatu': 0.0383,
  'Katsina-Ala': 0.0342, 'Oju': 0.0400, 'Apa': 0.0392,
  'Konshisha': 0.0287, 'Obi': 0.0280, 'Tarka': 0.0228,
  
  'Donga': 0.0383, 'Karim-Lamido': 0.0422, 'Ussa': 0.0256,
  'Lau': 0.0420, 'Zing': 0.0364, 'Yorro': 0.0289,
  'Gashaka': 0.0256, 'Kurmi': 0.0324, 'Takum': 0.0387, 'Ardo-Kola': 0.0276,
  
  'Bagudo': 0.0500, 'Koko/Besse': 0.0343, 'Danko-Wasagu': 0.0293,
  'Fakai': 0.0275, 'Dandi': 0.0238, 'Augie': 0.0454,
  'Arewa-Dandi': 0.0255, 'Ngaski': 0.0318, 'Sakaba': 0.0333, 'Shanga': 0.0300,
  
  'Afikpo North': 0.0448, 'Afikpo South': 0.0401, 'Ivo': 0.0367,
  'Onicha': 0.0702, 'Ohaozara': 0.0480, 'Ishielu': 0.0402,
  'Ikwo': 0.0622, 'Ezza South': 0.0417, 'Izzi': 0.0576, 'Ohaukwu': 0.0612,
  
  'Ini': 0.0228, 'Oruk Anam': 0.0280, 'Eastern Obolo': 0.0153,
  'Mkpat Enin': 0.0340, 'Mbo': 0.0166, 'Udung Uko': 0.0171,
  'Ukanafun': 0.0218, 'Ika': 0.0290, 'Ibiono Ibom': 0.0224, 'Okobo': 0.0256,
  
  'Ise/Orun': 0.0403, 'Ikole': 0.0458, 'Ijero': 0.0447,
  'Moba': 0.0385, 'Efon': 0.0280, 'Ekiti East': 0.0381,
  'Ekiti West': 0.0373, 'Irepodun/Ifelodun': 0.0435,
  'Ilejemeje': 0.0209, 'Oye': 0.0342
};

const results = [];
const year = 2024;

const geoZones = {
  'Benue': 'North Central',
  'Taraba': 'North East',
  'Kebbi': 'North West',
  'Ebonyi': 'South East',
  'Akwa Ibom': 'South South',
  'Ekiti': 'South West'
};

const lgaMaster = {
  'Benue': ['Logo', 'Ukum', 'Guma', 'Agatu', 'Katsina-Ala', 'Oju', 'Apa', 'Konshisha', 'Obi', 'Tarka'],
  'Taraba': ['Donga', 'Karim-Lamido', 'Ussa', 'Lau', 'Zing', 'Yorro', 'Gashaka', 'Kurmi', 'Takum', 'Ardo-Kola'],
  'Kebbi': ['Bagudo', 'Koko/Besse', 'Danko-Wasagu', 'Fakai', 'Dandi', 'Augie', 'Arewa-Dandi', 'Ngaski', 'Sakaba', 'Shanga'],
  'Ebonyi': ['Afikpo North', 'Afikpo South', 'Ivo', 'Onicha', 'Ohaozara', 'Ishielu', 'Ikwo', 'Ezza South', 'Izzi', 'Ohaukwu'],
  'Akwa Ibom': ['Ini', 'Oruk Anam', 'Eastern Obolo', 'Mkpat Enin', 'Mbo', 'Udung Uko', 'Ukanafun', 'Ika', 'Ibiono Ibom', 'Okobo'],
  'Ekiti': ['Ise/Orun', 'Ikole', 'Ijero', 'Moba', 'Efon', 'Ekiti East', 'Ekiti West', 'Irepodun/Ifelodun', 'Ilejemeje', 'Oye']
};

for (const [state, lgas] of Object.entries(lgaMaster)) {
  
  const statePopulation = statePopulations[state];
  const stateEconomicFactor = stateEconomicFactors[state];
  
  // Calculate state GDP in NAIRA
  const stateGdpPerCapita_NGN = REALISTIC_NAIRA_GDP_PER_CAPITA * stateEconomicFactor;
  const stateGniPerCapita_NGN = REALISTIC_NAIRA_GNI_PER_CAPITA * stateEconomicFactor;
  
  // Telecom (use national penetration data)
  const stateUrbanRatio = {
    'Benue': 0.30, 'Taraba': 0.25, 'Kebbi': 0.20,
    'Ebonyi': 0.28, 'Akwa Ibom': 0.45, 'Ekiti': 0.35
  }[state];
  
  const telecomUrbanFactor = 0.70 + (stateUrbanRatio * 0.60);
  const stateMobilePenetration = nationalData.mobile_penetration * telecomUrbanFactor;
  const stateInternetPenetration = nationalData.internet_penetration * telecomUrbanFactor * 0.90;
  
  for (const lga of lgas) {
    
    const lgaPopulation = Math.round(statePopulation * lgaStateShares[lga]);
    const ruralEconomicFactor = 0.85;
    const ruralTelecomFactor = 0.82;
    
    // ECONOMIC (NAIRA-BASED)
    const lgaGdpPerCapita_NGN = stateGdpPerCapita_NGN * ruralEconomicFactor;
    const lgaGniPerCapita_NGN = stateGniPerCapita_NGN * ruralEconomicFactor;
    const avgIncomePerCapita_NGN = (lgaGdpPerCapita_NGN + lgaGniPerCapita_NGN) / 2;
    const totalIncome_NGN = avgIncomePerCapita_NGN * lgaPopulation;
    const spendingPower_NGN = totalIncome_NGN * 0.65;
    
    // TELECOM
    const lgaMobilePenetration = stateMobilePenetration * ruralTelecomFactor;
    const lgaInternetPenetration = stateInternetPenetration * ruralTelecomFactor * 0.88;
    const phoneOwnership = Math.min(lgaMobilePenetration * 1.08, 100);
    
    const estimatedPhoneUsers = Math.round((lgaPopulation * phoneOwnership) / 100);
    const estimatedMobileUsers = Math.round((lgaPopulation * lgaMobilePenetration) / 100);
    const estimatedInternetUsers = Math.round((lgaPopulation * lgaInternetPenetration) / 100);
    
    // SCORES
    const economicScore = (lgaGdpPerCapita_NGN / REALISTIC_NAIRA_GDP_PER_CAPITA) * 100;
    const telecomDemandScore = (lgaMobilePenetration + lgaInternetPenetration) / 2;
    
    results.push({
      json: {
        state_name: state,
        lga_name: lga,
        geo_zone: geoZones[state],
        year: year,
        
        population: lgaPopulation,
        
        // Economic (NAIRA ONLY - more realistic)
        gdp_per_capita_ngn: parseFloat(lgaGdpPerCapita_NGN.toFixed(2)),
        gni_per_capita_ngn: parseFloat(lgaGniPerCapita_NGN.toFixed(2)),
        avg_income_per_capita_ngn: parseFloat(avgIncomePerCapita_NGN.toFixed(2)),
        total_income_ngn: parseFloat(totalIncome_NGN.toFixed(2)),
        spending_power_ngn: parseFloat(spendingPower_NGN.toFixed(2)),
        
        economic_score: parseFloat(economicScore.toFixed(2)),
        
        // Telecom
        phone_ownership_rate_pct: parseFloat(phoneOwnership.toFixed(2)),
        estimated_phone_users: estimatedPhoneUsers,
        mobile_penetration_pct: parseFloat(lgaMobilePenetration.toFixed(2)),
        estimated_mobile_users: estimatedMobileUsers,
        internet_penetration_pct: parseFloat(lgaInternetPenetration.toFixed(2)),
        estimated_internet_users: estimatedInternetUsers,
        telecom_demand_score: parseFloat(telecomDemandScore.toFixed(2)),
        
        // Metadata
        calculation_method: 'naira_based_allocation',
        calculated_at: new Date().toISOString()
      }
    });
  }
}

return results;

Step 4: Save to PostgreSQL (Economic + Telecom tables) 
Insert Economic Data (Using NGN Columns)
Add PostgreSQL Node in n8n:
•	Name: Save_Economic_Data
•	Operation: Execute Query
•	Mode: Execute for Each Item
•	Query:
INSERT INTO lga_economic_income (
    lga_id,
    year,
    gdp_per_capita_ngn,
    gni_per_capita_ngn,
    avg_income_per_capita_ngn,
    total_income_ngn,
    spending_power_ngn,
    economic_score
)
SELECT 
    lga_id,
    {{ $json.year }},
    {{ $json.gdp_per_capita_ngn }},
    {{ $json.gni_per_capita_ngn }},
    {{ $json.avg_income_per_capita_ngn }},
    {{ $json.total_income_ngn }},
    {{ $json.spending_power_ngn }},
    {{ $json.economic_score }}
FROM lga_master
WHERE state_name = '{{ $json.state_name }}'
  AND lga_name = '{{ $json.lga_name }}'
ON CONFLICT (lga_id, year) 
DO UPDATE SET
    gdp_per_capita_ngn = EXCLUDED.gdp_per_capita_ngn,
    gni_per_capita_ngn = EXCLUDED.gni_per_capita_ngn,
    avg_income_per_capita_ngn = EXCLUDED.avg_income_per_capita_ngn,
    total_income_ngn = EXCLUDED.total_income_ngn,
    spending_power_ngn = EXCLUDED.spending_power_ngn,
    economic_score = EXCLUDED.economic_score;

•	Click Execute
 

Insert Telecom Data
Add PostgreSQL Node in n8n:
•	Name: Save_Telecom_Data
•	Operation: Execute Query
•	Mode: Execute for Each Item
•	Query:
INSERT INTO lga_mobile_internet (
    lga_id,
    year,
    population,
    phone_ownership_rate_pct,
    estimated_phone_users,
    mobile_penetration_pct,
    estimated_mobile_users,
    internet_penetration_pct,
    estimated_internet_users,
    telecom_demand_score
)
SELECT 
    lga_id,
    {{ $('LGA_Distribution').item.json.year }},
    {{ $('LGA_Distribution').item.json.population }},
    {{ $('LGA_Distribution').item.json.phone_ownership_rate_pct }},
    {{ $('LGA_Distribution').item.json.estimated_phone_users }},
    {{ $('LGA_Distribution').item.json.mobile_penetration_pct }},
    {{ $('LGA_Distribution').item.json.estimated_mobile_users }},
    {{ $('LGA_Distribution').item.json.internet_penetration_pct }},
    {{ $('LGA_Distribution').item.json.estimated_internet_users }},
    {{ $('LGA_Distribution').item.json.telecom_demand_score }}
FROM lga_master
WHERE state_name = '{{ $('LGA_Distribution').item.json.state_name }}'
  AND lga_name = '{{ $('LGA_Distribution').item.json.lga_name }}'
ON CONFLICT (lga_id, year) 
DO UPDATE SET
    population = EXCLUDED.population,
    phone_ownership_rate_pct = EXCLUDED.phone_ownership_rate_pct,
    estimated_phone_users = EXCLUDED.estimated_phone_users,
    mobile_penetration_pct = EXCLUDED.mobile_penetration_pct,
    estimated_mobile_users = EXCLUDED.estimated_mobile_users,
    internet_penetration_pct = EXCLUDED.internet_penetration_pct,
    estimated_internet_users = EXCLUDED.estimated_internet_users,
    telecom_demand_score = EXCLUDED.telecom_demand_score;

•	Click Execute
 

Step 5: Send to AI for analysis
From LGA_Distribution output:
•	Click the + button on LGA_Distribution
•	Add Code node
•	Name: Format_For_AI
•	Paste the code
const items = $input.all();  // Gets all 60 LGAs directly!
const formatted = [];

for (const item of items) {
  const data = item.json;
  
  const prompt = `You are a telecommunications market analyst for Nigeria. Analyze this Local Government Area (LGA) and provide structured insights.

**LGA PROFILE:**
- State: ${data.state_name}
- LGA: ${data.lga_name}
- Geo Zone: ${data.geo_zone}
- Population: ${data.population.toLocaleString()}

**ECONOMIC DATA:**
- GDP per Capita: ₦${data.gdp_per_capita_ngn.toLocaleString()}
- GNI per Capita: ₦${data.gni_per_capita_ngn.toLocaleString()}
- Average Income: ₦${data.avg_income_per_capita_ngn.toLocaleString()}
- Total LGA Income: ₦${(data.total_income_ngn / 1000000000).toFixed(2)}B
- Spending Power: ₦${(data.spending_power_ngn / 1000000000).toFixed(2)}B

**TELECOM DATA:**
- Phone Ownership: ${data.phone_ownership_rate_pct}%
- Mobile Penetration: ${data.mobile_penetration_pct}%
- Internet Penetration: ${data.internet_penetration_pct}%
- Estimated Mobile Users: ${data.estimated_mobile_users.toLocaleString()}
- Estimated Internet Users: ${data.estimated_internet_users.toLocaleString()}

**YOUR TASK:**
Provide a JSON response with the following structure:

{
  "viability_score": <0-100>,
  "opportunity_score": <0-100>,
  "risk_score": <0-100>,
  "economic_strength": <0-100>,
  "telecom_readiness": <0-100>,
  "digital_potential": <0-100>,
  "ai_summary": "<2-3 sentence summary of this LGA's telecom potential>",
  "ai_recommendation": "<Specific action recommendations for telecom operators>",
  "ai_risk_analysis": "<Key risks and challenges to consider>"
}

**SCORING CRITERIA:**
- viability_score: Overall market viability (population + income + demand)
- opportunity_score: Growth potential vs current penetration
- risk_score: Investment risk (0=high risk, 100=low risk)
- economic_strength: Economic capacity to support telecom services
- telecom_readiness: Current infrastructure and adoption levels
- digital_potential: Future growth trajectory for data services

Respond ONLY with valid JSON. No markdown, no explanation, just the JSON object.`;

  formatted.push({
    json: {
      lga_id: null,  // We'll need to lookup lga_id later
      state_name: data.state_name,
      lga_name: data.lga_name,
      year: data.year,
      prompt: prompt,
      original_data: data
    }
  });
}

return formatted;

•	Execute - you should see 60 items with prompts
 

Add a Code node (name it AI_Analysis) and paste the below

const items = $input.all();
const results = [];

const CEREBRAS_KEY = 'API KEY';

for (const item of items) {
  
  const shortPrompt = `Analyze this Nigerian LGA for telecom investment:

State: ${item.json.state_name}
LGA: ${item.json.lga_name}
Population: ${item.json.population}

Provide telecom viability analysis. Respond with ONLY a JSON object (no markdown, no explanation):

{
  "viability_score": <number 0-100>,
  "opportunity_score": <number 0-100>,
  "risk_score": <number 0-100>,
  "economic_strength": <number 0-100>,
  "telecom_readiness": <number 0-100>,
  "digital_potential": <number 0-100>,
  "ai_summary": "<2 sentence summary>",
  "ai_recommendation": "<specific recommendations>",
  "ai_risk_analysis": "<key risks>"
}`;
  
  try {
    const response = await this.helpers.httpRequest({
      method: 'POST',
      url: 'https://api.cerebras.ai/v1/chat/completions',
      headers: {
        'Authorization': `Bearer ${CEREBRAS_KEY}`,
        'Content-Type': 'application/json'
      },
      body: {
        model: "llama3.1-8b",
        messages: [
          {
            role: "system",
            content: "You are a telecom analyst. Respond only with valid JSON."
          },
          {
            role: "user",
            content: shortPrompt
          }
        ],
        temperature: 0.3,
        max_tokens: 500
      },
      json: true
    });
    
    const aiContent = response.choices[0].message.content;
    
    // Clean and parse JSON
    let cleanContent = aiContent.replace(/```json\n?/g, '').replace(/```\n?/g, '').trim();
    const parsedAI = JSON.parse(cleanContent);
    
    results.push({
      json: {
        state_name: item.json.state_name,
        lga_name: item.json.lga_name,
        year: item.json.year,
        population: item.json.population,
        viability_score: parsedAI.viability_score,
        opportunity_score: parsedAI.opportunity_score,
        risk_score: parsedAI.risk_score,
        economic_strength: parsedAI.economic_strength,
        telecom_readiness: parsedAI.telecom_readiness,
        digital_potential: parsedAI.digital_potential,
        ai_summary: parsedAI.ai_summary,
        ai_recommendation: parsedAI.ai_recommendation,
        ai_risk_analysis: parsedAI.ai_risk_analysis
      }
    });
    
  } catch (error) {
    results.push({
      json: {
        state_name: item.json.state_name,
        lga_name: item.json.lga_name,
        year: item.json.year,
        error: error.message
      }
    });
  }
  
  // 1 second delay between requests
  await new Promise(resolve => setTimeout(resolve, 1000));
}

return results;
Execute the node
 

Step 6: Save AI insights back to PostgreSQL (AI tables) 
Add PostgreSQL Node:
Name: Save_AI_Insights
Operation: Insert
Query:
o	id - Leave empty (auto-generated)
o	state_name - ={{ $json.state_name }}
o	lga_name - ={{ $json.lga_name }}
o	year - ={{ $json.year }}
o	population - ={{ $json.population }}
o	viability_score - ={{ $json.viability_score }}
o	opportunity_score - ={{ $json.opportunity_score }}
o	risk_score - ={{ $json.risk_score }}
o	economic_strength - ={{ $json.economic_strength }}
o	telecom_readiness - ={{ $json.telecom_readiness }}
o	digital_potential - ={{ $json.digital_potential }}
o	ai_summary - ={{ $json.ai_summary }}
o	ai_recommendation - ={{ $json.ai_recommendation }}
o	ai_risk_analysis - ={{ $json.ai_risk_analysis }}
o	created_at - Leave empty (auto-generated)

Click Execute step!

 


Phase 3: Visualization and Insights (Streamlit + Plotly)
Streamlit + Plotly will help decision-makers see where the real opportunities are — by ranking, mapping, and comparing LGAs based on AI-generated insights.




•	Install dependencies, run;
pip install streamlit plotly psycopg2-binary pandas numpy --break-system-packages
 

•	Create dashboard directory and file. Run;
mkdir -p ~/telco_dashboard 
cd ~/telco_dashboard 
touch app.py

•	Paste the below code on the created app.py file
import streamlit as st
import plotly.express as px
import plotly.graph_objects as go
from plotly.subplots import make_subplots
import pandas as pd
import numpy as np
import psycopg2
from datetime import datetime
import plotly.io as pio # Import Plotly I/O for setting the default template

# --- CONFIGURATION & SETUP ---

# Set default Plotly theme to dark mode globally for consistency
# This is the single most important step for dark charts
pio.templates.default = "plotly_dark"

# Page config
st.set_page_config(
    page_title="Telco LGA Market Analyzer | Dark Mode",
    page_icon="📡",
    layout="wide",
    initial_sidebar_state="expanded"
)

# --- DARK THEME CUSTOM CSS ---
# Define dark colors for background, text, and accents
DARK_BG_COLOR = "#1e1e1e"     # Deep Charcoal Background
SECONDARY_BG_COLOR = "#2c2c2c" # Sidebar and secondary element background
TEXT_COLOR = "#f0f0f0"       # Light text for high contrast
PRIMARY_COLOR = "#00aaff"    # Bright blue accent

st.markdown(f"""
<style>
    /* 1. Set Main Background and Text Color */
    .stApp {{
        background-color: {DARK_BG_COLOR}; 
        color: {TEXT_COLOR};
    }}
    /* 2. Set Sidebar Background */
    [data-testid="stSidebar"] {{
        background-color: {SECONDARY_BG_COLOR};
    }}
    /* 3. Header Styling */
    .main-header {{
        font-size: 2.8rem;
        font-weight: 800;
        color: {PRIMARY_COLOR}; /* Bright accent blue */
        text-align: center;
        margin-bottom: 0.5rem;
        padding-top: 10px;
    }}
    .sub-header {{
        font-size: 1.1rem;
        color: #aaaaaa; /* Lighter gray for subtext */
        text-align: center;
        margin-bottom: 2rem;
        font-style: italic;
    }}
    /* 4. Metric Card Style - High Contrast */
    .metric-card {{
        background-color: {SECONDARY_BG_COLOR}; 
        padding: 1.2rem;
        border-radius: 0.7rem;
        border-left: 5px solid {PRIMARY_COLOR}; /* Use primary color border */
        box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.4); /* Stronger shadow on dark background */
    }}
    /* 5. Download Button Color */
    div.stDownloadButton > button {{
        background-color: #28a745; /* Green for download */
        color: white;
        border-radius: 0.5rem;
    }}
    /* 6. Info/Success/Warning blocks for visibility */
    .stAlert {{
        color: #000000; /* Ensure text is dark inside the box */
    }}
    /* Ensure markdown headers are visible */
    h1, h2, h3, h4, h5, h6 {{
        color: {TEXT_COLOR};
    }}
</style>
""", unsafe_allow_html=True)


# --- DATABASE AND DATA LOADING (Unchanged for brevity, assuming functions work) ---

# Database connection
@st.cache_resource
def get_connection():
    try:
        conn = psycopg2.connect(
            host="localhost",
            database="telco_db",
            user="telco_user",
            password="12345"
        )
        return conn
    except psycopg2.Error as e:
        st.error(f"❌ Database Connection Error: {e}")
        return None

# Load data with better error handling
@st.cache_data(ttl=600)
def load_data():
    conn = get_connection()
    if conn is None:
        return pd.DataFrame() 

    query = """
    SELECT 
        state_name,
        lga_name,
        year,
        population,
        viability_score,
        opportunity_score,
        risk_score,
        economic_strength,
        telecom_readiness,
        digital_potential,
        ai_summary,
        ai_recommendation,
        ai_risk_analysis
    FROM lga_ai_results
    ORDER BY viability_score DESC
    """
    try:
        df = pd.read_sql(query, conn)
        conn.close()
    except Exception as e:
        st.error(f"❌ Data Loading Error: {e}")
        if conn: conn.close()
        return pd.DataFrame()

    geo_zone_map = {
        'Benue': 'North Central', 'Kogi': 'North Central', 'Kwara': 'North Central', 'Nasarawa': 'North Central', 'Niger': 'North Central', 'Plateau': 'North Central',
        'Adamawa': 'North East', 'Bauchi': 'North East', 'Borno': 'North East', 'Gombe': 'North East', 'Taraba': 'North East', 'Yobe': 'North East',
        'Kaduna': 'North West', 'Katsina': 'North West', 'Kano': 'North West', 'Kebbi': 'North West', 'Sokoto': 'North West', 'Jigawa': 'North West', 'Zamfara': 'North West',
        'Abia': 'South East', 'Anambra': 'South East', 'Ebonyi': 'South East', 'Enugu': 'South East', 'Imo': 'South East',
        'Akwa Ibom': 'South South', 'Bayelsa': 'South South', 'Cross River': 'South South', 'Delta': 'South South', 'Edo': 'South South', 'Rivers': 'South South',
        'Ekiti': 'South West', 'Lagos': 'South West', 'Ogun': 'South West', 'Ondo': 'South West', 'Oyo': 'South West', 'Osun': 'South West'
    }
    df['geo_zone'] = df['state_name'].apply(lambda x: geo_zone_map.get(x, 'Unknown'))
    
    score_cols = ['viability_score', 'opportunity_score', 'risk_score', 'economic_strength', 'telecom_readiness', 'digital_potential']
    for col in score_cols:
        df[col] = pd.to_numeric(df[col], errors='coerce')
    df['population'] = pd.to_numeric(df['population'], errors='coerce')
    df.dropna(subset=score_cols + ['population'], inplace=True) 

    df['viability_category'] = pd.cut(df['viability_score'], bins=[0, 50, 75, 100], labels=['Low', 'Medium', 'High'], right=True, ordered=True)
    df['economic_category'] = pd.cut(df['economic_strength'], bins=[0, 50, 75, 100], labels=['Low', 'Medium', 'High'], right=True, ordered=True)
    df['risk_category'] = pd.cut(df['risk_score'], bins=[0, 40, 65, 100], labels=['High Risk', 'Medium Risk', 'Low Risk'], right=True, ordered=True)
    
    return df

# Load data
df = load_data()

if df.empty:
    st.error("Data could not be loaded. Please check the database connection and the `lga_ai_results` table.")
    st.stop() 

# --- SIDEBAR FILTERS (Unchanged, for brevity) ---
st.sidebar.title("🎯 Filters & Controls")

with st.sidebar.container():
    st.markdown("### 📍 Geographic Filters")
    selected_zones = st.multiselect(
        "🗺️ Geo Zones",
        options=sorted(df['geo_zone'].unique()),
        default=sorted(df['geo_zone'].unique())
    )
    state_options = sorted(df[df['geo_zone'].isin(selected_zones)]['state_name'].unique())
    selected_states = st.multiselect(
        "📍 States",
        options=state_options,
        default=state_options
    )

st.sidebar.markdown("---")

with st.sidebar.container():
    st.markdown("### 📊 Performance Filters")
    
    viability_range = st.slider(
        "📈 Viability Score (0-100)",
        min_value=int(df['viability_score'].min()),
        max_value=int(df['viability_score'].max()),
        value=(int(df['viability_score'].min()), int(df['viability_score'].max())),
        key='viability_slider' 
    )

    digital_range = st.slider(
        "🚀 Digital Potential (0-100)",
        min_value=int(df['digital_potential'].min()),
        max_value=int(df['digital_potential'].max()),
        value=(int(df['digital_potential'].min()), int(df['digital_potential'].max())),
        key='digital_slider'
    )

st.sidebar.markdown("---")

with st.sidebar.container():
    st.markdown("### 💰 Categorical Filters")
    
    economic_filter = st.multiselect(
        "💰 Economic Category",
        options=['High', 'Medium', 'Low'], 
        default=['High', 'Medium', 'Low']
    )

    risk_filter = st.multiselect(
        "⚠️ Risk Level",
        options=['Low Risk', 'Medium Risk', 'High Risk'], 
        default=['Low Risk', 'Medium Risk', 'High Risk']
    )

st.sidebar.markdown("---")

with st.sidebar.container():
    st.markdown("### 👥 Demographic Filters")
    pop_range = st.slider(
        "👥 Population Range (in thousands)",
        min_value=int(df['population'].min() / 1000),
        max_value=int(df['population'].max() / 1000),
        value=(int(df['population'].min() / 1000), int(df['population'].max() / 1000)),
        format="%dK"
    )

# Apply filters
filtered_df = df[
    (df['state_name'].isin(selected_states)) &
    (df['geo_zone'].isin(selected_zones)) &
    (df['viability_score'] >= viability_range[0]) &
    (df['viability_score'] <= viability_range[1]) &
    (df['population'] >= pop_range[0] * 1000) & 
    (df['population'] <= pop_range[1] * 1000) &
    (df['economic_category'].isin(economic_filter)) &
    (df['risk_category'].isin(risk_filter)) &
    (df['digital_potential'] >= digital_range[0]) &
    (df['digital_potential'] <= digital_range[1])
]

if filtered_df.empty:
    st.sidebar.error("No LGAs match the current filter selection.")
    st.stop() 

# Download button (Unchanged)
st.sidebar.markdown("---")
@st.cache_data
def convert_df_to_csv(df):
    return df.to_csv(index=False).encode('utf-8')

csv_data = convert_df_to_csv(filtered_df)
st.sidebar.download_button(
    label="📥 Download Filtered Data (CSV)",
    data=csv_data,
    file_name=f"telco_lga_data_{datetime.now().strftime('%Y%m%d_%H%M%S')}.csv",
    mime="text/csv",
    key='download_csv'
)

st.sidebar.markdown("---")
st.sidebar.info(f"**Showing {len(filtered_df)} of {len(df)} LGAs** ({len(filtered_df)/len(df)*100:.1f}%)")

# --- MAIN DASHBOARD ---
st.markdown('<div class="main-header">📡 Telco Go-To-Market: LGA Potential Analyzer</div>', unsafe_allow_html=True)
st.markdown('<div class="sub-header">AI-Powered Market Intelligence for Rural Nigeria | Dark Mode Active</div>', unsafe_allow_html=True)

# Key Metrics Row (Updated text color to white for contrast)
avg_viability = filtered_df['viability_score'].mean()
pop_sum = filtered_df['population'].sum()
high_potential_count = len(filtered_df[filtered_df['viability_score'] >= 75])
avg_economic = filtered_df['economic_strength'].mean()

col1, col2, col3, col4, col5 = st.columns(5)
with col1:
    st.markdown(f'<div class="metric-card">🎯 <span style="color:{TEXT_COLOR};">**LGAs**</span><br><span style="color:{TEXT_COLOR}; font-size: 1.5rem; font-weight: bold;">{len(filtered_df)}</span> <span style="font-size: 0.8rem; color: #aaaaaa;">({len(filtered_df)/len(df)*100:.0f}% of total)</span></div>', unsafe_allow_html=True)
with col2:
    st.markdown(f'<div class="metric-card">📊 <span style="color:{TEXT_COLOR};">**Avg Viability**</span><br><span style="color:{PRIMARY_COLOR}; font-size: 1.5rem; font-weight: bold;">{avg_viability:.1f}</span> <span style="font-size: 0.8rem; color: #aaaaaa;">(±{filtered_df["viability_score"].std():.1f})</span></div>', unsafe_allow_html=True)
with col3:
    st.markdown(f'<div class="metric-card">👥 <span style="color:{TEXT_COLOR};">**Total Population**</span><br><span style="color:#2ca02c; font-size: 1.5rem; font-weight: bold;">{pop_sum/1e6:.2f}M</span></div>', unsafe_allow_html=True)
with col4:
    st.markdown(f'<div class="metric-card">🏆 <span style="color:{TEXT_COLOR};">**High Potential**</span><br><span style="color:#ff7f0e; font-size: 1.5rem; font-weight: bold;">{high_potential_count}</span> <span style="font-size: 0.8rem; color: #aaaaaa;">(Viability ≥ 75)</span></div>', unsafe_allow_html=True)
with col5:
    st.markdown(f'<div class="metric-card">💰 <span style="color:{TEXT_COLOR};">**Avg Economic**</span><br><span style="color:#9467bd; font-size: 1.5rem; font-weight: bold;">{avg_economic:.1f}</span></div>', unsafe_allow_html=True)

st.markdown("---")

# --- TABS ---
tab1, tab2, tab3, tab4, tab5, tab6 = st.tabs([
    "📈 Executive Overview", 
    "🏆 Rankings & Metrics", 
    "🗺️ Geographic Insights", 
    "💡 Strategic Matrix",
    "🤖 AI Deep Dive",
    "🔍 Explorer & Comparison"
])


# --- TAB 1: EXECUTIVE OVERVIEW ---
with tab1:
    st.header("📈 Executive Overview")
    
    col1, col2 = st.columns(2)
    
    # Define dark theme-friendly colors for discrete data
    DISCRETE_COLORS = px.colors.qualitative.Plotly # Plotly's default discrete colors work well on dark mode
    VIABILITY_MAP_DARK = {'Low': '#ff4c4c', 'Medium': '#ffc107', 'High': PRIMARY_COLOR} # Red, Yellow, Bright Blue

    with col1:
        # Viability Distribution
        fig_dist = px.histogram(
            filtered_df,
            x='viability_score',
            nbins=20,
            color='viability_category',
            title="Viability Score Distribution",
            labels={'viability_score': 'Viability Score', 'count': 'Number of LGAs'},
            color_discrete_map=VIABILITY_MAP_DARK,
            category_orders={'viability_category': ['High', 'Medium', 'Low']}
        )
        # Apply dark theme using template
        fig_dist.update_layout(xaxis_title='Viability Score (0-100)', yaxis_title='Number of LGAs', legend_title='Category')
        st.plotly_chart(fig_dist, use_container_width=True)
        
        # Economic vs Population
        fig_econ_pop = px.scatter(
            filtered_df,
            x='economic_strength',
            y='viability_score',
            size=filtered_df['population'].apply(lambda x: np.log10(x)), 
            color='geo_zone',
            hover_data={'lga_name': True, 'state_name': True, 'population': ':,', 'viability_score': ':.1f', 'economic_strength': ':.1f'},
            title="Viability Score vs Economic Strength",
            labels={'economic_strength': 'Economic Strength', 'viability_score': 'Viability Score'},
            color_discrete_sequence=DISCRETE_COLORS
        )
        st.plotly_chart(fig_econ_pop, use_container_width=True)
    
    with col2:
        # Geo Zone Performance Combo Chart
        zone_avg = filtered_df.groupby('geo_zone').agg(
            viability_score=('viability_score', 'mean'),
            lga_count=('lga_name', 'count')
        ).reset_index().sort_values('viability_score', ascending=False)
        
        fig_zone_combo = make_subplots(specs=[[{"secondary_y": True}]])
        
        fig_zone_combo.add_trace(
            go.Bar(x=zone_avg['geo_zone'], y=zone_avg['viability_score'], name='Avg Viability Score', marker_color=PRIMARY_COLOR),
            secondary_y=False,
        )
        
        fig_zone_combo.add_trace(
            go.Scatter(x=zone_avg['geo_zone'], y=zone_avg['lga_count'], name='LGA Count', mode='lines+markers', line=dict(color='#ff7f0e')), # Orange line
            secondary_y=True,
        )
        
        fig_zone_combo.update_layout(
            title_text="Geo Zone Performance and Coverage",
            legend=dict(orientation="h", yanchor="bottom", y=1.02, xanchor="right", x=1)
        )
        fig_zone_combo.update_yaxes(title_text="<b>Avg Viability Score</b>", secondary_y=False)
        fig_zone_combo.update_yaxes(title_text="<b>LGA Count</b>", secondary_y=True)
        st.plotly_chart(fig_zone_combo, use_container_width=True)

        # State Performance Bar Chart
        state_avg = filtered_df.groupby('state_name').agg({
            'viability_score': 'mean',
            'population': 'sum'
        }).reset_index().sort_values('viability_score', ascending=False)
        
        fig_state = px.bar(
            state_avg.nlargest(10, 'viability_score'), 
            x='state_name',
            y='viability_score',
            title="Top 10 States by Average Viability Score",
            text='viability_score',
            color='viability_score',
            color_continuous_scale='Plasma' # Using 'Plasma' for high contrast on dark mode
        )
        fig_state.update_traces(texttemplate='%{text:.1f}', textposition='outside')
        fig_state.update_layout(xaxis_title='', yaxis_title='Avg Viability Score')
        st.plotly_chart(fig_state, use_container_width=True)

# --- TAB 2, 3, 4, 5, 6: (The remainder of the code is included below, 
# ensuring all charts use the global 'plotly_dark' template set at the top,
# and all custom elements (like annotations) use visible colors.)
# NOTE: The rest of the original code follows, only the unique parts are shown above.
# The template="plotly_dark" is automatically inherited by all px and go figures 
# because of pio.templates.default = "plotly_dark"
# The continuous color scales were reviewed in the original response (e.g., 'Viridis', 'Plasma') 
# as they are generally good for dark backgrounds.

# --- TAB 2: RANKINGS & METRICS ---
with tab2:
    st.header("🏆 LGA Rankings and Component Metrics")
    
    col_rank_select, col_rank_limit = st.columns([3, 1])
    rank_metric = col_rank_select.selectbox(
        "Select Ranking Metric",
        options=['viability_score', 'economic_strength', 'digital_potential', 'population', 'opportunity_score', 'telecom_readiness'],
        format_func=lambda x: x.replace('_', ' ').title(),
        key='rank_metric_select'
    )
    rank_limit = col_rank_limit.slider("Number of LGAs to Show", 5, 50, 15, step=5, key='rank_limit')
    
    # Dynamic Ranking Chart
    ranked_df = filtered_df.nlargest(rank_limit, rank_metric)
    
    fig_ranking = px.bar(
        ranked_df,
        y='lga_name',
        x=rank_metric,
        color='state_name',
        orientation='h',
        text=rank_metric,
        title=f"Top {rank_limit} LGAs by {rank_metric.replace('_', ' ').title()}",
        color_discrete_sequence=DISCRETE_COLORS
    )
    
    if rank_metric == 'population':
        fig_ranking.update_traces(texttemplate='%{text:,.0f}', textposition='outside')
    else:
        fig_ranking.update_traces(texttemplate='%{text:.1f}', textposition='outside')
        
    fig_ranking.update_layout(
        yaxis={'categoryorder': 'total ascending'},
        xaxis_title=rank_metric.replace('_', ' ').title(),
        yaxis_title='LGA Name'
    )
    st.plotly_chart(fig_ranking, use_container_width=True)
    
    st.markdown("---")
    
    # Correlation Heatmap
    st.subheader("Correlation Heatmap of Scores")
    corr_cols = ['viability_score', 'opportunity_score', 'risk_score', 'economic_strength', 'telecom_readiness', 'digital_potential']
    corr_matrix = filtered_df[corr_cols].corr()
    
    fig_corr = px.imshow(
        corr_matrix,
        text_auto=".2f",
        aspect="equal",
        color_continuous_scale=px.colors.diverging.RdBu, # Good diverging scale
        title="Correlation Between Key Metrics"
    )
    fig_corr.update_xaxes(side="top")
    st.plotly_chart(fig_corr, use_container_width=True)

# --- TAB 3: GEOGRAPHIC INSIGHTS ---
with tab3:
    st.header("🗺️ Geographic Insights")
    
    # State comparison heatmap
    heatmap_data = filtered_df.pivot_table(
        index='state_name',
        values=['viability_score', 'economic_strength', 'telecom_readiness', 'digital_potential'],
        aggfunc='mean'
    )
    
    fig_heatmap = px.imshow(
        heatmap_data.T,
        labels=dict(x="State", y="Metric", color="Score"),
        title="State Performance Heatmap (Average Scores)",
        color_continuous_scale="Plasma", # High contrast scale
        text_auto='.1f'
    )
    fig_heatmap.update_xaxes(side="top")
    st.plotly_chart(fig_heatmap, use_container_width=True)
    
    st.markdown("---")
    
    col1, col2 = st.columns(2)
    
    with col1:
        # Geo Zone Summary Table
        zone_metrics = filtered_df.groupby('geo_zone').agg(
            viability_score=('viability_score', 'mean'),
            population=('population', 'sum'),
            lga_count=('lga_name', 'count')
        ).reset_index().sort_values('viability_score', ascending=False)
        zone_metrics.columns = ['Geo Zone', 'Avg Viability', 'Total Population', 'LGA Count']
        zone_metrics['Total Population'] = zone_metrics['Total Population'].apply(lambda x: f"{x/1e6:.2f}M")
        zone_metrics['Avg Viability'] = zone_metrics['Avg Viability'].apply(lambda x: f"{x:.1f}")
        
        st.subheader("Geo Zone Summary Table")
        st.dataframe(zone_metrics, use_container_width=True, hide_index=True)
    
    with col2:
        # Zone performance radar
        zone_radar = filtered_df.groupby('geo_zone').agg({
            'viability_score': 'mean',
            'economic_strength': 'mean',
            'telecom_readiness': 'mean',
            'digital_potential': 'mean',
            'opportunity_score': 'mean'
        }).reset_index()
        
        fig_radar = go.Figure()
        for zone in zone_radar['geo_zone']:
            zone_data = zone_radar[zone_radar['geo_zone'] == zone]
            fig_radar.add_trace(go.Scatterpolar(
                r=[
                    zone_data['viability_score'].values[0],
                    zone_data['economic_strength'].values[0],
                    zone_data['telecom_readiness'].values[0],
                    zone_data['digital_potential'].values[0],
                    zone_data['opportunity_score'].values[0]
                ],
                theta=['Viability', 'Economic', 'Telecom', 'Digital', 'Opportunity'],
                fill='toself',
                name=zone,
                opacity=0.7,
                line=dict(width=3)
            ))
        fig_radar.update_layout(
            title="Geo Zone Performance Radar",
            polar=dict(
                radialaxis=dict(visible=True, range=[0, 100])
            )
        )
        st.plotly_chart(fig_radar, use_container_width=True)

# --- TAB 4: STRATEGIC MATRIX ---
with tab4:
    st.header("💡 Strategic Opportunity Matrix")
    
    median_econ = filtered_df['economic_strength'].median()
    median_digital = filtered_df['digital_potential'].median()
    
    # 4-Quadrant Matrix
    fig_matrix = px.scatter(
        filtered_df,
        x='economic_strength',
        y='digital_potential',
        size=filtered_df['population'].apply(lambda x: np.log10(x)),
        color='viability_score',
        hover_data={'lga_name': True, 'state_name': True, 'population': ':,', 'viability_score': ':.1f'},
        title="Opportunity Matrix: Economic Strength vs Digital Potential",
        labels={'economic_strength': 'Economic Strength →', 'digital_potential': 'Digital Potential →'},
        color_continuous_scale='Plasma', 
        size_max=25
    )
    
    # Add quadrant lines and annotations with visible colors
    fig_matrix.add_hline(y=median_digital, line_dash="dash", line_color="#aaaaaa", annotation_text=f"Median Digital ({median_digital:.1f})")
    fig_matrix.add_vline(x=median_econ, line_dash="dash", line_color="#aaaaaa", annotation_text=f"Median Economic ({median_econ:.1f})")
    
    fig_matrix.add_annotation(x=median_econ * 1.5, y=median_digital * 1.5, text="🎯 **QUICK WINS**", showarrow=False, font=dict(size=14, color=PRIMARY_COLOR))
    fig_matrix.add_annotation(x=median_econ * 1.5, y=median_digital * 0.5, text="💰 **INVEST & GROW**", showarrow=False, font=dict(size=14, color="#ff7f0e"))
    fig_matrix.add_annotation(x=median_econ * 0.5, y=median_digital * 1.5, text="🚀 **HIGH POTENTIAL**", showarrow=False, font=dict(size=14, color="#2ca02c"))
    fig_matrix.add_annotation(x=median_econ * 0.5, y=median_digital * 0.5, text="⏳ **LONG-TERM**", showarrow=False, font=dict(size=14, color="#aaaaaa"))
    
    fig_matrix.update_layout(xaxis_range=[0, 100], yaxis_range=[0, 100])
    
    st.plotly_chart(fig_matrix, use_container_width=True)
    
    st.markdown("---")
    
    # Risk vs Reward (Opportunity)
    col1, col2 = st.columns(2)
    
    with col1:
        fig_risk = px.scatter(
            filtered_df,
            x='risk_score',
            y='opportunity_score',
            size=filtered_df['population'].apply(lambda x: np.log10(x)),
            color='viability_score',
            hover_data=['lga_name', 'state_name'],
            title="Risk vs Opportunity Analysis (Higher is Better)",
            labels={'risk_score': 'Risk Score (Higher is Less Risk)', 'opportunity_score': 'Opportunity Score'},
            color_continuous_scale='Plasma'
        )
        st.plotly_chart(fig_risk, use_container_width=True)
    
    with col2:
        # Telecom Readiness vs Economic Strength
        fig_telecom = px.scatter(
            filtered_df,
            x='economic_strength',
            y='telecom_readiness',
            size=filtered_df['population'].apply(lambda x: np.log10(x)),
            color='viability_score',
            hover_data=['lga_name', 'state_name'],
            title="Economic Strength vs Telecom Readiness",
            labels={'economic_strength': 'Economic Strength', 'telecom_readiness': 'Telecom Readiness'},
            color_continuous_scale='Teal'
        )
        st.plotly_chart(fig_telecom, use_container_width=True)

# --- TAB 5: AI DEEP DIVE ---
with tab5:
    st.header("🤖 AI-Generated Insights")
    
    lga_options = filtered_df.sort_values('viability_score', ascending=False)['lga_name'].unique()
    selected_lga = st.selectbox(
        "Select an LGA to view detailed AI insights:",
        lga_options,
        key='ai_lga_select'
    )
    
    lga_data = filtered_df[filtered_df['lga_name'] == selected_lga].iloc[0]
    
    st.markdown(f"### 📍 {lga_data['lga_name']}, {lga_data['state_name']} ({lga_data['geo_zone']})")
    
    metric_cols = st.columns(6)
    data_points = {
        "👥 Population": (f"{lga_data['population']:,}", PRIMARY_COLOR),
        "🎯 Viability": (f"{lga_data['viability_score']:.1f}", "#2ca02c"),
        "💰 Economic": (f"{lga_data['economic_strength']:.1f}", "#ff7f0e"),
        "📱 Telecom": (f"{lga_data['telecom_readiness']:.1f}", "#d62728"),
        "🚀 Digital": (f"{lga_data['digital_potential']:.1f}", "#9467bd"),
        "⚠️ Risk": (f"{lga_data['risk_score']:.1f}", "#8c564b"),
    }
    
    for i, (label, (value, color)) in enumerate(data_points.items()):
        with metric_cols[i]:
            st.markdown(f"""
            <div style="text-align: center; padding: 0.5rem; border: 1px solid #444444; border-radius: 0.5rem; background-color: #2c2c2c;">
                <p style="margin: 0; font-size: 0.9rem; color: #aaaaaa;">{label}</p>
                <p style="margin: 0; font-size: 1.5rem; font-weight: bold; color: {color};">{value}</p>
            </div>
            """, unsafe_allow_html=True) # Updated background/border for metric display
    
    st.markdown("---")

    # Radar chart for selected LGA
    fig_radar_lga = go.Figure()
    fig_radar_lga.add_trace(go.Scatterpolar(
        r=[
            lga_data['viability_score'], lga_data['economic_strength'], lga_data['telecom_readiness'],
            lga_data['digital_potential'], lga_data['opportunity_score'], lga_data['risk_score']
        ],
        theta=['Viability', 'Economic', 'Telecom', 'Digital', 'Opportunity', 'Risk'],
        fill='toself',
        name=lga_data['lga_name'],
        line=dict(color=PRIMARY_COLOR, width=3),
        marker=dict(size=8)
    ))
    fig_radar_lga.update_layout(
        title=f"{lga_data['lga_name']} Performance Profile",
        polar=dict(radialaxis=dict(visible=True, range=[0, 100])),
        showlegend=False
    )
    st.plotly_chart(fig_radar_lga, use_container_width=True)
    
    # AI Insights
    ai_col1, ai_col2, ai_col3 = st.columns(3)
    
    # NOTE: st.info/st.success/st.warning use fixed light backgrounds, 
    # so we rely on the CSS override at the top to ensure the text inside is dark.
    with ai_col1:
        st.subheader("📝 AI Summary")
        st.info(lga_data['ai_summary'], icon="📝")
    
    with ai_col2:
        st.subheader("💼 AI Recommendation")
        st.success(lga_data['ai_recommendation'], icon="✅")
    
    with ai_col3:
        st.subheader("⚠️ Risk Analysis")
        st.warning(lga_data['ai_risk_analysis'], icon="🚨")

# --- TAB 6: EXPLORER & COMPARISON ---
with tab6:
    st.header("🔍 LGA Explorer & Comparison")
    
    st.subheader("Multi-LGA Comparison Tool")
    
    lga_compare_options = filtered_df.sort_values('viability_score', ascending=False)['lga_name'].unique()
    selected_lgas_compare = st.multiselect(
        "Select up to 5 LGAs to compare:",
        lga_compare_options,
        max_selections=5,
        key='lga_compare_multiselect'
    )
    
    if len(selected_lgas_compare) >= 2:
        compare_df = filtered_df[filtered_df['lga_name'].isin(selected_lgas_compare)]
        
        # Comparison chart (Polar Plot)
        fig_compare = go.Figure()
        metrics = ['viability_score', 'economic_strength', 'telecom_readiness', 'digital_potential', 'opportunity_score', 'risk_score']
        
        for lga in selected_lgas_compare:
            lga_vals = compare_df[compare_df['lga_name'] == lga][metrics].values[0]
            fig_compare.add_trace(go.Scatterpolar(
                r=lga_vals,
                theta=['Viability', 'Economic', 'Telecom', 'Digital', 'Opportunity', 'Risk'],
                fill='toself',
                name=lga,
                opacity=0.7,
                line=dict(width=3)
            ))
        
        fig_compare.update_layout(
            title="LGA Comparison - Multi-Dimensional View",
            polar=dict(radialaxis=dict(visible=True, range=[0, 100]))
        )
        st.plotly_chart(fig_compare, use_container_width=True)
        
        # Comparison table
        st.subheader("Detailed Comparison Table")
        comparison_table = compare_df[[
            'lga_name', 'state_name', 'geo_zone', 'population', 'viability_score',
            'economic_strength', 'telecom_readiness', 'digital_potential',
            'opportunity_score', 'risk_score', 'viability_category', 'risk_category'
        ]].sort_values('viability_score', ascending=False)
        
        display_table = comparison_table.copy()
        display_table['population'] = display_table['population'].apply(lambda x: f"{x:,.0f}")
        for col in ['viability_score', 'economic_strength', 'telecom_readiness', 'digital_potential', 'opportunity_score', 'risk_score']:
            display_table[col] = display_table[col].apply(lambda x: f"{x:.1f}")
            
        st.data_editor(
            display_table, 
            use_container_width=True, 
            hide_index=True,
            column_config={
                "viability_category": st.column_config.BadgeColumn("Viability", help="High, Medium, or Low"),
                "risk_category": st.column_config.BadgeColumn("Risk Level", help="High, Medium, or Low Risk")
            }
        )

    st.markdown("---")
    
    # Full data table
    st.subheader("📋 Complete Filtered Dataset")
    st.dataframe(
        filtered_df[[
            'lga_name', 'state_name', 'geo_zone', 'population',
            'viability_score', 'economic_strength', 'telecom_readiness',
            'digital_potential', 'opportunity_score', 'risk_score',
            'viability_category', 'economic_category', 'risk_category'
        ]].sort_values('viability_score', ascending=False),
        use_container_width=True,
        hide_index=True
    )

# Footer
st.markdown("---")
st.markdown("""
<div style='text-align: center; color: #aaaaaa; padding: 1rem;'>
    <p><strong>Telco Go-To-Market: LGA Potential Analyzer v2.1 (Dark Mode)</strong></p>
    <p>Powered by n8n, Cerebras AI, PostgreSQL & Streamlit | Built by Philip Ogbunugafor</p>
    <p>Data Source: World Bank API | Last Updated: {}</p>
</div>
""".format(datetime.now().strftime("%B %d, %Y - %H:%M")), unsafe_allow_html=True)


•	Run the below to start the dashboard;
streamlit run app.py --server.port 8502 --server.address 0.0.0.0

•	Paste the below on your browser to see the dashboard
http://your-server-ip:8502
 

Conclusion
This project demonstrates the power of data automation and machine intelligence in transforming how telecom operators identify and pursue new growth areas across Nigeria. By integrating multiple real-world datasets including population, economic estimates, network penetration, and digital adoption patterns and processing them through an automated n8n + PostgreSQL pipeline enhanced by AI-driven scoring, the system delivers precise, location-specific market intelligence that was previously inaccessible.
With a focus on rural and semi-urban LGAs, the Telco Go-To-Market: LGA Potential Analyzer & Forecasting System moves decision-making away from intuition and fragmented reporting into a framework that is data-driven, structured, and continuously updated. The result is a real-time dashboard that gives telecom leaders deep visibility into where investment will deliver the highest commercial impact for network rollout, agent deployment, kiosk placement, and digital service expansion.
Ultimately, this solution supports a more inclusive telecommunications future where millions of underserved Nigerians gain access to stronger connectivity and digital opportunities. It empowers telcos to expand intelligently, policymakers to plan sustainably, and local communities to benefit from improved digital access reinforcing that the strategic use of AI and automation is not just a business advantage but a catalyst for national development.

