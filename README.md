# 🧩 3jPatch Morphe

Version-locked Android patches for the [Morphe](https://morphe.software/) patching framework.

## ❓ About

The initial patch provides client-side cleanup for Grindr 26.17.0. It enables the app's own
presentation flags for suppressing ads and subscription-store surfaces without claiming to
unlock server-backed subscription features.

### How to use these patches

[Add 3jPatch_Morphe directly to Morphe](https://morphe.software/add-source?github=jjjusf16-sys/3jPatch_Morphe)

## 🩹 Patches list

<!-- PATCHES_START EXPANDED -->

The generated patch list will appear here after the first release.

<!-- PATCHES_END -->

### 🛠️ Building locally

- Run `./gradlew buildAndroid`
- The built patches .mpp file is found in `patches/build/libs/patches-*.mpp`
- Patch the mpp file using [Morphe-Desktop](https://github.com/MorpheApp/morphe-desktop)
  like any other patch bundle.

See the [Morphe documentation](https://github.com/MorpheApp/morphe-documentation) for more information.

## 📜 License

3jPatch_Morphe is licensed under the [GNU General Public License v3.0](LICENSE).
