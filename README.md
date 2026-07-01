## Release Information

---

- **Version**: 1.0.0
- **Certified**: No
- **Publisher**: Fortinet
- **Contributor**: Dylan Spille
- **Compatible Version**: FortiSOAR v7.6.2 and later

---

# Overview

---

## Introduction

---

### Contractor Access Provisioning

Managing contractor onboarding and access provisioning manually across multiple systems can lead to delays, operational overhead, and inconsistent access management. The **Contractor Access Provisioning** use case automates the end-to-end request handling process by integrating **ServiceNow** and **FortiAuthenticator**.

Using workflow automation, the solution retrieves open requests from ServiceNow, validates user information, provisions users in FortiAuthenticator when required, assigns users to the appropriate groups, and updates request status throughout the process. This automation helps organizations accelerate onboarding, maintain consistency, and reduce manual administrative effort.

---

### FortiGate Alerting

Monitoring and validating operational changes across network infrastructure often requires correlating device events with change management records. The **FortiGate Alerting** use case automates this process by integrating **FortiGate webhook events** with **ServiceNow** workflows.

The solution receives FortiGate alerts, extracts device information, validates related assets and operational records, and checks for associated change activities within a defined time window. Based on the correlation results, the workflow either updates existing ServiceNow records or creates a new incident for investigation. This automation improves operational visibility, accelerates response times, and strengthens change governance across network environments.

---

## Next Steps 

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) |
|----------------------------------------------|------------------------------------------------|--------------------------|--------------------------------|