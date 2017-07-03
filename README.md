# Jocuri-pt-Platforme-de-socializare

1. https://apps.facebook.com/sweettreatsnew/?ref=br_rs
	URL-ul Jocului de pe propriul site: https://www.aisgames.com/paul/candypop/
2. https://apps.facebook.com/bubbleswitch
	URL-ul Jocului de pe propriul site: https://www.aisgames.com/paul/masterofpotions/
3. https://apps.facebook.com/dayznew
	URL-ul Jocului de pe propriul site: https://www.aisgames.com/paul/1/asdgwq/
4. https://apps.facebook.com/jewelcraftnew
	URL-ul Jocului de pe propriul site: https://www.aisgames.com/paul/jewelish/
5. https://apps.facebook.com/captainpaul
	URL-ul Jocului de pe propriul site: https://www.aisgames.com/paul/test2/
6. https://apps.facebook.com/ancientdwarf
	URL-ul Jocului de pe propriul site: https://www.aisgames.com/paul/ancientore/
  
   Lini de cod ale Index-ului si frame-urile folosite pt jocuri si afisarea reclamelor:
   
   <html>
<head>
<title>Sweet Treats</title>
   <meta property="fb:app_id" content="" />
    <meta property="og:url" content="" />
    <meta property="og:site_name" content="" />
    <meta property="og:type" content="game" />
    <meta property="og:image" content="" />
    <meta property="og:image:width" content="128" />
    <meta property="og:image:height" content="128" />
    <meta property="og:description" content="" />
    <meta property="og:title" content="" />
<style type="text/css">
    body
    {
        background-color: #000000;
        color: white;
        margin: 0;
        padding: 0;
        overflow: hidden;
    }
    #up
    {
        height: 90px;
        position: absolute;
        left: 0px;
        right: 0px;
    }
	#down
    {
        height: 90px;
        position: absolute;
        left: 0px;
        right: 0px;
        bottom: 0px;
    }
    #left
	{
	    height: auto;
        position: absolute;
        left: 0px;
        top: 10px;

	}
	#right
	{
	    height: auto;
        position: absolute;
        right: 0px;
        top: 10px;
        bottom: ;

	}
    #main
    {
        position: absolute;
        left: 160px;
        top: 90px;
        bottom: 90px;
        right: 160px;
    }
    
    iframe
    {
		position: absolute;
		border: none;
        height: 100%;
        width: 100%;

    }
    #down
    {
        height: 90px;
        position: absolute;
        left: 0px;
        right: 0px;
        bottom: 0px;
    }
	.like {
    padding-top: 10px;
    padding-right: 0px;
    padding-bottom: 0px;
    padding-left: 200px;
		
    }
	.closetxt {
	color: #000000;
	}
#navi,
#infoi {
  width: 100%;
  height: 100%;
  position: absolute;
  top: 10%;
  left: 25%;
opacity: 1;
}
#infoi {
  z-index: 10;
  }
#container {
  width: 100%;
  height: 100%;
  position: relative;
  align-text; center;
}
#in {
  transition-delay: 5s;
  animation: seconds 5.0s forwards;
  animation-iteration-count: 1;
  animation-delay: 60s;
  position: absolute;
  top: 10%;
  left: 25%;
  z-index: 10;
  }
@-webkit-keyframes seconds {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    left: -9999px; 
  }
}
@keyframes seconds {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    left: -9999px; 
  }
}
.pop { display: none;
}
.contentPost { 
	display: none;
	position: absolute;
	text-align: center;
    margin-left: -325px;
	left: 50%;
	z-index: 9999;
}
UL { 
    position: absolute;
    background: #d9edf7;
	margin: 0 auto;
    padding: 3px 3px 3px 3px;
	height: 350px;
	width: 400px;
	z-index: 9999;
	-moz-border-radius: 15px;
	border-radius: 15px;
}
h1 {
    color: #000000;
	top: 200px;
}
.close {
	display: none;
    color: #aaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
}
.close:hover,
.close:focus {
    color: black;
    text-decoration: none;
    cursor: pointer;
}
.fb-share-button
{
 text-align: center;
position: absolute;
-webkit-transform: scale(3.5);
-o-transform: scale(3.5);
-moz-transform: scale(3.5);

}
</style>
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
<script src="https://code.jquery.com/jquery-2.2.4.min.js" integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44=" crossorigin="anonymous"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.2/jquery.min.js"></script>
<script type="text/javascript">  
$(document).ready(function() {
    $(".close").delay(5000).fadeIn(500); // .delay se seteaza timpul dupa cat timp sa apara butonul de share 300000 inseamana 5 min
});
$(document).ready(function() {
    $(".contentPost").delay(0).fadeIn(500); // .delay se seteaza timpul dupa cat timp sa apara butonul de share 300000 inseamana 5 min
});
$("button").click(function(){
    $("p").removeClass("intro");
});
</script>
<!--cod scurt lifestreet-->
<script src="//ads.lfstmedia.com/getad?site=277561" type="text/javascript"></script>
</head>
<body>
<div class="contentPost" div data-role="main">
	<UL>
 		 <div class="close" id="close" onClick="$(this).parent().remove();">Close(x)</div>
		 <br /> <br /> <br />
		 	<!-- Cod---------------------------------------------------------------  popup                   Facebook -->
<script type="text/javascript">
    //<![CDATA[
        LSM_Slot({
            adkey: '6b6',
            ad_size: '300x250',
            slot: 'slot163949'
        });
    //]]>
</script>
<br />
<div class="closetxt">Please wait 5 seconds for the close button to appear.</div>

	</UL>
</div>
<div id="up">
    <div style="margin: 0 auto; width: 728px;">
<script type="text/javascript">
    //<![CDATA[
        LSM_Slot({
            adkey: '103',
            ad_size: '728x90',
            slot: 'slot147324'
        });
    //]]>
</script>
    </div>
</div>
<div id="left">
    <div style="margin: 0 left; width: 160px;">
	<script type="text/javascript">
    //<![CDATA[
        LSM_Slot({
            adkey: 'dc0',
            ad_size: '160x600',
            slot: 'slot163951'
        });
    //]]>
</script>
    </div>
</div>
   <div id="main">
        <iframe allowfullscreen="true" src="main.htm" scrolling="no" noresize="noresize" ></iframe>
    </div>
	
<div id="down">
    <div style="margin: 0 auto; width: 728px;">
<script type="text/javascript">
    //<![CDATA[
        LSM_Slot({
            adkey: '371',
            ad_size: '728x90',
            slot: 'slot146786'
        });
    //]]>
</script>
    </div>
</div>
<div id="right">
    <div style="margin: 0 right; width: 160px;">
<script type="text/javascript">
    //<![CDATA[
        LSM_Slot({
            adkey: 'ea6',
            ad_size: '160x600',
            slot: 'slot163950'
        });
    //]]>
</script>
    </div>
</div>

<!-- Cod Facebook -->
<script>
  window.fbAsyncInit = function() {
    FB.init({
      appId      : '290332094664124',
      xfbml      : true,
      version    : 'v2.7'
    });

    // ADD ADDITIONAL FACEBOOK CODE HERE
  };

  (function(d, s, id){
     var js, fjs = d.getElementsByTagName(s)[0];
     if (d.getElementById(id)) {return;}
     js = d.createElement(s); js.id = id;
     js.src = "//connect.facebook.net/en_US/sdk.js";
     fjs.parentNode.insertBefore(js, fjs);
   }(document, 'script', 'facebook-jssdk'));
</script>
</body>

</html>
