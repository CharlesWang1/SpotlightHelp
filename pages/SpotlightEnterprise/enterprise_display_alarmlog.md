---
title: Alarm log
keywords: alarm log
summary: "The alarm log is a display of logged alarms."
sidebar: p_enterprise_sidebar
permalink: enterprise_alarmlog.html
folder: SpotlightEnterprise
---

{% include imageClient.html file="tb_alarms_log.png" alt="Alarm log" %}

## Open the Alarm log

Click **Monitor \| Alarm log** from the Spotlight ribbon to open the Alarm log for all monitored connections.

{% include tip.html content="The Alarm log can be opened to show a custom view of monitored connections or a view of all connections of a specific type. From the left Connections pane, click on a custom view or connection type then click **Alarm log** from the display pane. To open the Alarm log for just one connection, right click on the connection in the Connections pane then click **Alarm log** from the display pane." %}


## About the alarm log grid

The alarm log grid is made up of rows and columns where each row represents an alarm and each column information about that alarm.

Column | Description
-------|------------
Time | The time the alarm was raised or canceled.
Connection | The connection the alarm was raised on.
Connection Type | The type of connection the alarm was raised on (for example, SQL Server). This column is hidden by default.
Details | A brief description of the cause of the alarm. For more information, right click on the alarm and select **What's This?**.
Severity | The degree of urgency of the alarm. The color indicates the severity of the alarm.
Alarm | The name of the alarm.
Snoozed By | The user who requested the alarm be snoozed.
Snoozed Until | The alarm is snoozed until this time.
Acknowledged by | The user who acknowledged the alarm.
Acknowledgment Comment | The comment entered by the user when they acknowledged the alarm.

{% include tip.html content="The alarm log is a Spotlight grid which may be saved to a file or the clipboard. To show / hide columns on the grid, right-click the grid headings and select Organize Columns. Refer to the help for more information on Spotlight grids." %}


## Filter the alarm log
{% include imageClient.html file="tb_action_changefilter.png" alt="Filter" %}
Filter the Alarm log from the Filter ribbon group.

Ribbon Select | Description
--------------|------------
Filter by Severity | Show alarms of a certain severity.
Filter by Time | Show alarms raised and canceled in the last 15 minutes, 30 minutes, 1 hour, 1 day, 1 week. Select All to show all alarms raised and canceled in the alarm log.

{% include note.html content="By default the alarm log grid is filtered to show alarms raised and canceled in the last 15 minutes. Use Filter by Time to extend this time period. If a long period of time is selected and a large number of connections are monitored then the alarm log may take some time to load." %}

## Actions on the alarm log
These actions are selectable from the Action ribbon group while the alarm log is on display. Some actions are enabled only when an alarm is selected.

Icon | Ribbon Select | Description
-----|---------------|-------------
{% include inline_imageClient.html file="tb_action_diagnose.png" alt="Diagnose" %} | Diagnose | Drilldown on data from the connection relevant to the selected alarm.
{% include inline_imageClient.html file="tb_action_settings.png" alt="Alarm Settings" %} | Alarm Settings | Configure the selected alarm.
{% include inline_imageClient.html file="tb_action_ignorealarm.png" alt="Ignore this Alarm" %} | Ignore this Alarm | Request Spotlight ignore this alarm and future cases of this alarm. For future cases, request Spotlight ignore this alarm for the current value or for the current connection. The choices are dependent on the type of alarm. This is a simplified interface for Configure \| Alarms \| Do not alarm for certain values.
{% include inline_imageClient.html file="tb_alarms_time.png" alt="Show in Alarms by Time" %} | Show in Alarms by Time | Show the selected alarm in alarms by time.
{% include inline_imageClient.html file="tb_grid_find.png" alt="Find" %} | Find | Find text in the display.

{% include links.html %}
