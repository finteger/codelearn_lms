# CoderLMS - Official Release Repository

[![License](https://img.shields.io/badge/license-Proprietary-red.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.11+-blue.svg)](https://python.org)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)](docs/DEPLOYMENT.md)

**AI-Powered Learning Management System for Coding**

CoderLMS is a desktop application that combines curated coding challenges, a production-grade editor, automated test runners, and on-device AI coaching into a single cross-platform app.

## Features

- **Multi-Language Support** - Python, JavaScript/TypeScript, React, Dart/Flutter, Java, C/C++, Go, Rust, HTML/CSS, and more
- **AI-Powered Learning** - Local LLM integration for hints, explanations, and debugging without sending code to the cloud
- **Structured Learning Paths** - Organized modules from beginner to advanced with quizzes and assessments
- **Real-Time Testing** - Automated test runners with instant feedback and detailed results
- **Progress Tracking** - Leaderboards, certificates, and completion proofs
- **VS Code Integration** - Mirror API for live code sync with VS Code extension
- **Offline-First** - Works without internet; AI runs locally on your machine


## System Requirements

- **OS**: Windows 10+, macOS 10.15+, or Linux (Ubuntu 20.04+)
- **Python**: 3.11 or higher
- **RAM**: 4GB minimum, 8GB+ recommended for AI features
- **Storage**: 500MB for app, 2-4GB additional for AI models

## Project Structure

```
codelearn_lms/
├── src/                    # Source code
│   ├── core/              # App bootstrap and configuration
│   ├── controllers/       # Business logic controllers
│   ├── services/          # Service layer (AI, tests, etc.)
│   ├── ui/                # User interface components
│   ├── runners/           # Language test runners
│   └── database/          # SQLite database layer
├── assets/                # Icons, images, themes
├── data/                  # Challenge data and templates
├── docs/                  # Documentation
├── models/                # AI model files (GGUF)
├── sdks/                  # Bundled SDKs (Dart)
├── tests/                 # Test suites
└── licensing/             # License management
```

## License

Copyright © 2026-2027 Todd Nash. All rights reserved.

This software is proprietary. See [LICENSE](LICENSE) for details.

## Author

**Todd Nash**  
Red Deer Polytechnic  
Software Development Program

---

For support or inquiries, please refer to the [Troubleshooting Guide](docs/README.md#troubleshooting--support).
