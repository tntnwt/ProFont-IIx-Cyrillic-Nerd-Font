# ProFont-IIx-Cyrillic-Nerd-Font
ProFont IIx Nerd font with Cyrillic added

ProFont IIx patched with:

- Nerd Font symbols
- Cyrillic glyphs

This font is intended for terminal environments (kitty, alacritty, wezterm, etc.) and programming editors.

## Screenshot
<img width="780" height="212" alt="Screenshot from 2026-03-13 20-22-56" src="https://github.com/user-attachments/assets/469eacd1-358c-4ab2-93ed-6086471aa3fb" />
<img width="715" height="271" alt="Screenshot from 2026-03-13 20-20-22" src="https://github.com/user-attachments/assets/756118ae-3b1f-4352-8517-8f0cbea6644b" />

## Installation

Copy the font to your fonts directory:

Linux:
~/.local/share/fonts/

Then update font cache:

$ fc-cache -fv

## Installation in the terminal

I couldn't install this font in my Kitty terminal. It probably didn't recognize it as monospaced. Here's how I fixed it.

$ mkdir -p ~/.config/fontconfig/conf.d

Place the '99-profont-mono.conf' file inside conf.d/
Then

$ fc-cache -fv

## Sources

This font is based on:

- ProFont IIx  
  https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/ProFont

- werf ProFont Cyrillic  
  https://github.com/Rezmason/Scourge/tree/master/assets/fonts/werf%20-%20Profont%20Cyrillic
