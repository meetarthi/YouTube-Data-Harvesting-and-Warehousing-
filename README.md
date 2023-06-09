# YouTube-Data-Harvesting-and-Warehousing-
[Link to access the app](https://arthimurali-youtube.hf.space/)

YouTube Data Harvesting and Warehousing is a application which allows the users to access and analyze data from multiple YouTube channels. This application allows the user to give a YouTube channel ID as input and retrieves the relevant data.  
Able to collect data for multiple YouTube channels and store them in a database by just clicking a button. By Selecting a channel , we could migrate the data from Mongo Database to SQL, to retrieve the relevant youtube Channel information like video comments , likes.

**Developed using:**
------------
1. **Language** - Python

2. **Libraries** - python-youtube, pandas, mysql-connector, PyMySQL, SQLAlchemy

3. **Database** - MongoDB, MySQL

4. **API key**

5. **Front-End/GUI** - Streamlit


**Workflow**
------------
1. Create a dashboard using streamlit.
2. Obtain API credentials by enabling YouTube Data API in Google Developers console.
3. Using Google Api , extract YouTube Channel, Playlist, Video and Comment data.
4. Push the extracted YouTube data into MongoDB.
5. Migrate the data in MongoDB to SQL.
6. Retrieve the youtube information using SQL query.


**User-Interface and Output Display**
------------
1. **Intro Page - About the app and getting Channel ID**
------------
![Screenshot from 2023-06-10 03-28-26](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/1132fe20-ee4d-4e09-9eed-b3e20d3caed1)
![Screenshot from 2023-06-10 03-29-28](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/533616ea-bdcf-4409-93d3-345f76fddf24)
![Screenshot from 2023-06-10 03-30-37](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/af9952d2-3417-45a3-90d8-81d8ae7e1f0b)


2. **Enter Channel Id and Pushing the youtube data into MongoDB**
------------
![Screenshot from 2023-06-10 03-44-23](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/ef3a4d9b-36e3-46d3-923e-8c603951c33a)
![Screenshot from 2023-06-10 03-47-09](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/53b5ac0d-c26d-45a8-becd-d528011e293a)
- The user is supposed to enter a channel Id, and click the button **Store data in MongoDB** to push the data to MongoDB.
- The data is stored in MongoDB in JSON Format.


3. **Selecting a channel to migrate the channel data to SQL**
------------
![Screenshot from 2023-06-10 03-51-40](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/ee8df0ce-045e-4c9a-a6db-75a82679a822)
Select the Channel name from the Dropdown, and click the button **Migrate to SQL**,The data will be migrated to MySQL DB.
Once you select the channel and press the migrate button, the channel data would be deleted from mongodb collection, and the channel name won't appear in the dropdown.

4. **Retrieving YouTube information/data from SQL by selecting the Questions in the Dropdown**
------------
![Screenshot from 2023-06-10 04-13-38](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/ee523083-0938-448b-b044-067487d431c8)
![Screenshot from 2023-06-10 04-15-53](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/6471e9e8-a36a-4011-9d03-1d16fd92e234)
![Screenshot from 2023-06-10 04-17-25](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/d710a5d9-4754-476c-a348-6a4a245bb05c)
![Screenshot from 2023-06-10 04-18-26](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/f1279511-5a5c-457b-988d-b5ae6ed7199e)
![Screenshot from 2023-06-10 04-18-51](https://github.com/meetarthi/YouTube-Data-Harvesting-and-Warehousing-/assets/112666126/359dc89f-8a50-4e0b-9095-52a14d2cdbe2)





