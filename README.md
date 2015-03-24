# Primer

A custom UI and syntax theme for Sublime Text 2/3. Based on Mozilla's Firefox Developer Edition and [@kkga](https://github.com/kkga)'s [Spacegray](https://github.com/kkga/spacegray).

***

### Themes

#### Primer

Default flavor based on Firefox Developer Edition - Dark.

![image](screenshots/fox.dark-html.jpg)
![image](screenshots/fox.dark-css.jpg)
![image](screenshots/fox.dark-js.jpg)

*The font used in the screenshots is __Monaco__.*

***

### How to Install

#### Via Package Control

The easiest way to install is using [Sublime Package Control](https://sublime.wbond.net), where Fox is listed as `Theme - Primer`.

1. Open Command Palette using menu item `Tools -> Command Palette...` (<kbd>⇧</kbd><kbd>⌘</kbd><kbd>P</kbd> on Mac)
2. Choose `Package Control: Install Package`
3. Find `Theme - Primer` and hit <kbd>Enter</kbd>

#### Manual

You can also install the theme manually:

1. [Download the .zip](https://github.com/karelvuong/st-primer/archive/master.zip)
2. Unzip and rename the folder to `Theme - Primer`
3. Copy the folder into `Packages` directory, which you can find using the menu item `Sublime Text -> Preferences -> Browse Packages...`

***

### How to Activate

Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item `Sublime Text -> Preferences -> Settings - User` (<kbd>⌘</kbd><kbd>,</kbd> on Mac).

Primer comes with different accent colors based on GitHub's color scheme (http://primercss.io/colors/).

***Note: Don't forget to restart Sublime Text after activating the theme.***

#### Settings for Primer

Only choose one setting per section.

```json
{
  "theme": "Primer.sublime-theme",
  "color_scheme": "Packages/Theme - Primer/primer.light.tmTheme",
  
  // Accent Colors
  "theme_primer_tab_active_blue": true,       // default
  "theme_primer_tab_active_green": true,
  "theme_primer_tab_active_red": true,
  "theme_primer_tab_active_orange": true,
  "theme_primer_tab_active_purple": true,
  
  // Tab Label Font Size
  "theme_primer_tabs_font_small": true,
  "theme_primer_tabs_font_normal": true,      // default
  "theme_primer_tabs_font_large": true,
  "theme_primer_tabs_font_xlarge": true,
  
  // Sidebar Row Padding
  "theme_primer_sidebar_tree_xsmall": true,
  "theme_primer_sidebar_tree_small": true,      
  "theme_primer_sidebar_tree_normal": true,   // default
  "theme_primer_sidebar_tree_large": true,
  "theme_primer_sidebar_tree_xlarge": true,
  
  // Sidebar Font Size
  "theme_primer_sidebar_font_small": true,      
  "theme_primer_sidebar_font_normal": true,   // default
  "theme_primer_sidebar_font_large": true,
  "theme_primer_sidebar_font_xlarge": true,
}
```
