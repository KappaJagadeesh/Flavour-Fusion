
## 🔹 How to Set Up the API Key

To run this project, you need a valid Google Generative AI API Key.

### Step 1: Get Your API Key
1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Navigate to **APIs & Services > Credentials**.
3. Create an API key and copy it.

### Step 2: Store Your API Key
1. **Create a `.env` file** in the project directory.
2. Copy the content from `.env.template` and paste it into `.env`:

3. Replace `your_api_key_here` with your actual API key.

### Step 3: Run the Application
Now, you can start the project:



## # 🍽️ Flavour Fusion: AI-Driven Recipe Blogging  

## 📌 Introduction  
This is a **Streamlit-based web application** that generates **AI-driven recipe blogs** using **Google's Generative AI (Gemini 1.5 Flash)**. Users can enter a **recipe topic**, specify the **word count**, and get a **detailed recipe**. Additionally, a **random programmer joke** is displayed for fun while content is being generated.  

---

## 🚀 Features  
- **AI-generated recipe blogs** based on user input  
- **Customizable word count** (500–2000 words)  
- **Random programmer joke** for entertainment  
- **Simple web UI using Streamlit**  

---

## 🛠️ Setup Instructions  

### **1️⃣ Install Dependencies**  
Ensure you have **Python 3.8+** installed, then install the required libraries:  
```sh
pip install -r requirements.txt

```
step 2 :Set Up API Key
Create a file named api_key.env in the project directory.
Add the following line inside api_key.env:

GOOGLE_API_KEY=your_api_key_here
Do not upload api_key.env to GitHub (it is ignored via .gitignore).
Running the Application
Run the following command:


streamlit run app.py
The application will open in your browser.

How It Works
Enter a recipe topic (e.g., "Vegan Chocolate Cake").
Select the word count (500–2000 words).
Click "Generate Recipe" to get an AI-generated blog.
A programmer joke is displayed during generation.
Fun Feature: Programmer Jokes
Each time a recipe is generated, a random programmer joke is displayed.

Example:

Why do programmers prefer dark mode? Because light attracts bugs!


