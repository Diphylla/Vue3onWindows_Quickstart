# Vue3onWindows Quickstart Installation
*This is a recreation from the notes I made along the installation process, idk it might be wrong or outdated at some point.
I recommend you use Linux or Apple.
Created: 05.12.2024 for current latest version.*

**0.** cmd `set-executionpolicy remotesigned`

**1.** https://github.com/coreybutler/nvm-windows
  - latest release (download & run)
  - confirm cmd: `nvm -v`
  - copy [version]
  
**2.** `nvm install node`
  - `nvm use [version]`
  
**3.** `npm install -g @vue/cli`

**4.** `npm create vue@latest`

---

## Bonus: Bootstrap
`npm install bootstrap popper,js jquery --save-dev`

in main.js:

```
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap";
```
