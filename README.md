# PE14 Dipper ART/Conscrypt GitHub Builder

This repository runs a GitHub Actions module build for PixelExperience 14
`com.android.art` and `com.android.conscrypt` module targets only.

It does not build a full ROM. The expected workflow is to build same-version
ART/Conscrypt APEX outputs and replace those files into the official PE14
full ROM package.

The workflow uses the PixelExperience `fourteen` manifest by default. It does
not run a device full-ROM target.
