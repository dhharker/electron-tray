# Quickly add a tray icon to an electron app

Very basic at the moment, this module is either going nowhere or I might extend it to deal with app lifecycle management, window toggling etc.

## Usage:
```javascript
const trayControl = new TrayControl(electron.app, iconPath[, menu]);
```

### Example:
```javascript
import electron from 'electron';
const app = electron.app;

import TrayControl from 'electron-tray';

const iconPath = path.join(__dirname, 'icon.png');
// Keep this reference around otherwise the icon will vanish when the TrayControl instance gets GCed
const trayControl = new TrayControl(app, iconPath);


```
