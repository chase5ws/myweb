CSS

/* 讓內部元素預設橫著排 */

display: flex;

/* 調整flex內部元素的排列方式 flex-end靠右 */

justify-content: center;

/* 空間不夠，就換行 */

flex-wrap: wrap;

/* 讓超出的內容隱藏 */

overflow: hidden;

圖片
.card-img {

    width: 100%;
    
    height: 50%;
    
    display: block;
    
}

特效部分

.card {
    
    box-shadow: 0px 5px 3px rgba(0, 0, 0, 0.4);

    transform: scale(.95);

}

.card-title {

    transition: all .5s ease;

}

.card:hover {

    box-shadow: 0px 25px 20px rgba(102, 95, 95, 0.315);
    
    background: rgb(245, 245, 245);
    
    transform: scale(1);

}




