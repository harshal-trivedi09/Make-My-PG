# StayNest PG Management System — HTML & CSS

A complete responsive frontend UI for a Paying Guest (PG) Management System.

## Included
- Home page
- Login / registration
- PG listings and filters
- PG details
- Booking request form
- User dashboard
- Booking history
- Admin dashboard
- Add PG form
- Manage PG table
- 404 page
- Responsive CSS

## Folder Structure
```
pg-management-html-css/
├── index.html
├── login.html
├── register.html
├── pg-listings.html
├── pg-details.html
├── booking.html
├── dashboard.html
├── my-bookings.html
├── admin.html
├── add-pg.html
├── manage-pg.html
├── 404.html
├── css/
│   └── style.css
├── js/
└── README.md
```

## Run
No server is required for the static frontend. Open `index.html` in a browser, or use VS Code Live Server.

## GitHub
```bash
git init
git add .
git commit -m "Add PG management frontend"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

## Backend Integration
The forms and links are frontend-ready. Connect them to your Python Flask backend and MongoDB for real authentication, PG data, bookings, admin actions and database operations.
