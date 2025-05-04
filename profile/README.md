# ArduinoSensor

このOrganizationには，Arduinoにセンサを接続するアプリケーションやセンサのAPI，センサのデバイスドライバ(ライブラリ)を集めています．


## API

- [AusEx](https://github.com/ArduinoSensor/AusEx) : センサのデバイスドライバ類のAPIを統合するためのライブラリ
- [AusExOutputPlugin](https://github.com/ArduinoSensor/AusExOutputPlugin) : 上記APIで取得したデータをJSONやsyslog形式などに変換するライブラリ


## センサ用デバイスドライバ

以下は，デバイスドライバと対応するセンサモジュールのリスト．

### 温度,湿度,気圧

### 温度,湿度
- [AusEx library for DHT series sensor](https://github.com/ArduinoSensor/AusExDHT) : [Grove - Temperature&Humidity Sensor Pro(DHT22)](https://wiki.seeedstudio.com/Grove-Temperature_and_Humidity_Sensor_Pro/)
- [AusEx library for SHT31 sensor](https://github.com/ArduinoSensor/AusExSHT31) : [SHT31使用 高精度温湿度センサーモジュールキット](https://akizukidenshi.com/catalog/g/g112125/)
- [AusEx library for SHT2x series sensor](https://github.com/ArduinoSensor/AusExSHT2x) : [SHT-21 １チップ温度・湿度センサ・モジュール](https://strawberry-linux.com/catalog/items?code=80021)
- [AusExHTS221](https://github.com/ArduinoSensor/AusExHTS221) : [MKR ENV Shield](https://docs.arduino.cc/hardware/mkr-env-shield/)
- [HDC1000 統合センサライブラリ](https://github.com/ArduinoSensor/AusExHDC10XX) : [HDC1000](https://www.ti.com/product/ja-jp/HDC1000)
- [AusEx library for AM232X series sensor](https://github.com/ArduinoSensor/AusExAM232X) : AM2321

### 温度
- [AusExDallasTemperature](https://github.com/ArduinoSensor/AusExDallasTemperature) : [デジタル温度センサー(1wire)DS18B20+](https://akizukidenshi.com/catalog/g/g105276/)
- [Grove Analog Temperature Sensor AusEx driver](https://github.com/ArduinoSensor/AusExGroveAnalogTemperatureSensor) : [Grove - Temperature Sensor](https://www.seeedstudio.com/Grove-Temperature-Sensor.html)

### 気圧
- [AusExLPS22HB](https://github.com/ArduinoSensor/AusExLPS22HB) : [MKR ENV Shield](https://docs.arduino.cc/hardware/mkr-env-shield/)
- [AusExBMP180](https://github.com/ArduinoSensor/AusExBMP180) : [BMP180](https://akizukidenshi.com/catalog/g/g112854/)

## 加速度・ジャイロセンサデバイスドライバ
### 3軸加速度
- [AusExGrove3AxisAnalogAccelerometer](https://github.com/ArduinoSensor/AusExADXL335) : [Grove - ADXL335- 3-Axis Analog Accelerometer (±3g)](https://www.seeedstudio.com/Grove-3-Axis-Analog-Accelerometer-ADXL335.html)
- [AusExGrove3AxisDigitalAccelerometer1_5g](https://github.com/ArduinoSensor/AusExGrove3AxisDigitalAccelerometer1_5g) : [Grove - 3-Axis Digital Accelerometer(±1.5g)](https://www.seeedstudio.com/Grove-3-Axis-Digital-Accelerometer-1-5g.html)
- [AusExADXL345](https://github.com/ArduinoSensor/AusExADXL345) : [Grove - ADXL345 - 3-Axis Digital Accelerometer(±16g)](https://www.seeedstudio.com/Grove-3-Axis-Digital-Accelerometer-16g.html)

### 3軸ジャイロ
- [AusExGrove3AxisDigitalGyro](https://github.com/ArduinoSensor/AusExGrove3AxisDigitalGyro) : [Grove - 3-Axis Digital Gyro](https://www.seeedstudio.com/Grove-3-Axis-Digital-Gyro.html)


### 1軸ジャイロ
- [AusExGroveAnalog1AxisGyro](https://github.com/ArduinoSensor/AusExGroveAnalog1AxisGyro) : [Grove - Single Axis Analog Gyro](https://www.seeedstudio.com/Grove-Single-Axis-Analog-Gyro-p-1451.html)




## 対人センサデバイスドライバ
### タッチ
- [AusExGroveTouchSensor](https://github.com/ArduinoSensor/AusExGroveTouchSensor) : [Grove - Touch Sensor](https://www.seeedstudio.com/Grove-Touch-Sensor.html)
- [AusExGroveI2cTouchSensor](https://github.com/ArduinoSensor/AusExGroveI2cTouchSensor) : [Grove - I2C Touch Sensor](https://www.seeedstudio.com/Grove-I2C-Touch-Sensor-p-840.html)

### 人感センサ
- [AusExGrovePirSensor](https://github.com/ArduinoSensor/AusExGrovePirSensor) : [Grove - PIR Motion Sensor](https://www.seeedstudio.com/Grove-PIR-Motion-Sensor.html)
  
### 皮膚電気抵抗
- [AusExGroveGsr](https://github.com/ArduinoSensor/AusExGroveGsr) : [Grove - GSR sensor](https://www.seeedstudio.com/Grove-GSR-sensor-p-1614.html)

## 視覚関係センサデバイスドライバ
### 色彩
- [AusEx TCS34725 driver](https://github.com/ArduinoSensor/AusExTCS34725) : [TCS34725](https://akizukidenshi.com/catalog/g/g108220/)


### 明るさ
- [AusExTEMT6000](https://github.com/ArduinoSensor/AusExTEMT6000) : [Arduino MKR ENVシールド搭載TEMT6000](https://docs.arduino.cc/hardware/mkr-env-shield/)
- [AusExGroveSimpleLight](https://github.com/ArduinoSensor/AusExGroveSimpleLight) : [Grove - Light Sensor](https://www.seeedstudio.com/Grove-Light-Sensor-p-746.html)
- [AusExTSL2561](https://github.com/ArduinoSensor/AusExTSL2561) : [Grove - Digital Light Sensor](https://wiki.seeedstudio.com/Grove-Digital_Light_Sensor/)


## その他のセンサ用デバイスドライバ



### 水分
- [AusExGroveWaterSensor](https://github.com/ArduinoSensor/AusExGroveWaterSensor) : [Grove - Water Sensor](https://www.seeedstudio.com/Grove-Water-Sensor.html)
- [AusExGroveSimpleMoisture](https://github.com/ArduinoSensor/AusExGroveSimpleMoisture) : [Grove - Soil Moisture Sensor](https://www.seeedstudio.com/Grove-Moisture-Sensor.html)


### 音量
- [AusExGroveSimpleSound](https://github.com/ArduinoSensor/AusExGroveSimpleSound) : [Grove-Loudness Sensor](https://www.seeedstudio.com/Grove-Loudness-Sensor.html)


### 電流
- [AusExGroveAnalogCurrentSensor](https://github.com/ArduinoSensor/AusExGroveAnalogCurrentSensor) : [Grove - Electricity Sensor](https://www.seeedstudio.com/Grove-Electricity-Sensor.html)

### 赤外線
- [AusExGroveLineFinder](https://github.com/ArduinoSensor/AusExGroveLineFinder) : [Grove - Line Finder](https://www.seeedstudio.com/Grove-Line-Finder-v1-1.html)
- [AusExGroveInfraredReflectiveSensor](https://github.com/ArduinoSensor/AusExGroveInfraredReflectiveSensor) : [Grove - Infrared Reflective Sensor](https://www.seeedstudio.com/Grove-Infrared-Reflective-Sensor-v1-2.html)
- [AusExGroveInfraredDistanceSensor](https://github.com/ArduinoSensor/AusExGroveInfraredDistanceSensor) : [Grove - IR Distance Interrupter](https://www.seeedstudio.com/Grove-IR-Distance-Interrupter-v1-2.html)

### 角度
- [AusExGroveRotaryAngleSensor](https://github.com/ArduinoSensor/AusExGroveRotaryAngleSensor) : [Grove - Rotary Angle Sensor](https://www.seeedstudio.com/Grove-Rotary-Angle-Sensor.html)

### GPS
- [AusExGPS](https://github.com/ArduinoSensor/AusExGPS) : [Grove - GPS Module](https://www.seeedstudio.com/Grove-GPS-Module.html)


### その他
- [AusExGroveUltrasonicRanger](https://github.com/ArduinoSensor/AusExGroveUltrasonicRanger) : [Grove超音波センサ](https://www.seeedstudio.com/Grove-Ultrasonic-Distance-Sensor.html)
- [AusExGroveDustSensor](https://github.com/ArduinoSensor/AusExGroveDustSensor) : [Grove - Dust Sensor](https://www.seeedstudio.com/Grove-Dust-Sensor-PPD42NS.html)
- [AusExDigitalSwitch](https://github.com/ArduinoSensor/AusExDigitalSwitch) : [Grove - Digital Switch](https://www.seeedstudio.com/Grove-Switch(P)-p-1252.html)
