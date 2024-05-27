# GitHub Portfolio

### If you're struggling to create a portfolio website that looks professional, you don't have to search any further. You can use this GitHub Portfolio template to create your very own personalized portfolio using just your GitHub username! The website is designed to be user-friendly and easily customizable, which makes it an ideal solution for developers and freelancers alike.

---

# Demo :movie_camera:

![httpsgithub dharam_gfx](https://raw.githubusercontent.com/dharam-gfx/github-portfolio/main/public/git.jpeg)

## View live preview [here](https://dharam-gfx.netlify.app/)

---

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

If you want to use Google Analytics, Please create a new `.env` file from `.env.example` file and provide the value.

Eg:

```env
NEXT_PUBLIC_GTM = ""
```

### Now, you have to customize user data in the `data` [folder](https://github.com/dharam-gfx/github-portfolio/blob/main/data/user-data.js).

Eg:

```javascript
export const userData = {
  githubUser: "dharam-gfx",
  devUsername: "dharam-gfx",
  github: "https://github.com/dharam-gfx",
  facebook: "https://facebook.com/dharam01.official",
  linkedIn: "https://www.linkedin.com/in/dharmendra-kumar-a588a4119/",
  twitter: "https://twitter.com/dharam_gfx",
  stackOverflow: "https://stackoverflow.com/users/24954262/dharmendra-kumar",
  leetcode: "https://leetcode.com/u/dharam-gfx/",
  resume: "#",
  skills: [
    "React",
    "NextJS",
    "Redux",
    "Express",
    "NestJS",
    "MySql",
    "MongoDB",
    "Vue",
    "Adobe Photoshop",
    "Premiere Pro",
  ],
  timezone: "+6",
};
```

---

---

# Packages Used :package:

|   Used Package List   |
| :-------------------: |
|         next          |
|  @next/third-parties  |
|         axios         |
|      react-icons      |
| react-github-calendar |
|         sass          |
|      tailwindcss      |

---

## Disclaimer

I have used some figma degin in this repository. All of the credit goes to the degin owners.
