# 🏢 UNAK AI Initiative - Unified Repository

## 📁 Repository Structure

### 🎯 Core Organization
```
gervigreind-unak/
├── 📄 README.md              # Main repository overview
├── 📄 FRAMLAG.md             # Contributing guidelines
├── 📄 LICENSE                # MIT License
├── 📁 .github/               # GitHub workflows & templates
├── 📁 verkefni/              # Public project documentation (GitHub)
├── 📁 skjol/                 # Shared documents & templates
├── 📁 files/                 # Private project files & documents
├── 📁 admin/                 # Administrative documents
└── 📁 projects/              # Project workspaces (optional)
```

### 📂 Files Organization (Private/Local)
Located in `./files/` - not synced to GitHub:
- **01-BORG-kerfi/** - BORG system development files
- **02-Leidbeinandi-stefna/** - AI Policy development files
- **03-Scite-Integration/** - Scite.ai integration files  
- **04-Arctic-Tracker/** - Arctic tracker project files
- **05-Temjum-Taeknina/** - Podcast production files
- **06-Starfsmannakoennun/** - Survey design & data files

### 🗂️ Administrative Files
Located in `./admin/` - private administration:
- **fundir/** - Meeting minutes, agendas, action items
- **reports/** - Monthly reports, analytics, dashboards  
- **templates/** - Document templates, forms, guidelines

### 🌐 Public Documentation
Located in `./verkefni/` - synced to GitHub:
- Technical documentation
- Project overviews
- Public-facing information
- Contributing guidelines

## 🔗 Integration Points

### **📝 Notion Workspace** 
- **Project Database**: https://www.notion.so/214e5534e633810a9468cd79c56645ac
- **UNAK Hub**: https://www.notion.so/UNAK-AI-Initiative-Project-Management-Hub-214e5534e6338101b9e9ed53439aa29b
- **Meeting Database**: Fundarbók for structured meeting tracking

### **🌐 GitHub Repository**
- **Public URL**: https://github.com/Magnussmari/gervigreind-unak
- **Issues**: Project bugs and feature requests
- **Projects**: Kanban boards for development
- **Wiki**: Extended documentation

### **🏠 Local Files**
- **Path**: `/Users/magnussmari/Documents/gervigreind-unak/`
- **Git Status**: This is the working repository
- **Private Files**: Everything in `files/` and `admin/`

## 🔐 File Management Strategy

### **Public (GitHub)** 📢
- Project overviews and documentation
- Technical guides and tutorials
- Contributing guidelines
- Code samples and templates

### **Private (Local Only)** 🔒
- Budget and financial documents
- Meeting minutes and internal notes
- Sensitive stakeholder communications
- Raw survey data and analysis
- Draft documents and work-in-progress

### **Shared (Notion)** 👥
- Project status and progress tracking
- Team assignments and responsibilities
- Meeting scheduling and action items
- Cross-project resource allocation

## 🚀 Getting Started

### First Time Setup
```bash
cd /Users/magnussmari/Documents/gervigreind-unak
git status                    # Check current state
git pull origin main         # Get latest updates
```

### Working with Projects
```bash
# For public documentation
cd verkefni/[project-name]/
# Edit and commit to GitHub

# For private files
cd files/[project-folder]/
# Work locally, not synced to GitHub

# For admin tasks
cd admin/[area]/
# Local administration, private
```

### Adding New Content
- **Public docs** → `verkefni/` folder → commit to GitHub
- **Private files** → `files/` folder → local only (add to .gitignore)
- **Admin docs** → `admin/` folder → local only

## 📊 Quick Stats
- **Total Projects**: 6 active
- **Total Budget**: ~5.6M ISK  
- **Team Members**: 15+ across all projects
- **Timeline**: 2024-2025
- **Repository Size**: ~50MB (excluding private files)

---

*Unified repository structure created: 16. júní 2025*  
*All UNAK AI Initiative projects now in single location*
