# SMS Campaign Server

**Master Repository** of the project

## Project Overview

This project is designed to implement a complete system for managing SMS campaigns. The system enables users to create and manage SMS campaigns, interact with an SMS gateway, and visualize statistical data related to the campaigns.
The system consists of the following components:

### Backend
The backend is a **Node.js server** that communicates with an SMS gateway via the **SMPP protocol**. Its responsibilities include:
- Sending bundles of SMS requests to the SMS gateway and handling responses.
- Storing all related data for statistical purposes in a **MongoDB** database.
- Providing APIs for retrieving statistical data and managing campaigns.

[**Backend Repository**](https://github.com/FedBio01/sms-campaigns-backend)

### Frontend
The frontend is a user interface, developed with React.js, for managing SMS campaigns and analyzing campaign statistics. It allows users to:
- Create and manage new SMS campaigns.
- View statistics for ongoing and completed campaigns.

[**Frontend Repository**](https://github.com/FedBio01/sms-campaigns-frontend)

## Note
This project was created as part of an internship program and aims to provide hands-on experience in developing a complete system.

---
