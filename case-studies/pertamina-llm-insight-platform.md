# Pertamina EP WOPDM Z4 LLM Insight Platform

## 🧾 Overview

Enterprise LLM insight platform for internal analysis and operational workflows.

I worked on the backend layer that kept the system reliable, fast, and maintainable while supporting integration-heavy features.

---

## 🔗 Repository

- Private project; details sanitized for public sharing

---

## 🔑 Backend Keywords

Python, FastAPI, SQL Server, Milvus, Redis, RBAC, REST APIs, LLM integration, caching, API contracts, production backend, workflow support

---

## 🛠️ My Role

- Backend Engineer (Part-time)
- Focused on API contracts, data access, performance, RBAC, and integration-heavy features
- Worked across backend implementation, bug fixes, and workflow support

---

## ❗ Problem

The system needed reliable backend behavior, fast iteration, and structured access control. It also had to support LLM-related workflows without degrading stability or maintainability.

---

### 🧩 Sub-Problem: backend stability under workflow changes

- Problem: workflow requirements changed frequently and needed consistent API behavior.
- Solution: kept API contracts explicit and supported backend changes with a clear data access layer.
- Stack: FastAPI, SQL Server, Redis, RBAC.
- Result: faster issue-to-merge cycles and more reliable delivery.

### 📊 Metric callouts

<p align="left">
  <img src="https://img.shields.io/badge/51.9%25-faster_issue--to--merge-0ea5e9?style=for-the-badge" alt="51.9% faster issue to merge" />
  <img src="https://img.shields.io/badge/RBAC-structured_access_control-111827?style=for-the-badge" alt="RBAC structured access control" />
  <img src="https://img.shields.io/badge/Milvus+Redis-retrieval_%2B_caching-10b981?style=for-the-badge" alt="Milvus Redis retrieval and caching" />
</p>

### 🧩 Sub-Problem: retrieval support for LLM workflows

- Problem: the system needed retrieval support without sacrificing backend performance.
- Solution: used Milvus plus caching to support LLM-adjacent features.
- Stack: Milvus, Redis, FastAPI.
- Result: stable integration layer for LLM workflows.

## 🧰 Stack

- Python
- FastAPI
- SQL Server
- Milvus
- Redis
- RBAC
- REST APIs

---

## Architecture / Flow

- REST API layer for backend operations
- SQL Server for structured operational data
- Milvus for search / vector retrieval behavior
- Redis for caching and response optimization
- RBAC for access control across roles and workflows

## 📈 Result / Impact

- Reduced median issue-to-merge lead time by **51.9%**
- Built and fixed backend features with a production-first delivery cadence

---

## ✅ Solution

- Designed explicit REST API contracts for backend workflows
- Separated structured data in SQL Server from retrieval support in Milvus
- Added Redis caching to reduce repeated backend work
- Enforced RBAC so access stayed aligned with roles and workflows

---

## 🖼️ Evidence

### 🎥 Demo / Video

| Asset | Placeholder |
|---|---|
| Demo GIF | _add link or embed_ |
| YouTube / Loom | _add link or embed_ |

### 🏗️ Architecture

| Asset | Placeholder |
|---|---|
| Architecture diagram | _add link or embed_ |
| Flow diagram | _add link or embed_ |

### 🗃️ Data Model

| Asset | Placeholder |
|---|---|
| ERD | _add link or embed_ |

### 💻 Code / Pattern

| Asset | Placeholder |
|---|---|
| Code snippet | _add link or embed_ |
| Architecture pattern | API-first backend with explicit RBAC and caching |

### 📊 Metrics

| Metric | Value |
|---|---|
| Issue-to-merge lead time | 51.9% faster |
| LLM workflow support | Stable integration layer |

---

## ⚠️ Challenges

- Balancing feature speed with backend correctness
- Keeping integration points stable while iterating on workflow requirements
- Maintaining consistent API contracts across changing requirements

---

## 💡 What I Learned

- Backend reliability matters as much as feature speed in enterprise systems
- Clear contracts and access control reduce delivery friction
- Caching and data modeling can materially improve team throughput
