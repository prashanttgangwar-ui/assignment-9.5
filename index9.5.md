## 1. Objective

The objective of this assignment is to complete and review the landing page created in Assignment 9.4. The website should be responsive, user-friendly, visually attractive, and ready to showcase in a portfolio.

## 2. Project Structure

Create the following folder structure:

```text
responsive-landing-page/
│
├── index.html
├── style.css
└── images/
    ├── hero.jpg
    ├── feature-1.jpg
    ├── feature-2.jpg
    └── feature-3.jpg
```

## 3. Complete HTML Code

**File: `index.html`**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta
        name="description"
        content="NovaSpace helps teams organize projects, collaborate effectively, and achieve more."
    >

    <meta name="theme-color" content="#0f172a">

    <title>NovaSpace | Build Better Together</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Header and Navigation -->
    <header class="header" id="home">
        <nav class="navbar container" aria-label="Main navigation">

            <a href="#home" class="logo">NovaSpace<span>.</span></a>

            <input
                type="checkbox"
                id="menu-toggle"
                class="menu-toggle"
                aria-label="Toggle navigation menu"
            >

            <label for="menu-toggle" class="menu-icon">
                <span></span>
                <span></span>
                <span></span>
            </label>

            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact" class="nav-button">Get Started</a></li>
            </ul>

        </nav>
    </header>

    <main>

        <!-- Hero Section -->
        <section class="hero">
            <div class="container hero-content">

                <div class="hero-text">
                    <p class="eyebrow">WELCOME TO NOVASPACE</p>

                    <h1>Build Better Ideas. <span>Achieve More.</span></h1>

                    <p class="hero-description">
                        Bring your team, projects, and ideas together in one
                        simple workspace. Work smarter and turn your plans
                        into meaningful results.
                    </p>

                    <div class="hero-buttons">
                        <a href="#contact" class="button button-primary">
                            Get Started
                        </a>

                        <a href="#features" class="button button-secondary">
                            Explore Features
                        </a>
                    </div>

                    <div class="hero-note">
                        Simple workflow. Better collaboration. More progress.
                    </div>
                </div>

                <div class="hero-image">
                    <img
                        src="images/hero.jpg"
                        alt="Team collaborating on a creative project"
                        fetchpriority="high"
                    >
                </div>

            </div>
        </section>

        <!-- Features Section -->
        <section class="features section-padding" id="features">
            <div class="container">

                <div class="section-heading">
                    <p class="eyebrow">WHAT WE OFFER</p>
                    <h2>Everything You Need to Work Smarter</h2>
                    <p>
                        Discover tools that help you organize work,
                        collaborate with your team, and stay productive.
                    </p>
                </div>

                <div class="feature-grid">

                    <article class="feature-card">
                        <img
                            src="images/feature-1.jpg"
                            alt="Organized project planning workspace"
                            loading="lazy"
                        >

                        <div class="card-content">
                            <span class="feature-number">01</span>
                            <h3>Smart Planning</h3>
                            <p>
                                Organize your tasks, set priorities, and
                                manage projects with a clear plan.
                            </p>
                            <a href="#contact" class="text-link">
                                Learn More &rarr;
                            </a>
                        </div>
                    </article>

                    <article class="feature-card">
                        <img
                            src="images/feature-2.jpg"
                            alt="Team members working together"
                            loading="lazy"
                        >

                        <div class="card-content">
                            <span class="feature-number">02</span>
                            <h3>Team Collaboration</h3>
                            <p>
                                Share ideas, communicate clearly, and
                                keep everyone moving in the same direction.
                            </p>
                            <a href="#contact" class="text-link">
                                Learn More &rarr;
                            </a>
                        </div>
                    </article>

                    <article class="feature-card">
                        <img
                            src="images/feature-3.jpg"
                            alt="Productivity dashboard on a computer"
                            loading="lazy"
                        >

                        <div class="card-content">
                            <span class="feature-number">03</span>
                            <h3>Track Progress</h3>
                            <p>
                                Monitor milestones, review progress, and
                                make informed decisions for your projects.
                            </p>
                            <a href="#contact" class="text-link">
                                Learn More &rarr;
                            </a>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <!-- About Section -->
        <section class="about section-padding" id="about">
            <div class="container about-content">

                <div class="about-image">
                    <img
                        src="images/feature-2.jpg"
                        alt="People collaborating and sharing ideas"
                        loading="lazy"
                    >
                </div>

                <div class="about-text">
                    <p class="eyebrow">ABOUT NOVASPACE</p>

                    <h2>A Better Way to Bring Ideas to Life</h2>

                    <p>
                        NovaSpace is a sample digital workspace landing page
                        designed to demonstrate modern web development
                        practices and responsive user interface design.
                    </p>

                    <p>
                        Our goal is to present information clearly across
                        desktop, tablet, and mobile devices while keeping
                        navigation simple and the layout consistent.
                    </p>

                    <a href="#contact" class="button button-primary">
                        Join Our Community
                    </a>
                </div>

            </div>
        </section>

        <!-- Call to Action -->
        <section class="cta section-padding" id="contact">
            <div class="container cta-content">
                <p class="eyebrow">START SOMETHING GREAT</p>

                <h2>Ready to Turn Your Ideas into Action?</h2>

                <p>
                    Take the next step and discover a smarter way to organize
                    your work and collaborate with others.
                </p>

                <a href="mailto:hello@example.com" class="button button-light">
                    Contact Us
                </a>

                <p class="contact-note">
                    Demo contact: hello@example.com
                </p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="footer">
        <div class="container footer-content">

            <a href="#home" class="logo footer-logo">
                NovaSpace<span>.</span>
            </a>

            <p>
                &copy; 2026 NovaSpace. Created as a responsive web
                development project.
            </p>

            <a href="#home" class="back-to-top">Back to Top &uarr;</a>

        </div>
    </footer>

