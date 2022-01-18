# Write Something Nice: Vue Frontend (wsn-vue)

This is a fullstack project separated into 2 repos.
Visit the [REST API Git Repo](https://github.com/derekdkim/write-something-nice-api) for details, including a sitemap and Database ERD.

## Tech Stack

- Client: Vue.js (TypeScript), TailwindCSS
- REST API: FastAPI (Python), SQLAlchemy, Starlette + pytest (testing)
- Database: PostgreSQL
- Deployment: Linux VM (AWS EC2), NGINX, Gunicorn

## Introduction

Life is getting more stressful and isolated with the pandemic currently ongoing, and it's still very difficult and sometimes expensive to see a professional therapist. While this isn't meant to fill in that gap, it's always nice to have someone lend an ear without judgement. Write Something Nice is an app where users can reach out for help anonymously and good samaritans can write something nice to give them a hand. The goal of this app is to form just a little tiny bit more of empathy and human connection without the worry of exposing their personal information.

## Features

- OAuth authentication with JWT in cookies (stores very little personal user information to respect anonymity).
- Users can write posts to vent anonymously.
- Users can write replies to posts to write something nice for the original poster.
- The original poster can "like" a reply, giving the author of the reply reputation.
- Users can view their total reputation on their profile.

## Usage

### Locally

1. `npm install`
2. `npm run serve`

## Planned Features

- Leaderboard for reputation, sorted by month, year, all-time.
- Report troll posts and replies.
