# Homework_ICA

## Dataset
- Over 1000 records from Melbourne water database and Melbourne airport weather station (from 01/01/2014 to 31/12/2019)
- Several records with Null values, very low power consumption (near zero), extremely high consumptions, irrelevant feature
values, and outlier data values (data point that differs significantly
from other observations) were removed.

### Data (excluding day/month/year)
- avg-outflow: Average Outflow (Qout, m^3/s)
- avg-inflow: Average Inflow (Qin, m^3/s)
- total_grid: Daily Total Grid Power Consumption (Ec, MWh)
- Am: Ammonia (NH4-N, mg/L)
- BOD: Biological Oxygen Demand (mg/L)
- COD: Chemical Oxygen Demand (mg/L)
- TN: Total Nitrogen (mg/L)
- T: Average Temperature (Tavg, °C)
- TM: Maximum Temperature (Tmax, °C) 
- Tm: Minimum Temperature (Tmin, °C)
- SLP: Atmospheric Pressure (AP, hPa)
- H: Average Relative Humidity (H, %)
- PP: Total Rainfall and/or Snowmelt (Pr, mm)
- VV: Average Visibility (VIS, Km)
- V: Average Wind Speed (WSavg, Km/h)
- VM: Maximum Wind Speed (WSmax, Km/h)
- VG: Unknown/Unused?

Predictors dropped:
- SLP: Only 5 values different from 0;
- VG: No information about it;
---
## Código
Para rodar o código, basta clicar no arquivo ['HW_1_ICA.ipynb'](https://github.com/Krumpu/Homework_ICA/blob/main/HW_1_ICA.ipynb) e em seguida em 'Open in colab'. O código está dividido em tópicos com breves explicações das etapas e deve ser executado na ordem disposta.

## Contribuições Individuais
Giordano Bruno cuidou majoritariamente da escrita do texto, e teve participação na organização do código. Kaique Ferreira e Marco Penaforte escreveram o código quase em sua totalidade, divindindo tarefas entre si.
