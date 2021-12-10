# Didimo Digital Human - Unity Project

This is a ready to play Unity project that uses the included Didimo SDK as a git submodule.



1. **Clone** (don't download) repository _recursively_.

Most git clients handle recursive submodule downloads for you, otherwise from the terminal you can clone the project with the included submodules like this:

```bash
git clone --recurse-submodules git@github.com:didimoinc/didimo-digital-human-unity-project.git
```

2. If you don't see content in the `Assets/Didimo` folder, then try:

```bash
git submodule update --init
```

3. To ensure correct didimo rendering, go to:
Unity Editor Menu → Didimo → Didimo Manager, and click the Reimport didimos button.


For further information while using the SDK, please see the [SDKs README](https://github.com/didimoinc/didimo-digital-human-unity-sdk).
