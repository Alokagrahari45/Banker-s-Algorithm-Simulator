🏦 Banker's Algorithm Simulator

An interactive and visually rich Banker’s Algorithm Simulator built using HTML, CSS (Tailwind), and JavaScript to demonstrate resource allocation and deadlock avoidance in Operating Systems.

🚀 Features
🔐 User Authentication (Login / Signup using Local Storage)
🌙 Dark Mode Support
📊 Dynamic Allocation, Max, and Need Matrices
⚙️ Custom Number of Processes & Resources
📈 Automatic Need Matrix Calculation
🟢 Safe / Unsafe State Detection
🔄 Step-by-Step Execution Visualization
📉 Resource Utilization Display
🎯 Preloaded Example for Quick Testing
🧠 About Banker's Algorithm

Banker’s Algorithm is a deadlock avoidance algorithm used in Operating Systems.

It ensures that resource allocation happens only if the system remains in a safe state, meaning all processes can complete execution without causing a deadlock.

📂 Project Structure

Bankers-Algorithm-Simulator/
│── 1_os.html (Main file containing UI, logic, and authentication)

The entire project is implemented in a single file for simplicity.

⚙️ How to Run

Method 1: Direct Run

Download or clone the repository
Open 1_os.html in any web browser

Method 2: Live Server (Recommended)
Right click on the file → Open with Live Server

🧩 How It Works
Enter values for:
Allocation Matrix
Maximum Matrix
Available Resources
Click Execute Safety Algorithm
The system will:
Calculate the Need Matrix
Check if the system is safe or unsafe
Display the Safe Sequence (if available)
Show step-by-step execution
🔄 Algorithm Logic

Need = Max - Allocation

Work = Available
Finish[i] = false

Find process i such that:
Need[i] <= Work and Finish[i] == false

If found:
Work = Work + Allocation[i]
Finish[i] = true

Repeat until all processes finish

If all Finish[i] == true → SAFE
Else → UNSAFE

🛠️ Tech Stack
HTML5
CSS3 (Tailwind CSS)
JavaScript (Vanilla JS)
Font Awesome
🎯 Key Highlights
Fully interactive UI
Clean and modern design
Helps in understanding OS concepts visually
Beginner-friendly implementation
📌 Future Improvements
Backend authentication system
Database integration
Export results feature
Advanced animations
Multi-user support
👨‍💻 Author

Alok kumar Agrahari

⭐ Support

If you like this project, consider giving it a star ⭐ on GitHub!
