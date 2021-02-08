# SpigotBuildAction
Spigot Build Action is a simple GitHub Action project, for the server owners who cannot build Spigot on their own computer. You can download the spigot.jar in every build action.

## Maybe other versions?
You can get the other version just doing following steps,

1. Fork this repository. (Maybe leave a star)
1. Edit the `buildspigot.yml` in `.github/workflow/buildspigot.yml`. Change `--rev latest` to `--rev [whatever-you-wanted, like 1.16.5]`.
1. Push commit, and the action will automatically execute.
1. Download the artifact from the action.
