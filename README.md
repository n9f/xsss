<!DOCTYPE html>
<html translate="no" class="notranslate" lang="ar" dir="rtl">

<head>    <link href="/rappasoft/laravel-livewire-tables/core.min.css" rel="stylesheet" />     <link href="/rappasoft/laravel-livewire-tables/thirdparty.css" rel="stylesheet" />
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="csrf-token" content="ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD">
	<meta name="google" content="notranslate" />
    
    
		 <style type="text/css">@font-face {font-family:El Messiri;font-style:normal;font-weight:400;src:url(/cf-fonts/v/el-messiri/5.0.11/latin-ext/wght/normal.woff2);unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:400;src:url(/cf-fonts/v/el-messiri/5.0.11/latin/wght/normal.woff2);unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:400;src:url(/cf-fonts/v/el-messiri/5.0.11/cyrillic/wght/normal.woff2);unicode-range:U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:400;src:url(/cf-fonts/v/el-messiri/5.0.11/arabic/wght/normal.woff2);unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:600;src:url(/cf-fonts/v/el-messiri/5.0.11/arabic/wght/normal.woff2);unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:600;src:url(/cf-fonts/v/el-messiri/5.0.11/cyrillic/wght/normal.woff2);unicode-range:U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:600;src:url(/cf-fonts/v/el-messiri/5.0.11/latin/wght/normal.woff2);unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:600;src:url(/cf-fonts/v/el-messiri/5.0.11/latin-ext/wght/normal.woff2);unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:700;src:url(/cf-fonts/v/el-messiri/5.0.11/arabic/wght/normal.woff2);unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:700;src:url(/cf-fonts/v/el-messiri/5.0.11/cyrillic/wght/normal.woff2);unicode-range:U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:700;src:url(/cf-fonts/v/el-messiri/5.0.11/latin/wght/normal.woff2);unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;font-display:swap;}@font-face {font-family:El Messiri;font-style:normal;font-weight:700;src:url(/cf-fonts/v/el-messiri/5.0.11/latin-ext/wght/normal.woff2);unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:300;src:url(/cf-fonts/v/cairo/5.0.18/arabic/wght/normal.woff2);unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:300;src:url(/cf-fonts/v/cairo/5.0.18/latin/wght/normal.woff2);unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:300;src:url(/cf-fonts/v/cairo/5.0.18/latin-ext/wght/normal.woff2);unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:400;src:url(/cf-fonts/v/cairo/5.0.18/latin-ext/wght/normal.woff2);unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:400;src:url(/cf-fonts/v/cairo/5.0.18/arabic/wght/normal.woff2);unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:400;src:url(/cf-fonts/v/cairo/5.0.18/latin/wght/normal.woff2);unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:600;src:url(/cf-fonts/v/cairo/5.0.18/latin/wght/normal.woff2);unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:600;src:url(/cf-fonts/v/cairo/5.0.18/arabic/wght/normal.woff2);unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:600;src:url(/cf-fonts/v/cairo/5.0.18/latin-ext/wght/normal.woff2);unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:700;src:url(/cf-fonts/v/cairo/5.0.18/latin/wght/normal.woff2);unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:700;src:url(/cf-fonts/v/cairo/5.0.18/latin-ext/wght/normal.woff2);unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:700;src:url(/cf-fonts/v/cairo/5.0.18/arabic/wght/normal.woff2);unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:900;src:url(/cf-fonts/v/cairo/5.0.18/latin-ext/wght/normal.woff2);unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:900;src:url(/cf-fonts/v/cairo/5.0.18/arabic/wght/normal.woff2);unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC;font-display:swap;}@font-face {font-family:Cairo;font-style:normal;font-weight:900;src:url(/cf-fonts/v/cairo/5.0.18/latin/wght/normal.woff2);unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;font-display:swap;}</style>
	<link rel="icon" href="https://cdn.tjar.sa/media-uploader/colors/HaD5SHmvqKZAt0Qp10nuq7xLtOHvi0CVmC488y9I.jpg" type="image/png">
	<title>
        			الوان السعادة للسيارات قطع غيار اصلية لكيا وأقلام بوية برقم كود الوكالة
							- متجر الوان السعادة للسيارات | colors joy cars
					    </title>

	<meta name="google-site-verification" content="wuKuzZZog6zpukGYNVjeL3BPVPyxZdoebUoRvdAn7wg" />

	<link rel="icon" href="https://cdn.tjar.sa/media-uploader/colors/HaD5SHmvqKZAt0Qp10nuq7xLtOHvi0CVmC488y9I.jpg" type="image/png">

	
			<link rel="stylesheet" href="https://colorsjoycars.shop/assets/tenant/frontend/css/bootstrap.min.css">
		
	
			<link rel="stylesheet" href="https://colorsjoycars.shop/assets/tenant/frontend/css/nice-select.css?v=1.0">
				<link rel="stylesheet" href="https://colorsjoycars.shop/assets/tenant/frontend/css/line-awesome.min.css">
		
			<link rel="stylesheet" href="https://colorsjoycars.shop/assets/tenant/frontend/css/common.css?1.30">
		
			<link rel="stylesheet" href="https://colorsjoycars.shop/assets/common/css/toastr.css">
				<link rel="stylesheet" href="https://colorsjoycars.shop/assets/common/css/loader.css">
	
	

			<link rel="stylesheet" href="https://colorsjoycars.shop/shop/assets/css/style?v=1.16" type="text/css"/>
	
						<link rel="stylesheet" href="https://colorsjoycars.shop/shop/assets/css/rtl" type="text/css"/>
			

			<meta name ="author" content= "متجر الوان السعادة لخدمة السيارات" />
<meta name ="tags" content= "قطع غيار كيا, أقلام دهان كيا, بوية كيا بالكود, قلم بوية هيونداي, قلم بوية جينسيس, قلم بوية كريتا, قلم بوية النترا, خدمات دهان السيارات, دهان كيا أصلي, بوية كيا, بوية كي فايف, بوية كيا كي فايف, بوية أصلية, قطع غيار كيا أصلي, قلم بوية كيا كي فايف, قلم بوية كيا أصلي, قلم بوية كيل أصلي, قلم بوية تويوتا, قلم بوية تويوتا أصلي, قطع غيار هيونداي, قطع غيار كيا الأصلية, قطع غيار سيراتو, بوية ديكسون, بوية نيوميكس, بوية قولدن, قطع غيار K5, قطع غيار K8, قطع غيار K3, قطع غيار كيا اوبتيما, قلم بوية اوبتيما, قلم بويه اوبتيما, قلم بوية كريتا, قلم بوية اكسنت" />
<meta name ="keywords" content= "بوية كيا كي فايف , بوية كيا اصلية,كيا سبورتاج, كيا سورينتو, كيا سيراتو, كيا بيكانتو, كيا أوبتيما, كيا ريو, كيا كارينز, كيا كادينزا, طلاء كيا, دهان سيارات, قطع غيار كيا, بوية السيارات, بوية وكالة, دهان كيا سيراتو, دهان كيا سبورتاج, دهان كيا سورينتو, دهان كيا أوبتيما, دهان كيا بيكانتو, دهان كيا ريو, دهان كيا كارينز, دهان كيا كادينزا, بوية السيارات الأصلية, طلاء بالوكالة, طلاء السيارات الأصلي, دهان كيا بالوكالة, دهان كيا بكود, دهان سيارات كيا, بوية كيا الأصلية, دهان بالرقم كود, طلاء كيا بالوكالة, طلاء السيارات كيا, دهان السيارات كيا, دهان كيا حسب الطلب, دهان كيا مطابق, كيا دهان مطابق, كيا طلاء مطابق, بوية كيا بالكود, طلاء كيا بالكود, كيا دهان أصلي, طلاء سيارات كيا, قلم بوية كيا اصلي , قلم بوية تويوتا , قلم بوية هيونداي , قلم بوية مازدا , قلم بوية كامري , قلم بوية سونيت , قلم بوية كيا سونيت , قلم بوية كيا كارينز , قلم بوية اكسنت , قلم بوية اصلي , قلم بويه اصلي , قلم بوية يارس , قلم بوية النترا , قلم بوية هيونداي النترا, قلم بوية هيونداي النترا ابيض," />
<meta name ="description" content= "استكشف قطع غيارنا الأصلية وأقلام بوية اصلية بالكود لتلبية احتياجاتك بأعلى جودة ودقة في الخدمة احصل على أفضل الخيارات والأسعار التنافسية مع COLORS JOY CARS.." />
<meta property="og:type" content="article" />
<meta property="og:title" content="الوان السعادة للسيارات قطع غيار كيا | اقلام دهان بكود المصنع - COLORS JOY CARS" />
<meta property="og:description" content="احصل على قطع غيار وأقلام بوية بكود الوكالة بجودة عالية وأسعار تنافسية مع COLORS JOY CARS." />
<meta property="og:image" content="https://colorsjoycars.shop/assets/img/no-image.jpg" />
<meta property="og:url" content="https://colorsjoycars.shop" />
<meta property="og:site_name" content="متجر الوان السعادة لخدمة السيارات" />
<meta name="twitter:title" content="الوان السعادة للسيارات قطع غيار كيا | اقلام دهان بكود المصنع - COLORS JOY CARS">
<meta name="twitter:description" content="احصل على قطع غيار وأقلام بوية بكود الوكالة بجودة عالية وأسعار تنافسية مع COLORS JOY CARS.">
<meta name="twitter:image" content="https://colorsjoycars.shop/assets/img/no-image.jpg">
	
	<style>
    :root {
                    --main-color-one: #9c2821;
                    --secondary-color: #000d1d;
                    --secondary-text: #111111;
                --heading-font: "Cairo", sans-serif;
        --body-font: "El Messiri", sans-serif;
    }
