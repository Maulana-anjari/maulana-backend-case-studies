# Technocorner Registration Platform

## Overview

Backend system for a national competition registration platform supporting multiple competition tracks.

The goal was to deliver a stable registration backend quickly and keep event operations manageable.

## Repository

- Private project; details sanitized for public sharing

## Backend Keywords

Node.js, REST APIs, authentication, authorization, Google Drive integration, Google Sheets integration, deployment support, registration workflows, backend delivery

## My Role

- Backend Developer
- Built the REST API and integration logic from scratch

## Problem

The platform needed dependable backend support for registration, authentication, team workflows, admin operations, and external document handling under event deadlines.

### Sub-Problem: registration and team workflow handling

- Problem: registration logic had to support multiple competition tracks.
- Solution: built a REST API with track-aware backend logic.
- Stack: Node.js, REST APIs, backend workflow logic.
- Result: stable registration handling for 5 competition tracks.

### Sub-Problem: document and reporting integration

- Problem: the team needed document handling and reporting without manual overhead.
- Solution: integrated Google Drive and Google Sheets into backend workflows.
- Stack: Google Drive, Google Sheets, backend integration layer.
- Result: smoother event operations and admin support.

## Stack

- Node.js
- REST APIs
- Authentication / authorization
- Google Drive integration
- Google Sheets integration
- Deployment and integration support

## Architecture / Flow

- REST API for registration and admin actions
- Auth layer for protected workflows
- Integration layer for Google Drive and Sheets
- Backend logic for competition-track specific flows

## Impact

- Built the backend REST API from scratch for a national competition platform
- Supported **5 competition tracks**

## Solution

- Implemented backend endpoints for registration and admin actions
- Added auth and integration layers for protected workflows
- Supported track-specific logic without collapsing the system into one brittle flow

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
- Architecture pattern: registration API with track-aware workflows

### Metrics

- Backend API from scratch
- Supported 5 competition tracks

## Challenges

- Handling multiple event workflows in one backend system
- Keeping registration logic consistent across different competition tracks
- Resolving integration issues quickly during delivery

## What I Learned

- Event platforms need fast, dependable backend iteration
- Admin workflows deserve the same design rigor as public flows
- Integrations can become the critical path during launch windows
