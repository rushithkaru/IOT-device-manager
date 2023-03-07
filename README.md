# Aws_telemetry
(WIP)


Using an esp32 and a raspberry pi 4 as IoT devices, AWS IoT core as an MQTT broker this project is for me to practice sending and visualising telemetry data using react (Also getting better at React in general).
For visualising the data I am using a flask app and the boto3 library to pull data from dynamodb. This then connects to a React app. The app also allows users to publish MQTT messages to the devices (for example: pausing a device directly from the UI). I also plan to use AWS greengrass for the raspberry pi in the future and integrate with the UI.



![flow](https://user-images.githubusercontent.com/30048959/218290869-1a5877f9-344a-488f-babe-6cc64bf0318e.jpg)





<img width="1430" alt="Screen Shot 2023-03-07 at 9 20 00 pm" src="https://user-images.githubusercontent.com/30048959/223393948-ca6ab5de-3da3-4a1e-b1d6-7e353ece7ebe.png">


<img width="1297" alt="Screen Shot 2023-03-05 at 1 59 06 pm" src="https://user-images.githubusercontent.com/30048959/222939356-ac3498cd-cd95-48ec-b16b-9eb84d7e7f21.png">


<img width="1234" alt="Screen Shot 2023-02-16 at 10 34 44 pm" src="https://user-images.githubusercontent.com/30048959/219363007-35bf53ae-bfff-4236-ac34-37887eb67b0c.png">
