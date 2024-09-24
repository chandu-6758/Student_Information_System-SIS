# Student Information System(SIS) Database


(This is the HEXAWARE Assignment upto Task-4 (SQL))

The SIS database manages information about students, courses, enrollments, payments, and teachers.

## Tables

### Students
- Attributes: 'student_id', 'first_name', 'last_name', 'date_of_birth', 'email', 'phone_number'

### Courses
- Attributes: 'course_id', 'course_name', 'credits', 'teacher_id'

### Teacher
- Attributes: 'teacher_id', 'first_name', 'last_name', 'email'

### Enrollments
- Attributes: 'enrollment_id', 'student_id', 'course_id', 'enrollment_date'

### Payments
- Attributes: 'payment_id', 'student_id', 'amount', 'payment_date'
