# MimbleWimble Coin Address Tester

You can use this utility to test if a MimbleWimble Coin address is reachable by going [here](https://htmlpreview.github.io/?https://github.com/NicolasFlamel1/MimbleWimble-Coin-Address-Tester/blob/master/index.html). This utility supports testing HTTP, Tor, and MQS addresses.

It's recommended that you use this utility with your web browser's CORS restrictions and mixed-content restrictions disabled so that it can successfully test addresses that don't provide responses with CORS headers and addresses that use insecure protocols. [MQS addresses don't currently provide responses with CORS headers](https://github.com/mwcproject/mwcmqs/pull/1).

On **Windows** you can open Chrome with its CORS restrictions and mixed-content restrictions disabled by running the following command in a command prompt:
```
"C:\Program Files\Google\Chrome\Application\chrome.exe" --user-data-dir="C:\chrome_test" --disable-web-security --allow-running-insecure-content
```
On **macOS** you can open Chrome with its CORS restrictions and mixed-content restrictions  disabled by running the following command in a terminal:
```
open -n -a "/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --args --user-data-dir="/tmp/chrome_test" --disable-web-security --allow-running-insecure-content
```
On **Linux** you can open Chrome with its CORS restrictions and mixed-content restrictions  disabled by running the following command in a terminal:
```
google-chrome --user-data-dir="/tmp/chrome_test" --disable-web-security --allow-running-insecure-content
```
