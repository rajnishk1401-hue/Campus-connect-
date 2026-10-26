# CampusConnect

**Discover. Explore. Experience.**

CampusConnect is a student-first event discovery web app that brings campus happenings — hackathons, workshops, cultural nights, sports meets and more — into one clean, searchable place.

## What it does

- **Browse events** across categories: Technical, Cultural, Sports, Workshop, Hackathon, Seminar, Music and Entrepreneurship
- **Search** by event name, college or organizer
- **Filter and sort** by category, time (Today / This Week / Upcoming), free-only events, and Upcoming / Latest / Alphabetical order
- **View event details**: description, highlights, eligibility, venue, date and time, entry fee and registration deadline
- **Bookmark events** and revisit them on a dedicated Bookmarks page
- **Register** via the event's registration link, or see organizer info when no link is available
- **Light and dark theme** toggle
- **Responsive layout** that works on desktop and mobile
- **Persistent preferences**: bookmarks and theme are saved in the browser's `localStorage`

## Pages

| Page | Purpose |
|------|---------|
| Home | Hero section, category shortcuts and featured events |
| Events | Full listing with search, filters and sorting |
| Event Details | Complete information and registration for one event |
| Bookmarks | All saved events in one place |
| About | Purpose of the project |

## Tech stack

- **React 18**, loaded from a CDN (UMD build)
- **Babel Standalone**, for in-browser JSX compilation
- **HTML5 and CSS3**, with CSS custom properties for theming
- **JavaScript (ES6+)**, using React hooks (`useState`, `useEffect`)
- **Browser `localStorage`**, for bookmarks and theme
- **Google Fonts** (Inter) and **Unsplash** images

There is no backend. Event data is stored as a sample array inside the app.

## How to run

The whole app lives in a single `index.html` file, so there is nothing to install or build.

### Option 1: Open directly

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```
2. Open `index.html` in any modern browser (double-click it or drag it into a browser window).

An internet connection is required, because React, Babel, fonts and images load from CDNs.

### Option 2: Local server (optional)

```bash
# Python
python -m http.server 8000

# or Node
npx serve .
```

Then visit `http://localhost:8000`.
