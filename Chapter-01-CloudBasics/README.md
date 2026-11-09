
# HCIA-Cloud-Service-3.5
Notes from Huawei Cloud Service Certification 


# Chapter 1.1 Private Vs Public Cloud

## 1 - What is the cloud?
Its a group of powerful physical servers hosted in remote datacenters that can be accessed through the Internet globally.
Its an alternative way of powering business applications without the heavy capital investment needed for the physical hardware.
Example : If a company wants to back up their data instead of using on prem tape disks it could  autommtically sync backups  to the cloud. This will mitigate the risk of data being lost  if something happens to the main office like a fire 


## 2 - What is Public Cloud?

A Public Cloud is a cloud computing model where resources (such as servers, storage, and networking) are provided by a third-party cloud provider over the internet.
It follows a multi-tenant architecture, meaning multiple customers share the same underlying infrastructure and resource pool, while their data and environments remain logically isolated. (e.g Oman Data Park/AWS)

### 2a - Pros And Cons

| + Pros |  - Cons |
| :--- | :--- |
| **No Capital Expense:** Pay only for what you use . | **Less Security:** Resources are shared multiple tenants use the same hardware could cause Governance & Compliance Issues  |
| **High Scalability:** calability is immediate and nearly infinite. You can spin up or down thousands of servers in minutes. | **Vendor Lock-in & Less Control**: You cannot control the physical hardware or choose custom, non-standard infrastructure configurations.. |
| **Zero Hardware Maintenance** : The cloud vendor handles all physical security, hardware repairs, cooling, and facility upkeep | **Internet Dependency:** Total reliance on WAN/Internet connectivity. If your internet line goes down, you lose access to your resources.. |

### 2b - Main User/s of public clouds
- SMEs/Startups
- E-commerce and digital storefronts with predictable traffic (during eid sales)
- SAAS providers
- Enteprise DevOps teams that want a testing enviorment without waiting for hardware to be provisiones

## 3 - What is Private Cloud?
A Private Cloud is a cloud computing model where cloud resources are dedicated to a single organization rather than shared between multiple customers (tenants).
It can be hosted on the organization's own premises (on-premises) or managed by a third-party cloud provider (AWS,Oman DataPark, Azure, GCP).


### 3a - Pros And Cons

| + Pros | - Cons |
| :--- | :--- |
| **Greater Security & Privacy:** Infrastructure is dedicated to one organization, providing greater control over data access and security. | **High Capital Expense:** Requires significant upfront investment in servers, networking equipment, storage and infrastructure. |
| **Greater Control:** The organization has full control over its infrastructure, configurations, security policies and hardware choices. | **Hardware Maintenance:** The organization is responsible for hardware repairs, physical security, cooling and maintenance (unless outsourced). |
| **Customization:** Infrastructure can be customized to meet specific business requirements, governance and compliance standards. | **Limited Scalability:** Scaling requires purchasing and installing additional hardware, which takes time and money. |
| **Performance:** Dedicated resources provide more predictable performance without competing with other cloud customers for the same resources. | **Requires IT Expertise:** Needs skilled IT staff to manage, maintain and secure the infrastructure. |
| **Compliance:** Easier to enforce specific data residency, governance and regulatory requirements. | **Higher Operating Costs:** Electricity, cooling, staffing and infrastructure maintenance add ongoing expenses. |

### 3b - Main User/s of public clouds
- Government Instituition
- Banks/Finance Instituions
- Military
- Healthcare Organizations
- Organizations with Strict Compliance Requirement for oman's case it will be oil and gas companies
