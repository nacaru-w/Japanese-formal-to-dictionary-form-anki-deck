# Japanese formal to dictionary form Anki deck

An Anki deck for practising the conversion between the polite ます-form and the
plain dictionary form of Japanese verbs at the JLPT N5 level. Each card also
includes the English meaning of the verb.

The deck uses the **Basic (and reversed card)** note type, so cards are
generated in both directions: you will be tested on going from ます-form to
dictionary form and vice versa.

## Contents

- `jlpt_n5_masu_verbs.txt` — the tab-separated deck file, ready to be imported
  into Anki. It contains the import headers at the top so Anki picks up the
  correct separator and note type automatically.

## How to import the deck into Anki

1. Download or clone this repository and locate the file
   `jlpt_n5_masu_verbs.txt`.
2. Open Anki on your desktop. The import feature is only available in the
   desktop version, not AnkiWeb or AnkiMobile/AnkiDroid directly.
3. From the main window, click **File → Import...** (or press `Ctrl+Shift+I` /
   `Cmd+Shift+I`).
4. In the file picker, select `jlpt_n5_masu_verbs.txt`.
5. In the import dialogue, check the following settings:
   - **Type**: `Basic (and reversed card)`
   - **Deck**: choose an existing deck or create a new one (for example
     `JLPT N5 verbs`).
   - **Fields separated by**: `Tab`
   - **Allow HTML in fields**: unchecked
   - **Field 1 of file is**: mapped to `Front`
   - **Field 2 of file is**: mapped to `Back`
   The first few lines of the file (`#separator:tab`, `#html:false`,
   `#notetype:Basic (and reversed card)`, `#columns:Front Back`) tell Anki to
   apply these settings automatically, so in most cases you will not need to
   change anything.
6. Click **Import**. Anki will confirm how many notes were added.
7. Sync to AnkiWeb if you want the deck to be available on your other devices.

## Card format

- **Front**: the ます-form of the verb, with its reading in hiragana in
  parentheses where kanji is used.
- **Back**: the dictionary (plain) form of the verb, with its reading in
  hiragana, followed by the English meaning.

Example:

```
会います（あいます）    会う（あう）- to meet
```

Because the note type is *Basic (and reversed card)*, Anki will automatically
create a second card with the fields swapped, so you can practise both
directions.

## Updating or editing the deck

The source file is a simple tab-separated text file and can be edited with any
text editor. After editing, re-import it into Anki; existing notes with the
same first field will be updated rather than duplicated, as long as you keep
the same note type and deck.

## Licence

This deck is provided as-is for personal study. Feel free to modify it for
your own use.
