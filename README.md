# Attendence-System-with-Rfid-php

## Download the project and deploy it in server
```
xamp,wamp
```
## Import sql file to mysql on server

```
Attendence-System-with-Rfid-php/sql/nodemcu_rfidrc522_mysql.sql
```
## Set pins as pin diagram in following location

```
Attendence-System-with-Rfid-php/pin Diagram/NodeMCU-RFID-Reader.png
```
## Set ssid wuth your network name and pasword with your network password in rfid_duino.ino

```
Attendence-System-with-Rfid-php/rfid_duino/rfid_duino.ino
```
```
const char* ssid = "slt";
const char* password = "12345678";
```
## Upload rfid_duino.ino to your NodeMCU

## run the ```index.php``` on server
