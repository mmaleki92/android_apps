

# install kivy

```bash
python -m pip install kivy[base] kivy_examples
```

```bash
python3 -m pip install buildozer
```

```bash
sudo apt-get install -y git zip unzip openjdk-8-jdk python3-setuptools autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 libssl-dev libffi-dev libsqlite3-dev libgdbm-dev libbz2-dev liblzma-dev libjpeg-dev libgl1-mesa-dev libglu1-mesa-dev

```
```bash
buildozer init
```

# build APK
```bash
buildozer -v android debug
```


After the build completes, find the APK in the bin/ directory of your project folder.


Release Build:
If you are satisfied with the debug testing, you can create a release build by modifying the buildozer.spec file to increase the version number and changing the build mode to release:

```bash
buildozer -v android release
```