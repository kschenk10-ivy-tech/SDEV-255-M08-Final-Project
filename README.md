# SDEV-255-M08-Final-Project
This task list provides a roadmap for developing a comprehensive course management and student registration system. Adjustments may be needed based on testing feedback and evolving project requirements.

### **Stage 1: Development of Course Management System**

#### **Task 1: Define Data Structures**
- Define the data model for courses, including attributes like course name, description, subject area, and number of credits.
- Define the data model for teachers.

#### **Task 2: Build Backend API**
- Create API endpoints to create, view, edit, and delete courses.
- Implement authentication for teachers to ensure only signed-in teachers can manipulate course data.

#### **Task 3: Frontend Development**
- **Page 1: Course Creation and Index**
  - Design and implement a form for adding new courses.
  - Create an index page listing all courses with options to edit or delete them.
- **Page 2: Individual Course View**
  - Design and implement a page to view details of an individual course.

#### **Task 4: Initial Setup and Testing**
- Set up database and server configurations.
- Perform initial testing of CRUD operations for courses.
- Implement basic navigation and partial design of the site.

#### **Deliverables for Stage 1**
- Functional course addition and management interface.
- Active links and navigable pages between course listings and individual course views.
- Initial design elements established on the website.

### **Stage 2: Student Interaction and Course Scheduling**

#### **Task 1: Student Authentication and Registration**
- Implement a user authentication system with different permissions for students and teachers.
- Allow students to register and manage their profiles.

#### **Task 2: Course Enrollment System**
- Create a system where students can search for courses by name or number.
- Develop features for students to add courses to their schedule.

#### **Task 3: Manage Course Enrollment**
- Allow students to view their current course schedule.
- Implement functionality for students to drop courses from their schedule.

#### **Task 4: Testing and Refinement**
- Thorough testing of student login, registration, course addition, and drop features.
- Ensure proper authorization checks are in place to differentiate student and teacher capabilities.

#### **Deliverables for Stage 2**
- A working login system with session management.
- Differentiated user permissions between students and teachers.
- Functionalities for students to manage their course schedules effectively.

### **Additional Considerations**
- Ensure responsive design for accessibility across different devices.
- Implement security measures, such as SSL encryption and secure password storage.
- Plan for future scalability in both the backend and frontend architectures.

### **Follow-Up Tasks**
- After the completion of both stages, conduct user testing with real users to identify usability issues and bugs.
- Prepare documentation for the system usage and maintenance.
