Here are the 10 most used beginner MongoDB commands with simple examples and explanations:

# MongoDB Beginner's Cheat Sheet

## 1. Start MongoDB
- **Start MongoDB Server**:
  ```
  mongod
  ```
  *Imagine this as turning on the engine of a car. This command starts the MongoDB server.*

## 2. Connect to MongoDB
- **Connect to MongoDB**:
  ```
  mongo
  ```
  *This command is like opening the car door and getting inside. It connects you to the MongoDB server.*

## 3. Show Databases
- **Show Databases**:
  ```
  show dbs
  ```
  *Think of this as opening the glove box to see all the maps (databases) you have. This command shows all the databases.*

## 4. Create or Switch Database
- **Create or Switch Database**:
  ```
  use school
  ```
  *This is like picking a specific map to follow. If the map (database) doesn’t exist, MongoDB creates it for you. Here, we’re creating or switching to a database called "school".*

## 5. Show Collections
- **Show Collections**:
  ```
  show collections
  ```
  *Collections are like folders in a file cabinet. This command shows all the collections (folders) in the current database.*

## 6. Create Collection
- **Create Collection**:
  ```
  db.createCollection("students")
  ```
  *Imagine creating a new folder in your file cabinet to store student records. This command creates a new collection called "students".*

## 7. Insert One Document
- **Insert One Document**:
  ```
  db.students.insertOne({ name: "John", age: 12 })
  ```
  *This is like adding a single file (document) into the students folder (collection). We’re adding a student named John who is 12 years old.*

## 8. Find All Documents
- **Find All Documents**:
  ```
  db.students.find()
  ```
  *Imagine looking through all the files in the students folder. This command shows all the documents in the students collection.*

## 9. Update One Document
- **Update One Document**:
  ```
  db.students.updateOne({ name: "John" }, { $set: { age: 13 } })
  ```
  *This is like finding John’s file and changing his age from 12 to 13. The command updates one document that matches the name "John".*

## 10. Delete One Document
- **Delete One Document**:
  ```
  db.students.deleteOne({ name: "John" })
  ```
  *Imagine taking John’s file out of the folder and throwing it away. This command deletes one document that matches the name "John".*

## Summary
This cheat sheet covers the 10 most common MongoDB commands for beginners, with simple explanations and examples. Use these commands to start, connect to, and interact with your MongoDB server, databases, and collections.
