# Traffic Open Data
This repository hosts some **open data** about local **speed cameras** and **red-light cameras**.

### Note
This repository contains data about cameras' routes and position. 
If you want to check the time of service, please look at www.autoveloxlecce.it 

## Available datasets

| Dataset | Description | Format |
| ------ | ------- | ------- |
| [**autovelox-fissi-lecce**](https://github.com/jeckodevelopment/datasets/blob/master/autovelox-fissi-lecce.geojson) | List of all active fixed Autovelox (Speed cameras) in the Province of Lecce. | GeoJSON Format |
| [**autovelox-mobili-lecce**](https://github.com/jeckodevelopment/datasets/blob/master/autovelox-mobili-lecce.geojson) | List of all routes checked by mobile/temporary Autovelox (Speed cameras) in the Province of Lecce. | GeoJSON Format |
| [**photored-lecce**](https://github.com/jeckodevelopment/datasets/blob/master/photored-lecce.geojson) | List of all active Photored (Red Light Cameras) in the Province of Lecce. | GeoJSON Format |
| [**autovelox-mobili-brindisi**](https://github.com/jeckodevelopment/datasets/blob/master/autovelox-mobili-brindisi.geojson) | List of all routes checked by mobile/temporary Autovelox (Speed cameras) in the Province of Brindisi. | GeoJSON Format |

## How to read data
Different colors and pointers are used in order to mark different operators of the service.
### Legend
| Exa | Color | Meaning |
| ------ | ------ | ------- |
| #024efd | Blue | Polizia Stradale |
| #e9a414 | Yellow | Polizia Locale |
| #a60404 | Red | Polizia Provinciale |

## How to use data
You're more than welcome to use and implement these datasets provided in GeoJSON format in your applications and services.
If you use them, please let us know, we'll be happy to see your implementation.

## How to contribute / report
If you find typos and mistakes in the data or if you have some new data to add, please submit a pull request or raise an issue using in the GitHub repository.
