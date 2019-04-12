# Docgen binary

Transform your postman collection to html documentation

## Download

| OS      	| x86                                                                                      	| x86_64                                                                                      	|
|---------	|------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------	|
| Mac     	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2.3/mac_386.zip)     	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2.3/mac_amd64.zip)     	|
| Linux   	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2.3/linux_386.zip)   	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2.3/linux_amd64.zip)   	|
| FreeBSD 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2.3/freebsd_386.zip) 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2.3/freebsd_amd64.zip) 	|
| Windows 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2.3/windows_386.zip) 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2.3/windows_amd64.zip) 	|


## Installation

#### Mac
```bash
brew tap thedevsaddam/cli https://github.com/thedevsaddam/homebrew-cli.git
brew install docgen
```

#### Linux
Download the binary and unzip it then follow the instruction below
```bash
$ cp docgen /usr/local/bin/docgen
$ sudo chmod +x /usr/local/bin/docgen
```

#### Windows
**For windows download the binary and set environment variable so that you can access the binary from terminal**

### Available features
* Live postman collection to documentation
* Build postman collection to html/markdown documentation
* Supports multi-level collection build

### Usage
* To view live HTML documentation from postman collection use `docgen server -f input-postman-collection.json -p 8000` This will open the html version of postman collection to the defined port
* To view live Markown documentation from postman collection use `docgen server -f input-postman-collection.json -p 8000 -m` This will open the html version of postman collection to the defined port
* To make HTML documentation use `docgen build -i input-postman-collection.json -o ~/Downloads/index.html`
* To make Markdown documentation use `docgen build -i input-postman-collection.json -o ~/Downloads/index.md -m`

### Screenshot
![Docgen](https://raw.githubusercontent.com/thedevsaddam/docgen/v2/screenshot.png)
