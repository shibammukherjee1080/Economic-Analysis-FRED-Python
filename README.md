# Economic Data Analysis with FRED & Python

## Description
This project utilizes the Federal Reserve Economic Data (FRED) API and Python libraries to extract and analyze a significant amount of economic data, focusing on unemployment rates and labor force participation. The analysis aims to uncover trends and changes over time, particularly during periods of economic crisis. This project demonstrates proficiency in data extraction, analysis, and visualization using Python libraries such as Pandas and Matplotlib.

## Installation
To install the necessary packages, use the following command:
```bash
pip install fredapi pandas matplotlib plotly
```
# Project Structure
- **American Economic Data Analysis.ipynb**: The main notebook containing the data analysis.

## Analysis Overview

### 1. Importing Libraries and API Setup:
- Import essential libraries such as Pandas, NumPy, Matplotlib, and Plotly.
- Setup and initialization of the FRED API using a unique API key. 
  - *Note*: The unique API key can be requested from FRED's website.

### 2. Data Extraction:
- Extract various economic data series using the FRED API.
- Focus on datasets related to S&P indices, unemployment rates, and labor force participation.

### 3. Data Analysis and Plotting:
- Analysis of data over various economic cycles.
- Plotting and analyzing differences in the effects of the Economic Crisis of 2008 and 2020 using iterating subplotting methods.

### 4. Important Key  Findings and analysis of WHY?? (I found some shocking findings in the job participation rate - point 4.3)

#### 4.1: Unemployment vs. Job Participation Rate During Covid Crisis

![Screenshot 2024-08-22 141700](https://github.com/user-attachments/assets/09479061-e09c-4252-82f5-c358392e3333)

**Some Key Observations**:
1. **High economy states** like California, Texas, New York, and Florida:
   - Diverse economies helped cushion the initial blow, but strict lockdown measures impacted sectors like tourism, finance, and hospitality. The rebound likely reflects the state's technology and innovation sectors.

2. **Other states**:
   - **New Mexico**: Tourism and energy-dependent economy struggled with prolonged high unemployment and a substantial drop in labor force participation, indicating a sluggish recovery.
   - **West Virginia**: Declining coal industry and older workforce led to a significant decrease in labor force participation, coupled with elevated unemployment and a slow rebound.
   - **Mississippi**: Existing socioeconomic challenges were exacerbated by the pandemic, resulting in persistent high unemployment and a notable decline in labor force participation with limited recovery.
   - **Hawaii**: Reliance on tourism caused a devastating initial unemployment spike, but participation rebounded faster than other struggling states as tourism gradually resumed.

#### 4.2: Comparing the Unemployment Rate During 2008 Banking Crisis and 2020 Covid Crisis

![Unemp compare](https://github.com/user-attachments/assets/0216af23-620f-4a34-b147-e241b68bd9e7)

- The recovery of employment was slow in the 2008 crisis, taking roughly 3 to 4 years to reach pre-crisis levels.
- In 2020, although the initial shock was more severe with unemployment exceeding 16%, the recovery was much faster within 2 years.

**Several Factors Contributed to the Differing Recovery Speeds**:
1. **Nature of the Crisis**:
   - **2008**: A financial crisis rooted in the housing market, with cascading effects on the broader economy. The financial sector required extensive repair, and consumer and business confidence were deeply shaken.
   - **2020**: Primarily a health crisis, with economic impacts stemming from lockdowns and restrictions. While severe, the underlying economic structure remained largely intact.

2. **Policy Responses**:
   - **2008**: The response was initially slower and focused on stabilizing the financial system. Fiscal stimulus was implemented, but its impact was gradual.
   - **2020**: A swift and massive response, including fiscal stimulus, enhanced unemployment benefits, and direct support to businesses. This helped prevent widespread bankruptcies and layoffs, fostering a quicker rebound.

3. **Labor Market Dynamics**:
   - **2008**: The crisis led to structural changes in the labor market, with job losses concentrated in sectors like construction and finance. Re-employment was slower as workers needed to retrain or relocate.
   - **2020**: Job losses were more widespread but often temporary, as businesses closed due to lockdowns. Once restrictions eased, many workers could return to their previous jobs, accelerating the recovery.

4. **Global Factors**:
   - **2008**: The crisis was global, with interconnected economies experiencing simultaneous downturns. This limited the potential for external demand to drive recovery.
   - **2020**: While global, the recovery trajectories varied. Some economies, like the US, implemented aggressive stimulus measures, which helped boost demand for goods and services from other countries.

#### 4.3:  Declining Job Participation Rate During 2008 Banking Crisis and 2020 Covid Crisis (Shocking Findings) !!!!

<img width="609" alt="Job participation cmpare" src="https://github.com/user-attachments/assets/e374cfb4-9c0e-4cb9-a00c-63667f79adcd">

As of 2024, **unemployment is at its lowest** (below 4%), but a paradox exists when this lower unemployment rate is juxtaposed with a **lower labor force participation rate**.

**Factors Responsible for This Situation**:
1. **Demographic Changes**: The aging population has led to an increase in retirements, reducing the labor force participation rate. Many baby boomers have exited the workforce, and their numbers aren't being fully replaced by younger workers​ (Bureau of Labor Statistics)​.
2. **Increased School Enrollment**: More young people are staying in school longer, which decreases the number of people available to work at any given time​.
3. **Shift in Work Preferences**: There has been a shift in preferences, with some workers opting for freelance or gig work, which may not always be captured in traditional labor force statistics​.
