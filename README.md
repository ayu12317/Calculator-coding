# Calculator-coding

<!Doctype html>
<html class="no-js" lang="en-US">

<head>
  <meta charset="utf-8">
  <meta http-equiv="x-ua-compatible" content="ie=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#ffffff" />

  <title>Python Program to Make a Simple Calculator</title>
  <link rel="shortcut icon" href="/sites/tutorial2program/files/favicon.png" />
  <link type="text/css" rel="stylesheet" href="/sites/tutorial2program/files/advagg_css/css__NuHAAUSfHYnlqPjyAvUWFPOMPxyn0Mg_LRf9xCrHK3c__KQuVGih3SWllQCT8l7tgRXR9HTBFxqfdxs9G94NsLiM__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.css" media="all" />
<link type="text/css" rel="stylesheet" href="/sites/tutorial2program/files/advagg_css/css__DqoqWo9ss46Auy7AHkZpWa4FfBVCgxSqj_wl8DzuNks__zOFoKyda5cpUEflj9DXCYYSuZqzhwU-xa65PpDg6DpQ__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.css" media="all" />

  <!--[if IE]><![endif]-->
<link rel="dns-prefetch" href="//www.google.com" />
<link rel="preconnect" href="//www.google.com" />
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="description" content="In this example you will learn to create a simple calculator that can add, subtract, multiply or divide depending upon the input from the user." />
<meta name="generator" content="Drupal 7 (http://drupal.org)" />
<link rel="canonical" href="https://www.programiz.com/python-programming/examples/calculator" />
<link rel="shortlink" href="https://www.programiz.com/node/113" />
<script>
  var url = window.location.href;
  window.googletag = window.googletag || {cmd: []};
  window.googletag.cmd.push(function() {
      switch (true) {
          case url.includes("/python-programming/numpy"):
              window.googletag.pubads().setTargeting('prog_lang', 'numpy');
              break;
          case url.includes("/sql"):
              window.googletag.pubads().setTargeting('prog_lang', 'sql');
              break;
          case url.includes("/c-programming"):
              window.googletag.pubads().setTargeting('prog_lang', 'c_programming');
              break;
          case url.includes("/cpp-programming"):
              window.googletag.pubads().setTargeting('prog_lang', 'c_plus_plus');
              break;
          case url.includes("/csharp-programming"):
              window.googletag.pubads().setTargeting('prog_lang', 'c_sharp_lang');
              break;
          case url.includes("/dsa"):
              window.googletag.pubads().setTargeting('prog_lang', 'dsa');
              break;
          case url.includes("/java-programming"):
              window.googletag.pubads().setTargeting('prog_lang', 'java');
              break;
          case url.includes("/javascript"):
              window.googletag.pubads().setTargeting('prog_lang', 'javascript');
              break;
          case url.includes("/kotlin-programming"):
              window.googletag.pubads().setTargeting('prog_lang', 'kotlin');
              break;
          case url.includes("/python-programming"):
              window.googletag.pubads().setTargeting('prog_lang', 'python');
              break;
          case url.includes("/swift-programming"):
              window.googletag.pubads().setTargeting('prog_lang', 'swift');
              break;
      }
  });
</script>

<script src="https://cmp.uniconsent.com/v2/stub.min.js"></script>
<script async src='https://cmp.uniconsent.com/v2/a8d3ae4937/cmp.js'></script>
<script type="text/javascript">
    window.googletag = window.googletag || {};
    window.googletag.cmd = window.googletag.cmd || [];
    window.googletag.cmd.push(function () {
        window.googletag.pubads().enableAsyncRendering();
        window.googletag.pubads().disableInitialLoad();
    });
    (adsbygoogle = window.adsbygoogle || []).pauseAdRequests = 1;
</script>
<script>
    __tcfapi("addEventListener", 2, function (tcData, success) {
        if (success && tcData.unicLoad === true) {
            if (!window._initAds) {
                window._initAds = true;
                var script = document.createElement('script');
                script.async = true;
                script.src = '//dsh7ky7308k4b.cloudfront.net/publishers/Programizcomnew.min.js';
                document.head.appendChild(script);

                script = document.createElement('script');
                script.async = true;
                script.src = '//btloader.com/tag?o=5184339635601408&upapi=true';
                document.head.appendChild(script);
            }
        }
    });
</script>

<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-TKXT7MH');</script>
<style>.pub-ad{z-index:0;clear:both;position:relative;text-align:center}.pub-ad::before{content:'ADVERTISEMENTS';display:block;position:absolute;top:-20px;left:0;right:0;height:20px;font-size:9px;line-height:20px;letter-spacing:1px;color:#bcbfc5}</style>
<!-- Facebook Pixel Code -->
<script async>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '123000288571689');
fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=123000288571689&ev=PageView&noscript=1"
/></noscript>
<!-- End Facebook Pixel Code -->
<style>.adSpinner {display: none;}</style>
  
<!--[if lte IE 9]>
<script type="text/javascript" src="/sites/tutorial2program/files/advagg_js/js__2nu-f_-MK33dRIQaWIdLP84wUiGzIZwBgGaMto4f2kY__2pkqXjBO9pMF06nUvX11DkMECNCM7M-5Qm_bWm0bC9k__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.js#ie9-" onload="if(jQuery.isFunction(jQuery.holdReady)){jQuery.holdReady(true);}"></script>
<![endif]-->

<!--[if gt IE 9]>
<script type="text/javascript" src="/sites/tutorial2program/files/advagg_js/js__2nu-f_-MK33dRIQaWIdLP84wUiGzIZwBgGaMto4f2kY__2pkqXjBO9pMF06nUvX11DkMECNCM7M-5Qm_bWm0bC9k__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.js#ie10+" defer="defer" onload="if(jQuery.isFunction(jQuery.holdReady)){jQuery.holdReady(true);}"></script>
<![endif]-->

<!--[if !IE]><!-->
<script type="text/javascript" src="/sites/tutorial2program/files/advagg_js/js__2nu-f_-MK33dRIQaWIdLP84wUiGzIZwBgGaMto4f2kY__2pkqXjBO9pMF06nUvX11DkMECNCM7M-5Qm_bWm0bC9k__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.js" defer="defer" onload="if(jQuery.isFunction(jQuery.holdReady)){jQuery.holdReady(true);}"></script>
<!--<![endif]-->
<script type="text/javascript" src="/sites/tutorial2program/files/advagg_js/js__ZyeOaiFuDejQQbhUV7yg7atYZnj4WLfH77o0scv4068__jeShjS1-sEwOx4dbB-NSBsCnxWfNslS1Nkgx4CZngGA__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.js" defer="defer" onload="
function advagg_mod_2() {
  // Count how many times this function is called.
  advagg_mod_2.count = ++advagg_mod_2.count || 1;
  try {
    if (advagg_mod_2.count <= 40) {
      init_drupal_core_settings();

      // Set this to 100 so that this function only runs once.
      advagg_mod_2.count = 100;
    }
  }
  catch(e) {
    if (advagg_mod_2.count >= 40) {
      // Throw the exception if this still fails after running 40 times.
      throw e;
    }
    else {
      // Try again in 1 ms.
      window.setTimeout(advagg_mod_2, 1);
    }
  }
}
function advagg_mod_2_check() {
  if (window.init_drupal_core_settings && window.jQuery && window.Drupal) {
    advagg_mod_2();
  }
  else {
    window.setTimeout(advagg_mod_2_check, 1);
  }
}
advagg_mod_2_check();"></script>
<script type="text/javascript" src="/sites/tutorial2program/files/advagg_js/js__UW4URQsON5h-xjwepC-HoW32RCC10thhh4f0DQ1P8z4__V2RYL4VZntPWB_PMJnR7_8tZaKLRfCHmVvwTgS8C0iM__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.js" defer="defer"></script>
<script type="text/javascript" async="async" src="https://www.google.com/recaptcha/api.js?hl=en"></script>
<script type="text/javascript">
<!--//--><![CDATA[//><!--
function init_drupal_core_settings() {jQuery.extend(Drupal.settings,{"basePath":"\/","pathPrefix":"","setHasJsCookie":0,"ajaxPageState":{"theme":"programiz","theme_token":"y2ibdv-TX_RBMU7DnDcx_e6AG4n2jrGr_lORi0BcbeM","jquery_version":"1.10","css":{"modules\/system\/system.base.css":1,"modules\/system\/system.menus.css":1,"modules\/system\/system.messages.css":1,"modules\/system\/system.theme.css":1,"modules\/field\/theme\/field.css":1,"modules\/node\/node.css":1,"sites\/all\/modules\/programiz_pro_challenges\/css\/programiz_pro_challenges.css":1,"sites\/all\/modules\/programiz_pro_cornerstone_banner\/css\/programiz_pro_cornerstone_banner.css":1,"sites\/all\/modules\/programiz_rate_share\/rate_share.css":1,"modules\/user\/user.css":1,"sites\/all\/modules\/views\/css\/views.css":1,"sites\/all\/modules\/ctools\/css\/ctools.css":1,"public:\/\/honeypot\/honeypot.css":1,"sites\/all\/modules\/webform\/css\/webform.css":1,"sites\/all\/themes\/programiz\/lib\/highlightjs\/highlight.min.css":1,"sites\/all\/themes\/programiz\/lib\/mautic\/mautic.css":1,"sites\/all\/themes\/programiz\/dist\/main.css":1},"js":{"sites\/all\/modules\/programiz_pro_challenges\/js\/init_monaco.js":1,"sites\/all\/modules\/programiz_rate_share\/programiz_rate_share.js":1,"sites\/all\/modules\/captcha\/captcha.js":1,"misc\/textarea.js":1,"misc\/progress.js":1,"sites\/all\/modules\/webform\/js\/webform.js":1,"sites\/all\/themes\/programiz\/dist\/main.min.js":1,"sites\/all\/themes\/programiz\/lib\/highlightjs\/highlight.min.js":1,"sites\/all\/themes\/programiz\/lib\/mautic\/mautic.js":1,"sites\/all\/modules\/jquery_update\/replace\/jquery\/1.10\/jquery.min.js":1,"misc\/jquery-extend-3.4.0.js":1,"misc\/jquery-html-prefilter-3.5.0-backport.js":1,"misc\/jquery.once.js":1,"misc\/drupal.js":1,"sites\/all\/modules\/jquery_update\/replace\/ui\/external\/jquery.cookie.js":1,"sites\/all\/modules\/jquery_update\/replace\/misc\/jquery.form.min.js":1,"misc\/ajax.js":1,"sites\/all\/modules\/jquery_update\/js\/jquery_update.js":1,"https:\/\/www.google.com\/recaptcha\/api.js?hl=en":1}},"eventsData":[],"proUrlData":{"url":"https:\/\/programiz.pro\/learn\/master-python","language":"Python"},"better_exposed_filters":{"views":{"related_examples_c_cpp_python_r_":{"displays":{"block_2":{"filters":[]}}},"related_topics_sidebar_second_before_sticky_ad_":{"displays":{"block":{"filters":[]}}},"similar_python_programming_examples":{"displays":{"block":{"filters":[]}}}}},"ajax":{"edit-submit":{"callback":"page_feedback_webform_ajax_validate","wrapper":"webform-client-form-1680","progress":{"type":"throbber"},"event":"mousedown","keypress":true,"prevent":"click","url":"\/system\/ajax","submit":{"_triggering_element_name":"op","_triggering_element_value":"Submit Feedback"}}},"urlIsAjaxTrusted":{"\/system\/ajax":true,"\/python-programming\/examples\/calculator":true}}); 
if(jQuery.isFunction(jQuery.holdReady)){jQuery.holdReady(false);}} if(window.jQuery && window.Drupal){init_drupal_core_settings();}
//--><!]]>
</script>
</head>

<body>
    <div class="main--backdrop"></div>

<main class="soft-bg has-notice-bar-top">

  <header class="main-nav d-flex flex-column justify-content-center">
            
    
    
    
    
<!-- For mobile -->
<div class="notice-bar-top notice-bar-top--mobile d-flex d-lg-none">
  
