<h1 align="center">Hi there :wave:, I'm Devashish :ninja: </h1>

<h3 align="center">A Full Stack Developer From Rajasthan, India</h3>

<p align="center">
  🌐 <a href="https://www.devashishsuthar.dev" target="_blank"><strong>devashishsuthar.dev</strong></a>
  &nbsp;·&nbsp;
  💼 <a href="https://linkedin.com/in/devashish-suthar-mern-stack" target="_blank"><strong>LinkedIn</strong></a>
  &nbsp;·&nbsp;
  📧 <a href="mailto:devashish.suthar5728@gmail.com"><strong>Email</strong></a>
</p>
<br/>
<p><strong>Welcome to my coding realm! :rocket: As a coding enthusiast, I've turned my passion into a profession :ninja: , and I'm on a mission to unlock the potential of the digital world. :globe_with_meridians: <br/>
With a calm disposition, I wield my coding superpowers :muscle: in JavaScript, TypeScript, React, Next.js and Node — with over 7 years of industry experience :briefcase:, and increasingly, AI-agent engineering.</strong></p>
</br>

<ul>
  <!-- <li>:rocket: &nbsp;<strong>Open for Adventures:</strong> I'm currently exploring the vast realm of opportunities, seeking new horizons where I can contribute and thrive.</li> -->
  <li>:rocket: &nbsp;<strong>Open for Adventures:</strong> Actively looking for full-stack / AI-integrated engineering roles — remote or on-site.</li>
  <li>🤖 &nbsp;<strong>Currently exploring:</strong> Agentic systems — LLM tool-orchestration, grounding, and business-rule-enforcing tool design (see featured project below).</li>
  <li>:fist_right: &nbsp;<strong>Teamwork Maestro:</strong> Collaboration is where magic happens! Always up for kindred spirits to embark on thrilling coding adventures.</li>
  <li>:nerd_face: &nbsp;<strong>JavaScript Aficionado:</strong> When it comes to <strong>JavaScript, TypeScript, React, Next.js, and Node,</strong> I'm your go-to source of wisdom. Feel free to pick my brain about these tech wonders.</li>
  <li>:inbox_tray: &nbsp;<strong>Connect with Me:</strong> Have a brilliant idea or simply want to say hello? Don't hesitate to reach out at <strong><a href="mailto:devashish.suthar5728@gmail.com">devashish.suthar5728@gmail.com</a></strong>. Let's turn ideas into digital realities! :bulb: :fire:</li>
  <li>🧔✨&nbsp;<strong>Unveil my distinctive charm:</strong> In a world of color, I stand out with my monochrome charm — a single, natural white beard on the left, my trademark style. :sunglasses:</li>
</ul>

## 🛒 Featured Project: Supermarket Ops Agent

A conversational AI agent that runs a small Indian kirana (grocery) store end-to-end — receiving stock, cutting GST-correct bills, running customer credit (khata), closing the day, and generating real PDF invoices and PPTX analysis decks — entirely through plain-language Telegram messages. No admin panel, no web app. The chat *is* the product.

**Stack:** TypeScript · Next.js · Prisma · PostgreSQL · Vercel AI SDK · Claude Sonnet 5 (prod) / Groq (dev) · Telegram Bot API · pdf-lib · pptxgenjs

**Highlights:**
- Zero keyword/intent routing anywhere — the LLM composes tool calls itself; every business rule (GST math, oversell prevention, stock locking) is enforced at the tool/DB layer, not the prompt
- Row-locked concurrent stock updates (`SELECT ... FOR UPDATE`), idempotent webhook handling, and atomic bill finalization verified with a standalone concurrency test script
- Real generated artifacts: branded GST tax-invoice PDFs with CGST/SGST breakup tables, and PPTX sales-analysis decks with native charts
- Stretch features: voice-note ordering via Whisper transcription, scheduled weekly analysis decks, velocity-based reorder suggestions, khata payment reminders — all cron-driven and auto-sent

