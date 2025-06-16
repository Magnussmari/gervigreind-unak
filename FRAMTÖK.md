# 🤝 Framlag til Gervigreind verkefna - UNAK

Takk fyrir áhugann á að leggja til verkefnin okkar! Þessi leiðbeiningar hjálpa þér að skilja hvernig þú getur lagt þitt af mörkum á árangursríkan hátt.

## 🎯 Leiðarljós

Við viljum búa til **opið, gegnsætt og samvinnumiðað** umhverfi þar sem:
- 🔬 **Vísindaleg gæði** eru í fyrirrúmi
- 🤖 **Siðferðileg AI þróun** er leiðandi
- 🌍 **Samfélagsáhrif** eru jákvæð
- 📚 **Þekkingarmiðlun** er aðgengileg öllum

## 🚀 Hvernig á að leggja til

### 1️⃣ 🐛 Tilkynna vandamál (Issues)

**Fyrir villur og vandamál:**
```markdown
🐛 Bug Report Template:
- **Lýsing**: Hvað fór úrskeiðis?
- **Skref til að endurtaka**: 1, 2, 3...
- **Vænt niðurstaða**: Hvað átti að gerast?
- **Raunveruleg niðurstaða**: Hvað gerðist í raun?
- **Umhverfi**: OS, browser, version
- **Screenshots**: Ef við á
```

**Fyrir nýjar hugmyndir:**
```markdown
💡 Feature Request Template:
- **Vandamál**: Hvaða vandamál leysir þetta?
- **Lausn**: Hvað stingur þú upp á?
- **Valkostir**: Aðrar leiðir til að leysa þetta?
- **Samhengi**: Hvaða verkefni varðar þetta?
- **Ávinningur**: Hver verður ávinningurinn?
```

### 2️⃣ 🔄 Pull Requests

**Skref fyrir skref:**

1. **🍴 Fork repository-ið** á þína GitHub aðganginn
2. **🌿 Búðu til nýja grein** með lýsandi nafni:
   ```bash
   git checkout -b feature/ai-stefna-uppfærsla
   git checkout -b fix/borg-skjalaskoðun
   git checkout -b docs/arctic-tracker-leiðbeiningar
   ```

3. **✏️ Gerðu þínar breytingar** með góðum venjum:
   - Smáar, rökréttar breytingar
   - Skýr commit messages á íslensku/ensku
   - Fylgdu núverandi kóðastíl

4. **🧪 Prófaðu breytingarnar**:
   ```bash
   # Fyrir markdown breytingar
   markdownlint *.md
   
   # Fyrir kóða (ef við á)
   npm test
   python -m pytest
   ```

5. **📤 Push og opnaðu PR**:
   ```bash
   git push origin feature/mitt-feature
   ```

**PR Template:**
```markdown
## 📝 Lýsing
Stutt lýsing á því hvað þessi PR gerir.

## 🎯 Tengist Issue
Fixes #123 eða Related to #456

## 🧪 Testing
- [ ] Prófaði locally
- [ ] Uppfærði skjölun
- [ ] Bætti við tests (ef við á)

## 📸 Screenshots
(Ef UI breytingar)

## ✅ Checklist
- [ ] Kóði fylgir style guide
- [ ] Commit messages eru skýr
- [ ] Skjölun er uppfærð
- [ ] Engar breaking changes (eða skjalfest)
```

### 3️⃣ 📚 Skjöl og efni

**Hvað við þurfum hjálp með:**
- 📖 **Þýðingar**: Íslenska/enska skjöl
- 🎨 **Grafík**: Diagrams, charts, illustrations  
- 📹 **Video content**: Tutorials, explanations
- 📝 **Technical writing**: API docs, user guides
- 🔍 **Proofreading**: Grammar, accuracy, clarity

**Skjalastíll:**
- **Markdown format** fyrir alla skjölun
- **Íslenska** fyrir almennt efni, **enska** fyrir technical details
- **Consistent headers** og structure
- **Images** í `assets/` möppu með descriptive nöfnum

### 4️⃣ 💻 Kóði og Technical

**Coding Standards:**

**Python (BORG, data analysis):**
```python
# Black formatting
# Type hints required
# Docstrings fyrir public functions
def process_documents(docs: List[Document]) -> Dict[str, Any]:
    """Process documents for RAG indexing.
    
    Args:
        docs: List of document objects to process
        
    Returns:
        Dictionary with processed results and metadata
    """
    pass
```

**JavaScript/TypeScript (frontend):**
```javascript
// Prettier formatting
// ESLint compliance
// JSDoc fyrir functions
/**
 * Update project status in Notion
 * @param {string} projectId - The project identifier
 * @param {Object} status - Status update object
 * @returns {Promise<boolean>} Success status
 */
async function updateProjectStatus(projectId, status) {
    // Implementation
}
```

