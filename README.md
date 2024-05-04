# IOS-XE Sustainability Dashboard
# Description:

This is an example of how to use Model-Driven Telemetry, Telegraf, InfluxdB, and Grafana (TIG Stack) to visualize the sustainability telemetry from Cisco IOS-XE devices.  

Link to the [USECASE.md](https://github.com/rickbauer9482/IOS-XE-Sustainability-Dashboard/blob/main/USECASE.md)

# The Challenge:

•	Sustainability has become a hot topic
•	Not all customers use Catalyst Center as the Command and Control Center for their Campus Networks
•	Some customers prefer a Do it Yourself (DIY) OpenSource approach for their tooling
•	Legacy Pull solutions like SNMP and Syslog do not provide information fast enough 

# The Goal:

•	To provide a Sustainability Dashboard based on modern approaches (MDT) and OpenSource tools

# The Solution:

•	Telemetry subscriptions from Cisco IOS-XE devices to provide sub-second resolution to visualize sustainability data in a TIG Stack 

# The Results:

•	Quick and easy DIY solution to visualize telemetry data from Cisco IOS-XE devices

# Business Summary:

•	Simple, relevant, and flexible telemetry data visualized in a lightweight, easily deployed solution

# Links to DevNet Learning Labs

[Model-Driven Telemetry](https://developer.cisco.com/learning/labs/enabling_telemetry_on_iosxe/)

[Enabling Telemetry on IOS XE](https://developer.cisco.com/learning/labs/enabling_telemetry_on_iosxe/enabling-telemetry-on-ios-xe/)

# CONTRIBUTORS

Rick Bauer

Assuming that you have a TIG stack running to receive, store, and visualize the telemetry from the Cisco IOS-XE devices

1. Create the subscriptions on your IOS-XE devices
2. Import the JSON Grafana Dashboard
3. ENJOY

*** If you need help getting your Telegraf, InfluxDB, and Grafana (TIG Stack) set up see my cisco-mdt-tig repository for help getting started

<img width="1925" alt="image" src="https://github.com/rickbauer9482/IOS-XE-Sustainability-Dashboard/assets/19711276/b3b3efa0-67ec-47c4-bf15-15bf661625ac">
