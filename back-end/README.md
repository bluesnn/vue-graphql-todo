# Node Express Graphql API
vue & Node & Express GraphQL API Example

### step1 后端
进入 node-express-graphql-api
npm install cors --save

### step2 打开 index.js 文件
cors 中间件添加到 Express app 中
```javaScript
const cors = require('cors');

const  app  =  express();
app.use(cors())
```

### 启动服务器：
```javaScript
node index.js
```