# SAITM Student Records Database

This repository contains a MySQL database dump file named `saitm_tan9.sql`. It consists of a table called `tan9` that stores sample student records, useful for learning SQL, academic projects, and CRUD practice.

## File Information

| File Name        | Description                             |
|------------------|-----------------------------------------|
| saitm_tan9.sql   | MySQL dump containing table and records |

## Table Structure

The `tan9` table includes the following columns:

| Column | Type        | Description       |
|--------|-------------|-------------------|
| name   | VARCHAR(30) | Student name      |
| rollno | INT         | Roll number       |
| grade  | VARCHAR(10) | Student grade     |
| marks  | INT         | Marks obtained    |

## Sample Data

| Name   | Roll No | Grade | Marks |
|--------|---------|--------|-------|
| aman   | 1       | A      | 80    |
| shivam | 2       | A      | 77    |
| rahul  | 3       | B      | 55    |
| manoj  | 4       | B+     | 60    |
| tushar | 5       | B+     | 65    |
| amit   | 6       | B      | 53    |
| sahil  | 7       | B      | 52    |

## Requirements

- MySQL Server 8.0+
- Optional: phpMyAdmin or MySQL Workbench

## How to Import

### Method 1: Command Line
```bash
mysql -u root -p saitm < saitm_tan9.sql
