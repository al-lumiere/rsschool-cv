---
layout: default
title: Aliaksandra Pletsiazhova
---

# Aliaksandra Pletsiazhova

## Frontend Developer

Tel Aviv · Ready for relocation

---

## Contact

- Email: alyaplfv@gmail.com
- Phone: +972 58 7440301
- Telegram: @al_lmre
- Discord: @alexandrapletezhova
- GitHub: [github.com/al-lumiere](https://github.com/al-lumiere)

---

## About Me

Frontend Developer with a background in graphic design.

I approach interfaces with a designer's eye and an engineer's mindset, combining visual intuition with structured frontend architecture.

I develop web applications using React and TypeScript, focusing on maintainable code, reusable components, and thoughtful user experience.

---

## Skills

### Frontend

- HTML
- CSS / SCSS
- JavaScript
- TypeScript
- React
- Next.js
- React Router
- Redux Toolkit

### Tools & Technologies

- Axios
- Vite
- Webpack
- Storybook
- Vitest
- Cypress
- Git
- Figma

---

## Code Example

### Number of Integer Partitions — Codewars, 4 kyu

A dynamic programming solution that calculates the number of ways an integer can be represented as a sum of positive integers.

```javascript
function partitions(n) {
  const arr = new Array(n + 1).fill(0);

  arr[0] = 1;

  for (let i = 1; i <= n; i++) {
    for (let sum = i; sum <= n; sum++) {
      arr[sum] += arr[sum - i];
    }
  }

  return arr[n];
}
```

**Time complexity:** O(n²)
**Space complexity:** O(n)

---

## Algorithms & Problem Solving

- Codewars — **4 kyu**
- Yandex Algorithm Training — **top 350 participant**
- Repository with my algorithm solutions: [algo-practice](https://github.com/al-lumiere/algo-practice)

---

## Work Experience

### Mentoriya

**Frontend Developer Intern**
*June 2026 — Present*

Developing a web platform that helps tutors manage their profiles, schedules, and day-to-day work with students.

- Build reusable UI components and product pages with Next.js, React, TypeScript, and SCSS Modules.
- Implement email- and phone-based authentication and registration flows with client-side validation and server error handling.
- Integrate REST APIs with Axios, including token management and asynchronous data handling.
- Contribute to component architecture and maintain reusable components in Storybook.
- Participate in code reviews and task decomposition.

---

## Selected Projects

**Frontend Developer**
*2025 — Present*

- Built responsive React and TypeScript applications with reusable UI components and Redux Toolkit.
- Integrated REST APIs and asynchronous data handling.
- Wrote unit tests and worked with component-based architecture.
- Participated in code reviews and Git-based development workflows.

---

## Previous Experience

### EventMakers

**Designer**
*2023 — 2025*

- Developed and adapted key visuals for corporate events.
- Contributed to launching the EventMakers educational project.
- Worked on visual communication, social media management, and presentation materials.

### Gurtam

**Brand Designer**
*2022 — 2024*

- Worked on the company's HR brand and internal communications.
- Developed visual materials for corporate events, office branding, merchandise, and social media.
- Contributed to maintaining visual consistency across internal and external channels.

---

## Education

### Belarusian State University

**Bachelor's Degree — International Management**
Faculty of Economics
*2018 — 2022*

---

## Training

### Frontend Development

**Yandex Practicum**
*2025 — 2026*

**Yandex Algo Trainings**
*april 2026, september 2026*

### Visual Communication & Design

Adobe, Figma, Motion
*2020 — 2024*

---

## Languages

- Russian — Native
- English — Professional working proficiency