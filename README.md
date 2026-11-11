# OPTIC EVAL

A simple OMR answer-sheet checker that runs entirely in the browser: create an examination, define result groups (class, house, wing, ...), print sheets, scan them with the camera, and get ranked results (PDF / CSV).

© Anant Shukla (M.Sc. Physics)

## Notes
- It is a single static page (`index.html`). There is no server and no build step.
- All exams and student results are saved in the browser of the device that is used (local storage). They are not uploaded anywhere and are not shared between devices.
- The live camera needs a secure page, which GitHub Pages provides (https).
