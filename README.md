## 📌 First time using Mongo

This project demonstrates a complete data pipeline using cloud and online
tools, without relying on a local database setup.

The workflow was structured as follows:

1. **MongoDB Atlas (Cloud Database)**
   A free-tier cluster was created on MongoDB Atlas to host the database
   online. From there, a connection string was generated and used to link
   the cloud database to MongoDB Compass on the local machine, enabling
   visual inspection and management of the collections.

2. **Google Colab (Data Entry Interface)**
   The Atlas connection string was also integrated into a Google Colab
   notebook using the PyMongo library. This allowed student records to be
   entered directly from the notebook and stored in real time into the
   MongoDB Atlas database, with no need for a local server.

3. **Data Export**
   Once the student data was successfully stored in MongoDB, the collection
   was exported in CSV format, making it available for further analysis or
   reporting outside the database environment.

---

### 🔧 Tools Used

| Tool             | Purpose                                      |
|------------------|----------------------------------------------|
| MongoDB Atlas    | Cloud-hosted database (cluster creation)     |
| MongoDB Compass  | Visual interface to browse collections       |
| Google Colab     | Data entry via Python (PyMongo)              |
| CSV Export       | Data extraction for external use             |
