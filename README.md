## Tenant Management Application 

#### Introduction
This document outlines the design for a Tenant Management Application. The application is built using the Frappe framework and allows agents to manage houses, tenants, owners of rented properties, rental agreements, billing, maintainance requests, and payment of rent.
#### Scope
This application will be used by agents to manage houses and tenants. It will allow agents to capture information about the houses and tenants they are managing. The application will also allow agents to generate rental agreements, bill tenants for rent, track maintenance requests made by tenants and track payments made by tenants.
System Architecture
The Tenant Management Application will be built using the Frappe framework. The application will be hosted on a cloud server and can be accessed by agents using a web browser.
#### Database Design
The following are the doctypes that will be used to store data for this application:
- House
- Tenant
- Owner
- Agent
- Rental Agreement
- Billing
- Payment
- Maintenance Request
- Rents Paid
#### User Roles and Permissions
The following roles and permissions will be implemented in this application:
- Owner: can view details of their rented properties and payment history.
- Tenant: can view details of their rental agreement, billing, and payment history. A tenant can also create a maintenance request,
- Agent: can view and manage all properties, tenants, owners, rental agreements, billing, maintenance requests and payments.
#### Workflow
The following workflow were implemented in the Tenant Management Application:
- Agent creates a house record
- Agent creates a tenant record and assigns them to a house
- Agent creates an owner record and assigns the house to the owner
- Agent creates a rental agreement between the tenant, himself and the owner
- Agent creates a billing record for the tenant
- Tenant pays rent
- Agent adds record of payment
- Agent marks the billing record as paid
- Tenant requests for maintenance
- Agent makes comment before or after maintenance has been made
#### Authors
- Omole Emmanuel
#### Reviewers
- Victor Maduforo
#### License

- MIT