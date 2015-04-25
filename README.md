# gradle-android-flavor-build
A foray into the world of Android's Gradle plugin for coordinating more complex builds

### Overview
This Android Studio project uses the new build conventions to define:
* 2 Build Types
  * Debug
  * Release
    * Added automatic signing
* 2 Product Flavors
  * Free
  * Pro

There is no code duplication between the different variants. Only the necessary resources have been changed in product-flavor- or build-type-specific directories. Variant-independent code comes from the `main` directory.
