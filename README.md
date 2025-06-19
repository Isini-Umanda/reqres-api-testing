# Manual API Testing with Postman – Reqres API

This repository contains a collection of manual API tests created using Postman, based on the publicly available [Reqres API](https://reqres.in/).

---

## Files Included

 `Reqres API.postman_collection.json`: The exported Postman collection with all test requests.

---

## How to Use This Collection

1. Open **Postman**
2. Click **Import** → Select the file `Reqres API.postman_collection.json`
3. The collection will appear in your workspace
4. You can now run the requests and verify responses manually

---

## What’s Covered in This Collection

| Endpoint                        | Method  | Purpose                       |

| `/api/users?page=2`             | GET     | List users                    |

| `/api/users/2`                  | GET     | Get single user               |

| `/api/users`                    | POST    | Create user                   |

| `/api/users/2`                  | PUT     | Update entire user            |

| `/api/users/2`                  | PATCH   | Update partial user           |

| `/api/users/7`                  | DELETE  | Delete user                   |

| `/api/register`                | POST    | Register user                 |

| `/api/login`                   | POST    | Login user                    |

| `/api/unknown`                 | GET     | Get resource list             |

| `/api/users?delay=2`           | GET     | Get users with delay (simulate slow API) |

---

## Tools Used

- **Postman** for manual API testing
- **Reqres.in** as the API source (mock API for testing)

---


