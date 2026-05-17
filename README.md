# College Registration System

## Team
- Person 1 (Srijapyati) → Database
- Person 2 → Backend
- Person 3 → Frontend
- Person 4 → QA + Integration

## Database
- Tool: MongoDB
- Connection: mongodb://localhost:27017/college_registration

## Collections
- students → 3 records, indexed by email
- courses → 5 records, indexed by title & department
- enrollments → 3 records, indexed by student_id & course_id

## How to setup Database
1. Install MongoDB
2. Open MongoDB Compass
3. Connect to mongodb://localhost:27017
4. Import students.json, courses.json, enrollments.json

## Files
- students.json → sample student data
- courses.json → sample course data
- enrollments.json → sample enrollment data
