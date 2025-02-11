# AI-Powered Database Query Chatbot  

## Table of Contents  
- Project Overview  
- Key Features  
- Tools & Technologies  
- Folder Structure  
- Installation Guide  
- Usage Instructions  
- Contribution Guidelines  
- Conclusion  

## Project Overview  
The AI-Powered Database Query Chatbot revolutionizes user interaction with relational databases by enabling natural language queries. Leveraging OpenAI's advanced models and integrating with a PostgreSQL database, the chatbot simplifies data retrieval for users with or without SQL expertise. Its intuitive Streamlit-based interface ensures a seamless experience, allowing business analysts, developers, and other professionals to extract insights efficiently.  

## Key Features  
### **1. Interactive User Interface**  
- Built with Streamlit for an intuitive and visually appealing experience.  
- Customizable themes for user preference.  

### **2. AI-Powered Responses**  
- Utilizes OpenAI’s language models to generate human-like responses.  
- Provides accurate, context-aware answers to complex database queries.  

### **3. Seamless Database Integration**  
- Connects with a PostgreSQL database for real-time data retrieval.  
- Supports complex queries and dynamic data updates.  

### **4. Conversation History**  
- Stores interactions in markdown format for easy reference.  
- Enables users to review past queries and responses.  

## Tools & Technologies  
| Tool       | Purpose | Description |  
|------------|---------|-------------|  
| **Streamlit**  | Web UI | Enables rapid development of a responsive, user-friendly interface. |  
| **OpenAI API** | AI Processing | Powers the chatbot’s intelligent, contextual responses. |  
| **PostgreSQL** | Database | Stores and manages relational data efficiently. |  

## Folder Structure  
```
│   .env  
│   .gitignore  
│   app.py  
│   README.md  
│   requirements.txt  
│  
├───assets  
│   │   dark_theme.py  
│   │   light_theme.py  
│   │   made_by_sdw.py  
│  
├───chatlogs  
│  
└───utils  
    │   api_functions.py  
    │   chat_functions.py  
    │   config.py  
    │   database_functions.py  
    │   function_calling_spec.py  
    │   helper_functions.py  
    │   system_prompts.py  
```  

## Installation Guide  
Follow these steps to set up and run the chatbot:  

### **1. Clone the Repository**  
```bash  
git clone https://github.com/your-username/AI-Powered-Database-Query-Chatbot.git  
cd AI-Powered-Database-Query-Chatbot  
```  

### **2. Install Dependencies**  
```bash  
pip install -r requirements.txt  
```  

### **3. Configure Environment Variables**  
- Add PostgreSQL credentials and OpenAI API key in the `.env` file.  

## Usage Instructions  
### **1. Start the Application**  
```bash  
streamlit run app.py  
```  
### **2. Interact with the Chatbot**  
- Enter natural language queries related to the database.  
- Receive AI-generated, well-structured responses.  
- Save conversations as markdown files for future reference.  

## Contribution Guidelines  
We welcome contributions to enhance the chatbot’s functionality!  

### **How to Contribute**  
1. **Fork the Repository** – Create a copy of the project on your GitHub account.  
2. **Create a New Branch** – Develop features or bug fixes in a separate branch.  
3. **Submit a Pull Request** – Provide a clear description of your contributions.  

## Conclusion  
The AI-Powered Database Query Chatbot simplifies database querying by bridging the gap between natural language processing and structured data retrieval. It democratizes data access, making insights available to all users—regardless of technical expertise. By integrating AI-driven responses with a seamless interface, this project sets a benchmark for intuitive data interaction and AI-enhanced database management.
