## 第一題
``` css
.gallery img{
    width:180px;
    height: 130px;
    margin: 5px;
    position: relative;
    transition: transform 0.3s ease-in-out; /* 平滑轉場效果 */
}
```

## 第二題
修改
``` css
.gallery img{
    width:180px;
    height: auto;
    margin: 5px;
    max-width: 400px;
    transition: transform 0.3s ease-in-out; /* 平滑轉場效果 */
    object-fit: contain;
}
```
## 第三題
修改
``` css
.gallery{
    column-count:3;
    column-gap: 10px;
}

.gallery img{
    width: 100%;
    height: auto;
    margin: 5px;
    max-width: 400px;
    transition: transform 0.3s ease-in-out; /* 平滑轉場效果 */
    object-fit: contain;
}
``` 
