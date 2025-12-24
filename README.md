# BU unofficial PYQ Platform

A community-driven platform for burdwan university students to access and contribute
previous year question papers (PYQs).

## Problem
PYQs are scattered across WhatsApp groups and personal drives, making them
hard to find and unreliable.

## Solution
A centralized, moderation-based platform where students can:
- Browse PYQs semester-wise
- Upload papers for review
- Community-vote to approve correctness
- Download without login

## Tech Stack
- HTML, CSS, JavaScript
- Supabase (Database, Storage, RLS)
- Netlify (Hosting)
- Google Analytics

## Key Engineering Highlights
- Community-based moderation workflow
- Secure public uploads using Row Level Security
- Dynamic content fetching without server backend
- Scales safely for concurrent downloads

## Future Improvements
- Stronger abuse prevention
- Better UI
