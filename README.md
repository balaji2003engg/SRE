# SRE

Site Reliability Engineering (SRE) is a discipline that incorporates aspects of software engineering and applies them to infrastructure and operations problems. Here are some key terms and concepts commonly used in SRE:
 
1. **Service Level Objective (SLO):** A target level of reliability for a service. SLOs are specific, measurable goals that the service aims to achieve, such as 99.9% uptime.
 
2. **Service Level Indicator (SLI):** A metric used to measure the performance of a service. SLIs are used to assess whether SLOs are being met. For example, the latency of requests or error rates can be SLIs.
 
3. **Service Level Agreement (SLA):** A formal agreement between a service provider and a customer that specifies the expected level of service, including SLOs. SLAs are often legally binding.
 
4. **Error Budget:** The amount of allowable errors or downtime within a defined period. It’s derived from the SLO. If a service's error budget is exhausted, it indicates that the service is not meeting its reliability targets.
 
5. **Toil:** Repetitive, manual work that is operational in nature and does not add enduring value. SRE aims to reduce toil by automating repetitive tasks.
 
6. **Incident:** An unplanned interruption or reduction in quality of a service. Incidents can range from minor issues to major outages.
 
7. **Postmortem:** A review conducted after an incident to analyze what went wrong and how to prevent similar incidents in the future. This typically involves identifying root causes and creating action items for improvement.
 
8. **Runbook:** A document or collection of documents that provide instructions for operating a system or service, often including steps for handling incidents or routine tasks.
 
9. **Capacity Planning:** The process of ensuring that a system has enough resources (e.g., CPU, memory, storage) to handle its expected load, both currently and in the future.
 
10. **Load Balancer:** A device or software that distributes incoming network traffic across multiple servers to ensure that no single server becomes overwhelmed.
 
11. **Chaos Engineering:** The practice of intentionally introducing failures or disruptions into a system to test its resilience and improve its reliability.
 
12. **Golden Signal:** Key metrics that are critical to understanding the health of a service. Google’s SRE book identifies latency, traffic, errors, and saturation as the four golden signals.
 
13. **Reliability:** The ability of a service to consistently perform its intended functions without failure. In SRE, this is often measured against the SLOs and error budget.
 
14. **Change Management:** The process of managing changes to the system in a controlled manner to minimize the risk of disruptions.
 
15. **Observability:** The capability of a system to provide insights into its internal workings through metrics, logs, and traces. It helps in understanding and troubleshooting the system’s behavior.
 
These terms and concepts are fundamental to the practice of SRE and help in maintaining reliable and efficient systems
