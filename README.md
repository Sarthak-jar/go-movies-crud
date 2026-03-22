# 🎬 Go Movies CRUD API

A RESTful CRUD API built using **Go (Golang)** and **Gorilla Mux**.
This project demonstrates backend development concepts such as routing, JSON handling, and API design.

---

## 🚀 Features

* Create, Read, Update, and Delete (CRUD) operations
* RESTful API architecture
* JSON request and response handling
* API testing using Postman

---

## 🛠️ Tech Stack

* Go (Golang)
* Gorilla Mux
* net/http
* Postman (for API testing)

---

## 📂 Project Structure

```
go-movies-crud/
│── main.go
│── go.mod
│── go.sum
│── .gitignore
│── README.md
```

---

## ▶️ Getting Started

### Prerequisites

* Go installed on your system

### Run the project

```bash
go run main.go
```

Server will start at:

```
http://localhost:8000
```

---

## 📡 API Endpoints

| Method | Endpoint     | Description        |
| ------ | ------------ | ------------------ |
| GET    | /movies      | Get all movies     |
| GET    | /movies/{id} | Get movie by ID    |
| POST   | /movies      | Create a new movie |
| PUT    | /movies/{id} | Update a movie     |
| DELETE | /movies/{id} | Delete a movie     |

---

## 🧪 API Testing

All endpoints were tested using **Postman** to ensure correct request handling and responses.

---

## 📌 Example JSON

```json
{
  "id": "1",
  "isbn": "438227",
  "title": "Movie Name",
  "director": {
    "firstname": "John",
    "lastname": "Doe"
  }
}
```



This project was built as part of learning backend development in Go.
