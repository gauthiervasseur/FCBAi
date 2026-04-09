---
marp: true
theme: Page_FCBAi_Landscape
paginate: true
backgroundColor: white
---

<style>

:root {
  /* UC Berkeley palette */
  --berkeley-blue: #003262;
  --berkeley-gold: #FDB515;
  --color-muted: #6E6E70;
  --color-bg-light: #FFF3CC;  /* optional for table headers */
}

body {
  font-family: 'Montserrat', sans-serif;
}

/* =========================
   Logo Row
   ========================= */
.logo-row{
  display: flex;
  justify-content: space-between; /* keeps logos spread out */
  align-items: center;            /* vertically centers logos */
  margin-bottom: 1rem;
  gap: 10px;                      /* optional spacing between logos */
}

.logo-row img{
  height: 35px;                   /* smaller and more balanced */
  max-width: 120px;               /* prevents overly wide logos */
  object-fit: contain;            /* keeps aspect ratio intact */
}

/* =========================
   Headings
   ========================= */
h1 {
  font-family: 'Montserrat', sans-serif;
  font-size: 30px;
  line-height: 30px;
  color: var(--berkeley-blue);
  font-weight: 700;
}

h2 {
  font-family: 'Montserrat', sans-serif;
  font-size: 20px;
  line-height: 12px;
  text-align: center;
  color: var(--berkeley-gold);
  font-weight: 700;
}

/* =========================
   Tables
   ========================= */
table {
  width: 100%;
  border-collapse: collapse;
  font-size: 10.5px;
  text-align: left;
  border: 0.5px solid #ddd;
  font-family: 'Montserrat', sans-serif;
}

th, td {
  font-size: 10.25px;
}

table th, table td {
  border: 0.5px solid #ddd;
  padding: 8px;
}

table th {
  font-weight: bold;
  text-align: center;
}

/* Remove alternating row background colors */
table tr {
  background-color: transparent;  /* Make all rows transparent */
}

table tr:nth-child(even),
table tr:nth-child(odd) {
  background-color: transparent;  /* Override any default striping */
}

/* =========================
   Watermark / Draft
   ========================= */
section::before{
  content: "FCBA — DRAFT";
  font-family: 'Montserrat', sans-serif;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%) rotate(-30deg);
  font-size: 64px;
  font-weight: 700;
  letter-spacing: 0.08em;
  color: rgba(0,0,0,0.10);
  pointer-events: none;
  z-index: 0;
  white-space: nowrap;
}


/* Pagination / footer */
section::after {
  bottom: 0in;
  font-family: 'Montserrat', sans-serif;
  font-size: 10px;
  color: var(--berkeley-blue); 
  font-weight: normal;
}

</style>

<div class="logo-row">
<img src="./res/Berkeley Haas.png" />
<img src="./res/logo-fcba-transparent.png" />
<img src="./res/IBI Logo Final.png" />
<img src="./res/CNAM_Logo.png" />
</div>

<br>
<br>

# Entrepreneurship & Innovation in a Data-Driven World

## Think Big. Build Smart. Pitch Confidently. | July 5-11, 2026

<br>

