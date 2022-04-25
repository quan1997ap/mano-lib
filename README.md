README.md => https://dillinger.io/

1. YAML => JSON hoặc JSON => YAML

https://www.quora.com/How-can-I-convert-YAML-into-JSON-in-JavaScript-frontend-code-not-Node

```
function YAMLtoJSON(yamlStr) { 
	var obj = YAML.parse(yamlStr); 
	var jsonStr = JSON.stringify(obj); 
	return jsonStr; 
} 

function JSONtoYAML(jsonStr) { 
	var obj = JSON.parse(jsonStr); 
	var yamlStr = YAML.stringify(obj); 
	return yamlStr; 
}
```
2. View data ( JSON / YAML /, ...)
```
ngx-highlight-js
ngx-json-viewer
```
3. Build Lib
- Cài các lib cần trong dự án => run lệnh dưới
```
npm pack .
```
- Đổi tên lib vừa build
```
npm install lib-base-1.0.0.tgz
```
