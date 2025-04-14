# Account Manager Dashboard – Visual Analytics for Sales Performance

This repository contains project documentation and scripts for developing a dashboard to evaluate the performance of client-facing representatives in a professional services setting. The project demonstrates data engineering workflows, API integration, and dashboard visualizations to derive operational and revenue insights.

Note: Due to a non-disclosure agreement (NDA), the code and data for this project cannot be shared. This repository serves as a public case study summarizing the project scope, methodology, and key learnings.

---

### Business Problem

In many service-based organizations, evaluating the performance of client-facing roles (e.g., account managers) is essential for understanding business impact. However, performance tracking is often fragmented across systems, leading to missed opportunities for optimization and recognition.

This project addresses that challenge by building a centralized analytics dashboard to visualize key performance indicators such as revenue generated and operational workload, enabling leadership to make informed, data-driven decisions.

---

### Project Objective

The core objectives of this project include:

- Centralizing performance metrics such as **Revenue Generated** and **Client Orders Handled**.
- Providing interactive visualizations for leadership and operational teams.
- Creating a modular pipeline that can be extended or automated for continuous reporting.

These objectives aim to improve transparency, enhance decision-making, and streamline performance reviews.

---

### Solution Overview

The project implemented a complete data pipeline and visual analytics dashboard using open-source tools. The approach involved:

- **Data Extraction**: Pulling performance-related data from a spreadsheet and a REST API that supports multiple endpoints (e.g., client orders, personnel, companies).
- **Data Storage**: Structured data was loaded into a local SQLite database for aggregation and analysis.
- **Data Transformation**: Cleaned and normalized the data using Pandas, including type conversions, column standardization, and record filtering.
- **Visualization**: Created four types of visualizations using Plotly and Matplotlib:
  - Revenue by representative
  - Total order volume
  - Interactive pie chart for filtering contributions
  - Leaderboard of client activity by representative

This solution mimics a real-world business intelligence use case and is built to be both modular and replicable.

---

### My Contribution

I led the development of the technical backbone for this dashboard project. Contributions included:

- Building custom extractors for API and spreadsheet data.
- Designing and implementing the ETL pipeline with Pandas and SQLite.
- Developing visualizations with a focus on interactivity and clarity.
- Ensuring consistency between datasets from different sources.

---

### Business Value

This framework offers broad value for any organization with client-facing roles:

- **Operational Clarity**: Delivers a clear view of representative performance across multiple dimensions.
- **Recognition and Optimization**: Helps leadership identify top performers and areas for improvement.
- **Automation-Ready**: Modular code supports integration with workflow schedulers for regular updates.

---

### Challenges Encountered

- **API Structure**: Managing multiple endpoints and pagination increased integration complexity.
- **Data Consistency**: Required extensive transformation to unify schema across data sources.
- **Iteration Needs**: The dashboard evolved alongside stakeholder feedback and technical discoveries.

Despite these, the final product was robust, accurate, and easy to use.

---

### Lessons Learned

This project emphasized several key takeaways:

- The value of designing flexible ETL pipelines for varied data sources.
- The importance of clean, intuitive visualizations for stakeholder adoption.
- The need for modular code when iterating on business logic or automation goals.

This dashboard framework is adaptable and can be repurposed for many sales or operations-oriented data workflows.
