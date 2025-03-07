# 🛡️ Advanced Network Packet Analyzer

A powerful GUI-based network packet sniffer that provides:
✅ **Real-time Packet Monitoring**  
✅ **Protocol Filtering (TCP, UDP, ICMP)**  
✅ **Intrusion Detection for DDoS Attacks**  
✅ **User-friendly Interface Selection**  

## 🧿 Features
🔹 **Live Packet Capture & Display**  
🔹 **Suspicious Activity Alerts**  
🔹 **Filter Packets by Protocol**  
🔹 **Interactive GUI Built with Tkinter**  

## 🛠️ Technologies Used
 **Python** |  **Scapy** |  **Tkinter**

## 💻 Installation & Setup
1️⃣ **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/packet-sniffer.git
   cd packet-sniffer
   ```
2️⃣ **Install Dependencies**  
   ```bash
   pip install scapy
   ```
3️⃣ **Run the Packet Sniffer**  
   - **Find Available Interfaces**:  
     ```bash
     python get_interfaces.py
     ```
   - **Start the CLI Sniffer**:  
     ```bash
     python packetsniffer.py
     ```
   - **Launch the GUI Sniffer**:  
     ```bash
     python guipacketsniffer.py
     ```

## 📂 Project Structure
📜 `packetsniffer.py` - CLI-based packet sniffer.  
🖥️ `guipacketsniffer.py` - GUI version with alerts.  
🌐 `get_interfaces.py` - Lists available network interfaces.  

## 📸 Screenshots
**CLI Version:**  
![CLI Packet Sniffer](Screenshot-2025-02-20-222937.png)  

**GUI Version:**  
![GUI Packet Sniffer](Screenshot-2025-02-20-232828.png)  

## 📜 License
Open-source under the **MIT License**.

## 👤 Author
Developed by **Fayiz M P** 🚀

