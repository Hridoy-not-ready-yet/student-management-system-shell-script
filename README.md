# student-management-system-shell-script
n this project we have three acting users:

    Admin
    Teachers
    Students

Admin Admin has the conrol over the whole program. To loginto the admin the password id admin123. Admin can:

    Create Teachers
    Create Students
    Delete Students
    Create Semester
    Create Course
    Assign Teacher into the Course
    Enroll Students into the Course
    Modify assign Teacher
    View all action and data

Teacher Teacher is a restricted actor then the admin. A teacher only can update marks and view those students which specific course the teacher is assigned by the admin.

Student Student is fully restricted actor. A studnets only can view his marks.
Documentation

To run the Shell Script program flow the below steps
Clone and Run

If you want to run the script then first things first you need clone the project. For cloning just:

    Open Terminal (Alt + Ctrl + T)
    Run the .sh file

Run Locally

Install banner package

  sudo apt install sysvbanner

Clone the project

  git clone https://github.com/rudradcruze/student-management-system-shell-script.git

Go to the project directory

  cd student-management-system-shell-script

Run the script

  bash studentManagementSystem.sh

If you successfully run those command then you definitely successful to run the program.

NOTE: Admin default password was admin123
Features

    Automatic student mark calculation
    Multiple User
    User Authentaction
    Track Student, Teacher
    Report Generate
    Handel Multiple Course Load
    Handel Complex Database
