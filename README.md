# **Suraksha - Smart Security System**

## **Overview**

Suraksha is a sophisticated security system that combines face recognition, voice authentication, and password verification to create a hybrid security model. It helps safeguard confidential data through multi-level biometric verification, supporting emergency scenarios with fake passwords that alert security teams discreetly via email and SMS.

## **Tech Stack**

- **Programming Language**: Python
- **Libraries**: OpenCV, `face_recognition`, `speech_recognition`, `smtplib`, Fast2SMS API, `tkinter`

## **System Requirements**

- Python 3.x
- Webcam and microphone
- Internet connection for email and SMS alerts

## **Installation Guide**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/suraksha-smart-security-system.git
   cd suraksha-smart-security-system
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Email and SMS Alerts**
   - Update email and Fast2SMS API details in `config.py`.

## **Running the Project**

### **1. Registering a User**
To register a user with face, voice, and password:
```bash
python src/register.py
```

### **2. Login Process**
To verify user identity using face, voice, and password:
```bash
python src/login.py
```

### **3. Starting the Main Application**
To run the main security application:
```bash
python src/main.py
```

### **4. Testing Alerts**
To test the email and SMS alert system:
```bash
python src/alert.py
```

Now your project is ready, and you can run it using the commands above!
