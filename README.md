# Contract Monthly Claim System

### Description
The **Contract Monthly Claim System (CMCS)** is a .NET-based web application designed to streamline the process of submitting, verifying, and approving claims by lecturers. This system supports multiple roles, including **Lecturers**, **Programme Coordinators**, and **Academic Managers**. The UI is implemented using **WPF (.NET Core)** as a front-end prototype and follows the Model View Controller (MVC) design pattern.

### Features
- **Lecturer View**:
  - Submit claims for hours worked with details such as hourly rate and additional notes.
  - Upload supporting documents for claims.
  - User-friendly form with a single button to submit claims.
  
- **Coordinator View**:
  - View pending claims and decide whether to approve or reject them.
  - Easy-to-use interface with buttons for quick claim verification.
  
- **Manager View**:
  - Similar to the Coordinator View but intended for academic managers to verify claims.
  
- **Claim Status Tracking**:
  - Track the status of submitted claims (Pending, Approved, Rejected).
  - Real-time updates of the claim's progress from submission to approval/rejection.

### Project Structure

This project consists of the following parts:
1. **User Interface (WPF Prototype)**: A visually appealing front-end design using .NET Core and WPF. The current version is a non-functional prototype focused on front-end design with no back-end functionality.
2. **UML Class Diagram**: A class diagram representing the data structures of the CMCS system, showing relationships between entities such as `Claim`, `Lecturer`, and `Coordinator`.
3. **Project Plan**: Detailed project plan outlining tasks, timelines, and deadlines for building the full prototype.

### Installation & Setup
1. Clone the repository:
   
   git clone https://github.com/snazohappymgidi/Contract-Monthly-Claim-System.git
 
2. Open the solution in **Visual Studio** or any other compatible IDE.
3. Make sure **.NET Core** is installed on your system.
4. Build and run the project to explore the front-end prototype.

### Technologies Used
- **C#**
- **WPF (.NET Core)**
- **Model View Controller (MVC)**
- **Git Version Control**

### Design Choices
The design of the CMCS system was made to ensure simplicity and ease of use:
- **Color Scheme**: Each user role is given a unique background color to distinguish different views:
  - Lecturers: Light Green
  - Coordinators: Light Pink
  - Managers: Light Orange
  - Claim Status: Light Blue
- **Font and Layout**: We chose "Segoe UI" as the font for a modern and readable user interface. The layout is kept clean with proper padding and spacing to avoid clutter.

### Future Improvements
- Add backend functionality to make the system fully operational.
- Implement role-based authentication using ASP.NET Identity.
- Enhance error handling and validation to improve user experience.

### GitHub Repository
You can view the project repository on GitHub:  
[Contract Monthly Claim System](https://github.com/snazohappymgidi/Contract-Monthly-Claim-System.git)
