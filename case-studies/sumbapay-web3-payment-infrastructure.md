# SumbuPay Web3 Payment Infrastructure

## Overview

Backend foundations for a Web3 payment platform focused on payments, QRIS integration, and wallet workflows.

The work centered on making the backend dependable enough for product readiness while keeping the system flexible for future growth.

## Repository

- Private project; details sanitized for public sharing

## Backend Keywords

Node.js, NestJS, PostgreSQL, Prisma, QRIS integration, MPC wallet workflows, S3-compatible storage, payment infrastructure, backend architecture, product readiness

## My Role

- Backend Engineer (Part-time, Co-Founder)
- Responsible for backend design, integration layers, and product-readiness support
- Helped shape the technical foundation for the initiative

## Problem

The platform needed a reliable backend foundation for payment workflows while remaining flexible enough to support Web3-specific infrastructure and operational growth.

### Sub-Problem: payment workflow reliability

- Problem: payment-adjacent workflows needed to stay predictable and maintainable.
- Solution: separated service logic from persistence and external integration points.
- Stack: Node.js/NestJS, PostgreSQL, Prisma.
- Result: clearer backend boundaries for payment flows.

### Sub-Problem: QRIS and wallet integration

- Problem: the product required QRIS integration and MPC wallet workflows.
- Solution: structured integrations behind backend service boundaries.
- Stack: QRIS, MPC wallet workflows, backend services.
- Result: product-ready integration layer for future scaling.

## Stack

- Node.js / NestJS
- PostgreSQL
- Prisma
- QRIS integration
- MPC wallet workflows
- AWS / S3-compatible storage

## Architecture / Flow

- Backend service layer for payment and platform workflows
- Database layer for transactional records and operational state
- Integration points for QRIS and wallet operations
- Storage layer for assets and supporting artifacts

## Impact

- Supported product readiness for SumbuPay
- Helped the initiative receive **IDR 50,000,000** in FT UGM startup support funding

## Solution

- Built service boundaries around payment and platform workflows
- Used Prisma + PostgreSQL for transactional persistence
- Kept storage and integration concerns isolated from core business logic

## Evidence

### Demo / Video

- Demo GIF: _add link or embed_
- YouTube / Loom: _add link or embed_

### Architecture

- Architecture diagram: _add link or embed_
- Flow diagram: _add link or embed_

### Data Model

- ERD: _add link or embed_

### Code / Pattern

- Code snippet: _add link or embed_
- Architecture pattern: backend service boundaries for payment workflows

### Metrics

- IDR 50,000,000 startup support funding
- Product readiness achieved for the initiative

## Challenges

- Designing backend flows for payment-adjacent operations
- Keeping the system modular enough for future product expansion
- Coordinating integration work with product constraints

## What I Learned

- Payments infrastructure benefits from simple, explicit backend boundaries
- Product-readiness is often a backend problem as much as a product one
- Co-founding work demands both technical execution and delivery discipline
