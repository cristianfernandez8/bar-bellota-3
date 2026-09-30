```css
/* =========================================================
   BAR BELLOTA
   Premium / Elegant / Warm
   ========================================================= */

:root {
    --black: #171512;
    --black-soft: #211e19;
    --cream: #f4efe5;
    --cream-light: #faf8f3;
    --gold: #b89555;
    --gold-light: #d3b77d;
    --white: #ffffff;
    --text: #28251f;
    --muted: #777067;
    --border: rgba(23, 21, 18, 0.14);

    --font-display: "Playfair Display", Georgia, serif;
    --font-body: "DM Sans", Arial, sans-serif;

    --container: 1180px;
    --radius: 2px;
    --transition: 0.3s ease;
}

/* =========================================================
   RESET
   ========================================================= */

*,
*::before,
*::after {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    margin: 0;
    background: var(--cream-light);
    color: var(--text);
    font-family: var(--font-body);
    font-size: 16px;
    line-height: 1.7;
    -webkit-font-smoothing: antialiased;
}

img {
    max-width: 100%;
    display: block;
}

a {
    color: inherit;
    text-decoration: none;
}

button,
a {
    -webkit-tap-highlight-color: transparent;
}

button {
    font: inherit;
}

::selection {
    background: var(--gold);
    color: var(--black);
}

/* =========================================================
   LAYOUT
   ========================================================= */

.container {
    width: min(100% - 40px, var(--container));
    margin-inline: auto;
}

/* =========================================================
   TYPOGRAPHY
   ========================================================= */

h1,
h2,
h3,
h4,
p {
    margin-top: 0;
}

h1,
h2,
h3 {
    font-family: var(--font-display);
    font-weight: 500;
}

h1 {
    margin-bottom: 28px;
    color: var(--white);
    font-size: clamp(3.2rem, 8vw, 7.5rem);
    line-height: 0.94;
    letter-spacing: -0.045em;
}

h2 {
    margin-bottom: 30px;
    font-size: clamp(2.8rem, 6vw, 5.5rem);
    line-height: 0.98;
    letter-spacing: -0.035em;
}

h3 {
    font-size: 1.25rem;
    letter-spacing: 0.04em;
}

.eyebrow {
    margin-bottom: 22px;
    color: var(--gold);
    font-family: var(--font-body);
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0.22em;
    text-transform: uppercase;
}

/* =========================================================
   BUTTONS
   ========================================================= */

.button {
    display: inline-flex;
    min-height: 54px;
    align-items: center;
    justify-content: center;
    padding: 0 28px;
    border: 1px solid transparent;
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    transition:
        transform var(--transition),
        background var(--transition),
        color var(--transition),
        border-color var(--transition);
}

.button:hover {
    transform: translateY(-3px);
}

.button-light {
    background: var(--cream);
    color: var(--black);
}

.button-light:hover {
    background: var(--white);
}

.button-outline {
    border-color: rgba(255, 255, 255, 0.45);
    color: var(--white);
}

.button-outline:hover {
    border-color: var(--white);
    background: rgba(255, 255, 255, 0.08);
}

.button-dark {
    background: var(--black);
    color: var(--cream);
}

.button-dark:hover {
    background: var(--gold);
    color: var(--black);
}

.button-outline-dark {
    border-color: var(--black);
    color: var(--black);
}

.button-outline-dark:hover {
    background: var(--black);
    color: var(--cream);
}

/* =========================================================
   HEADER
   ========================================================= */

.site-header {
    position: fixed;
    z-index: 1000;
    top: 0;
    left: 0;
    width: 100%;
    border-bottom: 1px solid rgba(255, 255, 255, 0.12);
    background: rgba(23, 21, 18, 0.72);
    backdrop-filter: blur(16px);
    -webkit-backdrop-filter: blur(16px);
}

.header-inner {
    min-height: 82px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 30px;
}

.brand {
    display: flex;
    flex-direction: column;
    line-height: 1;
}

.brand-name {
    color: var(--white);
    font-family: var(--font-display);
    font-size: 1.65rem;
    letter-spacing: 0.12em;
}

.brand-subtitle {
    margin-top: 7px;
    color: var(--gold-light);
    font-size: 0.54rem;
    font-weight: 700;
    letter-spacing: 0.22em;
}

.main-nav {
    display: flex;
    align-items: center;
    gap: 34px;
    margin-left: auto;
}

.main-nav a {
    position: relative;
    color: rgba(255, 255, 255, 0.84);
    font-size: 0.7rem;
    font-weight: 600;
    letter-spacing: 0.13em;
    text-transform: uppercase;
}

.main-nav a::after {
    position: absolute;
    right: 0;
    bottom: -8px;
    left: 0;
    height: 1px;
    background: var(--gold);
    content: "";
    transform: scaleX(0);
    transform-origin: center;
    transition: transform var(--transition);
}

.main-nav a:hover {
    color: var(--white);
}

.main-nav a:hover::after {
    transform: scaleX(1);
}

.header-call {
    display: inline-flex;
    min-height: 42px;
    align-items: center;
    padding: 0 17px;
    border: 1px solid var(--gold);
    color: var(--gold-light);
    font-size: 0.66rem;
    font-weight: 700;
    letter-spacing: 0.13em;
}

.header-call:hover {
    background: var(--gold);
    color: var(--black);
}

.menu-toggle {
    display: none;
    width: 44px;
    height: 44px;
    padding: 10px;
    border: 0;
    background: transparent;
    cursor: pointer;
}

.menu-toggle span {
    display: block;
    height: 1px;
    margin: 6px 0;
    background: var(--white);
}

/* =========================================================
   HERO
   ========================================================= */

.hero {
    position: relative;
    min-height: 100vh;
    display: flex;
    align-items: center;
    overflow: hidden;
    background:
        linear-gradient(
            90deg,
            rgba(15, 13, 11, 0.96) 0%,
            rgba(15, 13, 11, 0.78) 45%,
            rgba(15, 13, 11, 0.56) 100%
        ),
        radial-gradient(
            circle at 78% 45%,
            rgba(184, 149, 85, 0.26),
            transparent 32%
        ),
        linear-gradient(
            135deg,
            #171512 0%,
            #332c21 50%,
            #171512 100%
        );
}

.hero::before {
    position: absolute;
    top: 15%;
    right: 7%;
    width: min(36vw, 540px);
    height: min(36vw, 540px);
    border: 1px solid rgba(184, 149, 85, 0.28);
    border-radius: 50%;
    content: "";
    box-shadow:
        0 0 0 40px rgba(184, 149, 85, 0.035),
        0 0 0 80px rgba(184, 149, 85, 0.025);
}

.hero::after {
    position: absolute;
    top: 0;
    right: 16%;
    bottom: 0;
    width: 1px;
    background: linear-gradient(
        transparent,
        rgba(184, 149, 85, 0.4),
        transparent
    );
    content: "";
}

.hero-inner {
    position: relative;
    z-index: 1;
    padding-top: 100px;
    padding-bottom: 80px;
}

.hero-text {
    max-width: 610px;
    margin-bottom: 38px;
    color: rgba(255, 255, 255, 0.75);
    font-size: clamp(1rem, 1.5vw, 1.2rem);
}

.hero-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 14px;
}

/* =========================================================
   GENERAL SECTIONS
   ========================================================= */

.section {
    padding: 130px 0;
}

.section-heading {
    max-width: 700px;
    margin-bottom: 65px;
}

.section-heading h2 {
    color: var(--black);
}

/* =========================================================
   EL BAR
   ========================================================= */

.section-bar {
    background: var(--cream-light);
}

.section-bar .container {
    display: grid;
    grid-template-columns: 0.9fr 1.1fr;
    gap: 100px;
    align-items: start;
}

.section-content {
    padding-top: 45px;
}

.section-content .lead {
    margin-bottom: 25px;
    font-family: var(--font-display);
    font-size: clamp(1.5rem, 2.5vw, 2.1rem);
    line-height: 1.25;
}

.section-content > p:not(.lead) {
    max-width: 600px;
    color: var(--muted);
}

blockquote {
    max-width: 550px;
    margin: 55px 0 0;
    padding: 25px 0 25px 28px;
    border-left: 2px solid var(--gold);
    color: var(--black);
    font-family: var(--font-display);
    font-size: 1.45rem;
    font-style: italic;
    line-height: 1.45;
}

/* =========================================================
   EXPERIENCE
   ========================================================= */

.section-experience {
    background: var(--black);
    color: var(--cream);
}

.experience-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    border-top: 1px solid rgba(255, 255, 255, 0.16);
    border-bottom: 1px solid rgba(255, 255, 255, 0.16);
}

.experience-card {
    min-height: 350px;
    padding: 48px 42px;
    border-right: 1px solid rgba(255, 255, 255, 0.16);
}

.experience-card:last-child {
    border-right: 0;
}

.experience-number {
    display: block;
    margin-bottom: 70px;
    color: var(--gold);
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0.15em;
}

.experience-card h3 {
    margin-bottom: 20px;
    color: var(--white);
}

.experience-card p {
    max-width: 280px;
    margin-bottom: 0;
    color: rgba(255, 255, 255, 0.58);
}

/* =========================================================
   CARTA
   ========================================================= */

.section-menu {
    background: var(--cream);
}

.menu-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 60px;
}

.menu-category h3 {
    padding-bottom: 20px;
    border-bottom: 1px solid var(--gold);
    color: var(--black);
}

.menu-item {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 20px;
    padding: 23px 0;
    border-bottom: 1px solid var(--border);
}

.menu-item h4 {
    margin: 0 0 4px;
    font-family: var(--font-display);
    font-size: 1.08rem;
    font-weight: 600;
}

.menu-item p {
    margin: 0;
    color: var(--muted);
    font-size: 0.78rem;
}

.menu-item strong {
    flex-shrink: 0;
    color: var(--gold);
    font-family: var(--font-display);
    font-size: 1rem;
    font-weight: 600;
}

.menu-note {
    margin-top: 35px;
    color: var(--muted);
    font-size: 0.76rem;
    font-style: italic;
}

.menu-action {
    margin-top: 35px;
}

/* =========================================================
   IMAGE / VISUAL
   ========================================================= */

.section-image {
    padding: 0;
    background: var(--black);
}

.image-placeholder {
    position: relative;
    min-height: 520px;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    background:
        radial-gradient(
            circle at 50% 50%,
            rgba(184, 149, 85, 0.22),
            transparent 30%
        ),
        linear-gradient(
            135deg,
            #211e19,
            #423725 50%,
            #171512
        );
}

.image-placeholder::before {
    position: absolute;
    width: 340px;
    height: 340px;
    border: 1px solid rgba(211, 183, 125, 0.35);
    border-radius: 50%;
    content: "";
}

.image-placeholder::after {
    position: absolute;
    width: 240px;
    height: 240px;
    border: 1px solid rgba(211, 183, 125, 0.2);
    border-radius: 50%;
    content: "";
}

.image-placeholder span {
    position: relative;
    z-index: 1;
    color: rgba(255, 255, 255, 0.48);
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.2em;
    text-transform: uppercase;
}

/* =========================================================
   HORARI
   ========================================================= */

.section-hours {
    background: var(--cream-light);
}

.section-hours .container {
    display: grid;
    grid-template-columns: 0.8fr 1.2fr;
    gap: 100px;
}

.hours {
    border-top: 1px solid var(--border);
}

.hour-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 30px;
    min-height: 67px;
    border-bottom: 1px solid var(--border);
}

.hour-row span {
    font-family: var(--font-display);
    font-size: 1.15rem;
}

.hour-row strong {
    color: var(--gold);
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.08em;
}

.hour-row.is-today {
    padding-left: 16px;
    border-left: 2px solid var(--gold);
    background: rgba(184, 149, 85, 0.07);
}

/* =========================================================
   CONTACTE
   ========================================================= */

.section-contact {
    background: var(--cream);
}

.contact-grid {
    display: grid;
    grid-template-columns: 1fr 0.8fr;
    gap: 100px;
    padding-top: 30px;
}

.contact-info {
    display: grid;
    gap: 40px;
}

.contact-item {
    padding-bottom: 30px;
    border-bottom: 1px solid var(--border);
}

.contact-label {
    display: block;
    margin-bottom: 12px;
    color: var(--gold);
    font-size: 0.68rem;
    font-weight: 700;
    letter-spacing: 0.18em;
}

.contact-item p {
    margin-bottom: 0;
    font-family: var(--font-display);
    font-size: 1.35rem;
    line-height: 1.45;
}

.contact-item a:hover {
    color: var(--gold);
}

.contact-actions {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 12px;
}

/* =========================================================
   CTA
   ========================================================= */

.cta-section {
    position: relative;
    overflow: hidden;
    padding: 130px 0;
    background: var(--black);
    color: var(--white);
    text-align: center;
}

.cta-section::before {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 600px;
    height: 600px;
    border: 1px solid rgba(184, 149, 85, 0.2);
    border-radius: 50%;
    content: "";
    transform: translate(-50%, -50%);
}

.cta-inner {
    position: relative;
    z-index: 1;
}

.cta-section h2 {
    margin-bottom: 35px;
    color: var(--white);
    font-size: clamp(3rem, 7vw, 6rem);
}

/* =========================================================
   FOOTER
   ===================
```
