![logo](/images/greengrass.png)
# AWS Greengrass Workshop

## Introduction
Greengrass is a software that allows you to extend AWS cloud capabilities to local devices, making it possible to collect data and securely communicate with local network and AWS Cloud. Fits very well for IoT solutions as gateway that need to communicate with Bluetooth, Zigbee or any other type of device communication.

![More information about Green Grass](https://docs.aws.amazon.com/greengrass/latest/developerguide/what-is-gg.html)


## Table of Content

### [1. Coinfigure your Raspberry Pi](#1configure-your-raspberry-pi)
### [2. Create your own Lambda Function for Nursing Skill](#2create-your-own-lambda-function-to-your-alexa-skill)
### [3. Create your own DynamoDB table](#3create-your-own-dynamodb-table)
### [4. Customizing Nursing Skill](#4customizing-nursing-skill)

## 1.Configure your Raspberry Pi

Before we start using Greengrass we need to configure our Raspberry PI AWS credentials for awscli and also be sure you have access to your Pi using SSH.

### Step #1: Open IAM Console to create an access key
![screen](/images/raspberry-config/01.png) 

### Step #2: Click in your AWS user
![screen](/images/raspberry-config/02.png) 

### Step #3: Click "Security Credentials"
![screen](/images/raspberry-config/03.png) 

### Step #4: Click "Create Access Key" 
![screen](/images/raspberry-config/04.png) 

### Step #25: Copy the Access Key ID and Secret Access

You can also download a CSV file with your keys!

![screen](/images/raspberry-config/05.png) 