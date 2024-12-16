# Data Folder
## Sub-Folders

### Source Data
* *[Countries of the World 2023](https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023?resource=download)*
* *[RESTful Countries API](https://restfulcountries.com/)*

### Supplementary Data
* *[CIA World Factbook](https://www.cia.gov/the-world-factbook)* 
* *[Our World in Data](https://ourworldindata.org/)*

### [raw_data](raw_data)
Original, unmodified data after downloading, scraping, etc.

### [final_data](final_data)
Data after cleaning, processing, analyzing

---

## Data Dictionary
| column | description | unit / format |
|----------|----------|----------|
| country | The name of the country | String | 
| population | The total population of the country | Integer |
| lat	| The latitude coordinate of the country | Decimal (Degrees) | 
| long | The longitude coordinate of the country | Decimal (Degrees) |
| continent	| The continent where the country is located | tring (e.g., Asia, Europe)
| gross_domestic_product_usd(b)	| The Gross Domestic Product (GDP) of the country in billions of USD | Float (Billions of USD)
| tax_revenue_pct	| The percentage of the country’s GDP collected as tax revenue | Float (Percentage)
| unemployment_rt	| The unemployment rate in the country | Float (Percentage)
| primary_education_enrollment_pct| The percentage of the population enrolled in primary education | Float (Percentage)
| secondary_education_enrollment_pcThet |  percentage of the population enrolled in secondary education | Float (Percentage)
| life_expectancy	| The average life expectancy in the country | Float (Years)
| birth_rt | The birth rate in the country (births per 1,000 people) | Float (Births per 1,000)
| infant_mortality_rt	| The infant mortality rate in the country (deaths per 1,000 live births) | Float (Deaths per 1,000 live births)
| physicians_per_thousand	| The number of physicians per 1,000 people in the country | Float (Physicians per 1,000)
| covid_death_rt | The COVID-19 death rate in the country (total deaths by total cases) |	Float (Percentage)|
