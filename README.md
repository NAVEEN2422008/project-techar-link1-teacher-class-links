# Techar Link 1 - Teacher Class Links Page

A simple static HTML page that aggregates a teacher's video-class links (Zoom meetings) for students, with the school logo as the background.

## Features

- Clean single-page directory of subject-based class links (Social, Maths, Chemistry)
- Each subject link opens the corresponding Zoom meeting URL in a new tab
- School logo used as a fixed background image with custom link styling (hover/active color states)

## Tech Stack

- **HTML5** with inline CSS (no external frameworks, no JavaScript)

## Project Structure

```
school/
├── link.html   # Class links page
└── logo.jpg    # School logo background image
```

## Installation

1. Clone the repository.
2. No build step required.

## Usage

1. Open `school/link.html` in any web browser.
2. Click a subject link (Social, Maths, or Chemistry) to join that class meeting.
3. To add or change links, edit the `<a href="...">` entries in `link.html`.
