# npm-install-errorunexpected-end-of-json-input


# npm ERR! Unexpected end of JSON input while parsing near '...lugin-dev-expression"'

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\HP\AppData\Roaming\npm-cache\_logs\2021-05-21T02_23_24_243Z-debug.log


# This solved it for me:

# Open Windows Powershell as admin

    npm cache clean --force
