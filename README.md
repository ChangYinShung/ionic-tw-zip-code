### ionic-tw-zip-code 臺灣郵遞區號

### Installation
Dependency plugin : `lodash`、`ionic-modal-select`

[ionic-modal-select] https://github.com/inmagik/ionic-modal-select 


```html
<sciprt src="twZipCode.directive.js"></script>
```

```javascript
angular.module('myApp', [
  'YC.Ionic.UI'
]);
```

### Usage
```html
<tw-zip-code county="Ctrl.Data.Shipment.County" district="Ctrl.Data.Shipment.District" zipcode="Ctrl.Data.Shipment.ZipCode"></tw-zip-code>
````
### 說明
`County` : 縣市  
`district` : 鄉鎮區  
`zipcode` : 郵遞區號
