# akvariumrus
<!DOCTYPE html>
<html lang="en">
<head>
<title>Готовый сайт о комнатных рыбках (ДЕМО шаблона сайта)</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<meta http-equiv="X-UA-Compatible" content="IE=9; IE=8;"/>
<link rel="canonical" href="http://www.templatemonster.com/ru/moto-cms-html-templates-type/42693.html"> <link rel="stylesheet" type="text/css" href="http://393252296.r.cdn77.net/ru/themes/rutm/css/normalize.css"/>
<link rel="stylesheet" type="text/css" href="http://393252296.r.cdn77.net/ru/themes/rutm/css/preview.css?20130713"/>
<link rel="stylesheet" type="text/css" href="http://393252296.r.cdn77.net/ru/themes/rutm/css/preview-responsive.css?3"/>
<script type="text/javascript" src="http://393252296.r.cdn77.net/ru/themes/rutm/js/jquery-1.8.1.min.js"></script>
<script charset="utf-8">
  //TODO: some strange value
    var min_height = 600;
    $(function(){
        resizeFrame();
    });
    function resizeFrame()
    {
    if (1 == 0)
      return false;
        var main_iframe = $('#preview');
        var height = $(window).height() - $('#preview-bar:visible').outerHeight();
        if($.browser.opera)
            height += 5;

        if (height < min_height)
            height = min_height;
        $('#preview').height(height);
        $('#iframelive').height(height);
      //$('#preview-wrapper').height(height);
        if ($(window).width() < 1400)
            $('#min-hide-this').hide();
        else
            $('#min-hide-this').show();

    }
    $(window).resize(function() {
        resizeFrame();
    }).load(function() {
        resizeFrame();
    });
  $(document).ready(function(){
    $('#close').click(function(e){
      e.preventDefault();
      document.location.href = "http://templates.cms-guide.com/42693/";
      /*$("#preview-bar").hide();
      resizeFrame();*/
    });
  })

    </script>
</head>
<body id='fullscreen-preview'>
 
<noscript><iframe src="//www.googletagmanager.com/ns.html?id=GTM-P5DSRW" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'//www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-P5DSRW');</script>
  <script>
//GLOBAL_HEAD_SCRIPT
</script>
<script type="text/javascript" src="http://vk.com/js/api/openapi.js?48"></script>
<script type="text/javascript">
  VK.init({apiId: 2828786, onlyWidgets: true});
</script> <div id="preview-bar">
<ul id="bar-inner">
<script src="http://393252296.r.cdn77.net/ru/themes/rutm/js/jquery.cookie.js?v2" type="text/javascript"></script>
<script type="text/javascript">
  $(document).ready(function(){
    function demo_block_logo(){
      var expireDate = new Date;
          expireDate.setDate(expireDate.getDate() + 1);       
      var state = $.cookie("demo_block_logo");
      var url = "";
      var image = "/ru/themes/rutm/images/preview/";
      var onclick = "";
      switch (state){
        case undefined: 
          $.cookie("demo_block_logo", 1, {expires: expireDate, path: '/ru/'});
          url = "http://www.templatemonster.com/ru/chat/";
          image += "tm_logo_chat.png";
          onclick = 'dataLayer.push({"event": "demo-frame", "eventCategory": "demo-frame", "eventAction": "click","eventLabel": "chat"});';
          break;
        case "1":
          $.cookie("demo_block_logo", 2, {expires: expireDate, path: '/ru/'});
          url = "http://www.templatemonster.com/ru/chat/";
          image += "tm_logo_chat.png";
          onclick = 'dataLayer.push({"event": "demo-frame", "eventCategory": "demo-frame", "eventAction": "click","eventLabel": "chat"});';
          break;
        case "2":
          $.cookie("demo_block_logo", 1, {expires: expireDate, path: '/ru/'});
          var locale = $.cookie("tm_country_code");
          if(locale == "UA"){
            url = "tel:+380443920785";
            image += "tm_logo_telephone_ua.png";
          }else{
            url = "tel:+74993460965";
            image += "tm_logo_telephone_ru.png";
          }
          onclick = 'dataLayer.push({"event": "demo-frame", "eventCategory": "demo-frame", "eventAction": "click","eventLabel": "phone"});';
          break;
      }
      var element = "<a href='" + url + "' onclick='" + onclick + "'><img src='" + image + "' width='298' height='57'></a>";
      $("#demo_logo_block").empty();        
      $("#demo_logo_block").append(element);
      setTimeout(function(){
        demo_block_logo()
      }, 5000);
    }
    demo_block_logo();
    var expireDate = new Date;
      expireDate.setDate(expireDate.getDate() + 1);   
    $.cookie("tm_country_code", "UA", {expires: expireDate, path: '/ru/'});   
  }); 
</script>
<style><!--
#sidebar-share-block li {
  width:100px;
}
--></style>

<li class="twttr-share-btn">
<div>
<noindex>
<a rel="nofollow" href="https://twitter.com/share" class="twitter-share-button" data-url="http://www.templatemonster.com/ru/moto-cms-html-templates-type/42693.html" data-lang="en"></a>
</noindex>
<script>!function (d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (!d.getElementById(id)) {
          js = d.createElement(s);
          js.id = id;
          js.src = "//platform.twitter.com/widgets.js";
          fjs.parentNode.insertBefore(js, fjs);
        }
      }(document, "script", "twitter-wjs");</script>
</div>
</li>
<li class="fb-share-btn" style="width: 81px;">
<div>
<div id="fb-root"></div>
<script>(function (d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (d.getElementById(id)) return;
        js = d.createElement(s);
        js.id = id;
        js.src = "//connect.facebook.net/en_US/all.js#xfbml=1&appId=322221494492881";
        fjs.parentNode.insertBefore(js, fjs);
      }(document, 'script', 'facebook-jssdk'));</script>
<div class="fb-like" data-send="false" data-layout="button_count" data-width="95" data-show-faces="false" data-href="http://www.templatemonster.com/ru/moto-cms-html-templates-type/42693.html"></div>
</div>
</li>
</ul>
</li>
</ul>
</div>
<div id="iframelive" class="no-responsive">
<div id="preview-wrapper">
<iframe id="preview" frameborder="0" src="http://templates.cms-guide.com/42693/" data-src="http://templates.cms-guide.com/42693/"> </iframe>
</div>
</div>
</body>
</html>
