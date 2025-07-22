# 📊 Python Data Science Project – Page Recommendation System

Welcome to this Python-based **Data Science project**, where we simulate a mini social network and recommend pages to users based on shared interests and behavior patterns.

---

## 🚀 Project Overview

This project uses a dictionary-based dataset of users and pages to:

- Analyze friendships and liked pages
- Suggest pages a user might like based on mutual interests with other users
- Apply basic recommendation logic without external libraries

---

## 📂 Dataset Structure

The data is stored in JSON format with two main components:

- **Users**: Each has an ID, name, list of friend IDs, and liked page IDs.
- **Pages**: Each has a page ID and a name.

Example:
```json
{
  "users": [
    {"id": 1, "name": "Amit", "friends": [2, 3], "liked_pages": [101]},
    {"id": 2, "name": "Priya", "friends": [1, 4], "liked_pages": [102]}
  ],
  "pages": [
    {"id": 101, "name": "Python Developers"},
    {"id": 102, "name": "Data Science Enthusiasts"}
  ]
}