🤖 [Try the bot: @StorePilotAIBot](https://t.me/StorePilotAIBot) &nbsp;·&nbsp; 📄 [Project Repo](https://github.com/DevashishSuthar/supermarket-ops-agent)

<br/>

<p><strong>Experimental Projects: </strong></p>
<ul>
    <li>
        <strong>Airbnb Clone App</strong> (Next.js + Typescript + Tailwind CSS):
        <a href="https://airbnb-next-me.vercel.app/" target="_blank">Demo </a>
    </li>
    <li>
        <strong>Hostshare App</strong> (Next.js + Typescript + Tailwind CSS):
        <a href="https://hostshare-next.vercel.app/" target="_blank">Demo </a>
    </li>
    <li>
        <strong>Catstronauts App with GraphQL</strong>:
        <a href="https://catstronauts-react.netlify.app/" target="_blank">Demo </a>
    </li>
    <li>
        <strong>Import Export Excel App</strong> (Loading delays expected due to server deployment on Render.com):
        <a href="https://import-export-excel.vercel.app/" target="_blank">Demo </a>
    </li>
    <li>
        <strong>Family Tree App</strong> (Loading delays expected due to server deployment on Render.com):
        <a href="https://family-tree-mine.vercel.app/" target="_blank">Demo </a>
    </li>
</ul>

<br/>

<!-- ## 📊 GitHub Stats -->

<!-- <p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=DevashishSuthar&show_icons=true&theme=default&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DevashishSuthar&layout=compact&hide_border=true" />
</p> -->

<!-- <br/> -->

<!-- ## 🧰 Tech Stack -->

<h2>Frontend</h2>
<p>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
        <img
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
            alt="javascript"
            height="85" />
    </a>
    &nbsp;&nbsp;
    <a href="https://www.typescriptlang.org/" target="_blank">
      <img
          src="https://www.vectorlogo.zone/logos/typescriptlang/typescriptlang-icon.svg"
          alt="typescript"
          height="85" />
    </a>
    &nbsp;&nbsp;
    <a href="https://reactjs.org/" target="_blank">
        <img 
          src="https://www.vectorlogo.zone/logos/reactjs/reactjs-ar21.svg" 
          alt="react" 
          height="85" /> 
    </a>
    &nbsp;&nbsp;
    <a href="https://nextjs.org/" target="_blank">
        <img
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original-wordmark.svg"
            alt="nextjs"
            height="85" />
    </a>
    &nbsp;&nbsp;
    <a href="https://www.apollographql.com/" target="_blank">
        <img
            src="https://www.vectorlogo.zone/logos/apollographql/apollographql-ar21.svg"
            alt="apollo-graphql"
            height="85" />
    </a>
</p>
<p>
    <a href="https://www.w3.org/html/" target="_blank">
        <img
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg"
            alt="html"
            height="85" />
    </a>
    &nbsp;&nbsp;
    <a href="https://www.w3schools.com/css/" target="_blank">
        <img
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg"
            alt="css"
            height="85" />
    </a>
</p>

<br />

<h2>Backend</h2>
<p>
  <a href="https://nodejs.org" target="_blank">
    <img
      src="https://www.vectorlogo.zone/logos/nodejs/nodejs-ar21.svg"
      alt="nodejs"
      height="85"
    />
  </a>
  &nbsp;&nbsp;
  <a href="https://expressjs.com" target="_blank">
    <img
      src="https://www.vectorlogo.zone/logos/expressjs/expressjs-ar21.svg"
      alt="express"
      height="85"
    /> </a
  >&nbsp;&nbsp;
  <a href="https://socket.io/" target="_blank"
    ><img
      src="https://www.vectorlogo.zone/logos/socketio/socketio-ar21.svg"
      alt="socketio"
      height="85" /></a
  >&nbsp;&nbsp;
  <a href="https://graphql.org/" target="_blank"
    ><img
      src="https://www.vectorlogo.zone/logos/graphql/graphql-ar21.svg"
      alt="graphql"
      height="85" /></a
  >&nbsp;&nbsp;
</p>

<br />

<h2>AI / Agents</h2>
<p>
  <img src="https://img.shields.io/badge/Vercel_AI_SDK-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
</p>

<br />

<h2>Database</h2>
<p>
  <a href="https://www.mongodb.com/" target="_blank">
    <img
      src="https://www.vectorlogo.zone/logos/mongodb/mongodb-ar21.svg"
      alt="mongodb"
      height="85"
    />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.mysql.com/" target="_blank">
    <img
      src="https://www.vectorlogo.zone/logos/mysql/mysql-ar21.svg"
      alt="mysql"
      height="85"
    />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.postgresql.org/" target="_blank"
    ><img
      src="https://www.vectorlogo.zone/logos/postgresql/postgresql-ar21.svg"
      alt="postgresql"
      height="85" /></a
  >&nbsp;&nbsp;
</p>

<br />
<h2>Testing & Tools</h2>
<p>
  <a href="https://jestjs.io/" target="_blank">
    <img
      src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-ar21.svg"
      alt="jest"
      height="85" />
  </a>
  &nbsp;&nbsp;
  <a href="https://git-scm.com/" target="_blank">
    <img
      src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg"
      alt="git"
      height="85"
    />
  </a>
</p>

<br />

<p align="center"><i>Thanks for stopping by — always happy to talk code, AI agents, or motorcycles 🏍️</i></p>
