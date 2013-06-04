* #### onUpdate
对Collection中Model更新的监听方法  
    * delta： 更新数据组成的数组
```js
session.collectionName.onUpdate = function (delta) {
  //todo dom operations
}
```

* #### onInsert
对Collection中Model新增的监听方法  
	* delta: 新政数据组成的数组
	
```js
session.collectionName.onInsert = function (delta) {
	//todo dom operations
}
```

* #### onDelete
对Collection中Model删除的监听方法 
	* delta: 被删除数据组成的数组
```js
session.collectionName.onDelete = function (delta) {
	//todo dom operations
}
```



