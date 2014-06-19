# talendEtl 

It is a module that implements the transformation from detailed data to historical data according to sensor's description in database set during the configuration process. 

It is a job bach of talend 5.3, so it is necessary to have a hourly scheduler (cron).

The configuration concerns mainly the Postgres Context, that are access credentials to the database.

## Requirements 

* Server Linux debian-like
* Java 1.7+
* Dog 2.5+
* Postgres 9+
* Cron
* Talend 5.3

## Development

If you need to modify jobs, you have to use the add-ons available in https://github.com/iEnergy/talendComponent

## Libraries 

This module uses the following libraries:

* angularjs 1.2.3 https://angularjs.org/
* boostrap  2.3.2 http://getbootstrap.com/