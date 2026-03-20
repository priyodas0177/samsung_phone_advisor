
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
http://127.0.0.1:8000
  
# This is first page if i asked him "compare Samsung Galaxy Z Flip7 and Samsung Galaxy Z Flip7FE" ->
![image alt](https://github.com/priyodas0177/samsung_phone_advisor/blob/main/samsung_phone_advisor/screenshot/Screenshot%202026-02-24%20015401.png?raw=true)

# again if i asked him "compare Samsung Galaxy F17 and Samsung Galaxy M17"
![image alt](https://github.com/priyodas0177/samsung_phone_advisor/blob/main/samsung_phone_advisor/screenshot/Screenshot%202026-02-24%20015434.png?raw=true)

# If any data is not store in db then show this message.
![image alt](https://github.com/priyodas0177/samsung_phone_advisor/blob/main/samsung_phone_advisor/screenshot/Screenshot%202026-02-24%20015508.png?raw=true)

