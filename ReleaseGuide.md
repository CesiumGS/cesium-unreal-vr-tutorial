<a name="tagrelease"></a>
## 1. Create and tag a release 🏷️

- Once the tutorial PR has been merged, create a new tag and release for the tutorial. Tags should be named with a 'v' before the number with minor versions increasing with each tutorial release. For example:

```
git tag -a v1.11 -m "Cesium for Unreal VR Tutorial v1.11"
git push origin --tags
```

- After a tag has been created, create a new release with that tag. 
- Set the title to "Cesium for Unreal VR Tutorial vX.X Latest".
- Remove "Latest" from the title of any previous releases.
- Add into the body any changes in this release, typically "Tutorials added in this release:"
```
Tutorials added in this release:

- "Tutorial Name"
```

<a name="marketplace"></a>
## 2. Edit file in the unreal marketplace 🎪

- Log into unrealengine.com with the unreal@cesium.com account.
- Navigate on the top bar: `Marketplace > Submit Content`, then select the "Cesium for Unreal VR Tutorials" product.
- Scroll down to the "Product Files" portion and select "Submit File Update"
- Edit the existing file submission:
    * Version title - To match the new release version number
    * Project File Link - To match the zip of the release
    * Version Notes - To match the new release

- Submit your changes and the new file will be reviewed by Epic
