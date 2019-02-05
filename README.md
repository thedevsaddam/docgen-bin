# Docgen binary

Transform your postman collection to html documentation

## Download

| OS      	| x86                                                                                      	| x86_64                                                                                      	|
|---------	|------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------	|
| Mac     	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2/mac_x86.zip)     	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2/mac_x86_64.zip)     	|
| Linux   	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2/linux_x86.zip)   	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2/linux_x86_64.zip)   	|
| FreeBSD 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2/freebsd_x86.zip) 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2/freebsd_x86_64.zip) 	|
| Windows 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2/windows_x86.zip) 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/v2/windows_x86_64.zip) 	|


### Installation
Mac/Linux download the binary and unzip it then follow the instruction below
```bash
$ cp docgen /usr/local/bin/docgen
$ sudo chmod +x /usr/local/bin/docgen
```
**For windows download the binary and set environment variable so that you can access the binary from terminal**

### Available features
* Live postman collection to documentation
* Build postman collection to html/markdown documentation
* Supports multi-level collection build

### Usage
* To see live documentation from postman collection use `docgen server -f input-postman-collection.json -p 8000` This will open the html version of postman collection to the defined port
* To build a HTML documentation use `docgen build -i input-postman-collection.josn -o ~/Downloads/index.html`
* To build a Markdown documentation use `docgen build -i input-postman-collection.josn -o ~/Downloads/index.md -m`

### Screenshot
![Docgen](https://raw.githubusercontent.com/thedevsaddam/docgen/v2/screenshot.png)
