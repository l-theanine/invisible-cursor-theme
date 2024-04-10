# invisible-cursor-theme
This theme addresses a common issue with Parsec on Linux where an extra cursor is displayed after connecting to the host PC. By providing an invisible cursor, this theme effectively resolves the problem.


## Installation
1. Copy the theme folder to `/home/$USER/.icons/`.
2. Create a keybind to switch between your default cursor theme and the Invisible Cursor theme.

## Usage
For example, in XFCE the following command can be used to switch the cursor theme.
```
xfconf-query --channel xsettings --property /Gtk/CursorThemeName --set InvisibleCursor
```
And vice versa to switch back to your original theme.

### Example Keybind Configuration
* Super+Insert: Switch to default cursor theme
* Super+Shift+Insert: Switch to Invisible Cursor theme
