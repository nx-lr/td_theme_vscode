# [TRU:CODE]

<div align=center>

![icon](https://github.com/nxltm/trucode_themes/blob/main/icon.png?raw=true)

<small>`image above by me / done using Figma and Canva`</small>

</div>

---

```js
const damage: boolean = true;
```

**_TruCode_** are a line of programming themes for Visual Studio Code, based on the official True Damage (2019) skins from League of Legends!

The themes are designed with [**_Theme Studio_**](https://themes.vscode.one/), which I recommend you try out for yourself if you're sane enough to create your own theme then have it previewed in real time.

The colors are adapted from [**_Electron_**](https://github.com/kcmr/electron-theme-vscode), augmented by other colors from popular themes, as well as [**_Coolors_**](coolors.co) and [**_Color Hunt_**](colorhunt.com).

Supports most languages, including, but not limited to: CSS, JS, TypeScript, HTML, PHP, Ruby, YAML, Markdown, Python, Ruby, Java, C#, Scala and more.

The colors are mostly based on the Electron/One Dark Pro/Material Themes, plus more colors sourced from. This was once my personal theme so there're a lot of colors in there.

These are my first themes, so make sure to let me know if you see something off or out of place, or even don't work well, and I'll try to find time to fix it.

### Recommended Settings

If you want to steal the look as per the screenshots, go and install [Cascadia Code](https://github.com/microsoft/cascadia-code/releases), download the **Variable Fonts**, then paste this code snippet in your `settings.json` file, excluding the outside braces:

```json
{
  "editor.fontFamily": "Cascadia Code, monospace",
  "editor.fontLigatures": "'ss01', 'ss20'", // insert your own custom configuration here
  "editor.fontSize": 13,
  "editor.letterSpacing": -0.5,
  "customizeUI.font.monospace": "Cascadia Code", // or Iosevka
  "customizeUI.font.regular": "Bahnschrift"
}
```

### Installation

- Install and launch Visual Studio Code
- Click on the Extensions Icon
- Search for `TruCode`
- Click `Install`, then `Set Color Theme`
- Select what theme you want to use from the dropdown

If you want to switch themes:

- Navigate to Code > Preferences > Color Theme, then type `TruCode`. You should see five themes.
- Then select `TruCode: {True Damage member}` from the dropdown

---

Coming soon:

## Screenshots

There's two themes for each of the True Damage members, with low and high contrast versions. In addition, there's a sixth Prestige edition theme, with custom accent colors for the Prestige members (Qiyana, Senna and Yasuo).

### Akali // Finished!

![Akali](./images/akali.jpg)

### Ekko // Almost done!

![Ekko](./images/ekko.jpg)

### Qiyana // Not yet done.

![Qiyana](./images/qiyana.jpg)

### Senna // Not yet done.

![Senna](./images/senna.jpg)

### Yasuo // Not yet done.

![Yasuo](./images/yasuo.jpg)

## Extension Pack

Once this theme is published on Visual Studio Code, it will also be available as an extension pack.

- **Customize UI** & **Monkey Patch** - to inject custom CSS and JS
- **Babel JavaScript** - syntax highlighting for Babel JavaScript. Also supports some experimental JavaScript features, and support for Flow, GraphQL and Styled Components.
- **Better Syntax** pack by Jeff Hykin
- **Markdown All-in-One** for better Markdown syntax
- **Bracket Pair Colorizer 2** - highlights different pairs or levels if brackets with different colors - also enables custom color sets)
- **Rainbow Tags** - XML/HTML tags
- **Indent Rainbow** - highlights different levels of indentation with different colors
- **Better Comments** - labelling your comments with different symbols gives them unique colors
- **Colorize** - highlights CSS colors - hexadecimal, RGBA, HSL and HSV
- **Comment Tagged Templates** - embedded highlighting for different types of languages in commented JavaScript ES6 template strings

### License

Copyright &copy; 2021 NoxUltima
