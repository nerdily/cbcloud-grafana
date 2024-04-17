# Readme
This project takes various information from Carbon Black Cloud and formats it for usage in Grafana. It does this by 
querying the cloud backend for information and storing it within a Timescale database. Grafana has native capabilities
to use Timescale as a source of data

Reference information about the API can be found [here](https://developer.carbonblack.com).

Where possible the required API permissions are contained at the top of each script. 

This repository and scripts are published under the MIT license. Feel free to use and modify as needed.