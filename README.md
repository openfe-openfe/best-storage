# best-storage
    简单封装本地存储api
## 如何安装

```
 npm install best-storage
```

## 如何使用

```
 import storage from 'best-storage'
 
 // localStorage
 storage.set(key,val) 
 
 storage.get(key, def)
 
 // sessionStorage
 storage.session.set(key, val)
 
 storage.session.get(key, val)
 
```

## API

#### set(key, val)



#### get(key, def)



#### remove(key)



#### has(key)



#### clear()


#### getAll()


#### forEach(callback)
forEach the storages and call the callback function with each storage
