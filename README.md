# IoT Engineering Project X
> Note: Adapt this template to your specific project.

[IoT Engineering](https://github.com/tamberg/fhnw-iot) course team project.

## Rules
> Note: The _deadline_ to commit and push the final version is _Demo Day, 00:00_.

- For details on what exactly is expected, see [IoT00Syllabus.pdf](http://www.tamberg.org/fhnw/2025/hs/IoT00Syllabus.pdf) pp.13 - 16.

## Team
> Note: Commit and push early and often, git history serves as a proof of team work.

* STUDENT1_NAME ([@GITHUB_USER1](https://github.com/GITHUB_USER1))
* STUDENT2_NAME ([@GITHUB_USER2](https://github.com/GITHUB_USER2))
* STUDENT3_NAME ([@GITHUB_USER3](https://github.com/GITHUB_USER3))

## Code
### Sensor
> Note: Use ESP8266 or nRF52840 (or Pi Zero w/ Cam).

* [ESP8266_Sensor.ino](arduino/ESP8266_Sensor/ESP8266_Sensor.ino)
* Expand ESP8266 with Grove adapter
* Connect XY sensor to Grove port N
* Install XY sensor Arduino library

<img src="" alt="Sensor device" width="500" height="376"/>

### Actuator
> Note: Use ESP8266 or nRF52840.

* [nRF52840_Actuator.ino](arduino/nRF52840_Actuator/nRF52840_Actuator.ino)
* Expand nRF52840 with Grove adapter
* Connect XY actuator to Grove port N
* Install XY actuator Arduino library
  
<img src="" alt="Actuator device" width="500" height="376"/>

### Backend (or Gateway or Client)
> Note: Use JS, Python, etc. or existing IoT platform.

* [code.js](nodejs/code.js)
* Setup, build and run with
    ```console
    $ cd nodejs
    $ npm install ...
    $ node code.js
    ```

<img src="" alt="Screenshot" width="500" height="376"/>

## Docs
> Note: See [rules](#Rules) above for expected content.

* [Slides](docs/Slides.pdf) (PDF)

## Prompts
> Note: Not using "AI" tools is absolutely fine.

* [Prompts](prompts)

## License
> Note: Make sure 3rd party code or content is compatible.

* Code is Copyright © 2025 FHNW, licensed under [MIT License](https://fhnw.mit-license.org).
* Docs by [Team](#Team), licensed under Creative Commons [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
