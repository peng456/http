# http
图解http协议。算是看完了，还差不到一章吧。在此记录，有输出。


书看完。感觉应该写blog 。一个是cookie 的 。一个是 https。还有本文。

http 协议 是建立在tcp 协议之上的协议。这涉及到网络分层的知识。现在先不写。以后有时间写。


http 客户端、服务器通信协议。

三次握手、四次挥手  发生在 TCP 协议层，不是http 层。

http 协议

header  + 空行   + body

header分两种  请求header 、响应header。


请求header  ====》  请求行   +   请求首部字段  + 通用首部字段 + 实体首部字段  + 其他  

响应header  ====》  状态行   +   响应首部字段  + 通用首部字段 + 实体首部字段  + 其他


请求行  ===》  方法/协议/版本

状态行 ===》  协议/版本 状态码 解释语


主要就是状态码    还有  字段（有时间写）
状态码：
（https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Status）  

100  系列  200 系列  300系列   400 系列  500系列。

100 Continue  

101 Switching Protocol

102 Processing (WebDAV)

200 OK  

202 Accepted

203 Non-Authoritative Information

204 No Content

205 Reset Content

206 Partial Content

207 Multi-Status 

208 Multi-Status

226 IM Used

300 Multiple Choice

301 Moved Permanently

302 Found

303 See Other

304 Not Modified

305 Use Proxy

306 unused

307 Temporary Redirect

308 Permanent Redirect

400 Bad Request

401 Unauthorized

402 Payment Required

403 Forbidden

404 Not Found

405 Method Not Allowed

406 Not Acceptable

407 Proxy Authentication Required

408 Request Timeout

409 Conflict

410 Gone

411 Length Required

412 Precondition Failed


413 Payload Too Large

414 URI Too Long

415 Unsupported Media Type

416 Requested Range Not Satisfiable

417 Expectation Failed

418 I'm a teapot

421 Misdirected Request

422 Unprocessable Entity (WebDAV)

423 Locked (WebDAV)

424 Failed Dependency (WebDAV)

426 Upgrade Required

428 Precondition Required

429 Too Many Requests

431 Request Header Fields Too Large

451 Unavailable For Legal Reasons

500 Internal Server Error

501 Not Implemented

502 Bad Gateway

503 Service Unavailable

504 Gateway Timeout

505 HTTP Version Not Supported

506 Variant Also Negotiates

507 Insufficient Storage

508 Loop Detected (WebDAV)

510 Not Extended

511 Network Authentication Required








