# 🚀 AI Cost Guard API

Control your AI costs before they get out of hand.

---

## 💡 Problem

AI APIs (like GPT) charge per token.  
Most developers don’t realize how fast costs grow.

👉 Result: Unexpected bills 💸

---

## ⚡ Solution

AI Cost Guard API helps you:

- Track usage in real-time
- Calculate cost per request
- Set spending limits
- Prevent overuse

---

## 🔐 Authentication

Uses API Key system.

Add this header:

x-api-key: your_api_key

---

## 📡 API Usage

### Endpoint

POST /track

---

### Example Request

```json
{
  "user_id": "user_123",
  "input_tokens": 1000,
  "output_tokens": 500
}