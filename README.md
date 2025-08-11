# Nebusis® Engage

Nebusis® Engage is a modular client engagement and work operating system designed to simplify collaboration, compliance, and operations for businesses, consultants, and government contractors. It provides secure portals, task and project tracking, document management, billing, and AI-powered assistance.

---

## 📌 Features

- **Modular Architecture** – Add or remove modules as needed.
- **Client Portals** – Secure, personalized client spaces.
- **Projects & Tasks** – Track deliverables and progress.
- **Document & Form Management** – Upload, share, and control access.
- **Billing & Payments** – Integrated invoicing and payment processing.
- **Contracts & E-signatures** – Secure digital signing process.
- **AI Assistant Integration** – Context-aware support for workflows.
- **Cloud-based** – Runs on AWS for scalability and security.

---

## 🚀 Getting Started (Local Development)

### Prerequisites
- Node.js 18+ with npm or yarn
- Go 1.21+
- MySQL 8 (or Docker)
- Git
- (Optional) [n8n](https://n8n.io/) for workflow automation

### Clone the Repository
```bash
git clone https://github.com/DonDuro/nebusis-engage.git
cd nebusis-engage
```

### Install Dependencies
#### Backend
```bash
cd backend
go mod tidy
```

#### Frontend
```bash
cd frontend
npm install
```

---

## 🛠 Running the App

### Backend
```bash
cd backend
go run main.go
```

### Frontend
```bash
cd frontend
npm start
```

### Using Docker (Optional)
```bash
docker-compose up --build
```

---

## 📂 Project Structure

```
nebusis-engage/
│
├── backend/             # Go-based API backend
├── frontend/            # React-based user interface
├── docs/                # Documentation
├── docker-compose.yml   # Docker configuration
└── README.md            # Project readme
```

---

## 🧪 Testing
```bash
cd backend
go test ./...
```

---

## 📦 Deployment
Nebusis® Engage is designed to run on AWS infrastructure, using:
- **EC2** for hosting
- **RDS (MySQL)** for database
- **S3** for file storage

---

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📜 License
Proprietary – Nebusis Cloud Services, LLC. All rights reserved.

---

## 🌐 Contact
- **Website:** [www.nebusis.com](https://www.nebusis.com)
- **Email:** info@nebusis.com
