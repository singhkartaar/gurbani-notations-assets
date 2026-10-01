# gurbani-notations-assets

Image crops of keertan notation books -- shabads of Gurbani set to music by
their authors (the shabad's text, a heading with the raag and taal, and a
grid of swaras over the sung syllables) -- served as **GitHub release
assets** for the Notations section of the Gurbani app. This repository holds
no code and no files in its tree; everything is in its releases.

- One series of releases per book: `notations-<book>-v1`, then
  `notations-<book>-v1-p2`, ... (at most 900 assets each).
- One asset per image, named after its content:
  `<book>-<page>-<seq>-<n>-<full|thumb>-<first 8 hex of its sha256>.png`.
  A changed crop gets a new name; a published URL never changes what it
  serves.
- The images are 1-bit crops of the scanned pages ("block" cuts: everything
  of one notation on one page) and small grayscale thumbnails.

The books are freely distributed as scans by
[sikhbookclub.com](https://www.sikhbookclub.com); the crops are cut from
those scans and credited to each book and its author in the app. The
notations are the work of their authors; Gurbani is the Guru's.

The crops are made by the notation pipeline of the Gurbani search project
(`29_notation_parse.py`) and uploaded by `tools/publish-notation-images.mjs`;
the public pipeline is [punjabi-ocr](https://github.com/singhkartaar/punjabi-ocr).
