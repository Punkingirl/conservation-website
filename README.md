Millars Beach Conservation Trust Website

A full-stack conservation website built during my studies for the Millars Beach Conservation Trust in New Zealand. This project combines my interest in environmental conservation with modern web development.

The website helps the trust connect with volunteers, donors, and the local community, while providing an easy way to share conservation updates and media.

About the Project

The Millars Beach Conservation Trust works to restore indigenous flora and fauna on the Millars Beach Peninsula through pest reduction and community involvement.

This website was built as a real-world project to support their work by:

-Sharing conservation updates

-Showcasing photos, videos, and native bird sounds

-Providing contact and donation options

Features

-Fully responsive design (desktop, tablet, mobile)

-Blog system for conservation updates

-Photo and video gallery

-Audio player with native bird sounds

-Contact forms for volunteers and supporters

-Donation page

-Admin dashboard for content management

Tech Stack
Frontend

-Next.js 14 (App Router)

-TypeScript

-Tailwind CSS

-React Hook Form

Backend

-Django

-Django REST Framework

-SQLite (upgradeable to PostgreSQL)

Deployment and Tools

-Local hosting for now, potentially hosting on AWS 

-GitHub for version control and media hosting

-GitHub raw URLs for external media hosting

Challenges and Solutions

Large Media Hosting

Issue: Audio and video files exceeded Vercel’s static file limits

Solution: Uploaded media to GitHub and referenced them via raw URLs

Result: Stable and reliable media delivery

Responsive Design

Issue: Supporting multiple screen sizes

Solution: Mobile-first design using Tailwind CSS

Result: Smooth experience on all devices

Project Structure
conservation-website/
─ app/                    # Next.js pages
─ components/             # Reusable components
─ conservation_backend/   # Django backend
─ public/                 # Static assets

Design Choices
Colour Palette

Dark Green (#2E7D32)

Sea Green (#4CAF50)

Spring Green (#66BB6A)

Charcoal (#374151)

Typography

Montserrat for headings

Open Sans for body text

Getting Started
Prerequisites

Node.js 18+

Python 3.8+

Git

Frontend Setup
git clone https://github.com/Punkingirl/conservation-website.git
cd conservation-website
npm install
npm run dev

Backend Setup
cd conservation_backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

Performance and Accessibility

Lighthouse score: 95+

Load time under 2 seconds

Fully responsive design

WCAG 2.1 AA compliant

Security

Client-side and server-side form validation

CSRF protection with Django

Input sanitisation to prevent XSS

HTTPS enforcement

Testing

Unit testing for components

API integration testing

Manual testing across browsers and devices

Accessibility testing

Future Improvements

Real-time updates using WebSockets

User analytics and engagement tracking

Progressive Web App (PWA) features

Multi-language support

Advanced CMS functionality

About Me

I am a student developer interested in building stuff. This project reflects my learning in full-stack development, deployment, and problem-solving.

Skills demonstrated:

Full-stack web development

JavaScript and TypeScript

Responsive design

API development

Deployment and debugging

