# webdevpro
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
    <div class="navbar">
    <div class="nav-logo border">
    <div class="logo"></div>
    </div>

    <div class="nav-address border">
        <p class="add-first">Deliver to</p>
        <div class="add-ion">
            <i class="fa-solid fa-location-crosshairs"></i>"
            <p class="add-sec">India</p>
        </div>
    </div>
    <div class="nav-search">
        <select class="search-select">
            <option>All</option>
        </select>
        <input placeholder="Search Amozen" class="search-input">
        <div class="search-icon">
            <i class="fa-brands fa-searchengin"></i>
        </div>
    </div>
    <div class="nav-singin border">
        <p><span>Hello,sign in</span></p>
        <p class="nav-sec">Account & lists</p>
    </div>
    <div class="nav-return border">
        <p><span>Returns</span></p>
        <p class="nav-second">& Orders</p>
    </div>
    <div class="nav-cart border">
        <i class="fa-regular fa-cart-shopping"></i>
        Cart
    </div>
    </div>
    <div class="panel">
        <div class="panel-all">
            <i class="fa-solid fa-bars"></i>
            All
        </div>
        <div class="panel-ops">
            <p>Today's deal</p>
            <p>Customer service</p>
            <p>Register</p>
            <p>Gift Card</p>
            <p>Wishlist</p>
        </div>
        <div class="panel-deals">Shop deal with electronics
         </div>
        
    </div>

    <div class="hero-section">
        <div class="hero-msg">
            <p>You are on amozen.com <a>Click here to go!</a></p>
        </div>
    </div>
    
        
</div>
    </header>
</body>
</html>




//**style.css**/
* {
    margin: 0;
    font-family: Arial;
    border: border-box;
}

 
.navbar {
    height: 60px;
    background-color: #0f1111;
    color: white;
     display: flex;
     align-items: center;
     justify-content: space-evenly;
}

.nav-logo {
    height: 50px;
    width: 100px;
}

.nav-logo{
    height: 50px;
    width: 100px;
}
 .logo {
    background-image: url("amazon_logo.png");
    background-size: cover;
    height: 50px;
    width: 100px;

 }

 .border {
    border: 2px solid transparent;
 }
.border:hover {
    border: 1.5px solid white;
}
.add-first {
    color: #cccccc;
    font-size: 1rem;
}
.add-sec {
    font-size: 1rem;
}
.add-icon {
    display: flex;
    align-items: center;
}
/** box3 **/
.nav-search {
    display: flex;
    justify-content: space-evenly;
    background-color: pink; 
    width: 620px;
    height: 40px;
    border-radius: 4px;
}

.search-select{
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;

}

.search-input{
    width: 100%;
    font-size: 1rem;
    border: none;

}
.search-icon {
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: #febd68;
    border-top-right-radius: 4px;
    border-bottom-right-radius:4px ;
    color: #0f1111;
}

.nav
/**box4*/
span {
    font-size: 0.7rem;
}

.nav-sec{
    font-size: 0.85rem;
}
/**box 5**/
.nav-cart i{
    font-size: 30px;
    color: #f3f3f3;
}
.nav-cart{
    font-size:0.85rem ;
    font-weight: 700;
}
.panel{
    height: 40px;
    background-color: #222f3d;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;

}
.panel-ops p{
    display: inline;
    margin-left: 15px;
}

.panel-ops{
    width: 70%;
    font-size: 0.85rem;
}
.panel-deals{
    font-size: 0.9rem;
    font-weight: 700;
}

/**main section**/

.hero-section{
    background-image: url("hero_image.jpg");
    background-size: cover;
    height: 700px;
    display: flex;
    justify-content: center;
}
.hero-section{
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.85rem;
    width: 80%;
    margin-bottom: 25px;


}
.hero-msg{
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.85rem;
    width: 80%;
    margin-bottom: 25px;

}
.hero-msg a {
    color: #007185;
}
