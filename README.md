[Get Started With Machine Learning on Arduino](https://docs.arduino.cc/tutorials/nano-33-ble-sense-rev2/get-started-with-machine-learning)

[Gesture recognition tutorial](https://colab.research.google.com/github/arduino/ArduinoTensorFlowLiteTutorials/blob/master/GestureToEmoji/arduino_tinyml_workshop.ipynb)

[Updated and working version of `imu_classify`](https://github.com/spaziochirale/ArduTFLite/tree/main/examples/ArduinoNano33BLE_GestureClassifier)

[Machine Learning on Arduino BLE (YouTube playlist)](
https://youtube.com/playlist?list=PL3E6XmqhhLBHXX2fG2dVER-LOq_7nl9p6&si=RG9CdAHWtexIOo61)

Steps:
* Install Arduino IDE
* Tools -> Board -> Board Manager -> install "Arduino Mbed OS Nano Boards"
* Sketch -> Include library -> Manage Library -> search "Arduino APDS9960"
* Sketch -> Include library -> Manage Library -> search "Arduino Sound SAMD21"
* Sketch -> Include library -> Manage Library -> search "Arduino_LSM" install LSM6DS3 and LSM9DS1 for accelerator (replaced by **Arduino_BMI270_BMM150**)
* Sketch -> Include library -> Manage Library -> search "Arduino_LPS22"
* Sketch -> Include library -> Manage Library -> search "Arduino_HTS221" (replaced by **Arduino_HS300x**)
* Sketch -> Include library -> Manage Library -> search "Arduino_TensorFlowLite" (replaced by ArduTFLite)
* File -> Examples -> Arduino APDS
* File -> Examples -> Arduino_TensorFlow_Lite -> magic_wand

https://www.szynalski.com/tone-generator/

https://github.com/AnbuKumar-maker/Machine-Learning-on-Arduino-33-BLE-Sense

[Exercises](https://github.com/arduino/ArduinoTensorFlowLiteTutorials/tree/master/GestureToEmoji/exercises)