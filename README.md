# Attendance System

## Overview

The Attendance System is a web-based application designed to manage and track attendance for organizations, schools, and other entities. The system allows administrators to create events or classes, and participants can mark their attendance either manually or through automated processes. This project aims to provide an efficient and user-friendly way to handle attendance records, ensuring accurate and timely data management.

## Features

- **User Authentication**: Secure login for administrators and participants.
- **Event Management**: Create, update, and delete events or classes.
- **Attendance Marking**: Multiple methods to mark attendance (manual entry, QR code scanning, etc.).
- **Real-time Reporting**: Generate attendance reports and analytics.
- **Notifications**: Send reminders and notifications to participants about upcoming events or attendance status.
- **Role-Based Access Control**: Different access levels for administrators, teachers, and students.

## Technologies Used

- **Programming Language**: Python
- **Libraries and Frameworks**:
  - **NumPy**: For numerical computations
  - **Pandas**: For data manipulation and analysis
  - **Matplotlib**: For creating static, animated, and interactive visualizations
  - **SciPy**: For scientific and technical computing
  - **Jupyter**: For creating and sharing documents that contain live code, equations, visualizations, and narrative text
  - **OpenCV**: For image processing and QR code scanning
  - **Streamlit**: For creating the web application
  - **Pillow**: For image processing

## Installation

### Prerequisites

- Python (>= 3.7)
- Pip (Python package installer)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Mattiechuks/attendance-system.git
   cd attendance-system
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   streamlit run app.py
   ```


## Usage

1. **Sign up / Login:**
   - Users can sign up for a new account or log in using existing credentials.

2. **Create Event:**
   - Administrators can create new events or classes and specify details such as date, time, and location.

3. **Mark Attendance:**
   - Participants can mark their attendance manually or through automated processes (e.g., QR code scanning).

4. **Generate Reports:**
   - Administrators can generate attendance reports for specific events or overall attendance records.

5. **Send Notifications:**
   - Send reminders or notifications to participants about upcoming events or attendance status.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push to the branch.
6. Open a pull request.


## Acknowledgements

- Thanks to the contributors of open-source projects that made this project possible.
