# Numworks-themes-listing

### Introduction

This is a list of custom themes for [Omega](https://github.com/Omega-Numworks/Omega) and [Upsilon](https://github.com/UpsilonNumworks/Upsilon).

### Creation

To create a new theme you need to create the icons, and palce thme in /themes/your theme/your_theme.
There is a script to create easily icon of a certain color. To use it, modify `logocolors.json` to put the colors you want, and run in your terminal:

```bash
./icon_maker.sh your_theme_name
```

You also need to create /themes/your theme/your_theme.json where you can list all system colors. There is a file in `docs` to explain each field of the json file to create.
You can test this file easily on [Omega-theme-maker](https://blog.mfriess.xyz/Omega-ThMkr/) or with the [desktop app](https://github.com/ArtichOwO/OmegaThemeMakerApp/releases).

### Installation

To compile your theme, you need to be able to compile Omega or Upsilon, then:

- either copy your theme in `/themes/themes/local/` and compile the OS adding the `THEME_NAME` flag:

```bash
make THEME_NAME="your_theme"
```

- either compile your theme from it's repository :
  _Note: if you want to compile your theme from this repository, you need to repalce the `/themes/themes_manager.py` by the one in this repo, unless you compile [SuperOS](https://github.com/AngeDieu/SuperOS)._

```bash
make THEME_NAME="your_theme" THEME_REPO="https://AngeDieu/Numworks-themes-listing"
```

### Contributing

Don't hesitate to add your theme in this list by creating a Pull Request or an Issue. If possible, it would be nice if you put sreenshots of your theme in the README file.

### Licence

This repo is released with a MIT licence.
All themes are released with their original licence. There is a licence file in each theme directory, if the original theme has one. Most themes are either under MIT licence or CC-BY-SA licence.

### Thanks

Thanks to :

- **Omega community** for developping [Omega](https://github.com/Omega-Numworks/Omega) and enableing themes for the Numworks calculator.
- Psi-Prod's [Omega-custom-theme-listing](https://github.com/Psi-Prod/Omega-custom-theme-Listing/blob/master/descriptions/french_index.json) for the idea and the frame of the repo, and for the french_json_explanations.json.
- [UpsilonNumworks](https://github.com/UpsilonNumworks/Upsilon/tree/upsilon-dev/themes) for the theme maker script (and dependencies)
- all the different theme creators.
