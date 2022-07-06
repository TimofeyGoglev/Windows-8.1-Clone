<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
body{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    box-sizing: border-box;margin: 0;padding: 0;
    background-color: rgb(14, 8, 74);
}
/*Windows*/
.windows:hover{
    border: 1px solid rgba(59, 26, 97, 0.66);
}
.window-1{
    position: fixed;top: 172px;left: 120px;
    width: 248px;height: 120px;

}
.window-2{
    position: fixed;top: 300px;left: 120px;
}
.window-3{
    position: fixed;top: 300px;left: 248px;
}
.window-4{
    position: fixed;top: 428px;left: 120px;
    width: 248px;height: 120px;
}
.window-5{
    position: fixed;top: 556px;left: 120px;
}
.window-6{
    position: fixed;top: 556px;left: 248px;
}
.window-7{
    position: fixed;top: 172px;left: 376px;
}
/*Header*/
#text-1{
    font-weight: lighter;font-size: 56px;
    color: #fff;
    position: fixed;top: -16px;left: 115px;
}
/*Img background*/
#fon{
    left: 1148px;
    position: fixed;
}
/*POP-UP*/
.button{
    margin-top: 40px;
    text-align: center;
}

.button a{   
    position: fixed;left: 1777px;top: 63px;
    color: #fff;  
}
.button a:hover{
    position: fixed;left: 1766px;top: 54px;
    padding: 9px 11px;
    background-color: rgba(60, 22, 149, 0.581);
}

.pop_up{
    display: none;
    width: 100%;
    height: 100%;
    position: fixed;
    left: 0;
    top: 0;
    
    z-index: 2;
}

.pop_up.active{
    display: block;
}

.pop_up_container{
    display: flex;
    width: 100%;
    height: 100%;
}

.pop_up_body{ 
    height: 134px;
    width: 194px;
    border: 2px rgb(42,42,42) solid;
    background-color: white;
    z-index: 99998;
    text-align: center;
    position: fixed;
    top: 110px;left: 1690px;
}

.pop_up_body p{
    font-size: 28px;
    font-family: Montserrat;
    font-weight: 608;
    color: #222620;
    margin-bottom: 48px;
}

.pop_up_body input {
    display: block;
    margin: 25px auto 0px auto;
    width: 330px;
    padding: 17px 28px;
    background-color: #E5E5E5;
    border-radius: 18px;
    border: none;
    font-family: Montserrat;
    font-weight: 508;
    font-size: 18px;
    color: #89909F;
}
.pop_up_body input:focus {
    outline: none;
}

.pop_up_body button {
    
    
    
    
    
    
    
    color: #fff;
    
    
}

.pop_up_close {
    position: relative;left: -1px;
    z-index: initial;
    background-color: rgba(255, 0, 0, 0);
    width: 2100px;
    height: 1110px;
    
}
/*header-text*/
#User{
    color: #fff;
    font-weight: lighter;font-size: 31px;
    position: fixed;left: 1640px;top: 26px;
    }
#avatar{
    width: 40px;height: 40px;
    position: fixed;left: 1714px;top: 60px;
}
#top-text{
    color: #fff;
    font-size: 56px;font-weight: lighter;
    position: fixed;top: -16px;left: 115px;
}
/*POP-UP-2*/
.button2{
    margin-top: 40px;
    text-align: center;
}

.button2 a{
    
    background-color: orange;
    
   
    text-decoration: none;
    color: #fff;
    font-weight: 500;
}

.pop_up2{
    display: none;
    width: 100%;
    height: 100%;
    position: fixed;
    left: 0;
    top: 0;
    
    z-index: 2;
}

.pop_up2.active{
    display: block;
}

.pop_up_container2{
    display: flex;
    width: 100%;
    height: 100%;
}

.pop_up_body2{
    margin: auto;
    width: 500px;
    background-color: #fff;
    
    text-align: center;
    padding: 100px 15px 110px 15px;
    position: relative;
    top: 200px;
}

.pop_up_body2 p{
    font-size: 28px;
    
    color: #222620;
    margin-bottom: 48px;
}

.pop_up_body2 input {
    display: block;
    margin: 25px auto 0px auto;
    width: 330px;
    padding: 17px 28px;
    background-color: #E5E5E5;
    
    border: none;
    
    
    font-size: 18px;
    color: #89909F;
}


.pop_up_body2 button {
    cursor: pointer;
    display: block;
    
   
    height: 134px;
    width: 194px;
    border: 2px rgb(42,42,42) solid;
    background-color: white;
    z-index: 99998;
    font-size: 16px;
    border: none;
    color: #fff;
    
    background-color: orange;
}

