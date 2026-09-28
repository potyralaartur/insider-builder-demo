# Insider Builder: demo

Interactive demo of **Insider Builder**, the tool Kellton Europe uses to put together its monthly internal newsletter *Insider* from ready-made blocks, preview it and send it through Gmail.

**Open the demo:** https://potyralaartur.github.io/insider-builder-demo/

- Nothing is sent. The backend is a fake that runs in your browser; "Wyślij test" and "Wyślij do wszystkich" only pretend.
- Your changes live until you reload the page.
- The app is in Polish. It starts with the September 2026 issue as a draft.

## Try other states

Add one of these to the URL (before the `#`):

| URL | Shows |
| --- | --- |
| `?wydania=brak` | the start screen, no issues yet |
| `?wysylka=blad` | sending to everyone fails (Gmail quota) |
| `?konflikt=1` | the issue is changed "in another tab" 5 s after it opens |
| `?zapis=blad` | saving fails for 20 s, then works |
| `?upload=blad` | the first two image uploads fail |
| `?obrazy=blad` | each preview image fails once |

This repo only holds the built page (`index.html`). The source is private.
