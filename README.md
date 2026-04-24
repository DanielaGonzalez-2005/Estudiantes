README.md preview

## 🗄️ MongoDB Atlas & Compass Integration

### MongoDB Atlas

MongoDB Atlas was used as the cloud-hosted database solution for this project.
The connection was established using a standard connection string provided by
Atlas, which was integrated into the application's environment configuration.

The database hosted a collection to store and manage student records, allowing
the app to perform CRUD operations remotely without the need for a local
MongoDB instance.

---

### MongoDB Compass

MongoDB Compass was used as a visual interface to monitor and inspect the
database during development. It allowed direct visualization of the student
collection, making it easier to verify that documents were being correctly
inserted, updated, and deleted.

Compass was especially useful during the **update** phase of the project,
which turned out to be the most challenging part. Seeing the data in real
time helped identify issues with the update logic and validate fixes as
they were applied.

---

### Challenges

The most significant challenge encountered during this project was
implementing the **update functionality**. Correctly targeting existing
documents and applying partial or full updates required careful handling
of MongoDB's update operators and schema validation.

This was ultimately resolved by cross-referencing the data state in
Compass with the application's request/response cycle, which helped
pinpoint where the logic was breaking down.
