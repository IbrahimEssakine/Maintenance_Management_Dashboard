# PART 1 : DIGITALIZATION PROPOSALS
# I. Use of Augmented Reality (AR) in Maintenance

Augmented Reality (AR) is an innovative technology finding increasing applications in various industrial sectors, including maintenance. In the context of SBGS, the use of AR in maintenance aims to revolutionize how technicians interact with equipment and machinery. This technology combines the real world with virtual elements, creating an interactive and immersive experience.
# Concept and Benefits: 
Enhanced Training, Faster and More Accurate Maintenance, Downtime Reduction, Predictive Maintenance, Improved Documentation
# Operation of the AR Maintenance Application
The AR maintenance application at SBGS follows a multi-step process to facilitate machine detection, procedure selection, real-time information and procedure visualization, and data backup for future analysis.

# Machine Detection:
The AR application activates automatically on the maintenance site, using the smartphone or tablet camera to scan the environment and detect machines through specific visual markers (QR codes) or pre-installed RFID tags.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/a5a03801-7764-406c-a1fb-e9fd04bf9cd9)

# Procedure Selection: 
Once machines are detected, the application allows the technician to select the specific machine and browse a list of available maintenance procedures.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/a6616800-ea7b-4fa8-82e3-17886789acb0)

# Visualization of Information and Procedures: 
After selecting the procedure, the AR application displays relevant information in real-time. This may include detailed 3D schematics of the machine, specific components to inspect, lubrication points, repair instructions, and more.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/5e617b53-f272-4114-a1f2-d31cb80b3c61)

# Data Backup:
Throughout the maintenance process, the AR application automatically records each action taken by the technician. This documentation is saved in a secure database for later analysis and processing. This data includes photos or videos of the machine, technician notes, and maintenance-related information.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/24e01690-f106-41e4-94cf-b1507447bfc4)

## Limitations of Mobile AR Applications for Maintenance

Mobile applications for Augmented Reality (AR) have introduced new possibilities in maintenance but come with limitations impacting technicians' experience and raising data security concerns.

Challenges include the need for technicians to constantly hold smartphones or tablets, which can be uncomfortable and lead to potential device damage. 
Data security and privacy issues arise from using personal smartphones, exposing sensitive company information to cybersecurity threats.

## Expanding into the World of Smart Glasses: A Glimpse into the Future
Considering the limitations of mobile AR applications, the future may involve smart glasses as a promising alternative for maintenance technicians. Smart glasses offer advantages such as a hands-free interface, enhanced data security, and seamless integration into existing maintenance processes.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/c463992e-b358-4456-94cc-6610fff0415f)

Maintenance Technician Using AR Glasses

# II. Task Management with a Mobile Application
Concept and Benefits: Effective Task Distribution, Distribution efficace des tâches, Suivi en temps réel, Communication transparente, Historique des tâches 

Operation of the Mobile Task Management Application

The operation of the mobile task management application at SBGS is designed to be user-friendly and tailored to the needs of different users, whether maintenance managers or field technicians.

# Account Login:
When the user opens the application, they must log in to their account. The type of account (Maintenance or Manager) determines the available features and interfaces.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/812069ea-20b0-49e1-bc8d-e878e2de6ecf)

# Manager Interface:
If the user logs in as a manager, they access an interface that allows them to manage maintenance tasks globally. The available options include:

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/f13dcfef-a02d-4c79-bbdc-176b752895cb)

# Task Assignment: 
The manager can assign tasks to technicians by filling in all necessary fields, such as task description, deadline, line, etc. They can also assign specific tasks to particular technicians.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/99d0c765-3d96-4d54-b95e-a2db02df59c8)

# Task Visualization:
The manager can view all ongoing and upcoming tasks, sorting them by priority,

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/c1725678-ed8d-405b-90fd-58701108c95f)

# Adding Feedback: 
After completing a task, the technician has the capability to provide feedback by including a photo, comments, and the status of the task (Completed or Not Completed).

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/f24cdbad-90d0-4594-b7c2-afcf42d18bf8)

# PART 2 :  PROJET DE RENOUVELLEMENT DU TABLEAU DE BORD EXCEL DE MAINTENANCE
# Introduction:
Maintenance plays a crucial role in the industry, directly contributing to operational continuity, worker safety, and equipment sustainability. This report delves into the "Maintenance Dashboard Excel Renewal Project" at SBGS. The project aims to modernize the central maintenance management tool using VBA (Visual Basic for Applications) in Excel.

