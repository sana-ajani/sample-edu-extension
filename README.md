# Sample Education Extension

We are exploring the concept of Profiles in VS Code that can customize your settings and layout.

The first step of the proposed Profiles solution is extensions being able to contribute default settings, layout, and keybinding overrides. Currently, extensions can override the default values for settings through the `configurationDefaults` contribution point in `package.json`.

Ultimately, this can allow educators to control and pre-determine Profiles they want to distribute via extensions. 

Additional asks we are tracking are:
- settings to configure views and configure menu/toolbar actions

Ideally, if an educator has multiple classes for which they need multiple Profiles, they would be able to do it all through the single extension. Like how users can choose from multiple presets (light, dark, high contrast) in one theme extension, users should be able to choose from multiple preset class profiles. 