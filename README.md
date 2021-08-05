# SpigotBuildAction
Spigot Build Action is a simple GitHub Action project, for the server owners who cannot build Spigot on their own computer. You can download the spigot.jar in every build action.

## Maybe other versions?
You can get the other version just doing following steps,

1. Fork this repository. (Maybe leave a star)
1. Edit the `buildspigot-buildtools.yml` in `.github/workflows`. Change `--rev latest` to `--rev [the version]` and change `java-version: "16"` to `java-version: "1.8"` if you're building Minecraft that version is below `1.17`.
1. Push the changed files.
1. Go to Actions, Workflows, All workflows, BuildSpigot, and Run workflow.
1. Wait for the action done.
1. Download the artifact from the action.

# Spigot 构建工作流

懂得都懂。

## 如何构建其他版本？

1. 复刻（Fork）这个项目。
2. 编辑 `.github/workflows` 里的 `buildspigot-buildtools.yml`：把 `--rev latest` 里的 latest 改成你要的版本，例如 `--rev 1.16.5`；如果你要的MC版本低于 `1.17.X`，记得把 `setup-java` 里的 `java-version: "16"` 改成 `java-version: "1.8"`。
3. 把改完的文件推上去。
4. 打开你的项目的 Actions，Workflows，BuildSpigot with Latest Tools，点 `Run workflow`。
5. 等待 Action 完成。
6. 点开最新的 Action，在下面的 Artifacts 里找到 Spigot，点击下载。
