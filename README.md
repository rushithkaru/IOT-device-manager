# Aws_telemetry
Repo for storing my iot project

Using and esp32 as an IoT device that uploads data to the cloud. Using the MQTT protocol and an AWS IoT core rule to push the telemtry data to dynamoDB. 
For visualising the data I am using a flask app and the boto3 library to pull data from dynamodb. This connects to a React app.
So far everything works but I want to make clean up the UI and optimise.
