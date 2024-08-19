# Apica Ascent Level monitoring

## Features
* Monitor overview of logs via Apica Ascent prometheus connector

## Configuration

* Edit filename.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor 


## Steps to import

* Download for ex: apica-monitoring.json
* Run apicactl to import the file apica-monitoring.json

```
apicactl create dashboard -f apica-monitoring.json

```

## Screenshot

![image info](./apica-monitoring.png)

