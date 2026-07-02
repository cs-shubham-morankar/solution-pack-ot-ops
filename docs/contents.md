| [Home](../README.md) |
| -------------------- |

# Contents

## Connectors

| Connector Name                           | Description                                                                                                                                                                      |
|:-----------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ServiceNow                               | ServiceNow connector provides functionality to create, read, update and delete records of Table and Catalog type                                                                 |
| Fortinet FortiAuthenticator              | FortiAuthenticator provides centralized authentication services for the Fortinet Security Fabric including single sign on services, certificate management, and guest management.|

>[!WARNING]
>After deployment, this solution pack installs or upgrades the connector to the latest version.

## Playbook Collection

| 02 - Use Case - Contractor Policy Automation |
|:---------------------------------------------|

| Playbook Name                              | Description                                                                                                                                                                   |
|:-------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sync SNOW User Requests                    | Using this playbook, open requests are retrieved from ServiceNow, and groups are fetched from FortiAuthenticator.                                                             |
| Create new Task Record                     | Using this playbook, to create a new network request record in ServiceNow.                                                                                                    |
| > Create FAC user per task found           | Using this playbook, the workflow automates user provisioning and group assignment in FortiAuthenticator, while maintaining synchronization and status updates in ServiceNow. |

| 02 - Use Case - FortiGate Alerting |
|:-----------------------------------|

| Playbook Name                               | Description                                                                                                                                                                                                                                                         |
|:--------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Receive FortiGate Trigger                   | This playbook is designed to correlate FortiGate-triggered events with ServiceNow change records and automatically decide whether to update an existing change record or create a new P1 incident.                                                                  |
| > Snow Firewall Asset Query                 | Using this playbook, the extracted serial number is used to query the asset inventory and retrieve the corresponding asset details.                                                                                                                                 |
| > Snow Task CI Query                        | Using this playbook, the asset information is used to query the associated ServiceNow CI Tasks for that asset.                                                                                                                                                      |
| > Snow Change Query                         | Using this playbook, the workflow identifies any configuration or operational changes that occurred within a ±30-minute window of the event time.                                                                                                                   |

> [!WARNING] 
> 
> It is recommended to clone these playbooks before making any customizations to avoid loss of information while upgrading the solution pack.
> 

# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|