# Smart-Campus-Management-System

### Overview
The Smart Campus Management System is an AI-powered full-stack web platform designed to digitize and automate core campus operations. It integrates facial recognition-based attendance, academic support management (make-up & remedial classes), smart food ordering, and intelligent campus resource allocation into one unified ecosystem.
The system enhances operational efficiency, improves transparency, and enables data-driven decision-making for administrators, faculty, and students.

### Problem Statement
Traditional campus systems suffer from:
* Manual attendance tracking
* Poor management of remedial and make-up classes
* Unorganized food ordering systems
* Inefficient allocation of campus resources (labs, classrooms, halls)
* Lack of centralized monitoring
* This platform solves these challenges using automation, AI, and real-time data processing.

### Core Features
1️⃣ AI-Based Facial Recognition Attendance
* Real-time face detection and recognition
*Automated attendance marking
* Secure student authentication
* Attendance analytics dashboard
* Low proxy attendance risk

2️⃣ Make-Up & Remedial Class Management
* Faculty can schedule make-up classes 
* Automated student notifications
* Remedial class assignment based on performance
* Attendance tracking for special sessions
* Academic performance monitoring

3️⃣ Smart Food Ordering System
* Digital campus canteen platform
* Menu management for vendors
* Student order placement
* Order tracking and status updates
* Admin analytics for food demand

4️⃣ Campus Resource Allocation
* Classroom booking system
* Lab and equipment reservation
* Auditorium scheduling
* Conflict-free time slot allocation

### Installation Guide
1️⃣ Clone Repository
git clone https://github.com/yourusername/smart-campus.git
cd smart-campus

2️⃣ Backend Setup
cd backend
python -m venv venv
venv\Scripts\activate   (Windows)
source venv/bin/activate  (Mac/Linux)
pip install -r requirements.txt
Run migrations:
python manage.py makemigrations
python manage.py migrate

3️⃣ Run Backend Server
python manage.py runserver

4️⃣ Frontend Setup
cd frontend
npm install
npm run dev


### Future Enhancements
* AI-based student performance prediction
* Mobile app integration
* RFID + Face hybrid attendance system
* Automated timetable generation
* Cloud deployment with CI/CD
* Blockchain-based academic record security


### Benefits
* Reduces manual administrative workload
* Enhances campus security
* Improves academic performance tracking
* Optimizes resource utilization
* Creates a smart digital campus ecosystem

### Conclusion
The Smart Campus Management System combines AI, automation, and intelligent scheduling to create a centralized, efficient, and scalable campus infrastructure. It transforms traditional campus operations into a secure, data-driven, and student-centric smart ecosystem.
