# Maryyam Tanveer

Computer Science student at PUCIT focused on backend and full-stack development. Building production systems with real authentication, deployment, and CMS integrations, alongside applied AI/ML projects using retrieval and computer-vision pipelines.

📫 tanvirmeryem2@gmail.com · [LinkedIn](https://linkedin.com/in/maryyam-tanveer) · [GitHub](https://github.com/meryem-cmd)

---

## Projects

### [rate-limiter](https://github.com/meryem-cmd/rate-limiter)
| | |
|---|---|
| **Stack** | Django · Redis (atomic Lua scripts) · Gunicorn · Prometheus/Grafana · k6 |
| **Key detail** | Built two versions of the core rate-check deliberately — naive vs. atomic — to prove a race condition mattered under concurrent load, not just claim it did |
| **Impact** | Naive version allowed 2x its configured limit under load; atomic Lua-script fix closed the race entirely and cut average response time ~10–25x (1.07s–4.47s → 164ms) |

### [url-security-scanner](https://github.com/meryem-cmd/url-security-scanner)
| | |
|---|---|
| **Stack** | Node.js · Express 5 · Python (subprocess) · MongoDB (scaffolded) |
| **Key detail** | Full-stack SQL injection scanner — submits a URL, runs a Python payload scanner as a child process, and classifies findings into Most Critical / Moderate / Least Critical severity tiers |
| **Impact** | Generates a self-contained, downloadable HTML report for offline review; built as an Information Security coursework project with a disclosed security notice on authorised use |

### [AI FitStyler](https://github.com/meryem-cmd/fitstyler)
| | |
|---|---|
| **Stack** | Python · Scikit-learn · FAISS · MediaPipe · OpenCV |
| **Key detail** | Multi-agent outfit recommendation system using body-shape and skin-tone detection via MediaPipe, with an embedding-based RAG pipeline (FAISS + HuggingFace) for context-aware search |
| **Impact** | Interactive Streamlit UI with AI-generated, single-guided recommendation flow |

### [Enchanted Trinkets](https://github.com/meryem-cmd/enchanted_trinkets)
| | |
|---|---|
| **Stack** | Node.js · Express.js · MongoDB · Cloudinary · JavaScript |
| **Key detail** | Full-stack e-commerce platform with role-based dashboards (Manager / Employee / Customer) and access-controlled REST APIs |
| **Impact** | Replaced one-by-one manual product entry with a batch-upload workflow; Cloudinary-based image hosting |

### [Django Blog App](https://github.com/meryem-cmd/django-blog-app)
| | |
|---|---|
| **Stack** | Python · Django · Wagtail CMS · Bootstrap 5 · SQLite |
| **Key detail** | Dual content system merging a custom Blog model with Wagtail-authored pages into one unified feed, with public/followers-only visibility |
| **Impact** | Deployed to AWS EC2 with Gunicorn (systemd service) and Whitenoise for static files |

---

## Tech Stack

**Languages:** JavaScript (ES6+), Python, Java, C++, C, Kotlin, HTML5, CSS3
**Frameworks & Libraries:** Django, React, Node.js, Express.js, Flask, Bootstrap, Tailwind CSS
**AI & Data:** LangChain, FAISS, HuggingFace, OpenCV, Scikit-learn, NumPy, Pandas, Streamlit
**Databases:** MongoDB, MySQL, SQLite
**Tools:** Git, GitHub, Postman, VS Code, Jira, Figma, Canva

---

## Currently

- Expanding into RAG systems, backend engineering, and scalable architectures
- Interested in AI applications, developer tools, cybersecurity, and user-focused products

## 📫 Connect With Me

📧 Email: [tanvirmeryem2@gmail.com](mailto:tanvirmeryem2@gmail.com)
💼 LinkedIn: linkedin.com/in/maryyam-tanvir
🌐 GitHub: github.com/meryem-cmd

---

> “Building things that are both useful and meaningful.”
