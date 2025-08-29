### [Jellyfin](https://jellyfin.org)

> The Dracula Theme for Jellyfin is a fork of the awesome [Catppuccin theme](https://github.com/catppuccin/jellyfin) - many thanks to [these awesome contributors.](https://github.com/catppuccin/jellyfin/graphs/contributors)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/jellyfin.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/jellyfin/archive/main.zip) option and unzip them.

#### Activating theme

1. Open `settings`, navigate to `display` and paste the CSS into the section called `custom CSS code`;
2. Copy the following import rules and paste them into this section (`custom CSS code`)

   ```css
   @import url("https://jellyfin.catppuccin.com/theme.css");
   @import url("https://cdn.jsdelivr.net/gh/Domoel/jellyfin-dracula-theme/themes/dracula.css");
   ```

3. Press save and you're done!
