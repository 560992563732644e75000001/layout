/*
Author: W3layout
Author URL: http://w3layouts.com
License: Creative Commons Attribution 3.0 Unported
License URL: http://creativecommons.org/licenses/by/3.0/
*/
/* reset */
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,dl,dt,dd,ol,nav ul,nav li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline;}
article, aside, details, figcaption, figure,footer, header, hgroup, menu, nav, section {display: block;}
ol,ul{list-style:none;margin:0;padding:0;}
blockquote,q{quotes:none;}
blockquote:before,blockquote:after,q:before,q:after{content:'';content:none;}
table{border-collapse:collapse;border-spacing:0;}
/* start editing from here */
a{text-decoration:none;}
.txt-rt{text-align:right;}/* text align right */
.txt-lt{text-align:left;}/* text align left */
.txt-center{text-align:center;}/* text align center */
.float-rt{float:right;}/* float right */
.float-lt{float:left;}/* float left */
.clear{clear:both;}/* clear float */
.pos-relative{position:relative;}/* Position Relative */
.pos-absolute{position:absolute;}/* Position Absolute */
.vertical-base{	vertical-align:baseline;}/* vertical align baseline */
.vertical-top{	vertical-align:top;}/* vertical align top */
.underline{	padding-bottom:5px;	border-bottom: 1px solid #eee; margin:0 0 20px 0;}/* Add 5px bottom padding and a underline */
nav.vertical ul li{	display:block;}/* vertical menu */
nav.horizontal ul li{	display: inline-block;}/* horizontal menu */
img{max-width:100%;}
/*end reset*/
body{
	font-family:Arial, Helvetica, sans-serif;
	background:#fff;
	font-weight:100%;
}
.wrap{
	width:100%;
	margin:0 auto;
}
.header{
	background: url(../images/bg.jpg)no-repeat;
	padding: 10px;
}
.product-header{
	background: url(../images/product-bg.png)no-repeat;
	padding:20px 10px;
}
.logo{
	text-align:center;
}
/*--menu--*/
.cssmenu{
	text-align:center;
}
.cssmenu > ul > li {
	display: inline-block;
	position: relative;
}
.cssmenu > ul > li.active a, .cssmenu > ul > li a:hover {
	color:#5F636D;
}
.cssmenu > ul > li > a {
	color: #FFF;
	display: block;
	margin:10px 5px;
	letter-spacing: 1px;
	font-size: 0.89em;
	font-family: 'Droid Sans', sans-serif;
}
.header-right{
	text-align:center;
}
.header-right p {
	line-height: 2.8em;
	font-size: 16px;
	color:#51565f;
	font-family: 'Droid Sans', sans-serif;
}
.header-right img {
	vertical-align:middle;
}
.follow_icon {
	float: left;	
	list-style: none;
	padding:20px 0 0;
}
.follow_icon li {
	padding-top: 1.7%;
}
.follow_icon li a img {
	vertical-align: middle;
}
.follow_icon li a img:hover{
	opacity:0.8;
}
.banner-img{
	float:right;
	margin-top:-120px;
}
/*-------LOGIN STARTS HERE -------*/
#loginContainer {
    position:relative;
    display: inline-block;
    padding-top: 5px;
}
#loginContainer span{
	color:#5f636d;
	font-size:0.89em;
	font-family: 'Droid Sans', sans-serif;
}
/* Login Button */
#loginButton { 
    display:inline-block;  
    position:relative;
    z-index:30;
    cursor:pointer;
}
/* Login Box */
#loginBox {
    position:absolute;
    top: 50px;
	right: -20px;
    display:none;
    z-index:29;
}
#loginForm span{
	display:block;
	font-size:0.89em;
	color:#FFF;
	padding-bottom:5px;
	font-family: 'Droid Sans', sans-serif;
	text-align: left;
}
#loginForm input[type="text"]{
	padding: 5px;
	display: block;
	width: 94%;
	background: #FCFCFC;
	border: none;
	outline: none;
	color: #464646;
	font-size: 0.8125em;
	font-family: Arial, Helvetica, sans-serif;
	-webkit-appearance: none;
}
#loginForm input[type="submit"]{
	padding:7px 12px;
	color:#FFF;
	cursor:pointer;
	background:#F58972 url(../images/large-button-overlay.png);
	border:none;
	outline:none;
	font-family: 'Droid Sans', sans-serif;
	-webkit-appearance: none;
}
#loginForm input[type="submit"]:hover{
	background-color:#333;
}
/* Login Form */
#loginForm {
   width: 190px;
	background: #707785;
	border-radius: 5px;
	-webkit-border-radius: 5px;
	border-radius: 5px;
	border-radius: 5px;
	position: relative;
	padding: 10px;
}
#loginForm:after {
	content: '';
	position: absolute;
	right: 40px;
	top: -6px;
	border-left: 6px solid rgba(0, 0, 0, 0);
	border-right: 6px solid rgba(0, 0, 0, 0);
	border-bottom: 6px solid #707785;
}
/*--content--*/
/*  GRID OF Content and sidebar   ============================================================================= */
.cont{
	display: block;
	float:left;
}
.rsidebar{
	display: block;
	float:left;
	margin: 1% 0 1% 1.6%;
} 	
.span_2_of_index, .span_2_of_3 {
	width: 64.1%;
}
.span_1_of_3 {
	width: 34.2%;
}
span.red{
	color:#f58972;
}
.span_2_of_index  h3,
.span_1_of_index  h3,
.span_2_of_3  h3 {
	color: #333;
	font-size:1em;
	line-height: 1.2;
	font-weight: normal;
	margin-top: 0px;
	letter-spacing: -1px;
	font-family: 'Roboto', sans-serif;
	text-transform: uppercase;
}
.span_2_of_index p,
.span_1_of_index  p,
.span_2_of_3 p{
	font-size: 0.89em;
	padding: 0.5em 0;
	color: #555;
	line-height: 1.5em;
	font-family: 'Droid Sans', sans-serif;
}
.content-top{
	border-bottom:2px solid #F5F5F5;
	padding-bottom: 10px;
}
.main{
	padding:30px 10px;
}
/* Circular Content Carousel Style */
.ca-container{
	position: relative;
	padding-top:20px;
	width:100%;
	height:310px;
}
.ca-wrapper{
	width:100%;
	height:100%;
	position:relative;
}
.ca-item{
	position: relative;
	float: left;
	width: 100%;
	height: 100%;
	text-align: center;
}
.ca-icon{
	width: 200px;
	height: 200px;
	display: block;
	position: relative;
	margin: 0 auto;
	background: transparent url(../images/pic.png) no-repeat center center;
	border-radius: 50%;
}
.ca-item-2 .ca-icon{
	background-image:url(../images/pic1.png);
}
.ca-item-3 .ca-icon{
	background-image:url(../images/pic2.png);
}
.ca-item-4 .ca-icon{
	background-image:url(../images/pic3.png);
}
.ca-item-5 .ca-icon{
	background-image:url(../images/pic.png);
}
.ca-item-6 .ca-icon{
	background-image:url(../images/pic1.png);
}
.ca-item-7 .ca-icon{
	background-image:url(../images/pic2.png);
}
.ca-item-8 .ca-icon{
	background-image:url(../images/pic3.png);
}
.ca-item h3{
	padding:30px 0 5px;
}
.ca-item h3 a{
	text-transform:uppercase;
	font-size:1em;
	color:#000;
	text-align:center;
	font-family: 'Roboto', sans-serif;
}
.ca-item h3 a:hover{
	color: #F58972;
}
.ca-item h4{
	position: relative;
	color: #555;
	margin: 0.8em 0;
	line-height: 1.8em;
	font-weight: 300;
	font-size: 0.89em;
	font-family: 'Droid Sans', sans-serif;
	font-style: italic;
}
.ca-content-text p{
	padding-bottom:5px;
}
.ca-nav span{
	width:25px;
	height:38px;
	background:transparent url(../images/arrows.png) no-repeat top left;
	position:absolute;
	top:50%;
	margin-top:-60px;
	text-indent:-9000px;
	opacity:0.7;
	cursor:pointer;
	z-index:100;
}
.ca-nav span.ca-nav-next{
	background-position:top right;
	left:auto;
	right: 0px;
}
.ca-nav span:hover{
	opacity:1.0;
}
.content-middle{
	border-bottom:2px solid #F5F5F5;
}
/*---start-mid-grids-----*/
/*  GRID OF TWO   ============================================================================= */
.col_1_of_2{
	display: block;
}
.span_1_of_2 {
	margin-bottom: 20px;
}
.span_1_of_2  h3{
	color: #333;
	font-size:1em;
	line-height: 1.2;
	font-weight: normal;
	margin-top: 0px;
	letter-spacing: -1px;
	font-family: 'Roboto', sans-serif;
	text-transform: uppercase;
}
.span_1_of_2  p{
	font-size:0.89em;
	padding:0.5em  0;
	color: #555;
	line-height: 1.5em;
	font-family: 'Droid Sans', sans-serif;
}
.heading{
	font-size:1em;
	font-family: 'Roboto', sans-serif;
	text-transform: uppercase;
}
/******** SAP ************/
.sap_tabs{
	clear:both;
	padding-top:20px;
}
.sap_tabs h2{
	font-size: 1.8em;
	color:#F58972;
	padding-bottom: 20px;
	text-transform: uppercase;
	font-family: 'Droid Sans', sans-serif;
}
.sap_tabs h3,.sap_tabs h3 a{
	font-size: 1em;
	color: #333;
	line-height: 1.8em;
}
.sap_tabs h3 a{
	font-size:.7em;
}
.sap_tabs h3 a:hover{
	text-decoration:underline;
}
.sap_tabs p{
	font-size: .85em;
	color: #5C5C5C;
	line-height: 1.8em;
	padding: 10px 0;
}
.sap_tabs p span{
   font-weight:bold;
}
.resp-tabs-list li, .resp-tabs-list1 li{
	font-size: 0.85em;
	color: #888;
	text-transform: uppercase;
	cursor: pointer;
	font-family: 'Roboto', sans-serif;
	padding: 20px 50px;
	display: inline-block;
	margin: 0;
	list-style: none;
	cursor: pointer;
	float: left;
	background: url(../images/shadow.png)#F0F0F0 repeat-x bottom;
	border-right: 1px solid #C9C6C6;
}
ul.resp-tabs-list > ul > li.active a, ul.resp-tabs-list > ul > li a:hover {
	background:red;
}
.resp-tabs-list li.first{
	background: #f3f2f2;
	border-right: 1px solid #C9C6C6;
	box-shadow: none;
	color: #000;
}
.resp-tabs-list li:hover, .resp-tabs-list1 li:hover{
	background:#EEE;
	color:#000;
	background: url(../images/shadow.png)#F0F0F0 repeat-x bottom;
}
.resp-tabs-container {
	padding: 0px;
	background: #f3f2f2;
	background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iI2YzZjJmMiIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiNmZmZmZmYiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
	background: -moz-linear-gradient(top,  #f3f2f2 0%, #ffffff 100%);
	background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#f3f2f2), color-stop(100%,#ffffff));
	background: -webkit-linear-gradient(top,  #f3f2f2 0%,#ffffff 100%);
	background: -o-linear-gradient(top,  #f3f2f2 0%,#ffffff 100%);
	background: -ms-linear-gradient(top,  #f3f2f2 0%,#ffffff 100%);
	background: linear-gradient(to bottom,  #f3f2f2 0%,#ffffff 100%);
	filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f3f2f2', endColorstr='#ffffff',GradientType=0 );
	clear: left;
}
h2.resp-accordion {
	cursor: pointer;
	padding: 5px;
	display: none;
}
.resp-tab-content {
	display: none;
	padding:10px 10px 0 10px;
	border: 1px solid #F1F1F1;
}
.resp-tab-active {
	border-bottom: none;
	margin-bottom: -1px !important;
}
.resp-tab-active:hover{
	background-color: #fff;
}
.resp-content-active, .resp-accordion-active {
   display: block;
}
h2.resp-accordion {
	font-size:1em;
	border: 1px solid #ECECEC;
	border-top: 0px solid #ECECEC;
	margin: 0px;
	padding: 10px 15px;
	background:#ECECEC;
	margin:10px 0;
}
h2.resp-accordion:hover{
	background: #222;
	text-shadow: none;
	color: #FFF;
}
h2.resp-tab-active {
	border-bottom: 0px solid #c1c1c1 !important;
	margin-bottom: 0px !important;
	padding: 10px 15px !important;
}
ul.resp-tabs-list {
  	display: none;
}
h2.resp-accordion {
  	display: block;
}
.resp-vtabs .resp-tab-content {
  	border: 1px solid #C1C1C1;
}
.resp-vtabs .resp-tabs-container {
	border: none;
	float: none;
	width: 100%;
	min-height: initial;
	clear: none;
}
.resp-accordion-closed {
	display: none !important;
}
.resp-vtabs .resp-tab-content:last-child {
	border-bottom: 1px solid #c1c1c1 !important;
}
/*--footer--*/
.footer{
	background: url(../images/f-bg1.png)repeat-x;
	padding: 20px 10px;
}
.footer_icon {
	list-style: none;
}
.footer_icon li{
	display:inline-block;
}
.footer_icon li a img:hover{
	opacity:0.9;
}
.col_1_of_footer {
	display: block;
}
.span_1_of_footer p {
	font-size: 0.89em;
	color:#fff;
	line-height: 1.5em;
	margin-bottom:10px;
	padding-right: 20px;
	font-family: 'Droid Sans', sans-serif;
}
.sidebar-nav h4, .sidebar-nav1 h4{
	font-size:1.1em;
	color:#fff;
	text-transform:uppercase;
	margin-bottom:15px;
	font-family: 'Droid Sans', sans-serif;
}
.sidebar-nav{
	padding-top:20px;
}
.sidebar-nav1{
	padding-top:20px;
}
.sidebar-nav li, .sidebar-nav1 li {
	margin-bottom:8px;
	font-family: 'Droid Sans', sans-serif;
}
.sidebar-nav li a, .sidebar-nav1 li a{
	font-size:0.89em;
	color: #fff;
}
.sidebar-nav li a:hover, .sidebar-nav1 li a:hover {
	color:#6E7279;
}
.copy{
	text-align:center;
	padding-top:10px;
}
.copy p{
	color:#fff;
	font-size:0.89em;
	line-height:1.5em;
	font-family: 'Droid Sans', sans-serif;
}
.copy p a{
	color:#F58972;
}
.copy p a:hover{
	color:#fff;
}
/*--products--*/
/*  GRID OF FOUR   ============================================================================= */
.images_1_of_4 {
	margin-bottom: 20px;
}
.grid_1_of_4 {
	display: block;
}
.grid_img{
	text-align:center;
}
.grid_1_of_4 h4 {
	text-transform: uppercase;
	-webkit-transition: all 0.3s ease-out;
	-moz-transition: all 0.3s ease-out;
	-ms-transition: all 0.3s ease-out;
	-o-transition: all 0.3s ease-out;
	transition: all 0.3s ease-out;
	cursor: pointer;
	padding: 13px 0px 2px 0px;
	color: #333;
	font-family: 'Roboto', sans-serif;
	font-size:1em;
	margin-bottom:5px;
}
.grid_1_of_4 h4:hover {
	color:#FAA685;
}
.grid_1_of_4 p {
	font-size:0.89em;
	color: #555;
	line-height: 1.6em;
	font-family: 'Droid Sans', sans-serif;
}
.link {
	background: url(../images/list-arrow.gif) no-repeat 100% 8px;
	display: inline-block;
	line-height: 19px;
	font-size:0.89em;
	padding-top:20px;
	font-style: normal;
	text-decoration: underline;
	color:#F58972;
	font-family: 'Droid Sans', sans-serif;
	text-transform: uppercase;
}
.link:hover {
	text-decoration:none;
	color:#333;
}
.heading4 h2{
	color: #000;
	font-family: 'ambleregular';
	font-size: 1.6em;
	margin-bottom:1%;
	text-transform: uppercase;
}
/*--services--*/
.span_1_of_about h3, .span_2_of_contact h3, .span_1_of_contact h3{
	color: #333;
	font-family: 'Roboto', sans-serif;
	font-size: 1em;
	margin-bottom: 10px;
	text-transform: uppercase;
}
.services-box {
	margin-bottom: 2%;
}
.span_1_of_2 img{
	display:block;
}
.span_1_of_about1 h3 {
	color: #000;
	font-family: 'Roboto', sans-serif;
	font-size: 1em;
	margin-bottom: 10px;
	text-transform: uppercase;
}
.services-nav {
	margin-bottom:20px;
}
.services-nav li {
	background: url(../images/list.png)no-repeat 0 11px;
	border-bottom: 1px dotted #BDBABA;
	padding: 4px 0 10px 10px;
	margin: 10px 0px 0px;
}
.services-nav li a {
	font-size: 0.89em;
	color: #555;
	font-family: 'Droid Sans', sans-serif;
}
.services-nav li a:hover{
	color:#F58972;
}
.services-nav li.last {
	border-bottom: none;
}
.poling {
	margin-bottom:20px;
}
.comments-custom li {
	overflow: hidden;
	margin: 0;
	padding: 0px 0 10px 0;
	border-bottom: none;
	background: none;
}
.comments-custom.unstyled .icon {
	background: url(../images/comment.png) no-repeat 0 50%;
	width: 37px;
	height: 70px;
	float: left;
	border-right: 1px solid #EBEBEB;
	padding: 0 8px 0 0;
	margin: 0 10px 0 0;
}
.right-text {
	width:78%;
	float: left;
	font-family: 'Droid Sans', sans-serif;
}
p.text1 {
	background:#F58972;
	padding:5px;
	color: #FFF;
	font-size:0.89em;
	text-transform: uppercase;
	font-family: 'Droid Sans', sans-serif;
}
.poll {
	margin-bottom:20px;
}
.text2 {
	float: left;
	font-family: 'Droid Sans', sans-serif;
	color: #555;
	font-size: 0.89em;
}
.percent {
	float: right;
	font-family: 'Droid Sans', sans-serif;
	color: #555;
	font-size:0.89em;
}
.skills {
	width: 100%;
	margin: 10px 0;
	background-color: #D7DEE0;
	height:5px;
}
.skills > div {
	height: 100%;
	display: block;
	background-color:#F58972;
}
.comments-custom.unstyled .comments-custom_h {
	font-size: .89em;
	color: #555;
	line-height: 1.5em;
	text-transform: uppercase;
}
.comments-custom.unstyled .comments-custom_txt a {
	font-size: 0.89em;
	color: #555;
	line-height: 1.5em;
}
.comments-custom.unstyled .comments-custom_txt a:hover{
	color:#F58972;
}
.comments-custom time {
	font-size: 12px;
	color: #555;
	line-height: 1.5em;
}
/*--contact--*/
/*  Contact Form  ============================================================================= */
.col{
	display: block;
}
.span_1_of_contact p {
	font-size: 0.89em;
	color: #555;
	line-height: 1.8em;
	font-family: 'Droid Sans', sans-serif;
}
.span_1_of_3 {
	width: 32.2%;
}
.contact-form{
	position:relative;
	padding-bottom:30px;
}
.contact-form div{
	padding:5px 0;
}
.contact-form span{
	display:block;
	font-size:0.89em;
	color: #555;
	padding-bottom:5px;
	font-family: 'Droid Sans', sans-serif;
}
.contact-form input[type="text"],.contact-form textarea{
	padding:8px;
	display:block;
	width:94%;
	background:#fcfcfc;
	border: none;
	outline:none;
	color:#464646;
	font-size:0.8125em;
	font-family:Arial, Helvetica, sans-serif;
	box-shadow: 0 0 5px #AAA;
	-webkit-box-shadow: 0 0 5px #AAA;
	-moz-box-shadow: 0 0 5px #AAA;
	-o-box-shadow: 0 0 5px #AAA;
	-webkit-appearance:none;
}
.contact-form input[type="text"]:hover, .contact-form textarea:hover{
	box-shadow: 0 0 2px #AAA;
	-webkit-box-shadow: 0 0 2px #AAA;
	-moz-box-shadow: 0 0 2px #AAA;
	-o-box-shadow: 0 0 2px #AAA;
}
.contact-form textarea{
	resize:none;
	height:120px;		
}
.contact-form input[type="submit"]{
	padding:8px 18px;
	color: #FFF;
	cursor: pointer;
	background: #F58972;
	border: none;
	font-family: 'Roboto', sans-serif;
	position: absolute;
	right: 0;
	outline: none;
	text-transform: uppercase;
    -webkit-appearance: none;
}
.contact-form input[type="submit"]:hover{
	background-color:#333;
}
.contact-form input[type="submit"]:active{
	background-color:#333;  
}
.company_address p span{
	text-decoration:underline;
	color:#555;
	cursor:pointer;
}
.company_address p span:hover{
	text-decoration:none;
}
.map{
	margin-top:20px;
}
/*--single--*/
/*  GRID OF Content and sidebar   ============================================================================= */
.lsidebar{
	display: block;
} 	
.span_2_of_bottom {
	width: 66.1%;
}
.span_1_of_bottom {
	padding: 10px;
	border: 1px solid #DDD;
	margin-bottom: 20px;
}
.span_2_of_bottom p,
.span_1_of_bottom  p  {
	font-size:0.8125em;
	padding:0.5em 0;
	color: #888;
	line-height: 1.5em;
	font-family: 'Droid Sans', sans-serif;
}
#cssmenu,
#cssmenu ul,
#cssmenu li,
#cssmenu a {
  margin: 0;
  padding: 0;
  border: 0;
  list-style: none;
  font-weight: normal;
  text-decoration: none;
  line-height: 1;
  font-size: 14px;
  position: relative;
}
#cssmenu {
 padding-bottom:20px;
}
#cssmenu a {
  line-height: 1.3;
}
#cssmenu > ul > li:first-child {
 background:#555;
}
#cssmenu > ul > li:first-child > a {
  padding: 10px 10px;
}
#cssmenu > ul > li:first-child > a > span {
  padding: 0;
  font-size:1.3em;
}
#cssmenu > ul > li:hover {
  background:#F58972;
}
#cssmenu > ul > li > a {
  display: block;
  color:#fff;
  border-top: none;
  font-family: 'Droid Sans', sans-serif;
}
#cssmenu > ul > li > a > span {
  display: block;
  padding: 12px 10px;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 4px;
}
#cssmenu > ul > li > a:hover {
  text-decoration: none;
}
#cssmenu > ul > li.active {
  border-bottom: none;
}
#cssmenu > ul > li.has-sub > a span {
  background: url(../images/icon_plus.png) 96% center no-repeat;
}
#cssmenu > ul > li.has-sub.active > a span {
  background: url(../images/icon_minus.png) 96% center no-repeat;
}
/* Sub menu */
#cssmenu ul ul {
  display: none;
  background: #fff;
}
#cssmenu ul ul li {
  padding: 0;
  border-bottom: 1px solid #d4d4d4;
  border-top: none;
  background: #f7f7f7;
  background: -moz-linear-gradient(#f7f7f7 0%, #ececec 100%);
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%, #f7f7f7), color-stop(100%, #ececec));
  background: -webkit-linear-gradient(#f7f7f7 0%, #ececec 100%);
  background: linear-gradient(#f7f7f7 0%, #ececec 100%);
}
#cssmenu ul ul li:last-child {
  border-bottom: none;
}
#cssmenu ul ul a {
  padding: 10px 10px 10px 25px;
  display: block;
  color: #676767;
  font-size: 12px;
  font-weight: normal;
  font-family: 'Droid Sans', sans-serif;
}
#cssmenu ul ul a:before {
  content: '»';
  position: absolute;
  left: 10px;
  color:#C0313C;
}
#cssmenu ul ul a:hover {
  color:#C0313C;
}
.box_wrapper {
	text-transform: uppercase;
	border-bottom: 1px solid #D0D0D0;
	font-family: 'AmbleRegular';
	padding:5% 0 2%;
}
.box_wrapper h1 {
	font-size:1.5em;
	line-height: 21px;
	color: #333;
}
.desc{
	padding:5%;
}
.desc h5 a{
	color:#C0313C;
	font-size: 0.788em;
}
.desc h5 a:hover{
	color:#333;
}
.button {
	border: none;
	background: #45A43E;
	color: #FEF503;
	float: right;
	padding: 7px 15px;
	font-size: 12px;
	cursor: pointer;
	outline: none;
	text-transform:uppercase;
}
.button:hover {
	background:#333;
}
.price-text{
	padding:5% 0;
}
.field{
	padding: 10px;
	text-align: center;
}
.field select {
	border: 1px solid #F0EFEE;
	background: #FFF;
	color: #555;
	outline: none;
	padding: 4px;
	font-family: 'Droid Sans', sans-serif;
	font-size: 0.89em;
}
.field select.select1 {
	width:100%;
}
.brands{
	border:1px solid #ddd;
}
.brands h1{
	background: #555;
	color: #FFF;
	padding: 10px;
	font-size: 1.3em;
	font-family: 'Droid Sans', sans-serif;
}
.banner-wrap.bottom_banner.color_link .main_link {
	border-color:#333;
	background:#555;
	-webkit-transition: all 300ms linear;
	-moz-transition: all 300ms linear;
	-o-transition: all 300ms linear;
	transition: all 300ms linear;
}
.main_link {
	border: 5px solid #E5E5E5;
	background: #FFF;
	padding: 15px 20px 10px;
	text-decoration: none!important;
	text-align: center;
	display: block;
	min-height: 68px;
}
.banner-wrap.bottom_banner .main_link figure {
	display: inline-block;
	margin: 0 9px 0 0;
	vertical-align: middle;	
}
.banner-wrap.bottom_banner.color_link .main_link h5{
	color: #fff;
}
.banner-wrap.bottom_banner .main_link h5 {
	text-transform: uppercase;
	margin: -5px 0 0 0;
	display: inline-block;
	font-family: 'Droid Sans', sans-serif;
	text-align: left;
	font-size: 13px;
	line-height: 18px;
	letter-spacing: -1px;
	vertical-align: middle;
}
.banner-wrap.bottom_banner .main_link h5 span {
	font-size:1.5em;
	line-height: 29px;
	font-family: 'Droid Sans', sans-serif;
}
.banner-wrap.bottom_banner.color_link .main_link p {
	color: #fff;
}
.banner-wrap.bottom_banner.color_link .main_link:hover {
	text-decoration: none;
	background:#F58972;
	border-color:#DA644A;
}
.sellers{
	padding-bottom:20px;
}
.sellers h4{
	font-size:1.5em;
	color:#333;
	line-height:1.5em;
	border-bottom:1px solid #ddd;
	font-family: 'Roboto', sans-serif;
}
.single-nav{
	padding-top:10px;
}
.single-nav li {
	list-style-image: url(../images/marker1.gif);
	border-bottom: 1px dotted #E8E8E8;
	margin: 0 20px 10px;
	padding-bottom: 10px;
}
.single-nav li a {
	font-size: 0.89em;
	color: #555;	
	font-family: 'Droid Sans', sans-serif;
}
.single-nav li a:hover {
	color: #F58972;
}
.banner-wrap{
	padding-bottom:20px;
}
.span_3_of_2 {
	width: 52.2%;
}
.desc1 {
	display: block;
	float: left;
}
.std p {
	font-size: 0.89em;
	padding: 0.5em 0;
	color: #555;
	line-height: 1.5em;
	font-family: 'Droid Sans', sans-serif;
}
p.stock {
	display: block;
	font-size: 0.89em;
	font-family: 'Droid Sans', sans-serif;
	color: #555;
	margin: 10px 0;
}
.row-2 {
	overflow: hidden;
	text-align: left;
	padding-top: 6px;
	border-top: 1px dotted #CCC;
	border-bottom: 1px dotted #CCC;
	font-family: 'Droid Sans', sans-serif;
}
#reduction_percent {
	padding: 16px 0 0 0;
	float: left;
	margin-right:8px;
	font-size:0.8125em;
	font-style: italic;
	font-weight: normal;
	color: #333;
}
.price {
	float: left;
	padding-top: 4%;
}
#old_price {
	padding: 16px 0 0 0;
	font-size:0.8125em;
	display: inline-block;
	font-style: italic;
	font-weight: normal;
	color: #333;
	float: left;
	margin-right: 7px;
}
.on_sale_img {
	float: right;
	margin-bottom: 8px;
}
span.on_sale {
	display: block;
	float: left;
	padding:16px 0px 0 10px;
	font-size:0.8125em;
	font-style: italic;
	font-weight: normal;
	color: #F58972;
}
.price1 {
	padding:20px 0;
	font-family: 'Droid Sans', sans-serif;
}
span.actual1 {
	text-decoration: line-through;
	margin-right: 10px;
	color: #888;
	font-size: 1em;
}
span.reducedfrom {
	color: #F58972;
	font-size: 1em;
}
.row-product1 {
	padding:10px 0 20px;
}
.row-product1 .no-rating1 {
	margin-bottom: 10px;
	background: url(../images/wishlist.png) left 3px no-repeat;
	padding-left: 22px;
	font-family: 'Droid Sans', sans-serif;
}
.row-product1 .no-rating1 a{
	color:#F58972;
	font-size: 0.89em;
}
.row-product1 .no-rating1 a:hover{
	color: #555;
}
.row-product1 .email-friend1 {
	background: url(../images/compare.png) left 3px no-repeat;
	padding-left: 27px;
	font-family: 'Droid Sans', sans-serif;
}
.row-product1 .email-friend1 a{
	color:#F58972;
	font-size: 0.89em;
}
.row-product1 .email-friend1 a:hover{
	color: #555;
}
.row-product .no-rating {
	margin-bottom:10px;
	background: url(../images/marker-reviews.gif) left 3px no-repeat;
	padding-left: 22px;
	font-size: 0.89em;
	font-family: 'Droid Sans', sans-serif;
}
.row-product .no-rating a {
	text-decoration: underline;
	color:#555;
}
.row-product .no-rating a:hover, .row-product .email-friend a:hover{
	text-decoration:none;
}
.row-product .email-friend {
	background: url(../images/marker-email.gif) left 5px no-repeat;
	padding-left: 27px;
	font-family: 'Droid Sans', sans-serif;
}
.row-product .email-friend a{
	color:#555;
	font-size:0.89em;
	text-decoration: underline;
}
.images_3_of_2 {
	width: 44.2%;
	float: left;
	margin-right:10px;
}
.span_3_of_2 h3 {
	color:#F58972;
	margin-bottom: 0.3em;
	font-size:1em;
	font-weight: normal;
	margin-top: 0px;
	letter-spacing: -1px;
	font-family: 'Roboto', sans-serif;
}
.single-bottom1 h6, .single-bottom2 h6 {
	background: #F3F3F3;
	padding: 10px;
	color: #333;
	font-size: 1.2em;
	font-family: 'Roboto', sans-serif;
}
p.prod-desc {
	color: #888;
	padding-top: 2%;
	font-size: 0.89em;
	line-height: 1.5em;
	font-family: 'Droid Sans', sans-serif;
}
.single-bottom1 {
	padding:20px 0;
}
.product {
	padding: 3% 0 0 0;
}
.product-desc {
	width:55.2%;
	float: left;
	border-width: 0 1px 0 0;
	border-right: 1px solid #DDD;
}
.product-img {
	width: 21.5%;
	float: left;
	margin-right: 2.5%;
}
.prod1-desc {
	width: 75.2%;
	float: left;
}
.product-desc h5 {
	padding-bottom: 2%;
	font-family: 'Droid Sans', sans-serif;
}
.product-desc h5 a{
	color:#555;
}
.product-desc h5 a:hover{
	color:#F58972;
}
p.product_descr {
	color: #555;
	font-size: 0.89em;
	line-height: 1.5em;
	font-family: 'Droid Sans', sans-serif;
}
.product_price {
	width: 40.7%;
	float: left;
	padding: 0 0px 0px 10px;
	font-family: 'Droid Sans', sans-serif;
}
.price-access {
	color: #555;
	font-size: 1em;
}
.button1 {
	border: none;
	background: #555;
	padding: 7px 15px;
	color: #FFF;
	font-size: 13px;
	cursor: pointer;
	outline: none;
	-webkit-appearance: none;
	font-family: 'Droid Sans', sans-serif;
}
.button1:hover{
	background:#F58972;
}
