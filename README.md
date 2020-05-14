# Docgen binary

Transform your postman collection to html documentation

## Download

| OS      	| x86                                                                                      	| x86_64                                                                                      	|
|---------	|------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------	|
| Mac     	| Download | [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/latest/mac_amd64)     	|
| Linux   	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/latest/linux_386)   	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/latest/linux_amd64)   	|
| Windows 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/latest/windows_386.exe) 	| [Download](https://github.com/thedevsaddam/docgen-bin/blob/master/latest/windows_amd64.exe) 	|


#### Installation on Mac/Linux
```bash
curl https://raw.githubusercontent.com/thedevsaddam/docgen/v3/install.sh -o install.sh && sudo chmod +x install.sh && sudo ./install.sh
```

**For windows download the binary and set environment variable so that you can access the binary from terminal**

#### [Download Binary](https://github.com/thedevsaddam/docgen-bin/tree/master/latest)

### Available features
* Live postman collection to documentation
* Build postman collection to HTML/Markdown documentation
* Supports multi-level collections

### Usage
* To view live HTML documentation from postman collection use `docgen server -f input-postman-collection.json -p 8000` This will open the html version of postman collection to the defined port
* To view live Markown documentation from postman collection use `docgen server -f input-postman-collection.json -p 8000 -m` This will open the markdown version of postman collection to the defined port
* To make HTML documentation use `docgen build -i input-postman-collection.json -o ~/Downloads/index.html`
* To make Markdown documentation use `docgen build -i input-postman-collection.json -o ~/Downloads/index.md -m`
* Use `-s` flag to sort API in lexical order

### Screenshot
![Docgen](https://raw.githubusercontent.com/thedevsaddam/docgen/v3/screenshot.png)
