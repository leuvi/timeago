## 安装:

```javascript
npm install sweet-time-ago --save
```

## 使用:

```javascript
import timeAgo from 'sweet-time-ago'

timeAgo(Date.now())  //刚刚
timeAgo(1498924800000)  //4周前
timeAgo('2017-07-24')  //2天前
timeAgo('2017/07/25')  //昨天
timeAgo('2017.7.25')  //昨天
timeAgo('2017 07 25')  //昨天
timeAgo('2017年7月25日')  //昨天
```

