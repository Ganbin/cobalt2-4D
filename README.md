# Cobalt2 Theme for 4D

![Preview](https://raw.githubusercontent.com/ganbin/cobalt2-4D/cobalt2-preview.png)

## Installation

1. Download the file corresponding to the version you like.
2. Go to the `Active 4D Folder`
   1. Windows 7 and higher: {disk}\Users\{UserName}\AppData\Roaming\4D\
   2. MacOS: {disk}:Users:{UserName}:Library:Application Support:4D:
3. Open the corresponding file.
4. Copy the part you like between the `<method_editor>` tag.

## Important: Other Settings in This File

It is important to notice that this file can contain other settings that you would like not to change. Be sure to read your original file and the one with the Cobalt2 theme to only change the part that has the theme settings (between the `<method_editor>` tag)

In the `<method_editor>` there are some options you may want to keep.

The ones that come with the Cobalt2 theme are those :

```xml
<options
  auto_quote="true"
  character_suggestion_validation="tabOnly"
  hilite_same_word="hiliteOnFullySelected"
  indentation="20"
  matching_parenthesis_style="backColor"
  show_blocks_hilite="false"
  show_line_numbers="true"
  show_lists="false"
/>
```

### Credits

This theme is an 4D adaptation of the [wesbos/cobalt2-vscode](https://github.com/wesbos/cobalt2-vscode) theme.