**Markdown (skjölun):**
```markdown
# Use proper heading hierarchy
## Don't skip levels
### This is correct progression

- Use consistent bullet styles
- Add line breaks between sections
- Include table of contents for long docs

**Bold for emphasis**, *italic for subtle emphasis*
`code snippets` for technical terms
```

## 🏗️ Verkefnaskipulag

### 📁 Directory Structure
```
gervigreind-unak/
├── 📄 README.md              # Aðal overview
├── 📄 FRAMTÖK.md             # Þessi skrá
├── 📄 LICENSE                # MIT license
├── 📁 verkefni/              # Verkefnamöppur
│   ├── 📁 borg-kerfi/        # BORG project
│   ├── 📁 ai-stefna/         # AI policy
│   ├── 📁 scite-innleiding/  # Scite integration
│   ├── 📁 arctic-tracker/   # Arctic research
│   └── 📁 hladhvarp/         # Podcast project
├── 📁 skjol/                 # Shared documents
│   ├── 📄 grunnupplysingar.md
│   └── 📁 sniðmöt/          # Templates
├── 📁 .github/              # GitHub configuration
│   ├── 📁 ISSUE_TEMPLATE/   # Issue templates
│   └── 📁 workflows/        # GitHub Actions
└── 📁 assets/               # Images, charts, media
```

### 🎯 Project Ownership

| Verkefni | Primary Owner | Secondary | Status |
|----------|---------------|-----------|---------|
| **BORG kerfið** | Magnús Smári | IT Dept | Production |
| **AI Stefna** | Magnús Smári | Legal Team | Review |
| **Scite Integration** | Magnús Smári | Library | Complete |
| **Arctic Tracker** | Magnús & Tom Barry | Students | Development |
| **Temjum Tæknina** | Magnús Smári | Media Lab | Active |

## 🔄 Workflow og Process

### 🌿 Branch Strategy

```
main (production-ready)
├── develop (integration branch)
├── feature/verkefni-nafn (new features)
├── fix/villa-lýsing (bug fixes)
├── docs/skjal-uppfærsla (documentation)
└── hotfix/critical-fix (urgent fixes)
```

### 📝 Commit Message Format

**Íslenska (preferred fyrir documentation):**
```bash
git commit -m "bæta: nýjum kafla um AI siðferði í stefnu"
git commit -m "laga: brotinn tengill í Arctic Tracker skjölun"
git commit -m "uppfæra: framfarir í BORG verkefni"
```

**English (fyrir code):**
```bash
git commit -m "feat: add user authentication to BORG API"
git commit -m "fix: resolve database connection timeout"
git commit -m "docs: update API documentation"
```

**Format:**
- `feat:` nýr eiginleiki
- `fix:` villa lagfæring
- `docs:` skjölunarbreytingar
- `style:` formatting, no code changes
- `refactor:` code cleanup
- `test:` test additions/fixes
- `chore:` maintenance tasks

### 🔍 Review Process

**Allar PR fara í gegnum:**
1. **🤖 Automated checks**: GitHub Actions validation
2. **👥 Peer review**: Að minnsta kosti 1 approval
3. **🧪 Testing**: Local og automated tests
4. **📚 Documentation**: Uppfærð skjölun ef þörf
5. **🚀 Merge**: Squash og merge til main

## 👥 Community Guidelines

### 🤝 Hegðunarreglur

**Við hvötum til:**
- 🎓 **Lærdómsmiðaðrar nálgunar** - mistök eru tækifæri
- 🌍 **Víðsýnni** - virðum mismunandi bakgrunna og skoðanir
- 💬 **Byggilegs samskiptis** - useful feedback og tillögur
- 🔄 **Samvinnu** - hjálpum hvort öðru að ná árangri
- 📈 **Stöðugra bætiferlis** - alltaf að læra og bæta

**Við tolerum ekki:**
- 🚫 Harassment eða mismunun
- 🚫 Trolling eða óviðeigandi hegðun
- 🚫 Spam eða off-topic content
- 🚫 Breach of confidentiality
- 🚫 Academic dishonesty

### 📞 Að fá hjálp

**Spurningar og stuðningur:**

1. **📖 Check documentation first**: README, project docs, FAQ
2. **🔍 Search existing issues**: Kannski er þetta þegar búið að ræða
3. **💬 Ask in discussions**: GitHub Discussions fyrir general questions
4. **📧 Email fyrir private matters**: magnuss@unak.is
5. **🚨 Emergency technical issues**: UNAK IT helpdesk

**Response times:**
- 🟢 **Issues og PR**: 1-3 dagar
- 🟡 **Email**: 3-7 dagar
- 🔴 **Emergency**: Same day

