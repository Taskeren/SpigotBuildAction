# SpigotBuildAction
Spigot Build Action is a simple GitHub Action project, for the server owners who cannot build Spigot on their own computer. You can download the spigot.jar in every build action.

## Maybe other versions?
You can get the other version just doing following steps,

1. Fork this repository. (Maybe leave a star)
1. Edit the `buildspigot-buildtools.yml` in `.github/workflows/buildspigot.yml`. Change `--rev latest` to `--rev [the version]` and change `java-version: "16"` to `java-version: "1.8"` if you're building Minecraft that version is below `1.17`.
1. Push the changed files.
1. Go to Actions, Workflows, All workflows, BuildSpigot, and Run workflow.
1. Wait for the action done.
1. Download the artifact from the action.
