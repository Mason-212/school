# OCR Inbox

Drop a photo of a worksheet or handwritten notes **in this folder**.

A matching `.md` file appears next to it after OCR finishes (often 2–6 minutes for a dense page — slower on purpose so it stays on glm-ocr). Everything runs **on this Mac** — nothing is uploaded.

Every future page gets the same house style: **bold** key ideas and titles, <u>underlines</u> where you underlined, a blank line between paragraphs, hole-punch words finished from context, and spelling fixed from the rest of the page. Columns stay split; drawn boxes stay boxes. All on this Mac.

You can also paste a photo into any note in this vault. Obsidian saves the image here, and the same markdown file is created.

Already have a photo somewhere else in the vault? In Cursor:

```
/ocr-to-md path/to/photo.jpg
```

Redo after engine updates:

```
/ocr-to-md --force path/to/photo.jpg
```
