# IseTrainingGuest

## Overview
The application is used to create guest user access within Cisco ISE. These users are defined in source data table. 
These users access is created by calling od Cisco ISE REST API. The user accesses are created using Cisco ISE REST API calls. 
Application prints report with these created accesses.

## Installation
This is a console application. This means that it is necessary to build the .NET application to start. Next, you need to configure the application in the configuration file AppData\Config.xml 

Application create ISE accounts according to user records, which are created in database tables Users. It's neccessary to create this table byt DB scripts

When User table is created is neccessary to load users to this table

## Usage
It is a console application. The binary file obtained by the build is run directly from the console.


