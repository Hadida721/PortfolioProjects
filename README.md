## PortfolioProjects
# Covid Cases & Deaths
Study based on most actual Data

1st Using a Select statement to gather all the Data that will be used (Location,date, Total Cases, new cases, total deaths, population)
while excempting continents to only show  countries.

2nd Formulated a query to find the likelihood of dying if you contracted covid in your country(ex.USA). Dividing (Total deaths/ Total Cases)*100).

3rd Showing what percentage of population got covid.
Formulated a query to find the percentage of population who got covid in their country (ex.USA). Dividing (Total cases/Population)*100).

4th Looking at countries with highest infection rate compared to population.
Using aggreggate functions (MAX) to display highest infection rate per location and population.

5th Showed countries with highest death count per population
Query grouped by continent showing highest death count with use of aggregate function.

6th Global Numbers

Demonstrated with the use of aggregate functions three colums showing the SUM of Total Cases, Total Deaths and the likelihood of dying percentage.


7th Looking at Total Population vs New Vaccinations

Using the Join function and partition by on tables (coviddeaths/covidvaccinations) united columns(continent,location,date,population and new vaccinations)
into alias Rolling peopleVaccinated to divided by population resulting in the percentage of people being vaccinated.

8th Created CTE ( Temp Table) PopsVac on the previous Join and subsequently created a table(PercentPopulationVaccinated).


9th Created two Visualizations using Tableau potratying the different studies performed.

Tableau [LINK1](https://public.tableau.com/views/TableauPersonalProjectCovid/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)
Tableau [LINK2](https://public.tableau.com/views/PersonalProjectCovidCasesDeathsDashboard/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

