# Pipeyard - AI Agent Integration Marketplace

A curated marketplace of pre-built MCP servers organized by industry and software type.

## Vision
Hundreds of developers are building the same AI agent integrations without knowing it. Pipeyard solves this by providing a central directory where developers can find, test, and deploy pre-built connectors in minutes instead of weeks.

## Features (MVP)
- 🔍 Browse MCP servers by industry (Construction, Medical, Logistics)
- 🧪 Sandbox testing environment
- ⚡ One-click deployment
- 📊 Usage analytics
- 💳 Subscription-based pricing ($50-$300/month)

## Tech Stack
- Backend: Python (Flask/FastAPI)
- Database: SQLite (MVP) → PostgreSQL (production)
- Frontend: HTML/CSS/JavaScript
- Deployment: GitHub Actions, Docker

## Getting Started

### Prerequisites
- Python 3.9+
- pip
- Git

### Installation
```bash
git clone https://github.com/Abulla2Marketplace/pipeyard.git
cd pipeyard
pip install -r requirements.txt
python app.py
```

Visit `http://localhost:5000` to see the app.

## Project Phases

### Phase 1: MVP (Week 1-2)
- [ ] Basic Flask app with connector listings
- [ ] SQLite database for connectors
- [ ] Category filtering (Construction, Medical, Logistics)
- [ ] Simple HTML frontend

### Phase 2: Core Features (Week 3-4)
- [ ] User authentication
- [ ] Sandbox testing
- [ ] One-click deployment mock
- [ ] Search functionality

### Phase 3: Scaling (Week 5+)
- [ ] Payment integration (Stripe)
- [ ] Usage analytics
- [ ] Advanced filtering
- [ ] API documentation

## Contributing
Contributions welcome! Start by picking an issue from the GitHub Issues tab.

## License
MIT

---

**Built with ❤️ for developers tired of reinventing the wheel.**