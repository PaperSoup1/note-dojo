# Note Dojo

Piano note-reading flashcards: treble and bass clef, hints, sight-reading lines.
Listens to a real piano through the microphone (or a MIDI piano on a computer).

Open it: https://papersoup1.github.io/note-dojo/

## Privacy and safety

- The whole app is this one `index.html` file. GitHub Pages hosts it for free; nothing runs on anyone's own computer except the open page.
- No accounts, no ads, no tracking, no cookies. Your progress is saved only in your own browser.
- The microphone audio is analysed on your device and never leaves it.
- A strict Content Security Policy in the page blocks it from loading or sending anything over the network.
- Only the repository owner can change the site. Anyone can read the code.

## Battery

- The microphone pauses itself after 10 quiet minutes. Tap anywhere to resume.
- While the page is in the background, it stops analysing sound.
- With the mic off, audio goes to sleep after 30 seconds of silence.
- The screen is kept awake only while the mic (or a MIDI piano) is in use.