</body>
</html>
```

## 4. Complete Responsive CSS Code

**File: `style.css`**

```css
/* ==============================
   1. Global Styles
============================== */

:root {
    --primary: #6366f1;
    --primary-dark: #4f46e5;
    --dark: #0f172a;
    --text: #475569;
    --light: #f8fafc;
    --white: #ffffff;
    --border: #e2e8f0;
    --radius: 18px;
    --shadow: 0 12px 35px rgba(15, 23, 42, 0.08);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    color: var(--dark);
    background-color: var(--white);
    line-height: 1.7;
    overflow-wrap: break-word;
}

img {
    display: block;
    width: 100%;
    max-width: 100%;
    height: auto;
    object-fit: cover;
}

a {
    color: inherit;
    text-decoration: none;
}

button,
input {
    font: inherit;
}

.container {
    width: min(1120px, calc(100% - 48px));
    margin-inline: auto;
}

.section-padding {
    padding-block: 90px;
}

.eyebrow {
    color: var(--primary);
    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 2px;
    margin-bottom: 14px;
}

h1,
h2,
h3 {
    line-height: 1.2;
}

h2 {
    font-size: clamp(1.8rem, 3.5vw, 2.7rem);
    letter-spacing: -1px;
}

p {
    color: var(--text);
}

a:focus-visible,
input:focus-visible,
label:focus-visible {
    outline: 3px solid #a5b4fc;
    outline-offset: 4px;
}

.button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-height: 48px;
    padding: 12px 24px;
    border: 2px solid transparent;
    border-radius: 8px;
    font-weight: 700;
    text-align: center;
    transition:
        background-color 0.2s ease,
        color 0.2s ease,
        transform 0.2s ease;
}

.button:hover {
    transform: translateY(-2px);
}

.button-primary {
    color: var(--white);
    background-color: var(--primary);
}

.button-primary:hover {
    background-color: var(--primary-dark);
}

.button-secondary {
    color: var(--dark);
    background-color: var(--white);
    border-color: var(--border);
}

.button-secondary:hover {
    border-color: var(--primary);
    color: var(--primary);
}


/* ==============================
   2. Header and Navigation
============================== */

.header {
    position: sticky;
    top: 0;
    z-index: 1000;
    background-color: rgba(255, 255, 255, 0.97);
    border-bottom: 1px solid var(--border);
}

.navbar {
    min-height: 76px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 24px;
}

.logo {
    font-size: 1.65rem;
    font-weight: 800;
    letter-spacing: -1px;
    white-space: nowrap;
}

.logo span {
    color: var(--primary);
}

.nav-links {
    display: flex;
    align-items: center;
    gap: 30px;
    list-style: none;
}

.nav-links a {
    font-size: 0.95rem;
    font-weight: 600;
    transition: color 0.2s ease;
}

.nav-links a:hover {
    color: var(--primary);
}

