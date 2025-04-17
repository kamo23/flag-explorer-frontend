# 🌐 Flag Explorer Frontend

This is the frontend of the **Flag Explorer App**, a modern Angular 19 standalone application that displays country flags and country details. It consumes a REST API served by the .NET 8 backend.

---

## 🚀 Features

- 🧭 Home screen: Grid layout displaying all country flags
- 🧾 Detail view: View a country's name, capital, and population
- ⚡ Built using Angular 19 with standalone components and Vite
- 🧪 Unit and integration test support
- 🐳 Containerized using Docker
- 🔄 CI/CD integration with GitHub Actions

---

## 🛠 Tech Stack

- [Angular 19](https://angular.io/)
- [Vite](https://vitejs.dev/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Docker](https://www.docker.com/)
- [GitHub Actions](https://docs.github.com/en/actions)

---

## 📁 Project Structure

 flag-explorer-frontend/ ├── src/ │ └── app/ │ ├── pages/ # Home and Details components │ ├── services/ # CountryService │ └── models/ # Country interfaces ├── .github/workflows/ci.yml ├── angular.json ├── package.json ├── Dockerfile └── README.md


---

## ⚙️ Setup Instructions

### 1. Clone and install dependencies

```bash
git clone https://github.com/your-org/flag-explorer-frontend.git
cd flag-explorer-frontend
npm install


npm run dev


npm run test


docker build -t flag-explorer-frontend .


docker run -p 4200:80 flag-explorer-frontend
 
