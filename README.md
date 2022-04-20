# Origins Example Datapack Workspace

## Use
1. Clone the repository using `git clone https://github.com/LimonBlaze/origins-example-datapacks`
2. Open the build.gradle in your IDE, see the [fabric wiki page](https://fabricmc.net/wiki/tutorial:setup) that relates to the IDE that you are using for more information.
3. Create your datapack directory under [PROJECT_DIR]/datapacks/ like the example one, prefer using a directory name like a namespace.
4. Specify the datapack's name and version using `[DATAPACK_DIR]_name` and `[DATAPACK_DIR]_version` (Optional)
5. Make the datapack, test it using `fabric/runClient` gradle task or the provided `MinecraftClient` run configuration.
6. Release the datapack using `other/releaseDatapacks` gradle task, the zip output should be in the `out/[DATAPACK_NAME]` directory.

## License
This template is available under the CC0 license. Feel free to learn from it and incorporate it in your own projects.
