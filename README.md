# Nina

**Nina — making it simple to talk with family**

Nina is a lightweight family messaging service built around voice-first communication. It is designed to help families stay in touch through a simple, calm interface that works especially well for elderly users who may find traditional messengers too complex.

The main goal of Nina is not to compete with feature-heavy chat apps, but to make everyday communication with loved ones feel easy and natural.

## Vision

Most messaging apps are overloaded with features, menus, and interaction patterns that can be confusing for older adults. Nina focuses on the opposite approach:

- minimal interface;
- very few buttons;
- voice messages as the primary form of communication;
- text and photos as secondary but important features.

Nina should make it easy to open the app, choose a loved one or family chat, record a voice message, and send it without friction.

## Target audience

Nina is designed primarily for:

- elderly users;
- people who are not comfortable typing on a keyboard;
- families who want a simpler and more personal way to stay connected.

## Core product principles

- **Simplicity over feature count**
- **Voice-first communication**
- **Large, clear interface elements**
- **Minimal navigation and visual noise**
- **Comfortable experience for elderly users**

## Planned MVP features

The first version of Nina is expected to include:

- user registration and login;
- a simple contact or chat list;
- one-to-one and/or family chat;
- sending and receiving voice messages;
- sending and receiving text messages;
- sending and receiving photos;
- notifications for new messages;
- a clean, accessible interface with large controls.

## User experience goals

The interface should be intentionally simple:

- large buttons;
- clear labels;
- high contrast;
- minimal text on screen;
- a prominent voice recording button;
- no complicated menus or hidden actions.

The ideal flow is:

1. Open the app
2. See family members or chats immediately
3. Tap one large button
4. Record and send a voice message

## Technical direction

Nina is planned as a service with a FastAPI backend.

Possible stack for the first version:

- **Backend:** FastAPI
- **Database:** PostgreSQL
- **ORM:** SQLAlchemy or SQLModel
- **Migrations:** Alembic
- **Authentication:** JWT or session-based auth
- **Media storage:** local storage or S3-compatible object storage
- **Realtime updates:** WebSocket or polling

## What is not included in the first version

To keep the product focused and usable, the MVP does not aim to include:

- video calls;
- group calls;
- stickers and reactions;
- advanced settings;
- complicated social features;
- message editing and deletion for everyone;
- overloaded navigation.

## Project status

The project is currently in the planning and early implementation stage.

## Mission

Make talking with family easier than figuring out the interface.
