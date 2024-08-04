# Installation :arrow_down:

### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

## <br />

# Getting Started :dart:

### Fork and Clone the repo

To Fork the repo click on the fork button at the top right of the page. Once the repo is forked open your terminal and perform the following commands

```
git clone https://github.com/<YOUR GITHUB USERNAME>/github-portfolio.git

cd github-portfolio
```

### Install packages from the root directory

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

# Usage :joystick:

### Now, you have to customize user data in the `data` [folder](https://github.com/KrishKoria/MySuperAwesomePortfolio/tree/main/data).

Eg:

```javascript
export const userData = {
  githubUser: "KrishKoria",
  devUsername: "KrishKoria",
  github: "https://github.com/KrishKoria",
  linkedIn: "https://www.linkedin.com/in/krishkoria/",
  twitter: "https://x.com/THEINDIANJEWEL1",
  stackOverflow: "https://stackoverflow.com/users/23176530/krish-koria",
  leetcode: "https://leetcode.com/u/krishkoria2004/",
  resume:
    "https://drive.google.com/file/d/1WqwFGzlR7VJnWKshY3uvg8W_ReGGcIW5/view?usp=sharing",
  languages: [
    "C",
    "C++",
    "Java",
    "Python",
    "HTML5",
    "Kotlin",
    "Dart",
    "JavaScript",
    "TypeScript",
    "Sql",
    "R",
  ],
  frameworks: [
    "React",
    "Flutter",
    "NodeJS",
    "ExpressJS",
    "NextJS",
    "TailwindCSS",
    "MaterialUI",
    "Google Cloud Platform",
    "NoSQL",
  ],
  tools: [
    "Android Studio",
    "Postman",
    "Git",
    "GitHub",
    "Heroku",
    "Postman",
    "Docker",
    "Cloudinary",
    "Vercel",
    "AWS",
  ],
  course_work: [
    "Data Structures",
    "Algorithms",
    "Object Oriented Programming",
    "Database Management Systems",
    "Data Analytics",
    "Operating Systems",
    "Computer Networks",
    "Software Engineering",
  ],
  timezone: "5.3",
};
```

---

# Packages Used :package:

|  Used Package List  |
| :-----------------: |
|        next         |
| @next/third-parties |
|     react-icons     |
|        sass         |
|     tailwindcss     |

---
