# MISP Platform 

[![Build Status](https://github.com/kc-node/repotest/actions/workflows/ci.yml/badge.svg)](https://github.com/kc-node/my-project/actions)
[![Coverage](https://img.shields.io/codecov/c/github/kc-node/repotest?style=flat-square)](https://codecov.io/gh/kc-node/repotest)
![Java 17](https://img.shields.io/badge/JDK-17-red?logo=java)
![Node](https://img.shields.io/badge/Node-18-green?style=flat-square&logo=node.js)
![Angular 17](https://img.shields.io/badge/Angular-17-dd0031?logo=angular)
![License](https://img.shields.io/github/license/kc-node/repotest?style=flat-square)
![Issues](https://img.shields.io/github/issues/kc-node/repotest?style=flat-square)

A comprehensive Municipal Integrated Service Portal (MISP) designed for resident service reporting, featuring a Spring Boot backend and an Angular frontend managed in a high-performance monorepo.

## Project Structure
- **apps/backend**: Spring Boot application (Java 17, Maven).
- **apps/frontend**: Angular application (Node 18, Yarn).
- **infrastructure**: Terraform and Docker configuration files.

## Getting Started
1. **CI/CD**: Every Pull Request triggers a GitHub Action to verify Maven and Yarn builds.
2. **Local Setup**: 
   - Backend: `mvn -f apps/backend/pom.xml clean install`
   - Frontend: `cd apps/frontend && yarn install`