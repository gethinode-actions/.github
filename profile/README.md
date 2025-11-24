## Hi there 👋

This organization maintains a fork of [peter-evans/create-pull-request](https://github.com/peter-evans/create-pull-request). GitHub actions requires a major version tag that points to the latest available release. Follow these steps to create a new release of `create-pull-request` correctly.

1. Synchronize the fork with the origin
2. Identify the latest release tag of the origin (e.g., `v7.0.9`)
3. Create a new release including tag using the GitHub GUI
4. Checkout the tag locally with `git checkout v7.0.9`
5. If tag `v7` already exists, delete it with `git tag -d v7` and `git push --delete origin v7`
6. Create an alias tag `v7` with `git tag v7`
7. Push the local tag to GitHub with `git push origin v7`
