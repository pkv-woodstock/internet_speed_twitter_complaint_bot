# Internet Speed Complaint Bot

## Description

The Internet Speed Complaint Bot is a Python application that uses Selenium to automatically run speed tests on speedtest.net, compare the results with the promised upload and download speeds from your ISP, and then tweets a complaint to the service provider if the speeds are not met.

## Features

- **Automated Speed Tests**: Uses Selenium to simulate a user running a speed test on speedtest.net.
- **Speed Comparison**: Compares the results with the speeds promised by your ISP.
- **Automated Twitter Complaints**: If the speed is below what's promised, it automatically sends a tweet to your ISP's Twitter handle.
- **Regular Monitoring**: Can be scheduled to run tests at regular intervals.
- **Logs**: Keeps a record of all the speed tests for documentation.
