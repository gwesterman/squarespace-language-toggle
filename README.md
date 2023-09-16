# Squarespace Language Toggle

This code is a simple way to toggle between two languages on Squarespace website. It works for both the desktop and mobile version.

The example uses German and English, but you can easily change the languages by editing the primary and secondary language variables in the code.

## How to use

1. The URL of any page has to include a language code (e.g. `https://www.example.com/de/foo` or `https://www.example.com/en/foo`), only then can the script determine which language is currently active. In this example it will check for `/de/` or `/en/`.

2. Add the code from `language-toggle.html` to the page settings (Settings > Advanced > Page Header Code Injection). Edit the code to match your primary and secondary language.

## Notes

1. Emoji flags are used as language buttons on all platforms except Windows. There the language buttons are displayed as text. This is due to the fact that Windows does not support the Unicode standard for emoji flags.

2. The code is written in JavaScript and uses the [jQuery](https://jquery.com/) library.
