---
title: Add / Remove Connections
tags: [connection_details]
summary: "Connect Spotlight to the SQL Server, Windows Server and other supported connection types in your enterprise. Add and remove connections and configure connection properties."
sidebar: p_enterprise_sidebar
permalink: enterprise_connect_addremove.html
folder: SpotlightEnterprise
---



## Add new connection

From the Spotlight Client

1. Click **Configure \| Connections**.
2. Double click **Add new connection**. You may be prompted to enter New Connection Details.
3. You will be prompted to fill in the connection properties.

The connection properties are dependent on the connection type.

<ul>
{% assign sorted_pages = (site.pages | sort: 'title') %}
{% for page in sorted_pages %}
{% for tag in page.tags %}
{% if tag == "connection_details" %}
<li><a href="{{ page.url | prepend: site.baseurl}}">{{page.title}}</a></li>
{% endif %}
{% endfor %}
{% endfor %}
</ul>

Properties | Description
-----------|------------
Details | The connection details are required. The details are dependent on the connection type.
Tags | Tags are a free form organizational tool that may be optionally applied to Spotlight connections. Tag names represent a project, geographic region or other indicator of interest to you and your organization. Multiple tags can be assigned to one connection.

## Discover

The Connection Discovery Wizard is used to locate resources on the network to add as Spotlight connections. The Connection Discovery Wizard can be used to locate SQL Server instances or Windows Servers. See the Connection Discovery Wizard.

From the Spotlight Client

1. Click Configure \| Connections.
2. Double click **Discover** from the list of All connections, SQL Server or Windows.


## Delete

From the Spotlight Client

1. Click **Configure \| Connections**.
2. Right-click on the connection and select **Delete**.

{% include tip.html content="If you have customized the alarms set for this connection or the scheduling information then those customizations will be deleted with the connection. You may like to backup your customizations before you delete the connection. To do so, backup the \Agent\Conf folder in the Spotlight Spotlight Diagnostic Server installation folder." %}

{% include links.html %}
