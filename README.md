# nextjs11_12mongo

 Version: 0.9.1

 Author  : Kouji Nakashima / kuc-arc-f.com

 date    : 2021/11/06

 update  :

***
### Summary

Next.js 11 + apollo-server-micro + mongoDB Atlas, sample

***
### Setup

* npm install

* next.config.js : MONGODB_URI: mongodb+srv setting, user, password, cluster, dbname
```
MONGODB_URI: "mongodb+srv://username:<<password>>@cluster0.db1234.mongodb.net/dbname",
```

* apollo-client.ts

uri: if change domain, setting require
```
uri: 'http://localhost:3000/api/graphql',
```

***
### Start server
* start :

yarn dev

***
### Blog:

https://zenn.dev/knaka0209/books/2f0e049833a8c4/viewer/61c80c

***

