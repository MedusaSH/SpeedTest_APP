🚀 SPEEDTEST PRO - PROJECT DOCUMENTATION
=======================================

📋 PROJECT OVERVIEW
------------------
SpeedTest Pro is a modern web application for testing network speeds with a sleek, user-friendly interface. The application measures download speed, upload speed, and ping latency in real-time.

🔧 TECHNICAL SPECIFICATIONS
-------------------------
Frontend:
- React.js 18.x
- Modern JavaScript (ES6+)
- CSS3 with modern features
- Custom SVG animations for the speed gauge

Backend:
- Node.js 16.x
- Express.js
- RESTful API architecture

📁 PROJECT STRUCTURE
------------------
/speedtest-pro
  ├── /src
  │   ├── /components
  │   │   └── SpeedGauge.js
  │   ├── App.js
  │   ├── App.css
  │   └── index.js
  ├── /server
  │   └── server.js
  └── README.md

🛠️ SETUP INSTRUCTIONS
-------------------
1. Clone Repository:
   git clone https://github.com/yourusername/speedtest-pro.git

2. Install Dependencies:
   # Frontend
   cd speedtest-pro
   npm install

   # Backend
   cd server
   npm install

3. Start Application:
   # Start backend (Terminal 1)
   cd server
   npm start

   # Start frontend (Terminal 2)
   cd ../
   npm start

4. Access application at: http://localhost:3000

🔌 API ENDPOINTS
--------------
1. GET /api/ping
   - Purpose: Test connection latency
   - Response: Timestamp

2. GET /api/download-test
   - Purpose: Perform download speed test
   - Response: Binary data for testing

3. POST /api/upload-test
   - Purpose: Perform upload speed test
   - Request: Binary data
   - Response: Speed results

4. POST /api/connection-type
   - Purpose: Set connection mode (single/multi)
   - Request: { type: "single" | "multi" }
   - Response: { success: boolean }

⚙️ FEATURES
----------
1. Speed Testing
   - Real-time download speed measurement
   - Real-time upload speed measurement
   - Ping latency testing
   - Progress visualization

2. Connection Modes
   - Multi-connection testing
   - Single connection testing
   - Automatic mode switching

3. Network Information
   - ISP detection
   - Server location
   - IP address display
   - Connection type indicator

4. User Interface
   - Interactive speed gauge
   - Real-time progress indicators
   - Dark theme
   - Responsive design

🔐 ENVIRONMENT VARIABLES
----------------------
PORT=3000
SERVER_PORT=3001
API_TIMEOUT=30000

📊 PERFORMANCE METRICS
-------------------
- Download Speed: Up to 1 Gbps
- Upload Speed: Up to 500 Mbps
- Ping Measurement: 1-1000 ms
- Test Duration: ~30 seconds

🐛 TROUBLESHOOTING
----------------
1. Connection Issues:
   - Verify server is running
   - Check port availability
   - Confirm network connectivity

2. Performance Issues:
   - Clear browser cache
   - Check network load
   - Verify server resources

3. Display Issues:
   - Update browser
   - Clear local storage
   - Refresh application

👥 DEVELOPMENT TEAM
-----------------
- Frontend Developer : MedusaSH
- Backend Developer:  MedusaSH
- UI/UX Designer: MedusaSH

📝 LICENSE
---------
MIT License
Copyright (c) 2024 MedusaSH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files.

🔄 VERSION HISTORY
----------------
v1.0.0 - Initial Release
- Basic speed testing functionality
- Multi/Single connection support
- Real-time progress monitoring
- Server information display

📞 SUPPORT
---------
For support inquiries:
- Create an issue on GitHub
- Email: medusa.pro.cc@gmail.com

-------------------
Made with ❤️ by MedusaSH
Last Updated: 03/03/2025 
