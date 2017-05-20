# Quickly add a tray icon to an electron app

Very basic at the moment, this module is either going nowhere or I might extend it to deal with app lifecycle management, window toggling etc.

## Usage:
```javascript

import electron from 'electron';
const app = electron.app;

import TrayControl from 'electron-tray';

const iconPath = path.join(__dirname, 'static', 'icon.png');
const trayControl = new TrayControl(app, iconPath);


```
