# 2022-02-23:
- Removed BetterLoading dependency
- Moved to local filepaths (NOTE: This means you MUST run MAS from the location of its executable)
- Remove dependence on MASDockingStation for getting mp3/ogg files from dir

# 2020-08-20:
- Remove overrides for renpy loader, opting to move to a dependency if on a non-windows system
- Update to use the submod updater
- Added some extra conditional checks + optimized some conditionals

# 2020-01-10:
- Playlist mode now works on the fly
- Various improvements and api additions
- Ability to use mp3 metadata (specifically the `genre` field) to serve as conditionals for songs
