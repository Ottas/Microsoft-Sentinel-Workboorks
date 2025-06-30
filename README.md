# Microsoft-Sentinel-Workboorks

## Objective

In my lab environment, I'm building Microsoft Sentinel workbooks with interactive map views that show activities.

- Entra ID (Azure) Authentication Success  
- Entra ID (Azure) Authentication Failures  
- VM Authentication Failures  
- Malicious Traffic Entering the Network




### Skills Learned

-Hands-on experience with Microsoft Sentinel for creating custom security workbooks and visualizations.
-Practical use of Kusto Query Language (KQL) to analyze log data and build dynamic dashboards.
-Improved ability to detect patterns and anomalies based on IP-based activity and event correlation.
-Better understanding of SIEM workflows, from data collection to visualization.
-Familiarity with GeoIP mapping and visual threat representation using IP origin data.

### Tools Used

- Microsoft Azure – cloud environment where all resources and logging are hosted
- Microsoft Sentinel – SIEM/SOAR tool used for log analysis, detection, and visualization
- Kusto Query Language (KQL) – used to write queries and build workbooks

## Steps

                        Sentinel → Threat Management → Workbooks → Add a Workbook
 
## Entra ID (Azure) Authentication `Success`
![1b](https://github.com/user-attachments/assets/633c70d2-add8-42a4-a6e5-13ccd970d178)
![1c](https://github.com/user-attachments/assets/73e4c90c-42f0-4c4b-bfd2-3c7b212de554)


-> We see a bunch of sign‑in activities, including the identity of the person logging in, as well as the `resultType`, which indicates who has successfully logged in.

---

## - Entra ID (Azure) Authentication `Failures`

![222](https://github.com/user-attachments/assets/e59ae081-de5c-4d50-8300-fb4065295e60)
![22222](https://github.com/user-attachments/assets/cbd5a7d2-facc-4f59-af1f-d095020fdf73)

---

## VM Authentication `Failure`

![3333333](https://github.com/user-attachments/assets/53aa8eef-46ac-44dd-9131-176529f0c75c)
![555555555](https://github.com/user-attachments/assets/87cd7b1f-608b-41aa-a7f3-6d959f2b470e)

-> This applies to all VMs that have been onboarded to MDE.

---

## Malicious Traffic Entering the Network

![5a](https://github.com/user-attachments/assets/fdf222a2-c36f-4d27-b453-99e3623b4319)
![5c](https://github.com/user-attachments/assets/905a954e-685d-4ed8-a0a7-73b73f91ad5d)

-> It basically counts the malicious traffic from individual IP addresses and then maps it.

---

## Summary

 I ran this exercise in our student Network, turning login, resource and network logs into simple world‑map dashboards. It was a great way to learn hands‑on Sentinel and KQL.










