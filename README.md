# PE14 Dipper ART/Conscrypt GitHub Builder

This repository runs a GitHub Actions baseline build for Android 14
`com.android.art` and `com.android.conscrypt` module targets only.

It does not build a full ROM. The expected workflow is to build same-version
ART/Conscrypt APEX outputs and replace those files into the official PE14
full ROM package.

The first workflow intentionally uses the AOSP `android-14.0.0_r22`
module build target. It avoids full PixelExperience device sync until the
baseline runner capacity is proven.
