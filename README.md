<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://zen-browser.app/">Zen Browser</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/zen-browser/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/zen-browser?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/zen-browser/issues"><img src="https://img.shields.io/github/issues/catppuccin/zen-browser?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/zen-browser/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/zen-browser?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

1. [Create a `chrome` folder](https://www.userchrome.org/how-create-userchrome-css.html) in your Zen Browser's profile directory and configure it to enable userstyles.
2. Copy the `userChrome.css`, `userContent.css`, and `zen-logo-<flavor>.svg` files of your preferred theme from the [`themes/`](themes/) directory in this repository to your `chrome` folder.
3. Enable `toolkit.legacyUserProfileCustomizations.stylesheets` in [about:config](about:config).

### 🌗 Light and dark mode

[🌻 Latte](themes/Latte/) is the light flavor. [🪴 Frappé](themes/Frappe/), [🌺 Macchiato](themes/Macchiato/), and [🌿 Mocha](themes/Mocha/) are dark. Zen has two separate light and dark settings, and the theme follows both:

| Setting | What it changes | Where to find it |
| --- | --- | --- |
| **Browser appearance** | The browser window: sidebar, tabs, menus, and address bar | Right-click the tab sidebar, select **Edit Theme**, and use the auto, light, and dark icons at the top. You can also use **View → Appearance** in the menu bar. Press <kbd>Alt</kbd> to show the menu bar. |
| **Website appearance** | Web pages and Zen's own pages, such as Settings and the new tab page | **Settings → Website appearance** (`about:preferences#appearance`) |

Set both to match your flavor, or set both to follow your system: **Auto** for browser appearance and **System** for website appearance.

> [!TIP]
> The theme replaces Zen's per-space gradient backgrounds with the flavor's colors. To keep your space gradients, delete the block marked `Space (workspace) gradients` in `userChrome.css`.

## 🙋 FAQ

- **Q:** What if I already have a `userChrome.css` and/or `userContent.css` configuration?
  
  **A:** You can copy and paste the content of our `userChrome.css` and/or `userContent.css` files into your existing ones. This way, you can keep your current configurations while applying the new theme settings.

- **Q:** Can I automatically switch flavors between light and dark mode?
  
  **A:** Yes! You can concatenate the `userChrome.css` and `userContent.css` files for 🌻 Latte (light mode) along with one of the dark mode themes like 🪴 Frappé, 🌺 Macchiato, or 🌿 Mocha. The theme then switches flavors with Zen's light and dark settings, described in [Light and dark mode](#-light-and-dark-mode).

## 💝 Thanks to

- [IAmJafeth](https://github.com/IAmJafeth)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
