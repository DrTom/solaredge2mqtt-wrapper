SolarEdge2MQTT Wrapper
=======================

A test and deploy project for the
[SolarEdge2MQTT](https://github.com/DerOetzi/solaredge2mqtt) project.


## Test

The test uses the inclued submodule `solaredge2mqtt`.


    SE2MQTT_MODBUS__HOST=SolarEdgeInverter SE2MQTT_MQTT__BROKER=localhost ./bin/solaredge2mqtt


## Deployment


The deployment uses a released version of solaredge2mqtt, see `solaredge2mqtt_version`.


### To `hab`

    ./bin/deploy2hab -v -e solaredge2mqtt_mqtt_password='XXXXXXXXX'

