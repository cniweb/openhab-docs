---
layout: documentation
title: YKFCON - ZWave
---

{% include base.html %}

# YKFCON Smart Living Keyfree Smart Lock

This describes the Z-Wave device *YKFCON*, manufactured by *ASSA ABLOY* with the thing type UID of ```yale_ykfcon_00_000```. 

Smart Living Keyfree Smart Lock


## Channels
The following table summarises the channels available for the YKFCON Smart Living Keyfree Smart Lock.

| Channel | Channel Id | Channel Type UID | Category | Item Type |
|---------|------------|------------------|----------|-----------|
| Door Lock | lock_door | lock_door | Door | Switch |
| Alarm | alarm_general | alarm_general | Door | Switch |
|  | battery-level | system.battery-level |  |  |


### Device Configuration
The following table provides a summary of the configuration parameters available in the YKFCON Smart Living Keyfree Smart Lock.
Detailed information on each parameter can be found below.

| Parameter   | Description |
|-------------|-------------|
| 1: Audio Volume | Sets the volume level of the beeps and voice prompts |
| 2: Auto Re-lock | When enabled, the unit will automatically re-lock |
| 3: Re-lock Time | Time after unlocking that the device will lock |
| 4: Wrong Code Entry Limit | The number of invalid tries before the lock shutdowns and sends an alarm |
| 5: Language | Language used by the voice prompts |
| 7: Shutdown Time | Number of times the device is locked out after the invalid retries are exceeded |
| 8: Operating Mode | Sets if the unit operates normal, or disables keypad and Z-Wave lock/unlock |
| 1: Alarm Reports | Alarm reports are sent out to all devices in the association group |


#### 1: Audio Volume

Sets the volume level of the beeps and voice prompts  


##### Overview 

1 = Silent

2 = Low

3 = High


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_1_1 |
| Data Type        | INTEGER || Default Value | 3 |
| Options | Silent (1) |
|  | Low (2) |
|  | High (3) |


#### 2: Auto Re-lock

When enabled, the unit will automatically re-lock  


##### Overview 

0 = Off

255 = On


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_2_1 |
| Data Type        | INTEGER || Default Value | 0 |
| Options | Off (0) |
|  | On (255) |


#### 3: Re-lock Time

Time after unlocking that the device will lock


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_3_1 |
| Data Type        | INTEGER |
| Range | 5 to 255 |
| Default Value | 30 |


#### 4: Wrong Code Entry Limit

The number of invalid tries before the lock shutdowns and sends an alarm


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_4_1 |
| Data Type        | INTEGER |
| Range | 1 to 7 |
| Default Value | 5 |


#### 5: Language

Language used by the voice prompts  


##### Overview 

1 = English

2 = Spanish

3 = French


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_5_1 |
| Data Type        | INTEGER || Default Value | 1 |
| Options | English (1) |
|  | Spanish (2) |
|  | French (3) |


#### 7: Shutdown Time

Number of times the device is locked out after the invalid retries are exceeded


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_7_1 |
| Data Type        | INTEGER |
| Range | 1 to 255 |
| Default Value | 30 |


#### 8: Operating Mode

Sets if the unit operates normal, or disables keypad and Z-Wave lock/unlock  


##### Overview 

0 = Normal

1 = Vacation Mode (User Codes Disabled)

2 = Privacy Mode (User Codes and ZWave Codes Disabled


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_8_1 |
| Data Type        | INTEGER || Default Value | 0 |
| Options | Normal (0) |
|  | Vacation Mode (1) |
|  | Privacy Mode (2) |


#### 1: Alarm Reports

Alarm reports are sent out to all devices in the association group


| Property         | Value    |
|------------------|----------|
| Configuration ID | group_1 |
| Data Type        | TEXT |
| Range |  to  |


---

Did you spot an error in the above definition or want to improve the content?
You can edit the database [here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/292).
