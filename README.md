# kindle-id
This is a Bash script that will pull the ASIN ids from an amazon kindle series page. ([like this](https://www.amazon.com/dp/B07ZTK14LG?binding=kindle_edition))

This script only reads local html files, it DOES NOT have amazon api access so attempting to use a link WILL FAIL.

You have to download a local copy of the page. This is built in to most browsers.

The output of this script is in the order the books are displayed on the series page.

## Installation
to install you can either:

1. copy "kindle-id" to /bin/\
   OR
2. copy "kindle-id" to ~/bin/ and add ~/bin to your PATH

Make sure you make "kindle-id" executable with: chmod u+rx kindle-id

You can then run the app with "kindle-id {path/to/html}"\

If you want to use this on macos, replace "grep" in "kindle-id" with "ggrep"