<a class="notice-bar-top__link" rel="nofollow" href="https://programiz.pro/learn/master-python" title="Try Programiz PRO today." target="_blank" style="background: #FFE8D6;">
    <div class="notice-bar-top__wrapper container">
      <!-- Left wrapper -->
      <!-- <div class="notice-bar-top__wrapper__left">
        <div class="notice-bar-top__sticker" style="background: #FE5196; color: #FFFFFF;">66% off</div>
      </div> -->
      <!-- Center wrapper -->
      <div class="notice-bar-top__wrapper__center pl-0x pr-0x">
        <!-- Title on mobile -->
        <div class="notice-bar-top__title d-none d-md-inline" style="color: #25265E;">Learn to code solving problems and writing code with our <strong>hands-on Python</strong> course.</div>
        <!-- Title on desktop -->
        <div class="notice-bar-top__title d-inline d-md-none" style="color: #25265E;">Learn to code solving problems with our <strong>hands-on Python</strong> course!</div>
        <span class="notice-bar-top__cta">Try Programiz PRO today.</span>
      </div>
      <!-- Right wrapper -->
      <div class="notice-bar-top__wrapper__right">
        <div class="notice-bar-top__title" style="color: #25265E;">
          Sale ends in <span class="notice-bar-top__sale-timer"></span>
        </div>
      </div>
    </div>
  </a></div>

<!-- For Desktop -->
<div class="notice-bar-top notice-bar-top--desktop d-none d-lg-flex">
  
<a class="notice-bar-top__link" rel="nofollow" href="https://programiz.pro/learn/master-python" title="Try Programiz PRO today." target="_blank" style="background: #FFE8D6;">
    <div class="notice-bar-top__wrapper container">
      <!-- Left wrapper -->
      <!-- <div class="notice-bar-top__wrapper__left">
        <div class="notice-bar-top__sticker" style="background: #FE5196; color: #FFFFFF;">66% off</div>
      </div> -->
      <!-- Center wrapper -->
      <div class="notice-bar-top__wrapper__center pl-0x pr-0x">
        <!-- Title on mobile -->
        <div class="notice-bar-top__title d-none d-md-inline" style="color: #25265E;">Learn to code solving problems and writing code with our <strong>hands-on Python</strong> course.</div>
        <!-- Title on desktop -->
        <div class="notice-bar-top__title d-inline d-md-none" style="color: #25265E;">Learn to code solving problems with our <strong>hands-on Python</strong> course!</div>
        <span class="notice-bar-top__cta">Try Programiz PRO today.</span>
      </div>
      <!-- Right wrapper -->
      <div class="notice-bar-top__wrapper__right">
        <div class="notice-bar-top__title" style="color: #25265E;">
          Sale ends in <span class="notice-bar-top__sale-timer"></span>
        </div>
      </div>
    </div>
  </a></div>

        
    <nav>
      <div class="container flex-1">
        <div class="d-flex align-items-center p-relative">
          <button class="main-nav__menu-btn d-lg-none d-flex">
            <svg class="programiz-icon">
              <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#menu"></use>
            </svg>
          </button>

          <div class="brand">
            <a href="/" title="Programiz">
              <img class="d-lg-none" src="//cdn.programiz.com/sites/tutorial2program/files/sp_logo.svg" width="28" height="28" alt="Programiz">
              <img class="d-none d-lg-block" src="//cdn.programiz.com/sites/tutorial2program/files/pc_logo.svg" width="84" height="28" alt="Programiz">
            </a>
          </div>

                      <div class="navigation d-none d-lg-flex align-items-center">
                
    
    
    
    <a class="navigation__node" href="#" title="Programming Tutorials" id="navigation-tutorials"><span class="navigation__node__label">Tutorials </span>
  <svg class="programiz-icon programiz-icon--smallest navigation__node__icon">
    <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#chevron-down"></use>
  </svg>
</a>
<a class="navigation__node" href="javascript:void(0);" title="Programming Examples" id="navigation-examples">
  <span class="navigation__node__label"> Examples </span>
  <svg class="programiz-icon programiz-icon--smallest navigation__node__icon">
    <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#chevron-down"></use>
  </svg>
</a>
<a class="navigation__node navigation__node--pro" href="#" title="Learn to Code Interactively" rel="nofollow" id="navigation-pro"><span class="navigation__node__label d-flex align-items-center">
    <img src="/sites/all/themes/programiz/assets/programiz-pro-mini-logo.svg" alt="Programiz Pro Logo" class="mr-2x" style="width: 32px;">
    Courses
  </span>
  <svg class="programiz-icon programiz-icon--smallest navigation__node__icon">
    <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#chevron-down"></use>
  </svg>
</a>

                </div>
          
                        
    
    
    
    <form action="/python-programming/examples/calculator" method="post" id="search-api-page-search-form-simplest-programming-tutorials-f" accept-charset="UTF-8"><div><div class="search-input search-api-page-search-form-simplest-programming-tutorials-f"><button type="submit" class="search-input__form-submit" hidden></button><button type='\"button\"' class="search-input__clear btn"><svg class="programiz-icon"><use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#x"></use></svg></button><button type='\"button\"' class="btn btn--clear c-default"><svg class="programiz-icon programiz-icon--small search-input__icon"><use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#search"></use></svg></button><input type="text" value="" placeholder="Search tutorials &amp; examples" id="edit-keys-2" name="keys_2" class="search-input__control" autocomplete="off"><input type="hidden" name="id" value="2"><input type="hidden" name="form_build_id" value="form-2n1XPDNYeRezVFBENGUfcocq6MmOTCV5LNJWAXm9H2k"><input type="hidden" name="form_id" value="search_api_page_search_form_simplest_programming_tutorials_f"></div></div></form>
    
    
    
    
    
<div class="get-app-link-wrapper animated get-app-link-wrapper--closed-state" style="display: flex;">
  <a class="get-app-link" href="https://programiz.pro/learn/master-python" target="_blank" rel="nofollow" title="Try Programiz PRO">
    <p class="app-link-items app-text app-link-items--closed-state"><span>Try </span>Programiz PRO</p>
  </a>
</div>
              
        </div>
      </div>

      <!-- Only on page.tpl.php -->
      <!-- Show progress bar as the user scrolls the page for tutorials, examples and methods individual pages -->
      <div class="main-nav__progress-bar-wrapper">
        <div class="progress-bar"></div>
      </div>
    </nav>
  </header>

  <!-- Tutorials and Examples contents -->
  <div class="sub-menu--backdrop"></div>
        
    
    
    
    
