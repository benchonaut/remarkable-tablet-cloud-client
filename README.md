# remarkable-tablet-cloud-client


`sudo apt-get update && sudo apt-get install libkf5archive5 libqt5xml5 libqt5websockets5 qml-module-qt-labs-platform qtquickcontrols2-5-dev
`

 To start the client, simply execute reMarkable in your terminal. If you want to start it via your desktop menu, create a file and copy it to /usr/share/applications/remarkable.desktop containing

```
[Desktop Entry]
Version=1.0
Type=Application
Name=reMarkable Desktop Client
GenericName=Desktop Client
Comment=reMarkable Desktop Client
Exec=reMarkable
Icon=accessories-text-editor
Terminal=false
Categories=Graphics;Office;
```
