# Training Notes

Training data and plans managed by [train-with-gpt](https://github.com/mkuzmik/train-with-gpt) — an MCP server that connects Strava and Garmin to AI coding assistants for personalized coaching.

## What's here

- `plan.md` — Weekly training plan (gym FBW 2x/week + calisthenics + cycling)
- `goals.md` — Training goals, profile, and constraints
- `notes/` — Timestamped consultation notes from each coaching session

## How it works

1. Train-with-gpt runs as an MCP server, exposing Strava activities, Garmin sleep/HRV/RHR data
2. AI assistant (OpenCode, Claude Code, etc.) reads goals and past notes for context
3. After each session I send raw unstructured notes — the assistant analyzes, adjusts weights, and updates the plan
4. Plan is also synced to a Google Doc for easy phone access during workouts

## Setup

The plan was built iteratively through conversation:
- Started from a previous trainer's proven 2x/week FBW program as reference
- Adapted based on available equipment, schedule constraints, and session feedback
- Every change is a git commit — easy to revert if something doesn't work

## Context

Preparing for a wedding (~14 months out). Goal is lean/athletic, not bulky. Training 2x/week gym with a friend, supplemented by home calisthenics and cycling.
