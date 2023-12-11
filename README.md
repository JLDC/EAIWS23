# EAIWS23
Emergent Algorithmic Intelligence Winter School 2023

## Predictive Challenge

The data can be downloaded here:
+ [train.pkl](https://jldc.ch/uploads/train.pkl)
+ [test.pkl](https://jldc.ch/uploads/test.pkl)

### Variables

| Variable | Description | Available Measurements |
| --- | --- | --- |
| `date` | Date of the measurement (hourly levels) | `YYYY-MM-DD HH:MM:SS` |
| `state` | The state where the measurement was taken | `string` |
| `city` | The city where the measurement was taken | `string` |
| `PM2.5_target` | Target variable (One hour ahead PM2.5) | `ug/m3` |
| `PM2.5` | Particulate matter 2.5 | `ug/m3` |
| `CO` | Carbon monoxide | `mg/m3` |
| `CO2` | Carbon dioxide | `mg/m3` |
| `NO` | Nitric oxide | `ug/m3` |
| `NO2` | Nitrogen dioxide | `ug/m3` |
| `NOx` | Nitrogen oxides | `ppb` |
| `NH3` | Ammonia | `ug/m3` |
| `SO2` | Sulfur dioxide | `ug/m3` |
| `Temp` | Temperature | `°C` |
| `AT` | Air temperature | `°C` |
| `BP` | Barometric pressure | `mmHg` |
| `Benzene`| Concentration of Benzene in the air| `ug/m3` |
| `CH4` | Methane | `ug/m3` |
| `Eth-Benzene` | Concentration of Ethylbenzene in the air | `ug/m3` |
| `HCHO` | Formaldehyde | `ug/m3` |
| `Hg` | Mercury | `ug/m3` |
| `MH` | Mixing height | `m` |
| `MP-Xylene` | Concentration of Meta-Para-Xylene in the air | `ug/m3` |
| `NMHC` | Non-methane hydrocarbons | `ug/m3` |
| `O Xylene` | Concentration of Ortho-Xylene in the air | `ug/m3` |
| `Ozone` | Ozone concentration | `ug/m3` |
| `Power` | Power consumption | `W` |
| `RF` | Rainfall | `mm` |
| `RH` | Relative humidity | `%` |
| `SPM` | Suspended particulate matter | `ug/m3` |
| `SR` | Solar radiation | `W/m2` |
| `THC` | Total hydrocarbons | `ug/m3` |
| `Toluene` | Concentration of Toluene in the air | `ug/m3` |
| `VWS` | Wind speed | `m/s` |
| `WD` | Wind direction | `degree` |
| `WS` | Wind speed | `m/s` |
| `Xylene` | Concentration of Xylene in the air | `ug/m3` |

The goal is to predict `PM2.5_target`, the one-hour ahead PM2.5 concentration, on the test set.

This data is a modification of publicly available data. Please do not use the original data set for your solution.