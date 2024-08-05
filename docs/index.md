# DataRun System, NMCP Yemen

## 1. Introduction

### 1.1 Purpose

The purpose of this document is to provide a comprehensive overview of the DataRun Information System, developed to manage activities and data for the National Malaria Control Program (NMCP). This document serves as a foundational reference for understanding the system's architecture, features, and functionalities. It is intended to facilitate the ongoing development, maintenance, and enhancement of the system, ensuring its effective implementation and integration with other health information systems.

### 1.2 Scope

This document covers the DataRun system in its entirety, including its design, architecture, key features, data management, database schema, user management, interoperability, security, user interface, workflow management, implementation details, and future enhancements. It provides detailed descriptions, diagrams, and visual aids to help stakeholders understand the system's components and their interactions.

### 1.3 Audience

The intended audience for this document includes:

- **Developers and Engineers**: For understanding the technical architecture and development requirements.
- **Project Managers and Coordinators**: For planning and overseeing the system's deployment and usage.
- **Data Analysts and Researchers**: For utilizing the data collection and visualization tools.
- **System Administrators**: For managing and maintaining the system's infrastructure and security.
- **Policy Makers and Stakeholders**: For evaluating the system's effectiveness and integration with national health strategies.

## 2. System Overview

### 2.1 System Description

DataRun is an advanced information system designed to streamline the management of activities and data for the National Malaria Control Program (NMCP). The system adopts a modular architecture, allowing for the dynamic configuration and management of projects, activities, teams, and assignments. It supports offline data collection through a mobile application, ensuring uninterrupted data capture in the field. DataRun facilitates data integrity, traceability, and interoperability with other health information systems through standardized APIs and adherence to interoperability standards.

### 2.2 Key Features

- **Modular Design**: DataRun's modular architecture separates activities, projects, teams, and assignments, promoting organization, scalability, and ease of future expansion.
- **Dynamic Data Forms**: The system allows the creation and configuration of data forms tailored to specific activities, ensuring relevant and accurate data collection.
- **Data Flow Management**: By specifying data entry and flow processes, DataRun enhances data integrity and traceability, critical for program monitoring and evaluation.
- **Offline Data Collection**: The mobile application supports data collection in remote areas without internet connectivity, with a synchronization mechanism to upload data once connectivity is restored.
- **Data Visualization Tools**: Pivot tables, charts, and dashboards are included for effective data analysis and the generation of user-friendly reports to aid in decision-making.
- **Open Architecture (API)**: A standard API facilitates seamless data exchange with other health information systems, promoting interoperability and data integration.
- **Interoperability**: Supports data interoperability with other health intervention areas (Eg. disease surveillance systems), quick and easy integration with existing platforms and systems such as supply chain, HRMS, LMIS, and DHIS2, facilitating interoperability and coordination at scale
- Uses a modular and standards-based architecture

### 2.3 Objectives

The primary objectives of the DataRun system are:

- **Enhance Data Management**: To improve the collection, processing, and storage of data related to NMCP activities.
- **Support Decision-Making**: To provide tools and reports that aid in informed decision-making for malaria control and prevention efforts.
- **Promote Interoperability**: To ensure seamless data exchange and integration with other health information systems.
- **Enable Field Data Collection**: To facilitate offline data collection in remote areas, ensuring comprehensive data capture regardless of internet connectivity.
- **Ensure Data Integrity**: To maintain high standards of data integrity and traceability through structured data flow management processes.
- Ability to reuse Activities data for planning and executing other activitiess leading to lower costs and lower turnaround time, leading to better estimation and planning.
- Provide visibility into stock availability and consumption data to enable supervisors to identify leakages/ wastages and avoid potential stock-outs 
