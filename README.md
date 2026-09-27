# Hey, I'm Nikhil 👋

### Backend Engineer · Builder · Curious about how things work

I started writing code because I wanted to make things.

Then I started asking questions.

**How does a browser talk to a server?**
**What actually happens to the data?**
**What happens when multiple users change something at the same time?**
**How do you protect data that shouldn't even be visible to the database?**

Most of my repositories are basically the trail of those questions.

---

## Table of Contents

- [The journey](#the-journey)
- [2024 — I started by making things](#making-things)
- [Then I discovered applications](#discovered-applications)
- [Then backend became interesting](#backend-became-interesting)
- [Then I started thinking in real time](#real-time-thinking)
- [Open Source](#open-source)
- [Then security became a rabbit hole](#security)
- [Real-time + Encryption](#realtime-encryption)
- [Sometimes I just build tools for myself](#developer-tools)
- [Physics → Software](#physics-to-software)
- [What I'm interested in now](#current-interests)

---

<a id="the-journey"></a>

## 🧭 The journey

```text
small programs
      │
      ▼
web applications
      │
      ▼
backend & APIs
      │
      ▼
real-time systems
      │
      ▼
open source
      │
      ▼
security & encryption
      │
      ▼
systems & developer tools
```

---

<a id="making-things"></a>

## 🪴 2024 — I started by making things

My first projects were small.

A game.
A calculator.
A few web experiments.

Nothing fancy.

I was mostly trying to answer one question:

> **"Can I build this myself?"**

A few of those early experiments:

🎮 [Tic-Tac-Toe](https://github.com/Nikhil-Gautam-dev/tic-tac-toe-game)
🧮 [Calculator](https://github.com/Nikhil-Gautam-dev/Calculator)
🐱 [Cat Facts](https://github.com/Nikhil-Gautam-dev/Cat-Facts)

---

<a id="discovered-applications"></a>

## 🌐 Then I discovered applications

Eventually, small experiments weren't enough.

I wanted to build things where multiple pieces had to work together.

That's where **Connectify** came in.

Frontend.
Backend.
Database.
APIs.

Suddenly, writing code wasn't enough.

The pieces had to communicate correctly.

→ [Connectify Frontend](https://github.com/Nikhil-Gautam-dev/connectify-frontend)
→ [Connectify Backend](https://github.com/Nikhil-Gautam-dev/connectify-backend-api)

---

<a id="backend-became-interesting"></a>

## ⚙️ Then backend became interesting

The more applications I built, the more interested I became in the part users don't see.

Requests.

Data.

Authentication.

Business logic.

Performance.

And eventually:

> **"Why is this request taking 2 seconds?"**

That's when backend stopped being just another part of the application and became the thing I wanted to understand deeply.

→ [AI Chat Backend](https://github.com/Nikhil-Gautam-dev/AIChatApp-backend)
→ [Chat App](https://github.com/Nikhil-Gautam-dev/chat-app)

---

<a id="real-time-thinking"></a>

## 🔄 Then I started thinking in real time

Request → response was only the beginning.

I wanted to understand what happens when systems need to communicate continuously.

That led me toward WebSockets, synchronization and eventually message brokers.

Projects like **SketchSync** and **Encora** came out of that curiosity.

→ [SketchSync](https://github.com/Nikhil-Gautam-dev/SketchSync)
→ [Encora](https://github.com/Nikhil-Gautam-dev/encora)

---

<a id="open-source"></a>

# 🌍 Open Source

At some point I stopped building only inside my own repositories.

I started fixing things in projects built by other people too.

### 🟢 Puter

**[PR #1463 — Update Norwegian Nynorsk translations](https://github.com/HeyPuter/puter/pull/1463)**

Merged into `HeyPuter/main`.

I updated the incomplete Norwegian Nynorsk translation, added missing keys, followed the project's conventions, and validated the changes.

→ [View PR #1463](https://github.com/HeyPuter/puter/pull/1463)

### 🟢 Realtime Collaborative Code Editor

**[PR #15 — Fix theme change resetting editor content](https://github.com/Mohitur669/code-editor/pull/15)**

Changing the editor theme was causing the application to reload and reset the user's code.

I fixed the theme handling so users could change themes without losing their current work.

→ [View PR #15](https://github.com/Mohitur669/code-editor/pull/15)

**2 merged PRs. Different projects. Different problems.**

That's one of the things I like about open source — you don't control the whole codebase, so you have to understand the system before changing it.

---

<a id="security"></a>

# 🔐 Then security became a rabbit hole

Building APIs taught me how to move data around.

Security made me ask:

> **"What if the database itself shouldn't be able to read some of this data?"**

That question eventually led me to MongoDB Client-Side Field Level Encryption.

Instead of implementing it separately in every application, I built:

### Mirage Encryption

A TypeScript utility library for MongoDB CSFLE with automated key and schema management and support for multiple KMS providers.

→ [Mirage Encryption](https://github.com/Nikhil-Gautam-dev/mirage-encryption)

And then I built something with it.

### TodoCrypt

A small application demonstrating what happens when application data is transparently encrypted at the database layer.

→ [TodoCrypt](https://github.com/Nikhil-Gautam-dev/TodoCrypt)

```text
       MIRAGE ENCRYPTION
          reusable layer
                │
                ▼
            TODOCRYPT
          actual usage
```

---

<a id="realtime-encryption"></a>

# 🔒 Real-time + Encryption

That curiosity also turned into **Encora**.

A real-time chat platform combining:

- WebSockets
- RabbitMQ
- MongoDB
- Web Crypto API
- ECDH P-256
- AES-256-GCM

The interesting part wasn't just making a chat application.

It was figuring out how all the pieces fit together.

→ [Encora](https://github.com/Nikhil-Gautam-dev/encora)

---

<a id="developer-tools"></a>

# 🖥️ Sometimes I just build tools for myself

Not everything needs to be a web application.

I wanted a terminal-first notes and reminder tool that I could actually use.

So I built **Nikki**.

SQLite.
CLI.
Background daemon.
systemd.
Notifications.

Small project.

Very useful.

→ [Nikki](https://github.com/Nikhil-Gautam-dev/nikki)

---

<a id="physics-to-software"></a>

# 🔬 Physics → Software

Before all of this, there was physics.

Some of my projects started as attempts to turn physics concepts into interactive software.

→ [Optical Fiber Simulation](https://github.com/Nikhil-Gautam-dev/optical-fiber-simulation)
→ [PhysXplore](https://github.com/Nikhil-Gautam-dev/physXplore)

Physics taught me to be curious about what's happening underneath the surface.

Software gave me another place to apply that curiosity.

---

<a id="current-interests"></a>

# 🧠 What I'm interested in now

I'm increasingly interested in the problems underneath applications:

**Distributed Systems**
**Backend Architecture**
**Databases**
**Networking**
**Security**
**Message-Driven Systems**
**Linux & Infrastructure**

I like taking an abstraction apart just to see what's underneath it.

---

## Currently building, learning & breaking things

```text
backend systems
distributed systems
database internals
networking
security
infrastructure
```

---

### Find me elsewhere

[Portfolio](https://Nikhil-Gautam-dev.github.io) · [LinkedIn](https://www.linkedin.com/in/nikhil-malhotra-80a344218/) · [daily.dev](https://daily.dev/nikhil3)

---

> I usually don't start a project because I know how to build it.
>
> I start because I want to know **how it works**.
