# Resources

## Azure Security Center and Azure Defender

We spoke about [Azure Security Center](https://docs.microsoft.com/en-gb/azure/security-center/security-center-intro).

*   Azure Security Center provides capabilities around managing your Cloud Security posture, leveraging off policies to detect potential vulnerabilities and areas of improvement. It also provides some capabilities around workload protection.
*   Azure Security Center also relies on Azure [Policies](https://docs.microsoft.com/en-gb/azure/governance/policy/overview), which allows you to create rules and effects for your resources in Azure and report on compliance to those rules. We have a gallery of [sample policy definitions](https://docs.microsoft.com/en-gb/azure/governance/policy/samples/). Recommended reading:
    *   [Understanding Azure Policy Effects](https://docs.microsoft.com/en-gb/azure/governance/policy/concepts/effects)
    *   [Azure Policy definition structure](https://docs.microsoft.com/en-gb/azure/governance/policy/concepts/definition-structure)
    *   [Determine causes of non-compliance](https://docs.microsoft.com/en-gb/azure/governance/policy/how-to/determine-non-compliance)
    *   Tutorial: [Create and manage policies to enforce compliance](https://docs.microsoft.com/en-gb/azure/governance/policy/tutorials/create-and-manage)
    *   Tutorial: [Working with Security Policies](https://docs.microsoft.com/en-gb/azure/security-center/tutorial-security-policy)
    *   [Azure security policies monitored by Security Center](https://docs.microsoft.com/en-gb/azure/security-center/security-center-policy-definitions)
*   We spoke about your [Secure Score and how to improve it](https://docs.microsoft.com/en-us/azure/security-center/security-center-secure-score).
*   We mentioned the capabilities of [Azure Defender for Servers](https://docs.microsoft.com/en-us/azure/security-center/defender-for-servers-introduction), you can read more about them here:
    *   [Just in Time Access](https://docs.microsoft.com/en-us/azure/security-center/security-center-just-in-time)
    *   [Adaptive Application Controls](https://docs.microsoft.com/en-us/azure/security-center/security-center-adaptive-application)
    *   [File Integrity Monitoring](https://docs.microsoft.com/en-us/azure/security-center/security-center-file-integrity-monitoring)
    *   [Adaptive Network Hardening](https://docs.microsoft.com/en-us/azure/security-center/security-center-adaptive-network-hardening)
*   We also mentioned that you can integrate ASC with [Defender for Endpoint](https://docs.microsoft.com/en-us/azure/security-center/security-center-wdatp) for advanced threat protection detection and response capabilities.
*   For downstream integration into your SIEM or another system, you can use [the continuous export capability](https://docs.microsoft.com/en-us/azure/security-center/continuous-export?tabs=azure-portal) in Security Center, and stream the events, alerts and recommendations to an Event Hub.

Learning resources:

*   [Identify security threats with Azure Security Center](https://docs.microsoft.com/en-us/learn/modules/identify-threats-with-azure-security-center/)
*   [Protect your servers and VMs from brute-force and malware attacks with Azure Security Center](https://docs.microsoft.com/en-us/learn/modules/secure-vms-with-azure-security-center/)
*   Video: [Azure Power Lunch: Azure Security Center](https://www.youtube.com/watch?v=0-DV3DFeHWc)
*   Video: [Securing the hybrid cloud | Azure Security Center Part 1](https://www.youtube.com/watch?v=3Ddli1q3CcQ)


## Azure Sentinel

<p>We had a quick look at <a href="https://docs.microsoft.com/en-gb/azure/sentinel/overview">Azure Sentinel</a>. Azure Sentinel is a Security Information and Event Management tool. Here are some resources for you:</p>

<p>It relies on <a href="https://docs.microsoft.com/en-gb/azure/azure-monitor/learn/quick-create-workspace">a Log Analytics workspace</a> for data collection, and we will discuss the principals for workspace design in future sessions, further reading:</p>

<ul>
  <li><a href="https://techcommunity.microsoft.com/t5/Azure-Sentinel/Best-practices-for-designing-an-Azure-Sentinel-or-Azure-Security/ba-p/832574">Best practices for designing an Azure Sentinel or Azure Security Center Log Analytics workspace</a></li>
</ul>

<p>Some additional reading on Workspace design:</p>

<ul>
  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/design-logs-deployment">Designing your Azure Monitor Logs deployment</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/roles-permissions-security#security-considerations-for-monitoring-data">Security considerations for monitoring data</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/manage-cost-storage">Manage usage and costs with Azure Monitor Logs</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-ingestion-time">Log data ingestion time in Azure Monitor</a></li>
</ul>

<p>Additional resources:</p>

<ul>
  <li>Steps for <a href="https://docs.microsoft.com/en-us/azure/sentinel/quickstart-onboard#enable-azure-sentinel-">enabling Sentinel</a></li>

  <li>Tutorial: <a href="https://docs.microsoft.com/en-us/azure/sentinel/tutorial-detect-threats-built-in">Use built-in analytic rules to detect threats</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/sentinel/connect-data-sources">Connect your data sources</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/sentinel/tutorial-investigate-cases">Investigate your cases</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/sentinel/tutorial-monitor-your-data">Use Workbooks to monitor your data</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/sentinel/notebooks">Use Jupyter notebooks to hunt for security threats</a></li>

  <li>Video: <a href="https://www.youtube.com/watch?v=Q-kkasdSA-E">Microsoft Threat Protection | Azure Sentinel and Microsoft 365 Threat Protection (Microsoft Ignite)</a></li>

  <li>Video: <a href="https://www.youtube.com/watch?v=_InlU0DbiNA">Azure Advent Calendar – Azure Sentinel</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/sentinel/connect-syslog">Connect your external solution using Syslog</a></li>

  <li>Blog Post: <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-syslog-cef-and-other-3rd-party-connectors-grand/ba-p/803891">Azure Sentinel: Syslog, CEF and other 3<sup>rd</sup> party connectors grand list</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-sources-syslog">Syslog data sources in Azure Monitor</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-sources-windows-events">Windows Event Log</a> data source in Azure Monitor Log Analytics</li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-sources-performance-counters">Performance Counters</a> data source in Azure Monitor Log Analytics</li>

  <li>Blog Post: <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/extending-azure-sentinel-apis-integration-and-management/ba-p/1116885">Extending Azure Sentinel: APIs, Integration and management automation</a></li>
</ul>

<p>Many of the components rely on querying the logs, here is some additional guidance on using Logs queries:</p>

<ul>
  <li>Kusto Query Language training: <a href="https://www.pluralsight.com/courses/kusto-query-language-kql-from-scratch">https://www.pluralsight.com/courses/kusto-query-language-kql-from-scratch</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/get-started-queries">Get started with log queries in Azure Monitor</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/query-language">Azure Monitor log queries</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/examples">Azure Monitor log query examples</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/log-query-performance">Writing efficient log queries</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/splunk-cheatsheet">Cheat sheet: Splunk to Azure Monitor log query</a></li>

  <li><a href="https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/sql-cheatsheet">Cheat sheet: SQL to Azure Monitor log query cheat sheet</a></li>
</ul>