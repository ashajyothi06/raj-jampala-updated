# Raj Jampala — Public Profile Website

React + Vite website, styled to match the supplied white/navy/saffron screenshot references.

## Run

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Edit

- `src/data.js`: activity cards, descriptions, categories, and image paths.
- `src/App.jsx`: pages, biography, contact form, headings and other content.
- `src/style.css`: colors, layout, typography, responsive design.
- `public/images/raj-portrait.png`: uploaded portrait.
- `public/images/raj-meeting.png`: uploaded photo of two people seated together.

To replace an activity image, add your photo under `public/images/` and set its activity's `image` property in `src/data.js`, e.g. `image:'/images/my-event.jpg'`.

**Important:** The activity names are supplied by the user but the dates, circumstances, relationships and official designations of people mentioned in them have not been independently verified. Do not present placeholder text as verified news. The contact form currently prepares/copies a draft only; it does not transmit data or promise a response. Connect a secure backend or official email workflow before production use. Add confirmed contact details and office hours when available.
