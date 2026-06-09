# AI Appointment Booking Agent

An AI-powered appointment scheduling assistant built using **n8n**, **Groq LLM**, and **Google Calendar API**.

The workflow understands natural language appointment requests, extracts meeting details using AI, and automatically creates events in Google Calendar.

---

## Features

✅ Natural language appointment booking

✅ AI-based extraction of meeting details

✅ Structured JSON output using Output Parser

✅ Automatic Google Calendar event creation

✅ Dynamic meeting title generation

✅ Calendar reminders

✅ End-to-end workflow automation

---

## Tech Stack

- n8n
- Groq API
- Llama 3
- Google Calendar API
- Structured Output Parser
- JSON Schema

---

## Workflow

```text
User Message
      ↓
AI Agent
      ↓
Groq LLM
      ↓
Structured Output Parser
      ↓
Google Calendar
      ↓
Event Created
```

---

## Example Input

```text
Book a meeting with Rahul tomorrow at 3 PM
```

## AI Output

```json
{
  "title": "Meeting with Rahul",
  "date": "tomorrow",
  "time": "3 PM",
  "attendee": "Rahul",
  "duration": 1
}
```

## Calendar Event

```text
Meeting with Rahul
Date: Tomorrow
Time: 3 PM
Duration: 1 Hour
```

---

## Project Architecture

### 1. Chat Trigger

Receives appointment requests from users.

### 2. AI Agent

Processes the user message and extracts appointment details.

### 3. Groq Chat Model

Uses an LLM to understand natural language requests.

### 4. Structured Output Parser

Converts AI responses into a predefined JSON structure.

### 5. Google Calendar

Automatically creates calendar events using extracted information.

---

## JSON Schema

```json
{
  "title": "string",
  "date": "string",
  "time": "string",
  "attendee": "string",
  "duration": "number"
}
```

---

## Skills Demonstrated

- AI Automation
- Workflow Automation
- Prompt Engineering
- LLM Integration
- API Integration
- JSON Processing
- Google Calendar Automation
- n8n Development

---

## Business Use Cases

- Personal Scheduling Assistant
- Interview Scheduling
- Client Meeting Booking
- Sales Call Scheduling
- Team Meeting Automation
- Appointment Management

---

## Future Enhancements

- WhatsApp Integration
- Email Notifications
- Meeting Rescheduling
- Multi-Attendee Support
- Conflict Detection
- Time Zone Handling
- Voice-Based Booking

---

## Author

**Wajeeha T**

- LinkedIn: linkedin.com/in/twajeeha
- GitHub: github.com/wajeehasheikh749
