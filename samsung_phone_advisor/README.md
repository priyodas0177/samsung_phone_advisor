
##  Project Overview

Samsung Phone Advisor is an intelligent assistant that helps users:

- Get Samsung phone specifications
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

###  Clone Repository
- git clone https://github.com/priyodas0177/Genuine_Technology_Research_Ltd.git 
- cd Genuine_Technology_Research_Ltd
- cd Trading_Adventure

###  Install Dependencies
pip install -r requirements.txt

## How to Run
uvicorn main:app --reload
http://127.0.0.1:8000
  
# This is 30 phone download and store in database
![image alt](https://github.com/priyodas0177/Genuine-Technology-Research-Ltd./blob/main/samsung_phone_advisor/screenshot/db.png?raw=true)
# This is first page if i asked him "compare Samsung Galaxy Z Flip7 and Samsung Galaxy Z Flip7FE" ->
![image alt](https://github.com/priyodas0177/Genuine-Technology-Research-Ltd./blob/main/samsung_phone_advisor/screenshot/1st.png)
# then show the output here.
![image alt](https://github.com/priyodas0177/Genuine-Technology-Research-Ltd./blob/main/samsung_phone_advisor/screenshot/Screenshot%202026-02-24%20015401.png)
# again if i asked him "compare Samsung Galaxy F17 and Samsung Galaxy M17"
![image alt](https://github.com/priyodas0177/Genuine-Technology-Research-Ltd./blob/main/samsung_phone_advisor/screenshot/2nd.png?raw=true)
# then the output here.
![image alt](https://github.com/priyodas0177/Genuine-Technology-Research-Ltd./blob/main/samsung_phone_advisor/screenshot/Screenshot%202026-02-24%20015434.png?raw=true)
# If any data is not store in db then show this message.
![image alt](https://github.com/priyodas0177/Genuine-Technology-Research-Ltd./blob/main/samsung_phone_advisor/screenshot/Screenshot%202026-02-24%20015508.png)
![image alt]()
