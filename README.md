*{
    padding: 0;
    margin: 0;/* Reset Css*/
    box-sizing: border-box;

}
#header{
    height: 46px;
    background-color: black;
    color: white;
    top: 0px;
    left: 0px;
    right: 0px;
    position: fixed;
    z-index: 1;

}
#nav{
    display: inline-block;
}

#nav li a{
    color: #ccc;
    padding-left: 24px;
    padding-right: 24px;
    line-height: 46px;
    text-decoration: none;
    display: block;
}
#nav > li{
    display: inline-block;
}
#nav > li > a{
    text-transform: uppercase;/*viết hoa*/
}
#slider{
    font-size: 25px;
    position: relative;/*đè lên layout*/
    margin-top: 46px;
    padding-top: 50%;
    background-color: rgb(0, 0, 0);
    background: url(/img/NTR_2524.jpg) top center / cover no-repeat;
    
}
#slider .text-content{
    color: rgb(14, 3, 3);
    position: absolute;/*vị trí*/
    bottom: 100px;
    text-align: center;
    left: 50%;
    transform: translateX(-50%);


}
#nav .nav-arrow-down{
    font-size: 12px;
}
.subnav li{
    list-style-type: none; /* bỏ dấu chấm cạnh chữ*/
    background-color: rgb(144, 122, 243);

}   
#nav .subnav a{
    color :#000;
    padding: 0 25px;
    line-height: 30px;
}
#nav li:hover .subnav{
    display: block;/*hiện class cấp 2*/
}
#nav .subnav{
    display: none;/*ẩn clas*/
    position: absolute;/*hiện subnav không bị đẩy nav*/
    background-color: #ccc;
}
#nav > li{
    display: inline-block;/*cho phép thiết lập chiều rộng và chiều cao trên phần tử.*/
}
#nav .subnav li:hover a,
#nav > li:hover > a{
    background-color: rgba(106, 127, 245, 0.795);
    color: rgb(0, 0, 0);
}
