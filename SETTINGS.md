This page contains settings for configuring SilverBullet and its plugs. Any changes outside of the yaml block will be overwritten.
A list of built-in settings [[!silverbullet.md/SETTINGS|can be found here]].

```yaml
indexPage: index

# Configure the shown action buttons (top right bar)
actionButtons:
- icon: home # Use any icon from https://feathericons.com
  command: "{[Navigate: Home]}"
  description: "Go to the index page"
- icon: book
  command: "{[Navigate: Page Picker]}"
  description: Open page
- icon: terminal
  command: "{[Open Command Palette]}"
  description: Run command
- icon: sidebar
  command: "{[Tree View: Toggle]}"
  description: "Toggle Tree View"
- icon: arrow-left
  command: "{[Navigate: Back in History]}"
  description: "Go to the previous page"
  mobile: true # Only show on mobile devices, set to false to show only on desktop
```
