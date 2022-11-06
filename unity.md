# Unity style guide
Style guide for Unity projects

## Table of Contents
1. [Naming](#naming)

## Naming
- Variables that reference a prefab for cloning should be suffixed with `Prefab`
- Variables that hold a reference to GameObject instances should be named accordingly
  - Locally scoped: `clone`
  - Globally scoped: prefab name + `Clone` (e.g. `weaponClone`)