.pop_up_close2 {
    position: absolute;
    top: 15px;
    right: 15px;
    font-size: 21px;
    cursor: pointer;
}
#open_pop_up2:hover{
    padding: 29px 80px;
    background-color: rgba(60, 22, 149, 0.581);
    position: fixed;left: 1613px;top: 51px;
}
/*BODY POP-UP*/
#a-1{
    color: black;
    position: fixed;
    text-decoration: none;font-size: 16px;font-weight: 600;
    left: 1712px;top: 125px;
}
#a-1:hover{
    background-color: rgba(141, 140, 140, 0.279);
    padding: 10px 21px;
    position: fixed;top: 115px;left: 1691px;
}

#a-2{
    color: black;
    position: fixed;left: 1713px;top: 170px;
    text-decoration: none;font-size: 16px;font-weight: 600;
}
#a-2:hover{
    background-color: rgba(141, 140, 140, 0.279);
    padding: 10px 22px;
    position: fixed;left: 1691px;top: 160px;
    width: 102px;
    
}

#a-3{
    color: black; 
    position: fixed;left: 1713px;top: 211px;
    text-decoration: none;font-size: 16px;font-weight: 600;
}
#a-3:hover{
    background-color: rgba(141, 140, 140, 0.279);
    padding: 10px 22px;
    position: fixed;top: 201px;left: 1691px;
}
</style>
<body>
    <!---Windows-->
    <div class="windows">
        <a href=""><div class="window-1">
            <img src="Img-menu/tiles/desktop.png" alt="">
        </div></a>
        <a href=""><div class="window-2">
            <img src="Img-menu/tiles/NEWsettengs2014.png" alt="">
        </div></a>
        <a href=""><div class="window-3">
            <img src="Img-menu/tiles/calc.png" alt="">
        </div></a>
        <a href=""><div class="window-4">
            <img src="Img-menu/tiles/mail.png" alt="">
        </div></a>
        <a href=""><div class="window-5">
            <img src="Img-menu/tiles/music.png" alt="">
        </div></a>
        <a href=""><div class="window-6">
            <img src="Img-menu/tiles/ie.png" alt="">
        </div></a>
        <a href=""><div class="window-7">
            <img src="Img-menu/tiles/oknastore.png" alt="">
        </div></a>
    </div>
    <!---header-->
    <!--POP-UP-2-->
    <div class="button2">
        <a href="#" id="open_pop_up2">
            <p id="User">User</p>
            <img src="Img-menu/avatar.png" id="avatar">
        </a>
    </div>
  
    <div class="pop_up2" id="pop_up2">
        <div class="pop_up-container2">
            <div class="pop_up_body2" id="pop_up_body2">
                <h1>Hello, my window</h1>
                  <div class="pop_up_close2" id="pop_up_close2">&#10006</div>
            </div>
        </div>
    </div>
    <!---POP-UP-2-END-->
        <p id="top-text">Пуск</p>
    
    <!--POP-UP-->
    
    <div class="button">
        <a href="#" id="open_pop_up"><img src="Img-menu/icons/rst.png" alt=""></a>
    </div>
  
    <div class="pop_up" id="pop_up">
        <div class="pop_up_close" id="pop_up_close">f</div>
        <div class="pop_up-container">
            <div class="pop_up_body" id="pop_up_body">
                   <a href="" id="a-1">Завершение работы</a>
                   <a href="" id="a-2">Перезагрузка</a>
                   <a href="" id="a-3">Recovery</a>
                  
            </div>
        </div>
    </div>
    <!---img background--
     <img src="Img-menu/tiles/2014_1_end.png" id="fon">-->
</body>
<script>
    const openPopUp = document.getElementById('open_pop_up');
const closePopUp = document.getElementById('pop_up_close')
const popUp = document.getElementById('pop_up')

openPopUp.addEventListener('click', function(e){
    e.preventDefault();
    popUp.classList.add('active');
})

closePopUp.addEventListener('click', () => {
    popUp.classList.remove('active');
})  
</script>
<!---2-->
<script>
    const openPopUp2 = document.getElementById('open_pop_up2');
const closePopUp2 = document.getElementById('pop_up_close2')
const popUp2 = document.getElementById('pop_up2')

openPopUp2.addEventListener('click', function(e){
    e.preventDefault();
    popUp2.classList.add('active');
})

closePopUp2.addEventListener('click', () => {
    popUp2.classList.remove('active');
})
</script>
</html>
