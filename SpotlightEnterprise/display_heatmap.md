---
title: Heatmap
tags: [heatmap]
keywords: heatmap
summary: "The Heat Map is an accurate reflection of the current environment. The Heat Map organizes connections based on the comparative number and severity of alarms raised against them. It refreshes itself automatically when connections are added and removed and when there is a change in the alarm status of the connections. Connections are removed from the heat map when monitoring is disabled and while they are in planned outage. The Heat Map answers the question: Which monitored connections require the most urgent attention?"
sidebar: p_enterprise_sidebar
permalink: /enterprise_heatmap/
---


## About the heat map
Connections with the most alarms raised against them are given the most surface area on the heat map.

### Hover the mouse over a connection

*  Show the full name of the connection
*  Show the connection type (For example: SQL Server, Windows, Analysis Services, SQL Azure)
*  Show the top 5 alarms currently raised against the connection
*  If there are more than 5 alarms, list the remaining alarm counts of each severity

### Click on a connection

Open the Spotlight Overview page for the connection.

## Color

Connections are colored according to the most severe current alarm.

Default Color | Severity | Description
--------------|----------|------------
![Normal color]({{ "/imagesClient/icon_alarm_green.png" | prepend: site.baseurl }})  | Normal | No alarms are raised against this connection.
![Information color]({{ "/imagesClient/icon_alarm_blue.png" | prepend: site.baseurl }})  | Information | At least one information alarm is raised against this connection. No other alarms are raised.
![Low color]({{ "/imagesClient/icon_alarm_yellow.png" | prepend: site.baseurl }})  | Low | At least one low severity alarm is raised against this connection. No high or medium severity alarms are raised.
![Medium color]({{ "/imagesClient/icon_alarm_orange.png" | prepend: site.baseurl }})  | Medium | At least one medium severity alarm is raised against this connection. No high severity alarms are raised.
![High color]({{ "/imagesClient/icon_alarm_red.png" | prepend: site.baseurl }})  | High | At least one high severity alarm is raised against this connection.


## Configure
The Heat Map can be configured to be the first page you see when you open the Spotlight Client. For more information, see Spotlight startup location.