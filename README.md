# Alarmageddon

> Because normal alarms are not annoying enough.

Alarmageddon is a mobile alarm app that is designed to make waking up as difficult as possible. Instead of simply playing a sound, the app can use loud and unusual sounds, math problems, physical tasks and other challenges to make sure the user actually gets out of bed.

The main goal of the project is to learn mobile development with C# and Avalonia while building something fun and different.

---

# Project Planning

## 1. Project Idea

**Alarmageddon is an alarm app that uses increasingly annoying and difficult challenges to make sure the user actually wakes up.**

The app should still work as a normal alarm clock, but waking up should be unnecessarily complicated and funny.

## 2. Expected Technical Challenges

I expect the following parts of the project to be challenging:

* Creating reliable alarms on mobile devices
* Handling background tasks and notifications
* Playing audio when the alarm goes off
* Working with vibration and other device features
* Creating different wake-up challenges
* Generating math problems
* Implementing QR code challenges
* Saving alarms and user data
* Tracking sleep and wake-up times
* Creating a basic sleep cycle prediction
* Making the UI work well on different screen sizes
* Learning how Avalonia works on mobile platforms

One of the biggest challenges will probably be dealing with the restrictions that mobile operating systems have for alarms, background processes and audio.

## 3. Non-Technical Goals

Besides programming, I want to practise the following skills:

* Planning a larger project
* Breaking features into smaller user stories
* Estimating how long tasks will take
* Keeping a project organised
* Writing useful documentation
* Designing a good user interface
* Making design decisions independently
* Reflecting on my progress
* Using Git and GitHub properly

I also want to practise finishing the important parts of a project before continuously adding new features.

## 4. Difference From My Previous Projects

Alarmageddon is quite different from my previous projects.

Most of my previous projects focused on areas such as web development, desktop applications, games and programming experiments. This project is mainly focused on mobile development.

I will work with technologies and concepts that I have not used much before, including:

* Mobile UI
* Mobile notifications
* Background processes
* Device features such as vibration and sensors
* Local data storage
* Mobile application lifecycle
* Cross-platform development with Avalonia

This makes the project a good addition to my previous work because it allows me to learn a different area of software development instead of repeating something I already know.

## Status Legend

* ○ Planned
* ⟳ In Progress
* ✓ Completed
* 🗙 Cancelled

## User Stories

The following table contains the planned user stories for the project.

| Status | ID | User Story | Target Date |
| :---: | :---: | --- | :---: |
| ○ | US-01 | As a user, I want to create an alarm so that I can wake up at a specific time. | 21.08.2026 |
| ○ | US-02 | As a user, I want to edit and delete alarms so that I can manage my alarms. | 21.08.2026 |
| ○ | US-03 | As a user, I want to choose an alarm sound so that I can decide how I want to wake up. | 21.08.2026 |
| ○ | US-04 | As a user, I want the alarm to become more annoying over time so that I cannot simply ignore it. | 28.08.2026 |
| ○ | US-05 | As a user, I want to solve a math problem before I can turn off the alarm. | 28.08.2026 |
| ○ | US-06 | As a user, I want to choose how difficult the wake-up challenges are. | 28.08.2026 |
| ○ | US-07 | As a user, I want to use a QR code as a wake-up challenge so that I have to get out of bed. | 04.09.2026 |
| ○ | US-08 | As a user, I want to see statistics about my alarms and wake-up behaviour. | 04.09.2026 |
| ○ | US-09 | As a user, I want the app to analyse my sleep history and suggest suitable wake-up times. | 04.09.2026 |
| ○ | US-10 | As a user, I want to customize how my alarm behaves. | 11.09.2026 |
| ○ | US-11 | As a user, I want different alarm difficulty levels. | 11.09.2026 |
| ○ | US-12 | As a user, I want my alarms and statistics to be saved when I close the app. | 11.09.2026 |
| ○ | US-13 | As a user, I want a simple and pleasant interface. | 11.09.2026 |
| ○ | US-14 | As a user, I want the app to give me feedback after successfully completing an alarm. | 11.09.2026 |

## Development Tasks

These tasks cover the technical preparation and project setup of Alarmageddon. They are separate from the user stories because they focus on the development process rather than user-facing features.

| Status | ID | Development Task | Target Date |
| :---: | :---: | --- | :---: |
| ○ | DEV-01 | As a developer, I want to set up the Avalonia project so that I have a working foundation for Alarmageddon. | 14.08.2026 |
| ○ | DEV-02 | As a developer, I want to create a basic project structure so that the code remains organised as the project grows. | 14.08.2026 |
| ○ | DEV-03 | As a developer, I want to set up the basic MVVM architecture so that UI and application logic are separated. | 14.08.2026 |
| ○ | DEV-04 | As a developer, I want to create the initial UI layout so that I have a foundation for the application interface. | 14.08.2026 |
| ○ | DEV-05 | As a developer, I want to configure Git and GitHub so that the project can be properly version controlled. | 14.08.2026 |
| ○ | DEV-06 | As a developer, I want to document the project structure and implementation plan so that I have a clear direction for development. | 14.08.2026 |

---

# Progress and Reflections

## 14.08.2026

### What I Did

I started the Alarmageddon project and set up the basic project structure. I created the Avalonia application projects for the supported platforms and configured the project so that the different targets are organised separately.

I also set up Git and GitHub for version control and created the initial project documentation. The README was structured to describe the project idea, technical challenges, goals, user stories and development tasks.

During the initial setup, I also reorganised the project structure by moving the application projects into a dedicated `src` directory and updating the solution files accordingly.

### Reflection

The first day was mainly focused on planning and setting up a solid foundation for the project. I now have a clearer overview of what I want to build and how I want to structure the development process.

I also gained some initial experience with setting up a cross-platform Avalonia project and organising a larger project with multiple platform targets. The project is now ready for the actual implementation of the first user-facing features.

---

## 21.08.2026

### What I Did

*To be filled in.*

### Reflection

*To be filled in.*

---

## 28.08.2026

### What I Did

*To be filled in.*

### Reflection

*To be filled in.*

---

## 04.09.2026

### What I Did

*To be filled in.*

### Reflection

*To be filled in.*

---

## 11.09.2026

### What I Did

*To be filled in.*

### Reflection

*To be filled in.*

---

# Technology

| Technology | Purpose |
| --- | --- |
| C# | Main programming language |
| .NET | Application framework |
| Avalonia UI | User interface |
| XAML | UI layout |
| MVVM | Application architecture |
| SQLite | Local data storage |
| Git | Version control |
| GitHub | Repository and documentation |

---

# Goals

By the end of the Lernperiode, I want to have a working prototype that can:

* Create and manage alarms
* Play an alarm sound
* Make the alarm increasingly annoying
* Require the user to solve challenges
* Generate math problems
* Save alarm and wake-up data
* Show basic statistics
* Provide a basic sleep cycle prediction
* Run on a mobile device
* Have a clean and recognizable user interface

Most importantly, I want to use this project to get my first proper experience with mobile development while creating something that is actually fun to use.
