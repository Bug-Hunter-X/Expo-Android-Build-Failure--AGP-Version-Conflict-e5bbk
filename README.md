This repository demonstrates a common but elusive bug encountered when building Android apps with Expo CLI. The issue stems from a mismatch in the Android Gradle Plugin (AGP) versions.  The root cause is often an outdated or conflicting AGP version in your project's `build.gradle` files. This may be due to manual updates or conflicts with dependencies. The solution involves ensuring consistency in AGP versions throughout the project.

**Problem:** Expo's build process might fail with vague errors unrelated to AGP if there's a version conflict.  This can be exceptionally tricky to diagnose.

**Solution:** Carefully review and synchronize the AGP version in all `build.gradle` files. The recommended way is using the Expo managed workflow to avoid manual AGP version management.