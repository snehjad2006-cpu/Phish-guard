# Phish-guard
PhishGuard is an interactive phishing awareness web application that teaches users how to recognize cyber threats through real vs fake message comparisons, simulations, and a short quiz. It provides instant feedback, a personalized risk score, and practical security tips to promote safer online behavior.


## 🚀 Key Features

### 1. **Tactical Tech-Stack**
The interface is really dark. Has a grid and scan lines that move. It uses fonts to look like a command line. The boxes have neon borders and blinking lights to show when something is happening.


### 2. **Intelligence Layer (Detection Engine)**
This is the part that figures out if something is a scam. It uses a point system to decide how risky something is.

-High Risk things get 40 points: these are things like web addresses, direct connections to bad servers and words that try to scare you.

-Medium Risk things get 20 points: these are things like redirects and generic greetings.

-Low Risk things get 10 points: these are things like websites and too many subdomains.

-It also has advanced ways to detect scams like finding characters that look like real ones.


### 3. **Operator Progression (Gamification)**
This is the game part. You get points for scanning URLs analyzing emails or taking quizzes.

You can move up in rank:
- 100 Points: you are a Junior Analyst
  
- 500 Points: you are a Senior Forensic Lead
  
- 501+ points: you are an Elite Defender



### 4. **Forensic Reporting**

You can make reports about incidents. Download them. These reports have timestamps, risk scores and information about the threat.

---

## 🛠️ Installation & Usage

### Prerequisites
- Python 3.8+
- Streamlit

### Setup
1.  **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/phish-shield.git
    cd phish-shield
    ```

2.  **Install Dependencies**
    ```bash
    pip install streamlit
    ```

3.  **Launch the Dashboard**
    ```bash
    python -m streamlit run app.py
    ```
    *Or simply:*
    ```bash
    python app.py
    ```

---

## 🕹️ Modules

| Module | Description |
| :--- | :--- |
| **URL X-RAY** | Deep scan of URLs for structure, TLDs, and obfuscation techniques. |
| **EMAIL SCAN** | Heuristic analysis of email text for social engineering patterns (Urgency, Pressure). |
| **THE GAUNTLET** | Interactive Quiz to test cyber-awareness. earn XP and unlock badges. |
| **FORENSIC LAB** | Side-by-side comparison of legitimate vs. malicious artifacts. |
| **NET-TOOLS** | Simulated operator tools (MFA Interception, Packet Sniffing). |

---

> **Operator Note**: Stay vigilant. The grid is watching. 
> *System Status: ENCRYPTED CONNECTION ACTIVE*
