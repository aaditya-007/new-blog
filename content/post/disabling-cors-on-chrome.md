+++
title = "Disabling CORS on MacOS for Chrome"
description = ""
date = 2020-04-20T02:13:50Z
author = "Aditya Tibrewal"
+++

At times we want data to be fetched from different origin. But browser disallows this due to the browser security.

Run this on terminal

`open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="/tmp/chrome_dev_test" --disable-web-security`

This opens a chrome instance with few security feauture disabled.








