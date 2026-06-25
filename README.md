# PE14 Dipper ART/Conscrypt GitHub Builder

This repository runs a GitHub Actions baseline build for Android 14
`com.android.art` and `com.android.conscrypt` module targets.

The first workflow intentionally uses the AOSP `android-14.0.0_r22`
module build target. It avoids full PixelExperience device sync until the
baseline runner capacity is proven.
