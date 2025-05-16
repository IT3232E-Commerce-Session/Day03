# Day03
# Student Management API

## Description
This is a simple Spring Boot REST API for managing students. The API allows users to retrieve student details, perform CRUD operations, and filter students based on their age.

## Overview
This Spring Boot application provides a RESTful API to manage student data. It includes functionalities to:
- Retrieve all students
- Retrieve a specific student by registration number
- Filter students within a specific age range
- Add a new student
- Update an existing student's details
- Delete a student record

## API Endpoints

### General Endpoints
```http
GET /app/msg
```
**Description:** Returns a welcome message

```http
GET /app/name
```
**Description:** Returns application name

```http
GET /app/age/{ag}
```
**Description:** Returns age from parameter

### Student Endpoints
```http
GET /app/students
```
**Description:** Retrieves all students

```http
GET /app/students/{reg}
```
**Description:** Retrieves a student by registration number

```http
GET /app/students/age-between
```
**Description:** Finds students with age between 20-23

```http
POST /app/students
```
**Description:** Adds a new student

```http
PUT /app/students/{id}
```
**Description:** Updates a student's details

```http
DELETE /app/students/{id}
```
**Description:** Deletes a student

