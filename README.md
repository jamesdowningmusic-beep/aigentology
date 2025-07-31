# AiGENTOLOGY - AI Real Estate Assistant

## Deployment Instructions

This is a full-stack Flask + React application for AI-powered real estate lead generation.

### Environment Variables Required

Set these in Railway:
OPENAI_API_KEY=your_openai_api_key_here
PORT=5000

### Project Structure

- `backend/` - Flask API server with SQLite database
- `backend/src/static/` - Built React frontend files
- `railway.json` - Railway deployment configuration
- `Procfile` - Process configuration

### API Endpoints

- `/api/leads` - Lead management
- `/api/chat` - AI chat functionality  
- `/api/appointments` - Appointment scheduling
- `/` - Serves React frontend

### Features

- AI-powered chat widget
- Lead capture and management
- Real estate agent CRM
- Appointment scheduling
- Analytics dashboard

Built with Flask, React, SQLite, OpenAI GPT-3.5, and Tailwind CSS.
