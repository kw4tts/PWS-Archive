# PWS-Archive

Publically accessible data from DIY personal weather station

## Disclamer

- The weather data in thes repository **might contain errors** that are caused by one of the following:
  - misplacement of personal weather station sensors
  - sensor failure
  - mathematical operations failure
  - other failure

- As such, the data sample rate might not always be 1/5min
- As such, values might exceed the expected ranges (>50°C, <-20°C, etc)
- As such, the data might be useful for orientation purposes only **at all**.

The author carries **no liability** over the (mis)interpretation of the data.

## How to use:

git clone, checkout yearly branch, use the data, cite if appropriate with the disclamer above taken into the account.

## Other info

- 5min logging interval
- InfluxQL line protocol language (RFC timestamp with values). 
  - T: Temprature (C)
  - H: Humidity (%)
  - Tdp: dewpoint (C)
  - P: Pressure at the sensor (1/10 of hPa / mBars)
  - Pasl: Recalculated pressure at the sea level (1/10 of hPa / mBars)
  - Habs: Humidity (g/m3)
  - D: density (kg/m3)

