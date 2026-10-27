# Say It!

Practice English pronunciation: type a sentence, listen to it, repeat it out loud, and get a star score.

**▶ Open the app: https://kirilkirin.github.io/say-it/**

Nothing to install and no account needed — it works on phones, tablets, and computers.

## How to use it

1. Type or paste any English text.
2. Pick an accent (🇺🇸 American or 🇬🇧 British) and a speed (🐢 Slow or 🐇 Normal).
3. Tap **Say it** to hear the sentence. Each word lights up as it is spoken, so you can read along.
4. Tap **My turn** and repeat the sentence out loud. The microphone stops by itself when you pause — no need to tap Stop.
5. You get:
   - a score from 1 to 5 stars,
   - the sentence the app heard you say,
   - every word colored: **green** = got it, **yellow** = close, **red** = missed.

The first time you tap **My turn**, your browser asks for microphone permission — allow it.

## Good to know

- Scoring is forgiving: capitals and punctuation are ignored, contractions match, and digits count as words ("2" = "two").
- The accent toggle changes both the speaking voice and the language the microphone listens for.
- Voices come from your own device, so the app can sound different on a phone than on a computer.

## Browser support

| Feature | Chrome / Edge | Safari (incl. iPhone and iPad) | Firefox |
|---|---|---|---|
| Listen (text-to-speech) | ✅ | ✅ | ✅ |
| My turn (speech scoring) | ✅ | ✅ | ❌ (button is hidden) |

Speech recognition is provided by the browser and may need an internet connection.

## Privacy

The whole app is a single HTML file — no server, no accounts, no tracking, and nothing you type is stored. When you use **My turn**, your browser's own speech-recognition service (for example Google's in Chrome, Apple's in Safari) converts your speech to text.

## Run your own copy

- **Quick:** download [`index.html`](index.html) (open the file, then use the download button next to "Raw") and open it in a browser.
- **Hosted:** fork this repository and turn on GitHub Pages (Settings → Pages → Source: Deploy from a branch → `main` / `(root)`).

## Credits

Built with the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API). Fonts: Fredoka and Atkinson Hyperlegible (Google Fonts).

Developed by Kiril Kirin.