</style>

	<link rel="stylesheet" href="https://colorsjoycars.shop/assets/tenant/frontend/css/shop-order-custom.css">
	<link rel="stylesheet" href="https://colorsjoycars.shop/assets/tenant/frontend/css/digital-shop-common.css?v=1.0">
	<link rel="stylesheet" href="https://colorsjoycars.shop/assets/tenant/frontend/css/shop-common.css?v=1.0">
	<link href="https://cdn.jsdelivr.net/npm/select2@4.1.0-rc.0/dist/css/select2.min.css" rel="stylesheet" />

		
	<style>
    .section-title {
  text-transform: uppercase;
    background-image: linear-gradient(-225deg, #575454 0%, #25346d 9%, #9d2723 67%, #000000cc 100%);  background-size: auto auto;
  background-clip: border-box;
  background-size: 200% auto;
  color: #fff;
  font-weight: 700;
  background-clip: text;
  text-fill-color: transparent;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 2s linear infinite;
  display: inline-block;
  font-size: 21px;
}

@keyframes textclip {
  to {
    background-position: 200% center
  }
}
.four-blocks .section-head {
    justify-content: center;
    padding: 0 !important;
}
.product-summary {
    padding: 10px;
}
.global-card {
    background: white;
}
body {
    background: #dfd9d9;
}
.product-card .add-to-cart-btn {
    background: #9c2821;
    color: white !important;
}
.product-card .add-to-cart-btn:not(.active):hover, .product-card .digital-add-to-cart-btn:not(.active):hover {
    background: #a63f39;
    box-shadow: inset 0 0 15rem -12rem var(--main-color-one);
}
.product-card .wish-icon {
    color: #ffffff;
    background: #24336c;
}

.four-blocks-box .single-border{
    border: 1px solid rgb(37 52 109);
}
.four-blocks-box {
    flex: calc(25% - 20px);
    margin: 10px;
    background: white;
    border-radius: 20px;
}
.single-border {
    border: 1px solid rgb(37 52 109);
     border-radius: 20px;
}
@media (max-width: 768px){
.four-blocks-grid > .four-blocks-box:first-child{
    flex: calc(100% - 20px);
  }
}
@media (max-width: 500px){
  .product__slide .splide__slide{
    width: calc(50% + -5px) !important;
  }
}
.arrow-box button {
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  transition: 0.2s;
}
.arrow-box button:hover {
    box-shadow: none;
}
.footer-section {
    background: #ffffff;
    border-top: 2px solid;
    border-color: #25346d;
}
.footer-widget .footer-inner .footer-social-list .lists a {
    border-radius: 20px;
}
.single-right-content .search-suggestions-icon-wrapper .search-click-icon{
    border-radius: 50%;
    border: 1px solid;
    border-color: #25346d;
}
.single-right-content .track-icon-list .single-icon .icon{
    border-radius: 50%;
    border: 1px solid;
    border-color: #25346d;
}
.single-right-content .login-account .accounts{
    border-radius: 50%;
    border: 1px solid;
    border-color: #25346d;
}
.global-card {
    box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px !important;
}
body::before{
  content: "";
  top: 0;
  background: #fff url(https://cdn.tjar.sa/media-uploader/colors/1prYpR954xUtI50Qmyo1RRCoy77HS0wTCyGnNJPh.jpg);
  background-size: 250px !important;
  background-repeat: no-repeat !important;
  background-position: center !important;
  width: 100%;
  height: 100vh !important;
  transform: scale(0);
  position: fixed;
  left: 0;
  z-index: 9999999 !important;
  animation: slide-out-right .5s cubic-bezier(.55, .085, .68, .53) 2s both
}

@keyframes slide-out-right {
  0% {
    transform: translateX(0);
    opacity: 1
  }

  100% {
    transform: translateX(3000px);
    opacity: 0
  }
}
header {
    background: transparent;
}
@media (min-width: 300px) and (max-width: 991.98px) {
    .navbar-area .nav-container .logo-wrapper .logo img {
        max-width: 170px;
        max-height: 70px;
    }
}
.navbar-area .nav-container .logo-wrapper .logo img {
    border-radius: 10px;
}
.hero-image {
    border-radius: 10px;
}
<!DOCTYPE html>
<html lang="ar">
<head>    <link href="/rappasoft/laravel-livewire-tables/core.min.css" rel="stylesheet" />     <link href="/rappasoft/laravel-livewire-tables/thirdparty.css" rel="stylesheet" />
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="keywords" content="
قلم بوية كيا سونيت, قلم بوية كيا اوبتيما, قلم بوية كيا, قلم بويه كيا, قلم بوية كيا سيراتو, قلم بوية كيا سبورتاج, قلم بوية كيا سول, قلم بوية كيا ستينجر, قلم بوية كيا كادينزا, قلم بوية كيا تيلورايد, قلم بوية هيونداي, قلم بوية هيونداي النترا, قلم بوية هيونداي سوناتا, قلم بوية هيونداي توسان, قلم بوية هيونداي كونا, قلم بوية هيونداي سنتافي, قلم بوية هيونداي باليسايد, قلم بوية جينيسيس, قلم بوية جينيسيس G70, قلم بوية جينيسيس G80, قلم بوية جينيسيس G90, قلم بوية جينيسيس GV70, قلم بوية جينيسيس GV80, دهان سيارات, دهان سيارة كيا, دهان سيارة هيونداي, دهان سيارة جينيسيس, دهانات سيارات كيا, دهانات سيارات هيونداي, دهانات سيارات جينيسيس, دهان وكالة كيا, دهان وكالة هيونداي, دهان وكالة جينيسيس, طلاء سيارات, طلاء سيارة كيا, طلاء سيارة هيونداي, طلاء سيارة جينيسيس, طلاء وكالة كيا, طلاء وكالة هيونداي, طلاء وكالة جينيسيس, بوية كيا, بوية هيونداي, بوية جينيسيس, بوية كيا سيراتو, بوية كيا سبورتاج, بوية كيا سول, بوية كيا ستينجر, بوية كيا كادينزا, بوية كيا تيلورايد, بوية هيونداي النترا, بوية هيونداي سوناتا, بوية هيونداي توسان, بوية هيونداي كونا, بوية هيونداي سنتافي, بوية هيونداي باليسايد, بوية جينيسيس G70, بوية جينيسيس G80, بوية جينيسيس G90, بوية جينيسيس GV70, بوية جينيسيس GV80, قطع غيار كيا, قطع غيار هيونداي, قطع غيار جينيسيس, قطع غيار أصلية كيا, قطع غيار أصلية هيونداي, قطع غيار أصلية جينيسيس, خدمات سيارات كيا, خدمات سيارات هيونداي, خدمات سيارات جينيسيس, صيانة سيارات كيا, صيانة سيارات هيونداي, صيانة سيارات جينيسيس, متجر بوية كيا, متجر بوية هيونداي, متجر بوية جينيسيس, متجر قطع غيار كيا, متجر قطع غيار هيونداي, متجر قطع غيار جينيسيس, متجر دهانات سيارات, متجر طلاء سيارات, متجر صيانة سيارات, موقع قطع غيار كيا, موقع قطع غيار هيونداي, موقع قطع غيار جينيسيس, موقع دهانات سيارات, موقع طلاء سيارات, موقع صيانة سيارات, دهانات أصلية, طلاء أصلي, بوية أصلية, دهان وكالة, طلاء وكالة, بوية وكالة, دهان عالي الجودة, طلاء عالي الجودة, بوية عالية الجودة, دهانات ممتازة, طلاء ممتاز, بوية ممتازة, دهان كيا عالي الجودة, طلاء كيا عالي الجودة, بوية كيا عالية الجودة, دهان هيونداي عالي الجودة, طلاء هيونداي عالي الجودة, بوية هيونداي عالية الجودة, دهان جينيسيس عالي الجودة, طلاء جينيسيس عالي الجودة, بوية جينيسيس عالية الجودة, دهانات حديثة, طلاء حديث, بوية حديثة, دهان سيارة حديث, طلاء سيارة حديث, بوية سيارة حديث, دهان سيارات موديل 2023, طلاء سيارات موديل 2023, بوية سيارات موديل 2023, دهان سيارات موديل 2024, طلاء سيارات موديل 2024, بوية سيارات موديل 2024, دهان سيارات كيا جديد, طلاء سيارات كيا جديد, بوية سيارات كيا جديدة, دهان سيارات هيونداي جديد, طلاء سيارات هيونداي جديد, بوية سيارات هيونداي جديدة, دهان سيارات جينيسيس جديد, طلاء سيارات جينيسيس جديد, بوية سيارات جينيسيس جديدة, دهان سيارات, دهان سيارات جديدة, طلاء سيارات جديدة, بوية سيارات جديدة, دهان سيارات حديثة, طلاء سيارات حديثة, بوية سيارات حديثة, متجر سيارات, متجر خدمات سيارات, متجر صيانة سيارات, متجر قطع غيار سيارات, متجر دهان سيارات, متجر طلاء سيارات, متجر بوية سيارات, متجر دهانات كيا, متجر دهانات هيونداي, متجر دهانات جينيسيس, متجر طلاء كيا, متجر طلاء هيونداي, متجر طلاء جينيسيس, متجر بوية كيا, متجر بوية هيونداي, متجر بوية جينيسيس, متجر قطع غيار كيا, متجر قطع غيار هيونداي, متجر قطع غيار جينيسيس, متجر سيارات كيا, متجر سيارات هيونداي, متجر سيارات جينيسيس, متجر خدمات سيارات كيا, متجر خدمات سيارات هيونداي, متجر خدمات سيارات جينيسيس, متجر دهانات, متجر طلاء, متجر بوية, متجر قطع غيار, خدمات دهان سيارات, خدمات طلاء سيارات, خدمات بوية سيارات, خدمات صيانة سيارات, خدمات قطع غيار سيارات, خدمات سيارات عالية الجودة, خدمات دهانات سيارات عالية الجودة, خدمات طلاء سيارات عالية الجودة, خدمات بوية سيارات عالية الجودة, خدمات صيانة سيارات عالية الجودة, خدمات قطع غيار سيارات عالية الجودة, دهان سيارات أصلي, طلاء سيارات أصلي, بوية سيارات أصلية, دهان سيارات وكالة, طلاء سيارات وكالة, بوية سيارات وكالة, دهان سيارات كيا أصلي, طلاء سيارات كيا أصلي, بوية سيارات كيا أصلية, دهان سيارات هيونداي أصلي, طلاء سيارات هيونداي أصلي, بوية سيارات هيونداي أصلية, دهان سيارات جينيسيس أصلي, طلاء سيارات جينيسيس أصلي, بوية سيارات جينيسيس أصلية, دهان سيارات كيا وكالة, طلاء سيارات كيا وكالة, بوية سيارات كيا وكالة, دهان سيارات هيونداي وكالة, طلاء سيارات هيونداي وكالة, بوية سيارات هيونداي وكالة, دهان سيارات جينيسيس وكالة, طلاء سيارات جينيسيس وكالة, بوية سيارات جينيسيس وكالة, دهان سيارات كيا جديد, طلاء سيارات كيا جديد, بوية سيارات كيا جديدة, دهان سيارات هيونداي جديد, طلاء سيارات هيونداي جديد, بوية سيارات هيونداي جديدة, دهان سيارات جينيسيس جديد, طلاء سيارات جينيسيس جديد, بوية سيارات جينيسيس جديدة, خدمات دهانات, خدمات طلاء, خدمات بوية, خدمات سيارات ممتازة, خدمات سيارات عالية الجودة, خدمات دهانات ممتازة, خدمات طلاء ممتازة, خدمات بوية ممتازة, دهانات عالية الجودة, طلاء عالي الجودة, بوية عالية الجودة, دهانات ممتازة, طلاء ممتاز, بوية ممتازة, دهان سيارات كيا حديث, طلاء سيارات كيا حديث, بوية سيارات كيا حديثة, دهان سيارات هيونداي حديث, طلاء سيارات هيونداي حديث, بوية سيارات هيونداي حديثة, دهان سيارات جينيسيس حديث, طلاء سيارات جينيسيس حديث, بوية سيارات جينيسيس حديثة, خدمات دهانات حديثة, خدمات طلاء حديثة, خدمات بوية حديثة, خدمات دهانات ممتازة, خدمات طلاء ممتازة, خدمات بوية ممتازة, خدمات دهان سيارات ممتازة, خدمات طلاء سيارات ممتازة, خدمات بوية سيارات ممتازة, خدمات دهان سيارات عالية الجودة, خدمات طلاء سيارات عالية الجودة, خدمات بوية سيارات عالية الجودة, متجر دهانات كيا, متجر دهانات هيونداي, متجر دهانات جينيسيس, متجر طلاء كيا, متجر طلاء هيونداي, متجر طلاء جينيسيس, متجر بوية كيا, متجر بوية هيونداي, متجر بوية جينيسيس, متجر دهانات حديثة, متجر طلاء حديث, متجر بوية حديث, متجر دهانات جديد, متجر طلاء جديد, متجر بوية جديد, متجر سيارات جديد, متجر دهانات سيارات جديد, متجر طلاء سيارات جديد, متجر بوية سيارات جديد, متجر دهانات سيارات حديث, متجر طلاء سيارات حديث, متجر بوية سيارات حديث, متجر سيارات كيا جديد, متجر سيارات هيونداي جديد, متجر سيارات جينيسيس جديد, متجر دهانات كيا حديث, متجر دهانات هيونداي حديث, متجر دهانات جينيسيس حديث, متجر طلاء كيا حديث, متجر طلاء هيونداي حديث, متجر طلاء جينيسيس حديث, متجر بوية كيا حديثة, متجر بوية هيونداي حديثة, متجر بوية جينيسيس حديثة
">
<meta name="keywords" content="قلم بوية,قلم بويه , قلم بوية اصلي , قلم بوية أصلي , قلم بوية هيونداي , قلم بوية تويوتا , قلم بوية كيا">
<title>قلم بوية لازالة واخفاء الخدوش</title>
<title>H1</title>
<h1>قلم بوية لازالة واخفاء الخدوش</h1>
<p>قلم بوية لازالة الخدوش والحكات<p/>
<script src="/rappasoft/laravel-livewire-tables/core.min.js"  ></script> <script src="/rappasoft/laravel-livewire-tables/thirdparty.min.js"  ></script></head>
<body>
</html>
	</style>

	

	<!-- Bootstrap Icons -->
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.0/font/bootstrap-icons.css">

	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@4.1.4/dist/css/splide.min.css">

	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
	<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@4.1.4/dist/js/splide.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/lodash@4.17.21/lodash.min.js"></script>
<script src="/rappasoft/laravel-livewire-tables/core.min.js"  ></script> <script src="/rappasoft/laravel-livewire-tables/thirdparty.min.js"  ></script></head>

<body class="theme-1" x-data="cart">
    <div id="wdgt_shipping_indicator__wrapper" class="d-none fs_track-row alert alert-dismissible fade show border-top border-bottom">
        <div class="d-flex align-items-center justify-content-between gap-2 w-100">
            <p class="w-100 text-center rsf-16">🚚 <b>شحن مجاني</b> للطلبات التي تزيد عن <b>80.00  ر.س!</b> 🎉 </p>
            <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
        </div>
        <div class="fs_track-wrap">
            <span id="wdgt_shipping_indicator" data-min_order="80" class="fs_track-bar progress-bar-striped progress-bar-animated" role="progressbar" data-width="0" style="width: 0%" aria-valuenow="0" aria-valuemin="0" aria-valuemax="100"><i>0%</i></span>
        </div>
    </div>
<div class="loader loader_page_single">
    <div class="loader-01">
    
    <img src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/loader.gif" width="80" height="80" alt="loader">
</div>
</div>
<header class="header-style-01 custom-nav">
    <nav class="navbar navbar-area navbar-expand-lg py-3">
        <div class="container container-one nav-container align-items-center px-0 px-md-3">
            <div class="responsive-mobile-menu d-flex flex-stack gap-4">
                <div class="logo-wrapper">
                    <a href="https://colorsjoycars.shop" class="logo" aria-label="home">
                        <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/1prYpR954xUtI50Qmyo1RRCoy77HS0wTCyGnNJPh.jpg" class="lazy" alt="Image"/>
                    </a>
                </div>

                <div class="d-flex d-lg-none align-items-center gap-2">
                                            <div class="search-suggestions-icon-wrapper z-3">
    <div class="search-click-icon nav_icon">
        <i class="las la-search"></i>
    </div>
    <div class="search-suggetions-show ">
        <div class="navbar-input searchbar-suggetions">
            <form action="">
                <div class="search-open-form">
                    <input autocomplete="off" class="form--control" id="search_form_input" type="text" placeholder="ابحث هنا....">
                    <button type="submit"> <i class="las la-search"></i> </button>
                    <span class="suggetions-icon-close"> <i class="las la-times"></i> </span>
                </div>
                <div class="search-suggestions" id="search_suggestions_wrap">
                    <div class="search-suggestions-inner">
                        <h6 class="search-suggestions-title">اقتراحات المنتج</h6>
                        <ul class="product-suggestion-list mt-4">

                        </ul>
                    </div>
                </div>
            </form>
        </div>
    </div>
</div>                    
                    
                    <span class="nav_icon" type="button" data-bs-toggle="offcanvas" data-bs-target="#multi_tenancy_menu">
                        <i class="las la-bars"></i>
                    </span>
                </div>
            </div>

            <div class="offcanvas offcanvas-end navbar-collapse" id="multi_tenancy_menu">
                <div class="offcanvas-header px-4 w-100 border-bottom">
                    <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">
                        <div class="logo-wrapper">
                            <a href="https://colorsjoycars.shop" class="logo" aria-label="home">
                                <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/1prYpR954xUtI50Qmyo1RRCoy77HS0wTCyGnNJPh.jpg" class="lazy" alt="Image"/>
                            </a>
                        </div>
                    </h5>
                    <button type="button" class="btn-close btn-close-dark" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                </div>
                <div class="offcanvas-body pb-lg-0 pb-5 w-100">
                    <div class="d-flex flex-column" style="min-height: 100%;">
                        <ul class="navbar-nav m-0 mb-lg-0 mb-4 pb-lg-0 pb-4">
                            
	<li > 
		<a href="https://colorsjoycars.shop/home"> الصفحة الرئيسية</a>
</li>
	<li > 
		<a href="https://colorsjoycars.shop/shop"> المنتجات</a>
</li>
	<li > 
		<a href="https://colorsjoycars.shop/about"> من نحن</a>
</li>
	<li > 
		<a href="https://colorsjoycars.shop/contact"> اتصل بنا</a>
</li>
                                                            <li>
                                    <a href="https://colorsjoycars.shop/shop/order-track">
                                        تتبع الطلب
                                    </a>
                                </li>
                                                    </ul>

                                            </div>
                </div>
            </div>

            <div class="navbar-right-content show-nav-content d-none d-lg-flex">
                <div class="single-right-content">
                    
                                            <div class="search-suggestions-icon-wrapper z-3">
    <div class="search-click-icon nav_icon">
        <i class="las la-search"></i>
    </div>
    <div class="search-suggetions-show ">
        <div class="navbar-input searchbar-suggetions">
            <form action="">
                <div class="search-open-form">
                    <input autocomplete="off" class="form--control" id="search_form_input" type="text" placeholder="ابحث هنا....">
                    <button type="submit"> <i class="las la-search"></i> </button>
                    <span class="suggetions-icon-close"> <i class="las la-times"></i> </span>
                </div>
                <div class="search-suggestions" id="search_suggestions_wrap">
                    <div class="search-suggestions-inner">
                        <h6 class="search-suggestions-title">اقتراحات المنتج</h6>
                        <ul class="product-suggestion-list mt-4">

                        </ul>
                    </div>
                </div>
            </form>
        </div>
    </div>
</div>                    
                    <div class="navbar-right-flex">
                                                    <div class="track-icon-list icon-track-navbar">
                                
                                <div class="single-icon cart-shopping" x-data="wishlistCart">
                                    <a class="nav_icon" href="https://colorsjoycars.shop/shop/wishlist/page" aria-label="wishlist"> <i class="lar la-heart"></i> </a>
<span class="icon-notification whishlistCount" x-text="count"></span>

<div class="addto-cart-contents" :class="count == 0 ? 'cart-empty' : ''">
    <div class="single-addto-cart-wrappers">
        <div class="p-2">
            <template x-if="count > 0 && !fetching">
                <template x-for="item in items">
                    <div class="single-addto-carts">
                        <div class="addto-cart-thumb">
                            <a href="javascript:void(0)">
                                <img x-bind:src="item.image_url" alt="item.name">
                            </a>
                        </div>
                        <div class="addto-cart-item-contents">
                            <div class="addto-cart-title">
                                <a x-bind:href="item.slug" class="col">
                                    <span x-text="item.name"></span>
                                </a>
                                <i class="las la-times col-auto" @click.prevent="deleteItem(item.id)"></i>
                            </div>
                            <div class="price-title mt-2">
                                <span x-text="item.price"></span>
                            </div>
                        </div>
                    </div>
                </template>
            </template>
            <template x-if="count == 0 && !fetching">
                <div class="single-addto-carts">
                    <p class="d-flex flex-column justify-content-center align-items-center gap-3 w-100 rsf-14 text-muted">
                        <i class="lar la-heart fs-2"></i> لا يوجد عنصر في قائمة الرغبات
                    </p>
                </div>
            </template>
            <template x-if="fetching">
                <div class="text-center text-muted">
                    <i class="las la-spinner la-spin fs-2"></i>
                </div>
            </template>
        </div>
    </div>

    <template x-if="count > 0 && !fetching">
        <div class="btn-wrapper mt-3 px-2 pb-2">
            <a href="https://colorsjoycars.shop/shop/wishlist/page" class="cart-btn"> عرض قائمة الرغبات </a>
        </div>
    </template>
</div>                                </div>
                                <div class="single-icon cart-shopping">
                                    <a class="nav_icon" href="https://colorsjoycars.shop/shop/cart" aria-label="cart"> <i class="las la-shopping-cart"></i> </a>
<a href="https://colorsjoycars.shop/shop/cart" class="icon-notification" aria-label="cart" x-text="cart.length"></a>

<div class="addto-cart-contents" :class="cart.length <= 0 ? 'cart-empty' : ''">
    <div class="single-addto-cart-wrappers mb-2">
        <div class="p-2">
            <template x-if="cart.length && !fetching">
                <div>
                    <template x-for="cartItem in cart" :key="cartItem.id + '-' + cartItem.options?.type + '_' + cartItem.random_timestamp">
                        <div class="single-addto-carts">
                            <div class="addto-cart-thumb">
                                <img x-bind:src="cartItem.image" alt="cartItem.name">
                            </div>
                            <div class="addto-cart-item-contents">
                                <div class="addto-cart-title">
                                    <a class="col" x-text="cartItem.name"></a>
                                    <i class="las la-times col-auto" @click.prevent="openDeleteAlert(cartItem.rowId)" x-bind:data-product_hash_id="cartItem.rowId"></i>
                                </div>
                                <div class="d-flex align-items-end justfiy-content-between gap-2 mt-2">
                                <span class="name-subtitle d-block col">
                                    الكمية: <span x-text="cartItem.qty"></span>
                                    <template x-if="cartItem.options?.color_name">
                                        <div>
                                            <span>
                                                اللون: <span x-text="cartItem.options.color_name?.name"></span>
                                            </span>
                                        </div>
                                    </template>
                                    <template x-if="cartItem.options?.size_name">
                                        <div>
                                            الحجم: <span x-text="cartItem.options.size_name?.name"></span>
                                        </div>
                                    </template>
                                    <template x-if="cartItem.options?.attributes">
                                        <br>
                                        <template x-for="(attr, index) in cartItem.options.attributes" :key="attr">
                                            <span x-text="index + ':' +attr"></span>
                                        </template>
                                    </template>
                                    <template x-if="cartItem.options?.product_options?.length">
                                        <div>
                                            <template x-for="pOption in cartItem.options?.product_options" :key="pOption.cost+'_'+pOption.option+'_'+pOption.value">
                                                <div>
                                                    <span x-text="pOption.option + ':'"></span>
                                                    <span x-text="((pOption.value?.length > 20 ? pOption.value.substring(0, 20) + '...' : pOption.value) ?? '--') + ' ' + pOption.formatted_cost"></span>
                                                </div>
                                            </template>
                                        </div>
                                    </template>
                                </span>
                                    <span class="price-title col-auto">
                                        <span x-text="cartItem.formatted_price"></span>
                                    </span>
                                </div>
                            </div>
                        </div>
                    </template>
                </div>
            </template>
            <template x-if="cart.length == 0 && !fetching">
                <div class="single-addto-carts">
                    <p class="d-flex flex-column justify-content-center align-items-center gap-3 w-100 rsf-14 text-muted">
                        <i class="las la-shopping-cart fs-2"></i> لا يوجد عنصر في السلة
                    </p>
                </div>
            </template>
            <template x-if="fetching">
                <div class="text-center text-muted">
                    <i class="las la-spinner la-spin fs-2"></i>
                </div>
            </template>
        </div>
    </div>

    <template x-if="cart.length">
        <div class="px-2 pb-2">
            <div class="cart-total-amount">
                <span class="amount-title"> المبلغ الإجمالي: </span> <span class="fw-semibold">
                    <span x-text="meta.formatted_subtotal"></span>
                </span>
            </div>
            <div class="btn-wrapper mt-3">
                <a href="https://colorsjoycars.shop/shop/checkout" class="cart-btn"> الدفع </a>
                <a href="https://colorsjoycars.shop/shop/cart" class="cart-btn cart-btn-outline mt-3"> عربة التسوق </a>
            </div>
        </div>
    </template>
</div>                                </div>
                            </div>
                                                <div class="login-account">
                            <a class="accounts nav_icon" href="https://colorsjoycars.shop/login" aria-label="account"> <i class="las la-user"></i> </a>
                            </div>
                    </div>
                </div>
            </div>
        </div>
    </nav>
</header>

<script>
    // mobile menu dropdown
    $('.navbar-nav > li > a').wrap('<div class="link-wrapper"></div>');

    $('.navbar-nav > li').each(function() {
        if ($(this).hasClass('menu-item-has-children') || $(this).hasClass('has-children')) {
            $(this).find('.link-wrapper').append('<div class="menu__dropdown-btn"><span class="lnil lnil-chevron-down"></span></div>');
        }
    });

    $('.menu-item-has-children .menu__dropdown-btn').click(function(){
        $('.menu-item-has-children').not($(this).closest('.menu-item-has-children')).find('.sub-menu').slideUp('normal');
        $(this).closest('.menu-item-has-children').find('.sub-menu').stop().slideToggle('normal');
    });

    $('.has-children .menu__dropdown-btn').click(function(){
        $('.has-children').not($(this).closest('.has-children')).find('.sub-category-insider-list').slideUp('normal');
        $(this).closest('.has-children').find('.sub-category-insider-list').stop().slideToggle('normal');
    });

    $(document).on('click', '.cart-item__delete', function (e){
        Swal.fire({
            title: "هل ترغب في إزالة هذا العنصر من سلة التسوق؟",
            icon: "warning",
            confirmButtonColor: "#dc3545",
            confirmButtonText: "حذف",
            customClass: {
                popup: 'remove-cart-popup',
            }
        }).then((result) => {
            if (result.isConfirmed) {
                let el = $(this);
                let product_hash_id = el.data('product_hash_id');
                $.ajax({
                    url: 'https://colorsjoycars.shop/shop/cart/product/delete',
                    type: 'GET',
                    data: {
                        'product_hash_id': product_hash_id,
                    },
                    beforeSend: function (){
                        $('.loader').show();
                    },
                    success: function (data){
                        if (data.msg)
                        {
                            toastr.success(data.msg);
                        }

                        $('.icon-track-navbar').load(location.href + " .icon-track-navbar");
                    },
                    complete: function(){
                        $('.loader').hide();
                        document.dispatchEvent(new CustomEvent('cart:updated'))
                    },
                    error: function (data){
                        $('.loader').hide();
                    }
                })
            }
        });
    });
</script>
<div class="search-suggestion-overlay"></div>



    


<div>
        <section class="hero-slider-area">
    <div class="container py-4 py-sm-5 container-fluid-sm slider-box">
        <div class="splide hero-slider default__arrow" id="slider-CIhuSmx9">
            <div class="splide__arrows">
                <button class="splide__arrow splide__arrow--prev">
                    <i class="las la-angle-right"></i>
                </button>
                <button class="splide__arrow splide__arrow--next">
                    <i class="las la-angle-left"></i>
                </button>
            </div>

            <div class="splide__track">
                <ul class="splide__list">
                                            <li class="splide__slide">
                            <img class="hero-image lazy" data-src="https://cdn.tjar.sa/media-uploader/colors/AHNWsVVZPyVP3AIcWVixhpXykZgXOFt0fcksuKlx.jpg" alt="image">
                        </li>
                                            <li class="splide__slide">
                            <img class="hero-image lazy" data-src="https://cdn.tjar.sa/media-uploader/colors/LJ0r3PWr2Il9EL1OxDz9VCZGKwdxpIwnOuU0ZGip.jpg" alt="image">
                        </li>
                                    </ul>
            </div>
        </div>
    </div>
</section>
<script>
    var splideCIhuSmx9 = new Splide('#slider-CIhuSmx9', {
        arrows: true,
        pagination: true,
        direction: $('html').attr('dir') === 'rtl' ? 'rtl' : 'ltr',
        rewind: true,
        autoplay: true,
        interval: 3000,
    });

    splideCIhuSmx9.on( 'overflow', function ( isOverflow ) {
        splideCIhuSmx9.options = {
            arrows    : isOverflow,
            pagination: isOverflow,
            drag      : isOverflow,
        };
    } );
    splideCIhuSmx9.mount();
</script>
<section class="product-cat-area my-5">
    <div class="container">
        <div class="section-head pt-3 pb-md-5 pb-4">
            <div>
                <h4 class="section-title">اكسسورات السيارات</h4>
                            </div>

            <div class="arrow-box">
                <button class="splide__prev prevBtn-CN3UK"><i class="las la-angle-left"></i></button>
                <button class="splide__next nextBtn-CN3UK"><i class="las la-angle-right"></i></button>
            </div>
        </div>

        <div class="splide product__slide" id="slider-CN3UK">
            <div class="splide__track">
                <ul class="splide__list">
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/741b860d-a22d-4bc0-9850-29db526f4fba" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/21062d1c-4486-427f-90b7-0576bcbdb799.jpg" class="lazy" alt="21062d1c-4486-427f-90b7-0576bcbdb799.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="2" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/741b860d-a22d-4bc0-9850-29db526f4fba" class="text-decoration-none">
                ميدالية لكزس
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 7.99  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="2" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/741b860d-a22d-4bc0-9850-29db526f4fba"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/741b860d-a22d-4bc0-9850-29db526f4fba"
                >
                <i class="las la-shopping-cart fs-4 addItem-2-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-2-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/bc222ecb-68c9-4fb2-bf90-40d5ee26ec12" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/c96a4d86-ea2f-4ca8-aa12-967a66da0e61.jpg" class="lazy" alt="c96a4d86-ea2f-4ca8-aa12-967a66da0e61.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="3" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/bc222ecb-68c9-4fb2-bf90-40d5ee26ec12" class="text-decoration-none">
                ميدالية GMC
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 7.99  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="3" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/bc222ecb-68c9-4fb2-bf90-40d5ee26ec12"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/bc222ecb-68c9-4fb2-bf90-40d5ee26ec12"
                >
                <i class="las la-shopping-cart fs-4 addItem-3-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-3-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/2016978f-9402-4242-b02d-40e2d57c7513" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/f4becdde-64d9-46bf-8ea0-a57c108a4e25.png" class="lazy" alt="f4becdde-64d9-46bf-8ea0-a57c108a4e25.png"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="9" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/2016978f-9402-4242-b02d-40e2d57c7513" class="text-decoration-none">
                ميدالية كيا كاربون فايبر
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 10.00  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/be5dc4fb-b81a-4bb6-a72f-8ba20cae42a8" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/7aa70779-3765-4282-8559-1b97f7ba3f79.jpg" class="lazy" alt="7aa70779-3765-4282-8559-1b97f7ba3f79.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="15" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/be5dc4fb-b81a-4bb6-a72f-8ba20cae42a8" class="text-decoration-none">
                ميدالية فورد
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 7.99  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="15" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/be5dc4fb-b81a-4bb6-a72f-8ba20cae42a8"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/be5dc4fb-b81a-4bb6-a72f-8ba20cae42a8"
                >
                <i class="las la-shopping-cart fs-4 addItem-15-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-15-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/d0b7c93a-c928-437b-8b00-859c066c15b8" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/1d007af6-5566-4b06-a819-4d6ecbc088e8.jpg" class="lazy" alt="1d007af6-5566-4b06-a819-4d6ecbc088e8.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="14" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/d0b7c93a-c928-437b-8b00-859c066c15b8" class="text-decoration-none">
                ميدالية نيسان
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 7.99  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="14" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/d0b7c93a-c928-437b-8b00-859c066c15b8"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/d0b7c93a-c928-437b-8b00-859c066c15b8"
                >
                <i class="las la-shopping-cart fs-4 addItem-14-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-14-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/d0b7c93a-c928-437b-8b00-859c066c15b8-1" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/321ca536-29dc-4856-ac6a-6eef44a41562.jpg" class="lazy" alt="321ca536-29dc-4856-ac6a-6eef44a41562.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="12" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/d0b7c93a-c928-437b-8b00-859c066c15b8-1" class="text-decoration-none">
                ميدالية الجميح GM
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 7.99  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="12" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/d0b7c93a-c928-437b-8b00-859c066c15b8-1"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/d0b7c93a-c928-437b-8b00-859c066c15b8-1"
                >
                <i class="las la-shopping-cart fs-4 addItem-12-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-12-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/56a06f80-1998-4bfe-b43c-765737766238" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/57f6f116-7061-402f-ad22-b725fad1d9fd.png" class="lazy" alt="57f6f116-7061-402f-ad22-b725fad1d9fd.png"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="17" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/56a06f80-1998-4bfe-b43c-765737766238" class="text-decoration-none">
                ميدالية مازدا
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 7.99  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="17" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/56a06f80-1998-4bfe-b43c-765737766238"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/56a06f80-1998-4bfe-b43c-765737766238"
                >
                <i class="las la-shopping-cart fs-4 addItem-17-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-17-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/d29d40b9-f0fc-477f-bc03-f1d256bcb757" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/b15202f4-1dc5-4a34-88d3-f328bfb785f5.jpg" class="lazy" alt="b15202f4-1dc5-4a34-88d3-f328bfb785f5.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="7" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/d29d40b9-f0fc-477f-bc03-f1d256bcb757" class="text-decoration-none">
                ميدالية تيوتا
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 7.99  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="7" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/d29d40b9-f0fc-477f-bc03-f1d256bcb757"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/d29d40b9-f0fc-477f-bc03-f1d256bcb757"
                >
                <i class="las la-shopping-cart fs-4 addItem-7-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-7-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/bc7acd49-02a1-4407-97be-e70e551a3fc9" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/5e1f0225-1827-4af7-ad3c-3fdc9f701a54.png" class="lazy" alt="5e1f0225-1827-4af7-ad3c-3fdc9f701a54.png"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="1" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/bc7acd49-02a1-4407-97be-e70e551a3fc9" class="text-decoration-none">
                منظف زجاج عام
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 4.99  ر.س </span>
            <sup class="sale"> 9.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="1" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/bc7acd49-02a1-4407-97be-e70e551a3fc9"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/bc7acd49-02a1-4407-97be-e70e551a3fc9"
                >
                <i class="las la-shopping-cart fs-4 addItem-1-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-1-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/6d89759d-1826-498b-8183-d97676f62591" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/93d82d75-844b-4e22-ac91-f1e1ef2d029f.jpg" class="lazy" alt="93d82d75-844b-4e22-ac91-f1e1ef2d029f.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="11" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/6d89759d-1826-498b-8183-d97676f62591" class="text-decoration-none">
                ميدالية هيونداي
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 7.99  ر.س </span>
            <sup class="sale"> 20.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="11" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/6d89759d-1826-498b-8183-d97676f62591"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/6d89759d-1826-498b-8183-d97676f62591"
                >
                <i class="las la-shopping-cart fs-4 addItem-11-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-11-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/1e1ba1b7-4912-4453-8475-c5b12c949cc2" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/b3a34e3d-4d81-4030-8503-8903456b5234.jpg" class="lazy" alt="b3a34e3d-4d81-4030-8503-8903456b5234.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="5" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/1e1ba1b7-4912-4453-8475-c5b12c949cc2" class="text-decoration-none">
                معطر سيارة السفينة ياباني الأصلي
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 4.00  ر.س </span>
            <sup class="sale"> 10.00  ر.س </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                    </ul>
            </div>
        </div>
    </div>
</section>

<script>
    var splideCN3UK = new Splide('#slider-CN3UK', {
        arrows: false,
        pagination: false,
        direction: $('html').attr('dir') === 'rtl' ? 'rtl' : 'ltr',
        gap: 24,
        perPage: 4,
        perMove: 1,
        rewind: true,
        autoplay: true,
        interval: 3000,
        breakpoints: {
            360: {
                perPage: 1,
            },
            600: {
                perPage: 2,
            },
            991: {
                perPage: 3,
                gap: 14,
            }
        }
    });

    $('.nextBtn-CN3UK').on('click', function () {
        splideCN3UK.go('+1');
    });

    $('.prevBtn-CN3UK').on('click', function () {
        splideCN3UK.go('-1');
    });

    splideCN3UK.on( 'overflow', function ( isOverflow ) {
        splideCN3UK.options = {
            drag: isOverflow,
        };
    } );
    splideCN3UK.mount();
</script>
<section class="hero-slider-area">
    <div class="container py-4 py-sm-5 container-fluid-sm slider-box">
        <div class="splide hero-slider default__arrow" id="slider-He9yFBRE">
            <div class="splide__arrows">
                <button class="splide__arrow splide__arrow--prev">
                    <i class="las la-angle-right"></i>
                </button>
                <button class="splide__arrow splide__arrow--next">
                    <i class="las la-angle-left"></i>
                </button>
            </div>

            <div class="splide__track">
                <ul class="splide__list">
                                            <li class="splide__slide">
                            <img class="hero-image lazy" data-src="https://cdn.tjar.sa/media-uploader/colors/bbY3aqHhag1ADpEAHy3pTzVr70fh1iDw1fQb0FxK.jpg" alt="image">
                        </li>
                                    </ul>
            </div>
        </div>
    </div>
</section>
<script>
    var splideHe9yFBRE = new Splide('#slider-He9yFBRE', {
        arrows: true,
        pagination: true,
        direction: $('html').attr('dir') === 'rtl' ? 'rtl' : 'ltr',
        rewind: true,
        autoplay: true,
        interval: 3000,
    });

    splideHe9yFBRE.on( 'overflow', function ( isOverflow ) {
        splideHe9yFBRE.options = {
            arrows    : isOverflow,
            pagination: isOverflow,
            drag      : isOverflow,
        };
    } );
    splideHe9yFBRE.mount();
</script>
<section class="product-cat-area my-5">
    <div class="container">
        <div class="section-head pt-3 pb-md-5 pb-4">
            <div>
                <h4 class="section-title">أقلام بوية</h4>
                            </div>

            <div class="arrow-box">
                <button class="splide__prev prevBtn-3Y05W"><i class="las la-angle-left"></i></button>
                <button class="splide__next nextBtn-3Y05W"><i class="las la-angle-right"></i></button>
            </div>
        </div>

        <div class="splide product__slide" id="slider-3Y05W">
            <div class="splide__track">
                <ul class="splide__list">
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-7" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/245afa67-b640-484b-b8cc-dec534c9ad4c.png" class="lazy" alt="245afa67-b640-484b-b8cc-dec534c9ad4c.png"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="13" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-7" class="text-decoration-none">
                قلم بوية كيا سونيت رمادي
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="13" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-7"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-7"
                >
                <i class="las la-shopping-cart fs-4 addItem-13-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-13-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-8" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/fa1f3a97-655c-43a3-a0e2-d3e4c20987af.jpg" class="lazy" alt="fa1f3a97-655c-43a3-a0e2-d3e4c20987af.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="16" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-8" class="text-decoration-none">
                قلم بوية صدام خلفي رصاصي كيا سونيت
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="16" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-8"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-8"
                >
                <i class="las la-shopping-cart fs-4 addItem-16-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-16-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-10" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/2d4719b1-d786-427a-a10a-848791e77eec.png" class="lazy" alt="2d4719b1-d786-427a-a10a-848791e77eec.png"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="18" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-10" class="text-decoration-none">
                قلم بوية كيا سيلتوس برتقالي A7A
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="18" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-10"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-10"
                >
                <i class="las la-shopping-cart fs-4 addItem-18-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-18-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-11" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/zjiz6aJoVRQcbdUTj537a9i753sNr5RA3LAhWLUa.jpg" class="lazy" alt="Image"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="19" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-11" class="text-decoration-none">
                قلم بوية كويك لاين ايطالي 1 + 1 مجانا
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 99.00  ر.س </span>
            <sup class="sale"> 199.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="19" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-11"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-11"
                >
                <i class="las la-shopping-cart fs-4 addItem-19-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-19-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-9" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/6e156a42-e744-4094-aaf1-5a86422d08ca.png" class="lazy" alt="6e156a42-e744-4094-aaf1-5a86422d08ca.png"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="20" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-9" class="text-decoration-none">
                قلم بوية كيا سونيت أحمر A6R
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="20" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-9"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-9"
                >
                <i class="las la-shopping-cart fs-4 addItem-20-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-20-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/a18b8ab5-1688-43a2-a33c-51aeab3bb812.png" class="lazy" alt="a18b8ab5-1688-43a2-a33c-51aeab3bb812.png"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="22" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy" class="text-decoration-none">
                قلم بوية كيا K5 - اسود لؤلؤي
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="22" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy"
                >
                <i class="las la-shopping-cart fs-4 addItem-22-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-22-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-2" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/4f2beb12-35d8-4d79-9ab3-f098e07b34aa.jpg" class="lazy" alt="4f2beb12-35d8-4d79-9ab3-f098e07b34aa.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="25" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-2" class="text-decoration-none">
                قلم بوية كيا سونيت فضي KLG
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="25" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-2"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-2"
                >
                <i class="las la-shopping-cart fs-4 addItem-25-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-25-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-3" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/b5455f1a-fbf4-4d7b-86a0-506465d9afe5.png" class="lazy" alt="b5455f1a-fbf4-4d7b-86a0-506465d9afe5.png"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="27" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-3" class="text-decoration-none">
                قلم بوية كيا K5 - أبيض UD
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="27" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-3"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-3"
                >
                <i class="las la-shopping-cart fs-4 addItem-27-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-27-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-4" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/f9d10f63-c67b-494e-aef8-6d7a3927a3a3.jpg" class="lazy" alt="f9d10f63-c67b-494e-aef8-6d7a3927a3a3.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="29" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-4" class="text-decoration-none">
                قلم بوية كيا سونيت ذهبي - QYG
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 35.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="29" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-4"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-4"
                >
                <i class="las la-shopping-cart fs-4 addItem-29-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-29-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-6" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/85ff9dd3-e355-46c9-a502-bc1081db953f.jpg" class="lazy" alt="85ff9dd3-e355-46c9-a502-bc1081db953f.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="31" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-6" class="text-decoration-none">
                قلم بوية كريتا T2X
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="31" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-6"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-6"
                >
                <i class="las la-shopping-cart fs-4 addItem-31-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-31-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-5" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/c09a928e-af54-4bcc-8b9f-2f41e493fcaf.jpg" class="lazy" alt="c09a928e-af54-4bcc-8b9f-2f41e493fcaf.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="34" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-5" class="text-decoration-none">
                قلم بوية كريتا R4G
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="34" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-5"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-5"
                >
                <i class="las la-shopping-cart fs-4 addItem-34-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-34-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-1" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/0a5d2ac4-e47c-4d37-897a-e7d510b0aadd.jpg" class="lazy" alt="0a5d2ac4-e47c-4d37-897a-e7d510b0aadd.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="35" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-1" class="text-decoration-none">
                قلم بوية كيا K5 رمادي نجمي AGT
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="35" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-1"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-1"
                >
                <i class="las la-shopping-cart fs-4 addItem-35-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-35-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/213901a3-dec7-41cd-9d74-53293f16a0a1" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/d3a96766-9efc-4486-a349-c9346b63c245.jpg" class="lazy" alt="d3a96766-9efc-4486-a349-c9346b63c245.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="39" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/213901a3-dec7-41cd-9d74-53293f16a0a1" class="text-decoration-none">
                قلم بوية هيونداي كريتا pwt
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 80.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="39" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/213901a3-dec7-41cd-9d74-53293f16a0a1"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/213901a3-dec7-41cd-9d74-53293f16a0a1"
                >
                <i class="las la-shopping-cart fs-4 addItem-39-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-39-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/093ecd97-3a51-45b9-ab7e-a39e543c120a" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/53845c92-1f0c-42f4-a2c8-26d74a0c9755.jpg" class="lazy" alt="53845c92-1f0c-42f4-a2c8-26d74a0c9755.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="42" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/093ecd97-3a51-45b9-ab7e-a39e543c120a" class="text-decoration-none">
                قلم بوية كيا K5 فضي ناعم 4ss
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="42" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/093ecd97-3a51-45b9-ab7e-a39e543c120a"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/093ecd97-3a51-45b9-ab7e-a39e543c120a"
                >
                <i class="las la-shopping-cart fs-4 addItem-42-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-42-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/7024a3cb-134c-4044-a7eb-6505503b29e4" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/dc82b553-aacc-4401-b6d3-1c18950fb880.jpg" class="lazy" alt="dc82b553-aacc-4401-b6d3-1c18950fb880.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="43" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/7024a3cb-134c-4044-a7eb-6505503b29e4" class="text-decoration-none">
                قلم بوية كريتا X5B
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 100.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="43" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/7024a3cb-134c-4044-a7eb-6505503b29e4"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/7024a3cb-134c-4044-a7eb-6505503b29e4"
                >
                <i class="las la-shopping-cart fs-4 addItem-43-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-43-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-12" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/WgxYhpLeKeanKQ1fCCWNOLtOgs4bCVB7sZf43ygC.webp" class="lazy" alt="Image"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="62" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-12" class="text-decoration-none">
                قلم بوية هيونداي النترا رمادي فلويد معدني M6T ميتالك
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 60.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="62" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-12"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-12"
                >
                <i class="las la-shopping-cart fs-4 addItem-62-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-62-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-13" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/Dk0cCnyFhgHYxgvpj7mTuYHN6TMtRS9ANfUDmJQ4.png" class="lazy" alt="Image"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="65" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-13" class="text-decoration-none">
                قلم بوية هيونداي النترا ابيض saw
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 60.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="65" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-13"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-13"
                >
                <i class="las la-shopping-cart fs-4 addItem-65-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-65-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-14" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/x1tmJFpKHX3MWgOWWo125pbR14aOxY53PMDeaKBB.png" class="lazy" alt="Image"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="66" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-14" class="text-decoration-none">
                قلم بوية هيونداي النترا رمادي سايبر معدني C5G
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 60.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="66" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-14"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-14"
                >
                <i class="las la-shopping-cart fs-4 addItem-66-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-66-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-15" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/JYfxZimYPHIhzD3dFLxv6rCiIqHHiPA6W5iFdKuQ.png" class="lazy" alt="Image"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="67" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-15" class="text-decoration-none">
                قلم بوية هيونداي النترا رمادي إيكوترونيك لؤلؤي PE2
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 60.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="67" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-15"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-15"
                >
                <i class="las la-shopping-cart fs-4 addItem-67-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-67-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/aklam-boy-16" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/l4qBZCIRlzR6Y3oC6wG1z1OpNJ33lNiBOisdxDvp.png" class="lazy" alt="Image"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="68" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/aklam-boy-16" class="text-decoration-none">
                قلم بوية هيونداي النترا رمادي أمازون معدني A5G
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 40.00  ر.س </span>
            <sup class="sale"> 60.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="68" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/aklam-boy-16"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/aklam-boy-16"
                >
                <i class="las la-shopping-cart fs-4 addItem-68-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-68-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                    </ul>
            </div>
        </div>
    </div>
</section>

<script>
    var splide3Y05W = new Splide('#slider-3Y05W', {
        arrows: false,
        pagination: false,
        direction: $('html').attr('dir') === 'rtl' ? 'rtl' : 'ltr',
        gap: 24,
        perPage: 4,
        perMove: 1,
        rewind: true,
        autoplay: true,
        interval: 3000,
        breakpoints: {
            360: {
                perPage: 1,
            },
            600: {
                perPage: 2,
            },
            991: {
                perPage: 3,
                gap: 14,
            }
        }
    });

    $('.nextBtn-3Y05W').on('click', function () {
        splide3Y05W.go('+1');
    });

    $('.prevBtn-3Y05W').on('click', function () {
        splide3Y05W.go('-1');
    });

    splide3Y05W.on( 'overflow', function ( isOverflow ) {
        splide3Y05W.options = {
            drag: isOverflow,
        };
    } );
    splide3Y05W.mount();
</script>
<section class="hero-slider-area">
    <div class="container py-4 py-sm-5 container-fluid-sm slider-box">
        <div class="splide hero-slider default__arrow" id="slider-76Vk3UiG">
            <div class="splide__arrows">
                <button class="splide__arrow splide__arrow--prev">
                    <i class="las la-angle-right"></i>
                </button>
                <button class="splide__arrow splide__arrow--next">
                    <i class="las la-angle-left"></i>
                </button>
            </div>

            <div class="splide__track">
                <ul class="splide__list">
                                            <li class="splide__slide">
                            <img class="hero-image lazy" data-src="https://cdn.tjar.sa/media-uploader/colors/jAlwEXN5hjZNVI5HxFyKY9LET0pefrIpXyLlwADC.jpg" alt="image">
                        </li>
                                    </ul>
            </div>
        </div>
    </div>
</section>
<script>
    var splide76Vk3UiG = new Splide('#slider-76Vk3UiG', {
        arrows: true,
        pagination: true,
        direction: $('html').attr('dir') === 'rtl' ? 'rtl' : 'ltr',
        rewind: true,
        autoplay: true,
        interval: 3000,
    });

    splide76Vk3UiG.on( 'overflow', function ( isOverflow ) {
        splide76Vk3UiG.options = {
            arrows    : isOverflow,
            pagination: isOverflow,
            drag      : isOverflow,
        };
    } );
    splide76Vk3UiG.mount();
</script>
<section class="product-cat-area my-5">
    <div class="container">
        <div class="section-head pt-3 pb-md-5 pb-4">
            <div>
                <h4 class="section-title">قطع غيار حسب الطلب</h4>
                            </div>

            <div class="arrow-box">
                <button class="splide__prev prevBtn-rwf0k"><i class="las la-angle-left"></i></button>
                <button class="splide__next nextBtn-rwf0k"><i class="las la-angle-right"></i></button>
            </div>
        </div>

        <div class="splide product__slide" id="slider-rwf0k">
            <div class="splide__track">
                <ul class="splide__list">
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/d4bac6fd-fdcb-4ddb-a232-2e9fe9db9cfa" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/fc2746a4-92e4-471d-b562-bc1f198595d6.png" class="lazy" alt="fc2746a4-92e4-471d-b562-bc1f198595d6.png"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="21" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/d4bac6fd-fdcb-4ddb-a232-2e9fe9db9cfa" class="text-decoration-none">
                فلتر هوا سونيت ( 2021-2023 )
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 85.00  ر.س </span>
            <sup class="sale">  </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/988760e9-4033-41d2-a371-e3ee2abef508" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/5cc0fe85-7c1f-4248-93f1-cc4c5b3f69d4.png" class="lazy" alt="5cc0fe85-7c1f-4248-93f1-cc4c5b3f69d4.png"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="23" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/988760e9-4033-41d2-a371-e3ee2abef508" class="text-decoration-none">
                فلتر مكيف سونيت ( 2021-2023 )
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 85.00  ر.س </span>
            <sup class="sale">  </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/d7e70b0d-8c3d-4cdd-801b-c74d30c6df0f" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/3f80c9cc-f13a-4edf-9486-6bdc9fd0e65d.png" class="lazy" alt="3f80c9cc-f13a-4edf-9486-6bdc9fd0e65d.png"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="33" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/d7e70b0d-8c3d-4cdd-801b-c74d30c6df0f" class="text-decoration-none">
                فلتر مكيف اكسنت 2019-2020
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 75.00  ر.س </span>
            <sup class="sale"> 55.00  ر.س </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/6b3c934a-2063-4f6b-b1c1-238aa2f02fd8" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/4978dd22-901b-4ef9-8d1c-64002103ad14.jpg" class="lazy" alt="4978dd22-901b-4ef9-8d1c-64002103ad14.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="37" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/6b3c934a-2063-4f6b-b1c1-238aa2f02fd8" class="text-decoration-none">
                فلتر هواء اكسنت 2019-2022
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 75.00  ر.س </span>
            <sup class="sale"> 55.00  ر.س </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/d21afa7b-7357-45da-be78-ad7d87f7afc6" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/debb5f9d-965b-4b06-add3-90505797996d.jpg" class="lazy" alt="debb5f9d-965b-4b06-add3-90505797996d.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="40" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/d21afa7b-7357-45da-be78-ad7d87f7afc6" class="text-decoration-none">
                فلتر زيت هيونداي
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 53.00  ر.س </span>
            <sup class="sale"> 46.00  ر.س </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/1b895d8b-6e11-4339-b3aa-5cb7ec8a7e92" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/cc96eb23-e02e-445c-9b9f-0603c1cce426.jpg" class="lazy" alt="cc96eb23-e02e-445c-9b9f-0603c1cce426.jpg"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="50" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/1b895d8b-6e11-4339-b3aa-5cb7ec8a7e92" class="text-decoration-none">
                فلتر زيت من كيا
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 59.00  ر.س </span>
            <sup class="sale"> 51.00  ر.س </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/e52140ba-a635-4e7a-b52d-330b68a13272" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/dcddee84-6fc8-4d6c-b5f0-e1c1a161ded9.jpg" class="lazy" alt="dcddee84-6fc8-4d6c-b5f0-e1c1a161ded9.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="44" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/e52140ba-a635-4e7a-b52d-330b68a13272" class="text-decoration-none">
                شمعة نور يمين LED كيا سونيت 2021
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 5,000.00  ر.س </span>
            <sup class="sale"> 7,250.00  ر.س </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/be216c0b-ee6a-4625-982e-b9e33afce246" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/d0cdb141-80bd-4800-94bf-03b8a9193e62.jpg" class="lazy" alt="d0cdb141-80bd-4800-94bf-03b8a9193e62.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> وصل حديثآ </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="52" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/be216c0b-ee6a-4625-982e-b9e33afce246" class="text-decoration-none">
                خدمة سعرلي قطع الغيار
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 5.00  ر.س </span>
            <sup class="sale">  </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="52" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/be216c0b-ee6a-4625-982e-b9e33afce246"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/be216c0b-ee6a-4625-982e-b9e33afce246"
                >
                <i class="las la-shopping-cart fs-4 addItem-52-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-52-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/f5035523-f3e9-409e-868a-28656588bab4" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/91cd8462-bdfe-4b48-8b93-8ecc6ea046b2.jpg" class="lazy" alt="91cd8462-bdfe-4b48-8b93-8ecc6ea046b2.jpg"/>
        </a>
        <div class="product-badge-box">
            
                            <span class="product-badge border border-1"> اكثر مبيعات </span>
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="38" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/f5035523-f3e9-409e-868a-28656588bab4" class="text-decoration-none">
                رسوم خدمة
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 50.00  ر.س </span>
            <sup class="sale"> 149.00  ر.س </sup>
        </div>
    </div>

                        <a class="add-to-cart-btn" href="#"
                data-type="0"
                data-product_id="38" data-action-route="https://colorsjoycars.shop/product/quick-viewpage/f5035523-f3e9-409e-868a-28656588bab4"
                aria-label="add cart"
                data-product_url="https://colorsjoycars.shop/p/f5035523-f3e9-409e-868a-28656588bab4"
                >
                <i class="las la-shopping-cart fs-4 addItem-38-0"></i> أضف إلى العربة
                <span class="done-txt done-txt-38-0">تمت الإضافة!</span>
            </a>
            </div>

                        </li>
                                            <li class="splide__slide">
                            <div class="product-card global-card product shadow-none">
    <div class="global-card-thumb product-head">
        <a href="https://colorsjoycars.shop/p/bory-kya-sonyt-asly-2021-2022-2023" class="product-img">
            <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/hD09iiaOfXWbYplLxLkcz8xNsnhGdYRXCGCh6uvj.jpg" class="lazy" alt="Image"/>
        </a>
        <div class="product-badge-box">
            
            
                    </div>
        <div class="product-icons">
            <a href="#" class="wish-icon add-to-wishlist-btn"
                data-product_id="63" aria-label="wishlist">
                <i class="lar la-heart heart"></i>
            </a>
            
        </div>
    </div>
    <div class="product-summary d-block">
        <h5 class="product-title text-truncate rsf-14">
            <a href="https://colorsjoycars.shop/p/bory-kya-sonyt-asly-2021-2022-2023" class="text-decoration-none">
                بوري كيا سونيت أصلي 2021-2022-2023
            </a>
        </h5>
                    <div class="rating-wrap">
                 <div class="ratings">
                        <span class="hide-rating"></span>
                        <span class="show-rating" style="width: 00% !important"></span>
                    </div>
                    <p>
                        <span class="total-ratings">(0)</span>
                    </p>
            </div>
                <div>
            <span class="product-price"> 120.00  ر.س </span>
            <sup class="sale"> 149.00  ر.س </sup>
        </div>
    </div>

                        <a style="pointer-events: none; opacity: 0.5;" class="add-to-cart-btn" href="javascript:void(0)">
                <i class="las la-lg la-box"></i>
                نفذ من المخزون
            </a>
            </div>

                        </li>
                                    </ul>
            </div>
        </div>
    </div>
</section>

<script>
    var spliderwf0k = new Splide('#slider-rwf0k', {
        arrows: false,
        pagination: false,
        direction: $('html').attr('dir') === 'rtl' ? 'rtl' : 'ltr',
        gap: 24,
        perPage: 4,
        perMove: 1,
        rewind: true,
        autoplay: true,
        interval: 3000,
        breakpoints: {
            360: {
                perPage: 1,
            },
            600: {
                perPage: 2,
            },
            991: {
                perPage: 3,
                gap: 14,
            }
        }
    });

    $('.nextBtn-rwf0k').on('click', function () {
        spliderwf0k.go('+1');
    });

    $('.prevBtn-rwf0k').on('click', function () {
        spliderwf0k.go('-1');
    });

    spliderwf0k.on( 'overflow', function ( isOverflow ) {
        spliderwf0k.options = {
            drag: isOverflow,
        };
    } );
    spliderwf0k.mount();
</script>
<section class="four-blocks promo-area my-5 py-3">
    <div class="container">
                    <div class="section-head pb-5">
                <div>
                    <h4 class="section-title">نـحـن عـنـوان  الـتـمـيّـز</h4>                                    </div>
            </div>
        
        <div class="four-blocks-grid">
                                                <div class="four-blocks-box">
                        <div class="single-promo center-text single-border p-2 p-sm-4 h-100">
                            <div class="single-promo-icon py-4">
                                <i class="las la-truck"></i>
                            </div>
                            <div class="single-promo-contents py-2">
                                <h4 class="single-promo-contents-title rsf-24 fw-600"> توصيل سريع </h4>
                                <p class="single-promo-contents-para rsf-18 py-2"> توصلك لباب بيتك بسرعة </p>
                            </div>
                        </div>
                    </div>
                                    <div class="four-blocks-box">
                        <div class="single-promo center-text single-border p-2 p-sm-4 h-100">
                            <div class="single-promo-icon py-4">
                                <i class="las la-fist-raised"></i>
                            </div>
                            <div class="single-promo-contents py-2">
                                <h4 class="single-promo-contents-title rsf-24 fw-600"> ضمان وجودة </h4>
                                <p class="single-promo-contents-para rsf-18 py-2"> منتجات اصلية وجودة عالية </p>
                            </div>
                        </div>
                    </div>
                                    <div class="four-blocks-box">
                        <div class="single-promo center-text single-border p-2 p-sm-4 h-100">
                            <div class="single-promo-icon py-4">
                                <i class="lab la-cc-visa"></i>
                            </div>
                            <div class="single-promo-contents py-2">
                                <h4 class="single-promo-contents-title rsf-24 fw-600"> دفع آمن </h4>
                                <p class="single-promo-contents-para rsf-18 py-2"> طرق دفع آمنة ومتعددة </p>
                            </div>
                        </div>
                    </div>
                                    </div>
    </div>
</section>

    
</div>
<script>
	$('button').attr('aria-label', 'button');
</script>
<div class="modal product-quick-view-bg-color" id="product_quick_view">
</div>
<footer class="footer-section footer-style-1 tbadge-footer-mb ">
            <div class="footer-content-wrap container">
            <div class="footer-content row justify-content-between gy-5 gy-lg-0 pb-5">
                                    <div class="footer-widget-1 col-12 col-lg-4 d-flex flex-column gap-md-4 gap-3 align-items-start">
                        <div class="d-flex flex-column gap-lg-4 gap-3">
                            <a href="https://colorsjoycars.shop" class="logo" aria-label="home">
                                                                    <img src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://cdn.tjar.sa/media-uploader/colors/1prYpR954xUtI50Qmyo1RRCoy77HS0wTCyGnNJPh.jpg" class="lazy" alt="Image"/>
                                                            </a>

                                                            <div class="site-description-wrap col-lg-12 col-sm-10">
                                    ألوان السعادة لخدمة السيارات هي وجهتك المثالية للحصول على المنتجات الفاخرة نقدم في متجرنا مجموعة واسعة من المنتجات عالية الجودة المصممة بعناية لتلبية احتياجات عملائنا الكرام مع ضمان تجربة تسوق مميزة وخدمة عملاء استثنائية.
                                </div>
                                                    </div>

                                                    <ul class="footer-social-list d-flex flex-wrap align-items-center gap-3">
                                                                    <li class="m-0">
                                        <a class="whatsapp" target="_blank" href="590375422"
                                            data-bs-toggle="tooltip" data-bs-title="whatsapp" aria-label="social">
                                            <i class="bi bi-whatsapp p-0"></i>
                                        </a>
                                    </li>
                                                                    <li class="m-0">
                                        <a class="tiktok" target="_blank" href="colorsjoycars"
                                            data-bs-toggle="tooltip" data-bs-title="tiktok" aria-label="social">
                                            <i class="bi bi-tiktok p-0"></i>
                                        </a>
                                    </li>
                                                            </ul>
                        
                                            </div>
                
                                    <div class="footer-widget-2 col-lg-3 col-6">
                        <h5 class="footer-title">روابط هامة</h5>

                        <ul class="footer-menu d-flex flex-column gap-lg-3 gap-2">
                            
	<li > 
		<a href="https://colorsjoycars.shop/home"> الصفحة الرئيسية</a>
</li>
	<li > 
		<a href="https://colorsjoycars.shop/shop"> المنتجات</a>
</li>
	<li > 
		<a href="https://colorsjoycars.shop/about"> من نحن</a>
</li>
	<li > 
		<a href="https://colorsjoycars.shop/contact"> اتصل بنا</a>
</li>
                                                            <li>
                                    <a href="https://colorsjoycars.shop/shop/order-track">
                                        تتبع الطلب
                                    </a>
                                </li>
                                                                                                                    <li>
                                    <a href="https://colorsjoycars.shop/privacy">الخصوصية</a>
                                </li>
                                                    </ul>
                    </div>
                
                                    <div class="footer-widget-3 col-lg-4 col-6">
                        <h5 class="footer-title">اتصل بنا</h5>
                        <div class="contact-menu d-flex flex-column gap-lg-3 gap-2">
                                                            <a class="contact-links" href="/cdn-cgi/l/email-protection#284b4744475a5b49464c58495a5c5b684f45494144064b4745">
                                    <i class="bi bi-envelope-at rsf-18"></i>
                                    <span class="__cf_email__" data-cfemail="2d4e4241425f5e4c43495d4c5f595e6d4a404c4441034e4240">[email&#160;protected]</span>
                                </a>
                                                                                                                    <span class="contact-links">
                                    <i class="bi bi-geo-alt rsf-18"></i>
                                    المنطقة الشرقية - حفر الباطن
                                </span>
                                                    </div>

                                            </div>
                            </div>
        </div>
    
            <div class="footer-bar">
            <div class="container">
                <div class="footer-bar-row d-flex flex-wrap align-items-center gap-lg-0 gap-2 py-3">
                                            <div class="col">
                            <div class="copyright-text d-flex justify-content-lg-start justify-content-center">
                                الوان السعادة لخدمة السيارات جميع حقوق النشر محفوظة
2024 &copy;
                            </div>
                        </div>
                    
                                            <div class="col-lg-6 col-12">
                            <div
                                class="d-flex flex-md-row flex-column align-items-center justify-content-lg-end justify-content-center gap-3">
                                                                    <div class="d-flex gap-2 align-items-center  business-certificate-wrap ">
                                                                                    <div class="business-certificate">
                                                                                                    <a class="business-certification-logo" target="_blank"
                                                        href="https://eauthenticate.saudibusiness.gov.sa/certificate-details/0000004246"
                                                        aria-label="certificat">
                                                        <img src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/business-center-logo.svg"
                                                            alt="image">
                                                    </a>
                                                                                            </div>
                                        
                                                                            </div>
                                
                                                                    <ul class="payment-logos d-flex flex-wrap justify-content-md-start justify-content-center gap-2">
                                                                                                                                    <li class="payment-logos-item">
                                                    <img data-src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/mada.png"
                                                        class="lazy" alt="mada" width="49"
                                                        height="32">
                                                </li>
                                                                                                                                                                                <li class="payment-logos-item">
                                                    <img data-src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/visa.png"
                                                        class="lazy" alt="visa" width="49"
                                                        height="32">
                                                </li>
                                                                                                                                                                                <li class="payment-logos-item">
                                                    <img data-src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/master-card.png"
                                                        class="lazy" alt="master-card" width="49"
                                                        height="32">
                                                </li>
                                                                                                                                                                                <li class="payment-logos-item">
                                                    <img data-src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/cash-on-delivery.png"
                                                        class="lazy" alt="cash-on-delivery" width="49"
                                                        height="32">
                                                </li>
                                                                                                                                                                                <li class="payment-logos-item">
                                                    <img data-src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/apple.png"
                                                        class="lazy" alt="apple" width="49"
                                                        height="32">
                                                </li>
                                                                                                                                                                                                                                                                    <li class="payment-logos-item">
                                                    <img data-src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/tamara.png"
                                                        class="lazy" alt="tamara" width="49"
                                                        height="32">
                                                </li>
                                                                                                                                                                                <li class="payment-logos-item">
                                                    <img data-src="https://colorsjoycars.shop/assets/plugins/PageBuilder/images/Tenant/service/bank.png"
                                                        class="lazy" alt="bank" width="49"
                                                        height="32">
                                                </li>
                                                                                                                        </ul>
                                                            </div>
                        </div>
                                    </div>
            </div>
        </div>
    </footer>

<!-- For Mobile nav start -->
    <div class="mobile-nav">
        <div class="mobile-nav-item">
            <a href="https://colorsjoycars.shop/shop" class="mobile-nav-link">
                <span class="mobile-nav-icon"><i class="las la-store-alt"></i></span>
                <span class="mobile-nav-title">متجر</span>
            </a>
        </div>
                    <div class="mobile-nav-item">
                <a href="https://colorsjoycars.shop/shop/cart" class="mobile-nav-link">
                    <span class="mobile-nav-icon">
                        <i class="las la-shopping-cart"></i>
                        <span class="icon-count" x-text="cart.length"></span>
                    </span>
                    <span class="mobile-nav-title">العربة</span>
                </a>
            </div>
                <div class="mobile-nav-item">
            <a href="/" class="mobile-nav-link">
                <span class="mobile-nav-icon"><i class="las la-home"></i></span>
                <span class="mobile-nav-title">الرئيسية</span>
            </a>
        </div>
                    <div class="mobile-nav-item">
                <a href="https://colorsjoycars.shop/shop/wishlist/page" class="mobile-nav-link">
                    <span class="mobile-nav-icon">
                        <i class="lar la-heart"></i>
                        <span class="icon-count" wishlistCount></span>
                    </span>
                    <span class="mobile-nav-title">الرغبات</span>
                </a>
            </div>
                            <div class="mobile-nav-item">
                                <a href="https://colorsjoycars.shop/login" class="mobile-nav-link">
                    <span class="mobile-nav-icon"><i class="las la-user"></i></span>
                    <span class="mobile-nav-title">الدخول</span>
                </a>
            </div>
            </div>
    <!-- For Mobile nav end -->


    <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script src="https://colorsjoycars.shop/assets/tenant/frontend/js/jquery-3.6.1.min.js"></script>



    <script src="https://colorsjoycars.shop/assets/tenant/frontend/js/bootstrap.bundle.min.js"></script>

    <script src="https://colorsjoycars.shop/assets/tenant/frontend/js/jquery.lazy.min.js?v=1.10"></script>





    <script src="https://colorsjoycars.shop/assets/tenant/frontend/js/viewport.jquery.js"></script>

    <script src="https://colorsjoycars.shop/assets/tenant/frontend/js/wow.js"></script>

    <script src="https://colorsjoycars.shop/assets/tenant/frontend/js/jquery.nice-select.js"></script>

    <script src="https://colorsjoycars.shop/assets/tenant/frontend/js/jquery.syotimer.min.js"></script>

    <script src="https://colorsjoycars.shop/assets/landlord/common/js/sweetalert2.js"></script>

    <script src="https://colorsjoycars.shop/assets/common/js/toastr.min.js"></script>


    <!-- Range Slider -->
    <script src="https://colorsjoycars.shop/assets/tenant/frontend/js/nouislider-8.5.1.min.js"></script>



    <!-- main js -->
    <script src="https://colorsjoycars.shop/assets/tenant/frontend/js/main.js"></script>

    <script src="https://colorsjoycars.shop/assets/common/js/star-rating.min.js"></script>

    <script src="https://colorsjoycars.shop/assets/common/js/md5.js"></script>




    <script src="https://colorsjoycars.shop/shop/assets/js/imagesloaded.pkgd.min"></script>
    <script src="https://colorsjoycars.shop/shop/assets/js/isotope.pkgd.min"></script>
    <script src="https://colorsjoycars.shop/shop/assets/js/main"></script>

<script>
    var currentUrl = window.location.href;
    var listItems = document.querySelectorAll('.custom-navbar-nav li');
    listItems.forEach(function(item) {
        var anchor = item.querySelector('a');
        var href = anchor.getAttribute('href');
        if (href === currentUrl) {
            // Add the class 'current-menu-item' to the list item
            item.classList.add('current-menu-item');
        }
    });
</script>

<script src="https://colorsjoycars.shop/assets/tenant/frontend/js/digital-shop-common.js"></script>
<script>
    
</script>

<script>
    let site_currency_symbol = ' ر.س';
</script>

<script>
    $(document).on('click', '.newsletter-submit-btn', function (e) {
        e.preventDefault();

        var email = $('.footer-widget input.email').val();

        var errrContaner = $(this).parent().parent().find('.form-message-show');
        errrContaner.html('');
        var el = $(this);

        $.ajax({
            url: "https://colorsjoycars.shop/subscribe-newsletter",
            type: "POST",
            data: {
                _token: "ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD",
                email: email
            },

            beforeSend: function() {
                $('.loader').show();
                el.text('Submiting..');
                el.attr('disabled', true);
            },

            success: function (data) {
                $('.loader').hide();
                $('.email').val('');
                el.text('Subscribe');
                el.attr('disabled', false);
                errrContaner.html('<div class="alert alert-'+data.type+'">' + data.msg + '</div>');
            },
            error: function (data) {
                $('.loader').hide();
                el.text('Subscribe');
                el.attr('disabled', false);
                var errors = data.responseJSON.errors;
                errrContaner.html('<div class="alert alert-danger">' + errors.email[0] + '</div>');
            }
        });
    });
</script>
<script>
    $(document).on('submit', '.custom-form-builder-land', function (e) {
        e.preventDefault();
        var btn = $('#contact_form_btn');
        var form = $(this);
        var formID = form.attr('id');
        var msgContainer =  form.find('.error-message');
        var formSelector = document.getElementById(formID);
        var formData = new FormData(formSelector);
        msgContainer.html('');
        $.ajax({
            url: "https://colorsjoycars.shop/tenant/submit-custom-form",
            type: "POST",
            headers: {
                'X-CSRF-TOKEN': "ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD",
            },
            beforeSend:function (){
                btn.html('<i class="fas fa-spinner fa-spin mr-1"></i> جارٍ الإرسال..');
            },
            processData: false,
            contentType: false,
            data:formData,
            success: function (data) {
                form.find('.ajax-loading-wrap').removeClass('show').addClass('hide');
                msgContainer.html('<div class="alert alert-'+data.type+'">' + data.msg + '</div>');
                btn.text('إرسال الرسالة');
                form[0].reset();

            },
            error: function (data) {

                form.find('.ajax-loading-wrap').removeClass('show').addClass('hide');
                var errors = data.responseJSON.errors;
                var markup = '<ul class="alert alert-danger">';

                $.each(errors,function (index,value){
                    markup += '<li>'+value+'</li>';})
                markup += '</ul>';


                msgContainer.html(markup);
                btn.text('إرسال الرسالة');
            }
        });
    });
</script>
<script>
    (function($){
        "use strict";
        $(document).ready(function(){
            $(document).on('click','.language_dropdown ul li',function(e){
                var el = $(this);
                $.ajax({
                    url : "https://colorsjoycars.shop/lang-change",
                    type: "GET",
                    data:{
                        'lang' : el.data('value')
                    },
                    beforeSend: function(){
                        $('.loader').show();
                    },
                    success:function (data) {
                        location.reload();
                    }
                })
            });
        });
    }(jQuery));
</script>
<script>
    $(function () {
        $(document).ready(function () {
            $(document).on('click', '.physical-explore-category-area .store-tabs .list', function (e) {
                e.preventDefault();

                let el = $(this);
                let tab = el.data('tab');
                let limit = el.data('limit');
                let allId = el.data('all-id');
                let sort_by = el.data('sort_by');
                let sort_to = el.data('sort_to');

                $.ajax({
                    type: 'GET',
                    url: "https://colorsjoycars.shop/category-wise-product/theme-bookpoint/physical",
                    data: {
                        category: tab,
                        limit: limit,
                        allId: allId,
                        sort_by: sort_by,
                        sort_to: sort_to
                    },
                    beforeSend: function () {
                        $('.loader').fadeIn(200);
                    },
                    success: function (data) {
                        let tab = $('li.list[data-tab=' + data.category + ']');
                        let markup_wrapper = $('.physical-explore-category-area .markup_wrapper');

                        $('li.list').removeClass('active');
                        tab.addClass('active');
                        markup_wrapper.hide();
                        markup_wrapper.html(data.markup);
                        markup_wrapper.fadeIn();
                        $('.loader').fadeOut(200);
                    },
                    error: function (data) {
                        console.log('error')
                    }
                });
            });

            $(document).on('click', '.digital-explore-category-area .store-tabs .list', function (e) {
                e.preventDefault();

                let el = $(this);
                let tab = el.data('tab');
                let limit = el.data('limit');
                let allId = el.data('all-id');
                let sort_by = el.data('sort_by');
                let sort_to = el.data('sort_to');

                $.ajax({
                    type: 'GET',
                    url: "https://colorsjoycars.shop/category-wise-product/theme-bookpoint",
                    data: {
                        category: tab,
                        limit: limit,
                        allId: allId,
                        sort_by: sort_by,
                        sort_to: sort_to
                    },
                    beforeSend: function () {
                        $('.loader').fadeIn(200);
                    },
                    success: function (data) {
                        let tab = $('li.list[data-tab=' + data.category + ']');
                        let markup_wrapper = $('.digital-explore-category-area .markup_wrapper');

                        $('li.list').removeClass('active');
                        tab.addClass('active');
                        markup_wrapper.hide();
                        markup_wrapper.html(data.markup);
                        markup_wrapper.fadeIn();
                        $('.loader').fadeOut(200);
                    },
                    error: function (data) {
                        console.log('error')
                    }
                });
            });
        });
    });
</script>

<script>
    $(function () {
        $(document).on('click', '.product-list .list', function (e) {
            e.preventDefault();

            let el = $(this);
            let tab = el.data('tab');
            let limit = el.data('limit');
            let sort_by = el.data('sort_by');
            let sort_to = el.data('sort_to');
            let allId = el.data('all-id');

            $.ajax({
                type: 'GET',
                url: "https://colorsjoycars.shop/category-wise-product/theme-casual",
                data: {
                    category: tab,
                    limit: limit,
                    sort_by: sort_by,
                    sort_to: sort_to,
                    allId: allId
                },
                beforeSend: function () {
                    $('.loader').fadeIn(200);
                },
                success: function (data) {
                    let tab = $('li.list[data-tab='+data.category+']');
                    let markup_wrapper = $('.markup_wrapper');

                    $('li.list').removeClass('active');
                    tab.addClass('active');
                    markup_wrapper.hide();
                    markup_wrapper.html(data.markup);
                    markup_wrapper.fadeIn();
                    $('.loader').fadeOut(200);
                },
                error: function (data) {
                    console.log('error')
                }
            });
        });
    });
</script>
<script>
    toastr.options = {
        "closeButton": true,
        "debug": false,
        "newestOnTop": true,
        "progressBar": false,
        "positionClass": "toast-top-right",
        "preventDuplicates": true,
        "onclick": null,
        "showDuration": "300",
        "hideDuration": "1000",
        "timeOut": "2000",
        "extendedTimeOut": "2000",
        "showEasing": "swing",
        "hideEasing": "linear",
        "showMethod": "slideDown",
        "hideMethod": "slideUp"
    };

    $(function() {
        $(document).on('keyup', '#search_form_input', function(e) {
            e.preventDefault();

            let search_text = $(this).val();

            $.ajax({
                url: 'https://colorsjoycars.shop/search',
                type: 'GET',
                data: {
                    search: search_text
                },
                beforeSend: function() {

                },
                success: function(data) {
                    if (data.product_object.length > 0) {
                        $('.product-suggestion-list').html(data.markup);
                    }
                }
            });
        });

        // Compare Product
        $(document).on('click', '.quick-view-compare-btn', function(e) {
            e.preventDefault();

            let quick_view_has_campaign = '0';
            let quick_view_campaign_expired = '0';

            if (quick_view_has_campaign === 1) {
                if (quick_view_campaign_expired === 0) {
                    toastr.error('The campaign is over, Sorry! you can not cart this product');
                    return false;
                }
            }

            let selected_size = $('#selected_size').val();
            let selected_color = $('#selected_color').val();

            let pid_id = getQuickViewAttributesForCart();

            let product_id = quick_view_product_id;
            let quantity = Number($('#quick-view-quantity').val().trim());
            let price = $('#price').text().split(site_currency_symbol)[1];
            let attributes = {};
            let product_variant = pid_id;
            let productAttribute = quick_view_selected_variant;

            attributes['price'] = price;

            // if selected attribute is a valid product item
            if (quickViewValidateSelectedAttributes()) {
                $.ajax({
                    url: 'https://colorsjoycars.shop/shop/product/compare/add',
                    type: 'POST',
                    data: {
                        product_id: product_id,
                        quantity: quantity,
                        pid_id: pid_id,
                        product_variant: product_variant,
                        selected_size: selected_size,
                        selected_color: selected_color,
                        _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                    },
                    beforeSend: function() {

                    },
                    success: function(data) {
                        if (data.quantity_msg) {
                            toastr.warning(data.quantity_msg);
                        } else if (data.error_msg) {
                            toastr.error(data.error_msg);
                        } else {
                            toastr.success(data.msg, 'الانتقال إلى السلة', '#', 60000);
                            $('.track-icon-list').load(location.href + " .track-icon-list");
                        }
                    },
                    erorr: function(err) {
                        toastr.error('حدث خطأ')
                    }
                });
            } else {
                toastr.error('اختر كل السمات للمتابعة')
            }
        });


        $(document).on('click', '.compare-btn', function(e) {
            e.preventDefault();

            let pid_id = null;
            let product_id = $(this).data("product_id");
            let quantity = 1;
            let product_variant = null;

            $.ajax({
                url: 'https://colorsjoycars.shop/shop/product/compare/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    quantity: quantity,
                    pid_id: pid_id,
                    product_variant: product_variant,
                    selected_size: null,
                    selected_color: null,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                beforeSend: function() {

                },
                success: function(data) {
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg);
                    } else if (data.error_msg) {
                        toastr.error(data.error_msg);
                    } else {
                        toastr.success(data.msg, 'الانتقال إلى السلة', '#', 60000);
                        $('.track-icon-list').load(location.href + " .track-icon-list");
                    }
                },
                erorr: function(err) {
                    toastr.error('حدث خطأ')
                }
            });

        });

        $(document).on('click', '.add-to-wishlist-btn', function(e) {
            e.preventDefault();

            let pid_id = null;
            let product_id = $(this).data("product_id");
            let quantity = 1;
            let product_variant = null;

            $.ajax({
                url: 'https://colorsjoycars.shop/shop/product/wishlist/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    quantity: quantity,
                    pid_id: pid_id,
                    product_variant: product_variant,
                    selected_size: null,
                    selected_color: null,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                beforeSend: function() {

                },
                success: function(data) {
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg);
                    } else if (data.error_msg) {
                        toastr.error(data.error_msg);
                    } else {
                        document.dispatchEvent(new CustomEvent('wishlist:updated', {
                            detail: {
                                items: data?.items ?? [],
                                count: data?.count ?? 0,
                            }
                        }));
                        toastr.success(data.msg, 'الانتقال إلى السلة', '#', 60000);
                        $('.single-icon-theme-3').load(location.href +
                            " .single-icon-theme-3");
                    }
                },
                erorr: function(err) {
                    toastr.error('تعذر إضافة العنصر إلى قائمة الأمنيات')
                }
            });

        });
        $(document).on('click', '.add-to-wishlist-digital-btn', function(e) {
            e.preventDefault();
            let product_id = $(this).data("product_id");
            let quantity = 1;

            $.ajax({
                url: 'https://colorsjoycars.shop/shop/digital/product/wishlist/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    quantity: quantity,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                beforeSend: function() {

                },
                success: function(data) {

                    // console.log(data)
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg);
                    } else if (data.error_msg) {
                        toastr.error(data.error_msg);
                    } else {
                        // $('.whishlistCount').html(data.count);
                        toastr.success(data.msg, 'انتقل إلى قائمة الأمنيات', '#', 60000);
                        $('.track-icon-list').load(location.href + " .track-icon-list");
                    }
                },
                erorr: function(err) {
                    toastr.error('حدث خطأ')
                }
            });

        });

        $(document).on('click', '.add-to-cart-btn', function(e) {
            e.preventDefault();
            document.dispatchEvent(new CustomEvent('cart:add', {
                detail: {
                    id: $(this).data("product_id"),
                    digital: parseInt($(this).data('type')) ?? 0,
                }
            }))

            return;

            let element = $(this);
            let pid_id = null;
            let product_id = $(this).data("product_id");
            let quantity = 1;
            let product_variant = null;

            $.ajax({
                url: 'https://colorsjoycars.shop/shop/product/cart/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    quantity: quantity,
                    pid_id: pid_id,
                    product_variant: product_variant,
                    selected_size: null,
                    selected_color: null,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                beforeSend: function() {
                    element.find('i').removeClass('las la-shopping-cart').addClass(
                        'las la-spinner la-spin');
                },
                success: function(data) {
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg);
                    } else if (data.error_msg) {
                        toastr.error(data.error_msg);
                    } else {
                        toastr.success(data.msg, 'الانتقال إلى السلة', '#', 60000);
                        // $('.single-icon').parent().load(location.href + " .single-icon");
                        $('.mobile-nav').load(location.href + " .mobile-nav");
                        $('.canvas-cart-sidebar').parent().load(location.href +
                            " .canvas-cart-sidebar");
                        $('.icon-track-navbar').load(location.href + " .icon-track-navbar");
                        document.dispatchEvent(new CustomEvent('cart:updated'))
                    }

                    element.addClass('active');

                    setTimeout(function() {
                        element.removeClass('active');
                        element.find('i').removeClass('las la-spinner la-spin')
                            .addClass('las la-shopping-cart');
                    }, 1500);
                },
                erorr: function(err) {
                    console.log(err)
                    toastr.error('حدث خطأ')
                    element.find('i').removeClass('las la-spinner la-spin').addClass(
                        'las la-shopping-cart');
                }
            });

        });

        $(document).on('click', '.digital-add-to-cart-btn', function(e) {
            e.preventDefault();
            let element = $(this);
            let product_id = $(this).data("product_id");

            document.dispatchEvent(new CustomEvent('cart:add', {
                detail: {
                    id: $(this).data("product_id"),
                    digital: 1
                }
            }))

            return;

            $.ajax({
                url: 'https://colorsjoycars.shop/shop/digital/product/cart/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                beforeSend: function() {
                    element.find('i').removeClass('las la-shopping-cart').addClass(
                        'las la-spinner la-spin');
                },
                success: function(data) {
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg);
                    } else if (data.error_msg) {
                        toastr.error(data.error_msg);
                    } else {
                        toastr.success(data.msg, 'الانتقال إلى السلة', '#', 60000);
                        // $('.single-icon').parent().load(location.href + " .single-icon");
                        $('.mobile-nav').load(location.href + " .mobile-nav");
                        $('.canvas-cart-sidebar').parent().load(location.href +
                            " .canvas-cart-sidebar");
                        $('.icon-track-navbar').load(location.href + " .icon-track-navbar");
                    }
                    setTimeout(function() {
                        element.find('i').removeClass('las la-spinner la-spin')
                            .addClass('las la-shopping-cart');
                    }, 1500);
                },
                erorr: function(err) {
                    toastr.error('حدث خطأ')
                    element.find('i').removeClass('las la-spinner la-spin').addClass(
                        'las la-shopping-cart');
                }

            });
        });

        function storeIntoSession(product_id) {
            let arrItem = [];

            if (sessionStorage.length === 0) {
                sessionStorage.setItem('products', product_id);
            } else {
                arrItem.push(sessionStorage.getItem('products'));
                arrItem.push(product_id);
                sessionStorage.setItem('products', arrItem);
            }

            return sessionStorage.getItem('products');
        }
    });

    $(document).on('click', '.social_share_parent', function(e) {
        $('.social_share_wrapper_item').toggleClass('show');
    });

    $('body').on('click', '.quick-view-size-lists li', function(event) {
        let el = $(this);
        let value = el.data('displayValue');
        let parentWrap = el.parent().parent();
        el.addClass('active');
        el.siblings().removeClass('active');
        parentWrap.find('input[type=text]').val(value);
        parentWrap.find('input[type=hidden]').val(el.data('value'));

        // selected attributes
        selectedAttributeSearch(this);
    });

    function selectedAttributeSearch(selected_item) {
        /*
         * search based on all selected attributes
         *
         * 1. get all selected attributes in {key:value} format
         * 2. search in attribute_store for all available matches
         * 3. display available matches (keep available matches selectable, and rest as disabled)
         * */

        let available_variant_types = [];
        let selected_options = {};

        $('.quick-view-size-lists li').addClass('disabled');

        // get all selected attributes in {key:value} format
        quick_view_available_options.map(function(k, option) {
            let selected_option = $(option).find('li.active');
            let type = selected_option.closest('.quick-view-size-lists').data('type');
            let value = selected_option.data('displayValue');

            if (type) {
                available_variant_types.push(type);
            }

            if (type && value) {
                selected_options[type] = value;
            }
        });

        quickViewSyncImage(get_quick_view_selected_options());
        quickViewSyncPrice(get_quick_view_selected_options());
        quickViewSyncStock(get_quick_view_selected_options());

        // search in attribute_store for all available matches
        let available_variants_selection = [];
        let selected_attributes_by_type = {};
        quick_view_attribute_store.map(function(arr) {
            let matched = true;

            Object.keys(selected_options).map(function(type) {

                if (arr[type] !== selected_options[type]) {
                    matched = false;
                }
            })

            if (matched) {
                available_variants_selection.push(arr);

                // insert as {key: [value, value...]}
                Object.keys(arr).map(function(type) {
                    // not array available for the given key
                    if (!selected_attributes_by_type[type]) {
                        selected_attributes_by_type[type] = []
                    }

                    // insert value if not inserted yet
                    if (selected_attributes_by_type[type].indexOf(arr[type]) <= -1) {
                        selected_attributes_by_type[type].push(arr[type]);
                    }
                })
            }

            window.quick_view_selected_variant = selected_attributes_by_type;
        });

        // selected item not contain product then de-select all selected option hare
        if (Object.keys(selected_attributes_by_type).length == 0) {
            $('.quick-view-size-lists li.active').each(function() {
                let sizeItem = $(this).parent().parent();

                sizeItem.find('input[type=hidden]').val('');
                sizeItem.find('input[type=text]').val('');
            });

            $('.quick-view-size-lists li.active').removeClass("active");
            $('.quick-view-size-lists li.disabled').removeClass("disabled");

            let el = $(selected_item);
            let value = el.data('displayValue');
            let parentWrap = el.parent().parent();

            el.addClass("active");
            el.siblings().removeClass('active');

            selectedAttributeSearch();

            parentWrap.find('input[type=text]').val(value);
            parentWrap.find('input[type=hidden]').val(el.data('value'));
        }

        // keep only available matches selectable
        Object.keys(selected_attributes_by_type).map(function(type) {
            // initially, disable all buttons
            $('.quick-view-size-lists[data-type="' + type + '"] li').addClass('disabled');

            // make buttons selectable for the available options
            selected_attributes_by_type[type].map(function(value) {
                let available_buttons = $('.quick-view-size-lists[data-type="' + type +
                    '"] li[data-display-value="' + value + '"]');
                available_buttons.map(function(key, el) {
                    $(el).removeClass('disabled');
                })
            })
        });
        // todo check is empty object
        // selected_attributes_by_type
    }

    function quickViewSyncImage(selected_options) {
        //todo fire when attribute changed
        let hashed_key = getQuickViewSelectionHash(selected_options);

        let product_image_el = $('.quick-view-long-img img');

        let img_original_src = product_image_el.parent().data('src');

        // if selection has any image to it
        if (quick_view_additional_info_store[hashed_key]) {
            let attribute_image = quick_view_additional_info_store[hashed_key].image;
            if (attribute_image) {
                product_image_el.attr('src', attribute_image);
            }
        } else {
            product_image_el.attr('src', img_original_src);
        }
    }

    function quickViewSyncPrice(selected_options) {
        let hashed_key = getQuickViewSelectionHash(selected_options);

        let product_price_el = $('#quick-view-price');
        let product_main_price = Number(String(product_price_el.data('mainPrice'))).toFixed(2);
        let site_currency_symbol = product_price_el.data('currencySymbol');

        // if selection has any additional price to it
        if (quick_view_additional_info_store[hashed_key]) {
            let attribute_price = quick_view_additional_info_store[hashed_key]['additional_price'];
            if (attribute_price) {
                let price = Number(product_main_price) + Number(attribute_price);
                product_price_el.text(site_currency_symbol + Number(price).toFixed(2));
            }
        } else {
            product_price_el.text(site_currency_symbol + product_main_price);
        }
    }

    function quickViewSyncStock(selected_options) {
        let hashed_key = getQuickViewSelectionHash(selected_options);
        let product_stock_el = $('#quick_view_stock');
        let product_item_left_el = $('#quick_view_item_left');

        // if selection has any size and color to it

        if (quick_view_additional_info_store[hashed_key]) {
            let stock_count = quick_view_additional_info_store[hashed_key]['stock_count'];

            let stock_message = '';
            if (Number(stock_count) > 0 && Number(stock_count) != -1) {
                stock_message = `<span class="text-success">في المخزون</span>`;
                product_item_left_el.text(`Only! ${stock_count} Item Left!`);
                product_item_left_el.addClass('text-success');
                product_item_left_el.removeClass('text-danger');
            } else {
                stock_message = `<span class="text-danger">مخزوننا</span>`;
                product_item_left_el.text(`No Item Left!`);
                product_item_left_el.addClass('text-danger');
                product_item_left_el.removeClass('text-success');
            }

            product_stock_el.html(stock_message);
        } else {
            product_stock_el.html(product_stock_el.data("stock-text"))
            product_item_left_el.html(product_item_left_el.data("stock-text"))
        }
    }

    function attributeSelected() {
        let total_options_count = $('.quick-view-size-lists').length;
        let selected_options_count = $('.quick-view-size-lists li.active').length;
        return total_options_count === selected_options_count;
    }

    function addslashes(str) {
        return (str + '').replace(/[\\"']/g, '\\$&').replace(/\u0000/g, '\\0');
    }

    // function getQuickViewSelectionHash(selected_options) {
    //     return MD5(JSON.stringify(selected_options));
    // }

    // function get_quick_view_selected_options() {
    //     let selected_options = {};
    //     var quick_view_available_options = $('.quick-view-value-input-area');
    //     // get all selected attributes in {key:value} format
    //     quick_view_available_options.map(function (k, option) {
    //         let selected_option = $(option).find('li.active');
    //         let type = selected_option.closest('.quick-view-size-lists').data('type');
    //         let value = selected_option.data('displayValue');

    //         if (type && value) {
    //             selected_options[type] = value;
    //         }
    //     });

    //     let ordered_data = {};
    //     let selected_options_keys = Object.keys(selected_options).sort();
    //     selected_options_keys.map(function (e) {
    //         ordered_data[e] = selected_options[e];
    //     });

    //     return ordered_data;
    // }

    // function getQuickViewAttributesForCart() {
    //     let selected_options = get_quick_view_selected_options();
    //     let cart_selected_options = selected_options;
    //     let hashed_key = getQuickViewSelectionHash(selected_options);

    //     // if selected attribute set is available
    //     if (quick_view_additional_info_store[hashed_key]) {
    //         return quick_view_additional_info_store[hashed_key]['pid_id'];
    //     }

    //     // if selected attribute set is not available
    //     if  (Object.keys(selected_options).length) {
    //         toastr.error('السمة غير متاحة')
    //     }

    //     return '';
    // }

    // function quickViewValidateSelectedAttributes() {
    //     let selected_options = get_quick_view_selected_options();
    //     let hashed_key = getQuickViewSelectionHash(selected_options);

    //     // validate if product has any attribute
    //     if (quick_view_attribute_store.length) {
    //         if (!Object.keys(selected_options).length) {
    //             return false;
    //         }

    //         if (!quick_view_additional_info_store[hashed_key]) {
    //             return false;
    //         }

    //         return !!quick_view_additional_info_store[hashed_key]['pid_id'];
    //     }

    //     return true;
    // }

    $(document).on('click', '.quick_view_add_to_cart', function(e) {
        e.preventDefault();

        let quick_view_has_campaign = '0';
        let quick_view_campaign_expired = '0';

        if (quick_view_has_campaign === 1) {
            if (quick_view_campaign_expired === 0) {
                toastr.error('The campaign is over, Sorry! you can not cart this product');
                return false;
            }
        }

        let selected_size = $('#selected_size').val();
        let selected_color = $('#selected_color').val();

        let pid_id = getQuickViewAttributesForCart();

        let product_id = quick_view_product_id;
        let quantity = Number($('#quick-view-quantity').val().trim());
        let price = $('#price').text().split(site_currency_symbol)[1];
        let attributes = {};
        let product_variant = pid_id;
        let productAttribute = quick_view_selected_variant;

        attributes['price'] = price;

        // if selected attribute is a valid product item
        if (quickViewValidateSelectedAttributes()) {
            $.ajax({
                url: 'https://colorsjoycars.shop/shop/product/cart/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    quantity: quantity,
                    pid_id: pid_id,
                    product_variant: product_variant,
                    selected_size: selected_size,
                    selected_color: selected_color,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                beforeSend: function() {

                },
                success: function(data) {
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg);
                    } else if (data.error_msg) {
                        toastr.error(data.error_msg);
                    } else {
                        toastr.success(data.msg, 'الانتقال إلى السلة', '#', 60000);
                        $('.track-icon-list').hide();
                        $('.track-icon-list').load(location.href + " .track-icon-list");
                        $('.track-icon-list').fadeIn();
                    }
                },
                erorr: function(err) {
                    toastr.error('حدث خطأ')
                }
            });
        } else {
            toastr.error('اختر كل السمات للمتابعة')
        }
    });

    $(document).on('click', '.quick_view_add_to_wishlist', function(e) {
        e.preventDefault();

        let quick_view_has_campaign = '0';
        let quick_view_campaign_expired = '0';

        if (quick_view_has_campaign === 1) {
            if (quick_view_campaign_expired === 0) {
                toastr.error('The campaign is over, Sorry! you can not cart this product');
                return false;
            }
        }

        let selected_size = $('#selected_size').val();
        let selected_color = $('#selected_color').val();

        let pid_id = getQuickViewAttributesForCart();

        let product_id = quick_view_product_id;
        let quantity = Number($('#quick-view-quantity').val().trim());
        let price = $('#price').text().split(site_currency_symbol)[1];
        let attributes = {};
        let product_variant = pid_id;
        let productAttribute = quick_view_selected_variant;

        attributes['price'] = price;

        // if selected attribute is a valid product item
        if (quickViewValidateSelectedAttributes()) {
            $.ajax({
                url: 'https://colorsjoycars.shop/shop/product/wishlist/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    quantity: quantity,
                    pid_id: pid_id,
                    product_variant: product_variant,
                    selected_size: selected_size,
                    selected_color: selected_color,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                beforeSend: function() {

                },
                success: function(data) {
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg);
                    } else if (data.error_msg) {
                        toastr.error(data.error_msg);
                    } else {
                        toastr.success(data.msg, 'الانتقال إلى السلة', '#', 60000);
                        $('.track-icon-list').load(location.href + " .track-icon-list");
                    }
                },
                erorr: function(err) {
                    toastr.error('حدث خطأ')
                }
            });
        } else {
            toastr.error('اختر كل السمات للمتابعة')
        }
    });

    $(document).on('click', '.quick_view_but_now', function(e) {
        e.preventDefault();

        let quick_view_has_campaign = '0';
        let quick_view_campaign_expired = '0';

        if (quick_view_has_campaign === 1) {
            if (quick_view_campaign_expired === 0) {
                toastr.error('The campaign is over, Sorry! you can not cart this product');
                return false;
            }
        }

        let selected_size = $('#selected_size').val();
        let selected_color = $('#selected_color').val();

        let pid_id = getQuickViewAttributesForCart();

        let product_id = quick_view_product_id;
        let quantity = Number($('#quick-view-quantity').val().trim());
        let price = $('#price').text().split(site_currency_symbol)[1];
        let attributes = {};
        let product_variant = pid_id;
        let productAttribute = quick_view_selected_variant;

        attributes['price'] = price;

        // if selected attribute is a valid product item
        if (quickViewValidateSelectedAttributes()) {
            $.ajax({
                url: 'https://colorsjoycars.shop/shop/product/cart/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    quantity: quantity,
                    pid_id: pid_id,
                    product_variant: product_variant,
                    selected_size: selected_size,
                    selected_color: selected_color,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                beforeSend: function() {

                },
                success: function(data) {
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg);
                    } else if (data.error_msg) {
                        toastr.error(data.error_msg);
                    } else {
                        toastr.success(data.msg, 'الانتقال إلى السلة', '#', 60000);
                        $('.track-icon-list').load(location.href + " .track-icon-list");
                    }

                    setTimeout(() => {
                        location.href = "https://colorsjoycars.shop/shop/checkout";
                    }, 2000)
                },
                erorr: function(err) {
                    toastr.error('حدث خطأ')
                }
            });
        } else {
            toastr.error('اختر كل السمات للمتابعة')
        }
    });

    /* ========================================
                Product Quantity JS
    ========================================*/

    $(document).on('click', '.quick-view-plus', function() {
        var selectedInput = $(this).prev('.quick-view-quantity-input');
        if (selectedInput.val()) {
            selectedInput[0].stepUp(1);
        }
    });

    $(document).on('click', '.quick-view-substract', function() {
        var selectedInput = $(this).next('.quick-view-quantity-input');
        if (selectedInput.val() > 1) {
            selectedInput[0].stepDown(1);
        }
    });