<!-- Mobile view -->
<div class="sub-menu sub-menu--sp sub-menu--sp--tutorial-examples sub-menu__mobile-head-wrap">
  <div class="sub-menu__wrap">
    <div class="sub-menu__head">
      <div class="sub-menu__tab">
        <div class="sub-menu__tab__head">
                    <button class="sub-menu__tab__node sub-menu__tab__node--explore">
            Tutorials
          </button>
          <button class="sub-menu__tab__node sub-menu__tab__node--courses">
            Courses
          </button>
        </div>
                <div class="sub-menu__tab__body sub-menu__tab__body--explore">
                      <a href="javascript:void(0);" title="Python" class="sub-menu__tab__list-node sub-menu__tab__list-node--active" data-language="python">Python</a>
                      <a href="javascript:void(0);" title="JavaScript" class="sub-menu__tab__list-node " data-language="javascript">JavaScript</a>
                      <a href="javascript:void(0);" title="SQL" class="sub-menu__tab__list-node " data-language="sql">SQL</a>
                      <a href="javascript:void(0);" title="HTML" class="sub-menu__tab__list-node " data-language="html">HTML</a>
                      <a href="javascript:void(0);" title="CSS" class="sub-menu__tab__list-node " data-language="css">CSS</a>
                      <a href="javascript:void(0);" title="R" class="sub-menu__tab__list-node " data-language="r">R</a>
                      <a href="javascript:void(0);" title="C" class="sub-menu__tab__list-node " data-language="c">C</a>
                      <a href="javascript:void(0);" title="C++" class="sub-menu__tab__list-node " data-language="cpp">C++</a>
                      <a href="javascript:void(0);" title="Java" class="sub-menu__tab__list-node " data-language="java">Java</a>
                      <a href="javascript:void(0);" title="RUST" class="sub-menu__tab__list-node " data-language="rust">RUST</a>
                      <a href="javascript:void(0);" title="Golang" class="sub-menu__tab__list-node " data-language="golang">Golang</a>
                      <a href="javascript:void(0);" title="Kotlin" class="sub-menu__tab__list-node " data-language="kotlin">Kotlin</a>
                      <a href="javascript:void(0);" title="Swift" class="sub-menu__tab__list-node " data-language="swift">Swift</a>
                      <a href="javascript:void(0);" title="C#" class="sub-menu__tab__list-node " data-language="csharp">C#</a>
                      <a href="javascript:void(0);" title="DSA" class="sub-menu__tab__list-node " data-language="dsa">DSA</a>
                  </div>
        <div class="sub-menu__tab__body sub-menu__tab__body--courses d-none"></div>
      </div>

      <button class="btn btn--skeleton menu-hide-trigger">
        <svg class="programiz-icon">
          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#x"></use>
        </svg>
      </button>
    </div>

    <div class="tabbed-content tabbed-content--no-border">
      
      <div class="tabbed-content__right tabbed-content__right--explore">
        <!-- PRO - Banner -->
                  <div class="sub-menu__cta sub-menu__mobile-banner">
            <div class="d-flex sub-menu--mobile-banner">
              <p class="body16-font-size font-weight-600">Learn Python practically <br>
                and <span class="get-certified-text">Get Certified</span>.</p>
              <a class="pro-link pro-link--mobile-pro-link body14-font-size" href="https://programiz.pro/learn/master-python" target="_blank">ENROLL</a>
            </div>
          </div>
                <div class="sub-menu__contents sub-menu--mobile sub-menu__contents--python" id="m-python">
          <div class="sub-menu__links">
            <!-- Popular tutorials -->
                          <div class="sub-menu__links__column sub-menu__links__column--left">
                <h4 class="sub-menu__links__column__title">Popular Tutorials</h4>
                <div class="sub-menu__link">
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Getting Started With Python" href="/python-programming/getting-started" class="sub-menu__link__column">Getting Started With Python</a>
                      </div>
                    </div>
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Python if Statement" href="/python-programming/if-elif-else" class="sub-menu__link__column">Python if Statement</a>
                      </div>
                    </div>
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="while Loop in Python" href="/python-programming/while-loop" class="sub-menu__link__column">while Loop in Python</a>
                      </div>
                    </div>
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Python Lists" href="/python-programming/list" class="sub-menu__link__column">Python Lists</a>
                      </div>
                    </div>
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Dictionaries in Python" href="/python-programming/dictionary" class="sub-menu__link__column">Dictionaries in Python</a>
                      </div>
                    </div>
                                  </div>
                <a title="Python Tutorials" href="/python-programming" class="d-flex align-items-center font-weight-500">
                  Start Learning Python                  <svg class="programiz-icon programiz-icon--small ml-2x">
                    <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                    </use>
                  </svg>
                </a>
              </div>
            
            <!-- Popular examples -->
                          <div class="sub-menu__links__column sub-menu__links__column--left">
                <h4 class="sub-menu__links__column__title">Popular Examples</h4>
                <div class="sub-menu__link">
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Add two numbers" href="/python-programming/examples/add-number" class="sub-menu__link__column">Add two numbers</a>
                      </div>
                    </div>
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Check prime number" href="/python-programming/examples/prime-number" class="sub-menu__link__column">Check prime number</a>
                      </div>
                    </div>
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Find the factorial of a number" href="/python-programming/examples/factorial" class="sub-menu__link__column">Find the factorial of a number</a>
                      </div>
                    </div>
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Print the Fibonacci sequence" href="/python-programming/examples/fibonacci-sequence" class="sub-menu__link__column">Print the Fibonacci sequence</a>
                      </div>
                    </div>
                                      <div class="sub-menu__link__row">
                      <div class="sub-menu__link__column">
                        <a title="Check leap year" href="/python-programming/examples/leap-year" class="sub-menu__link__column">Check leap year</a>
                      </div>
                    </div>
                                  </div>
                <a title="Python Examples" href="/python-programming/examples" class="d-flex align-items-center font-weight-500">
                  Explore Python Examples
                  <svg class="programiz-icon programiz-icon--small ml-2x">
                    <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                    </use>
                  </svg>
                </a>
              </div>
            
            <!-- Reference materials -->
                          <div class="sub-menu__links__column sub-menu__links__column--right">
                <h4 class="sub-menu__links__column__title">Reference Materials</h4>
                <div class="sub-menu__link">
                                      <div class="sub-menu__link__row">
                      <a href="/python-programming/methods/built-in" title="Built-in Functions" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                        Built-in Functions                        <svg class="programiz-icon programiz-icon--small ml-auto">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                          </use>
                        </svg>
                      </a>
                    </div>
                                      <div class="sub-menu__link__row">
                      <a href="/python-programming/methods/list" title="List Methods" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                        List Methods                        <svg class="programiz-icon programiz-icon--small ml-auto">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                          </use>
                        </svg>
                      </a>
                    </div>
                                      <div class="sub-menu__link__row">
                      <a href="/python-programming/methods/dictionary" title="Dictionary Methods" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                        Dictionary Methods                        <svg class="programiz-icon programiz-icon--small ml-auto">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                          </use>
                        </svg>
                      </a>
                    </div>
                                      <div class="sub-menu__link__row">
                      <a href="/python-programming/methods/string" title="String Methods" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                        String Methods                        <svg class="programiz-icon programiz-icon--small ml-auto">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                          </use>
                        </svg>
                      </a>
                    </div>
                  
                  <a title="Python References" href="/python-programming/methods" class="d-flex align-items-center font-weight-500">
                    View all
                    <svg class="programiz-icon programiz-icon--small ml-2x">
                      <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                      </use>
                    </svg>
                  </a>
                </div>
              </div>
                      </div>
        </div>
      </div>

      <div class="tabbed-content__right tabbed-content__right--courses">
        <div class="sub-menu__contents sub-menu--mobile sub-menu__contents--courses px-6x" id="m-courses">
          <!-- Logo -->
          <div class="d-flex flex-column mb-2x" style="gap: 4px">
            <img src="/sites/all/themes/programiz/assets/pro-images/programiz-pro-logo.svg" alt="Programiz Pro Logo" style="width: 112px;">
            <p class="mb-2x" style="font-size: 14px;font-weight: 500;line-height: 20px;">Created with over a decade of experience.</p>
          </div>

          <!-- Tab Headers -->
          <div class="tabs">
            <ul class="tabs-list">
                              <li>
                  <a href="javascript:void(0);" title="Learn" class="tab-header tab-header--active" data-type="courses" data-tab="#pro-courses">Learn</a>
                </li>
                              <li>
                  <a href="javascript:void(0);" title="Practice" class="tab-header " data-type="practices" data-tab="#pro-practices">Practice</a>
                </li>
                              <li>
                  <a href="javascript:void(0);" title="Compete" class="tab-header " data-type="challenges" data-tab="#pro-challenges">Compete</a>
                </li>
                          </ul>

            <!-- Tab contents -->
            <div>
                              <div id="pro-courses" class="sub-menu__contents sub-menu__contents--courses tab-content">
                  <div class="sub-menu__links">
                    <!-- Left Panel -->
                    <div class="sub-menu__links__column sub-menu__links__column--left">
                      <div class="sub-menu__link">
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Learn Python" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Learn Python                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Learn HTML" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Learn HTML                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Learn JavaScript" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Learn JavaScript                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Learn SQL" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Learn SQL                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Learn DSA" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Learn DSA                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Learn C" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Learn C                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Learn C++" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Learn C++                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Learn Java" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Learn Java                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                              </div>

                      <a title="View all Courses on PRO" href="https://programiz.pro/courses" class="d-flex align-items-center" style="font-size: 14px;font-weight: 500;line-height: 20px;">
                        View all Courses on
                        <img src="/sites/all/themes/programiz/assets/programiz-pro-mini-logo.svg" alt="Programiz Pro Logo" class="ml-1x" style="width: 32px;">
                        <svg class="programiz-icon programiz-icon--small ml-2x">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                          </use>
                        </svg>
                      </a>
                    </div>
                  </div>
                </div>
                              <div id="pro-practices" class="sub-menu__contents sub-menu__contents--practices tab-content">
                  <div class="sub-menu__links">
                    <!-- Left Panel -->
                    <div class="sub-menu__links__column sub-menu__links__column--left">
                      <div class="sub-menu__link">
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Python Basics" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Python Basics                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Python Intermediate" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Python Intermediate                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="C++ Basics" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                C++ Basics                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="C++ Intermediate" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                C++ Intermediate                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="C++ OOP" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                C++ OOP                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="C Programming" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                C Programming                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Java Basics" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Java Basics                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Java Intermediate" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Java Intermediate                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Java OOP" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Java OOP                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                              </div>

                      <a title="View all Courses on PRO" href="https://programiz.pro/courses" class="d-flex align-items-center" style="font-size: 14px;font-weight: 500;line-height: 20px;">
                        View all Courses on
                        <img src="/sites/all/themes/programiz/assets/programiz-pro-mini-logo.svg" alt="Programiz Pro Logo" class="ml-1x" style="width: 32px;">
                        <svg class="programiz-icon programiz-icon--small ml-2x">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                          </use>
                        </svg>
                      </a>
                    </div>
                  </div>
                </div>
                              <div id="pro-challenges" class="sub-menu__contents sub-menu__contents--challenges tab-content">
                  <div class="sub-menu__links">
                    <!-- Left Panel -->
                    <div class="sub-menu__links__column sub-menu__links__column--left">
                      <div class="sub-menu__link">
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Python Challenges" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Python Challenges                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="JavaScript Challenges" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                JavaScript Challenges                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Java Challenges" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                Java Challenges                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="C++ Challenges" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                C++ Challenges                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="C Challenges" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                                C Challenges                                <svg class="programiz-icon programiz-icon--small ml-auto">
                                  <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                  </use>
                                </svg>
                              </a>
                            </div>
                          </div>
                                              </div>

                      <a title="View all Challenges on PRO" href="https://programiz.pro/community-challenges" class="d-flex align-items-center" style="font-size: 14px;font-weight: 500;line-height: 20px;">
                        View all Challenges on
                        <img src="/sites/all/themes/programiz/assets/programiz-pro-mini-logo.svg" alt="Programiz Pro Logo" class="ml-1x" style="width: 32px;">
                        <svg class="programiz-icon programiz-icon--small ml-2x">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                          </use>
                        </svg>
                      </a>
                    </div>
                  </div>
                </div>
                          </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- PRO for Desktop -->
<div class="sub-menu sub-menu--pc sub-menu--pc--pro">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-sm-10">
        <div class="sub-menu__wrap">
          <div class="tabbed-content tabbed-content--no-border">
            <div class="tabbed-content__left tabbed-content__left--small">
              <div class="tabbed-link-container">
                                  <div class="tabbed-link">
                    <a href="javascript:void(0);" class="d-flex tabbed-link__node tabbed-link__node--active" data-type="courses">
                      <span>
                        Learn                      </span>
                    </a>
                  </div>
                                  <div class="tabbed-link">
                    <a href="javascript:void(0);" class="d-flex tabbed-link__node " data-type="practices">
                      <span>
                        Practice                      </span>
                    </a>
                  </div>
                                  <div class="tabbed-link">
                    <a href="javascript:void(0);" class="d-flex tabbed-link__node " data-type="challenges">
                      <span>
                        Compete                      </span>
                    </a>
                  </div>
                              </div>
            </div>

            <div class="tabbed-content__right">
                            <div class="sub-menu__contents sub-menu__contents--courses" id="t-courses">
                <div class="sub-menu__cta mb-0x" style="flex-wrap: nowrap;">
                  <div style="flex-grow: 1;">
                    <h4>Certification Courses</h4>
                    <p class="mb-4x">Created with over a decade of experience and thousands of feedback.</p>
                  </div>
                  <button class="btn btn--skeleton">
                    <svg class="programiz-icon">
                      <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#x"></use>
                    </svg>
                  </button>
                </div>
                <div class="sub-menu__links">
                  <!-- Left Panel -->
                  <div class="sub-menu__links__column sub-menu__links__column--left">
                    <div class="sub-menu__link">
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Learn Python" href="https://programiz.pro/learn/master-python" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              Learn Python                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                        </div>
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Learn HTML" href="https://programiz.pro/course/learn-html" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              Learn HTML                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                        </div>
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Learn JavaScript" href="https://programiz.pro/learn/master-javascript" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              Learn JavaScript                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                        </div>
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Learn SQL" href="https://programiz.pro/course/learn-sql-basics" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              Learn SQL                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                        </div>
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Learn DSA" href="https://programiz.pro/course/dsa-with-python" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              Learn DSA                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                        </div>
                                          </div>

                    <a title="View all Courses on PRO" href="https://programiz.pro/courses" class="d-flex align-items-center font-weight-500">
                      View all Courses on
                      <img src="/sites/all/themes/programiz/assets/programiz-pro-mini-logo.svg" alt="Programiz Pro Logo" class="ml-1x" style="width: 32px;">
                      <svg class="programiz-icon programiz-icon--small ml-2x">
                        <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                        </use>
                      </svg>
                    </a>
                  </div>

                  <!-- Right Panel -->
                  <div class="sub-menu__links__column sub-menu__links__column--right">
                    <div class="sub-menu__link">
                                              <div class="sub-menu__link__row">
                          <a title="Learn C" href="https://programiz.pro/learn/master-c-programming" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                            Learn C                            <svg class="programiz-icon programiz-icon--small ml-auto">
                              <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                              </use>
                            </svg>
                          </a>
                        </div>
                                              <div class="sub-menu__link__row">
                          <a title="Learn C++" href="https://programiz.pro/learn/master-cpp" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                            Learn C++                            <svg class="programiz-icon programiz-icon--small ml-auto">
                              <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                              </use>
                            </svg>
                          </a>
                        </div>
                                              <div class="sub-menu__link__row">
                          <a title="Learn Java" href="https://programiz.pro/learn/master-java" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                            Learn Java                            <svg class="programiz-icon programiz-icon--small ml-auto">
                              <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                              </use>
                            </svg>
                          </a>
                        </div>
                                          </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Desktop view -->
