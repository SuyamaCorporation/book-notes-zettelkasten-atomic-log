# Book Notes Zettelkasten Atomic Log
Capture atomic permanent notes from books. Fields: title, source book, concept tags (comma-separated), note body. Tag-based filtering. Link notes by tag overlap (show related). Full-text search. localStorage persistence.

## Features
- Atomic note creation with title, source book, tags, and body fields
- Tag-based filtering with toggle buttons (all unique tags shown)
- Full-text search across title, source, body, and tags simultaneously
- Related notes panel: shows notes sharing tag overlap (up to 5)
- Note detail modal with full content display
- Note count display updates with active filter/search
- localStorage persistence for all notes
- XSS-safe rendering (textContent throughout, no innerHTML)
- Keyboard accessible: tabindex, role=button, aria-label on all interactive elements
