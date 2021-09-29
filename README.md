# ssswitch

* Name: ssswitch *
* Editor: Sam *
* Version: v1.0 *

## 1. Introduction
This tool is used to turn on or off the superset.

## 2. Preparation
1. Configure the IP_ADDRESS of your superset
```shell
vi ssswitch

IP_ADDRESS="x.x.x.x"
```
2. Configure the SUPERSET_NAME of your conda env
```shell
vi ssswitch

SUPERSET_NAME
```
3. Activate the superset env
```shell
conda activate <your superset env>
```
4. Grant X mode to this file
```shell
chmod +x ssswitch
```

## 3. Usage
1. start
```shell
ssswitch start
```
2. stop
```shell
ssswitch stop
```
3. restart
```shell
ssswitch restart
```
4. status
```shell
ssswitch status
```

