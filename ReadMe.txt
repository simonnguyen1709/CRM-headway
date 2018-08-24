test Git
@import url(http://fonts.googleapis.com/css?family=Roboto);
html,

a:hover{text-decoration: none;}
a,a:active { text-decoration: none; }
a:hover { transition: all 200ms ease-in-out; }

.dropdown-menu{
    position: absolute;
    background-color: #e9e9e9;
    font-size: 12px;
    border: 1px solid rgba(158,150,204,1);
    border-radius: 3px;
    box-shadow: 0 2px 10px rgba(148,170,214,.2);
    margin-top: 150%;
}
.avatag-sm{
    width: 40px;
    height: 40px;
    border-radius: 50%;
    border: 2px solid white;
    background-color: Gray;
    padding: 3px;
}
.avatag-sm:hover{
    box-shadow: 1px 1px 2px rgba(0,0,5,.2);
 
}

.page-container {
    min-width: 100%;
    position: relative;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
    margin: 0px auto;
}

.content {
    max-width: 800px;
    min-width: 600px;
    display: block;
    padding: 50px;
    margin: 50px auto;
    box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.1);
    background-color: #ffffff;
    overflow: hidden;
}

.page-container.sidebar-collapsed {
/*    padding-right: 65px;*/
    transition: all 100ms linear;
    transition-delay: 300ms;
}

.page-container.sidebar-collapsed-back {
    padding-right: 180px;
    transition: all 100ms linear;
}

.page-container.sidebar-collapsed .sidebar-menu {
    width: 65px;
    transition: all 100ms ease-in-out;
    transition-delay: 300ms;
}

.page-container.sidebar-collapsed-back .sidebar-menu {
    width: 180px;
    transition: all 100ms ease-in-out;
}

.page-container.sidebar-collapsed .sidebar-icon {
    transform: rotate(90deg);
    transition: all 300ms ease-in-out;
}

.page-container.sidebar-collapsed-back .sidebar-icon {
    transform: rotate(0deg);
    transition: all 300ms ease-in-out;
}

.page-container.sidebar-collapsed .logo {
    padding: 21px;
    /*height: 136px;*/
    box-sizing: border-box;
    transition: all 100ms ease-in-out;
    transition-delay: 300ms;
}

.page-container.sidebar-collapsed-back .logo {
    width: 100%;
    padding: 21px;
    /*height: 136px;*/
    box-sizing: border-box;
    transition: all 100ms ease-in-out;
}

.page-container.sidebar-collapsed #logo {
    opacity: 0;
    transition: all 200ms ease-in-out;
}

.page-container.sidebar-collapsed-back #logo {
    opacity: 1;
    transition: all 200ms ease-in-out;
    transition-delay: 300ms;
}

.page-container.sidebar-collapsed #menu span {
    opacity: 0;
    transition: all 50ms linear;
}

.page-container.sidebar-collapsed-back #menu span {
    opacity: 1;
    transition: all 200ms linear;
    transition-delay: 300ms;
}

.sidebar-menu {
    position: fixed;
    float: left;
    width: 280px;
    top: 0;
    left: 0;
    bottom: 0;
/*    background-color: #303641;*/
    background-color: #444;
    color: #aaabae;
    font-family: "Segoe UI";
    box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.5);
    z-index: 1;
}

#menu {
    list-style: none;
    margin: 0;
    padding: 0;
    margin-bottom: 20px;
    
}

#menu li {
    position: relative;
    margin: 0;
    font-size: 12px;
    border-bottom: 1px solid rgba(69, 74, 84, 0.7);
    padding: 0;
}

#menu li ul {
    opacity: 0;
    height: 0px;
}

#menu li a {
    font-style: normal;
    font-weight: 400;
    position: relative;
    display: block;
    padding: 10px 20px;
    color: #aaabae;
    white-space: nowrap;
    z-index: 2;
}

#menu li a:hover {
    color: #ffffff;
    background-color: #333944;
    transition: color 250ms ease-in-out, background-color 250ms ease-in-out;
}

#menu li.active > a {
    background-color: #2b303a;
    color: #ffffff;
}

#menu ul li { 
    /*background-color: #2b303a;*/ 
    background-color: #444; 
}

#menu ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

#menu li ul {
    position: absolute;
    visibility: hidden;
    left: 100%;
    top: -1px;
    background-color: #2b303a;
    box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.5);
    opacity: 0;
    transition: opacity 0.1s linear;
    border-top: 1px solid rgba(69, 74, 84, 0.7);
}

#menu li:hover > ul {
    visibility: visible;
    opacity: 1;
}

#menu li li ul {
    left: 100%;
    visibility: hidden;
    top: -1px;
    opacity: 0;
    transition: opacity 0.1s linear;
}

#menu li li:hover ul {
    visibility: visible;
    opacity: 1;
}

#menu .fa { margin-right: 5px; }

.logo {
    width: 100%;
    padding: 21px;
    box-sizing: border-box;
}

.sidebar-icon {
    position: relative;
    float: right;
    margin-top: 32px;
    border: 1px solid #454a54;
    text-align: center;
    line-height: 1;
    font-size: 18px;
    padding: 6px 8px;
    border-radius: 3px;
    color: #888;
    background-clip: padding-box;
    text-shadow: 4px 4px 6px rgba(0,0,0,0.4);
}

.fa-html5 {
    color: #fff;
    margin-left: 50px;
}
.nav-stacked > li + li{margin-top: 0px;}
.meme  li >  a {
  margin: 0;
  padding: 6px 10px 6px 15px;
  border: 0;
  list-style: none;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  z-index: 2;
  font-size:14px;
  font-weight: bold;
  text-decoration: none;
  color: #383838;
}
.meme > li > a:hover{
    margin-right: 10px;
    border-radius: 0px 10px 10px 0px;
    background-color: rgba(252,212,217,0.8);
 /*  color: #eb3beb;
  background: -webkit-linear-gradient(#1fa0e4, #1992d1);
  background: -moz-linear-gradient(#1fa0e4, #1992d1);
  background: -o-linear-gradient(#1fa0e4, #1992d1);
  background: -ms-linear-gradient(#1fa0e4, #1992d1);
  background: linear-gradient(#1fa0e4, #1992d1);*/
}
.meme ul>li>a:hover{background-color: rgba(252,212,207,0.8);}
.meme ul li a {
  text-decoration: none;
  font-size: 12px;
  cursor: pointer;
  z-index: 1;
  color: #01083a;

}
.menu-div:hover ul>li>ul>li a{padding-left: 25px;}
.menu-div:hover ul>li>ul>li>ul>li a{padding-left: 30px;}
.menu-div:hover ul>li>ul>li>ul>li>ul>li a{padding-left: 45px;}
.menu-name{
    cursor: pointer;
    top: 0px;
}
span[id="name"]{
    margin-left: 10px;
    display: none;
    
}
.menu-div:hover span[id="name"]{
    display: inline-block;
}
.drag{
    margin-top: 61px;
}
.nav{
    margin-bottom: 0px;
}
.menu-div{
    margin-top: 5px;
    max-width: 250px;
    overflow: hidden;
}
.menu-name{
    display: inline-block;
    cursor: pointer;
    top: 0px;
}

