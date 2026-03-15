# DATABASE SYSTEMS PROJECT

## Peer Tutoring Platform

| System | Peer Tutoring Platform |
|--------|----------------------|
| **Group number and members** | **Group 5:**<br>1. 08331 Thomas Asamba<br>2. 224474 Abigail Githeci<br>3. 151426 Keittah Oyunga<br>4. 226076 Mumbya Lubamba Gloria<br>5. 166227 Jack Spencer Odisa |

---

## PART A: PROJECT OVERVIEW

### PART A-1: Project Idea Definition

#### Project Topic

The proposed system is a **Peer Tutoring Platform**, a web-based, database-driven application that connects students who need academic help with qualified peer tutors within their institution.

#### Problem Statement

Most students experience difficulties in their studies but often lack access to timely academic assistance. At the same time, other students possess strong knowledge in certain subjects and can provide peer support. However, the absence of a structured platform to connect tutors and learners results in inefficiencies such as:

- Difficulty in identifying qualified tutors  
- Scheduling conflicts  
- Lack of accountability  

This Peer Tutoring Platform aims to address these challenges by providing a centralized system where students can:

- Register as tutors or learners  
- List subjects they can teach  
- Request tutoring sessions  
- Schedule meetings  
- Provide feedback after sessions  

The system will store and manage information related to users, tutoring subjects, session bookings, schedules, and feedback. By organizing this information within a well-structured relational database, the system will:

- Improve access to academic support  
- Streamline tutoring coordination  
- Enhance the overall learning experience  

The platform is not merely a practical exercise; it is a tool for advancing educational equity. By structuring peer learning through a robust database system, this project supports **SDG 4**’s vision: quality education should be **accessible, inclusive, data-informed, and oriented toward developing well-rounded, capable individuals**.

---

### PART A-2: Scope and Objectives

#### Scope

The Peer Tutoring Platform focuses on managing the core data required to support peer-to-peer tutoring interactions within an academic environment. Functional areas include:

1. Student registration and profile management  
2. Tutor availability and subject listings  
3. Booking and scheduling tutoring sessions  
4. Managing tutoring session records  
5. Recording feedback and ratings after tutoring sessions  
6. Maintaining subject and tutor information  

**NB:** The system **will NOT** handle financial payments, video conferencing infrastructure, or integration with external learning management systems.

#### Objectives

The objectives of this Peer Tutoring Platform include:

1. Design a relational database that efficiently stores and manages information about students, tutors, subjects, and tutoring sessions  
2. Facilitate matching of students seeking academic assistance with suitable peer tutors based on subject expertise  
3. Support scheduling and management of tutoring sessions between students  
4. Demonstrate proper database design techniques including entity identification, normalization, and relational schema development  

---

### PART A-3: Stakeholders

Several stakeholders are involved in the Peer Tutoring Platform system.  

| Stakeholder | Role | System Interaction |
|------------|------|------------------|
| Student (Learners) | Primary users seeking tutoring help | Registers, searches tutors, books sessions, provides feedback (submits ratings) |
| Peer Tutor | Student offering tutoring services | Registers as tutor, lists subjects they can teach, sets availability, confirms/completes sessions |
| Administrator | Oversees platform | Manages users, monitors sessions, maintains subject lists, ensures database integrity and security, generates reports |
| Institution / Department | Indirect stakeholder | Reviews aggregate performance data and session reports |
