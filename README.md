第一題
.gallery img{
    width:180px;
    height: 130px;
    margin: 5px;
    position: relative;
    transition: transform 0.3s ease-in-out; /* 平滑轉場效果 */
}
第二題
修改
.gallery img{
    width:auto;
    height: auto;
    margin: 5px;
    max-width: 400px;
    transition: transform 0.3s ease-in-out; /* 平滑轉場效果 */
    object-fit: contain;
}
