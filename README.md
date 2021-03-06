
This is the Niagara module implementing the free 5-days weather report provided
by [Openweathermap](https://github.com/neopsis/niagara-weather.git). The module 
implements Niagara Weather API and uses standard Niagara icons so you can use 
it as the direct replacement for the discontinued Weather Underground service. 

##### History

| Date      |   Change                                    |
| ----------| --------------------------------------------|
| 9.1.2020  | Using HTTPConnection to pass NiagaraProxy   |
| 1.4.2019  | Module signed with Neopsis certificate      |
| 5.2.2019  | Initial Release                             |   


##### Usage

* Get the API key from the openweathemap homepage [here](https://openweathermap.org/appid).
* Install the module in your %niagara_home%/modules directory. 
* Add the Niagara WeatherService to your station's services. 
* Add new provider to the WeatherService - from the list of available
  services select `Nv Owm Provider`. 
* Add the location as `city`  or `city,country_code`, for example `London,GB`

To download the compiled module go to the 
[Releases](https://github.com/neopsis/niagara-weather/releases) link.

For developers: you can find the great documentation 
[here](https://godoc.org/github.com/briandowns/openweathermap)

The code is licensed under Apache 2.0 license, see the [LICENSE file](https://github.com/neopsis/niagara-weather/blob/master/LICENSE)

Enjoy
