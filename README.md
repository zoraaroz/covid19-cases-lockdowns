## Covid-19: Comparing cases and lockdowns in Berlin and Zurich

by Zora Schärer | June 2021

### Description
I live in Berlin and many of my friends and family live in Zurich. Like the rest of the world, we all felt the impact of Covid-19 in the past year but our experiences were somewhat different. The German and Swiss governments handeled the pandemic quite differently regarding regulations to contain the disease.

This project compares the Covid-19 cases in these Berlin and Canton Zurich. Was the number of cases similar in both locations? When did they differ and when were the synchronous?

Furthermore, I wanted to find what influenced the development of the incidences. I put together a data table to document the lockdowns in both locations and I included vaccination and temperature data. An ARIMA model was used to find out which regulations had an effect on the incidences or if other variables such as vaccinations and temperature had a stronger influence.

It turns out that in both Berlin and Zurich it was the temperature that had the strongest effect of the investigated variables. Apart from this seasonal character of Covid-19, the lockdown regulations do seem to have had an effect on the progress of incidences. In Berlin, is was mostly the mask mandate and closing of schools while in Zurich it was mostly the closing of retail trade and the mask mandate.

### Data sources
* [Berlin Covid data](https://www.kaggle.com/headsortails/covid19-tracking-germany) - Downloaded: 2.6.2021
* [Zurich Covid data](https://www.zh.ch/de/politik-staat/opendata.html?keyword=ogd#/details/671@gesundheitsdirektion-kanton-zuerich) - Downloaded: 9.6.2021
* [Vaccination data](https://www.kaggle.com/gpreda/covid-world-vaccination-progress) - Downloaded: 1.6.2021
* [Berlin Temperature data](https://www.wetterkontor.de/wetter-rueckblick/monats-und-jahreswerte.asp?id=23&jr0=2020&jr1=2021&mo0=1&mo1=12) - Downloaded: 11.6.2021
* [Zurich Temperature data](https://www.daswetter.com/wetter_Zurich-Europa-Schweiz-Zurich-LSZH-sactual-12195.html) - Accessed: 11.6.2021

Lockdowns in Berlin:
* https://www.deutschlandfunk.de/rueckblick-2020-chronologie-eines-schuljahrs-in-der.680.de.html?dram:article_id=489919
* https://de.wikipedia.org/wiki/COVID-19-Pandemie_in_Deutschland#Verlauf
* https://de.wikipedia.org/wiki/SARS-CoV-2-Verordnungen_in_Berlin
* https://www.berlin.de/sen/bjf/service/presse/

Lockdowns in Zurich:
* https://de.wikipedia.org/wiki/COVID-19-Pandemie_in_der_Schweiz#Bund
* https://www.zh.ch/de/gesundheit/coronavirus/zahlen-fakten-covid-19.html?keyword=covid19#/home
* https://www.oberrieden.ch/coronavirus-massnahmen-des-kantons-zuerich-weitere-informationen

### Files
data_analysis.ipynb - Jupyter notebook used for the data wrangnling and data_analysis
.csv files - Data files

### License
The contents of this repository are covered under the MIT License.