.nav-links .nav-button {
    padding: 11px 18px;
    border-radius: 8px;
    color: var(--white);
    background-color: var(--primary);
}

.nav-links .nav-button:hover {
    color: var(--white);
    background-color: var(--primary-dark);
}

.menu-toggle,
.menu-icon {
    display: none;
}


/* ==============================
   3. Hero Section
============================== */

.hero {
    padding-block: 80px;
    background:
        radial-gradient(
            circle at top right,
            #eef2ff 0,
            transparent 42%
        ),
        var(--light);
}

.hero-content {
    display: grid;
    grid-template-columns: 1fr 0.9fr;
    align-items: center;
    gap: 60px;
}

.hero-text h1 {
    max-width: 650px;
    margin-bottom: 22px;
    font-size: clamp(2.5rem, 5vw, 4.3rem);
    letter-spacing: -2.5px;
}

.hero-text h1 span {
    color: var(--primary);
}

.hero-description {
    max-width: 540px;
    margin-bottom: 28px;
    font-size: 1.08rem;
}

.hero-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 14px;
}

.hero-note {
    margin-top: 24px;
    color: #64748b;
    font-size: 0.9rem;
}

.hero-image img {
    aspect-ratio: 4 / 3;
    border-radius: var(--radius);
    box-shadow: var(--shadow);
}


/* ==============================
   4. Features Section
============================== */

.features {
    background-color: var(--white);
}

.section-heading {
    max-width: 680px;
    margin: 0 auto 48px;
    text-align: center;
}

.section-heading h2 {
    margin-bottom: 16px;
}

.section-heading > p:last-child {
    max-width: 600px;
    margin-inline: auto;
}

.feature-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 28px;
}

.feature-card {
    min-width: 0;
    overflow: hidden;
    border: 1px solid var(--border);
    border-radius: var(--radius);
    background-color: var(--white);
    transition:
        transform 0.25s ease,
        box-shadow 0.25s ease;
}

.feature-card:hover {
    transform: translateY(-6px);
    box-shadow: var(--shadow);
}

.feature-card > img {
    aspect-ratio: 16 / 10;
}

.card-content {
    padding: 25px;
}

.feature-number {
    color: var(--primary);
    font-size: 0.85rem;
    font-weight: 800;
}

.card-content h3 {
    margin-block: 10px;
    font-size: 1.3rem;
}

.card-content p {
    margin-bottom: 18px;
}

.text-link {
    color: var(--primary);
    font-weight: 700;
}

.text-link:hover {
    color: var(--primary-dark);
}


/* ==============================
   5. About Section
============================== */

.about {
    background-color: var(--light);
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    gap: 60px;
}

.about-image img {
    aspect-ratio: 5 / 4;
    border-radius: var(--radius);
    box-shadow: var(--shadow);
}

.about-text h2 {
    margin-bottom: 20px;
}

.about-text p {
    margin-bottom: 18px;
}

.about-text .button {
    margin-top: 8px;
}


/* ==============================
   6. Call to Action
============================== */

.cta {
    color: var(--white);
    background: linear-gradient(135deg, #4f46e5, #7c3aed);
}

.cta-content {
    max-width: 760px;
    text-align: center;
}

.cta .eyebrow {
    color: #ddd6fe;
}

.cta h2 {
    margin-bottom: 18px;
    color: var(--white);
}

.cta-content > p:not(.eyebrow, .contact-note) {
    max-width: 600px;
    margin: 0 auto 28px;
    color: #ede9fe;
}

.button-light {
    color: var(--primary-dark);
    background-color: var(--white);
}

.button-light:hover {
    background-color: #eef2ff;
}

.contact-note {
    margin-top: 16px;
    color: #ede9fe;
    font-size: 0.85rem;
}


/* ==============================
   7. Footer
============================== */

.footer {
    padding-block: 28px;
    background-color: var(--dark);
}

.footer-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 24px;
}

.footer-logo {
    color: var(--white);
}

.footer-content p {
    color: #cbd5e1;
    font-size: 0.85rem;
    text-align: center;
}

.back-to-top {
    color: var(--white);
    font-size: 0.9rem;
    font-weight: 600;
    white-space: nowrap;
}

.back-to-top:hover {
    color: #c7d2fe;
}


/* ==============================
   8. Tablet Breakpoint
   Screens up to 900px
============================== */

