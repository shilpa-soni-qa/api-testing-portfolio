# API Testing Portfolio — Shilpa Soni

REST API Testing Portfolio using Postman and JSONPlaceholder API.

## 🛠️ Tools Used
- Postman
- JSONPlaceholder API (https://jsonplaceholder.typicode.com)

## 📁 Collection Structure

### Users Folder
| Request | Method | Tests |
|---------|--------|-------|
| Get All Users | GET | 3 |
| Get Single User | GET | 4 |
| Create User | POST | 3 |
| Update User | PUT | 3 |
| Delete User | DELETE | 2 |

### Posts Folder
| Request | Method | Tests |
|---------|--------|-------|
| Get All Posts | GET | 3 |
| Get Single Post | GET | 3 |
| Create Post | POST | 3 |
| Update Post | PUT | 3 |
| Delete Post | DELETE | 2 |

### Negative Tests Folder
| Request | Method | Tests |
|---------|--------|-------|
| Get Invalid User | GET | 2 |
| Get Invalid Endpoint | GET | 1 |
| Create Post Empty Body | POST | 2 |

## ✅ Test Results
- Total Requests: 13
- Total Test Cases: 39
- All Tests Passing: ✅

## 📋 What is Tested
- Status codes (200, 201, 404)
- Response body validation
- JSON field existence
- Positive and negative scenarios

## 🔗 How to Run
1. Install Postman
2. Import `API-Testing-Portfolio.postman_collection.json`
3. Click Run Collection
4. All 34 tests should pass ✅

## 👩‍💻 Author
**Shilpa Soni** — QA Automation Engineer  
GitHub: https://github.com/shilpa-soni-qa  
LinkedIn: https://www.linkedin.com/in/shilpasoni94