</script>
<script>
    (function ($) {
        'use strict'

        // $("#product_quick_view .modal-content.p-5").niceScroll();

        let site_currency_symbol = ' ر.س';

        $('body').on('click', '.quick-view-size-lists li', function (event) {
            let el = $(this);
            let value = el.data('displayValue');
            let parentWrap = el.parent().parent();
            el.addClass('active');
            el.siblings().removeClass('active');
            parentWrap.find('input[type=text]').val(value);
            parentWrap.find('input[type=hidden]').val(el.data('value'));

            // selected attributes
            selectedAttributeSearch(this);
        });

        function selectedAttributeSearch(selected_item) {
            /*
            * search based on all selected attributes
            *
            * 1. get all selected attributes in {key:value} format
            * 2. search in attribute_store for all available matches
            * 3. display available matches (keep available matches selectable, and rest as disabled)
            * */

            let available_variant_types = [];
            let selected_options = {};

            // get all selected attributes in {key:value} format
            quick_view_available_options.map(function (k, option) {
                let selected_option = $(option).find('li.active');
                let type = selected_option.closest('.quick-view-size-lists').data('type');
                let value = selected_option.data('displayValue');

                if (type) {
                    available_variant_types.push(type);
                }

                if (type && value) {
                    selected_options[type] = value;
                }
            });

            quickViewSyncImage(get_quick_view_selected_options());
            quickViewSyncPrice(get_quick_view_selected_options());

            // search in attribute_store for all available matches
            let available_variants_selection = [];
            let selected_attributes_by_type = {};
            quick_view_attribute_store.map(function (arr) {
                let matched = true;

                Object.keys(selected_options).map(function (type) {

                    if (arr[type] !== selected_options[type]) {
                        matched = false;
                    }
                })

                if (matched) {
                    available_variants_selection.push(arr);

                    // insert as {key: [value, value...]}
                    Object.keys(arr).map(function (type) {
                        // not array available for the given key
                        if (!selected_attributes_by_type[type]) {
                            selected_attributes_by_type[type] = []
                        }

                        // insert value if not inserted yet
                        if (selected_attributes_by_type[type].indexOf(arr[type]) <= -1) {
                            selected_attributes_by_type[type].push(arr[type]);
                        }
                    })
                }
            });

            // selected item not contain product then de-select all selected option hare
            if (Object.keys(selected_attributes_by_type).length == 0) {
                $('.quick-view-size-lists li.active').each(function () {
                    let sizeItem = $(this).parent().parent();

                    sizeItem.find('input[type=hidden]').val('');
                    sizeItem.find('input[type=text]').val('');
                });

                $('.quick-view-size-lists li.active').removeClass("active");
                $('.quick-view-size-lists li.disabled-option').removeClass("disabled-option");

                let el = $(selected_item);
                let value = el.data('displayValue');

                el.addClass("active");
                $(this).find('input[type=hidden]').val(value);
                $(this).find('input[type=text]').val(el.data('value'));

                selectedAttributeSearch();
            }

            // keep only available matches selectable
            Object.keys(selected_attributes_by_type).map(function (type) {
                // initially, disable all buttons
                $('.quick-view-size-lists[data-type="' + type + '"] li').addClass('disabled-option');

                // make buttons selectable for the available options
                selected_attributes_by_type[type].map(function (value) {
                    let available_buttons = $('.quick-view-size-lists[data-type="' + type + '"] li[data-display-value="' + value + '"]');
                    available_buttons.map(function (key, el) {
                        $(el).removeClass('disabled-option');
                    })
                })
            });
            // todo check is empty object
            // selected_attributes_by_type
        }

        function quickViewSyncImage(selected_options) {
            //todo fire when attribute changed
            let hashed_key = getQuickViewSelectionHash(selected_options);
            let product_image_el = $('.quick-view-long-img img');

            let img_original_src = product_image_el.parent().data('src');

            // if selection has any image to it
            if (quick_view_additional_info_store[hashed_key]) {
                let attribute_image = quick_view_additional_info_store[hashed_key].image;
                if (attribute_image) {
                    product_image_el.attr('src', attribute_image);
                }
            } else {
                product_image_el.attr('src', img_original_src);
            }
        }

        function quickViewSyncPrice(selected_options) {
            let hashed_key = getQuickViewSelectionHash(selected_options);

            let product_price_el = $('#quick-view-price');
            let product_main_price = Number(String(product_price_el.data('mainPrice'))).toFixed(2);
            let site_currency_symbol = product_price_el.data('currencySymbol');

            // if selection has any additional price to it
            if (quick_view_additional_info_store[hashed_key]) {
                let attribute_price = quick_view_additional_info_store[hashed_key]['additional_price'];
                if (attribute_price) {
                    let price = Number(product_main_price) + Number(attribute_price);
                    product_price_el.text(site_currency_symbol + Number(price).toFixed(2));
                }
            } else {
                product_price_el.text(site_currency_symbol + product_main_price);
            }
        }

        $('body').on('click', '.add_to_cart_single_page_quick_view',function (e) {
            e.preventDefault();
            let selected_size = $('#quick_view_selected_size').val();
            let selected_color = $('#quick_view_selected_color').val();

            $(".quick-view-size-lists.active")

            let pid_id = getQuickViewAttributesForCart();

            let product_id = $(this).data('id');
            let quantity = Number($('#quick-view-quantity').val().trim());
            let price = $('#quick-view-price').text().split(site_currency_symbol)[1];
            let attributes = {};
            let product_variant = pid_id;

            attributes['price'] = price;

            // if selected attribute is a valid product item
            if (quickViewValidateSelectedAttributes()) {
                $.ajax({
                    url: 'https://colorsjoycars.shop/shop/product/cart/add',
                    type: 'POST',
                    data: {
                        product_id: product_id,
                        quantity: quantity,
                        pid_id: pid_id,
                        product_variant: product_variant,
                        selected_size: selected_size,
                        selected_color: selected_color,
                        attributes: attributes,
                        _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                    },
                    success: function (data) {
                        toastr.success(data.msg);
                        if (data.quantity_msg) {
                            toastr.warning(data.quantity_msg)
                        }

                        refreshShippingDropdown();
                    },
                    erorr: function (err) {
                        toastr.error('حدث خطأ');
                    }
                });
            } else {
                toastr.error('اختر كل السمات للمتابعة');
            }
        });

        let productQuickViewModel = document.getElementById("product_quick_view");
        let defaultQuickViewModel = document.getElementById("quick_view");

        window.onclick = function (event){
            if(productQuickViewModel == event.target){
                $("#product_quick_view").fadeOut();
                setTimeout(function (){
                    $("#product_quick_view").empty();
                },200);
            }else if(defaultQuickViewModel == event.target){
                $("#quick_view").fadeOut();
                $("#quick_view").removeClass('show');
                $(".modal-backdrop").fadeOut();
            }

            $("html body").removeClass("stop-scroll")
        }

        $(document).on('click','.add_to_cart_ajax', function (e) {
            e.preventDefault();
            let product_id = $(this).data('id');
            let quickViewQty = $("#quantity_single_quick_view_btn").val();
            quickViewQty = quickViewQty != undefined ? quickViewQty.trim() : 1;
            let quantity = Number(quickViewQty);
            $.ajax({
                url: 'https://colorsjoycars.shop/shop/product/cart/add',
                type: 'POST',
                data: {
                    product_id: product_id,
                    quantity: quantity,
                    product_attributes: null,
                    _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                },
                success: function (data) {
                    toastr.success(data.msg);
                    if (data.quantity_msg) {
                        toastr.warning(data.quantity_msg)
                    }
                    refreshShippingDropdown();
                },
                erorr: function (err) {
                    toastr.error('حدث خطأ');
                }
            });
        });

        // open modal with product quick view
        $(document).on("click",".product-quick-view-ajax",function (){
            let action_route = $(this).data('action-route');

            let icon = $(this).find("i");
            let oldIconClass = icon.attr("class");
            icon.attr("class","las la-spinner icon la-spin");

            $.ajax({
                url: action_route,
                type: 'GET',
                success: function (data) {
                    icon.attr("class",oldIconClass);

                    $("#product_quick_view").html(data);
                    $("#product_quick_view").fadeIn();


                    $("html body").addClass("stop-scroll")
                },
                erorr: function (err) {
                    toastr.error('حدث خطأ');
                }
            });
        });

        // close quick view details model and make empty
        $(document).on("click","#product_quick_view .quick-view-close-btn",function (){
            $("#product_quick_view").fadeOut();

            setTimeout(function (){
                $("#product_quick_view").empty();
            },200);
        });

        $(document).on("click","#quick_view .quick-view-close-btn",function (){
            $("#quick_view").fadeOut();
            $("#quick_view").removeClass('show');
            $(".modal-backdrop").fadeOut();
        });

        $(document).on('click','.quick-view', function (e) {
            e.preventDefault();

            //todo: work on showing campaign date countdown


            let data = $(this).data();
            let rating = $(this).data('rating');
            let stock_msg = "العنصر غير متوفر في المخزون";
            let stock_msg_type = "text-danger";
            let quick_view = $('#quick_view');
            quick_view.find('.flash-countdown-wrapper').hide();
            if(data.iscampaign){
                quick_view.find('.flash-countdown-title').text(data.campaigntitle);
                quick_view.find('.flash-countdown-product-2').attr('data-date',data.campaigndate);
                let coundClass = quick_view.find('.flash-countdown-product-2');
                let oldId = quick_view.find('.flash-countdown-product-2').attr('id');
                coundClass.removeClass(oldId);
                oldId = oldId.substr(35);

                let newClassGen = Math.random().toString(36).substring(2, 15) + Math.random().toString(36).substring(2, 15) + Math.random().toString(36).substring(2, 15);
                coundClass.addClass(oldId+newClassGen);
                coundClass.attr('id',oldId+newClassGen);

                loopcounter(quick_view.find('.flash-countdown-product-2').attr('id'));
                quick_view.find('.flash-countdown-wrapper').show();
            }


            quick_view.find('a.add-to-cart').data('id', data['id']);

            quick_view.find('.title').text(data['title']);
            quick_view.find('.info').text(data['summary']);
            quick_view.find('.del_price').text(data['price']);
            quick_view.find('.sale_price').text(data['salePrice']);
            quick_view.find('.product_category').text(data['category']);
            quick_view.find('.product_category').attr('href', data['categoryUrl']);
            quick_view.find('.product-img img').attr('src', data['image']);
            quick_view.find('.sku_wrapper .sku').text(data['inventory']);
            quick_view.find('.badge-tag').text(data['badge']);
            if(data['campaignPercentage']){
                quick_view.find('.discount-tag').text(data['campaignPercentage']);
            }else{
                quick_view.find('.discount-tag').text('');
            }

            quick_view.find('#unit').text(data['unit']);
            quick_view.find('#uom').text(data['uom']);

            // inventory
            if (data['inStock']) {
                stock_msg = "In stock " + data['inStock'];
                stock_msg_type = "text-success";
            }

            quick_view.find('.is_available').text(stock_msg);
            quick_view.find('.is_available').addClass(stock_msg_type);

            if (data['inventory'] && data['inventory'].length) {
                quick_view.find('.sku_wrapper').show();
            }

            // subcategory
            let subcategory_html = '';
            let subcategory = data['subcategory'];

            for (let i = 0; i < subcategory.length; i++) {
                let comma = '';
                if (i < subcategory.length - 1) {
                    comma += ', ';
                }
                subcategory_html += '<a href="' + subcategory[i]['url'] + '" class="tag-btn" rel="tag">' + subcategory[i]['name'] + '</a>' + comma;
            }

            quick_view.find('.subcategory_container').html(subcategory_html);

            if (!subcategory_html.length) {
                quick_view.find('.product-details-tag-and-social-link').hide();
            } else {
                quick_view.find('.product-details-tag-and-social-link').show();
            }

            if (subcategory_html.length <= 0) {
                $('.productview_subcategory').hide();
            } else {
                $('.productview_subcategory').show()
            }

            // rating
            let rating_html = '';
            for (let i = 0; i < Number(rating); i++) {
                rating_html += '<i class="las la-star icon"></i>';
            }

            for (let i = Math.ceil(Number(rating)); i < 5; i++) {
                rating_html += '<i class="lar la-star icon"></i>';
            }

            quick_view.find('.ratings').html(rating_html);

            if (Number(rating)) {
                quick_view.find('.ratings').show();
            } else {
                quick_view.find('.ratings').hide();
            }

            // quick_view.modal('show');
            $("#quick_view").fadeIn();
            $("#quick_view").addClass('show');
            $(".modal-backdrop").fadeIn();
        });

        $(document).ready(function () {
            refreshShippingDropdown();

            $('.add_to_cart_ajax_with_quantity').on('click', function (e) {
                e.preventDefault();
                let product_id = $(this).data('id');
                let quantity = $(this).closest('.product_card').find('.hover-content .qty_').val();
                $.ajax({
                    url: 'https://colorsjoycars.shop/shop/product/cart/add',
                    type: 'POST',
                    data: {
                        product_id: product_id,
                        quantity: quantity,
                        product_attributes: null,
                        _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                    },
                    success: function (data) {
                        if(data.type == 'danger'){
                            toastr.error(data.msg);
                        }else{
                            toastr.success(data.msg);
                        }

                        if (data.quantity_msg) {
                            toastr.warning(data.quantity_msg)
                        }
                        refreshShippingDropdown();
                    },
                    erorr: function (err) {
                        toastr.error('حدث خطأ');
                    }
                });
            });

            $('.attribute input[type=radio]').on('click', function () {
                let attribute_img_el = $('.attribute_img');
                let total_extra = 0;
                let main_price = Number($('#price').data('mainPrice'));
                let all_checked = $('.attribute input[type=radio]:checked');

                // image
                if ($(this).data('attrImage')) {
                    attribute_img_el.attr('src', $(this).data('attrImage')).show();
                    attribute_img_el.closest('.single-main-image').find('.magnific').attr('href', $(this).data('attrImage'));
                    attribute_img_el.prev().hide();
                } else {
                    attribute_img_el.hide();
                    attribute_img_el.prev().show();
                }

                //price
                for (let i = 0; i < all_checked.length; i++) {
                    total_extra += Number($(all_checked[i]).siblings('span').data('extra'));
                }
                let new_price = main_price + total_extra;
                $('#price').text(site_currency_symbol + parseFloat(new_price).toFixed(2));
            });

            $('.add_to_wishlist_ajax').on('click', function (e) {
                e.preventDefault();
                let product_id = $(this).data('id');
                $.ajax({
                    url: 'https://colorsjoycars.shop/shop/product/wishlist/add',
                    type: 'POST',
                    data: {
                        product_id: product_id,
                        quantity: 1,
                        pid_id: null,
                        _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                    },
                    success: function (data) {
                        toastr.success(data.msg);
                    },
                    erorr: function (err) {
                        toastr.error('حدث خطأ');
                    }
                });
            });

            $('.nav_search_btn').on('click', function (e) {
                e.preventDefault();
                if ($('.search_bar .form-group .form-control').val().length) {
                    $('#product_search_form').trigger('submit');
                } else {
                    $('.search_bar .form-group').toggle('fast', 'swing');
                }
            });

            // view data with



            $('.add_to_compare_ajax').on('click', function (e) {
                e.preventDefault();
                let product_id = $(this).data('id');
                $.ajax({
                    url: 'https://colorsjoycars.shop/shop/compare/items',
                    type: 'POST',
                    data: {
                        product_id: product_id,
                        _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                    },
                    success: function (data) {
                        if (data) {
                            toastr.success('العنصر تمت إضافته للمقارنة');
                        }
                    },
                    erorr: function (err) {
                        toastr.error('حدث خطأ');
                    }
                });
            });

            $('body').on('click','.add_to_compare_ajax_single_page_quick_view', function (e) {
                e.preventDefault();
                let product_id = $(this).data('id');
                $.ajax({
                    url: 'https://colorsjoycars.shop/shop/compare/items',
                    type: 'POST',
                    data: {
                        product_id: product_id,
                        _token: 'ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD'
                    },
                    success: function (data) {
                        if (data) {
                            toastr.success('العنصر تمت إضافته للمقارنة');
                        }
                    },
                    erorr: function (err) {
                        toastr.error('حدث خطأ');
                    }
                });
            });

            $(document).on('click', '.quick-view', function (e) {
                e.preventDefault();
                loadProductAttributeHtml($(this).data('slug'));
            });

            $(document).on('click', '#close_search_dropdown', function (e) {
                $('.category-searchbar').hide();
            });

            $(document).on('focus', '#search_form_input', function (e) {
                if ($('#search_result_categories').html().length && $('#search_result_products').html().length) {
                    $('.category-searchbar').show();
                }
            });

            /* Nice Scroll */
            // $(".category-searchbar").niceScroll({});
        });

        function refreshShippingDropdown() {

        }

        function loadFilterData(url) {
            $('.lds-ellipsis').show();
            $.ajax({
                url: url,
                type: 'GET',
                success: function (data) {
                    if (data) {
                        $('#product_filter_section').html(data);
                        $('.lds-ellipsis').hide();
                    }
                },
                erorr: function (err) {
                    toastr.error('حدث خطأ');
                    $('.lds-ellipsis').hide();
                }
            });
        }
    })(jQuery)

    function attributeSelected() {
        let total_options_count = $('.quick-view-size-lists').length;
        let selected_options_count = $('.quick-view-size-lists li.active').length;
        return total_options_count === selected_options_count;
    }

    function addslashes(str) {
        return (str + '').replace(/[\\"']/g, '\\$&').replace(/\u0000/g, '\\0');
    }

    function getQuickViewSelectionHash(selected_options) {
        return MD5(JSON.stringify(selected_options));
    }

    function get_quick_view_selected_options() {
        let selected_options = {};
        var quick_view_available_options = $('.quick-view-value-input-area');
        // get all selected attributes in {key:value} format
        quick_view_available_options.map(function (k, option) {
            let selected_option = $(option).find('li.active');
            let type = selected_option.closest('.quick-view-size-lists').data('type');
            let value = selected_option.data('displayValue');

            if (type && value) {
                selected_options[type] = value;
            }
        });

        let ordered_data = {};
        let selected_options_keys = Object.keys(selected_options).sort();
        selected_options_keys.map(function (e) {
            ordered_data[e] = selected_options[e];
        });

        return ordered_data;
    }

    function getQuickViewAttributesForCart() {
        let selected_options = get_quick_view_selected_options();
        let cart_selected_options = selected_options;
        let hashed_key = getQuickViewSelectionHash(selected_options);

        // if selected attribute set is available
        if (quick_view_additional_info_store[hashed_key]) {
            return quick_view_additional_info_store[hashed_key]['pid_id'];
        }

        // if selected attribute set is not available
        if  (Object.keys(selected_options).length) {
            toastr.error('السمة غير متاحة')
        }

        return '';
    }

    function send_ajax_response_get_response(type,url){
        $.ajax({
            url: url,
            type: type,
            data: {
                style: "two",
                limit: $(".product-filter-two-wrapper").data("item-limit")
            },
            headers: {
                'X-CSRF-TOKEN': "ef8PugtpAvtFZqcfRJFSKdXlo8YIXZ9FMmHmBNJD",
            },
            beforeSend:function (){
                $(".product-filter-two-wrapper").attr("style","height:912px");
                $(".filter-style-block-preloader.lds-ellipsis").show();
            },
            success: function (data) {
                $(".filter-style-block-preloader.lds-ellipsis").hide(300);
                $(".product-filter-two-wrapper").removeAttr("style");
                $(".product-filter-two-wrapper").html(data).removeAttr("style");

                if(data.success == false){
                    toastr.warning('There something is wrong please try again');
                }
            },
            erorr: function (err) {
                $(".product-filter-two-wrapper").removeAttr("style");
                $(".filter-style-block-preloader.lds-ellipsis").hide(300);
                toastr.error('حدث خطأ');
            }
        });
    }

    function quickViewValidateSelectedAttributes() {
        let selected_options = get_quick_view_selected_options();
        let hashed_key = getQuickViewSelectionHash(selected_options);

        // validate if product has any attribute
        if (quick_view_attribute_store.length) {
            if (!Object.keys(selected_options).length) {
                return false;
            }

            if (!quick_view_additional_info_store[hashed_key]) {
                return false;
            }

            return !!quick_view_additional_info_store[hashed_key]['pid_id'];
        }

        return true;
    }
</script>

            <script src='https://colorsjoycars.shop/assets/plugins/purify.min.js'></script>
            <script>
                document.addEventListener('cart:updated', function () {
                        $.ajax({
                            url: 'https://colorsjoycars.shop/__sendrequest/w/marketing:shipping_indicator',
                            type: 'GET',
                            success: async function (data) {
                                try {
                                    var el = document.getElementById('wdgt_shipping_indicator')

                                    if(data.data > 0)
                                        $('#wdgt_shipping_indicator__wrapper').removeClass('d-none')

                                    var minOrder = $(el).data('min_order')
                                    minOrder = DOMPurify.sanitize(minOrder)
                                    minOrder = minOrder === '' ? 0 : minOrder
                                    minOrder = parseInt(minOrder)

                                    if(isNaN(minOrder))
                                        throw new Error('XSS detected. Min order is NaN');

                                    progress = (data.data / minOrder) * 100

                                    var prevWidth  = $(el).data('width')
                                    prevWidth = DOMPurify.sanitize(prevWidth)
                                    prevWidth = prevWidth === '' ? 0 : prevWidth
                                    prevWidth = parseInt(prevWidth)

                                    if(isNaN(prevWidth))
                                        throw new Error('XSS detected. Previous width is NaN');

                                    progress = progress > 100 ? 100 : progress
                                    prevWidth = prevWidth > 100 ? 100 : prevWidth

                                    if(progress < prevWidth) {
                                        for(var i = prevWidth ; i >= progress ; i--) {
                                            await new Promise(res => {
                                                $(el).css('width', i + '%');
                                                $(el).data('width', i);
                                                $('#wdgt_shipping_indicator > i').html(i + '%')
                                                setTimeout(() => res(1), 10)
                                            })
                                        }
                                    } else {
                                        for(var i = progress ; i >= prevWidth ; prevWidth++) {
                                            await new Promise(res => {
                                                $(el).css('width', prevWidth + '%');
                                                $(el).data('width', prevWidth);
                                                $('#wdgt_shipping_indicator > i').html(prevWidth + '%')
                                                setTimeout(() => res(1), 10)
                                            })
                                        }
                                    }

                                } catch (e) {
                                    if(typeof e == 'object') {
                                        toastr.error(e.message)
                                    }
                                }
                            }
                        })
                })
            </script>
        
            <script async src="https://www.googletagmanager.com/gtag/js?id=G-TPBYXR43SP"></script>
            <script>
                window.dataLayer = window.dataLayer || [];
                function gtag(){dataLayer.push(arguments);}
                gtag("js", new Date()); 
                gtag("config", "G-TPBYXR43SP");
            </script>
        <style>
            ._wa{
                width: 60px;
                height: 60px;
                background-color: #118c7e;
                border-radius: 50%;
                position: fixed;
                bottom: 15px;
                right: 20px;
                box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
                display: flex;
                align-items: center;
                justify-content: center;
                color: white;
                font-size: 24px;
                transition: all 0.3s ease;
                z-index: 1000000;
            }
            ._wa:hover {
                transform: scale(1.1);
                color:white;
                box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
                z-index: 10000001111;
            }

            @media(max-width:992px){
                ._wa{
                    bottom: 75px;
                    right: 12px;
                }
                ._wa.bottom_hide{
                    bottom: 15px;
                }
                .widget-visible iframe[style*="bottom:20px"] {
                    translate: 12px -55px !important;
                }
            }

        </style>

        <div>
            <a target="_blank" href="https://wa.me/590375422" class="_wa tbadge " aria-label="whatsapp">
                <svg width="30" height="30" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 308 308" xml:space="preserve"><path d="M227.904 176.981c-.6-.288-23.054-11.345-27.044-12.781-1.629-.585-3.374-1.156-5.23-1.156-3.032 0-5.579 1.511-7.563 4.479-2.243 3.334-9.033 11.271-11.131 13.642-.274.313-.648.687-.872.687-.201 0-3.676-1.431-4.728-1.888-24.087-10.463-42.37-35.624-44.877-39.867-.358-.61-.373-.887-.376-.887.088-.323.898-1.135 1.316-1.554 1.223-1.21 2.548-2.805 3.83-4.348a141 141 0 0 1 1.812-2.153c1.86-2.164 2.688-3.844 3.648-5.79l.503-1.011c2.344-4.657.342-8.587-.305-9.856-.531-1.062-10.012-23.944-11.02-26.348-2.424-5.801-5.627-8.502-10.078-8.502-.413 0 0 0-1.732.073-2.109.089-13.594 1.601-18.672 4.802C90 87.918 80.89 98.74 80.89 117.772c0 17.129 10.87 33.302 15.537 39.453.116.155.329.47.638.922 17.873 26.102 40.154 45.446 62.741 54.469 21.745 8.686 32.042 9.69 37.896 9.69h.001c2.46 0 4.429-.193 6.166-.364l1.102-.105c7.512-.666 24.02-9.22 27.775-19.655 2.958-8.219 3.738-17.199 1.77-20.458-1.348-2.216-3.671-3.331-6.612-4.743"/><path d="M156.734 0C73.318 0 5.454 67.354 5.454 150.143c0 26.777 7.166 52.988 20.741 75.928L.212 302.716a3.998 3.998 0 0 0 4.999 5.096l79.92-25.396c21.87 11.685 46.588 17.853 71.604 17.853C240.143 300.27 308 232.923 308 150.143 308 67.354 240.143 0 156.734 0m0 268.994c-23.539 0-46.338-6.797-65.936-19.657a4 4 0 0 0-3.406-.467l-40.035 12.726 12.924-38.129a4 4 0 0 0-.561-3.647c-14.924-20.392-22.813-44.485-22.813-69.677 0-65.543 53.754-118.867 119.826-118.867 66.064 0 119.812 53.324 119.812 118.867.001 65.535-53.746 118.851-119.811 118.851"/></svg>
            </a>
        </div>
</body>

</html>
<script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/lodash@4.17.21/lodash.min.js"></script>


<script>
    document.addEventListener('alpine:init', () => {
        Alpine.data('cart', () => ({

            cartLastUpdated: null,

            requestHeaders: {
                "Content-type": "application/json; charset=UTF-8",
                "X-Requested-With": 'XMLHttpRequest',
                "X-CSRF-TOKEN": $('meta[name="csrf-token"]').attr('content')
            },

            cart: [],
            pageData: null,
            meta: {
                formatted_subtotal: 0,
                formatted_total: 0,
                subtotal: 0,
                total: 0
            },
            fetching: false,
            saving: false,
            updating: false,
            selected: null,

            // API Calls
            async getCart() {
                try {
                    this.fetching = true

                    const response = await fetch('/shop/v2/cart', {
                        headers: this.requestHeaders
                    })
                    const data = await response.json()

                    this.cart = [...data?.data]
                    this.meta = {...data?.meta}
                    localStorage.setItem('cart', JSON.stringify([...data?.data]))
                    localStorage.setItem('cart_meta', JSON.stringify({...data?.meta}))
                    localStorage.setItem('cart_updated_at', new Date().getTime())
                    localStorage.setItem('app_version', ('v1.77.5').replace(/\D/g, ""))

                } catch (error) {
                    console.error(error)
                } finally {
                    this.fetching = false
                }
            },

            async updateCart(id, quantity, type = 1) {
                try {
                    this.selected = id

                    this.updating = true

                    const response = await fetch('/shop/v2/cart/' + id, {
                        method: 'PUT',
                        body: JSON.stringify({
                            quantity,
                            type
                        }),
                        headers: this.requestHeaders
                    })
                    const data = await response.json()

                    if (response.ok) {
                        toastr.success(data.message)
                        this.updateDataAndSetMeta(data)
                        document.dispatchEvent(new CustomEvent('cart:updated'))
                        // await this.getCart()
                    } else if (response.status === 422) {
                        toastr.error(data.message);
                        await this.getCart()
                    } else {
                        await this.getCart()
                    }
                } catch (error) {
                    console.error(error)
                } finally {
                    this.selected = null
                    this.updating = false
                }
            },

            async addCart(
                {
                    id: productId,
                    pid,
                    product_variant,
                    selected_size,
                    selected_color,
                    product_options,
                    quantity = 1,
                    toCheckout = false,
                    isBooking = false,
                    selectedBookingDate = null,
                    selectedBookingTimeStart = null,
                    selectedBookingTimeEnd = null,
                    selectedProvider
                },
                isDigital = 1
            ) {
                if (this.saving)
                    return;

                let el = document.querySelector('.addItem-' + productId + '-' + isDigital)
                el = $(el)

                if (false) {
                    let product_card_a_href = el.parent('a').attr('data-product_url');
                    window.location.href = product_card_a_href;
                    return;
                }

                let oldClass = '';

                if (el.hasClass('las la-shopping-cart')) {
                    oldClass = 'las la-shopping-cart';
                } else if (el.hasClass('fa fa-plus')) {
                    oldClass = 'fa fa-plus'
                }

                // selectedBookingDate = (() => {
                //     if (selectedBookingDate === null || selectedBookingDate.split('/').length < 3)
                //         return null;

                //     let [month, day, year] = selectedBookingDate.split('/')
                //     if (month.length === 1)
                //         month = `0${month}`

                //     if (day.length === 1)
                //         day = `0${day}`

                //     return `${month}/${day}/${year}`;
                // })()

                el.removeClass(oldClass).addClass('las la-spinner la-spin');
                try {
                    this.selected = productId
                    this.saving = true
                    const response = await fetch('/shop/v2/cart', {
                        method: 'POST',
                        body: JSON.stringify({
                            product_id: productId,
                            quantity,
                            pid_id: pid,
                            product_variant,
                            selected_size,
                            selected_color,
                            product_options,
                            is_booking: isBooking,
                            booking_date: selectedBookingDate,
                            booking_start: selectedBookingTimeStart,
                            booking_end: selectedBookingTimeEnd,
                            provider_id: selectedProvider
                        }),
                        headers: this.requestHeaders,
                    })

                    const data = await response.json()

                    if (response.ok) {
                        toastr.success(data.message);
                        el.parent().addClass('active');
                        document.dispatchEvent(new CustomEvent('cart:updated'))
                        this.addDataAndSetMeta(data)
                        this.updateDataAndSetMeta(data)

                        document.dispatchEvent(new CustomEvent('cart:addedNewItem', {
                            detail: {
                                id: data?.data?.id ?? '',
                                slug: data?.data?.details_url ?? '',
                                name: data?.data?.name ?? '',
                                image: data?.data?.image ?? '',
                                price: data?.data?.price ?? '',
                                formatted_price: data?.data?.formatted_price ?? '',
                                quantity: data?.data?.qty ?? '',
                                type: data?.data?.type ?? '',
                            }
                        }))

                        if (toCheckout)
                            location.href = 'https://colorsjoycars.shop/shop/checkout'
                        // await this.getCart()
                    } else if (response.status === 422) {
                        toastr.error(data.message);
                        await this.getCart()
                    } else {
                        toastr.error(data.message);
                    }

                } catch (error) {
                    console.error(error)
                    toastr.error(error.response?.data?.message);
                } finally {
                    this.selected = null
                    this.saving = false

                    setTimeout(() => {
                        el.parent().removeClass('active');
                        el.removeClass('las la-spinner la-spin').addClass(oldClass);
                    }, 500)
                }
            },

            async removeCart() {
                if (this.selected === null)
                    return;

                try {
                    let id = this.selected
                    const response = await fetch('/shop/v2/cart/' + id, {
                        method: 'DELETE',
                        headers: this.requestHeaders
                    })
                    const data = await response.json()

                    if (response.ok) {
                        toastr.success(data.message);
                        this.removeDataAndSetMeta(id, data)
                        document.dispatchEvent(new CustomEvent('cart:updated'))
                        // await this.getCart()
                    } else {
                        this.selected = null
                    }
                } catch (error) {
                    console.error(error)
                    toastr.error('Something wrong with your request')
                } finally {
                }
            },

            isInCart(productId) {
                return this.cart.some(item => parseInt(item.id) == productId)
            },

            getCartInstance(productId) {
                if (this.cart.length === 0)
                    return;

                let index = _.findIndex([...this.cart.map(item => {
                    item.id = parseInt(item.id)
                    return item;
                })], {
                    id: parseInt(productId)
                })

                this.pageData = this.cart[index] ?? null

                return this.cart[index] ?? null
            },

            openDeleteAlert(id) {
                this.selected = id
                Swal.fire({
                    title: "هل ترغب في إزالة هذا العنصر من سلة التسوق؟",
                    icon: "warning",
                    showCloseButton: true,
                    confirmButtonColor: "#dc3545",
                    confirmButtonText: "حذف",
                    customClass: {
                        popup: 'remove-cart-popup',
                    }
                }).then((result) => {
                    if (result.isConfirmed) {
                        this.removeCart()
                    } else {
                        this.selected = false
                    }
                }).catch(() => {
                    this.selected = false
                }).finally(() => {
                    this.selected = false
                })
            },

            /**
             * Mutators
             */
            updateDataAndSetMeta(responseData) {
                if (!('meta' in responseData) && !('data' in responseData))
                    return;

                let data = responseData.data
                let meta = responseData.meta

                const prodExist = _.findIndex(this.cart, {
                    rowId: data.rowId,
                    type: data.type
                })

                if (prodExist >= 0) {
                    this.cart[prodExist] = {...data}
                    this.meta = {...meta}
                    localStorage.setItem('cart', JSON.stringify([...this.cart]))
                    localStorage.setItem('cart_meta', JSON.stringify({...this.meta}))
                    localStorage.setItem('cart_updated_at', new Date().getTime())
                }

            },
            addDataAndSetMeta(responseData) {
                if (!('meta' in responseData) && !('data' in responseData))
                    return;

                let data = responseData.data
                let meta = responseData.meta

                const prodExist = _.findIndex(this.cart, {
                    rowId: data.rowId,
                    type: data.type
                })

                if (prodExist >= 0)
                    return;

                this.cart.unshift(data)
                this.meta = {...meta}
                localStorage.setItem('cart', JSON.stringify([...this.cart]))
                localStorage.setItem('cart_meta', JSON.stringify({...this.meta}))
                localStorage.setItem('cart_updated_at', new Date().getTime())
            },

            removeDataAndSetMeta(id, responseData) {
                if (!('meta' in responseData))
                    return;

                let meta = responseData.meta

                const prodExist = _.findIndex(this.cart, {
                    rowId: id
                })

                if (prodExist >= 0) {
                    this.cart.splice(prodExist, 1)
                    this.meta = {...meta}
                    localStorage.setItem('cart', JSON.stringify([...this.cart]))
                    localStorage.setItem('cart_meta', JSON.stringify({...this.meta}))
                    localStorage.setItem('cart_updated_at', new Date().getTime())
                }
            },

            /**
             * Local Storage
             */
            ensureValidCartResources(data) {
                return new Promise((resolve, reject) => {
                    try {
                        if (!Array.isArray(data))
                            reject('Not an array')

                        let resourceKeys = [
                            'rowId',
                            'id',
                            'image',
                            'name',
                            'options',
                            'price',
                            'qty',
                            'random_timestamp',
                            'subtotal',
                            'tax',
                            'type',
                            'weight',
                            'details_url',
                            'formatted_price',
                            'discount'
                        ];

                        const isValid = data.map(e => {
                            return resourceKeys.map(key => key in e)
                                .every(item => item === true)
                        })

                        if (isValid) {
                            resolve(true)
                        } else {
                            reject('invalid keys')
                        }
                    } catch (e) {
                        reject(e)
                    }
                })
            },

            setItemsToCart(data) {
                return new Promise((resolve, reject) => {
                    try {
                        if (!Array.isArray(data))
                            reject('Not an array')

                        this.cart = [...data]
                        resolve(true)

                    } catch (e) {
                        reject(e)
                    }
                })
            },

            timeDifference(timestamp1, timestamp2) {
                let difference = timestamp1 - timestamp2;

                return Math.floor(difference / 1000 / 60);
            },

            async getLocalStorageCart() {
                try {
                    let lastUpdated = localStorage.getItem('cart_updated_at')
                    let localVersion = localStorage.getItem('app_version')

                    if (
                        lastUpdated === null
                        || localVersion === null
                        || isNaN(lastUpdated)
                        || isNaN(localVersion)
                        || this.timeDifference(new Date().getTime(), lastUpdated) >= 5
                        || localVersion !== ('v1.77.5').replace(/\D/g, "")
                    ) {
                        await this.getCart()
                        return;
                    }

                    let data = localStorage.getItem('cart')
                    let meta = localStorage.getItem('cart_meta')
                    meta = JSON.parse(meta)
                    data = JSON.parse(data)
                    await this.ensureValidCartResources(data)
                    await this.setItemsToCart(data)

                    if ('formatted_subtotal' in meta && 'formatted_total' in meta) {
                        this.meta = {...meta}
                    }
                } catch (e) {
                    console.error(e)
                    await this.getCart()
                }
            },

            // Getters
            get cartTotal() {
                return 0
            },

            init() {
                this.getCart()
                this.getLocalStorageCart()

                document.addEventListener('cart:add', (e) => {
                    let id = e.detail?.id
                    let pid = e.detail?.pid_id
                    let quantity = e.detail?.quantity ?? 1
                    let product_variant = e.detail?.product_variant
                    let selected_size = e.detail?.selected_size
                    let selected_color = e.detail?.selected_color
                    let product_options = e.detail?.product_options
                    let isDigital = e.detail?.digital ?? 0
                    let toCheckout = e.detail?.to_checkout ?? false
                    let isBooking = e.detail?.isBooking ?? false
                    let selectedBookingDate = e.detail?.selectedBookingDate ?? null
                    let selectedBookingTimeStart = e.detail?.selectedBookingTimeStart ?? null
                    let selectedBookingTimeEnd = e.detail?.selectedBookingTimeEnd ?? null
                    let selectedProvider = e.detail?.selectedProvider ?? null

                    this.addCart({
                        quantity,
                        id,
                        pid,
                        product_variant,
                        selected_size,
                        selected_color,
                        product_options,
                        toCheckout,
                        isBooking,
                        selectedBookingDate,
                        selectedBookingTimeStart,
                        selectedBookingTimeEnd,
                        selectedProvider
                    }, isDigital)
                })

                document.addEventListener('cart:update', e => {
                    let id = e.detail?.id
                    let quantity = e.detail?.quantity
                    let type = e.detail?.type

                    this.updateCart(id, quantity, type)
                })

                document.addEventListener('cart:get-instance', e => {
                    let id = e.detail?.id

                    this.getCartInstance(id)
                })

                setInterval(() => {
                    this.getCart();
                }, 50000);
            }
        }))

        Alpine.data('cartItem', ({id, quantity, type = 1, autoUpdate = true}) => ({
            id,
            type,
            quantity,
            autoUpdate,
            handleQuantityUpdate: _.debounce((this_) => {
                let uQuantity = this_.quantity
                if (this_.quantity <= 0) {
                    uQuantity = 1
                }

                document.dispatchEvent(new CustomEvent('cart:update', {
                    detail: {
                        id: this_.id,
                        quantity: uQuantity,
                        type: this_.type
                    }
                }))
            }, 500),
            init() {
                if (this.autoUpdate)
                    this.quantity = quantity
                else
                    this.quantity = 1

                this.$watch('quantity', () => {
                    if (this.autoUpdate)
                        this.handleQuantityUpdate(this)
                })
            }
        }))

        Alpine.data('wishlistCart', () => ({
            items: [],
            count: '',
            fetching: true,
            updateCount(count) {
                document.querySelectorAll('[wishlistCount]').forEach(el => {
                    el.innerText = count
                })
            },
            init() {
                this.getItems()
                document.addEventListener('wishlist:updated', (e) => {
                    this.count = e?.detail?.count,
                        this.items = e?.detail?.items
                });

                this.$nextTick(() => {
                    this.updateCount(this.count)
                })

                this.$watch('count', value => this.updateCount(value))
            },
            async getItems() {
                this.fetching = true
                try {
                    const response = await fetch('/shop/wishlist/product/fetch', {
                        headers: {
                            "Content-type": "application/json; charset=UTF-8",
                            "X-Requested-With": 'XMLHttpRequest',
                            "X-CSRF-TOKEN": $('meta[name="csrf-token"]').attr('content')
                        }
                    })
                    const data = await response.json()
                    this.count = data.count
                    this.items = data.items
                    this.fetching = false
                } catch (error) {
                    console.error(error)
                }
            },
            async deleteItem(id) {
                const $this = this
                $this.fetching = true
                Swal.fire({
                    title: "هل ترغب في إزالة هذا العنصر من سلة التسوق؟",
                    icon: "warning",
                    showCloseButton: true,
                    confirmButtonColor: "#dc3545",
                    confirmButtonText: "حذف",
                    customClass: {
                        popup: 'remove-cart-popup',
                    }
                }).then((result) => {
                    if (result.isConfirmed) {
                        fetch('/shop/wishlist/product/delete', {
                            method: 'POST',
                            headers: {
                                "Content-type": "application/json; charset=UTF-8",
                                "X-Requested-With": 'XMLHttpRequest',
                                "X-CSRF-TOKEN": $('meta[name="csrf-token"]').attr('content')
                            },
                            body: JSON.stringify({
                                product_hash_id: id
                            }),
                        })
                            .then(response => {
                                if (response.ok) {
                                    return response.json();
                                } else {
                                    toastr.error('حدث خطأ ما');
                                }
                            })
                            .then(data => {
                                toastr.success('تمت إزالة العنصر من قائمة الرغبات');
                                document.dispatchEvent(new CustomEvent('wishlist:updated', {
                                    detail: {
                                        items: data?.items ?? [],
                                        count: data?.count ?? 0,
                                    }
                                }));
                                $this.fetching = false
                            })
                            .catch(error => {
                                console.error('There has been a problem with your fetch operation:', error);
                            })
                            .finally(() => {
                                // any cleanup actions can be performed here
                            });

                    } else {
                        $this.fetching = false
                    }
                }).catch(() => {

                }).finally(() => {

                })
            },
            async addItem(id, slug = '') {
                document.dispatchEvent(new CustomEvent('cart:add', {
                    detail: {
                        id: id,
                    }
                }))

                if (false) {
                    window.location.href = slug;
                    return;
                }
            }
        }))
    })
</script>
