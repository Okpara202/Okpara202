<!--
  GitHub profile README for @Okpara202
  Lives in the repo github.com/Okpara202/Okpara202 — the name must match the
  username exactly, or GitHub will not surface it on the profile.

  Brown #AB7249 is the through-line, from okpara.netlify.app. Both of the site's
  themes are honoured rather than just the dark one:
    light  text #1A2233  muted #5A6577  brown #8B5B33
    dark   text #F0F4F9  muted #98A3B4  brown #C99B6E

  The hero, the section headers and the project cards are hand-built SVG in
  assets/ rather than badge-service images. GitHub strips CSS from READMEs, so
  an SVG we own is the only place a real card system can live.

  Two rules those files follow, both learned the hard way:
    1. No page-coloured fills. A card filled with the site's near-black reads as
       a hole punched through GitHub's light theme. The cards are transparent
       with a brown border, so the page shows through either way.
    2. Nothing is a fixed page colour. Text defaults to the light theme and
       swaps under prefers-color-scheme, with the light values repeated as
       presentation attributes for anything that ignores the stylesheet.
       That query reads the OS theme, not GitHub's own setting, so a reader
       with GitHub dark on a light OS still gets the light text — but because
       of rule 1 that only costs some contrast, it cannot go invisible.
       The hero is exempt: it carries its own brown ground and its own light
       text, so it needs no query at all.
  Editing one means editing its SVG — that is the cost of it not looking generic.
-->

<div align="center">

<img src="assets/hero.svg" width="100%" alt="Favour Okpara — fullstack developer and technical writer. Enugu, Nigeria, open to what's next." />

<!--
  One link, not two: the CV lives on the portfolio and is only ever updated there.
  Nothing here to keep in sync.
-->
<a href="https://okpara.netlify.app">
  <img src="https://img.shields.io/badge/Portfolio%20%26%20CV-AB7249?style=for-the-badge&logo=googlechrome&logoColor=F5EFE8" alt="Portfolio and CV" />
</a>
<a href="mailto:okparafavour202@gmail.com">
  <img src="https://img.shields.io/badge/Email-885A3A?style=for-the-badge&logo=gmail&logoColor=F5EFE8" alt="Email" />
</a>
<a href="https://www.linkedin.com/in/favour-okpara-8a14a4309">
  <img src="https://img.shields.io/badge/LinkedIn-05080F?style=for-the-badge&logo=linkedin&logoColor=AB7249" alt="LinkedIn" />
</a>
<a href="https://medium.com/@okparafavour202">
  <img src="https://img.shields.io/badge/Medium-05080F?style=for-the-badge&logo=medium&logoColor=AB7249" alt="Medium" />
</a>

<br /><br />

<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=2200&color=AB7249&center=true&vCenter=true&width=620&lines=Fullstack+developer%2C+frontend-leaning;React+%C2%B7+Next.js+%C2%B7+React+Native+%C2%B7+Node;I+build+interfaces+that+hold+up;and+I+write+down+how+they+work"
  alt="Fullstack developer, frontend-leaning"
/>

</div>

---

<!--
  Section headings stay real <h3> elements with the SVG inline, so the document
  outline and the alt text survive. An <img> on its own line would have thrown
  both away.
-->
### <img src="assets/section-about.svg" height="26" alt="About me" />

I studied the human body for four years, then pointed the same question at software and never really stopped: *what is this part for, and what breaks if it stops?*

- **Right now** — Frontend Engineer at **Netsprin** (full-time), freelance frontend at **Simbi**, based in Enugu, Nigeria.
- **Before that** — wrote and taught a 12-week React Native + Expo curriculum at Loctech, and took 50+ students through a full-stack curriculum at LanceySoft.
- **Open to** — frontend and fullstack roles (remote, or hybrid in Enugu), select freelance builds, and paid technical writing.
- **Hours** — WAT, UTC+1. A full working day's overlap with Europe; my afternoons are the US East Coast's mornings.
- **Rule I keep** — nothing on my CV I can't defend in a code review.

---

### <img src="assets/section-toolkit.svg" height="26" alt="What I reach for" />

**Frontend**

