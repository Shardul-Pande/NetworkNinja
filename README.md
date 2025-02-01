# Network Ninja: Supercharge Your Professional Connections

## 🏆 Welcome to Network Ninja
Network Ninja is a cutting-edge **Streamlit** application that harnesses the power of **Amazon Bedrock** and **LangChain** to revolutionize your networking experience. Say goodbye to awkward introductions and hello to meaningful connections!

---

## 🚀 The Problem
In today's fast-paced business world, making genuine connections can be challenging. Professionals often struggle with:

- ⏳ **Limited time** to research potential contacts before meetings  
- 🧐 **Difficulty finding relevant conversation starters**  
- 📖 **Inability to quickly understand a person's professional background**  
- ❌ **Missed opportunities** due to lack of preparation  

---

## ✅ Our Solution
**Network Ninja** addresses these challenges by providing **instant, AI-powered insights** about professional contacts. Simply enter a name, and our application will:

🔍 **Locate LinkedIn Profiles** – Quickly find the most relevant LinkedIn profile for your contact  
📜 **Generate Summaries** – Create concise, informative overviews of a person's career and accomplishments  
💬 **Provide Ice-Breakers** – Suggest unique and engaging conversation starters based on the person's background  

---

## 🎯 How It Helps
Network Ninja empowers you to:

- ⏳ **Save Time** – Eliminate hours of manual research  
- 💪 **Increase Confidence** – Enter meetings well-prepared and knowledgeable  
- 🤝 **Make Lasting Impressions** – Start conversations with relevant, personalized topics  
- 🌍 **Expand Your Network** – Connect more effectively with professionals in any industry  

---

## 🛠️ How It Works
Network Ninja leverages cutting-edge AI technologies:

- **Amazon Bedrock** – Powers deep data analysis and insight generation  
- **LangChain** – Enables sophisticated natural language processing for summary creation  

---

## 🔧 Getting Started

### **📌 Prerequisites**
Ensure you have the following before proceeding:

- Python **3.8+**  
- AWS account with **Bedrock** access  
- **Proxycurl API** key  
- **SerpAPI** key  

---

### **📥 Setup**

#### **1️⃣ Clone the repository**
```bash
git clone https://github.com/Shardul-Pandenetwork-ninja.git
cd network-ninja
2️⃣ Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3️⃣ Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Create a .env file in the project root
Add the following keys inside .env:

ini
Copy
Edit
PROXYCURL_API_KEY=your_proxycurl_key
SERPAPI_API_KEY=your_serpapi_key
AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key
AWS_DEFAULT_REGION=your_aws_region
5️⃣ Launch the application
bash
Copy
Edit
streamlit run app.py
🎯 Usage
1️⃣ Enter the name of the professional you want to research
2️⃣ Click "Get Summary"
3️⃣ Review the generated profile summary and ice-breakers
4️⃣ Use the insights to prepare for your meeting or connection