@media (max-width: 900px) {
    .section-padding {
        padding-block: 70px;
    }

    .hero {
        padding-block: 60px;
    }

    .hero-content {
        grid-template-columns: 1fr 0.85fr;
        gap: 32px;
    }

    .hero-text h1 {
        font-size: clamp(2.2rem, 5vw, 3.3rem);
    }

    .feature-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 22px;
    }

    .about-content {
        gap: 35px;
    }

    .nav-links {
        gap: 18px;
    }

    .footer-content {
        flex-wrap: wrap;
    }
}


/* ==============================
   9. Mobile Navigation and Layout
   Screens up to 650px
============================== */

@media (max-width: 650px) {
    .container {
        width: min(100% - 32px, 500px);
    }

    .section-padding {
        padding-block: 55px;
    }

    .navbar {
        position: relative;
        min-height: 68px;
        flex-wrap: wrap;
    }

    .logo {
        font-size: 1.45rem;
    }

    .menu-icon {
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 5px;
        width: 44px;
        height: 44px;
        padding: 10px;
        border: 1px solid var(--border);
        border-radius: 8px;
        cursor: pointer;
    }

    .menu-icon span {
        display: block;
        width: 100%;
        height: 2px;
        border-radius: 2px;
        background-color: var(--dark);
    }

    .menu-toggle:focus-visible + .menu-icon {
        outline: 3px solid #a5b4fc;
        outline-offset: 3px;
    }

    .menu-toggle:checked + .menu-icon {
        background-color: #eef2ff;
    }

    .nav-links {
        display: none;
        flex-basis: 100%;
        flex-direction: column;
        align-items: stretch;
        gap: 0;
        padding: 8px 0 18px;
    }

    .menu-toggle:checked ~ .nav-links {
        display: flex;
    }

    .nav-links li a {
        display: block;
        padding: 12px 10px;
    }

    .nav-links .nav-button {
        margin-top: 8px;
        text-align: center;
    }

    .hero {
        padding-block: 48px;
    }

    .hero-content {
        grid-template-columns: 1fr;
        gap: 32px;
    }

    .hero-text h1 {
        font-size: clamp(2.2rem, 10vw, 3.2rem);
        letter-spacing: -1.5px;
    }

    .hero-description {
        font-size: 1rem;
    }

    .hero-buttons {
        align-items: stretch;
        flex-direction: column;
    }

    .hero-buttons .button {
        width: 100%;
    }

    .hero-image img {
        aspect-ratio: 4 / 3;
    }

    .section-heading {
        margin-bottom: 32px;
        text-align: left;
    }

    .feature-grid {
        grid-template-columns: 1fr;
        gap: 22px;
    }

    .card-content {
        padding: 22px;
    }

    .about-content {
        grid-template-columns: 1fr;
        gap: 30px;
    }

    .about-text h2,
    .section-heading h2,
    .cta h2 {
        font-size: clamp(1.8rem, 7vw, 2.4rem);
    }

    .cta-content {
        text-align: center;
    }

    .footer-content {
        flex-direction: column;
        text-align: center;
        gap: 14px;
    }

    .footer-content p {
        max-width: 320px;
    }
}


/* ==============================
   10. Extra Small Screens
   Screens up to 380px
============================== */

@media (max-width: 380px) {
    .container {
        width: calc(100% - 24px);
    }

    .hero-text h1 {
        font-size: 2rem;
    }

    .button {
        padding: 11px 16px;
        font-size: 0.9rem;
    }

    .card-content {
        padding: 18px;
    }

    .section-padding {
        padding-block: 45px;
    }
}


/* ==============================
   11. Reduced Motion Accessibility
============================== */