![React](https://img.shields.io/badge/React-05080F?style=for-the-badge&logo=react&logoColor=AB7249)
![Next.js](https://img.shields.io/badge/Next.js-05080F?style=for-the-badge&logo=nextdotjs&logoColor=AB7249)
![TypeScript](https://img.shields.io/badge/TypeScript-05080F?style=for-the-badge&logo=typescript&logoColor=AB7249)
![Redux](https://img.shields.io/badge/Redux_Toolkit-05080F?style=for-the-badge&logo=redux&logoColor=AB7249)
![Zustand](https://img.shields.io/badge/Zustand-05080F?style=for-the-badge&logo=react&logoColor=AB7249)
![Tailwind](https://img.shields.io/badge/Tailwind-05080F?style=for-the-badge&logo=tailwindcss&logoColor=AB7249)

**Mobile**

![React Native](https://img.shields.io/badge/React_Native-05080F?style=for-the-badge&logo=react&logoColor=C1AA8B)
![Expo](https://img.shields.io/badge/Expo-05080F?style=for-the-badge&logo=expo&logoColor=C1AA8B)
![EAS Build](https://img.shields.io/badge/EAS_Build-05080F?style=for-the-badge&logo=expo&logoColor=C1AA8B)

**Backend & data**

![Node.js](https://img.shields.io/badge/Node.js-05080F?style=for-the-badge&logo=nodedotjs&logoColor=885A3A)
![Express](https://img.shields.io/badge/Express-05080F?style=for-the-badge&logo=express&logoColor=885A3A)
![NestJS](https://img.shields.io/badge/NestJS-05080F?style=for-the-badge&logo=nestjs&logoColor=885A3A)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-05080F?style=for-the-badge&logo=postgresql&logoColor=885A3A)
![MongoDB](https://img.shields.io/badge/MongoDB-05080F?style=for-the-badge&logo=mongodb&logoColor=885A3A)
![Redis](https://img.shields.io/badge/Redis-05080F?style=for-the-badge&logo=redis&logoColor=885A3A)

---

### <img src="assets/section-work.svg" height="26" alt="Selected work" />

<!--
  Cards sit loose inside a centred div rather than in a table: a table would
  lock the column count, this wraps to one-up on a narrow viewport on its own.
  Each card links to the live site. Repo links live in the line underneath —
  an <img> can only carry one href.
-->
<div align="center">

<a href="https://tuteraafrica.xyz/"><img src="assets/card-tutera.svg" width="47%" alt="Tutera — an LMS so educators across Africa can teach, own their material and get paid. Next.js, Zustand, Express." /></a>
<a href="https://www.bbtutors.org/"><img src="assets/card-bbtutors.svg" width="47%" alt="BB Tutors — a tutor's storefront: browse a lesson, buy it, watch it. Next.js, Express, Beepay." /></a>
<a href="https://vibecraft.today"><img src="assets/card-vibecraft.svg" width="47%" alt="VibeCraft — a website builder you talk to. Frontend only. Next.js, TypeScript." /></a>
<a href="https://adaptly.onrender.com/"><img src="assets/card-adaptly.svg" width="47%" alt="Adaptly — read a document in a language you don't speak, using Chrome's built-in AI. React." /></a>
<a href="https://griggsspecialisthospital.com.ng/"><img src="assets/card-griggs.svg" width="47%" alt="Griggs Specialist Hospital — a hospital site for people who are worried and in a hurry. React, Express." /></a>

</div>

**Code** — [VibeCraft](https://github.com/Okpara202/VibeCraft) and [Adaptly](https://github.com/Mmeso1/Adaptly) are public. Tutera, BB Tutors and Griggs are client work and stay private; happy to walk through any of them.

---

### <img src="assets/section-desk.svg" height="26" alt="On my desk this month" />

Neither is finished. That's rather the point of listing them.

- **Ahia** — a marketplace with the hard parts left in: real-time chat, escrow, and a notification pipeline that doesn't drop things. `Express` `Postgres` `Redis` `BullMQ`<br />
  → [backend](https://github.com/Okpara202/Ahia-backend) · [storefront](https://github.com/Okpara202/Ahia) · [admin](https://github.com/Okpara202/ahia-admn)
- **MyCompound** — rent tracking for landlords who currently do it in a notebook. Modelled properly before a line of code. `MongoDB` `Next.js`<br />
  → still on paper; the repo goes public with the first working slice

---

<div align="center">

<!--
  These use github-profile-summary-cards, NOT github-readme-stats.
  The github-readme-stats public instance is chronically rate-limited and was
  returning a hard 503 when this was written — it is the reason you see broken
  "Stats" images on so many profiles. Self-host that one if you ever want it.

  Deliberately dark in both colour schemes. A <picture> + prefers-color-scheme
  swap was tried and reverted: that media query reads the OS/browser theme, not
  the theme chosen in GitHub's own settings, so a dark-mode GitHub reader on a
  light OS got white cards on a dark page. Dark on light reads as a design
  choice; white on dark just reads as broken.
-->

<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Okpara202&theme=github_dark"
  width="88%"
  alt="Profile summary"
/>

<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Okpara202&theme=github_dark"
  height="200"
  alt="Commit stats"
/>
<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Okpara202&theme=github_dark"
  height="200"
  alt="Most used languages"
/>

<img
  src="https://github-readme-activity-graph.vercel.app/graph?username=Okpara202&bg_color=05080F&color=C1AA8B&line=AB7249&point=F5EFE8&area=true&hide_border=true"
  width="88%"
  alt="Contribution activity"
/>

</div>

---

### <img src="assets/section-writing.svg" height="26" alt="I also write" />

Mostly React, Next.js, React Native and the specific things that go wrong between a frontend and the API it's talking to — for the developer who is stuck on it right now, not for the algorithm.

- [**Understanding React's Rendering Behavior**](https://medium.com/@okparafavour202/understanding-reacts-rendering-behavior-what-actually-triggers-a-re-render-01ee19399d4f) — the four things that genuinely trigger a re-render, and the ones everyone blames that don't.
- [**Tree Shaking Isn't Magic**](https://medium.com/@okparafavour202/tree-shaking-isnt-magic-common-mistakes-that-keep-your-bundle-bloated-86a706669cd9) — six import and export habits that quietly keep dead code in the bundle you thought you'd trimmed.
- [**The Variable Trinity**](https://medium.com/@okparafavour202/the-variable-trinity-understanding-var-const-and-let-for-better-coding-041ad9293b1f) — `var`, `let` and `const`, and picking the one that fails loudest when you're wrong.
- [**HTML Semantics**](https://medium.com/@okparafavour202/html-semantics-elevate-your-web-development-with-meaningful-markup-235c82f4dfea) — markup that tells a screen reader, and a crawler, what it is actually looking at.

[Everything else on Medium →](https://medium.com/@okparafavour202)

---

<div align="center">

If you have a product engineers need to understand and nobody on the team has time to write it up, that's the job I want.

<a href="mailto:okparafavour202@gmail.com">
  <img src="https://img.shields.io/badge/Come%20tell%20me%20what%20you're%20building-AB7249?style=for-the-badge&logoColor=F5EFE8" alt="Get in touch" />
</a>

<br /><br />

<sub><i>Still the same habit — take it apart, see what each piece was doing there.</i></sub>

</div>
