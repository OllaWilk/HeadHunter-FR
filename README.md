# :construction_worker: HeadHunter MegaK v0.1.0 frontend
Application as a recruitment platform. It connects the graduates of programming school and potential employers. The purpose of the app is to help students find their first job as a developers.

## :bear: Resources

**Github frontend:** https://github.com/Jutrzenka/HeadHunterG11-FR \
**Github backend:** https://github.com/Jutrzenka/HeadHunterG11-BE


## :trophy: Project goals

  1. Create a web application supporting recruitment processes.
  2. Allow students to showcase their skills in a structured way.
  3. Enable HR departments and headhunters to easily search, filter and contact candidates.
  5. Provide administrators with control over access and user management.

## :sparkles: Main features
  
  1. Registration via invitation link – secure access for students (Kursant) and HR.
  2. Student profile – personal data, GitHub, portfolio, work preferences, expected salary, education, work experience, courses.
  3. HR panel – list of available students with search and sorting options.
  4. Conversation list – HR can mark selected students for interviews.
  5. CV view – detailed candidate profile with dynamic data.
  6. Statuses – Available / In conversation / Hired (automatic status updates after 10 days).
  7. PWA support – installable from Chrome & Safari mobile/desktop.

## :framed_picture: Screenshots

**Login view**  
![Login view](public/img/app-overview/HeadHunter_login.png) 

**Student profile**  
![Student dashboard](public/img/app-overview/HeadHunter_sudentprofile.png) 

**Student list (for students)** – adding and editing profile  
![Student list employers](public/img/app-overview/HeadHunter_sudentsLinst_employers.png) 


**Filtering students (for employers)**  
![Filtering students](public/img/app-overview/HeadHunter_sudentsLinstFilter_employers.png)

**Student list (for employers)**  
![Student list for students](public/img/app-overview/HeadHunter_studentsList_studentView.png)

## :cow: Tech Stack
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
## :guardsman: Authors:
**Group members:**
1. [Jutrzenka](https://github.com/Jutrzenka) **Jutrzenka#2251** kacperczaja1999@gmail.com
2. [iwanczakrafal](https://github.com/iwanczakrafal)
3. [madridista5](https://github.com/madridista5)
4. [Marcel998](https://github.com/Marcel998) **Marcel998#5607**
5. [marooonio](https://github.com/marooonio)
6. [NorGoz](https://github.com/NorGoz)
7. [OllaWilk](https://github.com/OllaWilk)
8. [RafalKuchta](https://github.com/RafalKuchta)

**Additional roles in the team:**
- SM: [Jutrzenka](https://github.com/Jutrzenka)
- Author of demo films: [Marcel998](https://github.com/Marcel998)

## :camel: Project structure
```
HeadHunterG11-FR
├── build
├── public
│   ├── img
│   ├── favicon.png
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── src
│   ├── components
│   ├── redux
│   ├── styles
│   ├── utils
│   ├── views
│   ├── App.tsx
│   └── config.env.ts
├── .env
├── .gitignore
├── .npmrc
├── package.json
├── package-lock.json
├── README.md
└── tsconfig.json
```
## :dragon_face: Installation project

**Clone the project:**
```
git clone https://github.com/Jutrzenka/HeadHunterG11-FR.git
```
**Go to the project directory:**
```
cd HeadHunterG11-FR
```
**Install dependencies:**
```
npm install
```
**Start the server:**
```
npm start
```