@media (prefers-reduced-motion: reduce) {
    *,
    *::before,
    *::after {
        scroll-behavior: auto !important;
        transition-duration: 0.01ms !important;
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
    }
}
```

## 5. Images Setup

Download four suitable, royalty-free images from Unsplash or another image source that permits your intended use.

Save them with these exact filenames:

- `hero.jpg`
- `feature-1.jpg`
- `feature-2.jpg`
- `feature-3.jpg`

Place all four files inside the `images` folder.

The project expects local image files, so the page will show broken images until the files are added with the correct names and extensions.

## 6. Responsive Breakpoints

| Screen Size | Layout |
|---|---|
| Desktop: above 900px | Two-column hero, three-column feature cards |
| Tablet: 651–900px | Compact hero, two-column feature cards |
| Mobile: up to 650px | Single-column content, collapsible navigation |
| Small mobile: up to 380px | Reduced padding and typography |

The CSS uses Grid, Flexbox, `clamp()`, `minmax()`, and flexible container widths to help prevent overlapping and horizontal scrolling.

## 7. Button and Link Functionality

The following features are implemented:

1. The NovaSpace logo links to the Home section.
2. Navigation links move to Home, Features, About, and Contact.
3. The Get Started buttons navigate to the Contact section.
4. Explore Features opens the Features section.
5. Learn More links navigate to the Contact section.
6. Contact Us opens the user's default email application using `mailto:hello@example.com`.
7. Back to Top returns to the top of the page.
8. The mobile menu opens and closes using the checkbox and label.

**Important:** Replace `hello@example.com` with a real contact email address if this page will be published as an actual business website. The current email is only a demo address.

## 8. Testing with Chrome DevTools

Open `index.html` in Chrome using the Live Server extension in VS Code.

Follow these steps:

1. Open the webpage in Chrome.
2. Right-click the page and select **Inspect**.
3. Click the **Toggle device toolbar** icon, or press `Ctrl + Shift + M`.
4. Test the page at these viewport sizes:
   - 1440 × 900 — Desktop
   - 1024 × 768 — Small desktop/tablet
   - 768 × 1024 — Tablet
   - 390 × 844 — Mobile
   - 320 × 568 — Small mobile
5. Refresh the page at each size.
6. Test every navigation link and button.
7. Open and close the mobile navigation menu.
8. Check that images load and maintain their proportions.
9. Check the browser console for errors.
10. Check that the page does not scroll horizontally.

## 9. Final Review Checklist

- [ ] Header and navigation work correctly.
- [ ] Mobile navigation opens and closes.
- [ ] Hero section adjusts to all screen sizes.
- [ ] Feature cards display in responsive columns.
- [ ] About and Contact sections fit small screens.
- [ ] Images load without broken-image icons.
- [ ] Text remains readable on desktop, tablet, and mobile.
- [ ] Buttons and internal links work correctly.
- [ ] No horizontal scrolling appears at the tested widths.
- [ ] No overlapping text or content is visible.
- [ ] HTML and CSS are properly formatted.
- [ ] Browser console has no project-related errors.
- [ ] Desktop, tablet, and mobile screenshots are captured.
- [ ] Final changes are pushed to GitHub.

## 10. Capture Screenshots

Capture at least three screenshots using Chrome DevTools:

**Screenshot 1 — Desktop**

- Set the viewport to 1440 × 900.
- Show the hero section and navigation.
- Save as `desktop.png`.

**Screenshot 2 — Tablet**

- Set the viewport to 768 × 1024.
- Show the responsive layout.
- Save as `tablet.png`.

**Screenshot 3 — Mobile**

- Set the viewport to 390 × 844.
- Show the mobile layout and navigation.
- Save as `mobile.png`.

Create a `screenshots` folder to organize the images:

```text
responsive-landing-page/
├── index.html
├── style.css
├── images/
└── screenshots/
    ├── desktop.png
    ├── tablet.png
    └── mobile.png
```

These screenshots must be captured from the actual running website; they are not generated automatically by the code.

## 11. Push Final Changes to GitHub

Open the project folder in VS Code and open its terminal.

Run the following commands:

```bash
git add .
git commit -m "Complete responsive landing page review"
git push
```

If GitHub has not been connected to the local project yet, create a repository on GitHub and follow these commands, replacing `YOUR_USERNAME` with your GitHub username:

```bash
git init
git add .
git commit -m "Build responsive landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/responsive-landing-page.git
git push -u origin main
```

If the remote repository is already configured, do not run `git remote add origin` again. Use the first three commands to commit and push your latest changes.

After pushing, open the repository on GitHub and confirm that `index.html`, `style.css`, and the image files are present.

## 12. Submission Details

**Assignment Name:** Assignment 9.5 — Responsive Landing Page: Finish & Review

**Project Name:** NovaSpace Responsive Landing Page

**Technologies Used:**
- HTML5
- CSS3
- CSS Grid
- Flexbox
- Media Queries
- Chrome DevTools
- Git and GitHub

**Files to Submit:**
1. Complete responsive landing page source code.
2. `desktop.png` screenshot.
3. `tablet.png` screenshot.
4. `mobile.png` screenshot.
5. GitHub repository URL.

