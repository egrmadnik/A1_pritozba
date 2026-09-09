# Complaint Regarding A1 4G/5G Internet Service Outage

> **Language / Jezik:** [Slovenska različica](A1_pritozba.md)

**Since Monday, September 7, 2026, A1 has failed to provide a basic, functional internet connection.**

For several days, I have been **completely without usable internet access**, despite being located only approximately **200 meters** from the base station.

## Technical Status

I am using a **ZTE888B** modem. The modem and local customer-premises equipment operate normally; however, the modem currently establishes only a **3G connection**.

On the modem, the **`Network` LED is blinking blue**, which signifies that the modem is connected / registered to the **3G network**. A **4G/LTE or 5G connection is not established**.

This is a critical technical distinction because:

* The modem is fully operational,
* The SIM card is inserted and recognized,
* The modem successfully connects to the mobile network,
* A **3G connection is established**,
* However, **4G/LTE and 5G connections fail**,
* Therefore, internet access is unusable or practically non-existent.

Given the above, it is highly unlikely that the problem lies within my local equipment. **The modem is clearly functional and communication with the cellular network is possible, but the network fails to provide the expected 4G/5G connection.**

It is particularly problematic that I am located only approximately **200 meters** from the base station, where one would expect normal 4G/5G signal coverage if it were being delivered properly at this site.

### Troubleshooting Steps Performed

Following customer support instructions, I have repeatedly performed all standard procedures:

* Powering down the modem,
* Waiting,
* Powering back on,
* Resetting the modem to factory defaults,
* Removing and reseating the SIM card.

**None of these procedures resolved the issue.**

Since the modem still operates exclusively on **3G** and neither 4G/LTE nor 5G is established after all these steps, repeating basic user-side troubleshooting is meaningless. What is required is **actual diagnostics of the mobile network, base station, and service configuration**.

---

## Request for Technical Diagnostics on A1's Side

Based on the described condition, please treat this issue as a **network / radio access fault** and no longer as customer equipment trouble.

I request verification of the following technical parameters:

### 1. Device Registration in the Network

Verify whether the SIM / subscriber profile is properly registered and authorized for:

* **4G/LTE (E-UTRAN)**,
* **5G NR**,
* The appropriate APN for data traffic,
* Data service usage at my location.

Specifically, please check whether there is any restriction, provisioning bar, or misconfiguration on the network side that forces the device to remain on 3G.

### 2. LTE/5G Coverage and Cell Status

Please inspect the specific base station / cell sector that my device attempts to connect to.

In particular, verify:

* Whether the **LTE sector/cell is active**,
* Whether the **5G NR cell is active**,
* Whether an outage has occurred on a specific sector,
* Whether the base station is running in a degraded mode,
* Whether alarms or errors are logged on the base station,
* Whether maintenance, upgrades, or configuration changes were carried out in recent days,
* Whether traffic has been rerouted or throttled/restricted to 3G due to a fault or maintenance.

### 3. Radio Access and Technology Selection

Since the device detects and connects to 3G without issues, yet **LTE/5G fails to establish**, please inspect the technology selection and **cell selection / cell reselection** behavior.

Specifically:

* Does the device receive LTE/5G broadcast system information at this location?
* Is the LTE/5G cell permitted for my SIM / subscriber profile?
* Does the network reject the device during attach / registration?
* Is there an issue with the handover or reselection from 3G to LTE?
* Is the radio access network configuration at this location correct?

### 4. Verification of Radio Parameters

If possible, please verify or provide the measured radio parameters for my location:

* **RSRP**,
* **RSRQ**,
* **SINR**,
* The active **LTE band / frequency band**,
* The serving cell identifiers (**Cell ID / eNB ID**),
* For 5G, the corresponding **NR band** and NR cell information.

Given that the device is approximately **200 m from the base station**, it should be evaluated whether radio parameters on the LTE/5G sector are within normal levels or whether an anomaly exists in the radio access network.

### 5. Verification of Subscriber Profile

Please also verify whether my subscriber profile is properly provisioned for:

> **LTE / 4G + 5G data access**

If the subscriber profile is configured correctly, please determine why the device still registers strictly on 3G.

### 6. Verification of Network Logs and Errors

Please review network signaling logs for my SIM / device regarding attempts to register on LTE/5G.

If registration attempts were rejected, inspecting the specific **reject cause** would directly indicate whether the cause is:

* Registration rejection,
* A subscriber profile issue,
* An authorization / authentication issue,
* Cell misconfiguration,
* A core network issue,
* Or a radio access issue.

---

## Important

Please **do not close this ticket with instructions to reboot, reset the modem, or reseat the SIM card**, as these steps have already been carried out multiple times without any effect.

The fact that:

1. The modem is operational,
2. The SIM card is detected,
3. The device registers with the mobile network,
4. A 3G connection is established,
5. 4G/LTE and 5G fail to establish,

is a strong and clear indicator that the problem must be investigated at the **network/radio access and subscriber configuration level**.

---

## Customer Support Conduct

Even more problematic than the technical failure itself is the **manner of customer support**.

Every time I call, I must recount the **entire story from the beginning**, as if previous calls and logged tickets never existed or were never recorded.

Over and over, I am given the same routine, ineffective instructions. Despite having completed them multiple times and explicitly stating that they did not help, the process is repeatedly restarted from scratch.

## Promised Call from Technical Support

I was also promised a **call from technical support**, which never occurred.

After several days of complete service disruption, repeated calls, and a total lack of concrete technical handling, I can only conclude:

> **Such unprofessional conduct is unacceptable.**

From a service provider **billing full price for service**, I expect at minimum:

* Basic communication,
* Proper documentation and tracking of the reported issue,
* Technical diagnostics on the network side,
* Verification of the base station and associated cells,
* Honoring commitments and promised return calls,
* And above all, **actual resolution of the issue**.

## Summary

| Parameter | Status |
| --- | --- |
| Modem | **ZTE888B – operational** |
| SIM Card | **Detected** |
| 3G | **Working / connection established** |
| 4G/LTE | **Not working** |
| 5G | **Not working** |
| Local Equipment | **No apparent issues** |
| Distance to Base Station | **~200 m** |
| Internet Access | **Down / unusable** |
| Resets and Basic Steps | **Performed repeatedly without result** |
| Technical Support Call-back | **Not performed** |
| Required Action | **Network / radio diagnostics** |

**The issue is no longer about user settings or restarting the modem. Technical investigation on A1's side is required to determine why a 3G connection can be established at this location while 4G/LTE and 5G do not work.**

I request a **concrete technical investigation and a written reply** stating what was checked, where the fault was identified, and when normal service will be restored.
