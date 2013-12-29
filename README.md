# DashMate

[Dash](http://kapeli.com/dash) integration for TextMate

"Dash gives you instant offline access to 80+ API documentation sets"

## Installation

To install, clone this repository into the Bundles folder.

### TextMate 2

Copy and paste the following commands in your terminal

Make sure the Bundles directory exists

```mkdir -p ~/Library/Application\ Support/Avian/Bundles/```

Clone the bundle

```bash
git clone \
https://github.com/ram-nadella/DashMate.tmbundle.git \
~/Library/Application\ Support/Avian/Bundles/DashMate.tmbundle
```

### TextMate 1

Make sure the Bundles directory exists

```mkdir -p ~/Library/Application\ Support/TextMate/Bundles/```

Clone the bundle

```bash
git clone \
https://github.com/ram-nadella/DashMate.tmbundle.git \
~/Library/Application\ Support/TextMate/Bundles/DashMate.tmbundle
```

### Alternate method

You can also install the bundle by just downloading and double clicking it

[Download a zip archive](https://github.com/ram-nadella/DashMate.tmbundle/archive/master.zip) of this repository, unzip and rename it to remove anything after .tmbundle, confirm the extension change and double click it

(Don't forget to install Dash if you don't have it already)

## Usage

* ⌘D will lookup the current word or selection in Dash
* ^D will lookup the current word or selection in Dash and automatically enable/disable docsets based on your current language scope

## Contributions

Can you make this better? Fork and submit a pull request!
