# FoodRoute - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_6a15b5c18a7dfe45e60a4a86_user:tCp29%2A5f6epdyh%26yNo5y%5EJaHIhZbfe9r@ep-winter-sea-ajdu54f7.c-3.us-east-2.aws.neon.tech:5432/AppDB_6a15b5c18a7dfe45e60a4a86?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
