<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
      &lt;head&gt;
<!-- Composite Start -->
<div id='M606140ScriptRootC953693'>
</div>
<script async='async' src='https://jsc.adskeeper.co.uk/c/i/aflami4uu.blogspot.com/.953693.js'>
</script>
<!-- Composite End -->
<!-- Composite Start -->
<div id='M606140ScriptRootC953703'>
</div>
<script async='async' src='https://jsc.adskeeper.co.uk/c/i/aflami4uu.blogspot.com.953703.js'>
</script>
<!-- Composite End -->
  
	<meta content='text/html; charset=UTF-8' http-equiv='Content-Type'/>
        <b:if cond='data:blog.isMobile'>
        <b:else/>
          <meta content='width=1100' name='viewport'/>
        </b:if>
        <b:include data='blog' name='all-head-content'/>
    <title>
		<b:if cond='data:blog.pageType == &quot;index&quot;'>
			<data:blog.pageTitle/>
		<b:else/>
			<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
				<data:blog.pageName/> - <data:blog.title/>
			<b:else/>
				404 - <data:blog.title/> 
			</b:if>
		</b:if>
    </title>
<!-- meta tags -->
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <meta expr:content='data:blog.pageName' property='og:title'/>
        <meta expr:content='data:blog.canonicalUrl' property='og:url'/>
        <meta content='article' property='og:type'/>
    </b:if>
    <b:if cond='data:blog.postImageUrl'>
        <meta expr:content='data:blog.postImageUrl' property='og:image'/>
    <b:else/>
    <b:if cond='data:blog.postImageThumbnailUrl'>
        <meta expr:content='data:blog.postImageThumbnailUrl' property='og:image'/>
    </b:if></b:if>
    <b:if cond='data:blog.metaDescription != &quot;&quot;'>
        <meta expr:content='data:blog.metaDescription' name='og:description'/>
    </b:if>
    <meta expr:content='data:blog.title' property='og:site_name'/>
    <meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
    <b:if cond='data:blog.postImageUrl'>
      <meta content='summary_large_image' name='twitter:card'/>
      <meta expr:content='data:blog.postImageUrl' name='twitter:image'/>
    <b:else/>
      <meta content='summary' name='twitter:card'/>
      <b:if cond='data:blog.postImageThumbnailUrl'>
        <meta expr:content='data:blog.postImageThumbnailUrl' name='twitter:image'/> 
      </b:if>
    </b:if>
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
    <b:if cond='data:blog.metaDescription'>
      <meta expr:content='data:blog.metaDescription' name='twitter:description'/>
    </b:if>

    <!-- Social Media meta tag need customer customization -->
    <meta content='Facebook App ID here' property='fb:app_id'/> 
    <meta content='Facebook Admin ID here' property='fb:admins'/> 
    <meta content='@username' name='twitter:site'/>
    <meta content='@username' name='twitter:creator'/>

<!-- end meta tags -->
<meta content='width=device-width, initial-scale=1, maximum-scale=1' name='viewport'/>

<link href='https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css' rel='stylesheet'/>
<link href='http://fonts.googleapis.com/earlyaccess/droidarabicnaskh.css' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/earlyaccess/droidarabickufi.css' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Play' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Lobster' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Shadows+Into+Light' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Droid+Sans:bold' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Droid+Serif:bold' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Raleway:100' rel='stylesheet' type='text/css'/>
	<b:skin><![CDATA[/*
-----------------------------------------------
Blank Blogger Template by nos5aa.COM
Name:        nos5a-cima
Designer:       AHMED ADLY
URL:        https://www.nos5aa.com
----------------------------------------------- */

/* Variables Definitions
------------------------------ */
/*

<Variable name="body.background" description="Body Background" type="background"
color="#f7f7f7" default="$(color) none repeat scroll top left" value="$(color) none repeat scroll top left"/>

<Variable name="test" description="test" type="color" default="#000" value="#000000"/>

*/


/* Tarnsition
------------------------------ */
 {transition: all .3s;-webkit-transition: all .3s;-o-transition: all .3s;-moz-transition: all .3s;}



.all-wrapper {
    overflow: initial;
    display: block;
    margin: auto;
    box-shadow: 0 4px 16px rgba(0,0,0,0.2);
}


/*header-top
-----------------------------*/
.header-top {
    overflow: hidden;
    position: relative;
    padding: 2px 0px 2px 0px;
    background: radial-gradient(ellipse at top,#2f1464,#673AB7 80%,#673AB7);
    box-shadow: 0px 2px 10px #000;
}
#menu-right{margin-right:6px}
#menu-right ul li:last-child a:after{display:none}
#menu-right ul li a{
    color: #ffffff;
    font-size: 15px;
    border-radius: 3px;
    padding: 18px;
    border-left: 1px solid rgba(0, 0, 0, 0.2);
    transition: 0.3s;
    line-height: 50px;
    font-family: 'DroidKufi bold' , Tahoma;
}
#menu-right ul li a:hover{
    color: #fff;
    box-shadow: inset 0px -60px 0px rgba(45, 69, 98, 0.82);
}
#menu-right, #menu-right ul li{float:right}
#menu-left ul li a {

    display: inline-block;
    font-size: 20px;
    box-sizing: border-box;
    padding-top: 10px;
    margin-left: 6px;
    text-align: center;
    line-height: 100%;
    float: right;
    height: 40px;
    box-shadow: 0px 2px 5px rgba(0,0,0,0.61);
    width: 44px;
    border-radius: 3px;
    background: rgba(247,247,247,0.18);
    font-family: Font Bold,Arial Black;
    margin-top: 4px;

}
#menu-left ul li a:hover {
    color: #fff !important;
}
#menu-left {
    float: left;
    margin-left: 6px;
}
#menu-left li {
    float: right;
}
a.facebook:before {
    content: "\f09a";
    font-family: fontawesome;
}
a.picalica:before {
    content: "\efc8";
    font-family: fontawesome;
}
a.khamsat:before {
    content: "\efc7";
    font-family: fontawesome;
}
a.instagram:before {
    content: "\f16d";
    font-family: fontawesome;
}
a.linkedin:before {
    content: "\f0e1";
    font-family: fontawesome;
}
a.twitter:before {
    content: "\f099";
    font-family: fontawesome;
}
a.whatsapp:before {
    content: "\f232";
    font-family: fontawesome;
}
a.vine:before {
    content: "\f1ca";
    font-family: fontawesome;
}
a.youtube:before {
    content: "\f167";
    font-family: fontawesome;
}
a.google-plus:before {
    content: "\f0d5";
    font-family: fontawesome;
}
a.snapchat:before {
    content: "\f2ac";
    font-family: fontawesome;
}
a.blogger:before {
    content: "\B";
    font-family: fontawesome;
}
a.rss:before {
    content: "\f09e";
    font-family: fontawesome;
}
.youtube:hover {
    background: #bb0000 !important;
}
.facebook:hover {
    background: #3b5998 !important;
}
.google-plus:hover {
    background: #dd4b39 !important;
}
.whatsapp:hover {
    background: #4dc247 !important;
}
.rss:hover {
    background: #ff6600!important;
}
.twitter:hover {
    background: #55acee !important;
}
.blogger:hover {
    background: #ff4500 !important;
}
.snapchat:hover {
    background: #fffc00 !important;
}
.vine:hover {
    background: #00bf8f !important;
}
.linkedin:hover {
    background: #007bb5 !important;
}
.instagram:hover {
    background: #D4C6A7 !important;
}
.picalica:hover {
    background: #615d9b !important;
}
.khamsat:hover {
    background: #f9b01c !important;
}

/*header-wrapper
----------------------------------*/
.header-wrapper {
    overflow: hidden;
    background: #fff0;
    padding: 24px 20px;
}
#logo {
    float: right;
}
#ads {
    float: left;
}

/*main-menu
---------------------------------*/
.main-menu {

    box-shadow: 0px 2px 10px #000;
    background-image: linear-gradient(to bottom,rgba(0,0,0,0) 0,rgba(0,0,0,0.2) 100%);
    border-bottom: 4px solid #673AB7;
    background-color: rgba(41, 11, 95, 0.95);
    position: relative;
    height: 60px;
    margin-bottom: 5px;

}
li.searchIcon a {
    color: #fff;
}
.Home {
    float: right;
    text-decoration: none;
    font-size: 18px;
    font-weight: 700;
    background: #673AB7;
    line-height: 100%;
    text-align: center;
    cursor: pointer;
    color: #fff;
    padding: 18px 18px;
}
li.searchIcon {
float: left;
text-decoration: none;
font-size: 18px;
font-weight: 700;
background: #673AB7;
line-height: 100%;
text-align: center;
cursor: pointer;
color: #fff;
padding: 18px 18px;
}

.main-menu ul li a:hover {
    background: #008de7;
    color: #fff;
    box-shadow: inset 0px -60px 0px #673AB7;
}

.main-menu ul li a {
    color: #fff;
    display: block;
    font-size: 14px;
    padding: 16px 14px;
    transition: 0.3s;
    border-left: 1px solid rgba(255,255,255,0.14);
    font-weight: bold;

}
.main-menu ul li {
    float: right;
    font-family: 'DroidKufi bold' , Tahoma;
}
span.sb {
    cursor: pointer;
}
span.sc {
    cursor: pointer;
}
#sub-menu li {
float: none;
display: block;
}
#sub-menu {
position: absolute;
top: 56px;
z-index: 99999;
width: 250px;
background: #243748;
display: none;
}
#sub-menu li a {
    color: #ffffff;
    line-height: 40px;
    border-bottom: 0px solid #eee;
    padding: 4px 10px;
    transition: 0.2s;
}
#sub-menu li a:before {
    content: "\f053";
    font-family: Fontawesome;
    padding-left: 7px;
    position: relative;
    background: transparent;
}


#sub-menu li a:hover {
    background: #0099cc;
    color: #ffffff;
}
#sub-menu li:first-child a {
background: none!important;
}
#sub-menu li:first-child a:hover {
    background: #0099cc!important;
    color: #ffffff;}
 #sub-menu li a:hover {
    background: #0099cc;
    color: #ffffff;}
.main-menu ul li:hover #sub-menu {display:block; }

