# AIELTS
**AIELTS** is a mobile app

## Overview

### Technical Stacks
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
