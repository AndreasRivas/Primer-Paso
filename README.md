# Primer Paso

**Primer Paso** is a web platform concept designed to help young people and first-time job seekers take their first steps into the world of work, even if they have little or no previous professional experience.

The project brings job-search resources and career preparation tools together in one place.

## Features

- **Job search:** Browse sample job opportunities and use search filters and sorting options.
- **CV builder:** Create a resume step by step, preview it, and print or save it as a PDF.
- **Account demo:** Register, sign in, and manage a local user profile.
- **Interview preparation:** Practice with interview questions and save practice responses.
- **Saved opportunities:** Keep track of jobs of interest during the current browser session.
- **Career resources:** Access guidance intended to support applicants starting their careers.

## Getting Started

This is a frontend project. You can run it locally without installing a backend.

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` with the Live Server extension, or use another local static web server.
4. Explore the pages and try the CV builder, job search, and interview preparation tools.

You can also visit the published site:

**[Open Primer Paso](https://andreasrivas.github.io/Primer-Paso/)**

## Built With

- HTML
- CSS
- JavaScript
- Browser `localStorage` for demonstration data

## Project Structure

Some of the main files are:

- `index.html` — Main landing page.
- `auth.html` / `auth.js` — Demo registration and sign-in.
- `cv.html` / `cv.js` — Step-by-step CV builder.
- `empleos.html` / `empleos.js` — Job listings and search.
- `entrevista.html` / `entrevista.js` — Interview practice.
- `styles.css`, `app.css`, and `empleos.css` — Page styles.

## Important Notes

This version is a frontend demonstration, not a production employment service.

- Demo accounts, profiles, CV information, and other user data are stored locally in the browser. There is no production backend, secure authentication system, or central database.
- Job listings and company information are sample content and are not verified vacancies.
- The Apply action records interest locally; it does not submit an application to an employer.
- Do not use real or sensitive passwords in this demo.

A production release would require secure authentication, a database, verified employers and job listings, and a real application/contact workflow.

## Future Improvements

- Add a secure backend and database.
- Provide employer accounts and verified job postings.
- Enable real applications and confirmed employer contact information.
- Add secure account recovery and persistent CV storage.

## Author

Developed as a learning project by **Andrea Rivas**.