<div class="sub-menu sub-menu--pc sub-menu--pc--tutorial">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-sm-10">
        <div class="sub-menu__wrap">
          <div class="tabbed-content tabbed-content--no-border">
            <div class="tabbed-content__left tabbed-content__left--small">
              <div class="tabbed-link-container">
                
                                      <div class="tabbed-link">
                      <a title="Python" href="javascript:void(0);" class="d-flex tabbed-link__node tabbed-link__node--active" data-language="python">
                        <span>
                          Python                        </span>
                      </a>
                    </div>

                                  
                                      <div class="tabbed-link">
                      <a title="JavaScript" href="javascript:void(0);" class="d-flex tabbed-link__node " data-language="javascript">
                        <span>
                          JavaScript                        </span>
                      </a>
                    </div>

                                  
                                      <div class="tabbed-link">
                      <a title="SQL" href="javascript:void(0);" class="d-flex tabbed-link__node " data-language="sql">
                        <span>
                          SQL                        </span>
                      </a>
                    </div>

                                  
                                      <div class="tabbed-link">
                      <a title="HTML" href="javascript:void(0);" class="d-flex tabbed-link__node " data-language="html">
                        <span>
                          HTML                        </span>
                      </a>
                    </div>

                                  
                                      <div class="tabbed-link">
                      <a title="CSS" href="javascript:void(0);" class="d-flex tabbed-link__node " data-language="css">
                        <span>
                          CSS                        </span>
                      </a>
                    </div>

                                  
                                      <div class="tabbed-link">
                      <a title="R" href="javascript:void(0);" class="d-flex tabbed-link__node " data-language="r">
                        <span>
                          R                        </span>
                      </a>
                    </div>

                                  
                                      <div class="tabbed-link">
                      <a title="C" href="javascript:void(0);" class="d-flex tabbed-link__node " data-language="c">
                        <span>
                          C                        </span>
                      </a>
                    </div>

                                  
                                      <div class="tabbed-link">
                      <a title="C++" href="javascript:void(0);" class="d-flex tabbed-link__node " data-language="cpp">
                        <span>
                          C++                        </span>
                      </a>
                    </div>

                                  
                                      <div class="tabbed-link">
                      <a title="Java" href="javascript:void(0);" class="d-flex tabbed-link__node " data-language="java">
                        <span>
                          Java                        </span>
                      </a>
                    </div>

                                  
                                  
                                  
                                  
                                  
                                  
                                                  <div class="tabbed-link">
                  <a title="More languages" href="javascript:void(0);" class="d-flex tabbed-link__node" data-language="more-language">
                    <span>
                      More languages
                    </span>
                  </a>
                </div>
              </div>
            </div>

            <div class="tabbed-content__right">
              <div class="sub-menu__contents sub-menu__contents--python" id="t-python">
                <!-- PRO - Banner -->
                                  <div class="sub-menu__cta">
                    <div class="d-flex sub-menu--desktop-banner">
                      <h3 class="h3-font">Learn Python practically <br>
                        and <span class="get-certified-text">Get Certified</span>.</h3>
                      <a class="pro-link body14-font-size font-weight-700" href="https://programiz.pro/learn/master-python" target="_blank">Try Programiz PRO!</a>
                    </div>
                    <button class="btn btn--skeleton">
                      <svg class="programiz-icon">
                        <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#x"></use>
                      </svg>
                    </button>
                  </div>

                
                <div class="sub-menu__links">
                  <!-- Popular tutorials -->
                                      <div class="sub-menu__links__column sub-menu__links__column--left">
                      <h4 class="sub-menu__links__column__title">Popular Tutorials</h4>
                      <div class="sub-menu__link">
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Getting Started With Python" href="/python-programming/getting-started" class="sub-menu__link__column">Getting Started With Python</a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Python if Statement" href="/python-programming/if-elif-else" class="sub-menu__link__column">Python if Statement</a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="while Loop in Python" href="/python-programming/while-loop" class="sub-menu__link__column">while Loop in Python</a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Python Lists" href="/python-programming/list" class="sub-menu__link__column">Python Lists</a>
                            </div>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <div class="sub-menu__link__column">
                              <a title="Dictionaries in Python" href="/python-programming/dictionary" class="sub-menu__link__column">Dictionaries in Python</a>
                            </div>
                          </div>
                                              </div>
                      <a title="Python tutorials" href="/python-programming" class="d-flex align-items-center font-weight-500 d-lg-none">
                        Start Learning Python                        <svg class="programiz-icon programiz-icon--small ml-2x">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right"></use>
                        </svg>
                      </a>
                      <a title="All Python tutorials" href="/python-programming" class="d-flex align-items-center font-weight-600 article-font-size sub-menu-all-tutorials-link">
                        <span>
                          All Python Tutorials
                        </span>
                        <svg class="programiz-icon programiz-icon--medium">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right"></use>
                        </svg>

                      </a>
                      <!-- <a title="Python tutorials" href="/python-programming" class="d-flex align-items-center font-weight-500">
                        View all tutorials
                        <svg class="programiz-icon programiz-icon--small ml-2x">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                          </use>
                        </svg>
                      </a> -->
                    </div>
                  
                  <!-- Reference materials -->
                                      <div class="sub-menu__links__column sub-menu__links__column--right">
                      <h4 class="sub-menu__links__column__title">Reference Materials</h4>
                      <div class="sub-menu__link">
                        
                                                  <div class="sub-menu__link__row">
                            <a title="Built-in Functions" href="/python-programming/methods/built-in" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              Built-in Functions                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <a title="List Methods" href="/python-programming/methods/list" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              List Methods                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <a title="Dictionary Methods" href="/python-programming/methods/dictionary" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              Dictionary Methods                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                                                  <div class="sub-menu__link__row">
                            <a title="String Methods" href="/python-programming/methods/string" class="btn btn--gray btn--small btn--block d-flex align-items-center">
                              String Methods                              <svg class="programiz-icon programiz-icon--small ml-auto">
                                <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right">
                                </use>
                              </svg>
                            </a>
                          </div>
                                              </div>
                      <a title="Python References" href="/python-programming/methods" class="d-flex align-items-center font-weight-500">
                        View all
                        <svg class="programiz-icon programiz-icon--small ml-2x">
                          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right"></use>
                        </svg>
                      </a>
                    </div>
                                                    </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

      
        
    
    
    
    
<!-- Desktop view only -->
<div class="sub-menu sub-menu--pc sub-menu--pc--examples">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-sm-10">
        <div class="sub-menu__wrap">
          <div class="tabbed-content tabbed-content--no-border">
            <div class="tabbed-content__left tabbed-content__left--small">

              <div class="tabbed-link-container">
                                  <div class="tabbed-link">
                    <a title="Python" href="javascript:void(0);" class="tabbed-link__node tabbed-link__node--active" data-language="python">Python</a>
                  </div>
                                  <div class="tabbed-link">
                    <a title="JavaScript" href="javascript:void(0);" class="tabbed-link__node " data-language="javascript">JavaScript</a>
                  </div>
                                  <div class="tabbed-link">
                    <a title="R" href="javascript:void(0);" class="tabbed-link__node " data-language="r">R</a>
                  </div>
                                  <div class="tabbed-link">
                    <a title="C" href="javascript:void(0);" class="tabbed-link__node " data-language="c">C</a>
                  </div>
                                  <div class="tabbed-link">
                    <a title="C++" href="javascript:void(0);" class="tabbed-link__node " data-language="cpp">C++</a>
                  </div>
                                  <div class="tabbed-link">
                    <a title="Java" href="javascript:void(0);" class="tabbed-link__node " data-language="java">Java</a>
                  </div>
                                  <div class="tabbed-link">
                    <a title="Kotlin" href="javascript:void(0);" class="tabbed-link__node " data-language="kotlin">Kotlin</a>
                  </div>
                              </div>

            </div>
            <div class="tabbed-content__right">
              <div class="sub-menu__contents sub-menu__contents--python" id="examples-python">
                                  <div class="sub-menu__cta">
                    <div class="d-flex sub-menu--desktop-banner">
                      <p class="h3-font">Learn Python practically <br>
                        and <span class="get-certified-text">Get Certified</span>.</p>
                      <a class="pro-link body14-font-size font-weight-700" href="https://programiz.pro/learn/master-python" target="_blank">Try Programiz PRO!</a>
                    </div>
                    <button class="btn btn--skeleton">
                      <svg class="programiz-icon">
                        <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#x"></use>
                      </svg>
                    </button>
                  </div>
                

                <div class="sub-menu__links">
                  <div class="sub-menu__links__column sub-menu__links__column--left">
                    <h4 class="sub-menu__links__column__title">Popular Examples</h4>
                    <div class="sub-menu__link">
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Add two numbers" href="/python-programming/examples/add-number" class="sub-menu__link__column">Add two numbers</a>
                          </div>
                        </div>
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Check prime number" href="/python-programming/examples/prime-number" class="sub-menu__link__column">Check prime number</a>
                          </div>
                        </div>
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Find the factorial of a number" href="/python-programming/examples/factorial" class="sub-menu__link__column">Find the factorial of a number</a>
                          </div>
                        </div>
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Print the Fibonacci sequence" href="/python-programming/examples/fibonacci-sequence" class="sub-menu__link__column">Print the Fibonacci sequence</a>
                          </div>
                        </div>
                                              <div class="sub-menu__link__row">
                          <div class="sub-menu__link__column">
                            <a title="Check leap year" href="/python-programming/examples/leap-year" class="sub-menu__link__column">Check leap year</a>
                          </div>
                        </div>
                                          </div>
                    <a title="Python Examples" href="/python-programming/examples" class="align-items-center font-weight-600 article-font-size sub-menu-all-tutorials-link d-none d-lg-flex">
                      <span>
                        All Python Examples
                      </span>
                      <svg class="programiz-icon programiz-icon--small ml-2x">
                        <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#arrow-right"></use>
                      </svg>
                    </a>
                  </div>
                                  </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

      
  <div class="contents">
    <div class="container">

      
      <div class="row">
        <div class="col-sm-12 d-md-flex">

                      <div class="left-bar left-bar--large-r-margin d-none d-lg-block">
                
    
    
    
    <div class="view view-related-examples-c-cpp-python-r- view-id-related_examples_c_cpp_python_r_ view-display-id-block_2 views-sidebar view-dom-id-742e854d8ab29504f74a17e9a26839dc">
        
  
  
      <div class="view-content">
      <div class="card-alt mb-10x d-block mobile-sidebar-tab"><h3>Python Examples</h3><div class="list list--active-right">    <ul class="related-examples-list">          <li class="">  
  <div>        <span><a href="/python-programming/examples/power-anonymous">Display Powers of 2 Using Anonymous Function</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/examples/number-divisible">Find Numbers Divisible by Another Number</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/examples/conversion-binary-octal-hexadecimal">Convert Decimal to Binary, Octal and Hexadecimal</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/examples/ascii-character">Find ASCII Value of Character</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/examples/hcf">Find HCF or GCD</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/examples/lcm">Find LCM</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/examples/factor-number">Find the Factors of a Number</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/examples/calculator" class="active">Make a Simple Calculator</a></span>  </div></li>
      </ul></div></div>    </div>
  
  
  
  
  
  
</div>
    
    
    
    
    <style>
    .ad1 {display:none; }
    @media(min-width: 992px) { .ad1 {display: block; width: 300px; min-height: 170px; margin: 32px 0; text-align: center; } }
    </style>
    <div class="ad1">
    <!-- <div id='div-gpt-ad-Programizcom36792'></div> -->

    <div id="div-gpt-ad-Programizcom39462" style="margin: 0px auto; text-align: center;"></div>
    </div>
    
    
    
    
    <div class="view view-related-topics-sidebar-second-before-sticky-ad- view-id-related_topics_sidebar_second_before_sticky_ad_ view-display-id-block views-sidebar view-dom-id-621d627b16a87b0882ca28ca5eb1c7c5">
        
  
  
      <div class="view-content">
      <div class="card-alt mb-10x d-block mobile-sidebar-tab"><h3 class="grouped-card-title">Python Tutorials</h3><div class="list ">    <ul class="related-topic-list">          <li class="">  
  <div>        <span><a href="/python-programming/user-defined-function">Python User-defined Functions</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/looping-technique">Python Looping Techniques</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/numbers">Python Numbers, Type Conversion and Mathematics</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/input-output-import"> Python Basic Input and Output  </a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/fstring">Python f-string</a></span>  </div></li>
          <li class="">  
  <div>        <span><a href="/python-programming/methods/built-in/input">Python input()</a></span>  </div></li>
      </ul></div></div>    </div>
  
  
  
  
  
  
</div>
    
    
    
    
    <style>
    .ad2 {display:none; }
    @media(min-width: 992px) { .ad2 {display: block; max-width: 300px; height: 600px; margin: 32px auto; text-align: center;} }
    </style>
    
    <div class="ad2">
    <div id="div-gpt-ad-Programizcom36787">
    </div>
    </div>
                </div>
          
          <div class="right-bar">
                            
    
    
    
    <style>#carbonads{font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",Helvetica,Arial,sans-serif;--width:728px;--font-size:22px}#carbonads{display:block;overflow:hidden;max-width:var(--width);position:relative;background-color:#fcfcfc;border:solid 1px #eee;font-size:var(--font-size);box-sizing:border-box;margin:0}.detail #carbonads{margin-top:12px}#carbonads a{color:inherit;text-decoration:none}#carbonads a:hover{color:inherit}.carbon-wrap{display:flex;align-items:center}carbon-img{display:block;float:left;margin:0;max-width:var(--width);line-height:1}.carbon-img img{display:block;margin:0;width:auto}.carbon-text{display:block;float:left;padding:0 1em;line-height:1.35;max-width:calc(100% - 130px - 2em);text-align:left}.carbon-poweredby{display:block;position:absolute;bottom:0;right:0;padding:6px 10px;background:repeating-linear-gradient(-45deg,transparent,transparent 5px,hsla(0,0%,0%,.025) 5px,hsla(0,0%,0%,.025) 10px) hsla(203,11%,95%,.8);text-align:center;text-transform:uppercase;letter-spacing:.5px;font-weight:600;font-size:8px;border-top-left-radius:4px;line-height:1}@media only screen and (min-width:320px) and (max-width:759px){.carbon-text{font-size:14px}}</style>

