# Trek

This repository serves as a consolidated archive of a discontinued business application suite composed of multiple modular repositories. The project was initially intended as a full-stack, cross-platform, serverless application built with Node.js, React, React Native, and MongoDB. While initial groundwork was laid across several submodules, development was halted before completion.

## ⚠️ Project Status: Archived

This project is no longer under development. It has been preserved here for reference only.

---

## Overview

This suite of repositories was part of a personal effort to rebuild a business application I had previously contributed to in a professional setting. The goal was to apply microservice principles, serverless architecture, and a modular repository structure to create a scalable product ecosystem.

However, I eventually concluded that continuing development could pose intellectual property concerns. Although the original idea never went to market, and my implementation was based on memory, I ultimately chose to archive the project out of caution and respect for potential intellectual property boundaries.

---

## Project Structure

| Repository   | Description |
|--------------|-------------|
| [`trek-API`](https://github.com/Chain52/trek-API) | API gateway for handling external requests |
| [`trek-API-common`](https://github.com/Chain52/trek-API-common) | Shared logic consumed by the API |
| [`trek-community`](https://github.com/Chain52/trek-community) | Placeholder for web dashboard (no implementation) |
| [`trek-passenger`](https://github.com/Chain52/trek-passenger) | React Native app starter (no implementation) |
| [`trek-utils`](https://github.com/Chain52/trek-utils) | Core logic for MongoDB integration and query execution |

Each sub-repository is added via Git submodules. For detailed information, code structure, and purpose, please take a look at their README documentation.

---

## Technologies

- **Node.js**: API layer and shared utilities
- **MongoDB** with **Mongoose**: data modeling
- **React Native** via **Expo**: mobile client
- **Modular monorepo**: structure with Git submodules
- **Serverless** architecture with **AWS Lambda**: intended for API deployment

---

## Lessons & Takeaways

While the suite never reached production, it was a valuable personal exercise in:

- Designing modular monorepos using submodules
- Building MongoDB schema factories and query abstractions
- Architecting for the separation of concerns across client/API layers
- Understanding the importance of IP ethics in side projects

---

## Final Note

This codebase is not intended for reuse or extension and has been made public for historical and educational reference only.