The renewed maintenance dashboard comprises three main elements: "Maintainers," "Plans," and "Tasks," each with two distinct interfaces for data input and information visualization. At its core, a main page displays all tasks on a calendar, enabling better planning and an overview of the entire maintenance process. Automated task scheduling based on frequency enhances resource management and reduces unplanned downtimes.

# I. Drawbacks of the Old Dashboard:
Before exploring the renewed maintenance dashboard, understanding the challenges of the old dashboard is crucial:

Manual Data Entry: Manual entry of team members, plans, and tasks was time-consuming and error-prone.
Lack of Connectivity: The old dashboard lacked real-time connectivity, leading to potential discrepancies in data.
Manual Task Scheduling: Tasks were not automatically scheduled, requiring manual assignment and causing delays.
Visual Appeal and User-Friendliness: The outdated aesthetics and less intuitive interfaces impacted the overall user experience.

# II. Dashboard Structure:
The renewed Maintenance Dashboard is organized into three main objects: "Maintainers," "Plans," and "Tasks." Each has specific information fields and user-friendly interfaces for data entry. The interaction between these objects facilitates effective maintenance task planning, assignment, and tracking.

# Class Diagram:
A class diagram illustrates the structure and relationships between key classes in the application. Classes include Maintainer, Plan, and Task, crucial for task management, activity planning, and communication.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/a02f4afe-21ef-4c6d-a70d-89edae6fc545)

# 1. Maintainer Object:
The Maintainer object is a vital component of the Maintenance Dashboard, encompassing essential information about maintenance technicians. The interface allows for the addition of new maintainers, creating a comprehensive list with details on completed tasks and current availability. A summary graph visually depicts each maintainer's task contributions.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/ede76005-123b-4b30-b22c-220e8c93a0cb)

Interface Design Prototype

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/fccd0b9a-87a3-45e7-95b9-fd44b9f2c6c0)

Interface for Adding New Maintainers

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/3c51a4a1-54fa-4038-af3d-ce42031300cf)

Maintainers List Interface!

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/33582078-c65d-4eb7-a1a5-e418986f4146)

Summary Chart

# 2. Plan Object:
The Plan object involves entering information such as plan name, associated label, and production line. A list and graphs visualize the distribution and frequency of maintenance plans, aiding better understanding and management.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/13fdaf97-0f5c-48b4-9d86-8ef1f2abebfc)

Prototype of the Services Interface

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/5be3ad05-51e8-4c1b-9c2f-8e181423a80b)

Interface for Adding New Plans

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/0f41bf4e-8a92-4531-a646-fbdd0d3ec1c4)

List of Plans Interface

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/724ba463-c2cd-47f8-a845-8eb5101b47ff)

Distribution Chart of Plan Types

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/9e7eb968-0487-4aa6-8ea1-7dd31d88fde8)

Frequency Chart of Plans

# 3. Task Object:
Tasks are added by selecting a maintainer, maintenance plan, and scheduled date. The interface distinguishes between scheduled and completed tasks, simplifying tracking and management.


![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/a9f0a3fb-3f21-4936-84b4-f349b0c7a3a5)

Prototype of the Tasks Interface

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/23351eb9-178b-45fa-998d-b9cda1bf2d35)

Interface for Adding New Tasks

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/091a4425-11f5-4cf5-a783-08db5a5bbc8e)

Circular Chart of Task Status

# 4. Main Page (Dashboard):
The main dashboard provides a comprehensive view of maintenance activities, featuring a month and year selector, quick access buttons to manage maintainers, plans, and tasks, and a synchronized calendar for efficient task management.

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/e40ffa96-c88c-4e7f-b6e0-2d0add1f5324)

Dashboard Prototype

![image](https://github.com/IbrahimEssakine/Maintenance_Management_Dashboard/assets/103626975/94448549-516d-43e4-acaa-2c05ce51c1dd)

Implementation of Dashboard in Excel

# General Conclusion:
The digitalization project for maintenance at SBGS signifies a pivotal step towards agile, efficient, and predictive maintenance management. It aligns with the industry's momentum towards inevitable modernization. SBGS, committed to leveraging technological advances, recognizes the imperative necessity of digitalizing maintenance processes for sustained competitiveness in a dynamically evolving industrial environment.
