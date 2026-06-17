# Hey, I'm Tyson

I'm a **Backend Developer in Progress** documenting my path from IT support into software development.

Right now, this profile is not really a hiring page. It is more of a public record of what I am learning, what I am building, and how my understanding of software is growing over time.

I started with Python, which helped me learn basic coding structure, scripting, automation, and how to break problems into smaller pieces. Since then, I have been spending most of my time with Go, PostgreSQL, server-rendered web apps, and backend-focused projects.

## What I'm Working Toward

My current goal is to become a **junior backend developer**.

Long term, I would love to learn lower-level languages like **C++** and **Rust**, and eventually work on interesting technology at a large game development studio.

For now, my focus is simpler and more practical:

I want to build tools that help people around me, automate annoying workflows, and make real tasks easier.

## Background

I work in IT support for tax software, mostly around local government workflows.

That gives me a lot of exposure to the messy side of software:

* real users
* confusing workflows
* repetitive manual processes
* data that needs to be searched, moved, cleaned, or organized
* systems that need to be understood before they can be improved

That has shaped how I think about programming. I am not just interested in making code run. I want to understand how the whole system behaves.

## Currently Building With

These are the tools and concepts I am actively working with:

* Go
* Python
* PostgreSQL
* SQL
* HTML
* CSS
* HTMX
* Bootstrap
* Server-rendered templates
* REST-style APIs
* Database-backed applications
* Internal tools
* Automation scripts

I am still learning, so I try not to present this as a finished skill list. These are the things I am practicing, using, breaking, fixing, and slowly getting better at.

## Featured Project

### Support Meeting App Demo

My main public project is a sanitized demo of an internal support meeting app.

The app pulls support tickets from Desk365, mirrors them into a local PostgreSQL database, and organizes them by client/county and product group for recurring support meetings.

The goal is to replace a more manual meeting workflow with a cleaner internal dashboard where support staff can review tickets, add notes, view conversation threads, and keep meeting information organized.

Built with:

* Go
* PostgreSQL
* sqlc
* goose
* HTMX
* Bootstrap
* Go `html/template`
* Desk365 API integration

Some of the main pieces include:

* ticket sync from Desk365 into Postgres
* grouped ticket dashboard
* county/client-level notes
* ticket-level notes
* conversation thread view
* server-side sessions
* protected routes
* local database mirror
* server-rendered HTML updates with HTMX

This project has been my main learning ground for understanding how backend applications fit together: routing, handlers, templates, SQL queries, migrations, authentication, API calls, data modeling, and UI behavior.

## What I'm Learning From It

The biggest thing I have learned so far is that building software is a lot of deciding what **not** to build yet.

I am learning to think ahead before adding features:

* what is worth building now
* what can wait until later
* what should be prepared for without overbuilding
* what might become useful but does not belong in the code yet
* what complexity is solving a real problem versus creating a new one

Simplicity usually ends up being better, but I think dealing with complexity is part of learning why that is true.

It is easy to say "keep it simple" when you have not had to untangle something messy yet. Running into confusing code, awkward data flow, or features that do too much has helped me understand why simple boundaries and clear structure matter.

I am also learning that debugging is not just fixing errors. It is tracing the environment the error came from.

When something breaks, I try to move through the layers:

* Is this a UI problem?
* Is the request wrong?
* Is the handler doing the wrong thing?
* Is the template receiving bad data?
* Is the database query returning something unexpected?
* Is the data model wrong?
* Did I make a bad assumption earlier?

That kind of debugging has become one of the most useful skills I have picked up. Instead of staring at the final symptom, I am getting better at tracing the issue backward until I find where the behavior actually changed.

## Problems I'm Interested In

I have not worked on enough different kinds of projects yet to know exactly what niche I like most.

For now, the problems that interest me are things like:

* turning manual workflows into useful tools
* building database-backed apps
* making information easier to search and filter
* connecting APIs to local systems
* automating repetitive work
* designing simple internal dashboards
* improving messy processes one piece at a time

I like boring software when it solves a real problem.

## How I Think About Learning

I am trying to move from:

> "I got it to work"

to:

> "I understand why it works, where it can fail, and how to make it better."

That means spending more time on debugging, naming, structure, data flow, and tradeoffs instead of only chasing the next feature.

I am not trying to look like an expert before I am one. I am trying to build enough real things that my understanding catches up with my ambition.

## Current Direction

Right now, I am focused on:

* writing better Go
* improving my SQL
* designing cleaner database schemas
* understanding backend architecture
* building practical internal tools
* getting better at debugging
* learning how to structure larger projects
* documenting my progress honestly

Eventually, I want to explore lower-level programming, performance, systems, game technology, and more advanced backend concepts.

For now, I am building one useful thing at a time.
