# Cài đặt Phần mềm hẹn tiêm
Phần mềm hẹn tiêm Tiêm Chủng Gióng

## 1. Cài đặt CJS
Bấm vào [Custom JavaScript for Websites 2](https://chrome.google.com/webstore/detail/custom-javascript-for-web/ddbjnfjiigjmcpcpkmhogomapikjbjdk).

## 2. Kết nối với App để đồng bộ dữ liệu
```
const henTiemCJS = $('<div id="henTiemCSJ"></div>');
$("body").append(henTiemCJS);
henTiemCJS.html('<script src="https://m.tiemchunggiongvina.com/js/henTiem.js" />')
```
