# Troubleshooting Guide for Uptime Kuma Monitor

Uptime Kuma Monitor is a simple and easy-to-use macOS menubar app that allows you to monitor the status of your Uptime Kuma service. However, there might be times when you encounter issues while using the app. This guide provides solutions to common issues you might run into while using Uptime Kuma Monitor.

## Offline Network Connectivity

If you're unable to access the Internet, Uptime Kuma Monitor will be unable to retrieve the status of your Uptime Kuma service. To fix this issue, make sure your Mac is connected to the Internet and try again.

## Unable to Access the Status Page

If Uptime Kuma Monitor is unable to access the status page, there could be a few reasons for this:

* Server not accessbible in current network. It usually happens when you have self hosted Uptime Kuma server in your home network, but then switch to a public network.
* Incorrect URL: Make sure the URL of your Uptime Kuma status page is correct.
* Blocked by Firewall: If you're behind a firewall, make sure the firewall is not blocking access to the status page.
* Server Down: If the Uptime Kuma server is down, Uptime Kuma Monitor will be unable to retrieve the status of your Uptime Kuma service.
* Status Page 404 (Not Found)

## Failing to Parse the Status Page Content

Uptime Kuma Monitor relies on parsing the status page content to retrieve the status page config of your Uptime Kuma service and generate heartbeats endpoint.

If Uptime Kuma Monitor is unable to parse the status page content, it might mean Uptime Kuma updates its status page format and the monitor app is not update to date yet, please file a [bug report](https://github.com/rebornix/uptime-kuma-monitor/issues/new).



