# 🚀 GigShield AI  
### Protecting the People Who Keep India Moving

---

## 💭 Why This Matters

Every day, millions of delivery partners step out to keep our lives running smoothly — delivering food, groceries, and essentials right to our doorstep.  

But what happens when things go wrong?

- A sudden downpour floods the streets  
- A heatwave makes it unsafe to work  
- Pollution levels spike  
- Orders suddenly drop due to app outages  

For most gig workers, this means one thing: **lost income**.  
There is no safety net. No backup plan. Just uncertainty.

---

## 🎯 Our Idea

We built **GigShield AI** to change that.

GigShield is an **AI-powered parametric insurance platform** that protects delivery partners from income loss caused by external disruptions.

Instead of making workers go through long claim processes, our system:

- Detects disruptions automatically  
- Calculates income loss using AI  
- Triggers payouts instantly  

**No paperwork. No waiting. Just support when it’s needed most.**

---

## 👤 Who We’re Building For

We focus on food delivery partners working with platforms like **Zomato** and **Swiggy**.

### 📌 Real-Life Example

Ravi, a delivery partner in Chennai, usually earns around **₹700/day**.  

But on days with heavy rain or extreme heat:
- He works fewer hours  
- Orders drop  
- His income falls to **₹400**  

That missing **₹300** makes a big difference.

👉 **GigShield detects this and compensates him automatically.**

---

## ⚙️ How It Works (Simple Flow)

### 1️⃣ Sign Up & Risk Profiling
We calculate a **Gig Risk Score** based on:
- Weather conditions  
- Location  
- Working patterns  

### 2️⃣ Weekly Insurance Plan
Workers get a simple weekly premium plan that fits their earning cycle.

### 3️⃣ Real-Time Monitoring
Our system continuously tracks:
- Weather conditions  
- Air quality  
- Traffic (mock data)  
- Platform activity  

### 4️⃣ Disruption Detection
When conditions cross certain thresholds (e.g., heavy rain, high AQI), the system identifies a disruption.

### 5️⃣ Income Prediction & Loss Calculation
We use AI to estimate:  
> *“How much the worker should have earned today”*  

Then compare it with actual earnings.

### 6️⃣ Automatic Claim & Payout
If a loss is detected:
- Claim is triggered automatically  
- Fraud checks are performed  
- Payout is credited instantly  

---

## 🧠 What Powers GigShield

We use a combination of AI models, each solving a specific problem:

### 🔹 Risk & Pricing
- **Random Forest** → risk score & weekly premium  

### 🔹 Disruption Prediction
- **Logistic Regression** → probability of disruptions  

### 🔹 Income Forecasting
- **Prophet (Time-Series Model)** →  
  - Predict expected earnings  
  - Capture daily & weekly patterns  

### 🔹 Loss Calculation
- **Linear Regression** → estimate income differences  

### 🔹 Fraud Detection
- **Isolation Forest** →  
  - Detect unusual claim behavior  
  - Identify suspicious activity  

---

## 🛠️ Tech Stack

We chose technologies that are practical, fast to build, and scalable.

### 📱 Frontend
- Flutter (mobile experience)

### ⚙️ Backend
- Node.js (APIs & business logic)

### 🤖 ML Services
- FastAPI (serving ML models)  
- Scikit-learn + Prophet  

### 🗄️ Database
- PostgreSQL (structured financial data)

### ⚡ Cache
- Redis (real-time processing)

### ☁️ Cloud
- AWS / GCP (deployment & scalability)

### 🔗 External APIs
- Weather data (OpenWeather)  
- AQI data  
- Mock delivery platform APIs  

---

## ⚡ Why This Is Feasible

We designed GigShield to be **realistic and buildable**, not just theoretical.

- Uses lightweight ML models (no heavy compute required)  
- Relies on easily available APIs  
- Modular architecture allows parallel development  
- Can be prototyped quickly within a hackathon  

👉 This means we can **build, test, and demo a working system efficiently.**

---

## 🌟 What Makes Us Different

We didn’t just build an insurance system — we built something smarter.

### 🔹 Predictive, Not Just Reactive
We don’t just compensate losses — we help workers **anticipate disruptions**.

### 🔹 Safe Working Window Suggestions
We recommend the **best times to work** to avoid income loss.

### 🔹 Disruption Heatmaps
Workers can identify **high-risk areas** and plan accordingly.

### 🔹 Platform Outage Detection
Even if delivery apps fail, workers are still protected.

### 🔹 Smart Wallet
Payouts are stored and can be reused for **future premiums**.
