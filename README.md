# Movies Service (REST API)

This service provides movie data via a simple REST API using json-server.

---

## 📦 Setup

```bash
npm init -y
npm install json-server
```

---

## 📁 File Structure

```
movies-service/
├── package.json
└── movies-list.json
```

---

## 📄 movies-list.json (Sample)

```json
{
  "movies": [
    {
      "id": 1,
      "name": "Fly a Kite",
      "duration": 120,
      "genre": "Fantasy",
      "views": 1000
    },
    {
      "id": 2,
      "name": "Ocean Deep",
      "duration": 90,
      "genre": "Drama",
      "views": 500
    }
  ]
}
```

---

## ▶️ Run Service

```bash
npx json-server --watch movies-list.json --port 3030
```

---

## 🌐 Endpoint

```
GET http://localhost:3030/movies
```

---

## ✅ Purpose

This service acts as the **data source for the Movies subgraph**.
