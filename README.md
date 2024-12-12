# **KhanBot Trading Platform**

KhanBot is a cryptocurrency trading automation platform that combines FastAPI backend services with a Streamlit dashboard interface.

## **Installation and Setup**

### **1. Download & Install**
* Download the latest KhanBot.dmg file
* Double click to mount the DMG
* Drag KhanBot into your Applications folder

### **2. Configure Environment**
Open Terminal and navigate to the KhanBot resources:
```bash
cd /Applications/KhanBot.app/Contents/Resources
chmod +x install.sh
./install.sh
```
This creates required conda environments and installs dependencies.

### **3. Start Services**
1. Open Docker Desktop and ensure it's running
2. Clear any existing services if needed:
```bash
# Optional: Kill existing processes on these ports if you get port-in-use errors
kill -9 $(lsof -ti:8000)
kill -9 $(lsof -ti:8501)
```

### **4. Launch KhanBot**
* Open KhanBot from your Applications folder
* Log in with your credentials
* The dashboard will load automatically

## **Troubleshooting**
* **Ports in use**: Use the kill commands above
* **Docker issues**: Make sure Docker Desktop is running
* **Access denied**: Make sure install.sh was made executable with chmod +x

## **Support**
Submit issues through our GitHub repository or contact support directly.