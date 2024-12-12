# Database-Project

## University Student Management System Database Design
## Overview
The University Student Management System is designed to efficiently manage and track all aspects of student data, including grades, personal information, course registrations, and facility usage. This project will cater to the evolving needs of a university that might expand its campuses in the future, ensuring seamless data sharing and access across locations.

## Members
- Krittant Phakpho - 6481189
- Krit Jarupantikul - 6480604

## Objective
Our goal is to create a robust database that can manage detailed records of students, course details, and facility usage while ensuring data consistency and ease of access.

## Scope
The database will include:
- **Student Records:** Student ID, personal info, academic records, course registrations, grades, and enrollment history.
- **Course Details:** Course ID, instructor information, credits, schedule, and student enrollments.
- **Facility Details:** Facility ID, name, usage data including date/time and user details.

## Implementation Steps
1. **Identify Entities:** Determine all entities such as students, courses, and facilities along with their relationships.
2. **Create Schema:** Develop a comprehensive database schema that is intuitive and ensures data integrity.
3. **Database Implementation:** Build the database according to the planned schema and populate it with sample data.
4. **Access and Queries:** Develop methods for easy data access and querying.
5. **Data Retrieval Tools:** Implement tools for effective data extraction and reporting.


## ER Diagram
![DB-ER](https://github.com/user-attachments/assets/5fed86f0-0c52-46ed-ad4b-600d24a60f1e)


## Sitemap
![Sitemap](https://github.com/LKJTC/Database-Project/blob/main/Sitemap.png)

## UI Prototype
- https://www.figma.com/proto/xS1I1QnyiKmYwVEhCBSckm/School-Management-System-(Community)?node-id=4-2&t=KDtaghz6VbouULOE-1

## Presentation
- https://www.canva.com/design/DAGYbjg4zVU/nhxXXFqWFi-BXJtI5yggQg/edit?utm_content=DAGYbjg4zVU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
  
## Report
- Design
➔ The design incorporates key entities such as Students, Courses, Instructors,
Enrollments, and Facilities, ensuring robust management of university
operations.
➔ Logical relationships are established between entities, such as the connection
between students and courses via enrollments, and facilities usage by students.
➔ The inclusion of attributes like student majors, course credits, and facility types
enhances the system’s functionality.
➔ An additional entity, PersonalInfo, allows the storage of extended student details
such as addresses, emergency contacts, and emails.
Performance
➔ The system performs efficiently for small to medium datasets. It can handle
common queries, such as listing students enrolled in specific courses, generating
grade reports, and booking facility usage.
➔ However, as the number of students, courses, and facilities grows significantly,
query times may increase, particularly for complex reports like Facility Usage
Analysis or Course Enrollment Trends.
- Security
➔ The system implements basic security measures, such as the potential for user
authentication and access restrictions.
➔ Sensitive data fields, such as emergency contacts and grades, should have stricter
access controls in future iterations.
- Strengths
1. Comprehensive Entity Relationships: The ER diagram captures all major
university processes, including course management, enrollment tracking, and
facility usage.
2. Extensibility: The modular design enables easy expansion, such as adding
financial tracking or research projects.
3. Data Depth: Attributes like instructor departments and facility types add realism
and enable diverse query possibilities.
4. Functional Sitemap: The sitemap provides a clear and intuitive navigation
structure for the system, facilitating ease of use for administrators and students.
- Weaknesses
1. Normalization Issues: While the design avoids excessive redundancy, minor
normalization issues remain. For example, contactInfo and address could be
unified for better consistency.
2. Lack of Financial Data: Salaries for instructors, facility maintenance costs, and
student fees are not included but are critical for real-world applications.
3. Scalability Concerns: Performance might degrade with large-scale datasets
without indexing or optimization techniques.
- Future Improvements
1. Financial Data Integration:
○ Track student fees, instructor salaries, and facility maintenance costs.
○ Enable financial reporting and budget management.
2. Advanced Analytics:
○ Include performance metrics such as student GPA trends and course
popularity analysis.
○ Add heatmaps for facility usage and student engagement.
3. Historical Data Support:
○ Enable analysis of long-term trends by storing historical enrollment and
usage data.
4. Automated Updates:
○ Use AI tools for real-time data updates, such as syncing course schedules
or facility bookings.
5. Enhanced Security:
○ Implement role-based access control, encryption for sensitive data, and
multi-factor authentication.
6. Improved UI Navigation:
○ Enhance the sitemap with better categorization and user-friendly features
for different roles (e.g., students, administrators).
## Conclusion
The current design of the University Management System is well-suited for managing
major operations such as course enrollments, facility usage, and instructor
assignments. While it performs effectively for small datasets and basic queries, future
improvements focusing on scalability, financial integration, and advanced analytics will
ensure its robustness and relevance for larger institutions.
