# EPFL Infoscience shortcode

## Description

This shortcode is intended at displaying data coming from Infoscience into the WordPress sites at EPFL

## Base information

|             |                                                          |
| ----------- | -------------------------------------------------------- |
| Plugin Name | EPFL Infoscience shortcode                               |
| Plugin URI  | https://github.com/epfl-idevelop/EPFL-WP-SC-Infoscience  |
| Description | provides a shortcode to display results from Infoscience |
| Version     | 1.0                                                      |
| Author      | Emmanuel JAEP                                            |
| Author URI  | https://people.epfl.ch/emmanuel.jaep?lang=en             |
| License     | Copyright (c) 2017 Ecole Polytechnique Federale de Lausanne, Switzerland |

## Installation

Simply clone this repository into the ```plugins``` or ```mu-plugins``` directory of WordPress

```bash
cd wp-content/plugins
git clone https://github.com/epfl-idevelop/EPFL-WP-SC-Infoscience.git
```

## Usage

This shortcode uses one parameter: url
This url is the path to the Infoscience bucket

For instance, you can use the below code

```
[epfl_infoscience url=http://infoscience.epfl.ch/curator/export/9665/?ln=en]
```