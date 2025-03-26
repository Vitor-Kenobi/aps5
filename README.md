# aps5
Supervised Practical Activities Project (APS) for the Computer Science program, submitted as part of the semester grade for the 5th semester in 2024.

<h2>🌱 EcoChat: Real-Time Communication for Environmental Monitoring</h2> 
EcoChat is a real-time communication application designed to facilitate instant messaging and file sharing between environmental inspectors monitoring industrial pollution along the Rio Tietê in São Paulo, Brazil. Developed using C# and .NET MAUI, this project leverages socket programming to enable seamless data exchange, supporting text messages, images, and documents. 

- Real-time text messaging
- Support for emoticons and special characters
- File transfer capability
- Graphical components for a user-friendly interface
- Implementation using Berkeley Sockets

<h2>📊 Project Overview</h2> 
The application addresses the need for efficient communication among inspectors from the State Environmental Secretariat, allowing them to report findings, share evidence, and coordinate actions in real time. Key features include: - **Real-time text messaging** with timestamps and user identification. - **Image and document sharing** for evidence collection. - **Multiplatform support** via .NET MAUI (Windows, macOS, iOS, Android). - **Socket-based architecture** for reliable TCP/IP communication. 
<h2>🗂️ Project Structure</h2>  
The repository is organized as follows:  

- client/: .NET MAUI client application (UI, WebSocket client logic).  
- server/: WebSocket server implementation (C# backend).
- ChatApp/: Project main folder.
- paper/: Contains documentation and reports related to the project.
 
<h2>🚀 Getting Started</h2> 
To run EcoChat locally: 
<h3>Prerequisites:</h3>
 - .NET 6 SDK - IDE (Visual Studio 2022 recommended) 
<h3>Clone and run:</h3>
```bash git clone https://github.com/Vitor-Kenobi/aps5.git cd aps5 ``` 1. **Server**: Navigate to `src/api/` and run: ```bash dotnet run ``` 2. **Client**: Open the `Client` folder in Visual Studio and deploy to your target platform. 
<h2>🤝 Contributors</h2>
I thank my teammates Leonardo and Kaiky for their exceptional collaboration in the research and structuring of this project, and my dear Nicolas and Diego for their brilliant support throughout the application's development process.

Special thanks to our advisor, Prof. Ms. Rafael Gross, for his guidance.

For detailed technical documentation, refer to the attached PDF (/paper) or explore the repository. 🚀

<h2>📜 License</h2> 
This project is part of an academic assignment and is not licensed for commercial use.