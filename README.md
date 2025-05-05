A **step‑by‑step Java Swing + MySQL project** that connects the fundamentals we’ve covered on our "LankaDroid Programming Kuppiya" YouTube channel (Java basics, OOP, ER diagrams, relational schema, MySQL, and GUI design) into a *working* student‑enrollment system.

---

## 📸 GUI Preview

| Login Dialog | Main Window | Student Management | Subject Management | Enrollment Management |
|--------------|-------------|--------------------|--------------------|-----------------------|
| ![Login](docs/screenshots/login.png) | ![Home](docs/screenshots/home.png) | ![Student Management](docs/screenshots/student-management.png) | ![Subject Management](docs/screenshots/subject-management.png) | ![Enrollment Management](docs/screenshots/enrollment-management.png) |

---


## Learning Goals

* Design a small‑scale CRUD application from scratch  
* Wire a Swing front‑end to a MySQL back‑end  
* Apply clean OOP principles and basic design patterns  
* Use Git branches to follow progressive checkpoints

---

## Roadmap / Episode Playlist  🚧

| # | Video & Focus | Core Concepts | What we build live | Homework branch |
|---|---------------|--------------|--------------------|-----------------|
| 0 | **Teaser (90 sec)** | Why the project matters • feature tour | Quick demo of finished app | — |
| 1 | Requirements & Use‑Cases | Functional vs. non‑functional | White‑board 5 use‑cases | `TBU` |
| 2 | Domain & ER Diagram | Entities • relationships | Draw ER (Student‑Course‑Enrollment) | `TBU` |
| 3 | Relational Schema | PK/FK • 3 NF recap | Convert ER → tables | `TBU` |
| 4 | MySQL Setup | Workbench • seed data | Create schema, insert sample rows | `TBU` |
| 5 | Java Kick‑off (NetBeans) |  • JDBC | Bootstrapped project skeleton | `TBU` |
| 6 | Student DAO & CRUD | DAO pattern | Implement `StudentDao` | `TBU` |
| 7 | Course & Enrollment DAO | Join queries | Batch enroll/unenroll | `TBU` |
| 8 | Service Layer & Validation | Business rules • exceptions | `EnrollmentService` | `TBU` |
| 9 | Swing UI Sketches | MVC in desktop apps | Layout screens in NetBeans | `TBU` |
|10 | Student Maintenance UI | Event handling refresher | Table + dialog | `TBU` |
|11 | Course Maintenance UI | Reuse vs. copy‑paste | Mirror of Student UI | `TBU` |
|12 | Enrollment Screen | Combos • live search | Multi‑step dialog | `TBU` |
|13 | Error Handling & Logging | SLF4J • global dialog | Rolling log file | `TBU` |
|14 | Packaging & Distribution | Shade plugin • exe wrapper | Runnable JAR + Windows exe | `TBU` |
|15 | **Wrap‑up & Next Steps** | Recap • refactor ideas | Showcase & GitHub tour | `TBU` |

> 📝 **Tip:** Each branch starts from the previous episode’s tag so you can follow along or jump in anywhere.

---

## 📁 Git Branch Strategy

This project uses a **branch-per-video** approach to clearly illustrate each stage of development:

* `main`: Contains the complete and finalized system.
* `video-xx-feature-name`: Represents the state of the project at the end of each corresponding video.

**Example:**

* `video-01-gui-skeleton`
* `video-02-database-schema`
* `video-03-student-crud`

### How to use branches:

Clone and checkout a specific video branch:

```bash
git clone https://github.com/nuwanAsiri/student-enroll-system.git
cd student-enroll-system
git checkout video-01-gui-skeleton
```

You can then explore and compare changes between branches directly on GitHub.

---

## 🛠 GitHub Collaboration

### Issues

Use [GitHub Issues](https://github.com/nuwanAsiri/student-enroll-system/issues) to:

* Ask questions or clarify doubts related to specific videos or concepts
* Report bugs and request enhancements
* Discuss and collaborate openly with peers

### Pull Requests (PRs)

Submit your improvements via [Pull Requests](https://github.com/nuwanAsiri/student-enroll-system/pulls):

* Fork the repository
* Create your feature branch (`git checkout -b feature/my-idea`)
* Commit your changes
* Push your branch and open a PR for review

### Discussions

Use [GitHub Discussions](https://github.com/nuwanAsiri/student-enroll-system/discussions) to:

* Engage in broader topic discussions and Q\&A sessions
* Share insights, challenges, and best practices with the community
* Get feedback on ideas or conceptual understanding

---


## Tech Stack

* Java 17  (works with 11+)  
* Swing (NetBeans GUI Builder)  
* MySQL 8  
* JUnit 5 (unit tests, later stage)

---

**Prerequisites**
* JDK 17+
* MySQL 8+
* NetBeans 17 or IntelliJ/Eclipse if you prefer

## Getting Started

```bash
# clone the repo
git clone https://github.com/nuwanAsiri/student-enroll-system.git
cd student-enroll-system

# import into NetBeans (File ▸ Open Project)
# create a local MySQL schema called 'lankadroid_student_enroll' TBU
# hit Run (F6) – the main screen should load
```
## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: git checkout -b feature/my-idea
3. Commit your changes
4. Push and open a Pull Request

## 📜 License
MIT – do anything, just give credit.