#searchWrap {
    width: 100%;
    height: 100%;
    position: fixed;
    top: 0;
    left: 0;
    opacity: 0;
    visibility: hidden;
    z-index: 999999;
    -webkit-transform: translateZ(0);
    -ms-transform: translateZ(0);
    transform: translateZ(0);
    background-color: rgba(255,255,255,.94);
    text-align: center;
    -webkit-transition: all ease-in-out .25s;
    -moz-transition: all ease-in-out .25s;
    -ms-transition: all ease-in-out .25s;
    -o-transition: all ease-in-out .25s;
    transition: all ease-in-out .25s;
}
.closeSearch {
    position: absolute;
    right: 20px;
    top: 20px;
    font-size: 22px;
}
.closeSearch i{
    color: #fefefe;
    background: #243748;
    display: block;
    width: 35px;
    height: 35px;
    line-height: 35px;
    text-align: center;
    transition: .3s;
    border-radius: 50%;
    margin-left: 10px;
}
.openSearch{visibility:visible!important;opacity:1!important;transition:all .3s ease;-webkit-transition:all .3s ease;-moz-transition:all .3s ease;-o-transition:all .3s ease}
#searchBar:focus{outline:none;-webkit-box-shadow:0 3px 0 0 #243748;-moz-box-shadow:0 3px 0 0 #243748;box-shadow:0 3px 0 0 #243748}
  #searchBar {
    position: absolute;
    top: 45%;
    font-size: 40px;
    text-align: center;
    width: 50%;
    background-color: transparent;
    -webkit-box-shadow: 0 3px 0 0 rgba(0,0,0,.1);
    -moz-box-shadow: 0 3px 0 0 rgba(0,0,0,.1);
    box-shadow: 0 3px 0 0 rgba(0,0,0,.1);
    border: 0;
    text-align: center;
    font-size: 15px;
    padding: 20px;
    color: #212121;
    -webkit-transition: all .3s ease-out;
    -moz-transition: all .3s ease-out;
    -ms-transition: all .3s ease-out;
    -o-transition: all .3s ease-out;
    transition: all .3s ease-out;
    font-family: inherit;
    position: absolute;
    left: 0;
    right: 25%;
    top: 30%;
}
#searchBar:focus{outline:none}
/* Slider-Show
=====================================*/
.slider{overflow:hidden}.slider .widget-title h2:before{content:&quot;\f25b&quot;;margin-left:12px;color:#0099cc;font-family:fontawesome;display:initial;background:transparent}.slider .author,.slider .psummary{display:none}.slider .columnl{padding:0}.slider .mainimg .imag{width:100%;height:250px;position:relative;display:block;transition:all 0.8s ease;-webkit-transition:all 0.8s ease;-moz-transition:all 0.5s ease;-o-transition:all 0.5s ease}.slider .owl-item:hover .mainimg .imag{transform:scale(1.5);-moz-transform:scale(1.5);-webkit-transform:scale(1.5);-o-transform:scale(1.5);-ms-transform:scale(1.5)}.slider .mainimg:after{content:no-close-quote;position:absolute;left:0;bottom:0;width:100%;height:171px;background:url(https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjAwepe7SNbSz-qinDwCBKiLwrXf9F2fj82Mba5VFzZLhyphenhyphenDMXYFeoZBr0OtZ0A6NrMoXfAkSTLxbTAOfSNPa3RVM3AG0cxBqpgpo37DK-6LKWoVk0jpdQ5valVwHGCJOjan8b_NS96MNaI/s1600-r/metabg.png) repeat-x;background-size:100% 100%;opacity:.8}.slider .cont{position:absolute;bottom:0;width:100%;z-index:2;box-sizing:border-box;padding:15px;text-align:right}.slider .tag a{display:inline-block;background-color:#243748;color:#fff;height:20px;line-height:20px;padding:0 6px;font-size:11px;text-transform:uppercase}.slider .titlelab{margin:10px 0 3px;font-size:16px;font-weight:500}.slider .titlelab a{color:#fefefe;display:inline-block;line-height:1.4em;text-shadow:0 .5px .5px rgba(34,34,34,0.3)}.slider .owl-prev,.slider .owl-next{margin-top:0;width:40px;height:40px;font-size:25px;line-height:40px;top:0;color:#1c1c1c;background-color:rgba(255,255,255,0.8);position:absolute;z-index:1;display:block;padding:0;cursor:pointer;padding:0;text-align:center;overflow:hidden;transition:all .3s ease;-webkit-transition:all .3s ease;-moz-transition:all .3s ease;-o-transition:all .3s ease}.slider .owl-prev{right:-60px}.slider .owl-next{left:-60px}.slider:hover .owl-prev{right:0}.slider:hover .owl-next{left:0}.slider .owl-prev:hover,.slider .owl-next:hover{background-color:rgba(23,23,23,0.9);color:#fefefe}
/* Gallery-Style
=====================================*/
.gallery{background:#fefefe;padding:2%;box-sizing:border-box;float:right;width:49%;border-radius:2px;margin-bottom:2%}.gallery1{margin-left:1%}.gallery2{margin-right:1%}.gallery1 .widget-title h2:before{content:&quot;\f13b&quot;;margin-left:12px;color:#f60;font-family:fontawesome;display:initial;background:transparent}.gallery2 .widget-title h2:before{content:&quot;\f121&quot;;margin-left:12px;color:#d80000;font-family:fontawesome;display:initial;background:transparent}.gallery .columnl{width:100%;padding-right:0;float:none;margin-bottom:15px}.gallery .columnl .mainimg{width:70px;margin-left:2%;float:right}.gallery .columnl .mainimg .imag{width:70px;height:70px;position:relative;display:block;border-radius:4px}.gallery .columnl .titlelab{display:flex}.gallery .columnl:nth-child(1) .mainimg{width:100%;margin-left:0;float:none;height:300px}.gallery .columnl:nth-child(1) .mainimg .imag{width:100%;height:300px;position:relative;display:block;border-radius:3px}.gallery .author,.gallery .psummary,.gallery .tag{display:none}.gallery .columnl:nth-child(1) .cont{position:absolute;bottom:0;padding:15px}.gallery .columnl .titlelab{margin:0 3px 10px;font-size:16px;font-weight:500}.gallery .cont .titlelab a{color:#212121;font-weight:500;position:relative;line-height:1.4em}.gallery .columnl:nth-child(1) .cont .titlelab a{color:#fefefe;text-shadow:0 1px 1px rgba(0,0,0,0.5)}.gallery .columnl:hover .cont .titlelab a{color:#0099cc;transition:all .3s ease;-webkit-transition:all .3s ease;-moz-transition:all .3s ease;-o-transition:all .3s ease}.gallery .columnl:hover .mainimg .imag{opacity:.7;transition:all .3s ease;-webkit-transition:all .3s ease;-moz-transition:all .3s ease;-o-transition:all .3s ease}.gallery .columnl:nth-child(1) .mainimg:after{content:no-close-quote;position:absolute;left:0;bottom:0;width:100%;height:171px;background:url(https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjAwepe7SNbSz-qinDwCBKiLwrXf9F2fj82Mba5VFzZLhyphenhyphenDMXYFeoZBr0OtZ0A6NrMoXfAkSTLxbTAOfSNPa3RVM3AG0cxBqpgpo37DK-6LKWoVk0jpdQ5valVwHGCJOjan8b_NS96MNaI/s1600-r/metabg.png) repeat-x;background-size:100% 100%;opacity:.8}.gallery .autre{font-size:12px;color:#888;font-weight:400}.gallery .columnl:nth-child(1) .autre{color:#ccc}
/*=====================================
= Owl Carousel - Animate Plugin
=====================================*/
.owl-carousel .animated{-webkit-animation-duration:1000ms;animation-duration:1000ms;-webkit-animation-fill-mode:both;animation-fill-mode:both}.owl-carousel .owl-animated-in{z-index:0}.owl-carousel .owl-animated-out{z-index:1}.owl-carousel .fadeOut{-webkit-animation-name:fadeOut;animation-name:fadeOut}@-webkit-keyframes fadeOut{0%{opacity:1}100%{opacity:0}}@keyframes fadeOut{0%{opacity:1}100%{opacity:0}}.owl-height{-webkit-transition:height 500ms ease-in-out;-moz-transition:height 500ms ease-in-out;-ms-transition:height 500ms ease-in-out;-o-transition:height 500ms ease-in-out;transition:height 500ms ease-in-out}.owl-carousel{display:none;width:100%;-webkit-tap-highlight-color:transparent;position:relative;z-index:1}.owl-carousel .owl-stage{position:relative;-ms-touch-action:pan-Y}.owl-carousel .owl-stage:after{content:&quot;.&quot;;display:block;clear:both;visibility:hidden;line-height:0;height:0}.owl-carousel .owl-stage-outer{position:relative;overflow:hidden;-webkit-transform:translate3d(0px,0px,0px)}.owl-carousel .owl-controls .owl-nav .owl-prev,.owl-carousel .owl-controls .owl-nav .owl-next,.owl-carousel .owl-controls .owl-dot{cursor:pointer;cursor:hand;-webkit-user-select:none;-khtml-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel.owl-loaded{display:block}.owl-carousel.owl-loading{opacity:0;display:block}.owl-carousel.owl-hidden{opacity:0}.owl-carousel .owl-refresh .owl-item{display:none}.owl-carousel .owl-item{position:relative;min-height:1px;float:left;-webkit-backface-visibility:hidden;-webkit-tap-highlight-color:transparent;-webkit-touch-callout:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel .owl-item img{display:block;width:100%;-webkit-transform-style:preserve-3d}.owl-carousel.owl-text-select-on .owl-item{-webkit-user-select:auto;-moz-user-select:auto;-ms-user-select:auto;user-select:auto}.owl-carousel .owl-grab{cursor:move;cursor:-webkit-grab;cursor:-o-grab;cursor:-ms-grab;cursor:grab}.owl-carousel.owl-rtl{direction:rtl}.owl-carousel.owl-rtl .owl-item{float:right}.no-js .owl-carousel{display:block}.owl-carousel .owl-item .owl-lazy{opacity:0;-webkit-transition:opacity 400ms ease;-moz-transition:opacity 400ms ease;-ms-transition:opacity 400ms ease;-o-transition:opacity 400ms ease;transition:opacity 400ms ease}.owl-carousel .owl-item img{transform-style:preserve-3d}.owl-carousel .owl-video-wrapper{position:relative;height:100%;background:#000}.owl-carousel .owl-video-play-icon{position:absolute;height:80px;width:80px;left:50%;top:50%;margin-left:-40px;margin-top:-40px;background:url(owl.video.play.png) no-repeat;cursor:pointer;z-index:1;-webkit-backface-visibility:hidden;-webkit-transition:scale 100ms ease;-moz-transition:scale 100ms ease;-ms-transition:scale 100ms ease;-o-transition:scale 100ms ease;transition:scale 100ms ease}.owl-carousel .owl-video-play-icon:hover{-webkit-transition:scale(1.3,1.3);-moz-transition:scale(1.3,1.3);-ms-transition:scale(1.3,1.3);-o-transition:scale(1.3,1.3);transition:scale(1.3,1.3)}.owl-carousel .owl-video-playing .owl-video-tn,.owl-carousel .owl-video-playing .owl-video-play-icon{display:none}.owl-carousel .owl-video-tn{opacity:0;height:100%;background-position:center center;background-repeat:no-repeat;-webkit-background-size:contain;-moz-background-size:contain;-o-background-size:contain;background-size:contain;-webkit-transition:opacity 400ms ease;-moz-transition:opacity 400ms ease;-ms-transition:opacity 400ms ease;-o-transition:opacity 400ms ease;transition:opacity 400ms ease}.owl-carousel .owl-video-frame{position:relative;z-index:1}
.slider {
    background: #fefefe;
    padding: 2%;
    border-radius: 2px;
    margin-bottom: 2%;
}
.post-plus {
    width: 97.9%;
    position: relative;
    display: block;
    overflow: hidden;
}
.slider .widget-title {
    display: block;
    border-bottom: 1px solid #e2e2e2;
    padding: 10px 0;
    margin: 0 15px 25px;
}
.gallery .widget-title {
    display: block;
    border-bottom: 1px solid #e2e2e2;
    padding: 10px 0;
    margin: 0 15px 25px;
}
.slider .autre {
    font-size: 12px;
    color: #ccc;
    font-weight: 400;
}
.slider .autre {
    font-size: 12px;
    color: #ccc;
    font-weight: 400;
}
.videos .widget-title {
    display: block;
    border-bottom: 1px solid #e2e2e2;
    padding: 10px 0;
    margin: 0 15px 25px;
}
.videos .autre .author i, .slider .autre i, .gallery .autre i {
    margin-left: 5px;
}
.slider .widget-title h2:before {
    content: "\f17b";
    margin-left: 12px;
    color: #39a526;
    font-family: fontawesome;
    display: initial;
    background: transparent;
}
.gallery2 .widget-title h2:before {
    content: "\f121";
    margin-left: 12px;
    color: #f60;
    font-family: fontawesome;
    display: initial;
    background: transparent;
}
.gallery1 .widget-title h2:before {
    content: "\f17a";
    margin-left: 12px;
    color: #d80000;
    font-family: fontawesome;
    display: initial;
    background: transparent;
}
/* Video
------------------------------------------*/
.videos,.slider{background:#fefefe;padding:2%;border-radius:4px;margin-bottom:2%}.videos .widget-title h2:before{content:"\f16a";margin-left:12px;color:#da3c2b;font-family:fontawesome;display:initial;padding: 5px;background: #fefefe;border-radius: 10px;}.videos ul li{width:33.3333%;float:right;padding:1px;box-sizing:border-box}.maincon{position:relative;overflow:hidden}.videos .mainimg .imag{display:block;width:100%;height:210px;position:relative;overflow:hidden;opacity:.3!important;transition:all 1s ease;-moz-transition:all .8s ease;-ms-transition:all .8s ease;-webkit-transition:all .8s ease;-o-transition:all .8s ease}.videos .columnl:hover .imag{transform:scale(1.5);-moz-transform:scale(1.5);-webkit-transform:scale(1.5);-o-transform:scale(1.5);-ms-transform:scale(1.5)}.videos .cont{position:absolute;bottom:0;padding:15px;width:100%;right:0;z-index:2;box-sizing:border-box}.videos .times,.videos .psummary,.videos .tag{display:none}.videos .forever:before{content:"\f01d";font-family:fontawesome;position:absolute;top:10px;left:10px;font-size:30px;color:#fefefe}.videos .columnl:hover .forever:before{-ms-transform:rotate(360deg);-moz-transform:rotate(360deg);-webkit-transform:rotate(360deg);-o-transform:rotate(360deg);transform:rotate(360deg);-webkit-transition-duration:1s;-webkit-transition-delay:now;-webkit-animation-timing-function:linear;-webkit-animation-iteration-count:infinite;color:#BD383A}.videos .maincon:hover .titlelab a,.videos .maincon:hover .autre{color:#333;transition:all 1s ease;-moz-transition:all .8s ease;-ms-transition:all .8s ease;-webkit-transition:all .8s ease;-o-transition:all .8s ease}.videos .mainimg{border-radius:4px;overflow:hidden;background:#333;transition:all 1s ease;-moz-transition:all .8s ease;-ms-transition:all .8s ease;-webkit-transition:all .8s ease;-o-transition:all .8s ease}.videos .columnl:hover .mainimg{background:#fefefe}.videos .cont .titlelab{font-size:16px;position:relative;margin-bottom:8px}.videos .cont .titlelab a{color:#fefefe;font-weight:500;position:relative;line-height:1.4em;text-shadow:0 1px 1px rgba(0,0,0,0.5)}.videos .autre,.slider .autre{font-size:12px;color:#ccc;font-weight:400}.videos .autre .author i,.slider .autre i,.gallery .autre i{margin-left:5px}

/* Slider Wrapper
------------------------------ */
.slider-wrapper{
display: block;
margin-top: 5px;
margin-bottom: 5px;
}

.slider-wrapper .mag-content {
    position: absolute;
    bottom: 0;
    padding: 15px;
    text-align: center;
    background: -moz-linear-gradient(top,rgba(0,0,0,0) 0%,rgba(0,0,0,0.5) 100%);
    background: -webkit-gradient(linear,left top,left bottom,color-stop(0%,rgba(0,0,0,0)),color-stop(100%,rgba(0,0,0,0.5)));
    background: -webkit-linear-gradient(top,rgba(0,0,0,0) 0%,rgba(0,0,0,0.5) 100%);
    background: -o-linear-gradient(top,rgba(0,0,0,0) 0%,rgba(0,0,0,0.5) 100%);
    background: -ms-linear-gradient(top,rgba(0,0,0,0) 0%,rgba(0,0,0,0.5) 100%);
    background: linear-gradient(to bottom,rgba(0,0,0,0) 0%,rgba(0,0,0,0.5) 100%);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000',endColorstr='#a6000000',GradientType=0);
    color: #fff;
    font-size: 13px;
    width: 100%;
    font-family: 'DroidKufi bold' , Tahoma;
}
img.katib {
position: absolute;
width: 36px !important;
height: 36px !important;
border-radius: 8px;
left: 4px;
top: 8px;
border: 2px solid #fff;
transition: 0.3s;
}
.slider-wrapper .mag-content h3.mag-title a {
    color: #fff;
    font-size: 16px;
    display: block;
    padding-right: 5px;
    margin: 10px auto;
}
h3.mag-title a {
    line-height: 25px;
}
.time-cumen2 i,.time-cumen1 i {
display: inline-block;
margin-left: 6px;
}
.time-cumen2, .time-cumen1 {
    text-transform: capitalize;
    font-size: 11px;
    color: #ddd;
    display: inline-block;
    margin-left: 6px;
    padding-right: 4px;
    margin-top: 7px;
}
.slider-wrapper .mag-content .wasf p{
color: #f7f7f7;
font-size: 12px;
text-align: center;

}

.wasf {
    display: none;
}
.slider-wrapper .mag-thumb > a.imag:after {
    content: "";
    display: block;
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
    background: -webkit-linear-gradient(to top,rgba(0,0,0,0.7),transparent);
    background: -moz-linear-gradient(to top,rgba(0,0,0,0.7),transparent);
    background: linear-gradient(to top,rgba(0,0,0,0.7),transparent);
}
.slider-wrapper ul li {
position: relative;
overflow: hidden;
}
.slider-tag a {
    padding: 6px 9px;
    background: #192733;
    color: #fff;
    font-size: 13px;
    display: inline-block;
    z-index: 1;
    border-radius: 2px;
}
.slider-wrapper .mag-thumb > a.imag {
display: block;
height: 300px;
}
.slider-wrapper .owl-next {
    color: #fff;
    display: inline-block;
    cursor: pointer;
    padding: 13px!important;
    font-size: 18px!important;
    border-radius: 0!important;
    background: #2f323b!important;
}
.slider-wrapper .owl-controls .owl-nav > div:hover {
background: #fff!important;
color: #2f323b!important;
}
.slider-wrapper .owl-prev {
    color: #fff;
    display: inline-block;
    cursor: pointer;
    padding: 13px!important;
    font-size: 18px!important;
    border-radius: 0!important;
    background: #2f323b!important;
}
.slider-wrapper .owl-prev {
    position: absolute;
    right: 0px;
    top: 40%;
    transition: 0.4s;

}
.slider-wrapper .owl-next {
    position: absolute;
    left: 0px;
    top: 40%;
    transition: 0.4s;
}
.slider-wrapper .owl-controls .owl-nav >div:hover {
    opacity: 1;
    transition: 0.3s;
}
/* Owl Carsoul Css Reset
----------------------------------*/
.owl-carousel .animated{-webkit-animation-duration:1000ms;animation-duration:1000ms;-webkit-animation-fill-mode:both;animation-fill-mode:both}.owl-carousel .owl-animated-in{z-index:0}.owl-carousel .owl-animated-out{z-index:1}.owl-carousel .fadeOut{-webkit-animation-name:fadeOut;animation-name:fadeOut}@-webkit-keyframes fadeOut{0%{opacity:1}100%{opacity:0}}@keyframes fadeOut{0%{opacity:1}100%{opacity:0}}.owl-height{-webkit-transition:height 500ms ease-in-out;-moz-transition:height 500ms ease-in-out;-ms-transition:height 500ms ease-in-out;-o-transition:height 500ms ease-in-out;transition:height 500ms ease-in-out}.owl-carousel{display:none;width:100%;-webkit-tap-highlight-color:transparent;position:relative;z-index:1}.owl-carousel .owl-stage{position:relative;-ms-touch-action:pan-Y}.owl-carousel .owl-stage:after{content:&quot;.&quot;;display:block;clear:both;visibility:hidden;line-height:0;height:0}.owl-carousel .owl-stage-outer{position:relative;overflow:hidden;-webkit-transform:translate3d(0,0,0)}.owl-carousel .owl-controls .owl-dot,.owl-carousel .owl-controls .owl-nav .owl-next,.owl-carousel .owl-controls .owl-nav .owl-prev{cursor:pointer;cursor:hand;-webkit-user-select:none;-khtml-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel.owl-loaded{display:block}.owl-carousel.owl-loading{opacity:0;display:block}.owl-carousel.owl-hidden{opacity:0}.owl-carousel .owl-refresh .owl-item{display:none}.owl-carousel .owl-item{position:relative;min-height:1px;float:left;-webkit-backface-visibility:hidden;-webkit-tap-highlight-color:transparent;-webkit-touch-callout:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel .owl-item img{display:none;width:100%;-webkit-transform-style:preserve-3d}.owl-carousel.owl-text-select-on .owl-item{-webkit-user-select:auto;-moz-user-select:auto;-ms-user-select:auto;user-select:auto}.owl-carousel .owl-grab{cursor:move;cursor:-webkit-grab;cursor:-o-grab;cursor:-ms-grab;cursor:grab}.owl-carousel.owl-rtl{direction:rtl}.owl-carousel.owl-rtl .owl-item{float:left}.no-js .owl-carousel{display:block}.owl-carousel .owl-item .owl-lazy{opacity:0;-webkit-transition:opacity 400ms ease;-moz-transition:opacity 400ms ease;-ms-transition:opacity 400ms ease;-o-transition:opacity 400ms ease;transition:opacity 400ms ease}.owl-carousel .owl-item img{transform-style:preserve-3d}.owl-carousel .owl-video-wrapper{position:relative;height:100%;background:#000}.owl-carousel .owl-video-play-icon{position:absolute;height:80px;width:80px;left:50%;top:50%;margin-left:-40px;margin-top:-40px;background:url(owl.video.play.png) no-repeat;cursor:pointer;z-index:1;-webkit-backface-visibility:hidden;-webkit-transition:scale 100ms ease;-moz-transition:scale 100ms ease;-ms-transition:scale 100ms ease;-o-transition:scale 100ms ease;transition:scale 100ms ease}.owl-carousel .owl-video-play-icon:hover{-webkit-transition:scale(1.3,1.3);-moz-transition:scale(1.3,1.3);-ms-transition:scale(1.3,1.3);-o-transition:scale(1.3,1.3);transition:scale(1.3,1.3)}.owl-carousel .owl-video-playing .owl-video-play-icon,.owl-carousel .owl-video-playing .owl-video-tn{display:none}.owl-carousel .owl-video-tn{opacity:0;height:100%;background-position:center center;background-repeat:no-repeat;-webkit-background-size:contain;-moz-background-size:contain;-o-background-size:contain;background-size:contain;-webkit-transition:opacity 400ms ease;-moz-transition:opacity 400ms ease;-ms-transition:opacity 400ms ease;-o-transition:opacity 400ms ease;transition:opacity 400ms ease}.owl-carousel .owl-video-frame{position:relative;z-index:1}






/* التجاوب
--------------------------- */
.selectnav {display:none;}

@media screen and (max-width : 1150px){

}

@media screen and (max-width : 1000px){

#nav1 {display:none;}
#selectnav1 {
    border: 0;
    display: block !important;
    width: 100%;
    background: #ffffff;
    color: #243748;
    font-size: 15px;
    padding: 8px 8px;
    border-radius: 3px;
    margin-top: 7px;
    margin-bottom: 6px;
    font-family: 'DroidKufi bold' , Tahoma;
}
#nav {
display:none;
}
#selectnav2 {
    border: 0;
    display: inline-block !important;
    background: #ffffff;
    width: 100%;
    color: #243748;
    font-size: 13px;
    padding: 8px 8px;
    border-radius: 3px;
    margin-top: 0px;
    font-family: 'DroidKufi bold' , Tahoma;
}
#selectnav1 {
    float: right!important;
    width: 66%!important;
    right: 6px;
    top: -2px;
    position: relative;
}
#ads {display:none;}

}


@media screen and (max-width: 345px){

#selectnav1 {
    width: 58%!important;
}

#menu-left ul li a {
    width: 28px!important;
    padding-top: 7px!important;
    margin-left: 6px!important;
    height: 34px!important;
}
}


@media screen and (max-width: 291px){

#selectnav1 {
    width: 58%!important;
}

#menu-left ul li a {
    width: 28px!important;
    padding-top: 7px!important;
    margin-left: 6px!important;
    height: 34px!important;
}
}




    ]]></b:skin>



	<b:template-skin>
<![CDATA[
body#layout:before {background: #fff url(https://4.top4top.net/p_1242rz7ai1.jpg) no-repeat top center !important;content: "";display: block;width: 800px;height: 250px;box-shadow: rgba(0,0,0,0.45) 0 0 2px 0, rgba(0,0,0,0.78) 0 2px 2px 0;margin-bottom: 20px;}
]]>
</b:template-skin>







    <style>
      /* <!--: Fonts :--> */
      @font-face {
        font-family: &#39;DroidKufi Normal&#39;;
        font-style: normal;
        font-weight: 400;
        src: url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Regular.eot);
        src: url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Regular.eot?#iefix) format(&#39;embedded-opentype&#39;),
        url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Regular.woff2) format(&#39;woff2&#39;),
        url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Regular.woff) format(&#39;woff&#39;),
        url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Regular.ttf) format(&#39;truetype&#39;);
      }
      @font-face {
        font-family: &#39;DroidKufi Bold&#39;;
        font-style: normal;
        font-weight: 700;
        src: url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Bold.eot);
        src: url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Bold.eot?#iefix) format(&#39;embedded-opentype&#39;),
        url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Bold.woff2) format(&#39;woff2&#39;),
        url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Bold.woff) format(&#39;woff&#39;),
        url(//fonts.gstatic.com/ea/droidarabickufi/v6/DroidKufi-Bold.ttf) format(&#39;truetype&#39;);
      }
      /* <!--: Reset :--> */
      *{
        margin:0px;
        padding:0px;
        outline: 0px;
        box-sizing:border-box;
      }
      a{
        text-decoration: none;
        color: #efefef;
      }
      ul{
        padding: 0px;
        margin: 0px;
        list-style: none;
      }
      li{
        list-style: none;
      }

      .no-float{
        float:none;
      }
      .abs{
        position:absolute;
      }
      .clr{
        clear:both;
      }
      /* <!--: body :--> */
      body {
    background-size: 100%;
    direction: rtl;
    font-family: Tahoma;
    font-size: 14px;
    overflow-x: hidden;
    color: white;
    background: #673AB7;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-image: url(https://d.top4top.net/p_1201aec2c1.jpg);
    background-size: cover;
      }
      body::-webkit-scrollbar {
        width: 10px;
      }
      .feed-links {
        display: none;
      }
      body::-webkit-scrollbar-track {
        background: #fff;
        border-radius: 0px;
        box-shadow:inset 0 0 5px rgba(0,0,0,0.33);
        margin-left: 10px;
      }
      body::-webkit-scrollbar-thumb 
      {
        border-radius: 0px;
        background: #673AB7;
      }
      /* <!--: main-menu :--> */


      .st-pusher {
        position: relative;
        left: 0;
        z-index: 99;
        height: 100%;
        -webkit-transition: -webkit-transform 0.5s;
        transition: transform 0.5s;
      }


.slider-home {
    position: relative;
    overflow: hidden;
    width: 1200px;
    margin: 0 auto;
    background-color: rgba(52, 54, 66, 0.5);
}





      /* <!--: ترقيم الصفحات :--> */
      /******************************************/
#blog-pager {
    padding-top: 10px;
    margin: 1em 0;
    text-align: center;
    overflow: hidden;
}


#blog-pager-newer-link {
    color: #FFF;
    background: #673AB7;
    margin: 3px;
    -moz-border-radius: 2px;
    -webkit-border-radius: 2px;
    border-radius: 2px;
    padding: 8px 15px 8px 15px;
    display: inline-block;
    box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.19);
}
#blog-pager-newer-link {
    float: right;
}
#blog-pager-older-link {
    float: left;
}
#blog-pager-older-link {
    color: #FFF;
    background: #673AB7;
    margin: 3px;
    -moz-border-radius: 2px;
    -webkit-border-radius: 2px;
    border-radius: 2px;
    padding: 8px 15px 8px 15px;
    box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.19);
}


      /******************************************/
.footer .right {
float: right;
}
.footer .left {
float: left;
}
.footer {
    overflow: hidden;
    position: relative;
    background-color: rgba(9, 9, 9, 0.7);
    color: white;
    display: table;
    background-size: 1px 1px;
    padding: 9px 9px 11px 5px;
    box-sizing: border-box;
    border-top: 3px solid #6621e0;
    width: 100%;
    font-family: &#39;DroidKufi bold&#39; , Tahoma;
}

div.clear {
    clear: both;
}
.right a {
    color: white;
    background: #673AB7;
    padding: 3px 11px;
    border-radius: 35px;
    box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.19);
}
.left a {
    color: white;
    background: #673AB7;
    padding: 3px 11px;
    border-radius: 35px;
    box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.19);
}
      /* <!--: توافق مع شاشات الهواتف و الاجهزة اللوحية الذكية :--> */
      /******************************************/


 @media screen and (max-width : 1280px) {
/* CSS CODE HERE FOR DESKTOP ---*/
.container, .men, .yc-Soundtrack-master-loop , #footer , .slider-home , .main , .main-menu {
    float: none!important;
    width: 100%!important;
    margin: 0px !important;
}



}

@media screen and (max-width : 1024px) {
/* CSS CODE HERE FOR TABLETS ---*/
.container, .men, .yc-Soundtrack-master-loop , #footer , .slider-home , .main , .postff-img , .post-by-area ul {
    float: none!important;
    width: 100%!important;
    margin: 0px !important;
}

#mbt-sub-box {
    display: block !important;
}
.addthis_toolbox.addthis_default_style {
    display: block !important;
}
.related-pre a {
    width: 32.7% !important;
}
}


@media screen and (max-width : 853px) {
/* CSS CODE HERE FOR SMALL MOBILES ---*/
.container, .men, .yc-Soundtrack-master-loop , #footer , .slider-home , .main , .postff-img , .post-by-area ul {
    float: none!important;
    width: 100%!important;
    margin: 0px !important;
}

#mbt-sub-box {
    display: block !important;
}
.addthis_toolbox.addthis_default_style {
    display: block !important;
}
.related-pre a {
    width: 32.6% !important;
}
.postff-img {
    margin-bottom: 10px !important;
}
div#monitor{
    width: 100% !important;
    height: 100% !important;
    background-size: 100% 88% !important;
}
iframe {
    width: 100% !important;
    height: 100% !important;
}


}



@media screen and (max-width : 768px) {
/* CSS CODE HERE FOR SMALL TABLETS ---*/
.container, .men, .yc-Soundtrack-master-loop , #footer , .slider-home , .main , .postff-img , .post-by-area ul {
    float: none!important;
    width: 100%!important;
    margin: 0px !important;
}


#mbt-sub-box {
    display: block !important;
}
.addthis_toolbox.addthis_default_style {
    display: block !important;
}
.related-pre a {
    width: 49.1% !important;
}
.postff-img {
    margin-bottom: 10px !important;
}


}


@media screen and (max-width : 640px) {
/* CSS CODE HERE FOR IPHONE ---*/
.container, .men, .yc-Soundtrack-master-loop , #footer , .slider-home , .main , .postff-img , .post-by-area ul {
    float: none!important;
    width: 100%!important;
    margin: 0px !important;

}
#mbt-sub-box {
    display: block !important;
}
.addthis_toolbox.addthis_default_style {
    display: block !important;
}
.related-pre a {
    width: 48.8% !important;
}
.postff-img {
    margin-bottom: 10px !important;
}


}

@media screen and (max-width : 480px) {
/* CSS CODE HERE FOR SMARTPHONES ---*/
.container, .men, .yc-Soundtrack-master-loop , #footer , .slider-home , .main , .postff-img , .post-by-area ul {
    float: none!important;
    width: 100%!important;
    margin: 0px !important;

}
#mbt-sub-box {
    display: block !important;
}
.addthis_toolbox.addthis_default_style {
    display: block !important;
}
.related-pre a {
    width: 100% !important;
}
.postff-img {
    margin-bottom: 10px !important;
}



}

@media screen and (max-width : 320px) {
/* CSS CODE HERE FOR SMALL MOBILES ---*/
.container, .men, .yc-Soundtrack-master-loop , #footer , .slider-home , .main , .postff-img , .post-by-area ul {
    float: none!important;
    width: 100%!important;
    margin: 0px !important;

}
#mbt-sub-box {
    display: block !important;
}
.addthis_toolbox.addthis_default_style {
    display: block !important;
}
.related-pre a {
    width: 100% !important;
}
.postff-img {
    margin-bottom: 10px !important;
}

}




/* related-posts
------------------------------ */

