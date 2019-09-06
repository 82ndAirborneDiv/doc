---
title: Mobile Policy Recommendation
description: CDC needs a framework for rapid deployment of in-house built mobile applications. We have partnered with DDPHSIS to pilot their app using this new OCIO process.
---

# Mobile Policy Recommendation

## Assumptions

* Current scope limited to CDC issued mobile devices.
* Further limited to Windows, iPhone, and Samsung devices.
* One user, one device.
* Data transmission over https.
* Data from app will be sent in JSON.

## Hurdles

* Communications in remote international locations is limited
* Updates to device platform impacted
* Updates to mobile app
* Wireless in foreign environment = increased chance of unauthorized data disclosure.
* Country offices typically are not staffed for management and support around mobile solutions.

## Requirements
* Mobile device shall be registered with CDC MDM.
* Mobile app must complete static and dynamic security scans
* Risks which cannot be corrected must be mitigated
* Https crypto must be at TLS 1.2 or higher.

## Future State
* Existing application deployment model relies on the SCCM process currently in place with ITSO.
* The vision for the future of mobile application deployment is via Device Application Store.
* Enhanced virtualization and application segmentation techniques will greatly improve OCIO ability to support rapid and scaled mobile deployments.

