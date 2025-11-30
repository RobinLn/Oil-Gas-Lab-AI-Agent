# Oil-Gas-Lab-AI-Agent
AI agents that analyze oil and gas lab samples and generate reports automatically

Completed the Agents Intensive – Capstone Project!
As part of the 5-Day AI Agents Intensive Course with Google (Nov 10–14, 2025), I built an Enterprise AI Agent that automates lab data analysis and generates client-ready oil & gas sample reports.

Problem Statement

Oil and gas labs generate extensive data from various tests on samples, including metals, sulfur content, physical properties, and more. Analysts currently spend a lot of time manually compiling these results into client-ready reports, which is labor-intensive, prone to human error, and slows down decision-making. Automating this process is critical for improving efficiency, accuracy, and timeliness in lab reporting.

Why agents?

AI agents are ideal for this problem because they can work in parallel to analyze multiple aspects of lab data simultaneously, follow structured instructions, identify anomalies, and generate coherent summaries. Unlike traditional scripts, agents can combine reasoning, tool usage, and natural language generation to produce actionable, client-ready reports automatically.

What you created

I built a multi-agent system called Enterprise Agent for Lab Data – Oil & Gas. The architecture includes:

1.Memory & Memory Management Agents – Store lab data, manage context, and track analysis across sessions.

2.Analysis Agents – Parallel agents that evaluate metals, physical properties, sulfur content, and other parameters.

3.Aggregator Agent – Collects outputs from all analysis agents, flags anomalies, and compiles a clean, readable report.

4.Deployment – The system is deployed on Vertex AI Agent Engine for scalable, low-latency execution.

Demo

Here’s how the system works in practice:

- The user submits a lab sample.

- Parallel agents analyze metals, physical properties, and sulfur content simultaneously.

- The aggregator compiles all findings, identifies anomalies, and generates a polished summary.

- Output: a complete, client-ready lab report with recommendations and flagged issues.

Example query: “Generate a full lab report for Sample #47.”
The agents automatically provide a detailed report including all test results and insights.

The Build

Tools & Technologies:

- Python and ADK (Agent Development Kit)

- Vertex AI Agent Engine for deployment

- Async agent queries for parallel processing

- GitHub for version control and collaboration

Process:

- Created separate notebooks for each agent type (Analysis, Memory, Aggregator, Deployment).

- Defined agent behavior using system prompts and tool functions for lab data analysis.

- onfigured deployment settings via .agent_engine_config.json and deployed to Vertex AI.

- Tested agents using async streaming queries to validate report generation.

If I had more time, this is what I'd do

- Expand the system to handle more lab tests, such as viscosity, flash point, and advanced chemical analysis.

- Add a real-time dashboard to visualize ongoing analyses.

- Integrate external lab instruments for live data ingestion.

- Include machine learning models for predictive insights based on historical lab results.

- Enhance the anomaly detection system with advanced statistical methods.
