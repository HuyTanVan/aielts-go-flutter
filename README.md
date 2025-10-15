# AIELTS
[English](./README.md) | [Tiếng Việt](./README.vi.md)  
**AIELTS** is an AI-powered mobile app designed to help Vietnamese students prepare for the IELTS exam by providing real practice questions and AI-powered feedback and scoring based on official IELTS criteria.  

## Overview
AIELTS is designed to support Vietnamese learners preparing for the IELTS test. The app provides:
- Daily speaking/writing practice questions sourced from real IELTS tests and student reviews.
- AI-powered speaking test simulations, where an AI acts as the examiner.
- Detailed feedback and scoring based on official IELTS Speaking criteria.
Future Plans:
- In-place/in-line translations.
- Word- and sentence-level insights using external dictionaries (e.g., [Cambridge Dictionary](https://dictionary.cambridge.org/)).
 --- 
## Technical Stacks
- Backend building blocks
  - [kyleconroy/sqlc](https://github.com/kyleconroy/sqlc)
    - [pq](github.com/lib/pq)
  - [golang-migrate/migrate/v4](https://github.com/golang-migrate/migrate)
  - Utils
    - [google/wire](github.com/google/wire)
    - [ilyakaznacheev/cleanenv](https://github.com/ilyakaznacheev/cleanenv)
    - golang.org/x/exp/slog
      - [sirupsen/logrus](https://github.com/sirupsen/logrus)
    - [samber/lo](https://github.com/samber/lo)
    - [automaxprocs/maxprocs](go.uber.org/automaxprocs/maxprocs)
    - [stretchr/testify](github.com/stretchr/testify)
    - golang/glog
    - google/uuid
- Infrastructure
  - Postgres, Redis
  - Google Cloud Run, R2 Cloudflare
  - docker and docker-compose
- AI Integration
  - [OpenAI Whisper 1 (speech-to-text)](https://platform.openai.com/docs/models/whisper-1)
  - OpenAI GPT-4o mini (language model)
- Security / Auth
  - JWT (JSON Web Tokens)
  - OAuth2
---
## App Interface / Demo
- [Figma](https://www.figma.com/proto/vPHyKs5zoKH0oUOJU4g5m6/Untitled?node-id=8-6&p=f&t=5Kwt2wjg0Qjcz6rK-1&scaling=scale-down&content-scaling=fixed&page-id=1%3A30&starting-point-node-id=8%3A24)
  
