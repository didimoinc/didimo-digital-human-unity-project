# Didimo Digital Human - Unity Project

This is a ready to play Unity project that uses the included Didimo SDK as a git submodule.

Please ensure you clone the repository _recursively_ when using your git client. 

Otherwise, from the terminal you can clone the project with the included submodules like this:

```bash
git clone --recurse-submodules git@github.com:didimoinc/didimo-digital-human-unity-project.git
```

If you don't see content in the `Assets/Didimo` folder, then try:

```bash
git submodule update --init
```


For further information while using the SDK, please see the [SDKs README](https://github.com/didimoinc/didimo-digital-human-unity-sdk]).