<div id="carbon-block"></div>
    
    
    
    
    <style>
    #div-gpt-ad-Programizcom36791 {display: none; }
    #div-gpt-ad-Programizcom39106 {display: block;}
    @media(min-width: 992px) { #div-gpt-ad-Programizcom36791 {display: block;} #div-gpt-ad-Programizcom39106 {display: none;}}
    </style>
    
    <div id="div-gpt-ad-Programizcom36791" class="content-top-ad" style="height:90px; width:728px; margin-bottom: 24px;">
    </div>
    
<div id="div-gpt-ad-Programizcom39106" class="content-top-ad" style="height: 100px; margin-bottom: 24px; "></div>

                
            <div class="editor-contents">
                              <h1>Python Program to Make a Simple Calculator</h1>
              
              
                            <!--  <p class="editor-contents__short-description"></p> -->
              
              
              <p>To understand this example, you should have the knowledge of the following <a href="/python-programming" title="Python tutorial">Python programming</a> topics:</p><ul><li><a href="/python-programming/operators">Python Operators</a></li><li><a href="/python-programming/function">Python Functions</a></li><li><a href="/python-programming/function-argument">Python Function Arguments</a></li><li><a href="/python-programming/user-defined-function">Python User-defined Functions</a></li></ul><hr>
                                
    
    
    
    <div id="node-113" class="node node-python-example clearfix" about="/python-programming/examples/calculator" typeof="sioc:Item foaf:Document">

  
      <span property="dc:title" content="Python Program to Make a Simple Calculator" class="rdf-meta element-hidden"></span>
  
  <div class="content">
      <h2>Example: Simple Calculator by Using Functions</h2>

<pre class="python-exec">
<code># This function adds two numbers
def add(x, y):
    return x + y

# This function subtracts two numbers
def subtract(x, y):
    return x - y

# This function multiplies two numbers
def multiply(x, y):
    return x * y

# This function divides two numbers
def divide(x, y):
    return x / y


print("Select operation.")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

while True:
    # take input from the user
    choice = input("Enter choice(1/2/3/4): ")

    # check if choice is one of the four options
    if choice in ('1', '2', '3', '4'):
        try:
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))
        except ValueError:
            print("Invalid input. Please enter a number.")
            continue

        if choice == '1':
            print(num1, "+", num2, "=", add(num1, num2))

        elif choice == '2':
            print(num1, "-", num2, "=", subtract(num1, num2))

        elif choice == '3':
            print(num1, "*", num2, "=", multiply(num1, num2))

        elif choice == '4':
            print(num1, "/", num2, "=", divide(num1, num2))
        
        # check if user wants another calculation
        # break the while loop if answer is no
        next_calculation = input("Let's do next calculation? (yes/no): ")
        if next_calculation == "no":
          break
    else:
        print("Invalid Input")</code></pre>

<p><strong>Output</strong></p>

<pre>
<samp>Select operation.
1.Add
2.Subtract
3.Multiply
4.Divide
Enter choice(1/2/3/4): 3
Enter first number: 15
Enter second number: 14
15.0 * 14.0 = 210.0
Let's do next calculation? (yes/no): no</samp></pre>

<p>In this program, we ask the user to choose an operation. Options 1, 2, 3, and 4 are valid. If any other input is given, <samp>Invalid Input</samp> is displayed and the loop continues until a valid option is selected.</p>

<p>Two numbers are taken and an <code>if...elif...else</code> branching is used to execute a particular section. User-defined functions <code>add()</code>, <code>subtract()</code>, <code>multiply()</code> and <code>divide()</code> evaluate respective operations and display the output.</p>
<hr>
<p><strong>Also Read:</strong></p>
<ul>
    <li><a href="https://www.programiz.com/python-programming/if-elif-else" title="Python if else">Python if else</a></li>
    <li><a href="https://www.programiz.com/python-programming/while-loop" title=" Python while loop">Python while loop</a></li>

</ul>


  </div>

  
  
