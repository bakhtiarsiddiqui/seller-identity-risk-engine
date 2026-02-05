# Seller Identity Risk Engine

## Overview
Seller Identity Risk Engine is a risk assistance tool designed to support trust and safety investigators by identifying potential identity reuse across multiple seller accounts using biometric similarity signals.

The system does NOT make automated enforcement decisions. It surfaces risk indicators to reduce investigator cognitive load and investigation time.

## Key Features (v1.0)
- Facial embedding-based identity similarity detection
- Vector search across historical seller embeddings
- Rule-based risk flagging (≥3 matched seller IDs)
- Investigator-facing risk alerts
- Secure and privacy-aware biometric handling

## Tech Stack
- Backend: Python, FastAPI
- ML: PyTorch, ArcFace
- Vector Search: FAISS
- Database: PostgreSQL
- Frontend: React
- Hosting: AWS (Prototype)

## Ethical & Compliance Design
- No automated seller blocking
- No long-term raw image storage
- Human-in-the-loop decision making
- Full audit logging

## Repository Structure
See `/docs/system_architecture.md` for detailed design.
