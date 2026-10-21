# FrameFix
Practice-only input correction for Geometry Dash (Geode 5.11.2, GD 2.2081, iOS target).

## Build without a computer setup
1. Make a new GitHub repo and upload ALL files from this folder.
2. Dot-folders are hidden on iOS, so make the workflow by hand:
   in the repo press Add file > Create new file, name it `.github/workflows/build.yml`
   (typing the slashes makes the folders), paste in the contents of `build.yml` from this zip.
3. Edit `id` and `developer` in mod.json.
4. Actions tab > "Build FrameFix" > Run workflow. Download the .geode from the artifact.
