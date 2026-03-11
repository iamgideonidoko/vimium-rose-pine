<h3 align="center">
	<img src="https://raw.githubusercontent.com/rose-pine/rose-pine-theme/main/assets/icon.png" width="100" alt="Logo"/><br/>
	<br/>
	Rosé Pine for <a href="https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb">Vimium</a>
</h3>

<p align="center">
  All natural pine, faux fur and a bit of soho vibes for the classy minimalist
</p>

## Variants

### 🌲 Rosé Pine <small>(Dark, warm base)</small>

![Preview of Rosé Pine](./assets/rose-pine.png)

### 🌅 Rosé Pine Dawn <small>(Light, soft morning tones)</small>

<details>
<summary>Click to expand preview </summary>

![Preview of Rosé Pine Dawn](./assets/rose-pine-dawn.png)

</details>

### 🌙 Rosé Pine Moon <small>(Dark, cooler alternative)</small>

<details>
<summary>Click to expand preview </summary>

![Preview of Rosé Pine Moon](./assets/rose-pine-moon.png)

</details>

## Color Roles

Each theme uses the following Rosé Pine palette roles:

| Role      | Usage                                           |
| --------- | ----------------------------------------------- |
| `pine`    | Titles, Vim keys, focused borders               |
| `iris`    | Vomnibar border, links                          |
| `foam`    | Link hints, URL match highlights                |
| `gold`    | Source labels, text selection                   |
| `rose`    | URL text                                        |
| `text`    | Default text                                    |
| `surface` | Slightly elevated backgrounds (dialogs, inputs) |
| `base`    | Main background                                 |

## Usage

1. Open Vimium's Options page.
1. Scroll down to the **"CSS for Vimium UI"** textbox.
1. Copy the content of your chosen variant from the [themes](./themes) folder:
   - [`themes/rose-pine.css`](./themes/rose-pine.css) — Rosé Pine (dark)
   - [`themes/rose-pine-moon.css`](./themes/rose-pine-moon.css) — Rosé Pine Moon (dark)
   - [`themes/rose-pine-dawn.css`](./themes/rose-pine-dawn.css) — Rosé Pine Dawn (light)
1. Paste it into the textbox, save changes, and restart your browser.

## Building from template

The `template.css` file uses [`@rose-pine/build`](https://github.com/rose-pine/build) variable syntax and can be used to regenerate the theme variants:

```sh
npx @rose-pine/build@latest -s false -p _ -t template.css
```

## Thanks to

- [rose-pine](https://github.com/rose-pine) — for the beautiful color palette
- [rose-pine/vimium-c](https://github.com/rose-pine/vimium-c) — for the Vimium C implementation that inspired this port

&nbsp;

<p align="center">
  <a href="https://github.com/rose-pine/rose-pine-theme">
    <img src="https://img.shields.io/badge/rose%20pine-262626?labelColor=191724&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCI+PGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTIiIGZpbGw9IiNlYjZmOTIiLz48L3N2Zz4=&style=for-the-badge" alt="Rosé Pine"/>
  </a>
</p>
<p align="center"><a href="./LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=e0def4&colorA=191724&colorB=c4a7e7"/></a></p>
