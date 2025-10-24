<!-- Improved modern README with better structure and visuals -->
<div align="center">
  <img src="public/img/logo.png" alt="Gembok Bill Logo" width="120" height="120">
  
  # Gembok Bill
  **Integrated ISP Management System**
  
  [![Node.js](https://img.shields.io/badge/Node.js-18.x-green?style=for-the-badge&logo=node.js)](https://nodejs.org/)
  [![License](https://img.shields.io/badge/license-ISC-blue?style=for-the-badge)](LICENSE)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](https://github.com/alijayanet/gembok-bill/pulls)
  [![GitHub Stars](https://img.shields.io/github/stars/alijayanet/gembok-bill?style=for-the-badge)](https://github.com/alijayanet/gembok-bill/stargazers)
</div>

## 🌐 About Gembok Bill

**Gembok Bill** is an integrated ISP management system designed to handle billing, customer service, and network operations through WhatsApp integration. This system provides an end-to-end solution for Internet Service Provider management with advanced features.

### 🚀 Key Features

- **📱 WhatsApp Gateway**: Customer interaction, voucher distribution, issue reporting, and automatic notifications
- **📡 GenieACS Integration**: Centralized CPE (Customer Premises Equipment) management
- **🔗 Mikrotik PPPoE & Hotspot Management**: User authentication and real-time bandwidth control
- **💳 Billing System**: Automatic invoice generation, payment tracking, and remittance
- **👥 Agent & Technician Management**: Role-based access control and flexible task assignment
- **📂 Database Migration**: SQL-based schema updates for continuous development
- **🗺️ Cable Network Mapping**: Visual management of ODPs, poles, and cable layouts

## 🛠️ Technologies Used

| Category | Technology |
|----------|-------------|
| **Backend** | Node.js, Express |
| **Database** | SQLite (development), MySQL (production) |
| **Frontend** | EJS, HTML5, CSS3, JavaScript |
| **WhatsApp** | [@whiskeysockets/baileys](https://github.com/WhiskeySockets/Baileys) |
| **Network** | Node-routeros for Mikrotik |
| **Payment** | Midtrans, Xendit |
| **Logging** | Winston, Pino |

## 📋 System Requirements

- **Node.js** >= 20.0.0
- **npm** >= 6.0.0
- **Database** SQLite (for development) or MySQL (for production)
- **WhatsApp Business Access** (for WhatsApp Gateway features)

## 🚀 Quick Installation

### 1. Clone Repository
```bash
git clone https://github.com/alijayanet/gembok-bill.git
```
```bash
cd gembok-bill
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Initialize Database
```bash
npm run setup
```

### 5. Run the Application
```bash
# For production
npm start
```
# For development
```bash
npm run dev
```

## 📁 Project Structure

```
gembok-bill/
├── app.js                  # Application entry point
├── package.json            # Dependencies and scripts
├── config/                 # Configuration files
├── data/                   # Database and backups
├── migrations/             # Database migration files
├── public/                 # Static files (CSS, JS, images)
├── routes/                 # API endpoints
├── scripts/                # Utility scripts
├── utils/                  # Utility functions
└── views/                  # EJS templates
```

## 📖 Complete Documentation

| Document | Description |
|---------|-----------|
| [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md) | Complete deployment guide for new servers |
| [DATA_README.md](DATA_README.md) | Information about data management |
| [WHATSAPP_SETUP.md](WHATSAPP_SETUP.md) | WhatsApp Gateway configuration |
| [WHATSAPP_FIX_SUMMARY.md](WHATSAPP_FIX_SUMMARY.md) | Summary of WhatsApp fixes |

## 🎯 How to Contribute

We welcome contributions from the community! Here’s how you can contribute:

1. **Fork** this repository
2. Create a **feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit** changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

### Contribution Guidelines
- Follow the existing code style
- Add documentation for new features
- Make sure all tests pass successfully
- Update README if necessary

## 📞 Support

If you need help:

- Create an **issue** on [GitHub Issues](https://github.com/alijayanet/gembok-bill/issues)
- Contact the development team via email
- Join the Discord community (if available)

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for more details.

## 👥 Development Team

- **ALIJAYA Team** - [@alijayanet](https://github.com/alijayanet)

## 🙏 Acknowledgements

- Thanks to all contributors who supported the project’s development
- The open-source community for inspiration and support

---
<div align="center">
  
  💻 Developed with ❤️ for the Indonesian ISP community
  
  [Report a Bug](https://github.com/alijayanet/gembok-bill/issues) · [Request a Feature](https://github.com/alijayanet/gembok-bill/issues) · [Documentation](DEPLOYMENT_GUIDE.md)
  
</div>
