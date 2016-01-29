LauncherV3
==========
Fork of the V3 Technic Launcher that allows for replacing the branding, default packs etc

Building
========
```bash
git clone --recursive https://github.com/disconsented/LauncherV3
cd LauncherV3
chmod +x gradlew
./gradlew clean && ./gradlew build shadowJar
```
To rebuild just type `./gradlew clean && ./gradlew build shadowJar` again.

Most values are adjusted within gradle.properties and branding is done by replacing the files inside /src/main/resources/.

urlDiscover replaces the [webpage](http://api.technicpack.net/discover/) used within the discovery tab.
urlNews replaces the news feed see [this](http://api.technicpack.net/news?build=404) for an example.
urlSponsor replaces the sponsor link in the bottom right corner of the launcher.
urlVersion replaces where the launcher looks for updates see [this](http://api.technicpack.net/launcher/version/stable4) for an example.
