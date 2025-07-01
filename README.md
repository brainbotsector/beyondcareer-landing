#  BeyondCareer Landing Page

Landing page built with **Next.js 15**, showcasing the mission, vision, and services of **Beyond Career**, demonstrating clean file structure, animations with `framer-motion`, and responsive design principles.


##  Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/)
- **Animation**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)
- **Intersection Observer**: For scroll-triggered animations
- **EmailJS**: [@emailjs/browser](https://www.emailjs.com/docs/sdk/send-form/) (installed but not used — awaiting verified email)

##  Features

- Animated landing sections (Hero, About, Contact)
- Responsive and mobile-friendly
- Modular component structure
- SEO & performance-friendly setup
- Minimal external dependencies

##  Setup Instructions

1. Clone the Repository

```bash
git clone https://github.com/brainbotsector/beyondcareer-landing.git
cd beyondcareer-landing
```

2. Install Dependencies

```bash
npm install
```

3. Run the Development Server

```bash
npm run dev
```
Open http://localhost:3000 in your browser to see the result.

4. Build for Production

```bash
npm run build
npm start
```

##  Environment Setup

  - Ensure have the following installed:

    > Node.js >= 18

    > npm >= 9

    > Internet access (for downloading image assets & fonts)

   - Optional:

     > ESLint plugin for your IDE for linting consistency

##  Styling Details

   - globals.css: Used for major sections like About, Hero, and Contact

   - Inline Styles: Used for Testimonials, Services, Navbar, and Footer due to time constraints

##  EmailJS (Optional Integration)

   The @emailjs/browser package is installed for future contact form integration. However, it's not currently functional due to missing verified sender email.