/* Related Posts CSS */
.pre-head{font-weight: 500; list-style: none; margin: 10px 0 20px 0; overflow: hidden; padding: 14px 10px; position: relative; background: #1a2d3d; border-radius: 4px; box-shadow: 0px 3px 3px rgba(0, 0, 0, 0.47); text-align: center; font-size: 16px; top: 0; width: 100%;}
.related-pre{margin:0 0 25px; overflow:hidden;}
.related-pre a{ margin: 5px 0px 0px 5px; display: block; width: 287.5px; float: right; height: 320px; overflow: hidden; position: relative; box-shadow: 0px 3px 3px rgba(0, 0, 0, 0.47); border: 5px solid #dddddd; border-radius: 5px;}
.related-pre img{ height: 100%; width: 100%;}

.pre-title {
    width: 100%;
    background-color: rgba(24, 23, 22, 0.69);
    position: absolute;
    top: -100px;
    padding: 10px 10px;
    font-size: 13px;
    line-height: 30px;
    font-family: &#39;DroidKufi Bold&#39; , Tahoma;
    font-weight: bold;
    min-height: 50px;
    color: #FDF8F8;
    text-align: center;
    -webkit-animation-duration: 0.2s;
    animation-duration: 0.2s;
    -webkit-animation-fill-mode: both;
    animation-fill-mode: both;
    -webkit-transition: all 0.2s ease-in-out;
    -moz-transition: all 0.2s ease-in-out;
    -o-transition: all 0.2s ease-in-out;
    -ms-transition: all 0.2s ease-in-out;
    transition: all 0.2s ease-in-out;
}

.related-pre a:hover .pre-title {
    top: 0px;
    -webkit-animation-duration: 0.2s;
    animation-duration: 0.2s;
    -webkit-animation-fill-mode: both;
    animation-fill-mode: both;
    -webkit-animation-name: zoomInDown;
    animation-name: zoomInDown;
    -webkit-transition: all 0.2s ease-in-out;
    -moz-transition: all 0.2s ease-in-out;
    -o-transition: all 0.2s ease-in-out;
    -ms-transition: all 0.2s ease-in-out;
    transition: all 0.2s ease-in-out;
    z-index: 99999999;
}

/* all wrapper
------------------------------ */



/*------------------------------ */


.clear {clear:both;}
.widget {margin: 0;}
.widget-item-control ,.blog-feeds ,.status-msg-body, .date-header, .post-feeds, .status-msg-border {display:none;}
.widget .widget-item-control a img {display:none;}
.widget li, .BlogArchive #ArchiveList ul.flat li {padding: 0;}
.post-footer-line&gt;* {margin-left: 0;}





.w-1000 {
    font-family: &#39;DroidKufi bold&#39; , Tahoma;
}


.post-body img {
display: none;
}

.separator {
    clear: left !important;
}


.sizewrap {
    max-width: 1200px;
    margin: auto;
}




.taqdim-post {
    padding: 10px 10px 10px 10px;
    font-size: 14px;
    font-family: &#39;DroidKufi bold&#39; ,Tahoma;
    font-weight: 700;
    border-radius: 5px;
    margin-bottom: 10px;
    background: #1b2e3ecc;
    box-shadow: 0 0 5px rgba(0,0,0,0.46);
    margin-top: -45px;
}
.detalis-post li {
background: #5a07ec82;
    padding: 10px;
    border-right: 5px solid #FFF;
    border-radius: 3px;
    margin-bottom: 5px;
}
.detalis-post li span {
    display: inline-block;
    float: right;
    margin-left: 10px;
}



input[type=&quot;button&quot;] {
    background-color: #fff;
    cursor: pointer;
    padding: 7px 10px 7px;
    color: white;
    margin-bottom: 6px;
    border: 1px solid rgba(255, 255, 255, 0.09);
    background: rgb(87, 25, 197);
    transition: .3s all ease;
    font-family: &#39;Droid Arabic Kufi&#39;;
    text-align: center;
    display: inline-block;
    margin: 0 auto;
    border-radius: 7px;
    font-size: 16px;
    border-bottom: 5px solid rgba(0,0,0,0.48);
    box-shadow: 0 6px 8px -4px rgba(0,0,0,0.47);
    font-weight: 600;
}
div#monitor {
    background-image: url(https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhDH4uZqXzCuPrruDRvaBffaZ7h0jaMRZKVglQ4KDzCn_XK40PqVqzAWIsySvXafZTRYiHtpTofKk175O7f_eu2_R7YsZUWzyXIQ7eRE_ivs0jV2CrcFv3DDOsOC4kC16A1nIDq23b-Q-7J/s1600/tvanoamhd.png);
    background-size: 100% 406px;
    width: 80%;
    height: 440px;
    margin: auto;
    padding-top: 20px;
    padding-right: 14px;
    background-repeat: no-repeat;
    padding-bottom: 20px;
    padding-left: 14px;
    margin-top: 20px;
}

.downfilm p.title {
text-align: center;
    font-size: 18px;
    color: white;
    border-radius: 5px;
    font-weight: bold;
    padding: 12px;
    position: relative;
    box-shadow: 0 6px 8px -4px black;
    border-bottom: 5px solid rgba(0,0,0,0.5);
    background: -webkit-linear-gradient(left, rgba(45, 69, 98, 0.65) 0%, #2d4562 100%), -webkit-linear-gradient(left, #4d90fe 0%, #666 100%);
    font-family: &#39;DroidKufi bold&#39; , Tahoma;
    margin: 10px;
}


.downloadsList {
    text-align: center;
}
.downloadsList&gt;li {
    list-style: none;
    display: inline-block;
    overflow: hidden;
    width: 232px;
    margin-left: 4px;
    margin-right: 4px;
    margin-bottom: 10px;
    border-radius: 10px;
    height: 75px;
    text-align: right;
    direction: rtl;
    box-shadow: 0px 3px 7px rgba(0,0,0,0.81);
    background: linear-gradient(to right,#673AB7,#4a00ce);
}
.downloadsList&gt;li a {
    color: White;
}
.downloadsList&gt;li i {
    display: inline-block;
    width: 40px;
    height: 40px;
    background: white;
    border-radius: 50%;
    text-align: center;
    padding-top: 9px;
    font-size: 25px;
    color: #1e8be4;
    float: right;
    margin-top: 18px;
    margin-right: 16px;
    margin-left: 12px;
}
.downloadsList&gt;li .name {
    display: block;
    font-weight: bold;
    font-size: 18px;
    margin-top: 11px;
    line-height: 100%;
}
.downloadsList&gt;li .quality {
    display: block;
    font-size: 12px;
    line-height: 22px;
}
.downloadsList&gt;li .size {
    color: #FFED8F;
    font-weight: bold;
    font-size: 14px;
    display: block;
    line-height: 11px;
}



    </style>



    <!-- Slider -->

    <script type='text/javascript'>
      posts_no_thumb_sum = 100;
      posts_thumb_sum = 200;
    </script>
    <script type='text/javascript'>
      //<![CDATA[
      function removeHtmlTag(strx,chop){
        if(strx.indexOf("<")!=-1)
        {
          var s = strx.split("<");
          for(var i=0;i<s.length;i++){
            if(s[i].indexOf(">")!=-1){
              s[i] = s[i].substring(s[i].indexOf(">")+1,s[i].length);
            }
          }
          strx = s.join("");
        }
        chop = (chop < strx.length-1) ? chop : strx.length-2;
        while(strx.charAt(chop-1)!=' ' && strx.indexOf(' ',chop)!=-1) chop++;
        strx = strx.substring(0,chop-1);
        return strx+'...';
      }
      function createSummaryAndThumb(pID, pURL, pTITLE){
        var div = document.getElementById(pID);
        var imgtag = "";
        var img = div.getElementsByTagName("img");
        var summ = posts_no_thumb_sum;
        if(img.length>=1) {
          imgtag = '<span class="posts-thumb" style="float:right; margin: 0px auto;"><a href="'+ pURL +'"><img src="'+img[0].src+'" /></a></span>';
          summ = posts_thumb_sum;
        }
        else {
          imgtag = '<span class="posts-thumb" style="float:right; margin: 0px auto;"><a href="'+ pURL +'" title="'+ pTITLE+'"><img src="http://www.arabiclanguageic.org/uploads/item-1336774717-366.jpg" style="" /></a></span>';
          summ = posts_thumb_sum;
        }
        var summary = imgtag + '<a href="'+ pURL +'"><div class="post-summary-text">' + removeHtmlTag(div.innerHTML,summ) + '</div></a>';
        div.innerHTML = summary;
      }
      //]]>
    </script>
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
      <style>


        .slider-home {
          min-height: 800px;
          padding-top: 80px;
          padding: 15px;
          margin-bottom: 10px;
        }
        h3.post-title.entry-title {
    list-style: none;
    margin: 10px 0 20px 0;
    overflow: hidden;
    padding: 14px 10px;
    position: relative;
    background: #1a2d3d;
    border-radius: 4px;
    box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.47);
    text-align: center;
    font-size: 16px;
    top: 0;
    width: 100%;
        }
        pan.post-timestamp {
          color: white;
          background: #673AB7;
          padding: 7px 12px;
          position: relative;
          font-size: 14px;
          font-family: &#39;DroidKufi bold&#39; , Tahoma;
          font-weight: bold;
          margin-bottom: 5px;
        }
        span.post-labels a {
    background: #673AB7;
    padding: 5px 10px;
    border-radius: 3px;
    margin-left: 5px;
    color: white;
    font-size: 13px;
    font-family: &#39;DroidKufi bold&#39; , Tahoma;
    font-weight: bold;
        }
        .post-footer {
          display: table;
          width: 100%;
          margin-bottom: 10px;
          padding: 5px 6px 1px;
          border-radius: 3px;
          background-color: #1F2025;
          border-top: 1px solid #3A3B42;
          box-shadow: 0 6px 8px -6px rgba(0, 0, 0, 0.84);
          color: #fff;
        }

      </style>
    </b:if>
    <style>

    </style>






<script src='//code.jquery.com/jquery-1.10.2.min.js' type='text/javascript'/>









   <b:if cond='data:blog.pageType == &quot;item&quot;'>
      <style type='text/css'>
/*===post img===*/

.postff-img { margin: 0; padding: 0; display: block; overflow: hidden; float: right; width: 320px; border-radius: 3px; box-shadow: 0 0 5px black; height: 410px; }
.postff-img img { position: relative; display: table; height: 410px !important; width: 100%; }


/*===social share===*/
.addthis_toolbox.addthis_default_style { display: flex; }
a.social_share i{display: inline-block; line-height: 32px; text-align: center; margin-right: 6px; font-size: 14px!important; text-decoration: none; width: 70px; border-radius: 8px; color: #fff;}
a.social_share i:hover:before{content:&quot;\f1e0&quot;;}
a.social_share i.fa.fa-facebook{background:#2e76e4!important;}
a.social_share i.fa.fa-twitter{background:#03A9F4!important;}
a.social_share i.fa.fa-google-plus{background:#ea6237!important;}
a.social_share i.fa.fa-pinterest{background:#f14d4d!important;}
/*===before===*/

/*===post===*/
.post-by-area ul li b.fa { width: 30px; height: 40px; padding: 0; margin: 0 5px; float: right; display: flex; justify-content: center; align-items: center; text-align: center; font-size: 14px!important; color: #FFEB3B!important; text-decoration: none; }
.post-by-area ul { margin: 0; padding: 0; display: block; float: left; overflow: hidden; width: 72%; background: rgba(0,0,0,.5); border-radius: 8px; box-shadow: 0px 1px 3px rgba(0,0,0,.47); }
.post-by-area li { list-style: none; padding: 5px; margin: 8px; overflow: auto; display: block;}
.post-by-area ul li { line-height: 2.9em; background: #0099ff21; }
.post-by-area { color: #fff; }
div#views-container { float: unset; overflow: hidden; display: inline-table; }
.Reporting-ba-button a { padding: 2px 8px; line-height: normal; position: relative; display: table; background-color: #673AB7; border-bottom: 2px solid rgba(0,0,0,0.10); color: #FFFFFF!important; font-weight: 700; }
.Reporting-ba-button a:hover { background-color: #5a5a5a; }
/*===taqyem===*/


/*===sub===*/
#mbt-sub-box { position: relative; overflow: hidden; display: flex; }
#mbt-sub-box h1 { text-align: center; color: #fff; font-size: 15px; background: #673AB7; padding: 0px 10px 0px 10px; border-bottom: 2px solid rgba(0,0,0,0.10); }
#mbt-sub-box input { text-shadow: none; border: medium none; font-size: 12px; margin: 0 0 0 10px; padding: 0 10px; width: 180px; height: 35px; color: #484848; background-color: #EFEFF0; border-bottom: 1px solid #eaeaea; font-family: inherit; }
#mbt-sub-box .submit { background-color: #673AB7; border-bottom: 2px solid rgba(0,0,0,0.10); color: #FFFFFF!important; cursor: pointer; font-weight: bold; width: 80px; font-family: inherit; margin: 0; line-height: normal; }

/*===sub===*/
.tabs {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
    font-size: 8px;
}

.tabs label {
-webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    display: block;
    padding: 1rem 2rem;
    cursor: pointer;
    font-weight: bold;
    -webkit-transition: background ease 0.2s;
    background: #673AB7;
    color: #fff;
    overflow: hidden;
    -webkit-transition: color 0.3s;
    transition: color 0.3s;
    font-size: 20px;
    box-shadow: 0px 1px 6px rgba(0, 0, 0, 0.51);
    display: block;
    margin: 0;
    border: none;
    vertical-align: middle;
    z-index: 1;
    -webkit-backface-visibility: hidden;
    -moz-osx-font-smoothing: grayscale;
    bottom: 0;
    left: 0;
    outline: none;
}

.tabs .tab {
  -webkit-box-ordinal-group: 100;
  -webkit-order: 99;
  -ms-flex-order: 99;
  order: 99;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  width: 100%;
  display: none;
  padding: 1rem;
background: #1b2e3ecc;
}

.tabs input[type=&quot;radio&quot;] {
  position: absolute;
  opacity: 0;
}

.tabs input[type=&quot;radio&quot;]:checked + label { background: #fafafa; color: #673AB7;}

.tabs input[type=&quot;radio&quot;]:checked + label + .tab { display: block; }
@media (max-width: 45em) {

.tabs .tab,  .tabs label {
  -webkit-box-ordinal-group: NaN;
  -webkit-order: initial;
  -ms-flex-order: initial;
  order: initial;
}

.tabs label {
  width: 100%;
  margin-right: 0;
  margin-top: 0.2rem;
}
}

    </style>
    <script src='//cdn.firebase.com/v0/firebase.js' type='text/javascript'/>
    <script async='async' id='dsq-count-scr' src='//NAME.disqus.com/count.js'/>
    </b:if>


<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<style type='text/css'>
/* Page Navigation */
#blog-pager{clear:both;width:auto;padding:22px;line-height:normal;position:relative;display:block;text-align:center;overflow:visible;margin:20px 0 5px 0}
.showpage a,.showpageNum a,.showpagePoint,.showpageOf{position: relative; background: #1a2d3d; display: inline-block; font-size: 13px; color: #fff; padding: 6px 12px; margin: 0 4px 0 0; transition: all .2s; border-radius: 5px; box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.47);}
.showpageNum a:before{content:&#39;&#39;;position:absolute;top:0;bottom:0;left:0;right:0;box-shadow:inset 0 -2px 2px rgba(0,0,0,0.02);transition:box-shadow 0.5s}

.showpageNum a:hover {
    background-color: #9fa2a2;
    color: #fff;
    transition: all .2s linear;
    border-radius: 100px;
    border-radius: 5px;
}

.showpagePoint{background:#673AB7;color:#fff;}
@media screen and (max-width:640px) {
#blog-pager {padding:12px;}
.showpage a,.showpageNum a,.showpagePoint,.showpageOf{margin:0 2px 2px 0;box-shadow:0 1px 2px 1px rgba(0,0,0,0.1);}}
@media screen and (max-width:320px) {
.showpage a,.showpageNum a,.showpagePoint,.showpageOf{padding:3px 6px}}
</style>
</b:if>
</b:if>



<b:if cond='data:blog.pageType != &quot;item&quot;'>
<style type='text/css'>

 @media screen and (max-width : 1280px) {
/* CSS CODE HERE FOR DESKTOP ---*/
.post {
    width: 24% !important;
}
}

@media screen and (max-width : 1024px) {
/* CSS CODE HERE FOR TABLETS ---*/
.post {
    width: 32.1% !important;
}
}

@media screen and (max-width : 853px) {
/* CSS CODE HERE FOR SMALL MOBILES ---*/
.post {
    width: 32% !important;
}
}

@media screen and (max-width : 768px) {
/* CSS CODE HERE FOR SMALL TABLETS ---*/
.post {
    width: 48.4% !important;
}
}

@media screen and (max-width : 640px) {
/* CSS CODE HERE FOR IPHONE ---*/
.post {
    width: 47.8% !important;
}
}
@media screen and (max-width : 480px) {
/* CSS CODE HERE FOR SMARTPHONES ---*/
.post {
    width: 97% !important;
}

}

@media screen and (max-width : 320px) {
/* CSS CODE HERE FOR SMALL MOBILES ---*/
.post {
    width: 96% !important;
}
}



</style>
</b:if>



<b:if cond='data:blog.pageType == &quot;item&quot;'>
<script type='text/javascript'>
//<![CDATA[

// related post widget
var relatedTitles = new Array(); var relatedTitlesNum = 0; var relatedUrls = new Array(); var thumburl = new Array(); function related_results_labels_thumbs(e) {for (var t = 0; t < e.feed.entry.length; t++) { var l = e.feed.entry[t]; relatedTitles[relatedTitlesNum] = l.title.$t; try { thumburl[relatedTitlesNum] = l.gform_foot.url } catch (r) { s = l.content.$t, a = s.indexOf("<img"), b = s.indexOf('src="', a), c = s.indexOf('"', b + 5), d = s.substr(b + 5, c - b - 5), thumburl[relatedTitlesNum] = -1 != a && -1 != b && -1 != c && "" != d ? d : "http://1.bp.blogspot.com/-Nit_LiUtMHE/VflsSxNxENI/AAAAAAAADiM/CuVVm4SVl8E/s320/No-image-bt9.jpg"}
relatedTitles[relatedTitlesNum].length > 47 && (relatedTitles[relatedTitlesNum] = relatedTitles[relatedTitlesNum].substring(0, 47) + "..."); for (var i = 0; i < l.link.length; i++) "alternate" == l.link[i].rel && (relatedUrls[relatedTitlesNum] = l.link[i].href, relatedTitlesNum++) }}
function removeRelatedDuplicates_thumbs() {for (var e = new Array(0), t = new Array(0), l = new Array(0), r = 0; r < relatedUrls.length; r++) contains_thumbs(e, relatedUrls[r]) || (e.length += 1, e[e.length - 1] = relatedUrls[r], t.length += 1, l.length += 1, t[t.length - 1] = relatedTitles[r], l[l.length - 1] = thumburl[r]);  relatedTitles = t, relatedUrls = e, thumburl = l}
function contains_thumbs(e, t) { for (var l = 0; l < e.length; l++) if (e[l] == t) return !0;  return !1}
function printRelatedLabels_thumbs() { for (var e = 0; e < relatedUrls.length; e++) relatedUrls[e] != currentposturl && relatedTitles[e] || (relatedUrls.splice(e, 1), relatedTitles.splice(e, 1), thumburl.splice(e, 1), e--); var t = Math.floor((relatedTitles.length - 1) * Math.random())  , e = 0; for (relatedTitles.length > 0 && document.write('<h4 class="pre-head">' + relatedpoststitle + "</h4>"), document.write('<div class="related-pre"/>'); e < relatedTitles.length && 20 > e && e < maxresults;) document.write('<a '), document.write(0 != e ? '"' : '"'), document.write(' href="' + relatedUrls[t] + '"><img src="' + thumburl[t] + '"/><div class="pre-title">' + relatedTitles[t] + "</div></a>"), t < relatedTitles.length - 1 ? t++ : t = 0, e++;  document.write("</div>"), relatedUrls.splice(0, relatedUrls.length), thumburl.splice(0, thumburl.length), relatedTitles.splice(0, relatedTitles.length)}
//]]>
</script>
</b:if>

      &lt;/head&gt;&lt;!--<head/>--&gt;



	<body expr:class='data:blog.pageType'>
    <div class='container'>



      <!-- start search -->
      <div id='searchWrap'>
        <a href='javascript:void(0)'><div class='closeSearch'><i aria-hidden='true' class='fa fa-times'/></div></a>
        <form action='/search' id='search' method='get' role='search'>
          <input id='searchBar' name='q' placeholder='اكتب كلمة البحث' type='text'/>
        </form>
      </div>
      <!-- end search -->


<div class='all-wrapper'>
      <div class='header-top'>
      <div class='sizewrap'>
    <div class='menu-right'>
      <b:section class='section' id='menu-right'>
        <b:widget id='LinkList2' locked='true' title='القائمه الرئيسيه' type='LinkList' version='1'>
          <b:widget-settings>
            <b:widget-setting name='sorting'>NONE</b:widget-setting>
            <b:widget-setting name='text-1'>اتصل بنا</b:widget-setting>
            <b:widget-setting name='link-1'>#</b:widget-setting>
            <b:widget-setting name='text-0'>الرئيسية</b:widget-setting>
            <b:widget-setting name='link-2'>#</b:widget-setting>
            <b:widget-setting name='link-0'>https://aflami4uu.blogspot.com/</b:widget-setting>
            <b:widget-setting name='text-2'>أعلن لدينا</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>

<b:if cond='data:title != &quot;&quot;'/>
 <div class='widget-content'>
   <ul id='nav1'>
     <b:loop values='data:links' var='link'>
       <li><a expr:href='data:link.target'><data:link.name/></a></li>
     </b:loop>
   </ul>
   <b:include name='quickedit'/>
 </div>
</b:includable>
        </b:widget>
        <b:widget id='Navbar1' locked='false' title='Navbar' type='Navbar' version='1'>
          <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/platform.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar/8113672208871274745?origin\x3dhttp://localhost:80&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
        </b:widget>
      </b:section>
        </div>
    <div class='menu-left'>
      <b:section class='section' id='menu-left'>
        <b:widget id='LinkList1' locked='true' title='التواصل الاجتماعي' type='LinkList' version='1'>
          <b:widget-settings>
            <b:widget-setting name='link-3'>https://www.youtube.com/channel/UCarFi61rWX8fiaB8mkVKM0w</b:widget-setting>
            <b:widget-setting name='sorting'>NONE</b:widget-setting>
            <b:widget-setting name='text-1'>google-plus</b:widget-setting>
            <b:widget-setting name='link-1'>https://www.youtube.com/channel/UCarFi61rWX8fiaB8mkVKM0w</b:widget-setting>
            <b:widget-setting name='text-0'>twitter</b:widget-setting>
            <b:widget-setting name='link-2'>https://www.youtube.com/channel/UCarFi61rWX8fiaB8mkVKM0w</b:widget-setting>
            <b:widget-setting name='text-3'>facebook</b:widget-setting>
            <b:widget-setting name='link-0'>https://www.youtube.com/channel/UCarFi61rWX8fiaB8mkVKM0w</b:widget-setting>
            <b:widget-setting name='text-2'>youtube</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>

 <div class='widget-content'>
   <ul>
     <b:loop values='data:links' var='link'>
       <li><a expr:class='data:link.name' expr:href='data:link.target'/></li>
     </b:loop>
   </ul>
   <b:include name='quickedit'/>
 </div>
</b:includable>
        </b:widget>
      </b:section>
        </div>
      </div>
      </div>
	  <div class='header-wrapper'>
      <div class='sizewrap'>
      <div id='logo'>
        <b:section class='section' id='logo'>
          <b:widget id='Header1' locked='true' title='أفلامي | مشاهدة الافلام مباشرة افلام مشاهدة مباشرة اون لاين عربى واجنبى (رأس الصفحة)' type='Header'>
            <b:widget-settings>
              <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhEHVqEb6_rIqo0ZEX9vupQ0orJIQN6wtkj6TGRvCaA4MnQXgk5ij6FFxhMkt8L55zeD8UohbDh2W9p7dxnxZgz8vGndekdXuF4LgM5aAUDys3uQ76bXN5X3UvyF00Ov07vHCuU3ZfjWb8R/s1600/Untitled-1.png</b:widget-setting>
              <b:widget-setting name='displayHeight'>186</b:widget-setting>
              <b:widget-setting name='sectionWidth'>194</b:widget-setting>
              <b:widget-setting name='useImage'>true</b:widget-setting>
              <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
              <b:widget-setting name='imagePlacement'>REPLACE</b:widget-setting>
              <b:widget-setting name='displayWidth'>370</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
        <div id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      <b:else/>
        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
            <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
            <b:includable id='title'>
  <b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
    <data:title/>
  </b:tag>
</b:includable>
          </b:widget>
        </b:section>
        </div>
      <div id='ads'>
        <b:section class='section' id='ads'>
          <b:widget id='HTML7' locked='false' title='' type='HTML'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[<script src="https://gloumsee.net/pfe/current/tag.min.js?z=3522663" data-cfasync="false" async="async" ></script>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
          </b:widget>
          <b:widget id='HTML12' locked='false' title='' type='HTML'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[<script>(function(s,u,z,p){s.src=u,s.setAttribute('data-zone',z),p.appendChild(s);})(document.createElement('script'),'https://iclickcdn.com/tag.min.js',3522655,document.body||document.documentElement)</script>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
          </b:widget>
        </b:section>
        </div>
        </div>
        </div>
      <div class='main-menu'>
      <div class='sizewrap'>
      <a class='Home' href='/' title='الرئيسية'><i class='fa fa-home'/></a>
        <b:section class='section' id='main-menu'>
          <b:widget id='LinkList3' locked='true' title='القائمه الرئيسيه' type='LinkList' version='1'>
            <b:widget-settings>
              <b:widget-setting name='link-5'>https://aflami4uu.blogspot.com/search/label/Netflix</b:widget-setting>
              <b:widget-setting name='link-3'>https://aflami4uu.blogspot.com/search/label/%D8%A3%D9%81%D9%84%D8%A7%D9%85%20%D8%A7%D9%84%D9%83%D8%B1%D8%AA%D9%88%D9%86</b:widget-setting>
              <b:widget-setting name='link-4'>https://aflami4uu.blogspot.com/search/label/%D9%85%D8%B3%D9%84%D8%B3%D9%84%D8%A7%D8%AA%20%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9</b:widget-setting>
              <b:widget-setting name='text-1'>افلام اجنبي</b:widget-setting>
              <b:widget-setting name='text-0'>افلام عربي</b:widget-setting>
              <b:widget-setting name='text-3'>افلام كرتون</b:widget-setting>
              <b:widget-setting name='text-2'>افلام هندي</b:widget-setting>
              <b:widget-setting name='text-5'>مسلسلات اجنبي</b:widget-setting>
              <b:widget-setting name='text-4'>مسلسلات كرتون</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='link-1'>https://aflami4uu.blogspot.com/search/label/%D8%A3%D9%81%D9%84%D8%A7%D9%85%20%D8%A7%D9%84%D8%A3%D9%83%D8%B4%D9%86</b:widget-setting>
              <b:widget-setting name='link-2'>https://aflami4uu.blogspot.coM/search/label/%D8%A3%D9%81%D9%84%D8%A7%D9%85%20%D9%87%D9%86%D8%AF%D9%8A%20%D8%A7%D9%83%D8%B4%D9%86</b:widget-setting>
              <b:widget-setting name='link-0'>https://aflami4uu.blogspot.com/search/label/%D8%A3%D9%81%D9%84%D8%A7%D9%85%20%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9%20%D8%AD%D8%B5%D8%B1%D9%8A%D8%A9</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>

 <div class='widget-content'>
   <ul id='nav'>
     <b:loop values='data:links' var='link'>
       <li><a expr:href='data:link.target'><data:link.name/></a></li>
     </b:loop>
   </ul>
   <b:include name='quickedit'/>
 </div>
<script type='text/javascript'> 
//<![CDATA[

$("#LinkList3").each(function(){var e="<ul id='nav'><li><ul id='sub-menu'>";$("#LinkList3 li").each(function(){var t=$(this).text(),n=t.substr(0,1),r=t.substr(1);"_"==n?(n=$(this).find("a").attr("href"),e+='<li><a href="'+n+'">'+r+"</a></li>"):(n=$(this).find("a").attr("href"),e+='</ul></li><li><a href="'+n+'">'+t+"</a><ul id='sub-menu'>")});e+="</ul></li></ul>";$(this).html(e);$("#LinkList3 ul").each(function(){var e=$(this);if(e.html().replace(/\s|&nbsp;/g,"").length==0)e.remove()});$("#LinkList3 li").each(function(){var e=$(this);if(e.html().replace(/\s|&nbsp;/g,"").length==0)e.remove()})});
$('ul#sub-menu').parent('li').children('a').addClass('has-sub');
//]]>
</script>
</b:includable>
          </b:widget>
        </b:section>
<li class='searchIcon'>
<a href='javascript:void(0)'><i aria-hidden='true' class='fa fa-search'/></a>
</li>
        </div>
        </div>
  </div>



<div class='clear'/>
<div class='clear'/>
    <b:if cond='data:blog.url == data:blog.homepageUrl'>
    <div class='slider-wrapper'>
      <b:section class='section' id='slider-posts'>
        <b:widget id='HTML3' locked='false' title='' type='HTML'>
          <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
        </b:widget>
        <b:widget id='HTML222' locked='true' title='سلايد شو' type='HTML' version='1'>
          <b:widget-settings>
            <b:widget-setting name='content'>افلام اجنبي</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
      <!-- only display title if it's non-empty -->
      <b:if cond='data:title != &quot;&quot;'>
      </b:if>
      <div class='widget-content'>
        <data:content/>
      </div>

      <b:include name='quickedit'/>
    </b:includable>
        </b:widget>
      </b:section>

      </div>
      </b:if>
<div class='clear'/>
<div class='clear'/>






      <div class='st-pusher'>









        <div class='w-1000'>
          <div class='slider-home'>
            <ul id='home-posts3'>
              <b:section class='main' id='main' showaddelement='no'>
                <b:widget id='Blog1' locked='true' title='رسائل المدونة الإلكترونية' type='Blog' version='1'>
                  <b:widget-settings>
                    <b:widget-setting name='commentLabel'>comments</b:widget-setting>
                    <b:widget-setting name='showShareButtons'>true</b:widget-setting>
                    <b:widget-setting name='authorLabel'>By</b:widget-setting>
                    <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                    <b:widget-setting name='timestampLabel'>-</b:widget-setting>
                    <b:widget-setting name='reactionsLabel'/>
                    <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
                    <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                    <b:widget-setting name='showLocation'>false</b:widget-setting>
                    <b:widget-setting name='showTimestamp'>false</b:widget-setting>
                    <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                    <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='backlinksLabel'/>
                    <b:widget-setting name='showDateHeader'>false</b:widget-setting>
                    <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showCommentLink'>false</b:widget-setting>
                    <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showAuthor'>false</b:widget-setting>
                    <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showLabels'>true</b:widget-setting>
                    <b:widget-setting name='postLabelsLabel'>.</b:widget-setting>
                    <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                    <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                    <b:widget-setting name='showReactions'>false</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main' var='top'>
                    <b:if cond='!data:mobile'>
                      <!-- posts -->
                      <div class='blog-posts hfeed'>
                        <b:include data='top' name='status-message'/>
                        <b:loop values='data:posts' var='post'>
                          <b:if cond='data:post.isDateStart and not data:post.isFirstPost'>
                            &lt;/div&gt;&lt;/div&gt;
                          </b:if>
                          <b:if cond='data:post.isDateStart'>
                            &lt;div class=&quot;date-outer&quot;&gt;
                          </b:if>
                          <b:if cond='data:post.dateHeader'>
                            <h2 class='date-header'>
                              <span>
                                <data:post.dateHeader/>
                              </span>
                            </h2>
                          </b:if>
                          <b:if cond='data:post.isDateStart'>
                            &lt;div class=&quot;date-posts&quot;&gt;
                          </b:if>
                          <div class='post-outer'>
                            <b:include data='post' name='post'/>
                            <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
                          </div>
                          <!-- Ad -->
                          <b:if cond='data:post.includeAd'>
                            <div class='inline-ad'>
                              <data:adCode/>
                            </div>
                          </b:if>
                        </b:loop>
                        <b:if cond='data:numPosts != 0'>
                          &lt;/div&gt;&lt;/div&gt;
                        </b:if>
                      </div>
                      <!-- navigation -->
                      <b:if cond='data:blog.pageType == &quot;index&quot;'>
                        <b:include name='nextprev'/>
                        <b:else/>
                        <b:if cond='data:blog.pageType == &quot;archive&quot;'>
                          <b:include name='nextprev'/>
                          <b:else/>
                          <b:if cond='data:blog.homepageUrl != data:blog.url'>
                            <!-- navigation -->
                            <b:include name='nextprev'/>
                          </b:if>
                        </b:if>
                      </b:if> 
                      <!-- feed links -->
                      <b:include name='feedLinks'/>
                      <b:else/>
                      <b:include name='mobile-main'/>
                    </b:if>
                    <b:if cond='data:top.showPlusOne'>
                      <data:top.googlePlusBootstrap/>
                    </b:if>
                  </b:includable>
                  <b:includable id='backlinkDeleteIcon' var='backlink'>
                    <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
                      <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
                        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
                      </a>
                    </span>
                  </b:includable>
                  <b:includable id='backlinks' var='post'>
                    <a name='links'/>
                    <h4>
                      <data:post.backlinksLabel/>
                    </h4>
                    <b:if cond='data:post.numBacklinks != 0'>
                      <dl class='comments-block' id='comments-block'>
                        <b:loop values='data:post.backlinks' var='backlink'>
                          <div class='collapsed-backlink backlink-control'>
                            <dt class='comment-title'>
                              <span class='backlink-toggle-zippy'>
                                &#160;
                              </span>
                              <b:include data='backlink' name='backlinkDeleteIcon'/>
                            </dt>
                            <dd class='comment-body collapseable'>
                              <data:backlink.snippet/>
                            </dd>
                            <dd class='comment-footer collapseable'>
                              <span class='comment-author'>
                                <data:post.authorLabel/>
                                <data:backlink.author/>
                              </span>
                              <span class='comment-timestamp'>
                                <data:post.timestampLabel/>
                                <data:backlink.timestamp/>
                              </span>
                            </dd>
                          </div>
                        </b:loop>
                      </dl>
                    </b:if>
                    <p class='comment-footer'>
                      <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'>
                        <data:post.createLinkLabel/>
                      </a>
                    </p>
                  </b:includable>
                  <b:includable id='comment-form' var='post'>
                    <div class='comment-form'>
                      <a name='comment-form'/>
                      <b:if cond='data:mobile'>
                        <h4 id='comment-post-message'>
                          <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'>
                            <data:postCommentMsg/>
                          </a>
                        </h4>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                        <data:blogTeamBlogMessage/>
                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                        <b:else/>
                        <h4 id='comment-post-message'>
                          <data:postCommentMsg/>
                        </h4>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                        <data:blogTeamBlogMessage/>
                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
                      </b:if>
                      <data:post.friendConnectJs/>
                      <data:post.cmtfpIframe/>
                      <script type='text/javascript'>
                        BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
                      </script>
                    </div>
                  </b:includable>
                  <b:includable id='commentDeleteIcon' var='comment'>
                    <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
                      <b:if cond='data:showCmtPopup'>
                        <div class='goog-toggle-button'>
                          <div class='goog-inline-block comment-action-icon'/>
                        </div>
                        <b:else/>
                        <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
                          <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
                        </a>
                      </b:if>
                    </span>
                  </b:includable>
                  <b:includable id='comment_count_picker' var='post'>
                    <b:if cond='data:post.commentSource == 1'>
                      <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.url.canonical.http'>
                      </span>
                      <b:else/>
                      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                        <data:post.commentLabelFull/>
                        :
                      </a>
                    </b:if>
                  </b:includable>
                  <b:includable id='comment_picker' var='post'>
                    <b:if cond='data:post.commentSource == 1'>
                      <b:include data='post' name='iframe_comments'/>
                      <b:elseif cond='data:post.showThreadedComments'/>
                      <b:include data='post' name='threaded_comments'/>
                      <b:else/>
                      <b:include data='post' name='comments'/>
                    </b:if>
                  </b:includable>
                  <b:includable id='comments' var='post'>
                    <div class='comments' id='comments'>
                      <a name='comments'/>
                      <b:if cond='data:post.allowComments'>
                        <h4>
                          <data:post.commentLabelFull/>
                          :
                        </h4>
                        <b:if cond='data:post.commentPagingRequired'>
                          <span class='paging-control-container'>
                            <b:if cond='data:post.hasOlderLinks'>
                              <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                                <data:post.oldestLinkText/>
                              </a>
                              &#160;
                              <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                                <data:post.olderLinkText/>
                              </a>
                              &#160;
                            </b:if>
                            <data:post.commentRangeText/>
                            <b:if cond='data:post.hasNewerLinks'>
                              &#160;
                              <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                                <data:post.newerLinkText/>
                              </a>
                              &#160;
                              <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                                <data:post.newestLinkText/>
                              </a>
                            </b:if>
                          </span>
                        </b:if>
                        <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
                          <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
                            <b:loop values='data:post.comments' var='comment'>
                              <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
                                <b:if cond='data:comment.favicon'>
                                  <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
                                </b:if>
                                <a expr:name='data:comment.anchorName'/>
                                <b:if cond='data:blog.enabledCommentProfileImages'>
                                  <data:comment.authorAvatarImage/>
                                </b:if>
                                <b:if cond='data:comment.authorUrl'>
                                  <b:else/>
                                  <data:comment.author/>
                                </b:if>
                                <data:commentPostedByMsg/>
                              </dt>
                              <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
                                <b:if cond='data:comment.isDeleted'>
                                  <span class='deleted-comment'>
                                    <data:comment.body/>
                                  </span>
                                  <b:else/>
                                  <p>
                                    <data:comment.body/>
                                  </p>
                                </b:if>
                              </dd>
                              <dd class='comment-footer'>
                                <span class='comment-timestamp'>
                                  <a expr:href='data:comment.url' title='comment permalink'>
                                    <data:comment.timestamp/>
                                  </a>
                                  <b:include data='comment' name='commentDeleteIcon'/>
                                </span>
                              </dd>
                            </b:loop>
                          </dl>
                        </div>
                        <b:if cond='data:post.commentPagingRequired'>
                          <span class='paging-control-container'>
                            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                              <data:post.oldestLinkText/>
                            </a>
                            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                              <data:post.olderLinkText/>
                            </a>
                            &#160;
                            <data:post.commentRangeText/>
                            &#160;
                            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                              <data:post.newerLinkText/>
                            </a>
                            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                              <data:post.newestLinkText/>
                            </a>
                          </span>
                        </b:if>
                        <p class='comment-footer'>
                          <b:if cond='data:post.embedCommentForm'>
                            <b:if cond='data:post.allowNewComments'>
                              <b:include data='post' name='comment-form'/>
                              <b:else/>
                              <data:post.noNewCommentsText/>
                            </b:if>
                            <b:elseif cond='data:post.allowComments'/>
                            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                              <data:postCommentMsg/>
                            </a>
                          </b:if>
                        </p>
                      </b:if>
                      <b:if cond='data:showCmtPopup'>
                        <div id='comment-popup'>
                          <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                          </iframe>
                        </div>
                      </b:if>
                      <div id='backlinks-container'>
                        <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                          <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
                        </div>
                      </div>
                    </div>
                  </b:includable>
                  <b:includable id='feedLinks'>
                    <b:if cond='data:blog.pageType != &quot;item&quot;'>
                      <!-- Blog feed links -->
                      <b:if cond='data:feedLinks'>
                        <div class='blog-feeds'>
                          <b:include data='feedLinks' name='feedLinksBody'/>
                        </div>
                      </b:if>
                      <b:else/>
                      <!--Post feed links -->
                      <div class='post-feeds'>
                        <b:loop values='data:posts' var='post'>
                          <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
                        </b:loop>
                      </div>
                    </b:if>
                  </b:includable>
                  <b:includable id='feedLinksBody' var='links'>
                    <div class='feed-links'>
                      <data:feedLinksMsg/>
                      <b:loop values='data:links' var='f'>
                        <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'>
                          <data:f.name/>
                          (
                          <data:f.feedType/>
                          )
                        </a>
                      </b:loop>
                    </div>
                  </b:includable>
                  <b:includable id='iframe_comments' var='post'>
                    <b:if cond='data:post.allowIframeComments'>
                      <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
                      <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>
                      <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
                        <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                          <data:postCommentMsg/>
                        </a>
                      </b:if>
                    </b:if>
                  </b:includable>
                  <b:includable id='mobile-index-post' var='post'>
                    <div class='mobile-date-outer date-outer'>
                      <b:if cond='data:post.dateHeader'>
                        <div class='date-header'>
                          <span>
                            <data:post.dateHeader/>
                          </span>
                        </div>
                      </b:if>
                      <div class='mobile-post-outer'>
                        <a expr:href='data:post.url'>
                          <h3 class='mobile-index-title entry-title' itemprop='name'>
                            <data:post.title/>
                          </h3>
                          <div class='mobile-index-arrow'>
                            &amp;rsaquo;
                          </div>
                          <div class='mobile-index-contents'>
                            <b:if cond='data:post.thumbnailUrl'>
                              <div class='mobile-index-thumbnail'>
                                <div class='Image'>
                                  <img expr:src='data:post.thumbnailUrl'/>
                                </div>
                              </div>
                            </b:if>
                            <div class='post-body'>
                              <b:if cond='data:post.snippet'>
                                <data:post.snippet/>
                              </b:if>
                            </div>
                          </div>
                          <div style='clear: both;'/>
                        </a>
                        <div class='mobile-index-comment'>
                          <b:include cond='data:blog.pageType != &quot;static_page&quot;                          and data:post.allowComments                          and data:post.numComments != 0' data='post' name='comment_count_picker'/>
                        </div>
                      </div>
                    </div>
                  </b:includable>
                  <b:includable id='mobile-main' var='top'>
                    <!-- posts -->
                    <div class='blog-posts hfeed'>
                      <b:include data='top' name='status-message'/>
                      <b:if cond='data:blog.pageType == &quot;index&quot;'>
                        <b:loop values='data:posts' var='post'>
                          <b:include data='post' name='mobile-index-post'/>
                        </b:loop>
                        <b:else/>
                        <b:loop values='data:posts' var='post'>
                          <b:include data='post' name='mobile-post'/>
                        </b:loop>
                      </b:if>
                    </div>
                    <b:include name='mobile-nextprev'/>
                  </b:includable>
                  <b:includable id='mobile-nextprev'>
                    <div class='blog-pager' id='blog-pager'>
                      <b:if cond='data:newerPageUrl'>
                        <div class='mobile-link-button' id='blog-pager-newer-link'>
                          <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>
                            &amp;lsaquo;
                          </a>
                        </div>
                      </b:if>
    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>
                      <div class='mobile-link-button' id='blog-pager-home-link'>
                        <a class='home-link' expr:href='data:blog.homepageUrl'>
                          <data:homeMsg/>
                        </a>
                      </div>
                      <div class='mobile-desktop-link'>
                        <a class='home-link' expr:href='data:desktopLinkUrl'>
                          <data:desktopLinkMsg/>
                        </a>
                      </div>
                    </div>
                    <div class='clear'/>
                  </b:includable>
                  <b:includable id='mobile-post' var='post'>
                    <div class='date-outer'>
                      <b:if cond='data:post.dateHeader'>
                        <h2 class='date-header'>
                          <span>
                            <data:post.dateHeader/>
                          </span>
                        </h2>
                      </b:if>
                      <div class='date-posts'>
                        <div class='post-outer'>
                          <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
                            <b:if cond='data:post.thumbnailUrl'>
                              <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
                            </b:if>
                            <meta expr:content='data:blog.blogId' itemprop='blogId'/>
                            <meta expr:content='data:post.id' itemprop='postId'/>
                            <a expr:name='data:post.id'/>
                            <b:if cond='data:post.title'>
                              <h3 class='post-title entry-title' itemprop='name'>
                                <b:if cond='data:post.link'>
                                  <a expr:href='data:post.link'>
                                    <data:post.title/>
                                  </a>
                                  <b:elseif cond='data:post.url and data:blog.url != data:post.url'/>
                                  <a expr:href='data:post.url'>
                                    <data:post.title/>
                                  </a>
                                  <b:else/>
                                  <data:post.title/>
                                </b:if>
                              </h3>
                            </b:if>
                            <div class='post-header'>
                              <div class='post-header-line-1'/>
                            </div>
                            <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
                              <data:post.body/>
                              <div style='clear: both;'/>
                              <!-- clear for photos floats -->
                            </div>
                            <div class='post-footer'>
                              <div class='post-footer-line post-footer-line-1'>
                                <span class='post-author vcard'>
                                  <b:if cond='data:top.showAuthor'>
                                    <b:if cond='data:post.authorProfileUrl'>
                                      <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                        <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                        <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                          <span itemprop='name'>
                                            <data:post.author/>
                                          </span>
                                        </a>
                                      </span>
                                      <b:else/>
                                      <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                        <span itemprop='name'>
                                          <data:post.author/>
                                        </span>
                                      </span>
                                    </b:if>
                                  </b:if>
                                </span>
                                <span class='post-timestamp'>
                                  <b:if cond='data:top.showTimestamp'>
                                    <data:top.timestampLabel/>
                                    <b:if cond='data:post.url'>
                                      <meta expr:content='data:post.url.canonical' itemprop='url'/>
                                      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                        <abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'>
                                          <data:post.timestamp/>
                                        </abbr>
                                      </a>
                                    </b:if>
                                  </b:if>
                                </span>
                                <span class='post-comment-link'>
                                  <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                                  and data:post.allowComments' data='post' name='comment_count_picker'/>
                                </span>
                              </div>
                              <div class='post-footer-line post-footer-line-2'>
                                <b:if cond='data:top.showMobileShare'>
                                  <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                                    <a href='javascript:void(0);'>
                                      <data:shareMsg/>
                                    </a>
                                  </div>
                                </b:if>
                                <b:if cond='data:top.showDummy'>
                                  <div class='goog-inline-block dummy-container'>
                                    <data:post.dummyTag/>
                                  </div>
                                </b:if>
                              </div>
                            </div>
                          </div>
                          <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
                        </div>
                      </div>
                    </div>
                  </b:includable>
                  <b:includable id='nextprev'>
                    <div class='blog-pager' id='blog-pager'>
                      <b:if cond='data:newerPageUrl'>
                        <span id='blog-pager-newer-link'>
                          <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
                        </span>
                      </b:if>

                      <b:if cond='data:olderPageUrl'>
                        <span id='blog-pager-older-link'>
                          <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
                        </span>
                      </b:if>

                      <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

                      <b:if cond='data:mobileLinkUrl'>
                        <div class='blog-mobile-link'>
                          <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
                        </div>
                      </b:if>
                    </div>
                    <div class='clear'/>
                  </b:includable>
                  <b:includable id='post' var='post'>
                    <div class='post hentry uncustomized-post-template' itemprop='blogPost' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
                      <b:if cond='data:post.firstImageUrl'>
                        <meta expr:content='data:post.firstImageUrl' itemprop='image_url'/>
                      </b:if>
                      <meta expr:content='data:blog.blogId' itemprop='blogId'/>
                      <meta expr:content='data:post.id' itemprop='postId'/>
                      <a expr:name='data:post.id'/>
                      <b:if cond='data:post.title'>
                        <h3 class='post-title entry-title' itemprop='name'>
                          <b:if cond='data:post.link or (data:post.url and data:blog.url != data:post.url)'>
                            <a expr:href='data:post.link ? data:post.link : data:post.url'>
                              <data:post.title/>
                            </a>
                            <b:else/>
                            <data:post.title/>
                          </b:if>
                        </h3>
                      </b:if>
                          <b:if cond='data:blog.pageType == &quot;item&quot;'>

                            <div class='post-film'>
                              <div class='postff-img'>
                                <div class='post-gr-wall-img'>
                                  <b:if cond='data:post.thumbnailUrl'><div class='clear'/><div class='post-gro-home'><div class='postff-home'><div class='postff-hover'><img class='posts-area' expr:alt='data:post.title' expr:src='data:post.firstImageUrl' expr:title='data:post.title'/></div></div></div><b:else/><img class='posts-area' expr:alt='data:post.title' expr:title='data:post.title' src='https://1.bp.blogspot.com/-dM6WQuAvOxU/WdO_W-Zg75I/AAAAAAAABwg/U5auFkOLlwsxZfg6FGyNalpExI_fNy5swCLcBGAs/s1600/noimage.png'/></b:if>
                                </div>
                              </div>
                              <div class='post-by-area'>
                                <ul>
                                  <li><b class='fa fa-bookmark'/><spane>العنوان :</spane><a class='onwan_area' expr:href='data:post.url'><data:post.title/></a><div class='clear'/></li>
                                    <li><b class='fa fa-user'/><spane>الكاتب :</spane><span class='post-author vcard'><b:if cond='data:postrofileUrl'><span class='fn' itemscope='itemscope' itemtype='#'><meta expr:content='data:post.authorProfileUrl' itemprop='url'/><a expr:href='data:post.authorProfileUrl' rel='author' title='بروفيل الكاتب'><span><data:post.author/></span></a></span><b:else/><span class='fn' itemscope='itemscope' itemtype='http://schema.org/Person'><span><data:post.author/></span></span></b:if></span></li>
                                  <li><b class='fa fa-tag'/><span class='post-labels'><b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'/></b:loop></b:if></span></li>
                                  <li>
                                    <div class='all-v' expr:id='&quot;obs-&quot; + data:post.id'><b class='fa fa-eye'/>
                                      <div id='views-container'>
                                        <span class='views-icon'/>
                                        <div class='views-text'>
                                        </div>
                                        <div class='DrROloading viewscount' id='postviews'/>
                                      </div>


                                      <spane>&amp;nbsp;مشاهدة</spane></div>
                                  </li>
                                  <li>
                                    <div class='Reporting-ba-button'><span class='eror-area'><b class='fa fa-exclamation-triangle'/></span>
                                      <a expr:href='&quot;https://mail.google.com/mail/?ui=2&amp;view=cm&amp;fs=1&amp;tf=1&amp;to=exempel@gmail.com&amp;su=&quot; + data:post.title + &quot;&amp;body=رسالة إلى مشرفي مدونة:blogg-code/الرابط المطلوب:&quot; + data:post.url' rel='nofollow' target='_blank' title='التبليغ عن خطأ أو رابط لايعمل أو إرسال ملفات للمشرف'>إبلاغ عن محتوى أو إرسال ملفات</a></div>
                                  </li>
                                  <li>
 <div class='addthis_inline_share_toolbox'>
                                     <summary> شارك الموضوع</summary>

<iframe allowtransparency='true' data-aa='1434250' scrolling='no' src='' style='width:728px; height:90px; border:0px; padding:0; overflow:hidden'/>

<i class=''/></div>
                                  </li>
                                  <li>
                                    <div id='mbt-sub-box'><span class='share'><b class='fa fa-paper-plane'/></span>
                                      <h1>أشترك ليصلك جديد الدروس والمواضيع!</h1><form action='http://feedburner.google.com/fb/a/mailverify' method='post' onsubmit='window.open(&apos;http://feedburner.google.com/fb/a/mailverify?uri=Previewextensions&apos;, &apos;popupwindow&apos;, &apos;scrollbars=yes,width=550,height=520&apos;);return true' rel='nofollow' target='popupwindow'><center><input autocomplete='off' name='email' onblur='if (this.value == &quot;&quot;) {this.value = &quot;أدخل البريد الإلكتروني ...&quot;;}' onfocus='if (this.value == &quot;أدخل البريد الإلكتروني ...&quot;) {this.value = &quot;&quot;}' size='30' type='text' value='أدخل البريد الإلكتروني ...'/>
                                      <input name='uri' type='hidden' value='Previewextensions'/> <input name='loc' type='hidden' value='en_US'/> <input class='submit' type='submit' value='أشترك'/></center></form></div>
                                  </li>
                                </ul>
                              </div>
                            </div>
                          </b:if>
                      <div class='post-header'>
                        <div class='post-header-line-1'/>
                      </div>
                      <!-- Then use the post body as the schema.org description, for good G+/FB snippeting. -->
                      <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' expr:itemprop='(data:blog.metaDescription ? &quot;&quot; : &quot;description &quot;) + &quot;articleBody&quot;'>
                        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                          <b:if cond='data:blog.pageType != &quot;item&quot;'>
                            <div expr:id='&quot;summary&quot; + data:post.id'>
                              <data:post.body/>
                            </div>
                            <script type='text/javascript'>
                              createSummaryAndThumb(&quot;summary<data:post.id/>&quot;,&quot;<data:post.url/>&quot;,&quot;<data:post.title/>&quot;);</script>
                            <span class='readmore' style='float:right;'>
                              <a expr:href='data:post.url'>
                                Read More &#187;
                              </a>
                            </span>
                          </b:if>
                          <b:if cond='data:blog.pageType != &quot;item&quot;'>
                            <style>
                              h2.date-header {
                                display: none;
                              }
                              .post {
                                z-index: 999;
                                position: relative;
                                border-radius: 4px;
                                display: inline-block;
                                text-decoration: none;
                                float: right;
                                margin: 0 1.1% 1% 0;
                                padding: 0!important;
                                overflow: hidden;
                                border-bottom: 5px solid RGB(222, 222, 222);
                                width: 290px;
                                height: 416px;
                                box-shadow: 0px 4px 10px 1px rgba(0,0,0,0.55);
                                margin: 5px;
                                direction: rtl;
                                text-align: center;
                                border: 5px solid #dddddd;
                                border-radius: 3px;
                                background-color: #d1d2d2;
                              }

                              .posts-thumb {
                                width: 100%!important;
                                overflow: hidden;
                                clear: both;
                                margin-top: 0px;
                              }
                              .post:hover img {
                                transform: rotate(10deg) scale(1.4);
                              }
                              .post img {
                                transition: .5s ease;
                              }
                              .post-body img {
                                z-index: 10;
                                display: block;
                                width: 100% !important;
                                height: 406px !important;
                                border: none;
                                outline: none;
                                position: relative;
                                margin: 0px;
                                padding: 0;
                              }

                              .post:hover h3.post-title.entry-title {

                              }
                              .post h3.post-title.entry-title {
                                text-shadow: 0 1px 10px #0C0C0C;
                                height: auto;
                                bottom: 0;
                                text-align: center;
                                width: 100%;
                                padding: 5px;
                                z-index: 9999;
                                right: 0px;
                                position: absolute !important;
                                margin-bottom: 0px;
                                background: linear-gradient(to top,rgba(0,0,0,1),rgba(0,0,0,.8),rgba(0,0,0,.6),rgba(0,0,0,.4),rgba(0,0,0,.1));
                                transition: .1s all ease;
                                -webkit-animation: rotateOutDownRight 1s both ease;
                                animation: rotateOutDownRight 1s both ease;
                              }
                              .post h3.post-title.entry-title a {
                                display: block;

                              }
                              a {
                                text-decoration: none;
                                color: #FFFFFF;
                              }
                              .post-summary-text {
                                top: 0;
                                padding-top: 50%;
                                text-align: center;
                                transition: .3s all ease;
                                height: 100%;
                                background: rgba(0,0,0,.75);
                                color: #fff;
                                z-index: 222;
                                display: none;
                                font-size: 14px;
                                font-weight: 400;
                              }
                              .post:hover .post-summary-text {

                                position: absolute;
                                display: block;
                              }

                              .post:hover .all-v:after{transform: rotate(-180deg);}
                              .post:hover .post-footer-line.post-footer-line-2 {
                                top: 40px;
                                -webkit-animation-duration: 0.2s;
                                animation-duration: 0.2s;
                                -webkit-animation-fill-mode: both;
                                animation-fill-mode: both;
                                -webkit-animation-name: zoomInDown;
                                animation-name: zoomInDown;
                                -webkit-transition: all 0.2s ease-in-out;
                                -moz-transition: all 0.2s ease-in-out;
                                -o-transition: all 0.2s ease-in-out;
                                -ms-transition: all 0.2s ease-in-out;
                                transition: all 0.2s ease-in-out;
                                z-index: 99999999;
                              }
                              .post-footer-line.post-footer-line-2 {
                                width: 100%;
                                position: absolute;
                                padding: 10px 10px;
                                font-size: 13px;
                                line-height: 30px;
                                font-family: &#39;DroidKufi Bold&#39; , Tahoma;
                                font-weight: bold;
                                min-height: 50px;
                                color: #FDF8F8;
                                text-align: center;
                                -webkit-animation-duration: 0.2s;
                                animation-duration: 0.2s;
                                -webkit-animation-fill-mode: both;
                                animation-fill-mode: both;
                                -webkit-transition: all 0.2s ease-in-out;
                                -moz-transition: all 0.2s ease-in-out;
                                -o-transition: all 0.2s ease-in-out;
                                -ms-transition: all 0.2s ease-in-out;
                                transition: all 0.2s ease-in-out;

                              }
                              .post:hover span.post-labels {
                                transform: translate(0);
                              }
                              span.post-labels {
                                position: absolute;
                                transition: .3s all ease;
                                left: 10px;
                                transform: translate(-200px,0px);
                              }
                              span.post-labels a {
                                background: #0087db;
                                margin-bottom: 5px;
                                border-radius: 5px;
                                padding: 2px 6px;
                                font-weight: 700;
                                box-shadow: 0 1px 2px rgba(0,0,0,0.58);
                              }

                              .post-footer-line-1{display:none;}
                              .post-labels a {
                                font-family: &#39;DroidKufi Bold&#39;;
                                color: white;
                                font-size: 15px;
                                font-weight: bold;
                                text-decoration: none;
                              }
                              .all-v , .post-footer-line.post-footer-line-2 {
                                -webkit-transition : all 0.3s ease-in-out;
                                -moz-transition: all 0.3s ease-in-out;
                                -o-transition: all 0.3s ease-in-out;
                                -ms-transition: all 0.3s ease-in-out;
                                transition: all 0.3s ease-in-out;
                              }

                              .post-footer {
                                height: 23px;
                                bottom: 6px;
                              }
                              span.post-labels{
                                color:#fff;
                              }
                              span.post-labels a:first-child {
                                display: inline-block;
                              }
                              span.post-labels a:nth-child(2){
                                display: inline-block;
                              }
                              span.post-labels a:nth-child(3){
                                display: inline-block;
                              }
                              span.post-labels a {
                                display: none;
                              }
                              .post:hover:after {
                                content: &quot;&quot;;
                                top: 0;
                                right: 0;
                                left: 0;
                                bottom: 0;
                                z-index: 6000;
                              }
                              .all-v {

                                top: 0px;
                                border-radius: 5px;
                                box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.58);
                                z-index: 44444;
                                display: none;
                                background-color: rgba(0, 0, 0, 0.72);
                                width: 100%;
                                margin: 0 auto;
                                text-align: left;
                                position: absolute;
                                font-size: 1.7em;
                                line-height: 1.7em;
                                height: 41px;
                              }


                              @-moz-document url-prefix() {
                                .all-v{
                                  background-color: rgba(0, 0, 0, 0.72);
                                  width: 97%;
                                  z-index: 20;
                                  margin: -44 auto;
                                  text-align: left;
                                  margin-bottom: 0;
                                  position: relative;
                                }
                              }
                              h3.post-title:hover &gt; .all-v:after{
                                width: 50px;
                              }
                              .post:hover .all-v {
                                display: block;
                              }
                              i.fa.fa-eye {
                                margin-left: 10px;
                                font-size: 30px;
                              }
                              div#views-container {
                                float: right;
                                width: 80%;
                                font-size: 20px;
                              }

                              .post-body {
                                border-radius: 2px;
                                overflow: hidden;
                                margin-top: 0px;
                                width: 100%;
                                margin-right: auto;
                                margin-left: auto;
                              }
                            </style>
                          </b:if>
                        </b:if>
                        <b:if cond='data:blog.pageType == &quot;item&quot;'>
                          <data:post.body/>
                        </b:if>
                        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>

                          <data:post.body/>
                        </b:if>
                        <div style='clear: both;'/>
                        <!-- clear for photos floats -->
                      </div>
                      <b:if cond='data:post.hasJumpLink'>
                        <div class='jump-link'>
                          <a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'>
                            <data:post.jumpText/>
                          </a>
                        </div>
                      </b:if>
                      <b:if cond='data:blog.pageType != &quot;item&quot;'>

                        <div class='all-v'>
                          <div id='views-container'>
                            <span class='views-icon'/>
                            <div class='views-text'>
                            </div>
                            <div class='DrROloading viewscount' id='postviews'/>
                          </div>
                          <i class='fa fa-eye'>
                          </i>
                        </div>
                        <div class='post-footer'>
                          <div class='post-footer-line post-footer-line-1'>
                            <span class='post-author vcard'>
                              <b:if cond='data:top.showAuthor'>
                                <data:top.authorLabel/>
                                <b:if cond='data:post.authorProfileUrl'>
                                  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                    <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                    <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                      <span itemprop='name'>
                                        <data:post.author/>
                                      </span>
                                    </a>
                                  </span>
                                  <b:else/>
                                  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                    <span itemprop='name'>
                                      <data:post.author/>
                                    </span>
                                  </span>
                                </b:if>
                              </b:if>
                            </span>
                            <span class='post-timestamp'>
                              <b:if cond='data:top.showTimestamp'>
                                <data:top.timestampLabel/>
                                <b:if cond='data:post.url'>
                                  <meta expr:content='data:post.url.canonical' itemprop='url'/>
                                  <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                    <abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'>
                                      <data:post.timestamp/>
                                    </abbr>
                                  </a>
                                </b:if>
                              </b:if>
                            </span>
                            <span class='reaction-buttons'>
                              <b:if cond='data:top.showReactions'>
                                <table border='0' cellpadding='0' cellspacing='0' width='100%'>
                                  <tr>
                                    <td class='reactions-label-cell' nowrap='nowrap' valign='top' width='1%'>
                                      <span class='reactions-label'>
                                        <data:top.reactionsLabel/>
                                      </span>
                                      &#160;
                                    </td>
                                    <td>
                                      <iframe allowtransparency='true' class='reactions-iframe' expr:src='data:post.reactionsUrl' frameborder='0' name='reactions' scrolling='no'/>
                                    </td>
                                  </tr>
                                </table>
                              </b:if>
                            </span>
                            <span class='post-comment-link'>
                              <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                          and data:post.allowComments' data='post' name='comment_count_picker'/>
                            </span>
                            <!-- backlinks -->
                            <span class='post-backlinks post-comment-link'>
                              <b:if cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                      and data:post.showBacklinks'>
                                <a class='comment-link' expr:href='data:post.url + &quot;#links&quot;'>
                                  <data:top.backlinkLabel/>
                                </a>
                              </b:if>
                            </span>
                            <span class='post-icons'>
                              <!-- email post links -->
                              <b:if cond='data:post.emailPostUrl'>
                                <span class='item-action'>
                                  <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
                                    <img alt='' class='icon-action' height='13' src='https://resources.blogblog.com/img/icon18_email.gif' width='18'/>
                                  </a>
                                </span>
                              </b:if>
                              <!-- quickedit pencil -->
                              <b:include data='post' name='postQuickEdit'/>
                            </span>
                            <!-- share buttons -->
                            <div class='post-share-buttons goog-inline-block'>
                              <b:include cond='data:post.sharePostUrl' data='post' name='shareButtons'/>
                            </div>
                          </div>
                          <div class='post-footer-line post-footer-line-2'>
                            <span class='post-labels'>
                              <b:if cond='data:top.showPostLabels and data:post.labels'>
                                <data:postLabelsLabel/>
                                <b:loop values='data:post.labels' var='label'>
                                  <a expr:href='data:label.url' rel='tag'>
                                    <data:label.name/>
                                  </a>
                                  <b:if cond='not data:label.isLast'>
                                  </b:if>
                                </b:loop>
                              </b:if>
                            </span>
                          </div>
                          <div class='post-footer-line post-footer-line-3'>
                            <span class='post-location'>
                              <b:if cond='data:top.showLocation and data:post.location'>
                                <data:postLocationLabel/>
                                <a expr:href='data:post.location.mapsUrl' target='_blank'>
                                  <data:post.location.name/>
                                </a>
                              </b:if>
                            </span>
                          </div>
                          <b:if cond='data:post.authorAboutMe'>
                            <div class='author-profile' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                              <b:if cond='data:post.authorPhoto.url'>
                                <img expr:src='data:post.authorPhoto.url' itemprop='image' width='50px'/>
                              </b:if>
                              <div>
                                <a class='g-profile' expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' title='author profile'>
                                  <span itemprop='name'>
                                    <data:post.author/>
                                  </span>
                                </a>
                              </div>
                              <span itemprop='description'>
                                <data:post.authorAboutMe/>
                              </span>
                            </div>
                          </b:if>
                        </div>
                      </b:if>
                      <b:if cond='data:blog.pageType == &quot;item&quot;'>
                        <div id='related-pre'>
                          <b:loop values='data:post.labels' var='label'>
                            <b:if cond='data:label.isLast != &quot;true&quot;'>
                            </b:if>
                            <script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels_thumbs&amp;max-results=8&quot;' type='text/javascript'/>
                          </b:loop>
<!-- Composite Start -->
<div id='M606140ScriptRootC953718'>
</div>
<script async='async' src='https://jsc.adskeeper.co.uk/c/i/aflami4uu.blogspot.com/.953718.js'>
</script>
<!-- Composite End -->

                          <script type='text/javascript'>
                            var currentposturl=&quot;<data:post.url/>&quot;;
                            var maxresults=8;
                            var relatedpoststitle=&quot;ذات صلة &quot;;
                            removeRelatedDuplicates_thumbs();
                            printRelatedLabels_thumbs();
                          </script>
                        </div>
                      </b:if>
                    </div>
                  </b:includable>
                  <b:includable id='postQuickEdit' var='post'>
                    <b:if cond='data:post.editUrl'>
                      <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
                        <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
                          <img alt='' class='icon-action' height='18' src='https://resources.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
                        </a>
                      </span>
                    </b:if>
                  </b:includable>
                  <b:includable id='shareButtons' var='post'>
                    <b:if cond='data:top.showEmailButton'>
                      <a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'>
                        <span class='share-button-link-text'>
                          <data:top.emailThisMsg/>
                        </span>
                      </a>
                    </b:if>
                    <b:if cond='data:top.showBlogThisButton'>
                      <a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'>
                        <span class='share-button-link-text'>
                          <data:top.blogThisMsg/>
                        </span>
                      </a>
                    </b:if>
                    <b:if cond='data:top.showFacebookButton'>
                      <a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'>
                        <span class='share-button-link-text'>
                          <data:top.shareToFacebookMsg/>
                        </span>
                      </a>
                    </b:if>
                    <b:if cond='data:top.showPinterestButton'>
                      <a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'>
                        <span class='share-button-link-text'>
                          <data:top.shareToPinterestMsg/>
                        </span>
                      </a>
                    </b:if>
                    <b:if cond='data:top.showPlusOne'>
                      <div class='goog-inline-block google-plus-share-container'>
                        <data:post.googlePlusShareTag/>
                      </div>
                    </b:if>
                  </b:includable>
                  <b:includable id='status-message'>
                    <b:if cond='data:navMessage'>
                      <div class='status-msg-wrap'>
                        <div class='status-msg-body'>
                          <data:navMessage/>
                        </div>
                        <div class='status-msg-border'>
                          <div class='status-msg-bg'>
                            <div class='status-msg-hidden'>
                              <data:navMessage/>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div style='clear: both;'/>
                    </b:if>
                  </b:includable>
                  <b:includable id='threaded-comment-form' var='post'>
                    <div class='comment-form'>
                      <a name='comment-form'/>
                      <b:if cond='data:mobile'>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                        <data:blogTeamBlogMessage/>
                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                        <b:else/>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                        <data:blogTeamBlogMessage/>
                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
                      </b:if>
                      <data:post.friendConnectJs/>
                      <data:post.cmtfpIframe/>
                      <script type='text/javascript'>
                        BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
                      </script>
                    </div>
                  </b:includable>
                  <b:includable id='threaded_comment_js' var='post'>
                    <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
                    <script type='text/javascript'>
                      (function() {
                        var items = <data:post.commentJso/>;
                        var msgs = <data:post.commentMsgs/>;
                        var config = <data:post.commentConfig/>;
                        // <![CDATA[
                        var cursor = null;
                        if (items && items.length > 0) {
                          cursor = parseInt(items[items.length - 1].timestamp) + 1;
                        }
                        var bodyFromEntry = function(entry) {
                          if (entry.gd$extendedProperty) {
                            for (var k in entry.gd$extendedProperty) {
                              if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
                                return '<span class="deleted-comment">' + entry.content.$t + '</span>';
                              }
                            }
                          }
                          return entry.content.$t;
                        }
                        var parse = function(data) {
                          cursor = null;
                          var comments = [];
                          if (data && data.feed && data.feed.entry) {
                            for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
                              var comment = {};
                              // comment ID, parsed out of the original id format
                              var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
                              comment.id = id ? id[2] : null;
                              comment.body = bodyFromEntry(entry);
                              comment.timestamp = Date.parse(entry.published.$t) + '';
                              if (entry.author && entry.author.constructor === Array) {
                                var auth = entry.author[0];
                                if (auth) {
                                  comment.author = {
                                    name: (auth.name ? auth.name.$t : undefined),
                                    profileUrl: (auth.uri ? auth.uri.$t : undefined),
                                    avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                                  };
                                }
                              }
                              if (entry.link) {
                                if (entry.link[2]) {
                                  comment.link = comment.permalink = entry.link[2].href;
                                }
                                if (entry.link[3]) {
                                  var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                                  if (pid && pid[1]) {
                                    comment.parentId = pid[1];
                                  }
                                }
                              }
                              comment.deleteclass = 'item-control blog-admin';
                              if (entry.gd$extendedProperty) {
                                for (var k in entry.gd$extendedProperty) {
                                  if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                                    comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                                  } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                                    comment.displayTime = entry.gd$extendedProperty[k].value;
                                  }
                                }
                              }
                              comments.push(comment);
                            }
                          }
                          return comments;
                        };
                        var paginator = function(callback) {
                          if (hasMore()) {
                            var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
                            if (cursor) {
                              url += '&published-min=' + new Date(cursor).toISOString();
                            }
                            window.bloggercomments = function(data) {
                              var parsed = parse(data);
                              cursor = parsed.length < 50 ? null
                              : parseInt(parsed[parsed.length - 1].timestamp) + 1
                              callback(parsed);
                              window.bloggercomments = null;
                            }
                            url += '&callback=bloggercomments';
                            var script = document.createElement('script');
                            script.type = 'text/javascript';
                            script.src = url;
                            document.getElementsByTagName('head')[0].appendChild(script);
                          }
                        };
                        var hasMore = function() {
                          return !!cursor;
                        };
                        var getMeta = function(key, comment) {
                          if ('iswriter' == key) {
                            var matches = !!comment.author
                            && comment.author.name == config.authorName
                            && comment.author.profileUrl == config.authorUrl;
                            return matches ? 'true' : '';
                          } else if ('deletelink' == key) {
                            return config.baseUri + '/delete-comment.g?blogID='
                            + config.blogId + '&postID=' + comment.id;
                          } else if ('deleteclass' == key) {
                            return comment.deleteclass;
                          }
                          return '';
                        };
                        var replybox = null;
                        var replyUrlParts = null;
                        var replyParent = undefined;
                        var onReply = function(commentId, domId) {
                          if (replybox == null) {
                            // lazily cache replybox, and adjust to suit this style:
                            replybox = document.getElementById('comment-editor');
                            if (replybox != null) {
                              replybox.height = '250px';
                              replybox.style.display = 'block';
                              replyUrlParts = replybox.src.split('#');
                            }
                          }
                          if (replybox && (commentId !== replyParent)) {
                            replybox.src = '';
                            document.getElementById(domId).insertBefore(replybox, null);
                            replybox.src = replyUrlParts[0]
                            + (commentId ? '&parentID=' + commentId : '')
                            + '#' + replyUrlParts[1];
                            replyParent = commentId;
                          }
                        };
                        var hash = (window.location.hash || '#').substring(1);
                        var startThread, targetComment;
                        if (/^comment-form_/.test(hash)) {
                          startThread = hash.substring('comment-form_'.length);
                        } else if (/^c[0-9]+$/.test(hash)) {
                          targetComment = hash.substring(1);
                        }
                        // Configure commenting API:
                        var configJso = {
                          'maxDepth': config.maxThreadDepth
                        };
                        var provider = {
                          'id': config.postId,
                          'data': items,
                          'loadNext': paginator,
                          'hasMore': hasMore,
                          'getMeta': getMeta,
                          'onReply': onReply,
                          'rendered': true,
                          'initComment': targetComment,
                          'initReplyThread': startThread,
                          'config': configJso,
                          'messages': msgs
                        };
                        var render = function() {
                          if (window.goog && window.goog.comments) {
                            var holder = document.getElementById('comment-holder');
                            window.goog.comments.render(holder, provider);
                          }
                        };
                        // render now, or queue to render when library loads:
                        if (window.goog && window.goog.comments) {
                          render();
                        } else {
                          window.goog = window.goog || {};
                          window.goog.comments = window.goog.comments || {};
                          window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
                          window.goog.comments.loadQueue.push(render);
                        }
                      })();
                      // ]]>
                    </script>
                  </b:includable>
                  <b:includable id='threaded_comments' var='post'>
                    <div class='comments' id='comments'>
                      <a name='comments'/>
                      <h4>
                        <data:post.commentLabelFull/>
                        :
                      </h4>
                      <div class='comments-content'>
                        <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
                        <div id='comment-holder'>
                          <data:post.commentHtml/>
                        </div>
                      </div>
                      <p class='comment-footer'>
                        <b:if cond='data:post.allowNewComments'>
                          <b:include data='post' name='threaded-comment-form'/>
                          <b:else/>
                          <data:post.noNewCommentsText/>
                        </b:if>
                      </p>
                      <b:if cond='data:showCmtPopup'>
                        <div id='comment-popup'>
                          <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                          </iframe>
                        </div>
                      </b:if>
                      <div id='backlinks-container'>
                        <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                          <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
                        </div>
                      </div>
                    </div>
                  </b:includable>
                </b:widget>
                <b:widget id='HTML4' locked='false' title='' type='HTML'>
                  <b:widget-settings>
                    <b:widget-setting name='content'><![CDATA[<script>(function(s,u,z,p){s.src=u,s.setAttribute('data-zone',z),p.appendChild(s);})(document.createElement('script'),'https://iclickcdn.com/tag.min.js',3522655,document.body||document.documentElement)</script>]]></b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
                </b:widget>
                <b:widget id='HTML6' locked='false' title='' type='HTML'>
                  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
                </b:widget>
                <b:widget id='HTML5' locked='false' title='' type='HTML'>
                  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
                </b:widget>
              </b:section>
            </ul>
          </div>
        </div>


<div class='footer'>
<div class='sizewrap'>
<div class='right'>
          جميع الحقوق محفوظة ل 
          <a expr:href='data:blog.homepageUrl' expr:title='data:blog.title'>
              <data:blog.title/>
            </a>

  </div>
<div class='left'>
  تصميم موقع : 
  <a href='https://aflami4uu.blogspot.com//' target='_blank'>Samurai</a>

    </div>
  </div>
  </div>


      </div>
      </div>


    <script type='text/javascript'>
      window.setTimeout(function() {     document.body.className = document.body.className.replace(&#39;loading&#39;, &#39;&#39;);       }, 10);   </script>
    <script src='https://cdn.firebase.com/v0/firebase.js' type='text/javascript'/>
    <script>
      $.each($(&#39;a[name]&#39;), function(i, e) { var elem = $(e).parent().find(&#39;#postviews&#39;).addClass(&#39;DrROloading&#39;); var blogStats = new Firebase(&quot;https://elprof.firebaseIO.com/pages/id/&quot; + $(e).attr(&#39;name&#39;)); blogStats.once(&#39;value&#39;, function(snapshot) { var data = snapshot.val(); var isnew = false; if(data == null) { data= {}; data.value = 0; data.url = window.location.href; data.id = $(e).attr(&#39;name&#39;); isnew = true; } elem.removeClass(&#39;DrROloading&#39;).text(data.value); data.value++; if(window.location.pathname!=&#39;/&#39;) { if(isnew) blogStats.set(data); else blogStats.child(&#39;value&#39;).set(data.value); } }); }); </script>

<style>
#shbtn + label span::before {
    content: &quot;\f002&quot;;
    cursor: pointer;
    display: block;
    float: left;
    font: 18px/35px fontawesome;
    position: relative;
    font-size: 18px;
    color: #ffffff;
    border: 3px solid #ffffff;
    width: 50px;
    text-align: center;
    line-height: 46px;
    background: -webkit-linear-gradient(left, rgba(45, 69, 98, 0.65) 0%, #2d4562 100%), -webkit-linear-gradient(left, #4d90fe 0%, #666 100%);
    z-index: 999999999999999;
}
#search-text {
    border: 0 none;
    color: #385a8d;
    text-align: center;
    position: absolute;
    top: 0;
    width: 100%;
    left: 0;
    right: 0;
    height: 100%;
    overflow: hidden;
    display: block;
    opacity: 0;
    filter: alpha(opacity=0);
    visibility: hidden;
    font-size: 24px !important;
    background: #fff;
}
#shbtn:checked + label span::before{content:&quot;\f00d&quot;;background-color:#123}
#shbtn:checked ~ #search-text {visibility: visible;width: 100%;max-width: 100%;opacity: 1; font-size: 15px;
    font-family: inherit;
    filter: alpha(opacity=100);
    visibility: visible;
    font-family: &#39;DroidKufi bold&#39; , Tahoma;
}



  </style>
<style>
#sub-menu li a:after {
    content: &quot;&quot;;
}
.has-sub:after {
    content: &quot;\f107&quot;;
    font-family: FontAwesome;
    display: inline-block;
    margin-right: 6px;
    top: 2px;
    position: relative;
}
 </style>

<b:if cond='data:blog.pageType == &quot;index&quot;'>
<script type='text/javascript'>
/*<![CDATA[*/
var postperpage=8;var numshowpage=4;var upPageWord ='السابق';var downPageWord ='التالي';var urlactivepage=location.href;var home_page="/";
/*]]>*/
</script>
<script src='https://cdn.rawgit.com/mohammedxx/madad2/e5a01ecf/unlipage.js' type='text/javascript'/>
</b:if>

<script>
//<![CDATA[

//SEARCH
$(document).ready(function(){
    $('.searchIcon').on('click', function(event) {
        event.preventDefault();
        $('#searchWrap').addClass('openSearch');
        //$('#searchBar').focus();
		setTimeout(function(){
			$('#searchBar').focus();
		}, 100);
    });
    
    $('#searchWrap, .closeSearch').on('click keyup', function(event) {
        if (event.target == this || event.target.className == 'closeSearch' || event.target.className == 'fa fa-times' || event.keyCode == 27) {
            $(this).removeClass('openSearch');
        }
    });
    
});

//]]>
</script>
<script type='text/javascript'>
    /*<![CDATA[*/
$(".slider-wrapper .widget-content").each(function(){var t=$(this),e=$(this).text();e.match("remove")?$("#HTML222").remove():$.ajax({url:"/feeds/posts/default/-/"+e+"?alt=json-in-script&max-results=8",type:"get",dataType:"jsonp",success:function(e){for(var i="",a="<div class='news-widget'><div class='item'><ul>",r=0;r<e.feed.entry.length;r++){for(var n=0;n<e.feed.entry[r].link.length;n++)if("alternate"==e.feed.entry[r].link[n].rel){i=e.feed.entry[r].link[n].href;break}for(var s=e.feed.entry[r].content.$t,o=$("<div>").html(s),l=o.text().substring(0,100)+"...",d=(o.find("img:first").attr("src"),e.feed.entry[r].title.$t,e.feed.entry[r].category[0].term),u=e.feed.entry[r].author[0].gd$image.src,f=e.feed.entry[r].author[0].uri.$t,m=e.feed.entry[r].author[0].name.$t,c=e.feed.entry[r].published.$t,h=[1,2,3,4,5,6,7,8,9,10,11,12],g=["يناير","فبراير","مارس","أبريل","ماي","يونيو","يوليوز","غشت","شتنبر","أكتوبر","نونبر","دجنبر"],p=c.split("-")[2].substring(0,2),v=c.split("-")[1],y=c.split("-")[0],w=0;w<h.length;w++)if(parseInt(v)==h[w]){v=g[w];break}c=p+" "+v+" "+y,a+='<li><div class="mag-thumb"><a class="imag" href="'+i+'" style="background:url('+(s.indexOf("<img")>-1?o.find("img:first").attr("src").replace("s72-c","s640"):"https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiTAWCak56u7KzN8K5ghZ9yrHkl0eCHxYOqpue2q5Tdo5cPapJSaYrxLee6xAUxlG9BEpaUfqiqKSxII5GKay5Hxxd48PtQCOet9SAAyoWF0beWrCt5Pnw0F-qvQ50pgRioJ9wsNyisieYM/s1600-r/alt.png")+') no-repeat center center;background-size: cover"></a></div><div class="mag-content"><div class="slider-tag"><a href="/search/label/'+d+'">'+d+"</a></div><a href="+f+'><img class="katib" src='+u+'></img></a><h3 class="mag-title"><a href="'+i+'">'+e.feed.entry[r].title.$t+'</a></h3><div class="time-cumen1"><i class="fa fa-clock-o"></i>'+c+'</div><div class="time-cumen2"><i class="fa fa-user-o"></i>'+m+'</div><div class="wasf"><p>'+l+"</p></div></div></li>"}a+="</ul></div></div>",$(t).html(a),$(t).find("ul").owlCarousel({rtl:!0,loop:!0,margin:0,nav:!0,autoplay:!0,navText:["<i class='fa fa-angle-right' aria-hidden='true'></i>","<i class='fa fa-angle-left' aria-hidden='true'></i>"],stopOnHover:!0,responsive:{0:{items:1},580:{items:1},900:{items:3},1200:{items:5}}})}})}),function(t){"function"==typeof define&&define.amd?define(["jquery"],t):t(jQuery)}(function(t){function e(){var e=i(this),s=n.settings;return isNaN(e.datetime)||(0==s.cutoff||Math.abs(r(e.datetime))<s.cutoff)&&t(this).text(a(e.datetime)),this}function i(e){if(!(e=t(e)).data("timeago")){e.data("timeago",{datetime:n.datetime(e)});var i=t.trim(e.text());n.settings.localeTitle?e.attr("title",e.data("timeago").datetime.toLocaleString()):!(i.length>0)||n.isTime(e)&&e.attr("title")||e.attr("title",i)}return e.data("timeago")}function a(t){return n.inWords(r(t))}function r(t){return(new Date).getTime()-t.getTime()}t.timeago=function(e){return a(e instanceof Date?e:"string"==typeof e?t.timeago.parse(e):"number"==typeof e?new Date(e):t.timeago.datetime(e))};var n=t.timeago;t.extend(t.timeago,{settings:{refreshMillis:6e4,allowPast:!0,allowFuture:!1,localeTitle:!1,cutoff:0,strings:{prefixAgo:null,prefixFromNow:null,suffixAgo:"تقريبا",suffixFromNow:"من الآن",inPast:"any moment now",seconds:"منذ أقل من دقيقة",minute:"منذ دقيقة",minutes:"منذ %d دقيقه",hour:"منذ  ساعه",hours:"منذ  %d ساعة",day:"منذ يوم",days:"منذ %d يوم",month:"منذ  شهر",months:"منذ %d أشهر",year:"منذ سنة تقريبا",years:"منذ  %d سنه",wordSeparator:" ",numbers:[]}},inWords:function(e){function i(i,r){var n=t.isFunction(i)?i(r,e):i,s=a.numbers&&a.numbers[r]||r;return n.replace(/%d/i,s)}if(!this.settings.allowPast&&!this.settings.allowFuture)throw"timeago allowPast and allowFuture settings can not both be set to false.";var a=this.settings.strings,r=a.prefixAgo,n=a.suffixAgo;if(this.settings.allowFuture&&e<0&&(r=a.prefixFromNow,n=a.suffixFromNow),!this.settings.allowPast&&e>=0)return this.settings.strings.inPast;var s=Math.abs(e)/1e3,o=s/60,l=o/60,d=l/24,u=d/365,f=s<45&&i(a.seconds,Math.round(s))||s<90&&i(a.minute,1)||o<45&&i(a.minutes,Math.round(o))||o<90&&i(a.hour,1)||l<24&&i(a.hours,Math.round(l))||l<42&&i(a.day,1)||d<30&&i(a.days,Math.round(d))||d<45&&i(a.month,1)||d<365&&i(a.months,Math.round(d/30))||u<1.5&&i(a.year,1)||i(a.years,Math.round(u)),m=a.wordSeparator||"";return void 0===a.wordSeparator&&(m=" "),t.trim([r,f,n].join(m))},parse:function(e){var i=t.trim(e);return i=i.replace(/\.\d+/,""),i=i.replace(/-/,"/").replace(/-/,"/"),i=i.replace(/T/," ").replace(/Z/," UTC"),i=i.replace(/([\+\-]\d\d)\:?(\d\d)/," $1$2"),i=i.replace(/([\+\-]\d\d)$/," $100"),new Date(i)},datetime:function(e){var i=n.isTime(e)?t(e).attr("datetime"):t(e).attr("title");return n.parse(i)},isTime:function(e){return"time"===t(e).get(0).tagName.toLowerCase()}});var s={init:function(){var i=t.proxy(e,this);i();var a=n.settings;a.refreshMillis>0&&(this._timeagoInterval=setInterval(i,a.refreshMillis))},update:function(i){var a=n.parse(i);t(this).data("timeago",{datetime:a}),n.settings.localeTitle&&t(this).attr("title",a.toLocaleString()),e.apply(this)},updateFromDOM:function(){t(this).data("timeago",{datetime:n.parse(n.isTime(this)?t(this).attr("datetime"):t(this).attr("title"))}),e.apply(this)},dispose:function(){this._timeagoInterval&&(window.clearInterval(this._timeagoInterval),this._timeagoInterval=null)}};t.fn.timeago=function(t,e){var i=t?s[t]:s.init;if(!i)throw new Error("Unknown function name '"+t+"' for timeago");return this.each(function(){i.call(this,e)}),this},document.createElement("abbr"),document.createElement("time")});
    /*]]>*/
</script>
<script>
/* <![CDATA[ */

//owl-carousel2
!function(a,b,c,d){function e(b,c){this.settings=null,this.options=a.extend({},e.Defaults,c),this.$element=a(b),this.drag=a.extend({},m),this.state=a.extend({},n),this.e=a.extend({},o),this._plugins={},this._supress={},this._current=null,this._speed=null,this._coordinates=[],this._breakpoint=null,this._width=null,this._items=[],this._clones=[],this._mergers=[],this._invalidated={},this._pipe=[],a.each(e.Plugins,a.proxy(function(a,b){this._plugins[a[0].toLowerCase()+a.slice(1)]=new b(this)},this)),a.each(e.Pipe,a.proxy(function(b,c){this._pipe.push({filter:c.filter,run:a.proxy(c.run,this)})},this)),this.setup(),this.initialize()}function f(a){if(a.touches!==d)return{x:a.touches[0].pageX,y:a.touches[0].pageY};if(a.touches===d){if(a.pageX!==d)return{x:a.pageX,y:a.pageY};if(a.pageX===d)return{x:a.clientX,y:a.clientY}}}function g(a){var b,d,e=c.createElement("div"),f=a;for(b in f)if(d=f[b],"undefined"!=typeof e.style[d])return e=null,[d,b];return[!1]}function h(){return g(["transition","WebkitTransition","MozTransition","OTransition"])[1]}function i(){return g(["transform","WebkitTransform","MozTransform","OTransform","msTransform"])[0]}function j(){return g(["perspective","webkitPerspective","MozPerspective","OPerspective","MsPerspective"])[0]}function k(){return"ontouchstart"in b||!!navigator.msMaxTouchPoints}function l(){return b.navigator.msPointerEnabled}var m,n,o;m={start:0,startX:0,startY:0,current:0,currentX:0,currentY:0,offsetX:0,offsetY:0,distance:null,startTime:0,endTime:0,updatedX:0,targetEl:null},n={isTouch:!1,isScrolling:!1,isSwiping:!1,direction:!1,inMotion:!1},o={_onDragStart:null,_onDragMove:null,_onDragEnd:null,_transitionEnd:null,_resizer:null,_responsiveCall:null,_goToLoop:null,_checkVisibile:null},e.Defaults={items:3,loop:!1,center:!1,mouseDrag:!0,touchDrag:!0,pullDrag:!0,freeDrag:!1,margin:0,stagePadding:0,merge:!1,mergeFit:!0,autoWidth:!1,startPosition:0,rtl:!1,smartSpeed:250,fluidSpeed:!1,dragEndSpeed:!1,responsive:{},responsiveRefreshRate:200,responsiveBaseElement:b,responsiveClass:!1,fallbackEasing:"swing",info:!1,nestedItemSelector:!1,itemElement:"div",stageElement:"div",themeClass:"owl-theme",baseClass:"owl-carousel",itemClass:"owl-item",centerClass:"center",activeClass:"active"},e.Width={Default:"default",Inner:"inner",Outer:"outer"},e.Plugins={},e.Pipe=[{filter:["width","items","settings"],run:function(a){a.current=this._items&&this._items[this.relative(this._current)]}},{filter:["items","settings"],run:function(){var a=this._clones,b=this.$stage.children(".cloned");(b.length!==a.length||!this.settings.loop&&a.length>0)&&(this.$stage.children(".cloned").remove(),this._clones=[])}},{filter:["items","settings"],run:function(){var a,b,c=this._clones,d=this._items,e=this.settings.loop?c.length-Math.max(2*this.settings.items,4):0;for(a=0,b=Math.abs(e/2);b>a;a++)e>0?(this.$stage.children().eq(d.length+c.length-1).remove(),c.pop(),this.$stage.children().eq(0).remove(),c.pop()):(c.push(c.length/2),this.$stage.append(d[c[c.length-1]].clone().addClass("cloned")),c.push(d.length-1-(c.length-1)/2),this.$stage.prepend(d[c[c.length-1]].clone().addClass("cloned")))}},{filter:["width","items","settings"],run:function(){var a,b,c,d=this.settings.rtl?1:-1,e=(this.width()/this.settings.items).toFixed(3),f=0;for(this._coordinates=[],b=0,c=this._clones.length+this._items.length;c>b;b++)a=this._mergers[this.relative(b)],a=this.settings.mergeFit&&Math.min(a,this.settings.items)||a,f+=(this.settings.autoWidth?this._items[this.relative(b)].width()+this.settings.margin:e*a)*d,this._coordinates.push(f)}},{filter:["width","items","settings"],run:function(){var b,c,d=(this.width()/this.settings.items).toFixed(3),e={width:Math.abs(this._coordinates[this._coordinates.length-1])+2*this.settings.stagePadding,"padding-left":this.settings.stagePadding||"","padding-right":this.settings.stagePadding||""};if(this.$stage.css(e),e={width:this.settings.autoWidth?"auto":d-this.settings.margin},e[this.settings.rtl?"margin-left":"margin-right"]=this.settings.margin,!this.settings.autoWidth&&a.grep(this._mergers,function(a){return a>1}).length>0)for(b=0,c=this._coordinates.length;c>b;b++)e.width=Math.abs(this._coordinates[b])-Math.abs(this._coordinates[b-1]||0)-this.settings.margin,this.$stage.children().eq(b).css(e);else this.$stage.children().css(e)}},{filter:["width","items","settings"],run:function(a){a.current&&this.reset(this.$stage.children().index(a.current))}},{filter:["position"],run:function(){this.animate(this.coordinates(this._current))}},{filter:["width","position","items","settings"],run:function(){var a,b,c,d,e=this.settings.rtl?1:-1,f=2*this.settings.stagePadding,g=this.coordinates(this.current())+f,h=g+this.width()*e,i=[];for(c=0,d=this._coordinates.length;d>c;c++)a=this._coordinates[c-1]||0,b=Math.abs(this._coordinates[c])+f*e,(this.op(a,"<=",g)&&this.op(a,">",h)||this.op(b,"<",g)&&this.op(b,">",h))&&i.push(c);this.$stage.children("."+this.settings.activeClass).removeClass(this.settings.activeClass),this.$stage.children(":eq("+i.join("), :eq(")+")").addClass(this.settings.activeClass),this.settings.center&&(this.$stage.children("."+this.settings.centerClass).removeClass(this.settings.centerClass),this.$stage.children().eq(this.current()).addClass(this.settings.centerClass))}}],e.prototype.initialize=function(){if(this.trigger("initialize"),this.$element.addClass(this.settings.baseClass).addClass(this.settings.themeClass).toggleClass("owl-rtl",this.settings.rtl),this.browserSupport(),this.settings.autoWidth&&this.state.imagesLoaded!==!0){var b,c,e;if(b=this.$element.find("img"),c=this.settings.nestedItemSelector?"."+this.settings.nestedItemSelector:d,e=this.$element.children(c).width(),b.length&&0>=e)return this.preloadAutoWidthImages(b),!1}this.$element.addClass("owl-loading"),this.$stage=a("<"+this.settings.stageElement+' class="owl-stage"/>').wrap('<div class="owl-stage-outer">'),this.$element.append(this.$stage.parent()),this.replace(this.$element.children().not(this.$stage.parent())),this._width=this.$element.width(),this.refresh(),this.$element.removeClass("owl-loading").addClass("owl-loaded"),this.eventsCall(),this.internalEvents(),this.addTriggerableEvents(),this.trigger("initialized")},e.prototype.setup=function(){var b=this.viewport(),c=this.options.responsive,d=-1,e=null;c?(a.each(c,function(a){b>=a&&a>d&&(d=Number(a))}),e=a.extend({},this.options,c[d]),delete e.responsive,e.responsiveClass&&this.$element.attr("class",function(a,b){return b.replace(/\b owl-responsive-\S+/g,"")}).addClass("owl-responsive-"+d)):e=a.extend({},this.options),(null===this.settings||this._breakpoint!==d)&&(this.trigger("change",{property:{name:"settings",value:e}}),this._breakpoint=d,this.settings=e,this.invalidate("settings"),this.trigger("changed",{property:{name:"settings",value:this.settings}}))},e.prototype.optionsLogic=function(){this.$element.toggleClass("owl-center",this.settings.center),this.settings.loop&&this._items.length<this.settings.items&&(this.settings.loop=!1),this.settings.autoWidth&&(this.settings.stagePadding=!1,this.settings.merge=!1)},e.prototype.prepare=function(b){var c=this.trigger("prepare",{content:b});return c.data||(c.data=a("<"+this.settings.itemElement+"/>").addClass(this.settings.itemClass).append(b)),this.trigger("prepared",{content:c.data}),c.data},e.prototype.update=function(){for(var b=0,c=this._pipe.length,d=a.proxy(function(a){return this[a]},this._invalidated),e={};c>b;)(this._invalidated.all||a.grep(this._pipe[b].filter,d).length>0)&&this._pipe[b].run(e),b++;this._invalidated={}},e.prototype.width=function(a){switch(a=a||e.Width.Default){case e.Width.Inner:case e.Width.Outer:return this._width;default:return this._width-2*this.settings.stagePadding+this.settings.margin}},e.prototype.refresh=function(){if(0===this._items.length)return!1;(new Date).getTime();this.trigger("refresh"),this.setup(),this.optionsLogic(),this.$stage.addClass("owl-refresh"),this.update(),this.$stage.removeClass("owl-refresh"),this.state.orientation=b.orientation,this.watchVisibility(),this.trigger("refreshed")},e.prototype.eventsCall=function(){this.e._onDragStart=a.proxy(function(a){this.onDragStart(a)},this),this.e._onDragMove=a.proxy(function(a){this.onDragMove(a)},this),this.e._onDragEnd=a.proxy(function(a){this.onDragEnd(a)},this),this.e._onResize=a.proxy(function(a){this.onResize(a)},this),this.e._transitionEnd=a.proxy(function(a){this.transitionEnd(a)},this),this.e._preventClick=a.proxy(function(a){this.preventClick(a)},this)},e.prototype.onThrottledResize=function(){b.clearTimeout(this.resizeTimer),this.resizeTimer=b.setTimeout(this.e._onResize,this.settings.responsiveRefreshRate)},e.prototype.onResize=function(){return this._items.length?this._width===this.$element.width()?!1:this.trigger("resize").isDefaultPrevented()?!1:(this._width=this.$element.width(),this.invalidate("width"),this.refresh(),void this.trigger("resized")):!1},e.prototype.eventsRouter=function(a){var b=a.type;"mousedown"===b||"touchstart"===b?this.onDragStart(a):"mousemove"===b||"touchmove"===b?this.onDragMove(a):"mouseup"===b||"touchend"===b?this.onDragEnd(a):"touchcancel"===b&&this.onDragEnd(a)},e.prototype.internalEvents=function(){var c=(k(),l());this.settings.mouseDrag?(this.$stage.on("mousedown",a.proxy(function(a){this.eventsRouter(a)},this)),this.$stage.on("dragstart",function(){return!1}),this.$stage.get(0).onselectstart=function(){return!1}):this.$element.addClass("owl-text-select-on"),this.settings.touchDrag&&!c&&this.$stage.on("touchstart touchcancel",a.proxy(function(a){this.eventsRouter(a)},this)),this.transitionEndVendor&&this.on(this.$stage.get(0),this.transitionEndVendor,this.e._transitionEnd,!1),this.settings.responsive!==!1&&this.on(b,"resize",a.proxy(this.onThrottledResize,this))},e.prototype.onDragStart=function(d){var e,g,h,i;if(e=d.originalEvent||d||b.event,3===e.which||this.state.isTouch)return!1;if("mousedown"===e.type&&this.$stage.addClass("owl-grab"),this.trigger("drag"),this.drag.startTime=(new Date).getTime(),this.speed(0),this.state.isTouch=!0,this.state.isScrolling=!1,this.state.isSwiping=!1,this.drag.distance=0,g=f(e).x,h=f(e).y,this.drag.offsetX=this.$stage.position().left,this.drag.offsetY=this.$stage.position().top,this.settings.rtl&&(this.drag.offsetX=this.$stage.position().left+this.$stage.width()-this.width()+this.settings.margin),this.state.inMotion&&this.support3d)i=this.getTransformProperty(),this.drag.offsetX=i,this.animate(i),this.state.inMotion=!0;else if(this.state.inMotion&&!this.support3d)return this.state.inMotion=!1,!1;this.drag.startX=g-this.drag.offsetX,this.drag.startY=h-this.drag.offsetY,this.drag.start=g-this.drag.startX,this.drag.targetEl=e.target||e.srcElement,this.drag.updatedX=this.drag.start,("IMG"===this.drag.targetEl.tagName||"A"===this.drag.targetEl.tagName)&&(this.drag.targetEl.draggable=!1),a(c).on("mousemove.owl.dragEvents mouseup.owl.dragEvents touchmove.owl.dragEvents touchend.owl.dragEvents",a.proxy(function(a){this.eventsRouter(a)},this))},e.prototype.onDragMove=function(a){var c,e,g,h,i,j;this.state.isTouch&&(this.state.isScrolling||(c=a.originalEvent||a||b.event,e=f(c).x,g=f(c).y,this.drag.currentX=e-this.drag.startX,this.drag.currentY=g-this.drag.startY,this.drag.distance=this.drag.currentX-this.drag.offsetX,this.drag.distance<0?this.state.direction=this.settings.rtl?"right":"left":this.drag.distance>0&&(this.state.direction=this.settings.rtl?"left":"right"),this.settings.loop?this.op(this.drag.currentX,">",this.coordinates(this.minimum()))&&"right"===this.state.direction?this.drag.currentX-=(this.settings.center&&this.coordinates(0))-this.coordinates(this._items.length):this.op(this.drag.currentX,"<",this.coordinates(this.maximum()))&&"left"===this.state.direction&&(this.drag.currentX+=(this.settings.center&&this.coordinates(0))-this.coordinates(this._items.length)):(h=this.coordinates(this.settings.rtl?this.maximum():this.minimum()),i=this.coordinates(this.settings.rtl?this.minimum():this.maximum()),j=this.settings.pullDrag?this.drag.distance/5:0,this.drag.currentX=Math.max(Math.min(this.drag.currentX,h+j),i+j)),(this.drag.distance>8||this.drag.distance<-8)&&(c.preventDefault!==d?c.preventDefault():c.returnValue=!1,this.state.isSwiping=!0),this.drag.updatedX=this.drag.currentX,(this.drag.currentY>16||this.drag.currentY<-16)&&this.state.isSwiping===!1&&(this.state.isScrolling=!0,this.drag.updatedX=this.drag.start),this.animate(this.drag.updatedX)))},e.prototype.onDragEnd=function(b){var d,e,f;if(this.state.isTouch){if("mouseup"===b.type&&this.$stage.removeClass("owl-grab"),this.trigger("dragged"),this.drag.targetEl.removeAttribute("draggable"),this.state.isTouch=!1,this.state.isScrolling=!1,this.state.isSwiping=!1,0===this.drag.distance&&this.state.inMotion!==!0)return this.state.inMotion=!1,!1;this.drag.endTime=(new Date).getTime(),d=this.drag.endTime-this.drag.startTime,e=Math.abs(this.drag.distance),(e>3||d>300)&&this.removeClick(this.drag.targetEl),f=this.closest(this.drag.updatedX),this.speed(this.settings.dragEndSpeed||this.settings.smartSpeed),this.current(f),this.invalidate("position"),this.update(),this.settings.pullDrag||this.drag.updatedX!==this.coordinates(f)||this.transitionEnd(),this.drag.distance=0,a(c).off(".owl.dragEvents")}},e.prototype.removeClick=function(c){this.drag.targetEl=c,a(c).on("click.preventClick",this.e._preventClick),b.setTimeout(function(){a(c).off("click.preventClick")},300)},e.prototype.preventClick=function(b){b.preventDefault?b.preventDefault():b.returnValue=!1,b.stopPropagation&&b.stopPropagation(),a(b.target).off("click.preventClick")},e.prototype.getTransformProperty=function(){var a,c;return a=b.getComputedStyle(this.$stage.get(0),null).getPropertyValue(this.vendorName+"transform"),a=a.replace(/matrix(3d)?\(|\)/g,"").split(","),c=16===a.length,c!==!0?a[4]:a[12]},e.prototype.closest=function(b){var c=-1,d=30,e=this.width(),f=this.coordinates();return this.settings.freeDrag||a.each(f,a.proxy(function(a,g){return b>g-d&&g+d>b?c=a:this.op(b,"<",g)&&this.op(b,">",f[a+1]||g-e)&&(c="left"===this.state.direction?a+1:a),-1===c},this)),this.settings.loop||(this.op(b,">",f[this.minimum()])?c=b=this.minimum():this.op(b,"<",f[this.maximum()])&&(c=b=this.maximum())),c},e.prototype.animate=function(b){this.trigger("translate"),this.state.inMotion=this.speed()>0,this.support3d?this.$stage.css({transform:"translate3d("+b+"px,0px, 0px)",transition:this.speed()/1e3+"s"}):this.state.isTouch?this.$stage.css({left:b+"px"}):this.$stage.animate({left:b},this.speed()/1e3,this.settings.fallbackEasing,a.proxy(function(){this.state.inMotion&&this.transitionEnd()},this))},e.prototype.current=function(a){if(a===d)return this._current;if(0===this._items.length)return d;if(a=this.normalize(a),this._current!==a){var b=this.trigger("change",{property:{name:"position",value:a}});b.data!==d&&(a=this.normalize(b.data)),this._current=a,this.invalidate("position"),this.trigger("changed",{property:{name:"position",value:this._current}})}return this._current},e.prototype.invalidate=function(a){this._invalidated[a]=!0},e.prototype.reset=function(a){a=this.normalize(a),a!==d&&(this._speed=0,this._current=a,this.suppress(["translate","translated"]),this.animate(this.coordinates(a)),this.release(["translate","translated"]))},e.prototype.normalize=function(b,c){var e=c?this._items.length:this._items.length+this._clones.length;return!a.isNumeric(b)||1>e?d:b=this._clones.length?(b%e+e)%e:Math.max(this.minimum(c),Math.min(this.maximum(c),b))},e.prototype.relative=function(a){return a=this.normalize(a),a-=this._clones.length/2,this.normalize(a,!0)},e.prototype.maximum=function(a){var b,c,d,e=0,f=this.settings;if(a)return this._items.length-1;if(!f.loop&&f.center)b=this._items.length-1;else if(f.loop||f.center)if(f.loop||f.center)b=this._items.length+f.items;else{if(!f.autoWidth&&!f.merge)throw"Can not detect maximum absolute position.";for(revert=f.rtl?1:-1,c=this.$stage.width()-this.$element.width();(d=this.coordinates(e))&&!(d*revert>=c);)b=++e}else b=this._items.length-f.items;return b},e.prototype.minimum=function(a){return a?0:this._clones.length/2},e.prototype.items=function(a){return a===d?this._items.slice():(a=this.normalize(a,!0),this._items[a])},e.prototype.mergers=function(a){return a===d?this._mergers.slice():(a=this.normalize(a,!0),this._mergers[a])},e.prototype.clones=function(b){var c=this._clones.length/2,e=c+this._items.length,f=function(a){return a%2===0?e+a/2:c-(a+1)/2};return b===d?a.map(this._clones,function(a,b){return f(b)}):a.map(this._clones,function(a,c){return a===b?f(c):null})},e.prototype.speed=function(a){return a!==d&&(this._speed=a),this._speed},e.prototype.coordinates=function(b){var c=null;return b===d?a.map(this._coordinates,a.proxy(function(a,b){return this.coordinates(b)},this)):(this.settings.center?(c=this._coordinates[b],c+=(this.width()-c+(this._coordinates[b-1]||0))/2*(this.settings.rtl?-1:1)):c=this._coordinates[b-1]||0,c)},e.prototype.duration=function(a,b,c){return Math.min(Math.max(Math.abs(b-a),1),6)*Math.abs(c||this.settings.smartSpeed)},e.prototype.to=function(c,d){if(this.settings.loop){var e=c-this.relative(this.current()),f=this.current(),g=this.current(),h=this.current()+e,i=0>g-h?!0:!1,j=this._clones.length+this._items.length;h<this.settings.items&&i===!1?(f=g+this._items.length,this.reset(f)):h>=j-this.settings.items&&i===!0&&(f=g-this._items.length,this.reset(f)),b.clearTimeout(this.e._goToLoop),this.e._goToLoop=b.setTimeout(a.proxy(function(){this.speed(this.duration(this.current(),f+e,d)),this.current(f+e),this.update()},this),30)}else this.speed(this.duration(this.current(),c,d)),this.current(c),this.update()},e.prototype.next=function(a){a=a||!1,this.to(this.relative(this.current())+1,a)},e.prototype.prev=function(a){a=a||!1,this.to(this.relative(this.current())-1,a)},e.prototype.transitionEnd=function(a){return a!==d&&(a.stopPropagation(),(a.target||a.srcElement||a.originalTarget)!==this.$stage.get(0))?!1:(this.state.inMotion=!1,void this.trigger("translated"))},e.prototype.viewport=function(){var d;if(this.options.responsiveBaseElement!==b)d=a(this.options.responsiveBaseElement).width();else if(b.innerWidth)d=b.innerWidth;else{if(!c.documentElement||!c.documentElement.clientWidth)throw"Can not detect viewport width.";d=c.documentElement.clientWidth}return d},e.prototype.replace=function(b){this.$stage.empty(),this._items=[],b&&(b=b instanceof jQuery?b:a(b)),this.settings.nestedItemSelector&&(b=b.find("."+this.settings.nestedItemSelector)),b.filter(function(){return 1===this.nodeType}).each(a.proxy(function(a,b){b=this.prepare(b),this.$stage.append(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)},this)),this.reset(a.isNumeric(this.settings.startPosition)?this.settings.startPosition:0),this.invalidate("items")},e.prototype.add=function(a,b){b=b===d?this._items.length:this.normalize(b,!0),this.trigger("add",{content:a,position:b}),0===this._items.length||b===this._items.length?(this.$stage.append(a),this._items.push(a),this._mergers.push(1*a.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)):(this._items[b].before(a),this._items.splice(b,0,a),this._mergers.splice(b,0,1*a.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)),this.invalidate("items"),this.trigger("added",{content:a,position:b})},e.prototype.remove=function(a){a=this.normalize(a,!0),a!==d&&(this.trigger("remove",{content:this._items[a],position:a}),this._items[a].remove(),this._items.splice(a,1),this._mergers.splice(a,1),this.invalidate("items"),this.trigger("removed",{content:null,position:a}))},e.prototype.addTriggerableEvents=function(){var b=a.proxy(function(b,c){return a.proxy(function(a){a.relatedTarget!==this&&(this.suppress([c]),b.apply(this,[].slice.call(arguments,1)),this.release([c]))},this)},this);a.each({next:this.next,prev:this.prev,to:this.to,destroy:this.destroy,refresh:this.refresh,replace:this.replace,add:this.add,remove:this.remove},a.proxy(function(a,c){this.$element.on(a+".owl.carousel",b(c,a+".owl.carousel"))},this))},e.prototype.watchVisibility=function(){function c(a){return a.offsetWidth>0&&a.offsetHeight>0}function d(){c(this.$element.get(0))&&(this.$element.removeClass("owl-hidden"),this.refresh(),b.clearInterval(this.e._checkVisibile))}c(this.$element.get(0))||(this.$element.addClass("owl-hidden"),b.clearInterval(this.e._checkVisibile),this.e._checkVisibile=b.setInterval(a.proxy(d,this),500))},e.prototype.preloadAutoWidthImages=function(b){var c,d,e,f;c=0,d=this,b.each(function(g,h){e=a(h),f=new Image,f.onload=function(){c++,e.attr("src",f.src),e.css("opacity",1),c>=b.length&&(d.state.imagesLoaded=!0,d.initialize())},f.src=e.attr("src")||e.attr("data-src")||e.attr("data-src-retina")})},e.prototype.destroy=function(){this.$element.hasClass(this.settings.themeClass)&&this.$element.removeClass(this.settings.themeClass),this.settings.responsive!==!1&&a(b).off("resize.owl.carousel"),this.transitionEndVendor&&this.off(this.$stage.get(0),this.transitionEndVendor,this.e._transitionEnd);for(var d in this._plugins)this._plugins[d].destroy();(this.settings.mouseDrag||this.settings.touchDrag)&&(this.$stage.off("mousedown touchstart touchcancel"),a(c).off(".owl.dragEvents"),this.$stage.get(0).onselectstart=function(){},this.$stage.off("dragstart",function(){return!1})),this.$element.off(".owl"),this.$stage.children(".cloned").remove(),this.e=null,this.$element.removeData("owlCarousel"),this.$stage.children().contents().unwrap(),this.$stage.children().unwrap(),this.$stage.unwrap()},e.prototype.op=function(a,b,c){var d=this.settings.rtl;switch(b){case"<":return d?a>c:c>a;case">":return d?c>a:a>c;case">=":return d?c>=a:a>=c;case"<=":return d?a>=c:c>=a}},e.prototype.on=function(a,b,c,d){a.addEventListener?a.addEventListener(b,c,d):a.attachEvent&&a.attachEvent("on"+b,c)},e.prototype.off=function(a,b,c,d){a.removeEventListener?a.removeEventListener(b,c,d):a.detachEvent&&a.detachEvent("on"+b,c)},e.prototype.trigger=function(b,c,d){var e={item:{count:this._items.length,index:this.current()}},f=a.camelCase(a.grep(["on",b,d],function(a){return a}).join("-").toLowerCase()),g=a.Event([b,"owl",d||"carousel"].join(".").toLowerCase(),a.extend({relatedTarget:this},e,c));return this._supress[b]||(a.each(this._plugins,function(a,b){b.onTrigger&&b.onTrigger(g)}),this.$element.trigger(g),this.settings&&"function"==typeof this.settings[f]&&this.settings[f].apply(this,g)),g},e.prototype.suppress=function(b){a.each(b,a.proxy(function(a,b){this._supress[b]=!0},this))},e.prototype.release=function(b){a.each(b,a.proxy(function(a,b){delete this._supress[b]},this))},e.prototype.browserSupport=function(){if(this.support3d=j(),this.support3d){this.transformVendor=i();var a=["transitionend","webkitTransitionEnd","transitionend","oTransitionEnd"];this.transitionEndVendor=a[h()],this.vendorName=this.transformVendor.replace(/Transform/i,""),this.vendorName=""!==this.vendorName?"-"+this.vendorName.toLowerCase()+"-":""}this.state.orientation=b.orientation},a.fn.owlCarousel=function(b){return this.each(function(){a(this).data("owlCarousel")||a(this).data("owlCarousel",new e(this,b))})},a.fn.owlCarousel.Constructor=e}(window.Zepto||window.jQuery,window,document),function(a,b){var c=function(b){this._core=b,this._loaded=[],this._handlers={"initialized.owl.carousel change.owl.carousel":a.proxy(function(b){if(b.namespace&&this._core.settings&&this._core.settings.lazyLoad&&(b.property&&"position"==b.property.name||"initialized"==b.type))for(var c=this._core.settings,d=c.center&&Math.ceil(c.items/2)||c.items,e=c.center&&-1*d||0,f=(b.property&&b.property.value||this._core.current())+e,g=this._core.clones().length,h=a.proxy(function(a,b){this.load(b)},this);e++<d;)this.load(g/2+this._core.relative(f)),g&&a.each(this._core.clones(this._core.relative(f++)),h)},this)},this._core.options=a.extend({},c.Defaults,this._core.options),this._core.$element.on(this._handlers)};c.Defaults={lazyLoad:!1},c.prototype.load=function(c){var d=this._core.$stage.children().eq(c),e=d&&d.find(".owl-lazy");!e||a.inArray(d.get(0),this._loaded)>-1||(e.each(a.proxy(function(c,d){var e,f=a(d),g=b.devicePixelRatio>1&&f.attr("data-src-retina")||f.attr("data-src");this._core.trigger("load",{element:f,url:g},"lazy"),f.is("img")?f.one("load.owl.lazy",a.proxy(function(){f.css("opacity",1),this._core.trigger("loaded",{element:f,url:g},"lazy")},this)).attr("src",g):(e=new Image,e.onload=a.proxy(function(){f.css({"background-image":"url("+g+")",opacity:"1"}),this._core.trigger("loaded",{element:f,url:g},"lazy")},this),e.src=g)},this)),this._loaded.push(d.get(0)))},c.prototype.destroy=function(){var a,b;for(a in this.handlers)this._core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Lazy=c}(window.Zepto||window.jQuery,window,document),function(a){var b=function(c){this._core=c,this._handlers={"initialized.owl.carousel":a.proxy(function(){this._core.settings.autoHeight&&this.update()},this),"changed.owl.carousel":a.proxy(function(a){this._core.settings.autoHeight&&"position"==a.property.name&&this.update()},this),"loaded.owl.lazy":a.proxy(function(a){this._core.settings.autoHeight&&a.element.closest("."+this._core.settings.itemClass)===this._core.$stage.children().eq(this._core.current())&&this.update()},this)},this._core.options=a.extend({},b.Defaults,this._core.options),this._core.$element.on(this._handlers)};b.Defaults={autoHeight:!1,autoHeightClass:"owl-height"},b.prototype.update=function(){this._core.$stage.parent().height(this._core.$stage.children().eq(this._core.current()).height()).addClass(this._core.settings.autoHeightClass)},b.prototype.destroy=function(){var a,b;for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoHeight=b}(window.Zepto||window.jQuery,window,document),function(a,b,c){var d=function(b){this._core=b,this._videos={},this._playing=null,this._fullscreen=!1,this._handlers={"resize.owl.carousel":a.proxy(function(a){this._core.settings.video&&!this.isInFullScreen()&&a.preventDefault()},this),"refresh.owl.carousel changed.owl.carousel":a.proxy(function(){this._playing&&this.stop()},this),"prepared.owl.carousel":a.proxy(function(b){var c=a(b.content).find(".owl-video");c.length&&(c.css("display","none"),this.fetch(c,a(b.content)))},this)},this._core.options=a.extend({},d.Defaults,this._core.options),this._core.$element.on(this._handlers),this._core.$element.on("click.owl.video",".owl-video-play-icon",a.proxy(function(a){this.play(a)},this))};d.Defaults={video:!1,videoHeight:!1,videoWidth:!1},d.prototype.fetch=function(a,b){var c=a.attr("data-vimeo-id")?"vimeo":"youtube",d=a.attr("data-vimeo-id")||a.attr("data-youtube-id"),e=a.attr("data-width")||this._core.settings.videoWidth,f=a.attr("data-height")||this._core.settings.videoHeight,g=a.attr("href");if(!g)throw new Error("Missing video URL.");if(d=g.match(/(http:|https:|)\/\/(player.|www.)?(vimeo\.com|youtu(be\.com|\.be|be\.googleapis\.com))\/(video\/|embed\/|watch\?v=|v\/)?([A-Za-z0-9._%-]*)(\&\S+)?/),d[3].indexOf("youtu")>-1)c="youtube";else{if(!(d[3].indexOf("vimeo")>-1))throw new Error("Video URL not supported.");c="vimeo"}d=d[6],this._videos[g]={type:c,id:d,width:e,height:f},b.attr("data-video",g),this.thumbnail(a,this._videos[g])},d.prototype.thumbnail=function(b,c){var d,e,f,g=c.width&&c.height?'style="width:'+c.width+"px;height:"+c.height+'px;"':"",h=b.find("img"),i="src",j="",k=this._core.settings,l=function(a){e='<div class="owl-video-play-icon"></div>',d=k.lazyLoad?'<div class="owl-video-tn '+j+'" '+i+'="'+a+'"></div>':'<div class="owl-video-tn" style="opacity:1;background-image:url('+a+')"></div>',b.after(d),b.after(e)};return b.wrap('<div class="owl-video-wrapper"'+g+"></div>"),this._core.settings.lazyLoad&&(i="data-src",j="owl-lazy"),h.length?(l(h.attr(i)),h.remove(),!1):void("youtube"===c.type?(f="http://img.youtube.com/vi/"+c.id+"/hqdefault.jpg",l(f)):"vimeo"===c.type&&a.ajax({type:"GET",url:"http://vimeo.com/api/v2/video/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a[0].thumbnail_large,l(f)}}))},d.prototype.stop=function(){this._core.trigger("stop",null,"video"),this._playing.find(".owl-video-frame").remove(),this._playing.removeClass("owl-video-playing"),this._playing=null},d.prototype.play=function(b){this._core.trigger("play",null,"video"),this._playing&&this.stop();var c,d,e=a(b.target||b.srcElement),f=e.closest("."+this._core.settings.itemClass),g=this._videos[f.attr("data-video")],h=g.width||"100%",i=g.height||this._core.$stage.height();"youtube"===g.type?c='<iframe width="'+h+'" height="'+i+'" src="http://www.youtube.com/embed/'+g.id+"?autoplay=1&v="+g.id+'" frameborder="0" allowfullscreen></iframe>':"vimeo"===g.type&&(c='<iframe src="http://player.vimeo.com/video/'+g.id+'?autoplay=1" width="'+h+'" height="'+i+'" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>'),f.addClass("owl-video-playing"),this._playing=f,d=a('<div style="height:'+i+"px; width:"+h+'px" class="owl-video-frame">'+c+"</div>"),e.after(d)},d.prototype.isInFullScreen=function(){var d=c.fullscreenElement||c.mozFullScreenElement||c.webkitFullscreenElement;return d&&a(d).parent().hasClass("owl-video-frame")&&(this._core.speed(0),this._fullscreen=!0),d&&this._fullscreen&&this._playing?!1:this._fullscreen?(this._fullscreen=!1,!1):this._playing&&this._core.state.orientation!==b.orientation?(this._core.state.orientation=b.orientation,!1):!0},d.prototype.destroy=function(){var a,b;this._core.$element.off("click.owl.video");for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Video=d}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this.core=b,this.core.options=a.extend({},e.Defaults,this.core.options),this.swapping=!0,this.previous=d,this.next=d,this.handlers={"change.owl.carousel":a.proxy(function(a){"position"==a.property.name&&(this.previous=this.core.current(),this.next=a.property.value)},this),"drag.owl.carousel dragged.owl.carousel translated.owl.carousel":a.proxy(function(a){this.swapping="translated"==a.type},this),"translate.owl.carousel":a.proxy(function(){this.swapping&&(this.core.options.animateOut||this.core.options.animateIn)&&this.swap()},this)},this.core.$element.on(this.handlers)};e.Defaults={animateOut:!1,animateIn:!1},e.prototype.swap=function(){if(1===this.core.settings.items&&this.core.support3d){this.core.speed(0);var b,c=a.proxy(this.clear,this),d=this.core.$stage.children().eq(this.previous),e=this.core.$stage.children().eq(this.next),f=this.core.settings.animateIn,g=this.core.settings.animateOut;this.core.current()!==this.previous&&(g&&(b=this.core.coordinates(this.previous)-this.core.coordinates(this.next),d.css({left:b+"px"}).addClass("animated owl-animated-out").addClass(g).one("webkitAnimationEnd mozAnimationEnd MSAnimationEnd oanimationend animationend",c)),f&&e.addClass("animated owl-animated-in").addClass(f).one("webkitAnimationEnd mozAnimationEnd MSAnimationEnd oanimationend animationend",c))}},e.prototype.clear=function(b){a(b.target).css({left:""}).removeClass("animated owl-animated-out owl-animated-in").removeClass(this.core.settings.animateIn).removeClass(this.core.settings.animateOut),this.core.transitionEnd()},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this.core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Animate=e}(window.Zepto||window.jQuery,window,document),function(a,b,c){var d=function(b){this.core=b,this.core.options=a.extend({},d.Defaults,this.core.options),this.handlers={"translated.owl.carousel refreshed.owl.carousel":a.proxy(function(){this.autoplay()
},this),"play.owl.autoplay":a.proxy(function(a,b,c){this.play(b,c)},this),"stop.owl.autoplay":a.proxy(function(){this.stop()},this),"mouseover.owl.autoplay":a.proxy(function(){this.core.settings.autoplayHoverPause&&this.pause()},this),"mouseleave.owl.autoplay":a.proxy(function(){this.core.settings.autoplayHoverPause&&this.autoplay()},this)},this.core.$element.on(this.handlers)};d.Defaults={autoplay:!1,autoplayTimeout:5e3,autoplayHoverPause:!1,autoplaySpeed:!1},d.prototype.autoplay=function(){this.core.settings.autoplay&&!this.core.state.videoPlay?(b.clearInterval(this.interval),this.interval=b.setInterval(a.proxy(function(){this.play()},this),this.core.settings.autoplayTimeout)):b.clearInterval(this.interval)},d.prototype.play=function(){return c.hidden===!0||this.core.state.isTouch||this.core.state.isScrolling||this.core.state.isSwiping||this.core.state.inMotion?void 0:this.core.settings.autoplay===!1?void b.clearInterval(this.interval):void this.core.next(this.core.settings.autoplaySpeed)},d.prototype.stop=function(){b.clearInterval(this.interval)},d.prototype.pause=function(){b.clearInterval(this.interval)},d.prototype.destroy=function(){var a,c;b.clearInterval(this.interval);for(a in this.handlers)this.core.$element.off(a,this.handlers[a]);for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},a.fn.owlCarousel.Constructor.Plugins.autoplay=d}(window.Zepto||window.jQuery,window,document),function(a){"use strict";var b=function(c){this._core=c,this._initialized=!1,this._pages=[],this._controls={},this._templates=[],this.$element=this._core.$element,this._overrides={next:this._core.next,prev:this._core.prev,to:this._core.to},this._handlers={"prepared.owl.carousel":a.proxy(function(b){this._core.settings.dotsData&&this._templates.push(a(b.content).find("[data-dot]").andSelf("[data-dot]").attr("data-dot"))},this),"add.owl.carousel":a.proxy(function(b){this._core.settings.dotsData&&this._templates.splice(b.position,0,a(b.content).find("[data-dot]").andSelf("[data-dot]").attr("data-dot"))},this),"remove.owl.carousel prepared.owl.carousel":a.proxy(function(a){this._core.settings.dotsData&&this._templates.splice(a.position,1)},this),"change.owl.carousel":a.proxy(function(a){if("position"==a.property.name&&!this._core.state.revert&&!this._core.settings.loop&&this._core.settings.navRewind){var b=this._core.current(),c=this._core.maximum(),d=this._core.minimum();a.data=a.property.value>c?b>=c?d:c:a.property.value<d?c:a.property.value}},this),"changed.owl.carousel":a.proxy(function(a){"position"==a.property.name&&this.draw()},this),"refreshed.owl.carousel":a.proxy(function(){this._initialized||(this.initialize(),this._initialized=!0),this._core.trigger("refresh",null,"navigation"),this.update(),this.draw(),this._core.trigger("refreshed",null,"navigation")},this)},this._core.options=a.extend({},b.Defaults,this._core.options),this.$element.on(this._handlers)};b.Defaults={nav:!1,navRewind:!0,navText:["next","prev"],navSpeed:!1,navElement:"div",navContainer:!1,navContainerClass:"owl-nav",navClass:["owl-prev","owl-next"],slideBy:1,dotClass:"owl-dot",dotsClass:"owl-dots",dots:!0,dotsEach:!1,dotData:!1,dotsSpeed:!1,dotsContainer:!1,controlsClass:"owl-controls"},b.prototype.initialize=function(){var b,c,d=this._core.settings;d.dotsData||(this._templates=[a("<div>").addClass(d.dotClass).append(a("<span>")).prop("outerHTML")]),d.navContainer&&d.dotsContainer||(this._controls.$container=a("<div>").addClass(d.controlsClass).appendTo(this.$element)),this._controls.$indicators=d.dotsContainer?a(d.dotsContainer):a("<div>").hide().addClass(d.dotsClass).appendTo(this._controls.$container),this._controls.$indicators.on("click","div",a.proxy(function(b){var c=a(b.target).parent().is(this._controls.$indicators)?a(b.target).index():a(b.target).parent().index();b.preventDefault(),this.to(c,d.dotsSpeed)},this)),b=d.navContainer?a(d.navContainer):a("<div>").addClass(d.navContainerClass).prependTo(this._controls.$container),this._controls.$next=a("<"+d.navElement+">"),this._controls.$previous=this._controls.$next.clone(),this._controls.$previous.addClass(d.navClass[0]).html(d.navText[0]).hide().prependTo(b).on("click",a.proxy(function(){this.prev(d.navSpeed)},this)),this._controls.$next.addClass(d.navClass[1]).html(d.navText[1]).hide().appendTo(b).on("click",a.proxy(function(){this.next(d.navSpeed)},this));for(c in this._overrides)this._core[c]=a.proxy(this[c],this)},b.prototype.destroy=function(){var a,b,c,d;for(a in this._handlers)this.$element.off(a,this._handlers[a]);for(b in this._controls)this._controls[b].remove();for(d in this.overides)this._core[d]=this._overrides[d];for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},b.prototype.update=function(){var a,b,c,d=this._core.settings,e=this._core.clones().length/2,f=e+this._core.items().length,g=d.center||d.autoWidth||d.dotData?1:d.dotsEach||d.items;if("page"!==d.slideBy&&(d.slideBy=Math.min(d.slideBy,d.items)),d.dots||"page"==d.slideBy)for(this._pages=[],a=e,b=0,c=0;f>a;a++)(b>=g||0===b)&&(this._pages.push({start:a-e,end:a-e+g-1}),b=0,++c),b+=this._core.mergers(this._core.relative(a))},b.prototype.draw=function(){var b,c,d="",e=this._core.settings,f=(this._core.$stage.children(),this._core.relative(this._core.current()));if(!e.nav||e.loop||e.navRewind||(this._controls.$previous.toggleClass("disabled",0>=f),this._controls.$next.toggleClass("disabled",f>=this._core.maximum())),this._controls.$previous.toggle(e.nav),this._controls.$next.toggle(e.nav),e.dots){if(b=this._pages.length-this._controls.$indicators.children().length,e.dotData&&0!==b){for(c=0;c<this._controls.$indicators.children().length;c++)d+=this._templates[this._core.relative(c)];this._controls.$indicators.html(d)}else b>0?(d=new Array(b+1).join(this._templates[0]),this._controls.$indicators.append(d)):0>b&&this._controls.$indicators.children().slice(b).remove();this._controls.$indicators.find(".active").removeClass("active"),this._controls.$indicators.children().eq(a.inArray(this.current(),this._pages)).addClass("active")}this._controls.$indicators.toggle(e.dots)},b.prototype.onTrigger=function(b){var c=this._core.settings;b.page={index:a.inArray(this.current(),this._pages),count:this._pages.length,size:c&&(c.center||c.autoWidth||c.dotData?1:c.dotsEach||c.items)}},b.prototype.current=function(){var b=this._core.relative(this._core.current());return a.grep(this._pages,function(a){return a.start<=b&&a.end>=b}).pop()},b.prototype.getPosition=function(b){var c,d,e=this._core.settings;return"page"==e.slideBy?(c=a.inArray(this.current(),this._pages),d=this._pages.length,b?++c:--c,c=this._pages[(c%d+d)%d].start):(c=this._core.relative(this._core.current()),d=this._core.items().length,b?c+=e.slideBy:c-=e.slideBy),c},b.prototype.next=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!0),b)},b.prototype.prev=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!1),b)},b.prototype.to=function(b,c,d){var e;d?a.proxy(this._overrides.to,this._core)(b,c):(e=this._pages.length,a.proxy(this._overrides.to,this._core)(this._pages[(b%e+e)%e].start,c))},a.fn.owlCarousel.Constructor.Plugins.Navigation=b}(window.Zepto||window.jQuery,window,document),function(a,b){"use strict";var c=function(d){this._core=d,this._hashes={},this.$element=this._core.$element,this._handlers={"initialized.owl.carousel":a.proxy(function(){"URLHash"==this._core.settings.startPosition&&a(b).trigger("hashchange.owl.navigation")},this),"prepared.owl.carousel":a.proxy(function(b){var c=a(b.content).find("[data-hash]").andSelf("[data-hash]").attr("data-hash");this._hashes[c]=b.content},this)},this._core.options=a.extend({},c.Defaults,this._core.options),this.$element.on(this._handlers),a(b).on("hashchange.owl.navigation",a.proxy(function(){var a=b.location.hash.substring(1),c=this._core.$stage.children(),d=this._hashes[a]&&c.index(this._hashes[a])||0;return a?void this._core.to(d,!1,!0):!1},this))};c.Defaults={URLhashListener:!1},c.prototype.destroy=function(){var c,d;a(b).off("hashchange.owl.navigation");for(c in this._handlers)this._core.$element.off(c,this._handlers[c]);for(d in Object.getOwnPropertyNames(this))"function"!=typeof this[d]&&(this[d]=null)},a.fn.owlCarousel.Constructor.Plugins.Hash=c}(window.Zepto||window.jQuery,window,document);


/* ]]> */
</script>
<script type='text/javascript'>
//<![CDATA[
$(document).ready(function(){$(".slider .labelposts").owlCarousel({rtl:!0,loop:!0,margin:2,autoplay:!0,slideSpeed:300,paginationSpeed:400,autoplayTimeout:4e3,nav:!0,navText:["<i class='fa fa-angle-right'></i>","<i class='fa fa-angle-left'></i>"],responsive:{0:{items:1},600:{items:2},1e3:{items:3}}})})
//]]>
</script>
<script type='text/javascript'>
  //<![CDATA[
window.selectnav=function(){"use strict";var e=function(e,t){function c(e){var t;if(!e)e=window.event;if(e.target)t=e.target;else if(e.srcElement)t=e.srcElement;if(t.nodeType===3)t=t.parentNode;if(t.value)window.location.href=t.value}function h(e){var t=e.nodeName.toLowerCase();return t==="ul"||t==="ol"}function p(e){for(var t=1;document.getElementById("selectnav"+t);t++);return e?"selectnav"+t:"selectnav"+(t-1)}function d(e){a++;var t=e.children.length,n="",l="",c=a-1;if(!t){return}if(c){while(c--){l+=o}l+=" "}for(var v=0;v<t;v++){var m=e.children[v].children[0];if(typeof m!=="undefined"){var g=m.innerText||m.textContent;var y="";if(r){y=m.className.search(r)!==-1||m.parentNode.className.search(r)!==-1?f:""}if(i&&!y){y=m.href===document.URL?f:""}n+='<option value="'+m.href+'" '+y+">"+l+g+"</option>";if(s){var b=e.children[v].children[1];if(b&&h(b)){n+=d(b)}}}}if(a===1&&u){n='<option value="">'+u+"</option>"+n}if(a===1){n='<select class="selectnav" id="'+p(true)+'">'+n+"</select>"}a--;return n}e=document.getElementById(e);if(!e){return}if(!h(e)){return}if(!("insertAdjacentHTML"in window.document.documentElement)){return}document.documentElement.className+=" js";var n=t||{},r=n.activeclass||"active",i=typeof n.autoselect==="boolean"?n.autoselect:true,s=typeof n.nested==="boolean"?n.nested:true,o=n.indent||"?",u=n.label||"- القائمة -",a=0,f=" selected ";e.insertAdjacentHTML("afterend",d(e));var l=document.getElementById(p());if(l.addEventListener){l.addEventListener("change",c)}if(l.attachEvent){l.attachEvent("onchange",c)}return l};return function(t,n){e(t,n)}}();$(document).ready(function(){selectnav('nav');selectnav('nav1');selectnav('nav3');});
  //]]>
</script>


<script async='async' data-cfasync='false' src='https://iptautup.com/pfe/current/tag.min.js?z=3522663'/>



	</body>

    </html>
