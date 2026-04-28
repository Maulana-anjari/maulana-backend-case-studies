# Pertamina EP WOPDM Z4 LLM Insight Platform

## Overview

Backend engineering for an enterprise LLM insight platform used to support internal analysis and operational workflows.

## My Role

- Backend Engineer (Part-time)
- Focused on API contracts, data access, performance, RBAC, and integration-heavy features

## Problem

The system needed to support a production workflow with reliable backend behavior, fast iteration, and structured access control. The work also had to accommodate LLM-related features without degrading stability or maintainability.

## Stack

- Python
- FastAPI
- SQL Server
- Milvus
- Redis
- RBAC
- REST APIs

## Architecture / Flow

- REST API layer for backend operations
- SQL Server for structured operational data
- Milvus for search / vector retrieval behavior
- Redis for caching and response optimization
- RBAC for access control across roles and workflows

## Impact

- Reduced median issue-to-merge lead time by **51.9%**
- Built and fixed backend features with a production-first delivery cadence

## Challenges

- Balancing feature speed with backend correctness
- Keeping integration points stable while iterating on workflow requirements
- Maintaining consistent API contracts across changing requirements

## What I Learned

- Backend reliability matters as much as feature speed in enterprise systems
- Clear contracts and access control reduce delivery friction
- Caching and data modeling can materially improve team throughput
