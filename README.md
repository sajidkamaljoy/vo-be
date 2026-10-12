# vo-be

An early snapshot of the NestJS backend for **Voktar Odhikar** (Bengali for "consumer rights"), a platform for food distributors, industries and admins.

## Current state

This repo holds the project scaffold and configuration only: `package.json`, the NestJS and TypeScript config, an e2e test stub, and sample files uploaded while testing (`upload/`, `uploads/`). The `src/` folder is empty.

**The complete backend and frontend are in the repo [`voktar-odhikar-test`](https://github.com/sajidkamaljoy/voktar-odhikar-test)** (`3npbackend/` and `3npfrontend/`). Use that repo instead.

## Tech stack (from the dependencies)

NestJS 10, TypeScript, TypeORM with PostgreSQL (`pg`), `bcrypt` for password hashing, `class-validator` and `class-transformer`, and Multer typings for file uploads.
