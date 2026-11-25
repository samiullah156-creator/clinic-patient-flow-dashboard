<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=Clinic%20Patient%20Flow%20Dashboard&fontSize=38&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Healthcare%20%E2%80%A2%20Custom%20healthcare%20dashboard&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="Clinic Patient Flow Dashboard" />

**A live clinic dashboard that puts every provider and room on one schedule, with wait times, no-shows and appointment status in real time.**

<p>
  <img src="https://img.shields.io/badge/Healthcare-167dfe?style=flat-square" alt="Healthcare" />
  <img src="https://img.shields.io/badge/Custom%20healthcare%20dashboard-9533fa?style=flat-square" alt="Custom healthcare dashboard" />
  <img src="https://img.shields.io/badge/React-231f20?style=flat-square" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-231f20?style=flat-square" alt="Node.js" />
  <img src="https://img.shields.io/badge/Python-231f20?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/Supabase-231f20?style=flat-square" alt="Supabase" />
  <img src="https://img.shields.io/badge/Scheduling%20API-231f20?style=flat-square" alt="Scheduling API" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![Clinic patient flow dashboard: a live schedule of every provider and room with wait times, no-shows and a current time marker.](assets/cover.webp)

## Overview

Clinic managers had no live view of bookings, no-shows or wait times. Lexvaxa built a custom dashboard connected to the clinic scheduling system that shows the whole day on one screen: each provider and room as a row, every appointment with its live status, and headline numbers for patients waiting, in the room, average wait and no-shows. Managers also see appointments per day and visits by department and booking channel. Screens shown use sample data, so no client records are exposed.

## The challenge

Bookings, no-shows and waiting patients were spread across the scheduling system and the front desk, so problems were only noticed after they caused delays.

## The solution

A React dashboard fed by the scheduling API through n8n and Supabase, showing a live day schedule, status colours and the key flow numbers.

## Key features

- Live day schedule by provider and room
- Appointment status: booked, waiting, in room, done
- Patients waiting, in room, average wait and no-shows
- Appointments per day trend
- Visits by department and booking channel
- Current time marker to spot running late

## Results

- Front desk and managers see the whole day at a glance
- Gaps and delays are caught early instead of after the fact

## Tech stack

![React](https://img.shields.io/badge/React-1d1726?style=for-the-badge) ![Node.js](https://img.shields.io/badge/Node.js-1d1726?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![Supabase](https://img.shields.io/badge/Supabase-1d1726?style=for-the-badge) ![Scheduling API](https://img.shields.io/badge/Scheduling%20API-1d1726?style=for-the-badge)

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/clinic-patient-flow-dashboard

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
