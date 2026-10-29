# Kiya Yilma | Personal Website

A six-page personal portfolio website built with **pure HTML5**, with no CSS and no JavaScript. It was created as a university web development lab project and shows semantic markup, multimedia embedding, tables, and validated forms.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Pages](#pages)
- [Features](#features)
- [HTML Concepts Demonstrated](#html-concepts-demonstrated)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Troubleshooting](#troubleshooting)
- [Roadmap](#roadmap)
- [Author](#author)

---

## About the Project

This website introduces **Kiya Yilma**, a Software Engineering student at Addis Ababa Science and Technology University (AASTU) with a strong interest in **AWS, DevOps, and software engineering**.

The site covers background, skills, projects, media, and contact details across six interconnected pages that share one navigation menu.

> _"Small steps taken consistently lead to meaningful progress. No excuse days."_

---

## Pages

| #   | Page                    | File            | Description                                                                         |
| --- | ----------------------- | --------------- | ----------------------------------------------------------------------------------- |
| 1   | Home                    | `index.html`    | Welcome message, profile photo, goals, and personal motto                           |
| 2   | About Me                | `about.html`    | Biography, values, interests, and a quotation                                       |
| 3   | Skills & Education      | `skills.html`   | Education and skills tables, progress indicators, key concepts, and a learning plan |
| 4   | Projects & Achievements | `projects.html` | Project figures, nested lists, achievements, and a downloadable resume              |
| 5   | Media & Interests       | `media.html`    | Audio player, video player, embedded YouTube video, and learning resources          |
| 6   | Contact Me              | `contact.html`  | Contact details and a validated message form                                        |

---

## Features

- Six pages linked by a consistent navigation menu
- Semantic HTML5 layout (`header`, `nav`, `main`, `section`, `footer`)
- Local audio and video playback
- Embedded YouTube video
- Accessible images with descriptive `alt` text
- Contact form with built-in browser validation
- Downloadable resume (PDF)
- External learning resources that open in a new tab

---

## HTML Concepts Demonstrated

| Category    | Elements / Attributes                                                                       |
| ----------- | ------------------------------------------------------------------------------------------- |
| Structure   | `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`                                      |
| Text        | `<blockquote>`, `<abbr>`, `<time>`, `<strong>`, `<em>`, `<code>`                            |
| Lists       | `<ul>`, `<ol>`, nested lists, `<dl>` / `<dt>` / `<dd>`                                      |
| Media       | `<img>`, `<figure>`, `<figcaption>`, `<audio>`, `<video>`, `<iframe>`                       |
| Tables      | `<table>`, `<thead>`, `<tbody>`, `<th>`, `<td>`                                             |
| Interactive | `<details>`, `<summary>`, `<progress>`, `<meter>`                                           |
| Forms       | `<form>`, `<fieldset>`, `<legend>`, `<label>`, `<input>`, `<select>`, `<textarea>`          |
| Validation  | `required`, `minlength`, `maxlength`, `pattern`, `min`, `max`, `type="email"`, `type="url"` |
| Links       | Internal links, `target="_blank"`, `mailto:`, `tel:`, `download`                            |

---

## Project Structure

```text
my-website/
│
├── index.html          # Home
├── about.html          # About Me
├── skills.html         # Skills & Education
├── projects.html       # Projects & Achievements
├── media.html          # Media & Interests
├── contact.html        # Contact Me
├── README.md           # Project documentation
│
├── images/
│   ├── profile.webp    # Profile photo
│   ├── project1.jpg    # Project 1 screenshot
│   └── project2.jpg    # Project 2 screenshot
│
├── audio/
│   └── favorite.mp3    # Favourite music
│
├── videos/
│   └── myvideo.mp4     # Personal video
│
└── files/
    └── resume.pdf      # Downloadable resume
```

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, or Safari)
- [Visual Studio Code](https://code.visualstudio.com/) (recommended)
- The [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension (recommended)

### Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/kiyayilma-dev/my-website.git
   ```

   _(Replace the URL with your actual repository link.)_

2. **Open the folder in VS Code**

   ```bash
   cd my-website
   code .
   ```

3. **Launch the site**
   - Right-click `index.html` and choose **Open with Live Server**, or
   - Double-click `index.html` to open it directly in your browser.

### Testing Checklist

- [ ] Every navigation link works on all six pages
- [ ] Profile and project images load
- [ ] Audio and video players play
- [ ] YouTube video loads (internet required)
- [ ] Contact form blocks empty or invalid submissions
- [ ] Resume download link works

---

## Troubleshooting

| Problem                                    | Solution                                                                                                                 |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| Image shows a broken icon                  | Check that the file name and extension match the `src` in the HTML, for example `profile.webp`                           |
| Audio or video does not play               | Confirm the files are named `favorite.mp3` and `myvideo.mp4` and sit in `audio/` and `videos/`                           |
| YouTube shows an error (such as Error 153) | Run the site through **Live Server** instead of opening the file directly. Also confirm the video owner allows embedding |
| Resume does not download                   | Make sure `resume.pdf` exists inside the `files/` folder                                                                 |
| Links open blank pages                     | Make sure all six `.html` files exist in the root folder                                                                 |

---

## Roadmap

- [ ] Add CSS for styling and a responsive layout
- [ ] Add JavaScript for interactivity
- [ ] Connect the contact form to a backend or form service
- [ ] Deploy to the cloud (AWS S3 static hosting)
- [ ] Add a dark mode toggle

---

## Author

**Kiya Yilma**
Software Engineering Student, Addis Ababa Science and Technology University (AASTU)

- Email: [kiyayilma1@gmail.com](mailto:kiyayilma1@gmail.com)
- LinkedIn: [linkedin.com/in/kiya-yilma-61a301302](https://www.linkedin.com/in/kiya-yilma-61a301302)
- GitHub: [github.com/kiyayilma-dev](https://github.com/kiyayilma-dev)

---

<p align="center">
  Built with HTML5 &nbsp;|&nbsp; No excuse days
</p>