## 🎓 Fyrir nemendur

### 📚 Learning Opportunities

**Hvað getur þú lært:**
- 🐍 **Python development** (BORG project)
- ⚛️ **React/Node.js** (Arctic Tracker)
- 📝 **Technical writing** (documentation)
- 🤖 **AI/ML implementation** (multiple projects)
- 📊 **Data visualization** (analytics, reporting)
- 🔄 **DevOps practices** (GitHub Actions, deployment)

**Student Project Ideas:**
- 📱 **Mobile app** fyrir Arctic Tracker
- 🎨 **UI/UX improvements** fyrir BORG
- 📊 **Analytics dashboard** fyrir podcast metrics
- 🔍 **Search functionality** fyrir documentation
- 🌐 **Website** fyrir project showcasing

### 🏆 Academic Credit

**Tækifæri fyrir academic credit:**
- **Final projects** í AI/CS courses
- **Research assistantships** með faculty
- **Independent study** projects
- **Thesis work** related to AI ethics/implementation
- **Internship opportunities** með UNAK IT

**Requirements:**
- Samráð við academic advisor
- Clear project scope og deliverables
- Regular progress meetings
- Final presentation/demo
- Contribution til open source project

## 🌟 Recognition

### 🎖️ Contributor Recognition

**Við viðurkennum framlög með:**
- 📋 **Contributors file** í repository
- 🏷️ **GitHub badges** fyrir significant contributions
- 📰 **University newsletter** features
- 📺 **Podcast mentions** fyrir major contributions
- 🎤 **Conference presentations** opportunities
- 💼 **Reference letters** fyrir job applications

**Contribution types we value:**
- 💻 Code contributions (any size!)
- 📝 Documentation improvements
- 🐛 Bug reports og testing
- 🎨 Design og UX improvements
- 🌐 Translation work
- 📢 Community building og outreach
- 🎓 Educational content creation

### 🚀 Career Benefits

**Contributing to UNAK AI projects can help with:**
- 💼 **Job applications** - real-world project experience
- 🎓 **Graduate school** - research experience
- 🌐 **Professional network** - connections með AI community
- 📊 **Portfolio building** - demonstrable skills
- 🏆 **Awards og recognition** - academic og professional

## 📊 Success Metrics

**Hvernig við mælum árangur:**
- 📈 **Active contributors** per month
- 🔄 **PR frequency** og merge rate  
- 📚 **Documentation completeness** score
- 🐛 **Issue resolution time** 
- 🌟 **Community satisfaction** surveys
- 🎯 **Project milestone** completion
- 📢 **External adoption** af our tools/methods

## 🔮 Future Roadmap

### 🎯 Short-term goals (Q2-Q3 2025)
- [ ] Establish regular contributor community
- [ ] Create video tutorial series
- [ ] Implement automated testing pipeline
- [ ] Launch student mentorship program
- [ ] Develop contributor onboarding process

### 🚀 Long-term vision (2025-2027)
- [ ] Nordic AI collaboration network
- [ ] International conference hosting
- [ ] Commercial partnerships
- [ ] Alumni contributor network
- [ ] Open source AI curriculum

---

## 📞 Tengiliðir

**Project Lead**: Magnús Smári
- 📧 Email: magnuss@unak.is
- 🐦 Twitter: [@magnussmari](https://twitter.com/magnussmari)
- 💼 LinkedIn: [magnussmari](https://linkedin.com/in/magnussmari)

**Technical Support**: UNAK IT Department
- 📧 Email: it@unak.is
- 📞 Phone: +354 460 8000

**Academic Affairs**: 
- 📧 Email: academic@unak.is

**Media og PR**:
- 📧 Email: media@unak.is

---

## 📚 Frekari lesning

- 🌐 [UNAK AI Strategy](https://www.unak.is/ai-strategy)
- 📖 [AI Ethics Guidelines](./verkefni/ai-stefna/)
- 🎙️ [Temjum Tæknina Podcast](https://anchor.fm/temjum-taeknina)
- 🔬 [Research Publications](https://research.unak.is/)
- 📊 [Project Analytics](https://analytics.unak.is/ai-projects)

---

<div align="center">
  <strong>🤝 Takk fyrir að leggja þitt af mörkum!</strong>
  <br>
  <em>Saman byggjum við betri framtíð með gervigreind</em>
  <br><br>
  <a href="https://github.com/magnussmari/gervigreind-unak/issues/new">🚀 Start Contributing</a> •
  <a href="https://github.com/magnussmari/gervigreind-unak/discussions">💬 Join Discussion</a> •
  <a href="mailto:magnuss@unak.is">📧 Get Support</a>
</div>
