# 📊 AI Data Analysis Agent

An AI-powered data analysis agent built with the **Agno Agent framework** and **OpenAI’s GPT-4o** model.  
This tool allows users to analyze CSV and Excel files using **natural language queries**, eliminating the need for SQL knowledge.

It leverages **DuckDB** for fast and efficient data processing and presents insights through a clean, interactive **Streamlit UI**.

---

## 🚀 Key Features

### 📤 File Upload & Data Handling
- Upload **CSV** and **Excel** files
- Automatic schema inference and data type detection
- Supports multiple file formats

### 💬 Natural Language to SQL
- Ask questions in plain English
- Automatically converts queries into SQL
- No SQL expertise required

### 🔍 Advanced Data Analysis
- Perform filtering, sorting, and aggregations
- Generate statistical summaries
- Create dynamic data visualizations

### 🎯 Interactive User Interface
- Built with **Streamlit**
- Real-time query execution
- Clear and structured result presentation

## How to Run

1. **Setup Environment**
   ```bash
   # Clone the repository
   git clone https://github.com/dhvanil16/ai_data_analysis_agent.git
   
   # Install dependencies
   pip install -r requirements.txt
   ```

2. **Configure API Keys**
   - Get OpenAI API key from [OpenAI Platform](https://platform.openai.com)

3. **Run the Application**
   ```bash
   streamlit run ai_data_analyst.py
   ```

