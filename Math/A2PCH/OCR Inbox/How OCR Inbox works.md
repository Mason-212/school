# OCR Inbox

Drop a photo of a worksheet or handwritten notes **in this folder**, then run OCR on purpose in Cursor:

```
/ocr-to-md path/to/photo.jpg
```

Nothing watches this folder in the background. llama-server starts only for that command.

A matching `.md` file appears next to the photo after OCR finishes (often 2–6 minutes for a dense page). Everything runs **on this Mac** — nothing is uploaded.

Every page gets the same house style: **bold** key ideas and titles, <u>underlines</u> where you underlined, a blank line between paragraphs, hole-punch words finished from context, and spelling fixed from the rest of the page. Columns stay split; drawn boxes stay boxes.

Redo after engine updates:

```
/ocr-to-md --force path/to/photo.jpg
```

