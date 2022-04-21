# Origins Example Datapack

## How To Use?
1. Use this as a repo template, or clone this repo if you don't feel like having a git repo.
2. Open the build.gradle in your IDE, see the [fabric wiki page](https://fabricmc.net/wiki/tutorial:setup) that relates to the IDE that you are using for more information.
3. Create your datapack directory under `[PROJECT_DIR]/datapacks/[DATAPACK_DIR]` like the example ones, prefer using a directory name like minecraft's namespace.
4. Specify your datapacks by adding their directory name to the `datapacks` field in `build.gradle`.
5. Specify the datapack's name and version using `[DATAPACK_DIR]_name` and `[DATAPACK_DIR]_version` in` gradle.properties`. (Optional)
6. Work on the datapack, test it using `fabric/runClient` gradle task or the provided `MinecraftClient` run configuration.
7. For reloading data and resources, build the project first before using `/reload` and F3+T.
8. Release the datapack using `other/releaseDatapacks` gradle task, the zip output should be in the `out/[DATAPACK_DIR]` directory.

## What's the benefit?
1. Releases can be created in one click.
2. Mixedpacks like the example datapacks are easier to make.
3. Working in an IDE provides useful functions such as highlighting and VCS, cooperating through Git also become possible.
4. Transforming the project into a mod is also possible.

## License
This template is available under the CC0 license. Feel free to learn from it and incorporate it in your own projects.
