# [Course Registration System](https://github.com/vermont849-gif/course-management-system)

A complete course enrollment system where students can register, log in, and manage their course registrations.

🔗 **Live Repository:** https://github.com/vermont849-gif/course-management-system

---

## Live Demo of Features

| Feature | What It Does |
|---------|---------------|
| 🔐 User Registration | Students create accounts (name, email, password) |
| 🔑 Login System | Secure authentication with session management |
| 📚 View All Courses | Shows available courses from database |
| ➕ Enroll | Students add courses to their schedule |
| 📋 My Courses | Shows only enrolled courses for logged-in user |
| ❌ Drop Course | Remove a course from enrollment |

---

## How It Works

Student registers → saved in 'users' table

Student logs in → session created

Views courses → reads from 'courses' table

Enrolls → saves to 'enrollments' table

Views enrolled → JOIN query shows only their courses

Drops course → deletes from 'enrollments'
