# Academy Cinemas

Academy Cinemas is a responsive, single-page movie theater website. It presents
current films, showtimes, ticket-selection fields, and contact information in a
cinema-inspired design.

## Features

- Responsive navigation with links to the movies, tickets, and contact sections
- Movie cards for *Ben-Hur*, *The Day the Earth Stood Still*, and *Vertigo*
- Film descriptions, cast and director details, posters, and showtimes
- Ticket form with movie, showtime, and ticket-quantity selections
- Contact form and theater information
- Custom theater styling with Bootstrap components and a curtain backdrop

The ticket and contact forms are front-end examples; this project does not
include a server or payment processing.

## Built With

- HTML5
- CSS3
- Bootstrap 5.3

## Project Structure

```text
Academy Cinemas/
├── index.html
├── movies.txt
├── css/
│   ├── custom.css
│   └── custom-css-media.css
└── Images/
    ├── logo.png
    ├── theater-curtains.jpg
    └── movie posters and rating images
```

## Run Locally

Open `index.html` in a browser, or start a local web server from the
`Academy Cinemas` directory:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.
