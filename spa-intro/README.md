# React & Redux Training - Gofore Oy

## Trainers
- Mikko Matilainen & Juhani Tapaninen
- Worked on projects using React, Redux and MobX

## Slides

Available in [react-redux-training.herokuapp.com](http://react-redux-training.herokuapp.com/)

---

## Agenda - Day 1
#### Morning
- Introduction to SPAs
- ES2016+ & Tooling
- React Fundamentals

#### Afternoon
- React Advanced Topics
- React Router

---

## Agenda - Day 2
#### Morning
- Redux
- Redux Form
- Reselect
- Async libraries

#### Afternoon
- Universal React
- Progressive Web Apps
- Testing

---

# Introduction to SPAs & React

## Agenda

- What is an SPA?
- Real-life examples
- Technical overview

---

# What Is a SPA?

- "A single-page application (SPA) is a web application or web site that fits on a single web page with the goal of providing a more fluid user experience similar to a desktop application." - Wikipedia
- Browser fetches executable code that makes asynchronous calls for actual data to be shown
- Data is visualized and/or manipulated and stored back on server asynchronously

---

# Real-life Examples
- [Google search](http://www.google.com)
- [Facebook](http://facebook.com)
- [Twitter](http://twitter.com)

---

# Technical Overview

- Initial page load fetches index HTML and JavaScript
- JavaScript fetches the actual data via AJAX (Asynchronous JavaScript and XML). Data is usually JSON (or XML)
- JavaScript renders the data on templates and binds event handlers for clicks, keyboard input etc.


---

# React

- JavaScript library for building user interfaces
- First release by Facebook in 2013
- Provides only the V in MVC
- Emphasis on declarative UI, view is a function of the state
- One-way data binding
- Multiple rendering targets (browser, mobile, desktop)