</div>

                  
                          </div>

                          <div class="block">
                  
    
    
    
    <style>
    #div-gpt-ad-Programizcom36790 {display:none; }
    #div-gpt-ad-Programizcom36794 {display: block; }
    @media(min-width: 992px) { #div-gpt-ad-Programizcom36790 {display: block;} #div-gpt-ad-Programizcom36794 {display: none; }}
    </style>
    
    <div id="div-gpt-ad-Programizcom36790" style=" margin: 32px 0 32px; height: 90px; width: 728px;">
    </div>
    
    <div id="div-gpt-ad-Programizcom36794" style="margin: 32px 0 32px; min-height: 250px;">
    </div>
    
    
    
    
    <section class="vote-share-wrapper">
    <div class="share-wrapper">
        <span>Share on:</span>
        <div class="share-buttons-container">
            <div class="social-button-individual"><a href="https://www.facebook.com/sharer/sharer.php?u=https://www.programiz.com/python-programming/examples/calculator"><svg width="32" height="32" viewbox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"> <circle cx="16" cy="16" r="15.3333" fill="white" stroke="#0556F3" stroke-width="1.33333"></circle> <path fill-rule="evenodd" clip-rule="evenodd" d="M18.9167 10.168H17.1667C15.5558 10.168 14.25 11.4738 14.25 13.0846V14.8346H12.5V17.168H14.25V21.8346H16.5833V17.168H18.3333L18.9167 14.8346H16.5833V13.0846C16.5833 12.7625 16.8445 12.5013 17.1667 12.5013H18.9167V10.168Z" stroke="#0556F3" stroke-width="1.16999" stroke-linecap="round" stroke-linejoin="round"></path> </svg></a></div>
            <div class="social-button-individual"><a href="https://twitter.com/intent/tweet?text=Check%20this%20amazing%20article%20on%20Python%20Program%20to%20Make%20a%20Simple%20Calculator:%20&amp;via=programiz&amp;url=https://www.programiz.com/python-programming/examples/calculator"><svg width="32" height="32" viewbox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"> <circle cx="16" cy="16" r="15.3333" fill="white" stroke="#0556F3" stroke-width="1.33333"></circle> <path fill-rule="evenodd" clip-rule="evenodd" d="M22.4167 10.7521C21.8581 11.1461 21.2396 11.4475 20.585 11.6446C19.8654 10.8171 18.7058 10.527 17.6813 10.918C16.6568 11.309 15.9853 12.2981 16 13.3946V13.9779C13.9179 14.0319 11.9471 13.0399 10.75 11.3354C10.75 11.3354 8.41671 16.5854 13.6667 18.9187C12.4653 19.7342 11.0342 20.1431 9.58337 20.0854C14.8334 23.0021 21.25 20.0854 21.25 13.3771C21.2495 13.2146 21.2339 13.0525 21.2034 12.8929C21.7987 12.3058 22.2189 11.5645 22.4167 10.7521Z" stroke="#0556F3" stroke-width="1.22222" stroke-linecap="round" stroke-linejoin="round"></path> </svg></a></div>
            <div class="social-button-individual"><a href="https://api.whatsapp.com//send?text=Check+this+amazing+article+on+Python%20Program%20to%20Make%20a%20Simple%20Calculator:+https://www.programiz.com/python-programming/examples/calculator"><svg width="32" height="32" viewbox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"> <circle cx="16" cy="16" r="15.3333" fill="white" stroke="#0556F3" stroke-width="1.33333"></circle> <path d="M21.0115 10.9885C19.7291 9.70613 18.0245 9 16.2108 9C16.2107 9 16.2103 9 16.2102 9C15.3132 9.00011 14.4391 9.17378 13.6122 9.51633C12.7853 9.85887 12.0445 10.3542 11.4101 10.9885C10.1278 12.2708 9.42169 13.9757 9.42169 15.7892C9.42169 16.8706 9.68263 17.9454 10.1771 18.9029L9.03589 22.163C8.95546 22.393 9.01239 22.6429 9.18479 22.8152C9.30538 22.9359 9.4641 23 9.62731 23C9.69727 23 9.76798 22.9883 9.83698 22.9641L13.0971 21.823C14.0546 22.3175 15.1294 22.5784 16.2108 22.5784C18.0243 22.5784 19.7291 21.8722 21.0115 20.5899C22.2938 19.3076 23 17.6027 23 15.7893C23 13.9757 22.2939 12.2708 21.0115 10.9885ZM20.4309 20.0093C19.3037 21.1366 17.8049 21.7572 16.2108 21.7572C15.2357 21.7572 14.2669 21.5161 13.4092 21.0596C13.2537 20.9769 13.0698 20.9627 12.9048 21.0205L9.94293 22.0571L10.9796 19.0952C11.0374 18.9299 11.0231 18.7461 10.9404 18.5907C10.484 17.7332 10.2428 16.7645 10.2428 15.7892C10.2428 14.1951 10.8635 12.6963 11.9907 11.5691C13.1178 10.4421 14.6164 9.82127 16.2103 9.82106H16.2108C17.805 9.82106 19.3037 10.4418 20.4309 11.5691C21.5582 12.6963 22.1789 14.195 22.1789 15.7892C22.1789 17.3833 21.5582 18.8821 20.4309 20.0093Z" fill="#0556F3" stroke="#0556F3" stroke-width="0.3"></path> <path d="M18.734 16.3976C18.4216 16.0853 17.9134 16.0853 17.6011 16.3976L17.2595 16.7392C16.4113 16.277 15.725 15.5906 15.2627 14.7424L15.6043 14.4009C15.9167 14.0885 15.9167 13.5803 15.6043 13.268L14.6838 12.3475C14.3715 12.0352 13.8633 12.0352 13.5509 12.3475L12.8146 13.0839C12.3928 13.5057 12.3717 14.2308 12.7553 15.1258C13.0883 15.9028 13.6978 16.7569 14.4714 17.5305C15.2451 18.3042 16.0991 18.9137 16.8762 19.2467C17.3014 19.4289 17.6882 19.5198 18.0224 19.5198C18.3916 19.5198 18.6967 19.4088 18.9181 19.1874L19.6545 18.4509V18.451C19.8058 18.2997 19.8891 18.0986 19.8891 17.8846C19.8891 17.6706 19.8058 17.4695 19.6545 17.3182L18.734 16.3976ZM18.3375 18.6068C18.2171 18.7272 17.8469 18.7693 17.1997 18.4921C16.5163 18.1992 15.7536 17.6515 15.0521 16.9499C14.3505 16.2484 13.8029 15.4857 13.51 14.8024C13.2326 14.1552 13.2748 13.7849 13.3952 13.6645L14.1175 12.9422L15.0096 13.8344L14.582 14.2621C14.3887 14.4554 14.342 14.7486 14.466 14.9917C15.0281 16.094 15.9079 16.9738 17.0102 17.536C17.2535 17.66 17.5466 17.6134 17.74 17.42L18.1675 16.9924L19.0597 17.8846L18.3375 18.6068Z" fill="#0556F3" stroke="#0556F3" stroke-width="0.3"></path> </svg></a></div>
            <div class="social-button-individual"><a href="https://www.linkedin.com/sharing/share-offsite/?url=https://www.programiz.com/python-programming/examples/calculator"><svg width="32" height="32" viewbox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"> <circle cx="16" cy="16" r="15.3333" fill="white" stroke="#0556F3" stroke-width="1.33333"></circle> <path d="M13.3748 14.5417V20.375C13.3748 20.4524 13.3441 20.5265 13.2894 20.5812C13.2347 20.6359 13.1605 20.6667 13.0832 20.6667H11.6248C11.5475 20.6667 11.4733 20.6359 11.4186 20.5812C11.3639 20.5265 11.3332 20.4524 11.3332 20.375V14.5417C11.3332 14.4643 11.3639 14.3901 11.4186 14.3354C11.4733 14.2807 11.5475 14.25 11.6248 14.25H13.0832C13.1605 14.25 13.2347 14.2807 13.2894 14.3354C13.3441 14.3901 13.3748 14.4643 13.3748 14.5417ZM21.2498 16.8225C21.2596 16.2095 21.0596 15.6115 20.683 15.1277C20.3063 14.644 19.7757 14.3034 19.179 14.1625C18.773 14.0751 18.352 14.0861 17.9511 14.1947C17.5502 14.3033 17.1812 14.5063 16.8748 14.7867V14.5417C16.8748 14.4643 16.8441 14.3901 16.7894 14.3354C16.7347 14.2807 16.6605 14.25 16.5832 14.25H15.1248C15.0475 14.25 14.9733 14.2807 14.9186 14.3354C14.8639 14.3901 14.8332 14.4643 14.8332 14.5417V20.375C14.8332 20.4524 14.8639 20.5265 14.9186 20.5812C14.9733 20.6359 15.0475 20.6667 15.1248 20.6667H16.5832C16.6605 20.6667 16.7347 20.6359 16.7894 20.5812C16.8441 20.5265 16.8748 20.4524 16.8748 20.375V17.085C16.8679 16.8012 16.9611 16.524 17.1382 16.3021C17.3153 16.0802 17.5649 15.9278 17.8432 15.8717C18.0121 15.8425 18.1854 15.8509 18.3507 15.8964C18.516 15.9418 18.6693 16.0231 18.7996 16.1345C18.93 16.2459 19.0341 16.3846 19.1047 16.5408C19.1754 16.697 19.2107 16.8669 19.2082 17.0383V20.375C19.2082 20.4524 19.2389 20.5265 19.2936 20.5812C19.3483 20.6359 19.4225 20.6667 19.4998 20.6667H20.9582C21.0355 20.6667 21.1097 20.6359 21.1644 20.5812C21.2191 20.5265 21.2498 20.4524 21.2498 20.375V16.8225ZM12.2082 10.75C11.9774 10.75 11.7519 10.8184 11.56 10.9466C11.3681 11.0748 11.2186 11.257 11.1303 11.4702C11.042 11.6834 11.0189 11.918 11.0639 12.1443C11.1089 12.3706 11.2201 12.5785 11.3832 12.7416C11.5464 12.9048 11.7543 13.0159 11.9806 13.0609C12.2069 13.1059 12.4415 13.0828 12.6546 12.9945C12.8678 12.9062 13.05 12.7567 13.1782 12.5648C13.3064 12.373 13.3748 12.1474 13.3748 11.9167C13.3748 11.6072 13.2519 11.3105 13.0331 11.0917C12.8143 10.8729 12.5176 10.75 12.2082 10.75Z" fill="#0556F3"></path> </svg></a></div>
        </div>
    </div>
    <div class="vote-wrapper">
        <span>Did you find this article helpful?</span>
        <div class="vote-container" data-nid="113">
            <div class="vote-up">
                <svg width="36" height="36" viewbox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M18 36C27.9411 36 36 27.9411 36 18C36 8.05887 27.9411 0 18 0C8.05887 0 0 8.05887 0 18C0 27.9411 8.05887 36 18 36Z" fill="#FFCC4D"></path>
                <path d="M18.0005 21.0014C14.3775 21.0014 11.9735 20.5794 9.00049 20.0014C8.32149 19.8704 7.00049 20.0014 7.00049 22.0014C7.00049 26.0014 11.5955 31.0014 18.0005 31.0014C24.4045 31.0014 29.0005 26.0014 29.0005 22.0014C29.0005 20.0014 27.6795 19.8694 27.0005 20.0014C24.0275 20.5794 21.6235 21.0014 18.0005 21.0014Z" fill="#664500"></path>
                <path d="M9.00049 22C9.00049 22 12.0005 23 18.0005 23C24.0005 23 27.0005 22 27.0005 22C27.0005 22 25.0005 26 18.0005 26C11.0005 26 9.00049 22 9.00049 22Z" fill="white"></path>
                <path d="M12.0017 17C13.3824 17 14.5017 15.433 14.5017 13.5C14.5017 11.567 13.3824 10 12.0017 10C10.621 10 9.50171 11.567 9.50171 13.5C9.50171 15.433 10.621 17 12.0017 17Z" fill="#664500"></path>
                <path d="M24.0002 17C25.381 17 26.5002 15.433 26.5002 13.5C26.5002 11.567 25.381 10 24.0002 10C22.6195 10 21.5002 11.567 21.5002 13.5C21.5002 15.433 22.6195 17 24.0002 17Z" fill="#664500"></path>
                </svg>
            </div>
            <div class="vote-down">
                <svg width="36" height="36" viewbox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M18 36C27.9411 36 36 27.9411 36 18C36 8.05887 27.9411 0 18 0C8.05887 0 0 8.05887 0 18C0 27.9411 8.05887 36 18 36Z" fill="#FFCC4D"></path>
                <path d="M25.4849 27.3751C25.4399 27.1961 24.3169 22.9961 17.9999 22.9961C11.6819 22.9961 10.5599 27.1961 10.5149 27.3751C10.4599 27.5921 10.5579 27.8171 10.7519 27.9291C10.9469 28.0401 11.1909 28.0071 11.3519 27.8521C11.3709 27.8331 13.3059 25.9961 17.9999 25.9961C22.6939 25.9961 24.6299 27.8331 24.6479 27.8511C24.7439 27.9461 24.8719 27.9961 24.9999 27.9961C25.0839 27.9961 25.1689 27.9751 25.2459 27.9321C25.4419 27.8201 25.5399 27.5931 25.4849 27.3751Z" fill="#664500"></path>
                <path d="M12.0024 17C13.3832 17 14.5024 15.433 14.5024 13.5C14.5024 11.567 13.3832 10 12.0024 10C10.6217 10 9.50244 11.567 9.50244 13.5C9.50244 15.433 10.6217 17 12.0024 17Z" fill="#664500"></path>
                <path d="M24.0005 17C25.3812 17 26.5005 15.433 26.5005 13.5C26.5005 11.567 25.3812 10 24.0005 10C22.6198 10 21.5005 11.567 21.5005 13.5C21.5005 15.433 22.6198 17 24.0005 17Z" fill="#664500"></path>
                </svg>
            </div>
        </div>
    </div>
        <div class="page-feedback-form" style="display: none;">
        <form class="webform-client-form webform-client-form-1680" action="/python-programming/examples/calculator" method="post" id="webform-client-form-1680" accept-charset="UTF-8"><div><div class="form-item webform-component webform-component-markup webform-component--page-feedback-header">
 <p class="font-weight-600" style="font-size: 18px;">Sorry about that.</p>
<label class="social-area__label" style="margin-top: 20px; font-size: 14px;">How can we improve it?</label>
</div>
<div class="rate-share-form"><div class="col-md-12"><div class="form"><div class="form-item webform-component webform-component-textarea webform-component--dislike-feedback">
  <label class="element-invisible" for="edit-submitted-dislike-feedback">Feedback <span class="form-required" title="This field is required.">*</span></label>
 <div class="form-textarea-wrapper resizable"><textarea required="required" placeholder="Enter your message..." class="form__control form__control--textarea form-textarea required" id="edit-submitted-dislike-feedback" name="submitted[dislike_feedback]" cols="60" rows="5"></textarea></div>
</div>
</div></div></div><input type="hidden" name="details[sid]">
<input type="hidden" name="details[page_num]" value="1">
<input type="hidden" name="details[page_count]" value="1">
<input type="hidden" name="details[finished]" value="0">
<input type="hidden" name="form_build_id" value="form-uV0pauoD7ackGcfqS6QtTU_7tX72i0nxzH8yC-QbpGw">
<input type="hidden" name="form_id" value="webform_client_form_1680">
<input type="hidden" name="honeypot_time" value="1745401089|bRreFQxdWoIIusP2K7ynNGVdHywI9zfeFb7JtAxb7CU">
<div class="phone-textfield"><div class="form-item form-type-textfield form-item-phone">
  <label for="edit-phone">Leave this field blank </label>
 <input autocomplete="off" type="text" id="edit-phone" name="phone" value="" size="20" maxlength="128" class="form-text">
</div>
</div><div class="captcha"><input type="hidden" name="captcha_sid" value="393760311">
<input type="hidden" name="captcha_token" value="14229d8f79e69903e90352bab4fbefc9">
<input type="hidden" name="captcha_response" value="Google no captcha">
<div class="g-recaptcha" data-sitekey="6LcpoEsUAAAAAP2oeouHeV70m85MUNlab8UrEqyL" data-theme="light" data-type="image"></div><noscript>
  <div style="width: 302px; height: 352px;">
    <div style="width: 302px; height: 352px; position: relative;">
      <div style="width: 302px; height: 352px; position: absolute;">
        <iframe src="https://www.google.com/recaptcha/api/fallback?k=6LcpoEsUAAAAAP2oeouHeV70m85MUNlab8UrEqyL&amp;hl=en" frameborder="0" scrolling="no" style="width: 302px; height:352px; border-style: none;"></iframe>
      </div>
      <div style="width: 250px; height: 80px; position: absolute; border-style: none; bottom: 21px; left: 25px; margin: 0px; padding: 0px; right: 25px;">
        <textarea id="g-recaptcha-response" name="g-recaptcha-response" class="g-recaptcha-response" style="width: 250px; height: 80px; border: 1px solid #c1c1c1; margin: 0px; padding: 0px; resize: none;" value=""></textarea>
      </div>
    </div>
  </div>
</noscript>
</div><div class="form-actions"><div><div class="d-flex justify-content-end"><input class="webform-submit button-primary btn btn-submit-feedback btn--medium btn--block-sp form-submit" type="submit" id="edit-submit" name="op" value="Submit Feedback"></div></div></div></div></form>    </div>
</section>
                  </div>
            
          </div>
        </div>
      </div>

                
    
    
    
    <style>
.programiz_bottom {
    background: #0556F3;
    color: white;
    border-radius: 4px;
    margin-top: 32px;
    margin-bottom: 32px;
}

.programiz_bottom--left {
    padding: 28px 20px;
}

.programiz_bottom--left p {
    margin-top: 12px;
    font-weight: 500;
    font-size: 20px;
    line-height: 1.5;
}

.programiz_bottom--left__button {
    background: white;
    text-decoration: none;
    color: #25265E;
    padding: 12px 0;
    margin-top: 24px;
    display: block;
    width: 180px;
    text-align: center;
    border-radius: 4px;
    font-weight: 500;
}

.programiz_bottom--left__button:hover {
    background: #F2F2F2;
}


.programiz_bottom--left__logo {
    background: url(/sites/tutorial2program/files/programiz_pro_logo_bottom.png) no-repeat;
    background-size: contain;
    background-position: center center;
    width: 124px;
    height: 42px;

}

.programiz_bottom--gap {
    display: none;
}
.programiz_bottom--right {
    display: none;
}

.programiz_bottom--left__invisible-inline,
.programiz_bottom--left__invisible-block
{
    display: none;
}

@media screen and (min-width: 768px) {

    .programiz_bottom--left__logo {
        width: 180px;
        height: 62px;
    }
    .programiz_bottom--left {
        padding: 32px 24px;
    }

    .programiz_bottom--left__invisible-block {
        display: block;
    }
}

@media screen and (min-width: 992px) {
    .programiz_bottom--left {
        padding: 36px 28px;
    }

    .programiz_bottom--left__invisible-inline {
        display: inline;
    }
}

@media screen and (min-width: 1160px) {

    .programiz_bottom--left__logo {
        width: 229px;
        height: 78px;
    }

    .programiz_bottom {
        width: 1140px;
        height: 352px;
        display: flex;
        border-radius: 6px;
        margin-bottom: 40px;
    }

    .programiz_bottom--left {
        width: 660px;
        padding: 36px 88px 44px 60px;
    }

    .programiz_bottom--left p {
        margin-top: 16px;
        font-weight: 500;
        font-size: 18px;
        line-height: 1.5;
    }

    .programiz_bottom--left__button {
        margin-bottom: 44px;
    }

    .programiz_bottom--right {
        position: relative;
        right: 100px;
        margin-top: 74px;
        margin-bottom: 48px;
        display: block;
    }
    
    .programiz_bottom--gap {
        width: 230px;
        display: block;
    }
    
    .programiz_bottom--gap__design {
        width: 24px;
        height: 100%;
        background: #7EAAFF;
        transform: skew(-33deg);
        position: relative;
    }
    
    .programiz_bottom--gap__design::before {
        content: '';
        position: absolute;
        width: 32px;
        height: 20px;
        background: #0556F3;
        right: -3px;
        top: 250px;
        transform: skew(-5deg, -18deg);
    }
    
    
    .programiz_bottom--right li {
        list-style: none;
        margin-bottom: 24px;
        margin-top: 16px;
        font-size: 18px;
    }
    
    .programiz_bottom--right li span {
        position: relative;
        bottom: 5px;
        margin-left: 8px;
    }    
}
</style>

    <div class="programiz_bottom">

        <div class="programiz_bottom--left">
            <div class="programiz_bottom--left__logo">
            </div>
            <p>
                Our premium learning platform, created with over a decade of experience<span class="programiz_bottom--left__invisible-inline"> and thousands of feedbacks</span>.
            </p>
            <p class="programiz_bottom--left__invisible-block">
                Learn and improve your coding skills like never before.
            </p>

            <a href="https://programiz.pro/" class="programiz_bottom--left__button" rel="nofollow" title="Programiz PRO: Premimum Learning Platform from Programiz">Try Programiz PRO</a>        
        </div>

        <div class="programiz_bottom--gap">
            <div class="programiz_bottom--gap__design"></div>
        </div>

        <div class="programiz_bottom--right">
            <ul>
                <li>
                    <svg width="22" height="22" viewbox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect x="1.21353" y="0.838529" width="19.8851" height="19.8851" rx="1.55727" stroke="white" stroke-width="1.67706"></rect>
                    <path d="M9.35933 13.9257L6.21484 10.7812L9.35933 7.63672" stroke="white" stroke-width="1.67706" stroke-linecap="round" stroke-linejoin="round"></path>
                    <path d="M12.9532 13.9257L16.0977 10.7812L12.9532 7.63672" stroke="white" stroke-width="1.67706" stroke-linecap="round" stroke-linejoin="round"></path>
                    </svg> <span>Interactive Courses</span></li>
                <li>
                    <svg width="22" height="22" viewbox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M7.75287 12.4816L6.66553 20.6682L11.1587 17.9723L15.6519 20.6682L14.5645 12.4727" stroke="white" stroke-width="1.79727" stroke-linecap="round" stroke-linejoin="round"></path>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.1586 13.4793C14.6327 13.4793 17.449 10.663 17.449 7.18887C17.449 3.71476 14.6327 0.898438 11.1586 0.898438C7.68449 0.898438 4.86816 3.71476 4.86816 7.18887C4.86816 10.663 7.68449 13.4793 11.1586 13.4793Z" stroke="white" stroke-width="1.79727" stroke-linecap="round" stroke-linejoin="round"></path>
                    </svg> <span>Certificates</span></li>
                <li><svg width="22" height="22" viewbox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M13.3119 2.39453C12.7862 5.67399 12.3445 7.62349 11.1324 8.83554C9.92037 10.0476 7.97087 10.4893 4.69141 11.015C7.97087 11.5407 9.92037 11.9825 11.1324 13.1982C12.3445 14.4102 12.7862 16.3597 13.3119 19.6417C13.8376 16.3597 14.2794 14.4102 15.4914 13.1945C16.7071 11.9825 18.6566 11.5407 21.9386 11.015C18.6566 10.4893 16.7071 10.0476 15.4951 8.83554C14.2794 7.62349 13.8376 5.67399 13.3119 2.39453Z" fill="white"></path>
                    <path d="M3.61207 3.47266C3.4149 4.70264 3.24922 5.4338 2.79464 5.88839C2.34005 6.34297 1.60889 6.50865 0.378906 6.70582C1.60889 6.90299 2.34005 7.06867 2.79464 7.52462C3.24922 7.9792 3.4149 8.71037 3.61207 9.94131C3.80924 8.71037 3.97492 7.9792 4.4295 7.52325C4.88545 7.06867 5.61662 6.90299 6.84756 6.70582C5.61662 6.50865 4.88545 6.34297 4.43087 5.88839C3.97492 5.4338 3.80924 4.70264 3.61207 3.47266Z" fill="white"></path>
                    <path d="M6.84254 13.1738C6.64537 14.4038 6.47969 15.135 6.02511 15.5896C5.57052 16.0441 4.83935 16.2098 3.60938 16.407C4.83935 16.6042 5.57052 16.7698 6.02511 17.2258C6.47969 17.6804 6.64537 18.4115 6.84254 19.6425C7.03971 18.4115 7.20538 17.6804 7.65997 17.2244C8.11592 16.7698 8.84709 16.6042 10.078 16.407C8.84709 16.2098 8.11592 16.0441 7.66134 15.5896C7.20538 15.135 7.03971 14.4038 6.84254 13.1738Z" fill="white"></path>
                    </svg> <span>AI Help</span></li>
                <li>
                    <svg width="24" height="21" viewbox="0 0 24 21" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M10.967 0.399697C11.4559 0.14879 12.0357 0.148789 12.5246 0.399696L20.6663 4.57816C21.2354 4.8702 21.5932 5.45606 21.5932 6.09566V14.1197C21.5932 14.7593 21.2354 15.3452 20.6663 15.6372L12.5246 19.8157C12.0357 20.0666 11.4559 20.0666 10.967 19.8157L2.82527 15.6372C2.25623 15.3452 1.8984 14.7593 1.8984 14.1197V6.09566C1.8984 5.45606 2.25623 4.8702 2.82527 4.57816L10.967 0.399697Z" fill="white"></path>
                    <path d="M10.9717 0.87115C11.4582 0.623255 12.0339 0.623255 12.5204 0.87115L20.2395 4.80438C20.811 5.09558 21.1708 5.68275 21.1708 6.32414V13.8384C21.1708 14.4798 20.811 15.067 20.2395 15.3582L12.5204 19.2914C12.0339 19.5393 11.4582 19.5393 10.9717 19.2914L3.25259 15.3582C2.68111 15.067 2.3213 14.4798 2.3213 13.8384V6.32414C2.3213 5.68275 2.68111 5.09558 3.25259 4.80438L10.9717 0.87115Z" fill="white"></path>
                    <mask id="mask0_2731_20483" style="mask-type:alpha" maskunits="userSpaceOnUse" x="1" y="0" width="21" height="21">
                    <path d="M10.9676 0.399662C11.4564 0.148775 12.0363 0.148775 12.5251 0.399662L20.6673 4.57817C21.2364 4.87021 21.5942 5.45607 21.5942 6.09569V14.1197C21.5942 14.7593 21.2364 15.3452 20.6673 15.6372L12.5251 19.8157C12.0363 20.0666 11.4564 20.0666 10.9676 19.8157L2.82538 15.6372C2.25632 15.3452 1.89847 14.7593 1.89847 14.1197V6.09569C1.89847 5.45607 2.25632 4.87021 2.82538 4.57817L10.9676 0.399662Z" fill="url(#paint0_linear_2731_20483)"></path>
                    </mask>
                    <g mask="url(#mask0_2731_20483)">
                    <g filter="url(#filter0_f_2731_20483)">
                    <path d="M20.1701 0.273153L21.8635 1.77201L3.77629 17.7442L2.08289 16.2453L20.1701 0.273153Z" fill="#91A7F5"></path>
                    </g>
                    <g filter="url(#filter1_f_2731_20483)">
                    <path d="M21.8791 2.87282L22.5337 3.45223L6.22807 17.787L5.57345 17.2076L21.8791 2.87282Z" fill="#F0FFEE"></path>
                    </g>
                    </g>
                    <path d="M11.4099 2.30632C11.6234 2.19956 11.8746 2.19956 12.0881 2.30632L19.2722 5.89949C19.529 6.02792 19.6912 6.29039 19.6912 6.5775V13.5852C19.6912 13.8723 19.529 14.1348 19.2722 14.2632L12.0881 17.8564C11.8746 17.9632 11.6234 17.9632 11.4099 17.8564L4.22576 14.2632C3.96898 14.1348 3.80679 13.8723 3.80679 13.5852V6.5775C3.80679 6.29039 3.96898 6.02792 4.22576 5.89949L11.4099 2.30632Z" fill="#25265E" fill-opacity="0.67"></path>
                    <path d="M11.4148 3.48434C11.6255 3.38089 11.8723 3.38089 12.083 3.48434L18.2081 6.49159C18.4677 6.61901 18.6321 6.88296 18.6321 7.17208V12.9863C18.6321 13.2754 18.4677 13.5394 18.2081 13.6668L12.083 16.674C11.8723 16.7775 11.6255 16.7775 11.4148 16.674L5.28961 13.6668C5.03008 13.5394 4.86562 13.2754 4.86562 12.9863V7.17208C4.86562 6.88296 5.03008 6.61901 5.28961 6.49159L11.4148 3.48434Z" fill="white"></path>
                    <path d="M10.8741 10.312L12.4372 13.5156H11.2434L10.2041 11.0592L9.17348 13.5156H8.01398L9.5428 10.3549L8.14282 7.58074H9.33666L10.2213 9.65924L11.1403 7.58074H12.2912L10.8741 10.312ZM14.5563 7.58074C15.2949 7.58074 15.8589 7.74107 16.2483 8.06172C16.6433 8.37664 16.8409 8.84616 16.8409 9.47028C16.8409 10.123 16.6433 10.6155 16.2483 10.9476C15.8589 11.2739 15.3207 11.4371 14.6336 11.4371H14.1354V13.5156H13.0189V7.58074H14.5563ZM14.5648 10.604C14.9485 10.604 15.2319 10.521 15.4151 10.3549C15.5984 10.1832 15.69 9.88827 15.69 9.47028C15.69 9.0981 15.5984 8.82612 15.4151 8.65434C15.2319 8.48257 14.9485 8.39668 14.5648 8.39668H14.1354V10.604H14.5648Z" fill="#25265E"></path>
                    <defs>
                    <filter id="filter0_f_2731_20483" x="0.187806" y="-1.62176" width="23.5707" height="21.2611" filterunits="userSpaceOnUse" color-interpolation-filters="sRGB">
                    <feflood flood-opacity="0" result="BackgroundImageFix"></feflood>
                    <feblend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"></feblend>
                    <fegaussianblur stddeviation="0.947601" result="effect1_foregroundBlur_2731_20483"></fegaussianblur>
                    </filter>
                    <filter id="filter1_f_2731_20483" x="3.67804" y="0.977845" width="20.7509" height="18.7045" filterunits="userSpaceOnUse" color-interpolation-filters="sRGB">
                    <feflood flood-opacity="0" result="BackgroundImageFix"></feflood>
                    <feblend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"></feblend>
                    <fegaussianblur stddeviation="0.947601" result="effect1_foregroundBlur_2731_20483"></fegaussianblur>
                    </filter>
                    <lineargradient id="paint0_linear_2731_20483" x1="7.06943" y1="1.38573" x2="18.7934" y2="20.6899" gradientunits="userSpaceOnUse">
                    <stop stop-color="#FFE76A"></stop>
                    <stop offset="0.766563" stop-color="#E9B947"></stop>
                    <stop offset="1" stop-color="#E7BB40"></stop>
                    </lineargradient>
                    </defs>
                    </svg> <span>2000+ Challenges</span></li>
            </ul>
        </div>
    </div>
    
    
    
    
    <div class="view view-similar-python-programming-examples view-id-similar_python_programming_examples view-display-id-block above-bottom-recommended-articles view-dom-id-30e178bbf46ca051c961f8a55a087a82">
        
  
  
      <div class="view-content">
      <div class="row"><div class="col-sm-12"><h3 class="grouped-card-title">Related Examples</h3></div><div class="col-md-6 col-lg-3"><a href="/python-programming/examples/largest-number-three"> <div class="card card--even-spaced card--examples card--examples--blue card--examples--1"><p class="card__title">Python Example</p><p class="card__description">Find the Largest Among Three Numbers</p></div></a></div><div class="col-md-6 col-lg-3"><a href="/python-programming/examples/add-number"> <div class="card card--even-spaced card--examples card--examples--blue card--examples--2"><p class="card__title">Python Example</p><p class="card__description">Add Two Numbers</p></div></a></div><div class="col-md-6 col-lg-3"><a href="/python-programming/examples/lcm"> <div class="card card--even-spaced card--examples card--examples--blue card--examples--3"><p class="card__title">Python Example</p><p class="card__description">Find LCM</p></div></a></div><div class="col-md-6 col-lg-3"><a href="/python-programming/user-defined-function"> <div class="card card--even-spaced card--examples card--examples--blue card--examples--4"><p class="card__title">Python Tutorial</p><p class="card__description">Python User-defined Functions</p></div></a></div></div></div>    </div>
  
  
  
  
  
  
</div>
          
      <!-- Get app link -->
                    
    </div>
  

      <footer class="footer">
        
    
    
    
    <style>
  .footer__columns {
    width: 100%;
    display: flex;
    flex-direction: row;
    gap: 12px 24px;
    justify-content: space-between;
    flex-wrap: wrap;
  }

  .footer__columns__item {
    flex-grow: 1;
  }

  .footer__link-area .footer__link-area__title {
    font-size: 22px;
    line-height: 30px;
    font-weight: 600;
    margin-bottom: 20px;
  }

  .footer__links__nodes .link-node {
    font-weight: 500;
  }

  .footer__end {
    margin-top: 24px;
  }

  .footer__end .copyright-text {
    font-weight: 500;
  }

  /* Media query */
  @media (min-width: 992px) {
    .footer__end {
      margin-top: 48px;
    }
  }
</style>

<div class="container">
  <div class="footer__columns">
    <div class="footer__column__item">
      <div class="footer__link-area">
        <h4 class="footer__link-area__title">Free Tutorials</h4>

        <ul class="footer__links">
          <li class="footer__links__nodes">
            <a class="link-node" href="/python-programming" title="Python 3 Tutorials">Python 3 Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/sql" title="SQL Tutorials">SQL Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/r" title="R Tutorials">R Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/html" title="HTML Tutorials">HTML Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/css" title="CSS Tutorials">CSS Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/javascript" title="JavaScript Tutorials">JavaScript Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/java-programming" title="Java Tutorials">Java Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/c-programming" title="C Tutorials">C Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/cpp-programming" title="C++ Tutorials">C++ Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/dsa" title="Data Structures and Algorithms">DSA Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/csharp-programming" title="C# Tutorials">C# Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/golang" title="Golang Tutorials">Golang Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/kotlin-programming" title="Kotlin Tutorials">Kotlin Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/swift-programming" title="Swift Tutorials">Swift Tutorials</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/rust" title="Rust Tutorials">Rust Tutorials</a>
          </li>

        </ul>
      </div>
    </div>

    <div class="footer__column__item">
      <div class="footer__link-area">
        <h4 class="footer__link-area__title">Paid Courses</h4>

        <ul class="footer__links">
          <li class="footer__links__nodes">
            <a class="link-node" href="https://programiz.pro/learn/master-python" title="Master Python" target="_blank">Master Python</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="https://programiz.pro/course/learn-sql-basics" title="Learn SQL" target="_blank">Learn SQL</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="https://programiz.pro/course/learn-html" title="Learn HTML" target="_blank">
              Learn HTML
              <span class="badge ml-1x" style="background: #FFC33D;color: #25265EAB;padding: 2px 4px;border-radius: 2px;font-weight: 600;position: relative;bottom: 2px;">FREE</span>
            </a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="https://programiz.pro/learn/master-javascript" title="Master JavaScript" target="_blank">Master JavaScript</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="https://programiz.pro/learn/master-c-programming" title="Master C" target="_blank">Master C</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="https://programiz.pro/learn/master-cpp" title="Master C++" target="_blank">Master C++</a>
          </li>
            
          <li class="footer__links__nodes">
            <a class="link-node" href="https://programiz.pro/learn/master-java" title="Master Java" target="_blank">Master Java</a>
          </li>
          
          <li class="footer__links__nodes">
            <a class="link-node" href="https://programiz.pro/learn/master-dsa-with-python" title="Master DSA with Python" target="_blank">Master DSA with Python</a>
          </li>
        </ul>
      </div>
    </div>

    <div class="footer__column__item">
      <div class="footer__link-area">
        <h4 class="footer__link-area__title">Online Compilers</h4>

        <ul class="footer__links">
          <li class="footer__links__nodes">
            <a class="link-node" href="/python-programming/online-compiler" title="Python Compiler">Python Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/r/online-compiler" title="R Compiler">R Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/sql/online-compiler" title="SQL Editor">SQL Editor</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/html/online-compiler" title="HTML/CSS Editor">HTML/CSS Editor</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/javascript/online-compiler" title="JavaScript Editor">JavaScript Editor</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/java-programming/online-compiler" title="Java Compiler">Java Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/c-programming/online-compiler" title="C Compiler">C Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/cpp-programming/online-compiler" title="C++ Compiler">C++ Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/csharp-programming/online-compiler" title="C# Compiler">C# Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/golang/online-compiler" title="Go Compiler">Go Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/php/online-compiler" title="PHP Compiler">PHP Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/swift/online-compiler" title="Swift Compiler">Swift Compiler</a>
          </li>

          <li class="footer__links__nodes">
            <a class="link-node" href="/rust/online-compiler" title="Rust Compiler">Rust Compiler</a>
          </li>
        </ul>
      </div>
    </div>

    <div class="footer__column__item">
      <div class="footer__link-area">
        <h4 class="footer__link-area__title">Mobile Apps</h4>

        <ul class="footer__links">
          <li class="footer__links__nodes">
            <a class="link-node" href="/learn-python" title="Learn Python: Programiz" target="_blank">Learn Python App</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" href="/learn-c" title="Learn C Programming: Programiz" target="_blank">Learn C App</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" href="/learn-java" title="Learn Java: Programiz" target="_blank">Learn Java App</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" href="/learn-cpp" title="Learn C++: Programiz" target="_blank">Learn C++ App</a>
          </li>
        </ul>
      </div>
    </div>

    <div class="footer__column__item">
      <div class="footer__link-area">
        <h4 class="footer__link-area__title">Company</h4>

        <ul class="footer__links">
          <li class="footer__links__nodes">
            <a class="link-node" id="unic-gdpr" onclick='__tcfapi("openunic");return false;' style="display:none;cursor:pointer;">Change Ad Consent</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" id="unic-ccpa" onclick="window.__uspapi('openunic')" style="display:none;cursor:pointer;">Do not sell my data</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" href="/about-us" title="About us">About</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" href="/contact" title="Contact us">Contact</a>
          </li>
          <li class="footer__links__nodes">
            <a title="Blog" href="/blog" class="link-node">Blog</a>
          </li>
          <li class="footer__links__nodes">
            <a title="Programiz on Youtube" href="https://www.youtube.com/channel/UCREFp3D_n8JfcDonlm7Mpyw" class="link-node">Youtube</a>
          </li>
          <li class="footer__links__nodes">
            <a title="Careers" href="/careers" class="link-node">Careers</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" href="/advertise" title="Advertise with us">Advertising</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" href="/privacy-policy" title="Privacy Policy">Privacy Policy</a>
          </li>
          <li class="footer__links__nodes">
            <a class="link-node" href="/terms-of-use" title="Terms &amp; Conditions">Terms &amp; Conditions</a>
          </li>

      </ul></div>
    </div>
  </div>

  <div class="footer__end">
    <p class="copyright-text">© Parewa Labs Pvt. Ltd. All rights reserved.</p>

    <div class="social-icons">
      <a class="social-icons__links" href="https://www.facebook.com/programiz" title="Programiz on Facebook">
        <svg class="programiz-icon programiz-icon--small">
          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#facebook"></use>
        </svg>
      </a>
      <a class="social-icons__links" href="https://www.instagram.com/_programiz/" title="Programiz on Instagram">
        <svg class="programiz-icon programiz-icon--small">
          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#instagram"></use>
        </svg>
      </a>
      <a class="social-icons__links" href="https://www.linkedin.com/company/programiz" title="Programiz on Linkedin">
        <svg class="programiz-icon programiz-icon--small">
          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#linkedin"></use>
        </svg>
      </a>
      <a class="social-icons__links" href="https://twitter.com/programiz" title="Programiz on Twitter">
        <svg class="programiz-icon programiz-icon--small">
          <use xlink:href="/sites/all/themes/programiz/assets/feather-sprite.svg#twitter"></use>
        </svg>
      </a>
    </div>
  </div>
</div>

<script>
function advagg_mod_1() {
  // Count how many times this function is called.
  advagg_mod_1.count = ++advagg_mod_1.count || 1;
  try {
    if (advagg_mod_1.count <= 40) {
      
  (function waitGEO() {
    var readyGEO;
    if (window['UnicI'] && window['UnicI'].geo && window['UnicI'].geo !== '-') {
      readyGEO = true;
      console.log(window['UnicI'].geo);
      if (window['UnicI'].geo === 'EU') {
        if (document.getElementById("unic-gdpr")) {
          document.getElementById("unic-gdpr").style.display = 'block';
        }
      }
      if (window['UnicI'].geo === 'CA') {
        if (document.getElementById("unic-ccpa")) {
          document.getElementById("unic-ccpa").style.display = 'block';
        }
      }
    }
    if (!readyGEO) {
      setTimeout(waitGEO, 200);
    }
  })();


      // Set this to 100 so that this function only runs once.
      advagg_mod_1.count = 100;
    }
  }
  catch(e) {
    if (advagg_mod_1.count >= 40) {
      // Throw the exception if this still fails after running 40 times.
      throw e;
    }
    else {
      // Try again in 250 ms.
      window.setTimeout(advagg_mod_1, 250);
    }
  }
}
function advagg_mod_1_check() {
  if (window.jQuery && window.Drupal && window.Drupal.settings) {
    advagg_mod_1();
  }
  else {
    window.setTimeout(advagg_mod_1_check, 250);
  }
}
advagg_mod_1_check();</script>
    
    
    
    
    <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-TKXT7MH" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
        </footer>
  </main>

  <script type="text/javascript" src="/sites/tutorial2program/files/advagg_js/js__gDJOV3I1eT4meY0X9y-duzScaJvsBXv3tMwFDWcM-Bo__qLSvnvZ27GTtRxeCP2niPdU_XTxSlWCo2qU-qLaujYU__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.js" defer="defer"></script>
<script type="text/javascript" src="/sites/tutorial2program/files/advagg_js/js__pfQA3swpNJywiBvAkC8RJAjJhuMLWd_kl5R0-HkFwI4__1AJeWNPHY55Nyv2jniRilcu27VhsdFlNQZAxDoVxHEU__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.js" defer="defer"></script>
<script type="text/javascript" src="/sites/tutorial2program/files/advagg_js/js__--0Z8Ko2Ouantt4UUbDD1guuMHUWwLlSlrZ6GNz8h-g__ltjkcJyWJRLxGkRr53YybC-K7GdXtnXaDFxZx6y8RLg__bCS_vRPSPhWjQrSwUudaIT6Apl9ThEOgdjF4W3y9VhA.js" defer="defer"></script>
<script type="text/javascript">
<!--//--><![CDATA[//><!--

function advagg_mod_3() {
  // Count how many times this function is called.
  advagg_mod_3.count = ++advagg_mod_3.count || 1;
  try {
    if (advagg_mod_3.count <= 40) {
      var base_path = '/'; var module_path = 'sites/all/modules/programiz_rate_share';

      // Set this to 100 so that this function only runs once.
      advagg_mod_3.count = 100;
    }
  }
  catch(e) {
    if (advagg_mod_3.count >= 40) {
      // Throw the exception if this still fails after running 40 times.
      throw e;
    }
    else {
      // Try again in 250 ms.
      window.setTimeout(advagg_mod_3, 250);
    }
  }
}
function advagg_mod_3_check() {
  if (window.jQuery && window.Drupal && window.Drupal.settings) {
    advagg_mod_3();
  }
  else {
    window.setTimeout(advagg_mod_3_check, 250);
  }
}
advagg_mod_3_check();
//--><!]]>
</script>
<script defer src="https://static.cloudflareinsights.com/beacon.min.js/vcd15cbe7772f49c399c6a5babf22c1241717689176015" integrity="sha512-ZpsOmlRQV6y907TI0dKBHq9Md29nnaEIPlkf84rnaERnq6zvWvPUqr2ft8M1aS28oN72PdrCzSjY4U6VaAw1EQ==" data-cf-beacon='{"rayId":"934c62e63bf8b1c8","version":"2025.4.0-1-g37f21b1","r":1,"token":"0a465ad039704d1f9760ad556f6f3cdd","serverTiming":{"name":{"cfExtPri":true,"cfL4":true,"cfSpeedBrain":true,"cfCacheStatus":true}}}' crossorigin="anonymous"></script>
</body>

</html>
