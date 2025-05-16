
# 📸 ResqCam - Smart Surveillance Emergency System

**ResqCam** is an AI-powered smart surveillance and emergency alert system built using Python and Streamlit. It enables users to quickly send emergency alerts via SMS using Twilio, capture webcam footage, share real-time GPS location, and notify saved emergency contacts with a simple button click.

---

## 🚀 Features

- 🔒 **User Authentication** (Signup/Login with phone number)
- 📞 **Emergency Button** to send alerts via SMS (Twilio)
- 📍 **Real-Time GPS Location** capture and sharing
- 🎥 **Webcam Integration** for capturing evidence
- 🗺️ **Map View** of nearby police stations
- 📱 **Emergency Contacts** save and manage
- 🌐 **Ngrok Integration** for public URL access
- 🧠 Voice/Keyword Trigger (planned)
- ☁️ Cloud Backup and Auto Image Capture (optional/future)

---

## 📂 Project Structure

```bash
ResqCam/
│
├── Resqcam(final).ipynb     # Main Jupyter Notebook app (Streamlit code)
├── README.md                # Project overview and documentation
├── requirements.txt         # List of required Python libraries
└── assets/                  # Optional directory for storing static files
```

---

## ⚙️ Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/ResqCam.git
cd ResqCam
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Add your Twilio credentials:**

In the notebook/code, replace these with your credentials:

```python
account_sid = "YOUR_TWILIO_SID"
auth_token = "YOUR_TWILIO_AUTH_TOKEN"
twilio_number = "YOUR_TWILIO_PHONE_NUMBER"
```

4. **Run the app:**

```bash
streamlit run Resqcam(final).ipynb
```

5. **Expose local app with Ngrok:**

```bash
ngrok http 8501
```

Copy the Ngrok URL to share your app publicly.

---

## ✅ Requirements

- Python 3.7+
- Streamlit
- Twilio
- Geopy
- OpenCV
- PyNgrok
- Pandas
- Geocoder
- Folium
