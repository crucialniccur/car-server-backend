# 🚗 Car Review JSON Server API

This is a lightweight backend powered by [JSON Server](https://github.com/typicode/json-server), hosted on [Render](https://car-server-backend.onrender.com), that serves car data for use in frontend apps. It supports full CRUD operations and is perfect for mock testing or MVPs.

## 🔗 Live API URL

> 🌐 [https://car-review-api.onrender.com/cars](https://car-review-api.onrender.com/cars)  
Will replace this later***.

---

## 📦 What’s Inside?

The API exposes a `/cars` route with objects like:

```
{

"name": "M4",

"year": "2014 - Present",

"info": "The BMW M4 is a high-performance sports coupé known for its potent engine, agile handling, and aggressive styling. It's available in various configurations, including the M4 Coupé, M4 Competition Coupé, and the more track-focused M4 CS and M4 CSL. ",

"specs": {

"engine": "2993 cc, 6-cylinder inline, B58 Twin-Turbocharged I6",

"power": "523 bhp @ 6250 rpm",

"torque": "650 Nm @ 2750 rpm",

"drivetrain": "AWD and Rear-Wheel Drive options",

"transmission": "8-speed automatic with paddle shift and Sport Mode",

"acceleration": "(0-100 kmph): 3.5 seconds",

"top Speed": "250 kmph (155 mph)",

"fuel type": "Petrol",

"dimensions": {

"Length": "4794 mm (189.0 in)",

"Width": "1887 mm (75.5 in)",

"Height": "1393 mm (55.1 in)",

"Wheelbase": "2857 mm (112.5 in)"

}
}

```

```

---

## 🔧 Available Routes

| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| GET    | `/cars`          | Fetch all cars           |
| GET    | `/cars/:id`      | Fetch one car by ID      |
| POST   | `/cars`          | Add a new car            |
| PATCH  | `/cars/:id`      | Update a car’s data      |
| DELETE | `/cars/:id`      | Delete a car             |

---

```

4. Make sure `json-server` is listed in `dependencies` in `package.json`.

---

## 🛠 Local Dev Setup

```bash
git clone https://github.com/crucialniccur/car-server-backend
cd car-review-api
npm install
npx json-server --watch db.json --port 3001
```

Then visit: `http://localhost:3001/cars`

---

## 💡 Notes

- This is meant for dev/testing only. JSON Server is not for production.
- No auth, no validation — keep it chill and clean.

---

## Credits

Built with ❤️ by [Mati Joseph]  
Feel free to PR or open issues if you wanna collab or suggest improvements.
Wagwan.
