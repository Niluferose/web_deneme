# MeetUp Buddy — Project Plan

> *Team Size:* 3 students  
> *Duration:* 2 weeks  
> *Goal:* Create a Django-based event planning platform where users can create and join events based on their interests.
> *Status:* In Progress �� 

---
## 1 · Scope at a Glance
| We *will* build | We will *not* build |
|---|---|
| User authentication & profiles ✅ | REST APIs, separate JS front‑end |
| Event model with CRUD operations ✅ | Docker, CI/CD pipelines |
| Interest-based event filtering ✅ | Complex payment systems |
| Bootstrap 5 via CDN for styling ✅ | Kubernetes, container orchestration |
| Manual deployment guide ✅ | GitHub Actions automation |

---
## 2 · Roles & Responsibilities
| Member | Focus | Description | Status |
|---|---|---|---|
| Frontend Developer | Front‑end | HTML templates, Bootstrap, UX | In Progress 🔄 |
| Backend Developer | Back‑end | Models, views, authentication | In Progress 🔄 |
| Full Stack Developer | QA & Docs | Testing, deployment, documentation | In Progress 🔄 |

Each member owns 12 GitHub Issues and touches multiple files.

---
## 3 · Timeline (2 Weeks)
| Week | Milestone | Status |
|---|---|---|
| 1 | Project setup + User auth + Event model & CRUD | In Progress 🔄 |
| 2 | Interest system, event filtering, tests & docs | Not Started ❌ |

---
## 4 · Work‑Breakdown Structure (WBS)
### 4.1 Frontend Developer (12 Tasks)
| ID | Issue Title | Key Files | Status |
|---|---|---|---|
| F‑01 | Design base template | templates/base/base.html | Completed ✅ |
| F‑02 | Implement Home page | templates/events/home.html | Completed ✅ |
| F‑03 | User registration page | templates/users/register.html | Completed ✅ |
| F‑04 | User login page | templates/users/login.html | Completed ✅ |
| F‑05 | User profile page | templates/users/profile.html | Completed ✅ |
| F‑06 | Event list template | templates/events/event_list.html | Completed ✅ |
| F‑07 | Event detail template | templates/events/event_detail.html | Completed ✅ |
| F‑08 | Event creation form | templates/events/event_form.html | Completed ✅ |
| F‑09 | Responsive design | static/css/style.css | Completed ✅ |
| F‑10 | Form validations | static/js/main.js | Completed ✅ |
| F‑11 | UI animations | static/js/animations.js | Completed ✅ |
| F‑12 | Error pages | templates/errors/* | Completed ✅ |

### 4.2 Backend Developer (12 Tasks)
| ID | Issue Title | Key Files | Status |
|---|---|---|---|
| B‑01 | User model & auth | users/models.py | Completed ✅ |
| B‑02 | Event model | events/models.py | Completed ✅ |
| B‑03 | User profile management | users/views.py | Completed ✅ |
| B‑04 | Event CRUD operations | events/views.py | Completed ✅ |
| B‑05 | Event filtering | events/views.py | Completed ✅ |
| B‑06 | Location-based filtering | events/views.py | Completed ✅ |
| B‑07 | Notification system | users/views.py | Completed ✅ |
| B‑08 | User interactions | events/views.py | Completed ✅ |
| B‑09 | API endpoints | users/urls.py, events/urls.py | Completed ✅ |
| B‑10 | Security measures | meetup_buddy/settings.py | Completed ✅ |
| B‑11 | Database optimization | users/models.py, events/models.py | Completed ✅ |
| B‑12 | Cache system | meetup_buddy/settings.py | Completed ✅ |

### 4.3 Full Stack Developer (12 Tasks)
| ID | Issue Title | Key Files | Status |
|---|---|---|---|
| C‑01 | Project configuration | requirements.txt, manage.py | Completed ✅ |
| C‑02 | Database schema | meetup_buddy/settings.py | Completed ✅ |
| C‑03 | Deployment setup | Dockerfile, docker-compose.yml | Completed ✅ |
| C‑04 | Test scenarios | tests/ | Completed ✅ |
| C‑05 | Docker configuration | Dockerfile, docker-compose.yml | Completed ✅ |
| C‑06 | Performance optimization | meetup_buddy/settings.py | Completed ✅ |
| C‑07 | SEO optimization | templates/base/base.html | Completed ✅ |
| C‑08 | Error handling | meetup_buddy/settings.py | Completed ✅ |
| C‑09 | UX improvements | static/js/main.js | Completed ✅ |
| C‑10 | Project documentation | README.md, docs/ | Completed ✅ |
| C‑11 | Security tests | tests/ | Completed ✅ |
| C‑12 | Monitoring setup | scripts/ | Completed ✅ |

---
## 5 · Folder Overview

meetup_buddy/
  ├── users/
  ├── events/
  ├── templates/
  │   ├── base/
  │   ├── users/
  │   └── events/
  ├── static/
  │   ├── css/
  │   └── js/
  ├── tests/
  ├── scripts/
  ├── docs/
  └── README.md

---
## 6 · Risks & Mitigations
| Risk | Mitigation | Status |
|---|---|---|
| Time management | Weekly check‑ins + clear milestones | Addressed ✅ |
| Code conflicts | Small PRs + code review | Addressed ✅ |
| Security issues | Early security testing + validation | Addressed ✅ |

---
## 7 · Issue Template
```markdown
### Description
<!-- What & why -->

### Acceptance Criteria
- [ ] Implemented
- [ ] Tests pass locally
- [ ] PR approved
```

---
### Project Completion
Project is currently in progress. All team members are actively working on their assigned tasks. Frontend and backend implementations are well underway, with full stack tasks following closely behind.

Next steps:
1. Complete remaining frontend tasks
2. Finish backend implementations
3. Implement full stack features
4. Conduct thorough testing
5. Prepare deployment documentation

Project Status: In Progress 🔄
