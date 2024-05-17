<h1 align="center">Nuit de L'Informatique 2022</h1>

The "Nuit de L'Informatique 2022" GitHub project is a backup of the web application developed on December 1 and 2, 2022 from 4:35 PM to 8:00 AM for the contest.

<p align="center">
  <img src="https://github.com/Corentin-Lcs/nuit-de-l-informatique/blob/main/Nuit_De_L'Info.png" alt="Nuit_De_L'Info.png"/>
</p>

## Description

The [Night of Computing](https://nuitdelinfo.com/) is a national competition that brings together around 5 000 students (400 to 500 teams from 100 institutions across 60 locations) from all over France.

The Night takes place every year, from the first Thursday of December at sunset until sunrise the next morning.

Participants have the duration of one night to propose, implement, and package a Web 2.0 application. The project must be related to the national theme, announced at the beginning of the competition.

During this night, partners launch challenges (for example : the most user-friendly web interface, best system architecture, best collaboration, etc.) to the participating teams and offer prizes to the teams that have excelled the most. Participants take on around thirty computer challenges (up to a maximum of 5 per team).

The night is also an opportunity for meetings and discussions with teachers, companies, engineers, and business leaders who come to support the students and even offer them some advice to better meet the challenges.

## Results

The team I was on is called `LopotiCode`. Here are the rewards of our work :

🥇 : [Submit me if you can !](https://www.nuitdelinfo.com/inscription/defis/347) (Company : VIVERIS)

🥉 : [On the quest for the easter egg](https://www.nuitdelinfo.com/inscription/defis/302) (Company : ASI)

## Installation

To set up the project's dependencies, run the following command :

```
npm install
```

## Usage

To compile and hot-reload the project during development, type the following command :

```
npm run dev
```

To compile and minify the project for production, execute the following command :

```
npm run build
```

> This task will create a distribution version of the project inside your local `dist/` folder.

## Further Information

This template should help get you started developing with Vue 3 and Typescript in Vite. The template uses Vue 3 <script setup> SFCs, check out the [script setup docs](https://vuejs.org/api/sfc-script-setup.html) to learn more. The recommended IDE setup is [VSCode](https://code.visualstudio.com/) with [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (disable Vetur) and [TypeScript Vue Plugin](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin). And to configure Vite, consult the [reference](https://vitejs.dev/config/).

## Project's Structure

```
nuit-de-l-informatique/
├─ README.md
├─ LICENSE
├─ Sujet.pdf
├─ Nuit_De_L'Info.png
└─ src/
   ├─ index.html
   ├─ package.json
   ├─ public
   │  └─ favicon.ico
   ├─ src/
   │  ├─ App.vue
   │  ├─ assets/
   │  │  ├─ cap1.png
   │  │  ├─ localStorageManager.js
   │  │  ├─ logo.svg
   │  │  ├─ logo_sida_alternatif.svg
   │  │  ├─ main.css
   │  │  ├─ trooper.png
   │  │  └─ utils.js
   │  ├─ components/
   │  │  ├─ FirstLoader.vue
   │  │  ├─ FirstPart.vue
   │  │  ├─ FourthPart.vue
   │  │  ├─ HomePage.vue
   │  │  ├─ Jauge.vue
   │  │  ├─ Loader.vue
   │  │  ├─ SecondPart.vue
   │  │  ├─ ThirdPart.vue
   │  │  └─ logo/
   │  │     ├─ LogoHomeCatTop.vue
   │  │     ├─ LogoLoPotiChatCapote.vue
   │  │     ├─ LogoLoPotiChatChapoCapote.vue
   │  │     ├─ LogoLoPotiChatFleche.vue
   │  │     ├─ LogoLoPotiChatMain.vue
   │  │     ├─ LogoLoPotiCodeLoupe.vue
   │  │     ├─ LogoSida.vue
   │  │     ├─ LogoWavesBottom.vue
   │  │     ├─ LogoWavesTop.vue
   │  │     └─ logoCapote.vue
   │  └─ main.js
   └─ vite.config.js
```

Named `Sujet.pdf` (Subject.pdf), the file contains the subject of the night 2022.

## Meta

Created by [@Corentin-Lcs](https://github.com/Corentin-Lcs). Feel free to contact me !

Distributed under the GNU GPLv3 license. See [LICENSE](https://github.com/Corentin-Lcs/nuit-de-l-informatique/blob/main/LICENSE) for more information.
