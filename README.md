<p align="center"><img src="web/static/image/icons/banner.png" alt="EveryNasa banner" title="EveryNasa"></p>

The program takes a picture from the NASA [website](https://apod.nasa.gov/apod) every day
and sets it as a background for your workspace.

---

| OS      | Status      | Latest version | Download                                                                                                       |
|---------|-------------|----------------|----------------------------------------------------------------------------------------------------------------|
| Windows | Available   | 2.1            | [.msi](https://github.com/Redume/EveryNasa/releases/download/v2.1/EveryNasa.msi)                               |
| Linux   | Available   | 2.1            | [There is no installation file but there is a separate branch](https://github.com/Redume/EveryNasa/tree/linux) |
| Android | Available   | 1.2.1          | [Play Market](https://play.google.com/store/apps/details?id=ru.murzify.everynasa)                              |
| MacOS   | Unavailable |                |                                                                                                                |
| iOS     | Unavailable |                |                                                                                                                |

---

### Solution or answers to possible problems
Any bugs / problems that are not covered by these questions, please open an [issue](https://github.com/Redume/EveryNasa/issues/new?assignees=&labels=bug&template=bug_report.md&title=Bug)

<details>
<summary>Windows</summary>
    <li>To make all functions work correctly, install the program anywhere except Program Files(x86) / Program Files</li>
</details>


<details>
<summary>Linux</summary>

- If you have a mistake with `ayatana-appindicator3-0.1`

    <details>
        <summary><b>Debian / Ubuntu / Mint</b></summary>
        <details>
            <summary><b>KDE Plasma</b></summary>

  ```shell
  $ sudo apt install gir1.2-appindicator3-0.1
  ```

  </details>
  <details>
  <summary><b>GNOME</b></summary>

    - Install the package
  ```shell
  $ sudo apt install gnome-shell-extension-appindicator
  ```
### License
```
Copyright 2022 Redume
    - Open `Tweaks`
    - Go to `Extensions`
    - Enable `Kstatusnotifieritem/appindicator support`
</details>
</details>
</details>

### License
This project is licensed under the Apache-2.0 License - see the [LICENSE](LICENSE) file for details.
   http://www.apache.org/licenses/LICENSE-2.0
  
### Third-party library licenses
- [getlantern/systray](https://github.com/getlantern/systray) — [Apache-2.0](https://github.com/getlantern/systray/blob/master/LICENSE)
- [gofiber/fiber](https://github.com/gofiber/fiber) — [MIT](https://github.com/gofiber/fiber/blob/master/LICENSE)
- [go-ole/go-ole](https://github.com/go-ole/go-ole) — [MIT](https://github.com/go-ole/go-ole/blob/master/LICENSE)
- [mattn/go-sqlite3](https://github.com/mattn/go-sqlite3) — [MIT](https://github.com/mattn/go-sqlite3/blob/master/LICENSE)
- [rodkranz/fetch](https://github.com/rodkranz/fetch) — [MIT](https://github.com/rodkranz/fetch/blob/master/LICENSE)
- [shirou/gopsutil](https://github.com/shirou/gopsutil) — [BSD-3](https://github.com/shirou/gopsutil/blob/master/LICENSE)
- [skratchdot/open-golang](https://github.com/skratchdot/open-golang) — [MIT](https://github.com/skratchdot/open-golang/blob/master/LICENSE)
- [twbs/bootstrap](https://github.com/twbs/bootstrap) — [MIT](https://github.com/twbs/bootstrap/blob/main/LICENSE)