# Proposed GitHub Issues for New Features

Based on the comparison with Latest-Optimum-School-System, here are the new features to add to our Mergington High School Activities API. Each major feature should be a separate GitHub issue for tracking.

## Issue 1: Add User Roles and Authentication
**Title:** Implement User Roles and Authentication System  
**Body:**  
Add role-based access (e.g., students, admins) with authentication. Currently, our API is anonymous. Integrate with a database for user management.  
- Subtasks:  
  - Add user model (email, name, role).  
  - Implement login/logout endpoints.  
  - Restrict endpoints based on roles.  
- Related: Latest-Optimum has full user management.

## Issue 2: Add Club/Event Creation and Editing
**Title:** Allow Admins to Create and Edit Extracurricular Activities  
**Body:**  
Currently, activities are static. Add endpoints for admins to create/edit/delete activities (title, description, schedule, max participants).  
- Subtasks:  
  - Add POST/PUT/DELETE /activities endpoints.  
  - Add admin role checks.  
  - Persist to database.  
- Related: Latest-Optimum has full club management.

## Issue 3: Implement Attendance Tracking
**Title:** Add Attendance Tracking for Activities  
**Body:**  
Track who signed up and attended events. Add QR codes or manual check-ins.  
- Subtasks:  
  - Add attendance field to registrations.  
  - Add endpoint to mark attendance.  
  - Generate reports.  
- Related: Latest-Optimum has daily attendance.

## Issue 4: Add Financial Management (Payments and Budgets)
**Title:** Integrate Payment System and Budget Tracking  
**Body:**  
Allow entry fees, track budgets/incomes/expenses. Integrate PayPal or similar.  
- Subtasks:  
  - Add payment endpoints.  
  - Track transactions.  
  - Add budget fields to activities.  
- Related: Latest-Optimum has full accounting.

## Issue 5: Add Messaging and Notifications
**Title:** Implement User Messaging and Notifications  
**Body:**  
Add private messaging between users, SMS/email alerts for events.  
- Subtasks:  
  - Add message endpoints.  
  - Integrate SMS service (e.g., Twilio).  
  - Send notifications for signups/updates.  
- Related: Latest-Optimum has messaging and SMS.

## Issue 6: Add Reporting and Analytics
**Title:** Create Dashboards and Reports  
**Body:**  
Add endpoints for stats (e.g., participant counts, attendance rates). Generate PDFs.  
- Subtasks:  
  - Add /reports endpoint.  
  - Integrate charting library.  
  - Export to PDF/CSV.  
- Related: Latest-Optimum has dashboards and reports.

## Issue 7: Add Task Management
**Title:** Allow Task Assignment for Activities  
**Body:**  
Admins can assign tasks (e.g., event prep) and track completion.  
- Subtasks:  
  - Add task model.  
  - Add endpoints for CRUD tasks.  
  - Link to activities.  
- Related: Latest-Optimum has task management.

## Issue 8: Add Media and File Uploads
**Title:** Support Image/Video Uploads for Activities  
**Body:**  
Allow uploading posters, materials. Store in cloud or locally.  
- Subtasks:  
  - Add file upload endpoints.  
  - Integrate storage (e.g., AWS S3).  
  - Display in activity details.  
- Related: Latest-Optimum has media management.

## Issue 9: Add Settings and Customization
**Title:** Implement System Settings  
**Body:**  
Allow admins to configure themes, languages, notifications.  
- Subtasks:  
  - Add settings endpoints.  
  - Store configs in DB.  
  - Apply settings globally.  
- Related: Latest-Optimum has extensive settings.

## Issue 10: Add Library/Transport/Hostel Management
**Title:** Extend to Full School Management Features  
**Body:**  
Add endpoints for books, transport, dorms (if relevant to activities).  
- Subtasks:  
  - Add related models.  
  - Integrate with activities.  
- Related: Latest-Optimum includes these.

Copy these to GitHub Issues in the repository: https://github.com/svisakh/skills-integrate-mcp-with-copilot/issues