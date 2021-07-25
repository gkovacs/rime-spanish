# rime-spanish

## About

This is a layout for writing Spanish, French, Portuguese, German, and Hungarian. All accented letters in Spanish, German, and Hungarian can be entered with `;` followed by 1 keystroke, and all accented letters in French and Portuguese can be entered with `;` followed by at most 2 keystrokes.

### Spanish / Español

* `á` = `;a`
* `é` = `;e`
* `í` = `;i`
* `ó` = `;o`
* `ú` = `;u`
* `ý` = `;y`
* `ñ` = `;n`

### French / Français

* `ç` = `;c`
* Letters with grave: `à` = `;fa`
* Letters with circumflex: `â` = `;ja` (or with colemak: `;la`)
* Letters with umlaut: `ë` = `;ve`

### Portuguese / Português

* Letters with tilde: `ã` = `;xa`

### German / Deutsch

* `ß` = `;b`
* `ö` = `;d`
* `ü` = `;s`
* `ä` = `;r`

### Hungarian / Magyar

* `ő` = `;k` (qwerty only) `ő` = `;e` (colemak only) 
* `ű` = `;l` (qwerty only) `ű` = `;w` (both qwerty and colemak)

### Punctuation, non-accented characters, uppercase, colemak

Non-accented characters can be typed as usual. To type `;` itself, use `;;`. For uppercase characters, replace the last character with uppercase. So `Á` = `;A`, `À` = `;fA`

### Colemak

A colemak version is also available. For colemak, `;` in the colemak position (on the `p` letter), the accent modifier key (middle key) is in the QWERTY position if present, and the base vowel (final key) is typed according to the colemak position. For example, `ñ` would be typed `;n` (according to colemak position) / `pj` (according to QWERTY positions), and `à` would be typed `;ta` (according to colemak position) / `pfa` (according to QWERTY position).

## Installing

First ensure you have plum installed. For macOS this would be:

```bash
cd ~/Library/Rime
wget https://git.io/rime-install
```

Then install `gkovacs/rime-spanish` using plum:

```bash
bash rime-install gkovacs/rime-spanish
```

Finally edit `default.custom.yaml` and add `international` to the schema list:

```bash
patch:
  schema_list:
    - schema: spanish
```

Now reload RIME and it should appear under your layouts.
