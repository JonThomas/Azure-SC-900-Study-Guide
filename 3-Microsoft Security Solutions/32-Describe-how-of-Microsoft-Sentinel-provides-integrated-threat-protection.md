# Describe how of Microsoft Sentinel provides integrated threat protection

[Describe how of Microsoft Sentinel provides integrated threat protection](https://docs.microsoft.com/en-us/learn/modules/describe-security-capabilities-of-azure-sentinel/3-describe-sentinel-provide-integrated-threat-protection)

Microsoft Sentinel provides a single solution for alert detection, threat visibility, proactive hunting, and threat response. It is both a SIEM and SOAR tool. 

* Collect data using Data connectors
    * Azure AD connector
    * Trusted Automated eXchange of Indicator Information - TAXII - for Threat Intelligence !?
    * Windows Event Logs
    * AWS
* Azure Monitor Workbooks - used to organize and communicate data insights: Metrics and trends.
    * Sentinel integrates with Azure Monitor Workbooks for this functionality.
    * Drill down to raw data 
    * "See sign-ins by Alice Whooper, by device types"
* Analytics
    * Alerts: You'll get notified when anything suspicious occurs
    * Alerts by Microsoft, built on machine learning models
    * Alerts edited and set up by your organization
* Incidents
    * Created when an alert is triggered.
    * Incidents can be assigned and change status
    * Based on Analytics
* Hunting
    * Search and Queries tool
    * Bookmark, share and group events
* Notebooks
    * ???
* Playbooks
    * A collection of procedures to automate and orchestrate your response.
    * Run manually or automatically, when specific alerts are triggered
    * Based on Azure Logic Apps

[Return to Microsoft Security Solutions](README.md)

[Return to Table of Contents](../README.md)