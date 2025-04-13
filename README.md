✅ What I Learned – Docker & Jenkins Setup
🔧 Docker:
Explored Docker installation on Windows.

Learned about WSL (Windows Subsystem for Linux) and how it interacts with Docker Desktop.

Practiced using key Docker-related commands:

wsl --shutdown

wsl --unregister

docker run hello-world

Understood common errors such as:

Docker Desktop service not running

Pipe errors related to dockerDesktopLinuxEngine

Identified alternative ways to verify Docker installation without a running container.

🔧 Jenkins:
Gained experience running Jenkins via the jenkins.war file.

Learned that Jenkins requires Java 11 or higher, while also maintaining Java 8 for compatibility.

Handled Java version conflicts by:

Installing Java 17 separately

Running Jenkins using a specific Java version without changing system defaults

(bash) C:\Path\To\Java17\bin\java.exe -jar jenkins.war

