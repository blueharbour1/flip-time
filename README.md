# FLIP / TIME — V32 Journal Edit Test

V32 adds direct journal opening for activities that already have a journal note.

- Tap a saved colored activity **with a note**: opens its journal immediately, with focus in the note textarea.
- Tap a saved activity **without a note**: opens the existing color editing screen.
- In journal view, tap the outlined **pencil** button to return to Select color. Any edited note text remains in the editor state, including while selecting a new color.
- Choose a color, continue to activity title, optionally return to the journal, then use the check button to save all fields together.
- Export Backup includes activity `note` fields in the `ft-records` data, unchanged from V31.

**Important:** Closing the modal without pressing the check button discards unsaved changes. For production iOS/Android verification, test the keyboard and export/import backup on a real device before uploading to the live GitHub Pages site.

To deploy, replace the existing `index.html` and `sw.js` in your GitHub Pages repository. Other files have not changed.