| Date       | Location                  | Time         | Theme                     | Day Progression             | Session Title                               | Speaker                                           |
|------------|---------------------------|-------------|---------------------------|----------------------------|--------------------------------------------|--------------------------------------------------|
| 07/06/26   | UC Berkeley/SF           | 09:00–10:30 | Entrepreneurship          | Inspire & open mindset     | Innovation Mindset & Silicon Valley DNA    | Gigi Wang                                        |
| 07/06/26   | UC Berkeley/SF           | 10:45–12:15 | Leadership & Creativity   | Build team dynamics        | Improvisation & Entrepreneurial Presence   | Dan Klein                                        |
| 07/06/26   | UC Berkeley/SF           | 13:30–15:00 | Entrepreneurship          | Form teams & define ideas  | Mini-Project Kickoff: Startup Creation     | Rhonda Schrader                                  |
| 07/06/26   | UC Berkeley/SF           | 15:15–16:45 | Strategy & Data           | Frame opportunity spaces   | Platform & Data-Driven Business Models     | Greg LaBlanc                                     |
| 07/06/26   | UC Berkeley/SF           | 17:00–18:30 | Applied Entrepreneurship  | Select problem space       | Guided Ideation Workshop (On the Bay)      | Rhonda Schrader                                  |
| 07/07/26   | SF                        | 18:30–21:00 | Boat Session              | Networking & ideation      | Evening Reflection & Team Bonding          | Facilitators                                     |
| 07/07/26   | UC Berkeley              | 09:00–10:30 | Design Thinking           | Problem framing           | Start with the Right Problem (Design Thinking) | Dave Rochlin                                  |
| 07/07/26   | UC Berkeley              | 10:45–12:15 | Applied Design Thinking   | Real-world application    | Applied Design Thinking Case               | Elizabeth Glenewinkel                             |
| 07/07/26   | UC Berkeley              | 13:30–15:00 | Applied Entrepreneurship  | Understand users          | Customer Discovery & Personas Workshop    | Dave Rochlin                                     |
| 07/07/26   | UC Berkeley              | 15:15–16:45 | Innovation                | Broaden perspective       | Innovation & Design in Silicon Valley     | Barry Katz                                       |
| 07/07/26   | UC Berkeley              | 17:00–18:30 | Applied Entrepreneurship  | Refine problem & solution | Mini-Project Sprint #1                     | Rhonda Schrader                                  |
| 07/08/26   | UC Berkeley              | 09:00–10:30 | Data & AI                 | Introduce data strategy   | Data-Driven Decision Making for Startups  | Gauthier Vasseur                                 |
| 07/08/26   | UC Berkeley              | 10:45–12:15 | AI Fundamentals           | Understand capabilities   | Generative AI Fundamentals                | Michael Wu                                       |
| 07/08/26   | UC Berkeley              | 13:30–15:00 | AI Governance             | Build responsible solutions | Explainability & Trust in AI            | Genevieve Smith                                  |

---
<div class="logo-row">
<img src="./res/Berkeley Haas.png" />
<img src="./res/logo-fcba-transparent.png" />
<img src="./res/IBI Logo Final.png" />
<img src="./res/CNAM_Logo.png" />
</div>

<br>


| Date       | Location                  | Time         | Theme                     | Day Progression             | Session Title                               | Speaker                                           |
|------------|---------------------------|-------------|---------------------------|----------------------------|--------------------------------------------|--------------------------------------------------|
| 07/08/26   | UC Berkeley              | 15:15–16:45 | Applied Data & Validation | Define validation framework | Data-Driven Validation for Startups      | Gauthier Vasseur    |
| 07/08/26   | UC Berkeley              | 17:00–18:30 | Applied Data & Validation | Validate idea with data   | Mini-Project Sprint #2                     | Rhonda Schrader + Gauthier Vasseur              |
| 07/09/26   | UC Berkeley              | 09:00–10:30 | Entrepreneurship          | Build & iterate           | Lean Startup & Iteration                  | Rhonda Schrader                                  |
| 07/09/26   | UC Berkeley              | 10:45–12:15 | Marketing                 | Reach customers           | Go-To-Market Strategy for Startups        | Holly Roland                                     |
| 07/09/26   | UC Berkeley              | 13:30–15:00 | Finance & Growth          | Think like investors      | VC Mindset & Scaling Startups             | George Panagiotakopoulos                                           |
| 07/09/26   | UC Berkeley              | 15:15–16:45 | Pitching                  | Structure compelling pitch | Pitching with Data & Storytelling         | Gauthier Vasseur                                 |
| 07/09/26   | UC Berkeley              | 17:00–18:30 | Applied Pitching          | Finalize deck & narrative | Mini-Project Sprint #3 (Pitch Prep)       | Gauthier Vasseur                                 |
| 07/10/26   | Plug and Play Tech Center | 09:00–10:30 | Capstone                  | Deliver final startup pitch | Final Pitch Competition                   | Jury: Rhonda Schrader, Gauthier Vasseur, Chris Bush, Kateryna Akymenko |
| 07/10/26   | Plug and Play Tech Center | 10:45–12:15 | Ecosystem                 | Startup acceleration insights | Visit Plug and Play Tech Center          |                                                  |
| 07/10/26   | Silicon Valley           | 13:00–14:30 | Innovation                | Corporate innovation      | Visit Apple Park (Innovation at Scale)    |                                                  |
| 07/10/26   | Silicon Valley           | 14:45–16:15 | AI & Product              | Real-world applications   | Visit Google (AI & Product)               |                                                  |
| 07/10/26   | Silicon Valley           | 16:30–18:00 | Academia & Entrepreneurship | Research ecosystem       | Visit Stanford University                  |                                                  |