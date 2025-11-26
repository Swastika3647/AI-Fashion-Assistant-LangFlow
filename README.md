# 👗 AI Fashion Assistant (LangFlow)

An AI-powered fashion assistant built using **LangFlow**, **Google Generative AI**, and **image analysis pipelines**.  
It analyzes a user’s uploaded image, extracts physical features (body shape, face shape, undertone, hair texture), and provides **personalized styling recommendations** like a high-end digital stylist.

---

## 🚀 Features

- 🧠 **LLM-powered fashion analysis**
- 👤 **Image-to-text physical description pipeline**
- 🎨 Trend-aware outfit and styling suggestions
- 🔄 Conversation memory & context-aware responses
- 🔍 Integrated Google Search Tool (optional)
- ⚙️ Fully configurable in LangFlow

---


---

## 🧩 LangFlow Pipeline Overview

Your flow contains:

### **1. Chat Input**
Receives user message + image.

### **2. Google Generative AI Model**
Extracts:
- Body shape  
- Face shape  
- Undertone  
- Hair texture  

### **3. Prompt Template (VogueGPT Mode)**
Final prompt uses:
- Physical description  
- User question  
- Chat history  

### **4. Agent + Tools (Google Search Optional)**  
Allows external lookups on trends.

### **5. Chat Output**  
Shows the final personalized fashion advice.

---

## 🛠 How to Run

### **Option 1: In LangFlow**
1. Open LangFlow  
2. Import `AI FASHION ASST 2.json`  
3. Add your **Google API key**  
4. Upload an image  
5. Ask styling questions like:  
   - *“What outfit suits me for college?”*  
   - *“Suggest winter looks based on my body shape.”*

---

## 🧪 Example Output

> “Honey, with that soft-oval face and warm undertone, avoid harsh neons.  
> Try earthy palettes, structured jackets, and wide-leg trousers — trust me.”

---

## 🔧 Requirements (if running manually)

```txt
langflow
google-generativeai
langchain_google_genai


