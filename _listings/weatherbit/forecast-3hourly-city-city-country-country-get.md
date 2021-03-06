---
swagger: "2.0"
info:
  title: Weatherbit Get Forecast 3hourly City & Country
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  version: 2.0.0
host: api.weatherbit.io
basePath: /v2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /forecast/3hourly?city={city}&country={country}:
    get:
      summary: Get Forecast 3hourly City & Country
      description: Returns a 3-hourly forecast, where each point represents a three
        hour   period
      operationId: returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city
        description: City search
      - in: path
        name: country
        description: Country Code (2 letter)
      - in: query
        name: days
        description: Number of days to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See <a href=''/api/requests''>language
          field description</a>'
      - in: query
        name: state
        description: Full name of state
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - weather
      - forecast
      - 3hourly
      - city
      - city
      - '&country'
      - country
definitions:
  CurrentObs:
    properties:
      app_temp:
        description: This is a default description.
        type: get
      city_name:
        description: This is a default description.
        type: get
      clouds:
        description: This is a default description.
        type: get
      country_code:
        description: This is a default description.
        type: get
      datetime:
        description: This is a default description.
        type: get
      dewpt:
        description: This is a default description.
        type: get
      dhi:
        description: This is a default description.
        type: get
      elev_angle:
        description: This is a default description.
        type: get
      hour_angle:
        description: This is a default description.
        type: get
      lat:
        description: This is a default description.
        type: get
  CurrentObsGroup:
    properties:
      count:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
  EnergyObs:
    properties:
      cdd:
        description: This is a default description.
        type: get
      city_name:
        description: This is a default description.
        type: get
      clouds:
        description: This is a default description.
        type: get
      country_code:
        description: This is a default description.
        type: get
      dewpt:
        description: This is a default description.
        type: get
      dhi:
        description: This is a default description.
        type: get
      hdd:
        description: This is a default description.
        type: get
      lat:
        description: This is a default description.
        type: get
      lon:
        description: This is a default description.
        type: get
      precip:
        description: This is a default description.
        type: get
  EnergyObsGroup:
    properties:
      count:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
      end_date:
        description: This is a default description.
        type: get
      start_date:
        description: This is a default description.
        type: get
  Error:
    properties:
      code:
        description: This is a default description.
        type: get
      message:
        description: This is a default description.
        type: get
  Forecast:
    properties:
      app_max_temp:
        description: This is a default description.
        type: get
      app_min_temp:
        description: This is a default description.
        type: get
      clouds:
        description: This is a default description.
        type: get
      datetime:
        description: This is a default description.
        type: get
      dewpt:
        description: This is a default description.
        type: get
      max_dhi:
        description: This is a default description.
        type: get
      max_temp:
        description: This is a default description.
        type: get
      min_temp:
        description: This is a default description.
        type: get
      pod:
        description: This is a default description.
        type: get
      pop:
        description: This is a default description.
        type: get
  ForecastDay:
    properties:
      city_name:
        description: This is a default description.
        type: get
      country_code:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
      lat:
        description: This is a default description.
        type: get
      lon:
        description: This is a default description.
        type: get
      state_code:
        description: This is a default description.
        type: get
      timezone:
        description: This is a default description.
        type: get
  ForecastHour:
    properties:
      app_temp:
        description: This is a default description.
        type: get
      clouds:
        description: This is a default description.
        type: get
      datetime:
        description: This is a default description.
        type: get
      dewpt:
        description: This is a default description.
        type: get
      dhi:
        description: This is a default description.
        type: get
      pod:
        description: This is a default description.
        type: get
      pop:
        description: This is a default description.
        type: get
      precip:
        description: This is a default description.
        type: get
      precip6h:
        description: This is a default description.
        type: get
      pres:
        description: This is a default description.
        type: get
  ForecastHourly:
    properties:
      city_name:
        description: This is a default description.
        type: get
      country_code:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
      lat:
        description: This is a default description.
        type: get
      lon:
        description: This is a default description.
        type: get
      state_code:
        description: This is a default description.
        type: get
      timezone:
        description: This is a default description.
        type: get
  GeoIPObj:
    properties:
      area_code:
        description: This is a default description.
        type: get
      charset:
        description: This is a default description.
        type: get
      city:
        description: This is a default description.
        type: get
      continent_code:
        description: This is a default description.
        type: get
      country_code:
        description: This is a default description.
        type: get
      country_code3:
        description: This is a default description.
        type: get
      dma_code:
        description: This is a default description.
        type: get
      ip:
        description: This is a default description.
        type: get
      latitude:
        description: This is a default description.
        type: get
      longitude:
        description: This is a default description.
        type: get
  History:
    properties:
      city_name:
        description: This is a default description.
        type: get
      country_code:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
      lat:
        description: This is a default description.
        type: get
      lon:
        description: This is a default description.
        type: get
      state_code:
        description: This is a default description.
        type: get
      timezone:
        description: This is a default description.
        type: get
  HistoryDay:
    properties:
      city_name:
        description: This is a default description.
        type: get
      country_code:
        description: This is a default description.
        type: get
      data:
        description: This is a default description.
        type: get
      lat:
        description: This is a default description.
        type: get
      lon:
        description: This is a default description.
        type: get
      state_code:
        description: This is a default description.
        type: get
      timezone:
        description: This is a default description.
        type: get
  HistoryDayObj:
    properties:
      datetime:
        description: This is a default description.
        type: get
      dewpt:
        description: This is a default description.
        type: get
      dhi:
        description: This is a default description.
        type: get
      max_temp:
        description: This is a default description.
        type: get
      max_temp_ts:
        description: This is a default description.
        type: get
      max_uv:
        description: This is a default description.
        type: get
      max_wind_dir:
        description: This is a default description.
        type: get
      max_wind_spd:
        description: This is a default description.
        type: get
      max_wind_spd_ts:
        description: This is a default description.
        type: get
      min_temp:
        description: This is a default description.
        type: get
  HistoryObj:
    properties:
      datetime:
        description: This is a default description.
        type: get
      dewpt:
        description: This is a default description.
        type: get
      dhi:
        description: This is a default description.
        type: get
      elev_angle:
        description: This is a default description.
        type: get
      h_angle:
        description: This is a default description.
        type: get
      pod:
        description: This is a default description.
        type: get
      precip:
        description: This is a default description.
        type: get
      precip6h:
        description: This is a default description.
        type: get
      pres:
        description: This is a default description.
        type: get
      qc:
        description: This is a default description.
        type: get
x-collection-name: Weatherbit
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---