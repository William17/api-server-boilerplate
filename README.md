## /api， /api/admin/v1, /api/user/v1, /api/public/v1  
/api目录用来放所有接口函数， 接口可能分组， 可以下面有`admin`, `public`, `user`分组， 每个接口可能有不同的版本， 所以每个版本下有`v1`，应对将来的多版本  

## /model, /model/v1
用来放数据模型， 数据模型可能有不兼容修改， 所以模型也以目录区分版本  

## log.js  
输出一个log函数  

## session.js  
输出一个session中间件


