# 🤖 BORG - Byggt á Opinberum Rannsóknum og Gögnum

![Status](https://img.shields.io/badge/Status-Alpha%20Production-yellow)
![Users](https://img.shields.io/badge/Users-15--20%20Active-green)
![Tech](https://img.shields.io/badge/Tech-Python%20%7C%20FastAPI%20%7C%20RAG-blue)

> Innri AI spjallþjón og upplýsingakerfi fyrir starfsfólk Háskóla Akureyrar með áherslu á intelligent skjalaleit og talgreiningu.

## 🎯 Verkefnayfirlit

BORG er comprehensive AI assistance platform sem byggir á **Retrieval-Augmented Generation (RAG)** tækni til að veita starfsfólki HA aðgang að snjallri upplýsingaleit, skjalagreiningu og AI aðstoð í daglegum verkefnum.

### 🔑 Lykileiginleikar

- **🔍 Smart Document Search**: RAG-based leit í innri skjölum og gögnum
- **💬 AI Chat Assistant**: OpenAI-powered spjallþjón fyrir almennar spurningar
- **🎙️ Voice-to-Text**: Whisper AI integration fyrir talgreiningu
- **📊 Analytics Dashboard**: Notkunartölfræði og insights
- **🔐 Secure Access**: Role-based authentication og data privacy

## 📈 Núverandi staða

### Alpha Production (frá janúar 2025)
- **Notendur:** 15-20 virkir starfsmenn
- **Uptime:** 99.2% síðustu 30 daga
- **Average Response Time:** <2 sekúndur
- **Document Index:** 500+ skjöl í RAG database

### 📊 Usage Metrics (síðasta mánuður)
- **Spurningar per dag:** ~45-60
- **Vinsælustu categories:** Stefnur (35%), Procedures (28%), Research (22%), Other (15%)
- **User Satisfaction:** 4.2/5 (byggt á feedback)

## 🛠️ Tæknileg uppbygging

### Tech Stack
```
Frontend:
├── React.js (v18.2)
├── TypeScript
├── Material-UI
└── Socket.io (real-time chat)

Backend:
├── Python 3.11
├── FastAPI
├── PostgreSQL (document storage)
├── Redis (caching)
├── Celery (async tasks)
└── Docker Compose

AI/ML:
├── OpenAI GPT-4 (chat responses)
├── Whisper (speech-to-text)
├── LangChain (RAG orchestration)
├── ChromaDB (vector storage)
└── SentenceTransformers (embeddings)
```

### 🏗️ Architecture Overview

```mermaid
graph TB
    A[Web Frontend] --> B[FastAPI Gateway]
    B --> C[Authentication Service]
    B --> D[Chat Service]
    B --> E[Document Service]
    
    D --> F[OpenAI API]
    D --> G[RAG Engine]
    E --> H[Document Database]
    G --> I[Vector Database]
    
    J[Admin Dashboard] --> B
    K[Voice Input] --> L[Whisper Service]
    L --> D
```

## 🔧 Installation & Setup

### Prerequisites
- Python 3.11+
- Docker & Docker Compose
- PostgreSQL 15+
- Redis 7+

### Quick Start
```bash
# Clone the repository
git clone https://github.com/magnussmari/borg-system.git
cd borg-system

# Setup environment
cp .env.example .env
# Edit .env with your configurations

# Start with Docker Compose
docker-compose up -d

# Initialize database
docker-compose exec api python manage.py migrate
docker-compose exec api python manage.py create-admin

# Access the application
# Web: http://localhost:3000
# API: http://localhost:8000
# Admin: http://localhost:8000/admin
```

### 🔑 Environment Variables
```bash
# OpenAI Configuration
OPENAI_API_KEY=your_openai_key
OPENAI_MODEL=gpt-4

# Database
DATABASE_URL=postgresql://user:pass@localhost:5432/borg
REDIS_URL=redis://localhost:6379

# Authentication
JWT_SECRET=your_jwt_secret
LDAP_SERVER=ldap.unak.is  # For UNAK authentication

# File Storage
UPLOAD_PATH=/data/uploads
MAX_FILE_SIZE=50MB
```

## 📋 Beta útgáfa - Roadmap

### 🎯 Q2 2025 (Beta Launch)
- [ ] **Extended User Base**: Rollout til allra 150+ starfsmanna
- [ ] **Mobile App**: iOS/Android companion app
- [ ] **Advanced Analytics**: Comprehensive usage insights
- [ ] **Multi-language Support**: Enska og íslenska interface
- [ ] **API Integration**: Tengingar við Outlook, Teams, SharePoint

### 🎯 Q3 2025 (Feature Expansion)
- [ ] **Custom Knowledge Bases**: Department-specific RAG databases  
- [ ] **Workflow Automation**: Smart task suggestions og reminders
- [ ] **Video Analysis**: Integration með Teams recordings
- [ ] **Advanced Search**: Semantic search með filters
- [ ] **Collaboration Tools**: Shared documents og annotations

### 🎯 Q4 2025 (Enterprise Features)
- [ ] **Single Sign-On (SSO)**: Full LDAP/Active Directory integration
- [ ] **Compliance Dashboard**: GDPR og data governance tools
- [ ] **Custom Integrations**: Third-party API connections
- [ ] **Advanced Security**: End-to-end encryption, audit logs
- [ ] **Performance Optimization**: Sub-second response times

## 📊 Development Status

| Component | Status | Progress | Next Milestone |
|-----------|--------|----------|----------------|
| Core Chat | ✅ Live | 95% | Performance optimization |
| RAG Engine | ✅ Live | 90% | Semantic filtering |
| Voice Input | ✅ Live | 85% | Noise reduction |
| Admin Dashboard | 🟡 Beta | 70% | Advanced analytics |
| Mobile App | 🔴 Planning | 10% | MVP development |
| API Gateway | 🟡 Beta | 80% | Rate limiting |

## 🧪 Testing

### Automated Testing
```bash
# Run full test suite
docker-compose exec api pytest tests/ -v

# Run specific test categories
pytest tests/test_rag.py -v        # RAG functionality
pytest tests/test_auth.py -v       # Authentication
pytest tests/test_api.py -v        # API endpoints
```

### Manual Testing Checklist
- [ ] Chat conversation flow
- [ ] Document upload og indexing
- [ ] Voice input accuracy
- [ ] Multi-user sessions
- [ ] Performance under load

## 🔒 Security og Privacy

### Data Protection
- **Encryption**: All data encrypted at rest og in transit
- **Access Control**: Role-based permissions (Admin, User, Guest)
- **Audit Logging**: Complete activity tracking
- **Data Retention**: 90-day automatic cleanup of chat history
- **GDPR Compliance**: User data export og deletion rights

### Privacy Measures
- Engar persónulegar samtöl sendar til OpenAI
- Local Whisper processing fyrir talgreining
- Anonymized analytics data
- Opt-out possibilities fyrir alla data collection

## 📞 Support og Documentation

### 🆘 Getting Help
- **Internal Slack**: #borg-support channel
- **Email**: borg-support@unak.is  
- **Office Hours**: Þriðjudaga 14:00-15:00 (H209)
- **Emergency**: Magnús Smári (magnuss@unak.is)

### 📚 Resources
- [User Manual](./docs/user-manual.md)
- [API Documentation](./docs/api-docs.md)
- [FAQ](./docs/faq.md)
- [Video Tutorials](https://video.unak.is/borg-tutorials)

## 🤝 Contributing

Sjá [Contributing Guidelines](../../FRAMTÖK.md) fyrir almennar reglur.

### BORG-specific Guidelines
1. **Code Style**: Black formatting, type hints required
2. **Testing**: 80%+ test coverage for new features  
3. **Documentation**: Docstrings fyrir allar public functions
4. **Security**: Security review required fyrir user-facing changes

### 🐛 Bug Reports
Template fyrir bug reports:
```markdown
**Environment:** Production/Staging/Development
**User Role:** Admin/User/Guest
**Browser:** Chrome/Safari/Firefox + version
**Steps to Reproduce:**
1. ...
2. ...
**Expected vs Actual Result:**
**Screenshots/Logs:**
```

## 📈 Metrics og Analytics

### Business Metrics
- **User Adoption Rate**: 45% of all staff (target: 80% by Q3)
- **Daily Active Users**: 12-15 average (target: 25+ by Q4)
- **Query Success Rate**: 87% (target: 95%)
- **User Retention**: 92% week-over-week

### Technical Metrics
- **API Response Time**: 1.8s average (target: <1s)
- **System Uptime**: 99.2% (target: 99.5%)
- **Error Rate**: <2% (target: <1%)
- **Database Query Performance**: 150ms average

## 🚀 Deployment

### Production Environment
- **Hosting**: UNAK private cloud
- **Load Balancer**: Nginx with SSL termination
- **Monitoring**: Prometheus + Grafana
- **Backups**: Daily automated með 30-day retention
- **CI/CD**: GitHub Actions fyrir automated testing og deployment

### Staging Environment
- **Purpose**: Pre-production testing og user acceptance
- **URL**: https://borg-staging.unak.is
- **Data**: Anonymized production subset
- **Deployment**: Automatic við merge til `develop` branch

---

## 📞 Team og Contact

**Project Lead:** Magnús Smári (magnuss@unak.is)  
**Technical Lead:** [TBD]  
**Product Owner:** [TBD]  

**Development Team:**
- Backend Development: Magnús Smári
- Frontend Development: [External contractor]
- DevOps: UNAK IT Department
- Testing: [TBD]

---

<div align="center">
  <strong>🤖 BORG - Intelligent AI fyrir Háskóla Akureyrar</strong>
  <br>
  <em>Byggt með áherslu á privacy, security og user experience</em>
</div>
