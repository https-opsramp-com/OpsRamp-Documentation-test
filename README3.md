[Back](Tables.md)....................................................................................................... [Next](Integrationstestfile.md)

## Introduction
Onboarding is bringing a new device onto the OpsRamp for the first time. The onboarded device is managed and monitored by OpsRamp.

> Three simple steps in onboarding are:
1. Add Devices
2. Assign Templates
3. Validate

## Onboarding Quick Start
Review Onboarding overall flow

1. Choose a scenario for Agent and Gateway deployment. See scenarios for deploying Agent and Gateway
2. Add Device Credentials.
3. Add devices. See instructions for adding devices
4. Assign monitoring templates. See instructions for assigning templates
5. Assign jobs. See instructions for configuring Jobs
6. Validate. See instructions for validating devices

## Core Concepts
### Device
Any element managed by OpsRamp is a device, like a Windows server or a network device.

### Discovery Profile
Discovery profile defines the range of devices that you want to discover, letting you to select devices specific to a Gateway or an Agent. You can create multiple discovery profiles, each with a different set of devices.

### Monitoring Template
Monitoring template lets you standardize monitoring settings across the organization by enabling you to specify the monitoring settings and assign them to the devices.

### Onboarding Policy
Whenever a device is discovered, you can create an onboarding policy such that it gets added to a specified device group. For example, whenever a network device is added or discovered it should be part of network device groups.

## Add Device
There are two ways to add devices to OpsRamp.

### Discovery
The devices available in the network can be discovered and added to OpsRamp. You can discover a specific device, devices present in a specific IP range and even multiple devicess.

### Discovery Profile
Discovery profile defines the range of devices you want to discover and lets you select devices to be managed or unmanaged. You can create multiple discovery profiles, each for a different set of devices. Each profile can then be saved and reused for future discoveries.

### Create Discovery Profile
1. Log into OpsRamp.
2. Click 'All Clients' and from the displayed list, select the Client.
3. From the options in the drop-down menu, click 'Setup'.
4. From the left pane, click Resource Management> Discovery and Deployment.
5. Select the client in which the discovery profile needs to be added and then click 'Add'.
6. Provide following discovery details
