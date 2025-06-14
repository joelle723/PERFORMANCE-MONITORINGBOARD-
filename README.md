# PERFORMANCE-MONITORINGBOARD-
COMPANY: CODTECH IT SOLUTIONS

NAME: JOELLE AMBAR

INTERN ID: CT08DN1843

DOMAIN: .NET WEB DEVELOPMENT

DURATION: 8 WEEKS

MENTOR: NEELA SANTHOSH

DESCRIPTION OF THE TASK

The objective of Task 2 was to integrate performance monitoring capabilities into a .NET-based application using Azure Application Insights. The primary deliverable was a functional and insightful monitoring dashboard capable of tracking key performance metrics such as request and response times, real-time server health, system trends, and error rates. The goal was to enable developers to observe the application’s behavior in real time, identify bottlenecks, and quickly respond to any performance issues before they impact users. This type of observability is essential for maintaining the reliability, responsiveness, and stability of modern software systems.

My Implementation: Building the Performance Monitoring Module
To implement this task, I developed a .NET Console Application named MonitoredApp. This application was instrumented to simulate system activity while transmitting telemetry data to Azure. The implementation focused on two major components: the code logic within the application, and the Azure Application Insights integration that collects and analyzes the performance data.

The entire application logic was written in the Program.cs file. This file includes code to simulate processing, delays, and error handling, so that meaningful data is available for Azure to collect. I also added trace and log messages, which help monitor how the application behaves during execution. These logs were configured to be automatically sent to Azure through Application Insights.

To integrate Application Insights, I used Visual Studio’s built-in telemetry tools. By selecting "Instrument your application" and choosing ".NET" as the platform, Visual Studio added the necessary configuration and NuGet packages to enable telemetry. After linking the project to my Azure resource, I confirmed that the Instrumentation Key was inserted into the project, allowing the application to securely transmit logs and traces.

Azure Configuration and Dashboard
In the Azure portal, I created an Application Insights resource named CodTechDashboardApp. This resource receives and stores all telemetry data coming from my application. I then configured the project to connect to this resource, ensuring that logs such as trace messages, exceptions, and performance timings were sent directly to the Azure cloud.

To visualize the data, I created a custom Azure Dashboard titled CTmonitoringdashboard. On this dashboard, I added a line chart specifically to display the average response time. This metric is essential for identifying slow operations or performance degradation over time. I also enabled Live Metrics, a feature that provides real-time data about server load, request rates, failure rates, and memory usage.

Validation and Outcome
Once the application was running, I observed the results in the Azure portal. Logs and traces appeared in real time, and the dashboard correctly displayed the configured metrics. The Live Metrics view confirmed that the application was actively sending telemetry data and allowed me to verify the correctness of the setup. The result was a complete, functioning performance monitoring module that provides full observability over the application's health and behavior.
This implementation meets the requirements of Task 2 by delivering a working, secure, and insightful monitoring solution using Azure Application Insights.

OUTPUT 
![Image](https://github.com/user-attachments/assets/2d4bca90-bfcf-407e-85dc-51420b62b066)
![Image](https://github.com/user-attachments/assets/46a4e8c5-4df5-4461-892a-7d29fc8f5b4c)
