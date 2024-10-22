# MongoDB-Library-Management-System

This project is a simple **Library Management System** using **MongoDB**. It demonstrates the basic CRUD operations (Create, Read, Update, Delete) as well as advanced queries using MongoDB shell commands. The system manages a collection of books, authors, and patrons.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Setup Instructions](#setup-instructions)
3. [Database Creation](#database-creation)
4. [Collections and Documents](#collections-and-documents)
    - [Books Collection](#books-collection)
    - [Authors Collection](#authors-collection)
    - [Patrons Collection](#patrons-collection)
5. [CRUD Operations](#crud-operations)
    - [Read Operations](#read-operations)
    - [Update Operations](#update-operations)
    - [Delete Operations](#delete-operations)
6. [Advanced Queries](#advanced-queries)

---

## Introduction

This project focuses on the basic MongoDB commands and terminology needed to interact with a database via **MongoDB Compass**. It includes CRUD operations on collections such as **Books**, **Authors**, and **Patrons**, as well as more complex queries.

---

## Setup Instructions

### Prerequisites

- **MongoDB Compass**: Make sure you have **MongoDB Compass** installed. If not, [install it here](https://www.mongodb.com/try/download/compass).
- **MongoDB Shell (Mongosh)**: You can also use **MongoDB Shell** for command-line operations. [Install it here](https://www.mongodb.com/try/download/shell).

### Steps to Connect to MongoDB via MongoDB Compass

1. Download and install **MongoDB Compass**.
2. Launch **MongoDB Compass** and connect using `localhost:27017` (if you are running a local instance of MongoDB).
3. Create a new database called `LibraryDB`.
4. Once connected, you can begin creating collections and inserting documents.

---

## Database Creation

Once connected to **MongoDB Compass**, create the `LibraryDB` database by simply entering `LibraryDB` in the database name field in **Compass** and clicking "Create Database."

---

## Collections and Documents

### Books Collection

To create the `Books` collection, navigate to **Compass**, select `LibraryDB`, and create a new collection called `Books`.

Here’s an example of a document in the `Books` collection:

```json
{
  "_id": 1,
  "title": "1984",
  "author_id": 1,
  "published_year": 1949,
  "available": true
}
