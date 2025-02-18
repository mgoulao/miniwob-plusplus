# Setup

Follow the instructions below to setup the Python interface.

## Install the MiniWoB++ Library

Inside the repository directory, run

```sh
pip install .
```

If this gives you problems, try again and add pip's `--ignore-installed` flag.

## Install Chrome/Chromium and ChromeDriver

We strongly recommend using Chrome or Chromium as the web browser,
as other browsers may render the environments differently.

The MiniWoB++ Python interface uses [Selenium](https://www.selenium.dev/documentation/webdriver/),
which interacts with the browser via the [WebDriver API](https://w3c.github.io/webdriver/).
If you use Google Chrome as the web browser, follow one of the
[instruction methods](https://www.selenium.dev/documentation/webdriver/getting_started/install_drivers/)
to install ChromeDriver. The simplest method is to download
[ChromeDriver](https://chromedriver.chromium.org/downloads) with the matching version,
unzip it, and then add the directory containing the `chromedriver` executable to the `PATH` environment variable:

```sh
export PATH=$PATH:/path/to/chromedriver
```

For Chromium, the driver may also be available in a software package; for example, in Debian/Ubuntu:

```sh
sudo apt install chromium-driver
```
