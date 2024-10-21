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
7. [Backup Instructions](#backup-instructions)
8. [Conclusion](#conclusion)

---

## Introduction

This project focuses on the basic MongoDB commands and terminology needed to interact with a database via the MongoDB shell (Mongosh). It includes CRUD operations on collections such as **Books**, **Authors**, and **Patrons**, as well as more complex queries.

---

## Setup Instructions

### Prerequisites

- **MongoDB Atlas Account**: Set up a free or paid cluster on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
- **MongoDB Shell (Mongosh)**: Make sure you have **MongoDB shell** installed. If not, [install it here](https://www.mongodb.com/try/download/shell).

### Steps to Connect to MongoDB Atlas

1. After logging into MongoDB Atlas, create a new cluster if you haven't done so.
2. Navigate to the **Database Access** tab, and create a user with a **username** and **password**. 
3. Get the **connection string** from the **Connect** button in your Atlas cluster. Use the following command to connect to your cluster using MongoDB shell:

```bash
mongosh "mongodb+srv://<cluster-url>/LibraryDB" --mabohlalenkuna --password 
```
**to create database run**
```
use LibraryDB

```
