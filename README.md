
##  Project Overview

Samsung Phone Advisor is an intelligent assistant that helps users:

- Get Samsung phone specifications in online and save it into database.
- Compare multiple phones
- Receive recommendations based on user needs
 
##  Features

-  Phone specification search
-  Phone comparison
-  AI-based recommendation
-  PostgreSQL structured database
-  FastAPI REST API
-  Natural language responses
---

##  System Architecture

User Query → FastAPI → Agents → Database → Response

## 🛠 Technologies Used

- Python
- FastAPI
- PostgreSQL
- SQLAlchemy
- Pandas
- Web Scraping (GSMArena)
- RAG Architecture


###  Install Dependencies
pip install -r requirements.txt

## How to Run
uvicorn main:app --reload
