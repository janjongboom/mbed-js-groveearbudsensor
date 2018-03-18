# Grove Earbud HR monitor driver for Mbed.js

To install, run in your mbed-js gulp based project:

```
$ npm install mbed-js-groveearbudsensor
```

## Usage

```
var sensor = InterruptIn(D2);
var hr = GroveEarbudSensor(sensor);

setInterval(function() {
    print("Heart rate is " + hr.getHeartRate());
}, 1000);
```
