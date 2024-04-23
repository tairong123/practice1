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
    width:300px;
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
@media screen and (min-width: 800px) {
    .gallery {
        column-count: 3; /* 螢幕寬度大於 800px 時使用三列排列 */
    }
}

@media screen and (max-width: 799px) {
    .gallery {
        column-count: 1; /* 螢幕寬度小於等於 799px 時變為單列排列 */
    }
}
``` 
