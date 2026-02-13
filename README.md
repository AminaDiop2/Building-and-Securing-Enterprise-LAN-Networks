# Building-and-Securing-Enterprise-LAN-Networks
**Design and Implementation of a Campus Network Lab**

**BeGreat** University is a large higher education institution operating across two campuses located approximately 20 miles apart. The university community consists of students and staff distributed across four academic faculties: Health and Sciences, Business, Engineering and Computing, and Art and Design. Each member of staff is assigned a dedicated workstation, and students are provided access to laboratory PCs within their respective faculties.

The purpose of this coursework is to design, configure, and evaluate a secure, scalable, and efficient enterprise network infrastructure that supports both academic and administrative operations across the two campuses.

---

Project Requirements:

### 1-- Develop a comprehensive network topology incorporating all major infrastructure components necessary to support the following environment:

***Main Campus***:
Building A: Hosts the Administrative departments including Management, Human Resources, and Finance. Administrative staff PCs are distributed across multiple offices and are expected to share networking infrastructure. The implementation of Virtual LANs (VLANs) is required to logically segment departments while utilizing shared switching hardware. The Faculty of Business is also located within this building.
Building B: Accommodates the Faculty of Engineering and Computing as well as the Faculty of Art and Design.
Building C: Contains student laboratories and the central IT department. The IT department hosts the University Web Server and other internal servers critical to university operations.
An external email server is hosted in the cloud and must be accessible from the internal network.

Smaller Campus:
Faculty of Health and Sciences: Staff offices and student laboratories are located on separate floors and must be logically segmented within the network design.

---

### 2-- Configure the core networking devices and selected end devices to ensure full end-to-end connectivity, including secure access to internal servers and the externally hosted email server.
Each department or faculty must operate within its own dedicated IP subnet to ensure proper segmentation and structured network management.
Switches must be configured with appropriate VLAN assignments and security settings to enhance traffic isolation and protect network resources.
RIPv2 must be implemented to provide dynamic routing between internal routers. Static routing must be configured where necessary to enable connectivity to the external email server.
Devices located in Building A must obtain dynamic IP addressing through a router-based DHCP server.

Project Tasks:

***Task 1: Plan, design, and prototype the complete network topology for BeGreat University using Cisco Packet Tracer. This task focuses on architectural planning, logical segmentation, and infrastructure layout.***

#### Check out the design here [Network Architecture](Network_Topology/Network_Architecture.png)

***Task 2: Implement and configure the network within Cisco Packet Tracer using appropriate protocols, addressing schemes, VLAN configurations, and routing mechanisms to meet all specified requirements.***
#### Check out the document that have all layer 2 switches configuration here 
#### Check out the document that have all layer 3 switches configuration here 
#### Check out the document that have the main campus router configuration here 
#### Check out the document that have the second campus router configuration here 
#### Check out the document that have the Cloud router configuration here 


*Task 3: Produce a professional technical report (maximum 1500 words) evaluating your proposed network design. The evaluation must include a critical appraisal of performance, scalability, reliability, and security considerations.


