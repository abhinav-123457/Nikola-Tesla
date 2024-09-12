# Nikola-Tesla
A website showcasing the life and legacy of Nikola Tesla

## File 

index.html: The main HTML file for the website



CODE 
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Nikola Tesla</title>
    <meta content="yes" name="apple-touch-fullscreen" />
    <meta content="yes" name="apple-mobile-web-app-capable" />
    <meta content="black-translucent" name="apple-mobile-web-app-status-bar-style" />
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <meta name="robots" content="noindex">

    <meta property="og:title" content="Nikola Tesla">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://new.express.adobe.com/webpage/u2O0C695fPwsD/resources/1726154488437?asset_id=rendition">
    <meta property="og:url" content="https://new.express.adobe.com/webpage/u2O0C695fPwsD">
    <meta property="og:image:width" content="1024">
    <meta property="og:image:height" content="512">
    <meta property="og:site_name" content="Adobe Express">
    <meta property="og:description" content="A story told with Adobe Express">

    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Nikola Tesla">
    <meta name="twitter:image:src" content="https://new.express.adobe.com/webpage/u2O0C695fPwsD/resources/1726154488437?asset_id=rendition">
    <meta name="twitter:description" content="A story told with Adobe Express">

    <link rel="apple-touch-icon" href="https://new.express.adobe.com/webpage/u2O0C695fPwsD/resources/1726154488437?asset_id=rendition">
    <link rel="shortcut icon" href="/webpage/static/runtime/images/favicon.ico">

    <meta property="fb:app_id" content="919039361464473">
    <meta name="twitter:site" content="@AdobeSpark">

    <script src="/webpage/static/runtime/base-fonts.gz.js"></script>
    <script src="/webpage/static/runtime/themes/crisp-fonts.gz.js"></script>
    <script src="/webpage/static/runtime/typekit-load.gz.js"></script>
    <link href="/webpage/static/runtime/runtime.gz.css" type="text/css" rel="stylesheet">
    <style>
      /* custom-theme base */

      .crisp-theme .single-column-section .section-background,
      .crisp-theme .title-section {
        background-color: #484848;
      }

      .crisp-theme .title-header {
        height: 100%;
        text-align: center;
        box-sizing: border-box;
        font-size: 0;
      }

      .crisp-theme .title-top-left .title-header,
      .crisp-theme .title-left .title-header,
      .crisp-theme .title-bottom-left .title-header {
        text-align: left;
      }
      .crisp-theme .title-top .title-header,
      .crisp-theme .title-center .title-header,
      .crisp-theme .title-bottom .title-header {
        text-align: center;
      }
      .crisp-theme .title-top-right .title-header,
      .crisp-theme .title-right .title-header,
      .crisp-theme .title-bottom-right .title-header {
        text-align: right;
      }

      .crisp-theme .title-header:before {
        content: '';
        display: inline-block;
        width: 0;
        height: 100%;
        vertical-align: bottom;
      }

      .crisp-theme .title-top-left .title-header:before,
      .crisp-theme .title-top .title-header:before,
      .crisp-theme .title-top-right .title-header:before {
        vertical-align: top;
      }

      .crisp-theme .title-left .title-header:before,
      .crisp-theme .title-center .title-header:before,
      .crisp-theme .title-right .title-header:before {
        vertical-align: middle;
      }

      .crisp-theme .title-header-view {
        position: relative;
        display: inline-block;
        top: 0;
        right: 0;
        bottom: 0;
        left: 0;
      }

      .crisp-theme .title-header .gradient-overlay {
        background-color: rgba(0, 0, 0, 0);
        background-image: -webkit-linear-gradient( -270deg /*[gradient-angle-aligned-center]*/, rgba(0,0,0,0)  /*[gradient-stop-0-color-aligned-center]*/ 0% /*[gradient-stop-0-percent-aligned-center]*/, rgba(0,0,0,0.25)  /*[gradient-stop-1-color-aligned-center]*/ 25% /*[gradient-stop-1-percent-aligned-center]*/, rgba(0,0,0,0.50)  /*[gradient-stop-2-color-aligned-center]*/ 50% /*[gradient-stop-2-percent-aligned-center]*/, rgba(0,0,0,0.25)  /*[gradient-stop-3-color-aligned-center]*/ 75% /*[gradient-stop-3-percent-aligned-center]*/, rgba(0,0,0,0)  /*[gradient-stop-4-color-aligned-center]*/ 100% /*[gradient-stop-4-percent-aligned-center]*/);
        background-image: linear-gradient(0deg,rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.25) 25%, rgba(0, 0, 0, 0.50) 50%, rgba(0, 0, 0, 0.25) 75%, rgba(0, 0, 0, 0) 100%);
      }

      .crisp-theme .title-top-left .title-header .gradient-overlay,
      .crisp-theme .title-top .title-header .gradient-overlay,
      .crisp-theme .title-top-right .title-header .gradient-overlay {
        background-image: -webkit-linear-gradient( -270deg /*[gradient-angle-aligned-top]*/, rgba(0,0,0,0)  /*[gradient-stop-0-color-aligned-top]*/ 0% /*[gradient-stop-0-percent-aligned-top]*/, rgba(0,0,0,0.5)  /*[gradient-stop-1-color-aligned-top]*/ 100% /*[gradient-stop-1-percent-aligned-top]*/);
        background-image: linear-gradient(0deg,rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.5) 100%);
      }

      .crisp-theme .title-bottom-left .title-header .gradient-overlay,
      .crisp-theme .title-bottom .title-header .gradient-overlay,
      .crisp-theme .title-bottom-right .title-header .gradient-overlay {
        background-image: -webkit-linear-gradient( -270deg /*[gradient-angle-aligned-bottom]*/, rgba(0,0,0,0.5) /*[gradient-stop-0-color-aligned-bottom]*/ 0% /*[gradient-stop-0-percent-aligned-bottom]*/, rgba(0,0,0,0) /*[gradient-stop-1-color-aligned-bottom]*/ 100% /*[gradient-stop-1-percent-aligned-bottom]*/);
        background-image: linear-gradient(0deg,rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0) 100%);
      }

      .crisp-theme .card-flipbook-section .section-content .content-container {
        box-shadow: 0 0 4px rgba(0,0,0,.25);
      }

      .crisp-theme .card-flipbook-section .section-content .card-right .content-container {
        margin-left: auto;
      }

      .crisp-theme .card-flipbook-section .section-content .card-center .content-container {
        margin-left: auto;
        margin-right: auto;
      }

      /* crisp-theme components */

      .crisp-theme.article,
.crisp-theme .section {
  background-color: rgba(255,255,255,1);
}

.crisp-theme .section-content .content-container {
  padding-left: 20%;
  padding-right: 20%;
}

/*
 * Browsers vary in their default behavior of <b>/<strong> tags. Some default to
 * font-weight: bold (Chrome) and others default to font-weight: bolder (Firefox).
 * We explicitly match Chrome's behavior here so that font face fallback logic
 * is consistent between browsers (MRVL-15001)
 */
.crisp-theme strong,
.crisp-theme b {
  font-weight: bold;
}

/* title-section gradient-overlay treatment */

.crisp-theme .title-section {
  background-color: #484848;
}
.crisp-theme .title-header {
  padding: 64px 5% 64px 5%;
  background-color: transparent;
}
.crisp-theme .title-header-view {
  padding: 0px 0px 0px 0px;
  width: 100%;
  max-width: 89%;
  background-color: transparent;
  border-radius: 0px 0px 0px 0px;
}
.crisp-theme .title-header .gradient-overlay {
  right: -25%;
  left: -25%;
}
.crisp-theme .title-top-left .title-header .gradient-overlay,
.crisp-theme .title-top .title-header .gradient-overlay,
.crisp-theme .title-top-right .title-header .gradient-overlay {
  top: -64px;
  bottom: -50%;
  height: auto;
}
.crisp-theme .title-bottom-left .title-header .gradient-overlay,
.crisp-theme .title-bottom .title-header .gradient-overlay,
.crisp-theme .title-bottom-right .title-header .gradient-overlay {
  top: -50%;
  bottom: -64px;
  height: auto;
}
.crisp-theme .title-header .title {
  margin: 0 0;
  padding: 0 0;
  max-height: 3.1395em;
  color: rgba(255,255,255,1);
  font-family: proxima-nova,sans-serif;
  font-size: 94px;
  font-style: normal;
  font-weight: 100;
  text-transform: none;
  line-height: 1.0465;
  letter-spacing: normal;
  text-shadow: 0px 2px 2px rgba(0,0,0,0.25);
}
.crisp-theme .title-header .subtitle {
  margin-top: 1rem;
  padding: 0;
  max-height: 4.8149999999999995em;
  color: rgba(255,255,255,1);
  font-family: proxima-nova,sans-serif;
  font-size: 24px;
  font-style: normal;
  font-weight: 300;
  text-transform: uppercase;
  line-height: 1.605;
  letter-spacing: normal;
  text-shadow: 0px 2px 2px rgba(0,0,0,0.25);
}
@media ( max-width: 767px ) {
  .crisp-theme .title-header {
    padding: 32px 5% 32px 5%;
  }
}

/* Wide Screen Widths */

@media (min-width: 1300px) {
  /* each pair of title padding values should sum to 30% */
  .crisp-theme .title-top-left .title-header-view,
  .crisp-theme .title-left .title-header-view,
  .crisp-theme .title-bottom-left .title-header-view {
    padding-left: 10%;
    padding-right: 20%;
  }
  .crisp-theme .title-top .title-header-view,
  .crisp-theme .title-center .title-header-view,
  .crisp-theme .title-bottom .title-header-view{
    padding-left: 15%;
    padding-right: 15%;
  }
  .crisp-theme .title-top-right .title-header-view,
  .crisp-theme .title-right .title-header-view,
  .crisp-theme .title-bottom-right .title-header-view {
    padding-left: 20%;
    padding-right: 10%;
  }
}

/* Extra Wide Screen Widths */

@media (min-width: 1800px) {
  /* each pair of title padding values should sum to 50% */
  .crisp-theme .title-top-left .title-header-view,
  .crisp-theme .title-left .title-header-view,
  .crisp-theme .title-bottom-left .title-header-view {
    padding-left: 15%;
    padding-right: 35%;
  }
  .crisp-theme .title-top .title-header-view,
  .crisp-theme .title-center .title-header-view,
  .crisp-theme .title-bottom .title-header-view {
    padding-left: 25%;
    padding-right: 25%;
  }
  .crisp-theme .title-top-right .title-header-view,
  .crisp-theme .title-right .title-header-view,
  .crisp-theme .title-bottom-right .title-header-view {
    padding-left: 35%;
    padding-right: 15%;
  }
}

/* Super Wide Screen Widths */

@media (min-width: 2300px) {
  /* each pair of title padding values should sum to 60% */
  .crisp-theme .title-top-left .title-header-view,
  .crisp-theme .title-left .title-header-view,
  .crisp-theme .title-bottom-left .title-header-view {
    padding-left: 20%;
    padding-right: 40%;
  }
  .crisp-theme .title-top .title-header-view,
  .crisp-theme .title-center .title-header-view,
  .crisp-theme .title-bottom .title-header-view {
    padding-left: 30%;
    padding-right: 30%;
  }
  .crisp-theme .title-top-right .title-header-view,
  .crisp-theme .title-right .title-header-view,
  .crisp-theme .title-bottom-right .title-header-view {
    padding-left: 40%;
    padding-right: 20%;
  }
}


@media ( max-width: 767px ) {
  .crisp-theme .title-header .title {
    font-size: 50px;
  }
}
@media ( max-width: 767px ) {
  .crisp-theme .title-header .subtitle {
    font-size: 20px;
  }
}

/* heading no treatment */

.crisp-theme .content-container h3 {
  z-index: 0;
  font-family: proxima-nova,sans-serif;
  font-size: 60px;
  font-style: normal;
  font-weight: 300;
  text-transform: none;
  line-height: 1.1500000000000001;
  letter-spacing: normal;
  color: rgba(0,0,0,1);
  text-align: left;
}




@media ( max-width: 767px ) {
  .crisp-theme .content-container h3 {
    font-size: 36px;
  }
}

.crisp-theme .content-container h4 {
  font-family: proxima-nova,sans-serif;
  font-size: 29px;
  font-style: normal;
  font-weight: 400;
  text-transform: none;
  line-height: 1.4;
  letter-spacing: normal;
  color: rgba(0,0,0,1);
  text-align: left;
}

@media ( max-width: 767px ) {
  .crisp-theme .content-container h4 {
    font-size: 21px;
  }
}
.crisp-theme .single-column-section .content-container p,
.crisp-theme .card-flipbook-section .content-container p {
  font-family: proxima-nova,sans-serif;
  font-size: 20px;
  font-style: normal;
  font-weight: 300;
  text-transform: none;
  line-height: 1.6;
  letter-spacing: normal;
  color: rgba(17,26,11,1);
}

@media ( max-width: 767px ) {
  .crisp-theme .single-column-section .content-container p,
  .crisp-theme .card-flipbook-section .content-container p {
    font-size: 18px;
  }
}
.crisp-theme .content-container ul li {
  font-family: proxima-nova,sans-serif;
  font-size: 20px;
  font-style: normal;
  font-weight: 300;
  text-transform: none;
  line-height: 1.6;
  letter-spacing: normal;
  color: rgba(17,26,11,1);
  margin-left: 36px;
  margin-right: 0px;
}

@media ( max-width: 767px ) {
  .crisp-theme .content-container ul li {
    font-size: 18px;
  }
}
.crisp-theme .content-container ol li {
  font-family: proxima-nova,sans-serif;
  font-size: 20px;
  font-style: normal;
  font-weight: 300;
  text-transform: none;
  line-height: 1.6;
  letter-spacing: normal;
  color: rgba(17,26,11,1);
  margin-left: 36px;
  margin-right: 0px;
}

@media ( max-width: 767px ) {
  .crisp-theme .content-container ol li {
    font-size: 18px;
  }
}




/* blockquote left rule treatment */

.crisp-theme .content-container blockquote {
  z-index: 0;
  position: relative;
  font-family: proxima-nova-condensed,sans-serif;
  font-size: 36px;
  font-style: italic;
  font-weight: 300;
  text-transform: none;
  line-height: 1.2449999999999999;
  letter-spacing: normal;
  color: rgba(0,0,0,1);
  text-align: left;
  margin-top: 0px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  padding-top: .25em;
  padding-bottom: .25em;
  padding-left: 1em;
  padding-right: 1em;
}
.crisp-theme .content-container blockquote:before {
  content: "";
  display: inline-block;
  z-index: -1;
  position: absolute;
  top: 0px;
  right: auto;
  bottom: 0px;
  left: 0px;
  width: 5px;
  background-color: rgba(0,0,0,0.9);
}


@media ( max-width: 767px ) {
  .crisp-theme .content-container blockquote {
    font-size: 27px;
  }
}

.crisp-theme .image-wrapper {
  overflow: hidden;
}

/* inline image no treatment */

.crisp-theme .card-flipbook-section .caption, .crisp-theme .single-column-section .caption {
  font-family: proxima-nova,sans-serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  text-transform: none;
  line-height: 1.6;
  letter-spacing: normal;
  color: rgba(17,26,11,1);
  text-align: center;
  margin: .5em 0px;
}



@media ( max-width: 767px ) {
  .crisp-theme .card-flipbook-section .caption, .crisp-theme .single-column-section .caption {
    font-size: 16px;
  }
}


/* button rounded treatment */

.crisp-theme .content-container a.link-button {
  display: inline-block;
  border-radius: 0.2em;
  border: solid 1px rgba(0,0,0,1);
  padding-top: 7px;
  padding-left: 17px;
  padding-right: 17px;
  padding-bottom: 7px;
  font-family: proxima-nova,sans-serif;
  font-size: 19px;
  font-style: normal;
  font-weight: 400;
  text-transform: none;
  line-height: 1.35;
  letter-spacing: normal;
  text-decoration: none;
  text-align: center;
  color: rgba(0,0,0,1);

  -webkit-transition: color .15s linear, background-color .15s ease-in-out, border-color .15s ease-in-out;
  -moz-transition: color .15s linear, background-color .15s ease-in-out, border-color .15s ease-in-out;
  -o-transition: color .15s linear, background-color .15s ease-in-out, border-color .15s ease-in-out;
  -ms-transition: color .15s linear, background-color .15s ease-in-out, border-color .15s ease-in-out;
  transition: color .15s linear, background-color .15s ease-in-out, border-color .15s ease-in-out;
}
.crisp-theme .content-container a.link-button:hover {
  border-color: rgba(38,38,38,1);
  color: rgba(38,38,38,1);
}

@media ( max-width: 767px ) {
  .crisp-theme .content-container a.link-button {
    padding-top: 5px;
    padding-left: 17px;
    padding-right: 17px;
    padding-bottom: 5px;
  }
}




@media ( max-width: 767px ) {
  .crisp-theme .content-container a.link-button {
    font-size: 18px;
  }
}

.crisp-theme .single-column-section .content-container a:not(.link-button),
.crisp-theme .card-flipbook-section .content-container a:not(.link-button),
.crisp-theme .photo-grid-section    .content-container a:not(.link-button),
.crisp-theme .full-width-section    .content-container a:not(.link-button) {
  background-color: transparent;
  color: rgba(82,159,198,1);
  text-decoration: 
underline;
  -webkit-transition: color .15s linear;
  -moz-transition: color .15s linear;
  -o-transition: color .15s linear;
  -ms-transition: color .15s linear;
  transition: color .15s linear;
}
.crisp-theme .single-column-section .content-container a:not(.link-button):hover,
.crisp-theme .card-flipbook-section .content-container a:not(.link-button):hover,
.crisp-theme .photo-grid-section    .content-container a:not(.link-button):hover,
.crisp-theme .full-width-section    .content-container a:not(.link-button):hover {
  color: rgba(31,91,122,1);
}


/* full width image no treatment */

.crisp-theme .full-width-section .caption {
  font-family: proxima-nova,sans-serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  text-transform: none;
  line-height: 1.6;
  letter-spacing: normal;
  color: rgba(17,26,11,1);
  text-align: center;
  margin: .5em 0px;
}
.crisp-theme .full-width-section .caption {
  padding-right: 5%;
  padding-left: 5%;
}



@media ( max-width: 767px ) {
  .crisp-theme .full-width-section .caption {
    font-size: 16px;
  }
}
/* fillscreen section */


.crisp-theme .fullscreen-photo-section .pull-quote {
  position: absolute;
  top: 0px;
  right: auto;
  bottom: auto;
  left: 0px;
  margin: 96px 32px;
  padding: 0;
  max-width: 50%;
  font-family: proxima-nova,sans-serif;
  font-size: 25px;
  font-style: normal;
  font-weight: 300;
  text-transform: none;
  line-height: 1.5;
  letter-spacing: normal;
  text-shadow: 1px 1px 2px rgba(0,0,0,.35);
  color: rgba(0,0,0,1);
  background-color: transparent;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  -o-box-sizing: border-box;
  -ms-box-sizing: border-box;
  box-sizing: border-box;
}

.crisp-theme .fullscreen-photo-section .pull-quote .content-container {
  padding: 24px;
  color: rgba(0,0,0,1);
  background-color: rgba(255,255,255,0.8);
}

.crisp-theme .fullscreen-photo-section .pull-quote .content-container.empty {
  padding: 12px;
}

@media ( max-width: 767px ) {
  .crisp-theme .fullscreen-photo-section .pull-quote {
    font-size: 19px;
    margin: 48px 16px;
  }

  .crisp-theme .fullscreen-photo-section .pull-quote .content-container {
    padding: 12px;
  }

  .crisp-theme .fullscreen-photo-section .pull-quote .content-container.empty {
    padding: 6px;
  }
}


/* window section */

.crisp-theme .window-section .pull-quote {
  position: absolute;
  top: 0px;
  right: auto;
  bottom: auto;
  left: 0px;
  margin: 48px 32px;
  padding: 0;
  max-width: 50%;
  font-family: proxima-nova,sans-serif;
  font-size: 25px;
  font-style: normal;
  font-weight: 300;
  text-transform: none;
  line-height: 1.5;
  letter-spacing: normal;
  text-shadow: 1px 1px 2px rgba(0,0,0,.35);
  color: rgba(17,26,11,1);
  background-color: transparent;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  -o-box-sizing: border-box;
  -ms-box-sizing: border-box;
  box-sizing: border-box;
}

.crisp-theme .window-section .pull-quote .content-container {
  padding: 24px;
  color: rgba(17,26,11,1);
  background-color: rgba(255,255,255,0.8);
}

.crisp-theme .window-section .pull-quote .content-container.empty {
  padding: 12px;
}

@media ( max-width: 767px ) {
  .crisp-theme .window-section .pull-quote {
    font-size: 19px;
    margin: 24px 16px;
  }

  .crisp-theme .window-section .pull-quote .content-container {
    padding: 12px;
  }

  .crisp-theme .window-section .pull-quote .content-container.empty {
    padding: 6px;
  }
}



/* photo grid no treatment */

.crisp-theme .grid-caption {
  margin: .5em 0px;
  font-family: proxima-nova,sans-serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  text-transform: none;
  line-height: 1.6;
  letter-spacing: normal;
  text-align: center;
  color: rgba(17,26,11,1)
}



@media ( max-width: 767px ) {
  .crisp-theme .grid-caption {
    font-size: 16px;
  }
}

.crisp-theme .card-flipbook-section .section-content .content-container {
  background-color: rgba(255,255,255,0.9);
}
.crisp-theme .content-spacer {
  height: 0.125rem;
}
.crisp-theme .content-item-spacer {
  height: 5.000rem;
}
.crisp-theme .section .section-content .content-container {
  padding-top: 2.500rem;
  padding-bottom: 2.500rem;
}
.crisp-theme .full-width-section .section-content .content-container {
  padding-top: 0;
  padding-bottom: 0;
}
.crisp-theme .section.large-content-spacing-top .section-content .content-container {
  padding-top: 5.000rem;
}
.crisp-theme .section.large-content-spacing-bottom .section-content .content-container {
  padding-bottom: 5.000rem;
}
.crisp-theme .content-container > :first-child {
  margin-top: 0;
}
.crisp-theme .content-container > :last-child {
  margin-bottom: 0;
}
.crisp-theme ul,
.crisp-theme ol {
  padding: 0
}
.crisp-theme li {
  margin-bottom: 0.500rem;
}
.crisp-theme li:last-child {
  margin-bottom: 0;
}
.crisp-theme .content-container p {
  margin-top: 0;
  margin-bottom: 0;
}
.crisp-theme .content-container p + p{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol + p{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul + p{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 + p{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 + p{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote + p{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper + p{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image + p{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol {
  margin-top: 0;
  margin-bottom: 0;
}
.crisp-theme .content-container p + ol{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol + ol{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul + ol{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 + ol{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 + ol{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote + ol{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper + ol{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image + ol{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul {
  margin-top: 0;
  margin-bottom: 0;
}
.crisp-theme .content-container p + ul{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol + ul{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul + ul{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 + ul{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 + ul{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote + ul{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper + ul{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image + ul{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 {
  margin-top: 0;
  margin-bottom: 0;
}
.crisp-theme .content-container p + h3{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol + h3{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul + h3{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 + h3{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 + h3{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote + h3{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper + h3{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image + h3{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 {
  margin-top: 0;
  margin-bottom: 0;
}
.crisp-theme .content-container p + h4{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol + h4{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul + h4{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 + h4{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 + h4{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote + h4{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper + h4{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image + h4{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote {
  margin-top: 0;
  margin-bottom: 0;
}
.crisp-theme .content-container p + blockquote{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol + blockquote{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul + blockquote{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 + blockquote{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 + blockquote{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote + blockquote{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper + blockquote{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image + blockquote{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper {
  margin-top: 0;
  margin-bottom: 0;
}
.crisp-theme .content-container p + .link-button-wrapper{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol + .link-button-wrapper{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul + .link-button-wrapper{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 + .link-button-wrapper{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 + .link-button-wrapper{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote + .link-button-wrapper{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper + .link-button-wrapper{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image + .link-button-wrapper{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image {
  margin-top: 0;
  margin-bottom: 0;
}
.crisp-theme .content-container p + div.image{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ol + div.image{
  margin-top: 2.500rem;
}
.crisp-theme .content-container ul + div.image{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h3 + div.image{
  margin-top: 2.500rem;
}
.crisp-theme .content-container h4 + div.image{
  margin-top: 2.500rem;
}
.crisp-theme .content-container blockquote + div.image{
  margin-top: 2.500rem;
}
.crisp-theme .content-container .link-button-wrapper + div.image{
  margin-top: 2.500rem;
}
.crisp-theme .content-container div.image + div.image{
  margin-top: 2.500rem;
}
.crisp-theme .photo-grid-section + .single-column-section h3:first-child,
.crisp-theme .photo-grid-section + .single-column-section h4:first-child,
.crisp-theme .photo-grid-section + .single-column-section blockquote:first-child {
  margin-top: 2.500rem;
}
.crisp-theme .photo-grid-section + .single-column-section blockquote:last-child {
  margin-top: 2.500rem;
}
@media (max-width: 767px) {
  .crisp-theme .content-spacer {
    height: 0.125rem;
  }
  .crisp-theme .content-item-spacer {
    height: 2.500rem;
  }
  .crisp-theme .section .section-content .content-container {
    padding-top: 1.250rem;
    padding-bottom: 1.250rem;
  }
  .crisp-theme .full-width-section .section-content .content-container {
    padding-top: 0;
    padding-bottom: 0;
  }
  .crisp-theme .section.large-content-spacing-top .section-content .content-container {
    padding-top: 2.500rem;
  }
  .crisp-theme .section.large-content-spacing-bottom .section-content .content-container {
    padding-bottom: 2.500rem;
  }
  .crisp-theme .content-container > :first-child {
    margin-top: 0;
  }
  .crisp-theme .content-container > :last-child {
    margin-bottom: 0;
  }
  .crisp-theme ul,
  .crisp-theme ol {
    padding: 0
  }
  .crisp-theme li {
    margin-bottom: 0.250rem;
  }
  .crisp-theme li:last-child {
    margin-bottom: 0;
  }
  .crisp-theme .content-container p {
    margin-top: 0;
    margin-bottom: 0;
  }
  .crisp-theme .content-container p + p{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol + p{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul + p{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 + p{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 + p{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote + p{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper + p{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image + p{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol {
    margin-top: 0;
    margin-bottom: 0;
  }
  .crisp-theme .content-container p + ol{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol + ol{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul + ol{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 + ol{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 + ol{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote + ol{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper + ol{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image + ol{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul {
    margin-top: 0;
    margin-bottom: 0;
  }
  .crisp-theme .content-container p + ul{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol + ul{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul + ul{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 + ul{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 + ul{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote + ul{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper + ul{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image + ul{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 {
    margin-top: 0;
    margin-bottom: 0;
  }
  .crisp-theme .content-container p + h3{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol + h3{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul + h3{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 + h3{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 + h3{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote + h3{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper + h3{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image + h3{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 {
    margin-top: 0;
    margin-bottom: 0;
  }
  .crisp-theme .content-container p + h4{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol + h4{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul + h4{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 + h4{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 + h4{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote + h4{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper + h4{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image + h4{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote {
    margin-top: 0;
    margin-bottom: 0;
  }
  .crisp-theme .content-container p + blockquote{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol + blockquote{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul + blockquote{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 + blockquote{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 + blockquote{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote + blockquote{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper + blockquote{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image + blockquote{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper {
    margin-top: 0;
    margin-bottom: 0;
  }
  .crisp-theme .content-container p + .link-button-wrapper{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol + .link-button-wrapper{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul + .link-button-wrapper{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 + .link-button-wrapper{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 + .link-button-wrapper{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote + .link-button-wrapper{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper + .link-button-wrapper{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image + .link-button-wrapper{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image {
    margin-top: 0;
    margin-bottom: 0;
  }
  .crisp-theme .content-container p + div.image{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ol + div.image{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container ul + div.image{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h3 + div.image{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container h4 + div.image{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container blockquote + div.image{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container .link-button-wrapper + div.image{
    margin-top: 1.250rem;
  }
  .crisp-theme .content-container div.image + div.image{
    margin-top: 1.250rem;
  }
  .crisp-theme .photo-grid-section + .single-column-section h3:first-child,
  .crisp-theme .photo-grid-section + .single-column-section h4:first-child,
  .crisp-theme .photo-grid-section + .single-column-section blockquote:first-child {
    margin-top: 1.250rem;
  }
  .crisp-theme .photo-grid-section + .single-column-section blockquote:last-child {
    margin-top: 1.250rem;
  }
}



/* Default Screen Widths */

.crisp-theme .section-content .content-container {
  padding-left: 20%;
  padding-right: 20%;
}

.crisp-theme .card-flipbook-section .section-content .content-container {
  width: 50%;
  margin: 32px 32px;
  padding: 56px 32px;
}

.crisp-theme .card-flipbook-section .section-content .card-center .content-container {
  width: 65%;
  max-width: 900px;
}

/* Narrow Screen Widths */

@media (max-width: 768px) {
  .crisp-theme .section-content .content-container {
    padding-left: 12.5%;
    padding-right: 12.5%;
  }
  .crisp-theme .card-flipbook-section .section-content .content-container {
    width: 60%;
    margin: 32px 32px;
    padding: 56px 32px;
  }
  .crisp-theme .card-flipbook-section .section-content .card-center .content-container {
    width: 75%;
    max-width: 900px;
  }
}

/* Extra Narrow Screen Widths */

@media (max-width: 480px) {
  .crisp-theme .section-content .content-container {
    padding-left: 7%;
    padding-right: 7%;
  }
  .crisp-theme .card-flipbook-section .section-content .content-container {
    width: 70%;
    margin: 18px 14px;
    padding: 31px 13px;
  }
  .crisp-theme .card-flipbook-section .section-content .card-center .content-container {
    width: 75%;
    max-width: 900px;
  }
}

/* Super Narrow Screen Widths */

@media (max-width: 320px) {
  .crisp-theme .section-content .content-container {
    padding-left: 7%;
    padding-right: 7%;
  }
  .crisp-theme .card-flipbook-section .section-content .content-container {
    width: 70%;
    margin: 18px 14px;
    padding: 31px 12px;
  }
  .crisp-theme .card-flipbook-section .section-content .card-center .content-container {
    width: 75%;
    max-width: 900px;
  }
}

/* Wide Screen Widths */

@media (min-width: 1300px) {
  .crisp-theme  .section-content .content-container {
    padding-left: 25%;
    padding-right: 25%;
  }

  .crisp-theme  .card-flipbook-section .section-content .content-container {
    width: 40%;
    margin: 32px 32px;
    padding: 56px 32px;
    max-width: 580px;
  }
  .crisp-theme  .card-flipbook-section .section-content .card-center .content-container {
    width: 65%;
    max-width: 900px;
  }
}

/* Extra Wide Screen Widths */

@media (min-width: 1800px) {
  .crisp-theme .section-content .content-container {
    padding-left: 30%;
    padding-right: 30%;
  }

  .crisp-theme .card-flipbook-section .section-content .content-container {
    width: 30%;
    margin: 32px 80px;
    padding: 56px 32px;
    max-width: 580px;
  }
  .crisp-theme .card-flipbook-section .section-content .card-center .content-container {
    width: 65%;
    max-width: 900px;
  }
}

/* Super Wide Screen Widths */

@media (min-width: 2300px) {
  .crisp-theme .section-content .content-container {
    padding-left: 33%;
    padding-right: 33%;
  }

  .crisp-theme  .card-flipbook-section .section-content .content-container {
    width: 25%;
    margin: 32px 80px;
    padding: 56px 32px;
    max-width: 580px;
  }
  .crisp-theme  .card-flipbook-section .section-content .card-center .content-container {
    width: 65%;
    max-width: 900px;
  }
}

.crisp-theme .section.author-section .author-appreciation-container {
  border-color: rgba(17,26,11,0.5);
}
.crisp-theme .section.author-section .author {
  font-family: proxima-nova;
  color: rgba(17,26,11,1);
}

.crisp-theme .section.author-section .appreciate-button {
  color: rgba(17,26,11,0.5);
  border-color: rgba(17,26,11,0.5);
}

.crisp-theme .section.author-section .appreciate-button:before {
  background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgdmlld0JveD0iMCAwIDMyIDMyIj48cGF0aCBzdHlsZT0iZmlsbDpyZ2JhKDE3LDI2LDExLDAuNSk7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDMpIiBkPSJNMTYsMjZMMi44LDE0LjRDMS4xLDEyLjksMCwxMC43LDAsOC40YzAtMi4zLDEtNC41LDIuOC02QzQuNiwwLjksNi45LDAsOS4yLDBjMi40LDAsNC42LDAuOCw2LjQsMi40YzAuMSwwLjEsMC4zLDAuMywwLjQsMC40YzAuMS0wLjEsMC4zLTAuMywwLjQtMC40QzE4LjIsMC45LDIwLjUsMCwyMi44LDBjMi4zLDAsNC42LDAuOCw2LjQsMi40QzMxLDMuOSwzMiw2LjEsMzIsOC40YzAsMi4zLTEsNC41LTIuOCw2TDE2LDI2eiBNOS4yLDQuN0M4LDQuNyw2LjksNS4yLDYsNS45QzUuMyw2LjUsNC44LDcuNCw0LjgsOC40YzAsMSwwLjUsMS45LDEuMiwyLjVsMTAsOC44bDEwLTguOGMwLjctMC42LDEuMi0xLjUsMS4yLTIuNWMwLTEtMC41LTEuOS0xLjItMi41Yy0xLjktMS41LTQuNS0xLjUtNi40LDBjLTAuNywwLjYtMS4yLDEuNS0xLjIsMi41aC00LjhjMC0xLTAuNS0xLjktMS4yLTIuNUMxMS41LDUuMSwxMC40LDQuNyw5LjIsNC43eiIvPjwvc3ZnPg==');
}

.crisp-theme .section.author-section .appreciate-button:after {
  background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgdmlld0JveD0iMCAwIDMyIDMyIj48cGF0aCBzdHlsZT0iZmlsbDpyZ2JhKDE3LDI2LDExLDEpOyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAzKSIgZD0iTTIuOCwxNC40QzEuMSwxMi45LDAsMTAuNywwLDguNGMwLTIuMywxLTQuNSwyLjgtNkM0LjYsMC45LDYuOSwwLDkuMiwwYzIuNCwwLDQuNiwwLjgsNi40LDIuNGMwLjEsMC4xLDAuMywwLjMsMC40LDAuNGMwLjEtMC4xLDAuMy0wLjMsMC40LTAuNEMxOC4yLDAuOSwyMC41LDAsMjIuOCwwYzIuMywwLDQuNiwwLjgsNi40LDIuNEMzMSwzLjksMzIsNi4xLDMyLDguNGMwLDIuMy0xLDQuNS0yLjgsNkwxNiwyNiIvPjwvc3ZnPg==');
}

.crisp-theme .section.author-section .appreciate-button.appreciated:before {
  background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgdmlld0JveD0iMCAwIDMyIDMyIj48cGF0aCBzdHlsZT0iZmlsbDpyZ2JhKDE3LDI2LDExLDAuNSk7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDMpIiBkPSJNMi44LDE0LjRDMS4xLDEyLjksMCwxMC43LDAsOC40YzAtMi4zLDEtNC41LDIuOC02QzQuNiwwLjksNi45LDAsOS4yLDBjMi40LDAsNC42LDAuOCw2LjQsMi40YzAuMSwwLjEsMC4zLDAuMywwLjQsMC40YzAuMS0wLjEsMC4zLTAuMywwLjQtMC40QzE4LjIsMC45LDIwLjUsMCwyMi44LDBjMi4zLDAsNC42LDAuOCw2LjQsMi40QzMxLDMuOSwzMiw2LjEsMzIsOC40YzAsMi4zLTEsNC41LTIuOCw2TDE2LDI2Ii8+PC9zdmc+');
}

.crisp-theme .section.author-section .appreciate-button.appreciated:after {
  background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgdmlld0JveD0iMCAwIDMyIDMyIj48cGF0aCBzdHlsZT0iZmlsbDpyZ2JhKDE3LDI2LDExLDEpOyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAzKSIgZD0iTTE2LDI2TDIuOCwxNC40QzEuMSwxMi45LDAsMTAuNywwLDguNGMwLTIuMywxLTQuNSwyLjgtNkM0LjYsMC45LDYuOSwwLDkuMiwwYzIuNCwwLDQuNiwwLjgsNi40LDIuNGMwLjEsMC4xLDAuMywwLjMsMC40LDAuNGMwLjEtMC4xLDAuMy0wLjMsMC40LTAuNEMxOC4yLDAuOSwyMC41LDAsMjIuOCwwYzIuMywwLDQuNiwwLjgsNi40LDIuNEMzMSwzLjksMzIsNi4xLDMyLDguNGMwLDIuMy0xLDQuNS0yLjgsNkwxNiwyNnogTTkuMiw0LjdDOCw0LjcsNi45LDUuMiw2LDUuOUM1LjMsNi41LDQuOCw3LjQsNC44LDguNGMwLDEsMC41LDEuOSwxLjIsMi41bDEwLDguOGwxMC04LjhjMC43LTAuNiwxLjItMS41LDEuMi0yLjVjMC0xLTAuNS0xLjktMS4yLTIuNWMtMS45LTEuNS00LjUtMS41LTYuNCwwYy0wLjcsMC42LTEuMiwxLjUtMS4yLDIuNWgtNC44YzAtMS0wLjUtMS45LTEuMi0yLjVDMTEuNSw1LjEsMTAuNCw0LjcsOS4yLDQuN3oiLz48L3N2Zz4=');
}

.publication-viewer.touch-disabled .crisp-theme .section.author-section .appreciate-button:hover {
  color: rgba(17,26,11,1);
  border-color: rgba(17,26,11,1);
}

.publication-viewer.touch-disabled .crisp-theme .section.author-section .appreciate-button:active {
  color: rgba(17,26,11,0.5);
  border-color: rgba(17,26,11,0.5);
}

.publication-viewer.touch-disabled .crisp-theme .section.author-section .appreciate-button:active:after {
  background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgdmlld0JveD0iMCAwIDMyIDMyIj48cGF0aCBzdHlsZT0iZmlsbDpyZ2JhKDE3LDI2LDExLDAuNSk7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDMpIiBkPSJNMi44LDE0LjRDMS4xLDEyLjksMCwxMC43LDAsOC40YzAtMi4zLDEtNC41LDIuOC02QzQuNiwwLjksNi45LDAsOS4yLDBjMi40LDAsNC42LDAuOCw2LjQsMi40YzAuMSwwLjEsMC4zLDAuMywwLjQsMC40YzAuMS0wLjEsMC4zLTAuMywwLjQtMC40QzE4LjIsMC45LDIwLjUsMCwyMi44LDBjMi4zLDAsNC42LDAuOCw2LjQsMi40QzMxLDMuOSwzMiw2LjEsMzIsOC40YzAsMi4zLTEsNC41LTIuOCw2TDE2LDI2Ii8+PC9zdmc+');
}

.publication-viewer.touch-disabled .crisp-theme .section.author-section .appreciate-button.appreciated:active:after {
  background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgdmlld0JveD0iMCAwIDMyIDMyIj48cGF0aCBzdHlsZT0iZmlsbDpyZ2JhKDE3LDI2LDExLDAuNSk7IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDMpIiBkPSJNMTYsMjZMMi44LDE0LjRDMS4xLDEyLjksMCwxMC43LDAsOC40YzAtMi4zLDEtNC41LDIuOC02QzQuNiwwLjksNi45LDAsOS4yLDBjMi40LDAsNC42LDAuOCw2LjQsMi40YzAuMSwwLjEsMC4zLDAuMywwLjQsMC40YzAuMS0wLjEsMC4zLTAuMywwLjQtMC40QzE4LjIsMC45LDIwLjUsMCwyMi44LDBjMi4zLDAsNC42LDAuOCw2LjQsMi40QzMxLDMuOSwzMiw2LjEsMzIsOC40YzAsMi4zLTEsNC41LTIuOCw2TDE2LDI2eiBNOS4yLDQuN0M4LDQuNyw2LjksNS4yLDYsNS45QzUuMyw2LjUsNC44LDcuNCw0LjgsOC40YzAsMSwwLjUsMS45LDEuMiwyLjVsMTAsOC44bDEwLTguOGMwLjctMC42LDEuMi0xLjUsMS4yLTIuNWMwLTEtMC41LTEuOS0xLjItMi41Yy0xLjktMS41LTQuNS0xLjUtNi40LDBjLTAuNywwLjYtMS4yLDEuNS0xLjIsMi41aC00LjhjMC0xLTAuNS0xLjktMS4yLTIuNUMxMS41LDUuMSwxMC40LDQuNyw5LjIsNC43eiIvPjwvc3ZnPg==');
}


.crisp-theme .section.credits-section {
  color: rgba(17,26,11,1);
}

      /* behaviors css */
      /* Default content behaviors */

.crisp-theme div.image {
  -webkit-transition: opacity .5s cubic-bezier(0.455, 0.030, 0.515, 0.955), -webkit-transform .5s cubic-bezier(0.455, 0.030, 0.515, 0.955);
  -moz-transition: opacity .5s cubic-bezier(0.455, 0.030, 0.515, 0.955), -moz-transform .5s cubic-bezier(0.455, 0.030, 0.515, 0.955);
  -o-transition: opacity .5s cubic-bezier(0.455, 0.030, 0.515, 0.955), -o-transform .5s cubic-bezier(0.455, 0.030, 0.515, 0.955);
  -ms-transition: opacity .5s cubic-bezier(0.455, 0.030, 0.515, 0.955), -ms-transform .5s cubic-bezier(0.455, 0.030, 0.515, 0.955);
  transition: opacity .5s cubic-bezier(0.455, 0.030, 0.515, 0.955), transform .5s cubic-bezier(0.455, 0.030, 0.515, 0.955);

  opacity: 1;

  -webkit-transform: translate3d(0,0,0);
  -moz-transform: translate3d(0,0,0);
  -o-transform: translate3d(0,0,0);
  -ms-transform: translate3d(0,0,0);
  transform: translate3d(0,0,0);
}

.crisp-theme div.image.hidden {
  opacity: 0;

  -webkit-transform: translate3d(0,40px,0);
  -moz-transform: translate3d(0,40px,0);
  -o-transform: translate3d(0,40px,0);
  -ms-transform: translate3d(0,40px,0);
  transform: translate3d(0,40px,0);
}

.crisp-theme .caption,
.crisp-theme .grid-caption {
  -webkit-transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), -webkit-transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);
  -moz-transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), -moz-transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);
  -o-transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), -o-transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);
  -ms-transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), -ms-transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);
  transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);

  opacity: 1;

  -webkit-transform: translate3d(0,0,0);
  -moz-transform: translate3d(0,0,0);
  -o-transform: translate3d(0,0,0);
  -ms-transform: translate3d(0,0,0);
  transform: translate3d(0,0,0);
}

.crisp-theme .caption.hidden,
.crisp-theme .grid-caption.hidden {
  opacity: 0;

  -webkit-transform: translate3d(20px,0,0);
  -moz-transform: translate3d(20px,0,0);
  -o-transform: translate3d(20px,0,0);
  -ms-transform: translate3d(20px,0,0);
  transform: translate3d(20px,0,0);
}

.crisp-theme blockquote {
  -webkit-transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), -webkit-transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);
  -moz-transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), -moz-transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);
  -o-transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), -o-transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);
  -ms-transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), -ms-transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);
  transition: opacity .5s cubic-bezier(0.250, 0.460, 0.450, 0.940), transform .5s cubic-bezier(0.250, 0.460, 0.450, 0.940);

  opacity: 1;

  -webkit-transform: translate3d(0,0,0);
  -moz-transform: translate3d(0,0,0);
  -o-transform: translate3d(0,0,0);
  -ms-transform: translate3d(0,0,0);
  transform: translate3d(0,0,0);
}

.crisp-theme blockquote.hidden {
  opacity: 0;

  -webkit-transform: translate3d(20px,0,0);
  -moz-transform: translate3d(20px,0,0);
  -o-transform: translate3d(20px,0,0);
  -ms-transform: translate3d(20px,0,0);
  transform: translate3d(20px,0,0);
}


      /* overrides to some alignments defined after component
         styles to make sure they will override the component
         defaults when they have the same specificity */

      .crisp-theme .link-button-wrapper, /* default */
      .crisp-theme .link-button-wrapper.link-left {
        text-align: left;
      }

      .crisp-theme .link-button-wrapper.link-center {
        text-align: center;
      }

      .crisp-theme .link-button-wrapper.link-right {
        text-align: right;
      }

      .crisp-theme p.text-left,
      .crisp-theme h3.text-left,
      .crisp-theme h4.text-left,
      .crisp-theme .caption.text-left,
      .crisp-theme .grid-caption.text-left {
        text-align: left;
      }

      .crisp-theme .caption, /* defaults */
      .crisp-theme .grid-caption,

      .crisp-theme p.text-center,
      .crisp-theme h3.text-center,
      .crisp-theme h4.text-center,
      .crisp-theme .caption.text-center,
      .crisp-theme .grid-caption.text-center {
        text-align: center;
      }

      .crisp-theme p.text-right,
      .crisp-theme h3.text-right,
      .crisp-theme h4.text-right,
      .crisp-theme .caption.text-right,
      .crisp-theme .grid-caption.text-right {
        text-align: right;
      }

      .crisp-theme .caption-right .pull-quote {
        right: 3%;
        left: auto;
        margin-left: 0;
        margin-right: 2rem;
      }
    </style>
    <noscript id="noscript-static-layout" data-href="/webpage/static/runtime/noscript.gz.css">
      <link href="/webpage/static/runtime/noscript.gz.css" type="text/css" rel="stylesheet">
    </noscript>
    <!--BEGIN-BUMPER-STYLE-SHEET-->
    <!--END-BUMPER-STYLE-SHEET-->
</head>
<body class="">
  <div id="app">
    <div id="publication-viewer" class="publication-viewer">
      <div id="luca-splash" class="splash">
        <div class="background" style="background-image: url(/webpage/u2O0C695fPwsD/resources/2fdf9203-545a-424d-9eb6-4a1a70308997-whatsapp_ima?asset_id=f6b53da1-6fa7-4494-a9c9-d782475dc054&img_etag=%22b817d4b0a0ed4a82adf2b274e21e8ffc%22&image_assets=false&size=1024); background-position: 50% 50%;"></div>
        <div class="content">
          <div class="logo"></div>
          <div class="loading-label"></div>
          <div class="wp-progress-bar">
            <div class="wp-progress-bar-clip">
              <div class="wp-progress-bar-view"></div>
            </div>
          </div>
        </div>
      </div>
            <div class="publication-view">
        <div class="wp-swipe-panel-group">
          <div class="wp-swipe-panel-group-view">
              <div class="wp-swipe-panel-group-panel article-panel">
                <div class="article crisp-theme sections-article-layout" data-article-type="sections-article">
        <div class="section title-section title-center"  data-section-behavior="crisp-title"  data-layer="1" data-layer-name="over" data-scroll-after-animation="false">
        <div class="section-view">
          <div class="section-background ">
            <div class="section-background-image"  style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/2fdf9203-545a-424d-9eb6-4a1a70308997-whatsapp_ima?asset_id=f6b53da1-6fa7-4494-a9c9-d782475dc054&img_etag=%22b817d4b0a0ed4a82adf2b274e21e8ffc%22&image_assets=false&size=1024" data-image-width="1344" data-image-height="896"></a></div>
          </div>

            <div class="title-header">
              <h1 class="title-header-view">
                <span class="gradient-overlay"></span>
                <span class="title">NIKOLA TESLA</span>
                <span class="subtitle">A brief overview of tesla&#39;s life and contributions to Science</span>
              </h1>
            </div>
      
          <div class="navigation-hint down"></div>
        </div>
      </div>
      <div class="section spacer-section content-spacer bottom-shadow" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section card-flipbook-section" data-section-behavior="crisp-column-overlay" data-spacing=".75" data-layer="-1" data-layer-name="under">
        <div class="section-view">
          <div class="section-background">
            <div class="section-background-image" style=" background-position: 50% 50%;" data-pan-and-zoom="zoom-in"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/b12428c4-8777-4228-bfa0-6693d9836401-whatsapp_ima?asset_id=1e8b0e19-4aa5-4cad-aa77-02f709f24ae7&img_etag=%22b367df9a90114fcebe547c410ca3c482%22&image_assets=false&size=1024" data-image-width="728" data-image-height="410"></a></div>
          </div>
          <div class="section-content">
            <div class="section-content-view card-center">
              <div class="content-container">
                            <h3 class=" text-center" >TESLA&#39;S BIRTH (1856)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/0d64633c-affe-41a4-8680-c557ec4bf29f-whatsapp_ima?asset_id=3f55605c-b5db-4372-b489-a3043231d27e&amp;img_etag=%22119271d4654d4722a24f44570301f19f%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                         aria-label="Large preview" 
                      >
                        <span data-id="0d64633c-affe-41a4-8680-c557ec4bf29f" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/0d64633c-affe-41a4-8680-c557ec4bf29f-whatsapp_ima?asset_id=3f55605c-b5db-4372-b489-a3043231d27e&amp;img_etag=%22119271d4654d4722a24f44570301f19f%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024" data-decorative="true"></span>
                      </a>
                    </div>
                  </div>
                                  <p class=" " >Tesla was born into a Serbian Orthodox family in Smiljan, Croatia (then part of the Austrian Empire) on July 10 , 1856 . His father was a priest, and his mother was an inventor in her own right, crafting small household devices. This section could focus on Tesla&#39;s cultural and familial roots and the environment that nurtured his genius.</p>
                                  <h3 class=" text-center" >TESLA&#39;S CHILDHOOD</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/c628be61-bc60-4aa7-8eb1-56b14eda7112-whatsapp_ima?asset_id=9ed07623-4a20-4f4e-9d53-dd81bdab1cfb&amp;img_etag=%22ce4ed7a415a9412a8369ac7495c5b6fe%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="c628be61-bc60-4aa7-8eb1-56b14eda7112" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/c628be61-bc60-4aa7-8eb1-56b14eda7112-whatsapp_ima?asset_id=9ed07623-4a20-4f4e-9d53-dd81bdab1cfb&amp;img_etag=%22ce4ed7a415a9412a8369ac7495c5b6fe%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                  </div>
                                  <p class=" " ><i><b>Tesla&#39;s early fascination with electricity started during childhood, and he showed signs of extraordinary intelligence. Struggled with illness, including a serious case of cholera, which led him to develop a powerful will to recover.</b></i></p>
                                  <h3 class=" text-center" >TESLA&#39;S COLLEGE (1875-82)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/a5348a77-0d61-4e88-8b11-148bf8c43438-whatsapp_ima?asset_id=a01acce2-20a9-4d25-81cb-c16bd29b6c61&amp;img_etag=%2251b181a67cef4e4fb3c3387fae83dbee%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="a5348a77-0d61-4e88-8b11-148bf8c43438" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/a5348a77-0d61-4e88-8b11-148bf8c43438-whatsapp_ima?asset_id=a01acce2-20a9-4d25-81cb-c16bd29b6c61&amp;img_etag=%2251b181a67cef4e4fb3c3387fae83dbee%22&amp;image_assets=false&amp;size=1024" style="width: 1344px; padding-top: 66.66666666666666%" data-image-width="1344" data-image-height="896"></span>
                      </a>
                    </div>
                  </div>
                                  <h3 class=" text-center" >Tesla Meets the Wizard of Menlo Park (1882-85)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/e7b4bc5c-356f-4198-ba0f-0932231885b8-images_jpeg?asset_id=732d9117-bbf0-4296-b29e-f8387b741a62&amp;img_etag=%224de0ea7bfa364a108de97c547aed2822%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="e7b4bc5c-356f-4198-ba0f-0932231885b8" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/e7b4bc5c-356f-4198-ba0f-0932231885b8-images_jpeg?asset_id=732d9117-bbf0-4296-b29e-f8387b741a62&amp;img_etag=%224de0ea7bfa364a108de97c547aed2822%22&amp;image_assets=false&amp;size=1024" style="width: 275px; padding-top: 66.54545454545455%" data-image-width="275" data-image-height="183"></span>
                      </a>
                    </div>
                  </div>
                                  <p class=" text-left" ><i><b>Tesla moved to Paris in 1882 to work for the Continental Edison Company, improving dynamos.In 1884, he emigrated to the U.S. to work with Thomas Edison in New York, marking the beginning of a legendary rivalry.</b></i></p>
                              <div class="image" role="figure" aria-labelledby="caption-fb3fadab-ac0b-4056-bc67-bc4834cfcb6f">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/fb3fadab-ac0b-4056-bc67-bc4834cfcb6f-acdc_jpg?asset_id=044a4dea-4111-4db4-a39c-002763e0c64d&amp;img_etag=%229daccd8270b044fc9fb3bfedeec04e4e%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="fb3fadab-ac0b-4056-bc67-bc4834cfcb6f" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/fb3fadab-ac0b-4056-bc67-bc4834cfcb6f-acdc_jpg?asset_id=044a4dea-4111-4db4-a39c-002763e0c64d&amp;img_etag=%229daccd8270b044fc9fb3bfedeec04e4e%22&amp;image_assets=false&amp;size=1024" style="width: 320px; padding-top: 71.5625%" data-image-width="320" data-image-height="229"></span>
                      </a>
                    </div>
                    <div id="caption-fb3fadab-ac0b-4056-bc67-bc4834cfcb6f" class="caption ">Thinking of the Edison and Tesla regarding AC and DC currents</div>
                  </div>
                                  <h3 class=" text-center" >Liberty Street (1886-88)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/aafadaa0-5d9e-49ed-8d5f-f57825ed0ef5-tesla_left_e?asset_id=d9595b56-1200-489c-aafc-df924792bfad&amp;img_etag=%224fcb7554e5f1463c9a3d1707231e358d%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="aafadaa0-5d9e-49ed-8d5f-f57825ed0ef5" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/aafadaa0-5d9e-49ed-8d5f-f57825ed0ef5-tesla_left_e?asset_id=d9595b56-1200-489c-aafc-df924792bfad&amp;img_etag=%224fcb7554e5f1463c9a3d1707231e358d%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                  </div>
                                  <h3 class=" text-center" >Induction at Pittsburgh (1889)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/26f3d3fd-1c61-48ef-b930-d5b1ccc750b1-8c8121bc2dea?asset_id=a00a002e-00d5-4e9d-8165-2d037e5f5900&amp;img_etag=%220747ffc7aebf468a9401466928e05b09%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="26f3d3fd-1c61-48ef-b930-d5b1ccc750b1" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/26f3d3fd-1c61-48ef-b930-d5b1ccc750b1-8c8121bc2dea?asset_id=a00a002e-00d5-4e9d-8165-2d037e5f5900&amp;img_etag=%220747ffc7aebf468a9401466928e05b09%22&amp;image_assets=false&amp;size=1024" style="width: 650px; padding-top: 71.38461538461539%" data-image-width="650" data-image-height="464"></span>
                      </a>
                    </div>
                  </div>
                                  <p class=" " ><b><i>Tesla began working with George Westinghouse in Pittsburgh to commercialize his alternating current system, including the invention of the induction motor.</i></b></p>
                                <div class="embedded-gif image ">
                            <div class="embedded-gif-wrapper image-wrapper">
                              <img src="https://media.giphy.com/media/VVZsU6RG7MmxaJi6dL/giphy.gif" alt="" data-href="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExN2NkaTV5d3Z0a3g4ZjFjMHkzM2p5dnY3NXhyYjFvZDZoM2ExMWw2dSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/VVZsU6RG7MmxaJi6dL/giphy.gif" />
                            </div>
                    </div>
                                  <h3 class=" text-center" >South Fifth Avenue (1890-91)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/6a8465af-a716-426e-9119-bfb8638f9893-tesla_left_e?asset_id=0ed8873a-db84-4b24-80e1-d00394fd5492&amp;img_etag=%22cd2a059baaba492784b498a5e36b04cc%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="6a8465af-a716-426e-9119-bfb8638f9893" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/6a8465af-a716-426e-9119-bfb8638f9893-tesla_left_e?asset_id=0ed8873a-db84-4b24-80e1-d00394fd5492&amp;img_etag=%22cd2a059baaba492784b498a5e36b04cc%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                  </div>
                                  <h3 class=" text-center" >Revising the Past (1891)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/82945849-435d-4da5-9da6-6e852769d52f-tesla_wirele?asset_id=358a86e4-9ea9-4950-a942-255a7440257a&amp;img_etag=%22e5a73d8ef061483183cd1a8b5cf77eeb%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="82945849-435d-4da5-9da6-6e852769d52f" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/82945849-435d-4da5-9da6-6e852769d52f-tesla_wirele?asset_id=358a86e4-9ea9-4950-a942-255a7440257a&amp;img_etag=%22e5a73d8ef061483183cd1a8b5cf77eeb%22&amp;image_assets=false&amp;size=1024" style="width: 400px; padding-top: 66.5%" data-image-width="400" data-image-height="266"></span>
                      </a>
                    </div>
                  </div>
                                  <p class=" " ><i><b>Tesla continued refining his work on AC, eventually giving a famous lecture to the American Institute of Electrical Engineers, solidifying his reputation.</b></i></p>
                                  <h3 class=" text-center" >Father of the Wireless (1893)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/a5c0c75e-2d72-4f2e-9b20-e801cf04129e-tesla_left_e?asset_id=37bab54e-b4c4-4c2c-a56a-ca05cc239887&amp;img_etag=%221f470b2367894de19991fba0768069a0%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="a5c0c75e-2d72-4f2e-9b20-e801cf04129e" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/a5c0c75e-2d72-4f2e-9b20-e801cf04129e-tesla_left_e?asset_id=37bab54e-b4c4-4c2c-a56a-ca05cc239887&amp;img_etag=%221f470b2367894de19991fba0768069a0%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                  </div>
                                  <h3 class=" text-center" >Niagara Power (1894)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/1d6e5a7d-14dd-4282-9679-92271c8e923d-tesla_s_ac_s?asset_id=d9331d5c-66a1-4ae4-ba01-2456f44ea04b&amp;img_etag=%2242179329af49407b9fb4dc05c44dd687%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="1d6e5a7d-14dd-4282-9679-92271c8e923d" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/1d6e5a7d-14dd-4282-9679-92271c8e923d-tesla_s_ac_s?asset_id=d9331d5c-66a1-4ae4-ba01-2456f44ea04b&amp;img_etag=%2242179329af49407b9fb4dc05c44dd687%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer top-shadow" data-section-behavior="crisp-spacer" data-layer="1" data-layer-name="over">
      </div>
      <div class="section single-column-section split-layout image-on-right" data-section-behavior="crisp-split-layout" data-layer="0" data-layer-name="over">
        <div class="section-view">
              <div class="section-background">
                <div class="section-background-image" style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/68fe1ea7-fc6e-4480-9b7d-ec902ad35557-whatsapp_ima?asset_id=b27ac5cb-ae7d-4285-a69d-4850cd36bf75&amp;img_etag=%226311ae898a30475e9b89972e1bd89230%22&amp;image_assets=false&amp;size=1024" data-image-width="187" data-image-height="230"></a></div>
              </div>
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                            <h3 class=" text-center" >Shadowgraph (1896)</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/911ce749-4b38-4690-8c01-63eb7f888dab-images_png?asset_id=499caad8-3a83-49e7-9e52-50d9afc0a30a&amp;img_etag=%22e82cefbc7f6f4983b28f1a1c723bb216%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="911ce749-4b38-4690-8c01-63eb7f888dab" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/911ce749-4b38-4690-8c01-63eb7f888dab-images_png?asset_id=499caad8-3a83-49e7-9e52-50d9afc0a30a&amp;img_etag=%22e82cefbc7f6f4983b28f1a1c723bb216%22&amp;image_assets=false&amp;size=1024" style="width: 382px; padding-top: 34.55497382198953%" data-image-width="382" data-image-height="132"></span>
                      </a>
                    </div>
                  </div>
                                  <p class=" " ><b><i>Tesla discovered the potential of X-rays, which he called &quot;shadowgraphs,&quot; leading to groundbreaking experiments in imaging.</i></b></p>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer bottom-shadow" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section card-flipbook-section" data-section-behavior="crisp-column-overlay" data-spacing=".75" data-layer="-1" data-layer-name="under">
        <div class="section-view">
          <div class="section-background">
            <div class="section-background-image" style=" background-position: 50% 50%;" data-pan-and-zoom="zoom-in"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/eb6f56d4-79b1-4e1f-afe6-ecf6b1ea2bca-image__1__jp?asset_id=b856d167-d52e-481b-965e-a7d63b956d0d&img_etag=%22964b0768fe594244b6ab8def830cd749%22&image_assets=false&size=1024" data-image-width="981" data-image-height="650"></a></div>
          </div>
          <div class="section-content">
            <div class="section-content-view card-center">
              <div class="content-container">
                            <h3 class=" text-center" >Luminaries (1896-98)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-a5b97000-4791-4315-9815-cac5bec9c347">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/a5b97000-4791-4315-9815-cac5bec9c347-image__3__jp?asset_id=df5eb4af-35c9-42ba-a880-4a83777275d2&amp;img_etag=%2288c215a43ba5427da444671beb134830%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="a5b97000-4791-4315-9815-cac5bec9c347" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/a5b97000-4791-4315-9815-cac5bec9c347-image__3__jp?asset_id=df5eb4af-35c9-42ba-a880-4a83777275d2&amp;img_etag=%2288c215a43ba5427da444671beb134830%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-a5b97000-4791-4315-9815-cac5bec9c347" class="caption "><i><b>Tesla collaborated with and influenced many prominent scientists and inventors during this period, including Lord Kelvin and Sir William Crookes. His ideas on electricity and wireless power attracted the brightest minds of the era</b></i>.</div>
                  </div>
                                  <h3 class=" text-center" >Vril Power (1898)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-c3e126c0-cebc-4fac-9640-69a91f76add4">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/c3e126c0-cebc-4fac-9640-69a91f76add4-image__4__jp?asset_id=dbae0bc4-293c-4a4b-9382-63f518d7effd&amp;img_etag=%2257ab139c3d3f46e1b32a44faf2de6b3f%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="c3e126c0-cebc-4fac-9640-69a91f76add4" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/c3e126c0-cebc-4fac-9640-69a91f76add4-image__4__jp?asset_id=dbae0bc4-293c-4a4b-9382-63f518d7effd&amp;img_etag=%2257ab139c3d3f46e1b32a44faf2de6b3f%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-c3e126c0-cebc-4fac-9640-69a91f76add4" class="caption "><i><b>Tesla’s ideas about unseen energy forms, like wireless power transmission and teleforce (sometimes referred to as &quot;Vril energy&quot;), began to take shape in this period.</b></i></div>
                  </div>
                                  <h3 class=" text-center" >Waldorf-Astoria (1898)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-fd4a05eb-7b66-445d-99a7-02ba7a2552b2">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/fd4a05eb-7b66-445d-99a7-02ba7a2552b2-image__5__jp?asset_id=c764b4d0-04a9-4536-88c5-3fd7e451cd89&amp;img_etag=%22c782eb84fba340ffb3a50d4ecaf4aeee%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="fd4a05eb-7b66-445d-99a7-02ba7a2552b2" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/fd4a05eb-7b66-445d-99a7-02ba7a2552b2-image__5__jp?asset_id=c764b4d0-04a9-4536-88c5-3fd7e451cd89&amp;img_etag=%22c782eb84fba340ffb3a50d4ecaf4aeee%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-fd4a05eb-7b66-445d-99a7-02ba7a2552b2" class="caption "><i><b>Tesla took residence at the Waldorf-Astoria Hotel in New York, where he lived for many years. During this time, he developed various innovations and worked on perfecting wireless transmission.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer top-shadow" data-section-behavior="crisp-spacer" data-layer="1" data-layer-name="over">
      </div>
      <div class="section single-column-section split-layout image-on-left" data-section-behavior="crisp-split-layout" data-layer="0" data-layer-name="over">
        <div class="section-view">
              <div class="section-background">
                <div class="section-background-image" style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/9996020a-a499-4c72-8a1d-3ecb1d82406c-tesla_colora?asset_id=c542f10c-bf03-4007-b26f-1ff3da146d40&amp;img_etag=%22f6274f809e6c457ca0e19795b5b551df%22&amp;image_assets=false&amp;size=1024" data-image-width="500" data-image-height="519"></a></div>
              </div>
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                            <h3 class=" text-center" >Colorado Springs (1899)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-9fc9f0f3-64dc-487d-929c-066ebbaba072">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/9fc9f0f3-64dc-487d-929c-066ebbaba072-image__6__jp?asset_id=27ca03db-727d-4e61-9113-9db869673888&amp;img_etag=%224a16947c0ce24991874a8cc88fd90c56%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="9fc9f0f3-64dc-487d-929c-066ebbaba072" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/9fc9f0f3-64dc-487d-929c-066ebbaba072-image__6__jp?asset_id=27ca03db-727d-4e61-9113-9db869673888&amp;img_etag=%224a16947c0ce24991874a8cc88fd90c56%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-9fc9f0f3-64dc-487d-929c-066ebbaba072" class="caption "><i><b>Tesla moved to Colorado Springs to conduct large-scale electrical experiments, including lightning tests and wireless transmission experiments. This is where he created the famous photos of artificial lightning.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer bottom-shadow" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section card-flipbook-section" data-section-behavior="crisp-column-overlay" data-spacing=".75" data-layer="-1" data-layer-name="under">
        <div class="section-view">
          <div class="section-background">
            <div class="section-background-image" style=" background-position: 50% 50%;" data-pan-and-zoom="zoom-in"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/352432f5-2405-4c91-a804-246416bc949d-image__7__jp?asset_id=135287d1-76de-4ad2-a15f-7f965c34a161&img_etag=%22bac7a2ccdbc54ad9be18fb26104b620f%22&image_assets=false&size=1024" data-image-width="1024" data-image-height="1024"></a></div>
          </div>
          <div class="section-content">
            <div class="section-content-view card-center">
              <div class="content-container">
                            <h3 class=" text-center" >The House of Morgan (1901)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-e40a3fbb-4e19-4c58-8aef-a5a5b0323177">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/e40a3fbb-4e19-4c58-8aef-a5a5b0323177-lab_photo_th?asset_id=41399326-d3a1-47f9-a498-e6a0ac527c50&amp;img_etag=%2243d5ed77fa97485fa5d75de847f2695f%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="e40a3fbb-4e19-4c58-8aef-a5a5b0323177" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/e40a3fbb-4e19-4c58-8aef-a5a5b0323177-lab_photo_th?asset_id=41399326-d3a1-47f9-a498-e6a0ac527c50&amp;img_etag=%2243d5ed77fa97485fa5d75de847f2695f%22&amp;image_assets=false&amp;size=1024" style="width: 1199px; padding-top: 62.38532110091744%" data-image-width="1199" data-image-height="748"></span>
                      </a>
                    </div>
                    <div id="caption-e40a3fbb-4e19-4c58-8aef-a5a5b0323177" class="caption "><i><b>Tesla secured funding from financier J.P. Morgan to build Wardenclyffe Tower, his ambitious project to create a global wireless communication system.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer top-shadow" data-section-behavior="crisp-spacer" data-layer="1" data-layer-name="over">
      </div>
      <div class="section single-column-section split-layout image-on-right" data-section-behavior="crisp-split-layout" data-layer="0" data-layer-name="over">
        <div class="section-view">
              <div class="section-background">
                <div class="section-background-image" style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/b60688fb-909a-4a1d-a998-e189beaa2e46-image__9__jp?asset_id=b8f9110c-1bb6-4202-84d3-99b405b6b186&amp;img_etag=%2234e4ed0032b64c77af562b9f66703f5c%22&amp;image_assets=false&amp;size=1024" data-image-width="1024" data-image-height="1024"></a></div>
              </div>
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                            <h3 class=" text-center" >Clash of the Titans (1901)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-7eece5f4-0fab-4f23-8e67-733c512634f6">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/7eece5f4-0fab-4f23-8e67-733c512634f6-england_559a?asset_id=84aac580-d993-41cd-802f-b5f4faf76928&amp;img_etag=%224305a3c169784215b0b3b728aacec0b4%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="7eece5f4-0fab-4f23-8e67-733c512634f6" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/7eece5f4-0fab-4f23-8e67-733c512634f6-england_559a?asset_id=84aac580-d993-41cd-802f-b5f4faf76928&amp;img_etag=%224305a3c169784215b0b3b728aacec0b4%22&amp;image_assets=false&amp;size=1024" style="width: 1500px; padding-top: 69%" data-image-width="1500" data-image-height="1035"></span>
                      </a>
                    </div>
                    <div id="caption-7eece5f4-0fab-4f23-8e67-733c512634f6" class="caption text-center"><i><b>Tesla’s dream of wireless communication faced competition from Guglielmo Marconi, who ultimately succeeded in transmitting the first transatlantic radio signal, a major blow to Tesla’s plans.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer bottom-shadow" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section card-flipbook-section" data-section-behavior="crisp-column-overlay" data-spacing=".75" data-layer="-1" data-layer-name="under">
        <div class="section-view">
          <div class="section-background">
            <div class="section-background-image" style=" background-position: 50% 50%;" data-pan-and-zoom="zoom-in"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/9f801327-685f-4a60-9630-d404d338e49c-image__10__j?asset_id=36d30f64-309d-4626-b483-b15841d45360&img_etag=%229ba5fa4f157c4e328c3fefb6de29336b%22&image_assets=false&size=1024" data-image-width="1024" data-image-height="1024"></a></div>
          </div>
          <div class="section-content">
            <div class="section-content-view card-center">
              <div class="content-container">
                            <h3 class=" text-center" >The Execution (1903)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-50ab4458-3029-4413-bae8-53e4823d0c83">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/50ab4458-3029-4413-bae8-53e4823d0c83-electrocutin?asset_id=66ae8847-1d93-4602-a815-1357d9187d24&amp;img_etag=%2258c1867571284c2b86f0fe2bdaad79cd%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="50ab4458-3029-4413-bae8-53e4823d0c83" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/50ab4458-3029-4413-bae8-53e4823d0c83-electrocutin?asset_id=66ae8847-1d93-4602-a815-1357d9187d24&amp;img_etag=%2258c1867571284c2b86f0fe2bdaad79cd%22&amp;image_assets=false&amp;size=1024" style="width: 2048px; padding-top: 66.748046875%" data-image-width="2048" data-image-height="1367"></span>
                      </a>
                    </div>
                    <div id="caption-50ab4458-3029-4413-bae8-53e4823d0c83" class="caption "><b><i>Thomas Alva Edison executed the elephant to show how dangerous is AC current .</i></b></div>
                  </div>
                                  <h3 class=" text-center" >Dissolution (1904-1906)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-f473858e-c15d-4c5b-807c-0799dfd4a8c3">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/f473858e-c15d-4c5b-807c-0799dfd4a8c3-image__11__j?asset_id=e955966f-95de-4934-97a3-40dea00d2039&amp;img_etag=%227c188d918fb84ebbb843567d33cef05d%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="f473858e-c15d-4c5b-807c-0799dfd4a8c3" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/f473858e-c15d-4c5b-807c-0799dfd4a8c3-image__11__j?asset_id=e955966f-95de-4934-97a3-40dea00d2039&amp;img_etag=%227c188d918fb84ebbb843567d33cef05d%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-f473858e-c15d-4c5b-807c-0799dfd4a8c3" class="caption "><i>Tesla’s dream collapsed as Wardenclyffe was abandoned, and he lost the backing of Morgan. His financial troubles deepened</i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer top-shadow" data-section-behavior="crisp-spacer" data-layer="1" data-layer-name="over">
      </div>
      <div class="section single-column-section split-layout image-on-left" data-section-behavior="crisp-split-layout" data-layer="0" data-layer-name="over">
        <div class="section-view">
              <div class="section-background">
                <div class="section-background-image" style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/86cc7f63-ad6a-4413-b127-92f68e194550-image__14__j?asset_id=fdd75bc1-7618-4911-a92c-67c8e0f5c8c8&amp;img_etag=%22e158e6fe7f504bffb3dfcf09bf98c2f0%22&amp;image_assets=false&amp;size=1024" data-image-width="1024" data-image-height="1024"></a></div>
              </div>
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                            <h3 class=" text-center" >The Child of His Dreams (1907-1908)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-0da46eda-850e-4e72-aefe-b4c7e08cfb12">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/0da46eda-850e-4e72-aefe-b4c7e08cfb12-image__13__j?asset_id=5a278089-713d-4089-8661-d0a6a838216f&amp;img_etag=%2264c80bd3e9404af79fa1df41e98b1520%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="0da46eda-850e-4e72-aefe-b4c7e08cfb12" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/0da46eda-850e-4e72-aefe-b4c7e08cfb12-image__13__j?asset_id=5a278089-713d-4089-8661-d0a6a838216f&amp;img_etag=%2264c80bd3e9404af79fa1df41e98b1520%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-0da46eda-850e-4e72-aefe-b4c7e08cfb12" class="caption "><i><b>Tesla continued working on his bladeless turbine, which he believed would revolutionize power generation.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer bottom-shadow" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section card-flipbook-section" data-section-behavior="crisp-column-overlay" data-spacing=".75" data-layer="-1" data-layer-name="under">
        <div class="section-view">
          <div class="section-background">
            <div class="section-background-image" style=" background-position: 50% 50%;" data-pan-and-zoom="zoom-in"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/0210ddaf-b27e-4f22-a0b4-f4ebf773cd71-171713033081?asset_id=896e4d15-a134-48eb-a0cc-a0ae01d21444&img_etag=%22ad90dde61cda4569a22e521fc2db0b1d%22&image_assets=false&size=1024" data-image-width="720" data-image-height="720"></a></div>
          </div>
          <div class="section-content">
            <div class="section-content-view card-center">
              <div class="content-container">
                            <h3 class=" text-center" >Bladeless Turbines (1909-10)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-875f9682-6bc7-466e-a903-4693ef3954c7">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/875f9682-6bc7-466e-a903-4693ef3954c7-tesla_s_turb?asset_id=ceb036cd-3296-4724-b411-6de64e4d8906&amp;img_etag=%22ae30f9e000f946caae45de37b90bc8f5%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="875f9682-6bc7-466e-a903-4693ef3954c7" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/875f9682-6bc7-466e-a903-4693ef3954c7-tesla_s_turb?asset_id=ceb036cd-3296-4724-b411-6de64e4d8906&amp;img_etag=%22ae30f9e000f946caae45de37b90bc8f5%22&amp;image_assets=false&amp;size=1024" style="width: 800px; padding-top: 119.75%" data-image-width="800" data-image-height="958"></span>
                      </a>
                    </div>
                    <div id="caption-875f9682-6bc7-466e-a903-4693ef3954c7" class="caption "><i><b>Tesla filed patents for his bladeless turbines, though the invention never saw widespread commercial success.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer top-shadow" data-section-behavior="crisp-spacer" data-layer="1" data-layer-name="over">
      </div>
      <div class="section single-column-section split-layout image-on-right" data-section-behavior="crisp-split-layout" data-layer="0" data-layer-name="over">
        <div class="section-view">
              <div class="section-background">
                <div class="section-background-image" style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/95d0eb88-670a-4e1f-bd64-78af19d265b3-0_b7jhzttny9?asset_id=e24b4e28-a89e-4044-9650-fd27581d575b&amp;img_etag=%22cddc62ae3d2742b693ac695309b6a573%22&amp;image_assets=false&amp;size=1024" data-image-width="470" data-image-height="330"></a></div>
              </div>
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                            <h3 class=" text-center" >J. P. Morgan Jr. (1912-14)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-8b6cb567-6b32-46b1-9426-1c62daf5bda6">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/8b6cb567-6b32-46b1-9426-1c62daf5bda6-0_fhqpjcumkw?asset_id=3b79bee4-4cc5-4ba2-8608-e76f29c713f9&amp;img_etag=%2249e9e33cdb2d4956b9a4a2441ece891e%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="8b6cb567-6b32-46b1-9426-1c62daf5bda6" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/8b6cb567-6b32-46b1-9426-1c62daf5bda6-0_fhqpjcumkw?asset_id=3b79bee4-4cc5-4ba2-8608-e76f29c713f9&amp;img_etag=%2249e9e33cdb2d4956b9a4a2441ece891e%22&amp;image_assets=false&amp;size=1024" style="width: 600px; padding-top: 78.5%" data-image-width="600" data-image-height="471"></span>
                      </a>
                    </div>
                    <div id="caption-8b6cb567-6b32-46b1-9426-1c62daf5bda6" class="caption "><i><b>Tesla tried to regain the backing of J.P. Morgan’s son, J.P. Morgan Jr., to fund his wireless projects, but failed to secure new investments.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer bottom-shadow" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section card-flipbook-section" data-section-behavior="crisp-column-overlay" data-spacing=".75" data-layer="-1" data-layer-name="under">
        <div class="section-view">
          <div class="section-background">
            <div class="section-background-image" style=" background-position: 50% 50%;" data-pan-and-zoom="zoom-in"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/3d41ed6a-c5e7-4cda-849d-37fd432a1381-1_kgao4gvtcx?asset_id=0c1aad19-639b-4caf-8347-43665d2a237b&img_etag=%223a3b9cd3f1274868ad8560fbf6bea21f%22&image_assets=false&size=1024" data-image-width="700" data-image-height="400"></a></div>
          </div>
          <div class="section-content">
            <div class="section-content-view card-center">
              <div class="content-container">
                            <h3 class=" text-center" >The Invisible Audience (1915-21)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-a3586d97-6ed7-46c5-960a-895016c5194a">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/a3586d97-6ed7-46c5-960a-895016c5194a-image__15__j?asset_id=e2d1f4f3-dfbe-4822-ab4a-86b6692d9097&amp;img_etag=%229a47068c41ec4fa59b7f5a048fc5fa23%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="a3586d97-6ed7-46c5-960a-895016c5194a" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/a3586d97-6ed7-46c5-960a-895016c5194a-image__15__j?asset_id=e2d1f4f3-dfbe-4822-ab4a-86b6692d9097&amp;img_etag=%229a47068c41ec4fa59b7f5a048fc5fa23%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-a3586d97-6ed7-46c5-960a-895016c5194a" class="caption "><i><b>Tesla began retreating from public life, although he continued to work on smaller inventions and projects, such as remote control and robotics.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer top-shadow" data-section-behavior="crisp-spacer" data-layer="1" data-layer-name="over">
      </div>
      <div class="section single-column-section split-layout image-on-left" data-section-behavior="crisp-split-layout" data-layer="0" data-layer-name="over">
        <div class="section-view">
              <div class="section-background">
                <div class="section-background-image" style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/1e6524ca-f4e0-4e89-bbf7-8f9cdd439421-image__17__j?asset_id=0eec45f3-808e-44f1-a281-913558ba3972&amp;img_etag=%228f566c164e1e439ba3582a4876552a1b%22&amp;image_assets=false&amp;size=1024" data-image-width="1024" data-image-height="1024"></a></div>
              </div>
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                            <h3 class=" text-center" >Transmutation (1918-21)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-dbab7350-7de8-494d-8e73-98463da6387d">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/dbab7350-7de8-494d-8e73-98463da6387d-image__16__j?asset_id=b1f702e5-6fb4-4eda-a6e6-56b91cdccb50&amp;img_etag=%22d38b9ec55f2d4ba98dd42b27ebf28382%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="dbab7350-7de8-494d-8e73-98463da6387d" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/dbab7350-7de8-494d-8e73-98463da6387d-image__16__j?asset_id=b1f702e5-6fb4-4eda-a6e6-56b91cdccb50&amp;img_etag=%22d38b9ec55f2d4ba98dd42b27ebf28382%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-dbab7350-7de8-494d-8e73-98463da6387d" class="caption "><i><b>Tesla explored ideas related to &quot;transmutation,&quot; believing that he could create new materials and elements using high-frequency electricity.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer bottom-shadow" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section card-flipbook-section" data-section-behavior="crisp-column-overlay" data-spacing=".75" data-layer="-1" data-layer-name="under">
        <div class="section-view">
          <div class="section-background">
            <div class="section-background-image" style=" background-position: 50% 50%;" data-pan-and-zoom="zoom-in"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/eb7980fb-4c04-409c-bde6-63fcdf99b69a-image__19__j?asset_id=65d18632-ca2b-4a7c-a6da-d8f669af59b7&img_etag=%22d5a236cac6d64dddaeeb13d32c18b67f%22&image_assets=false&size=1024" data-image-width="1024" data-image-height="1024"></a></div>
          </div>
          <div class="section-content">
            <div class="section-content-view card-center">
              <div class="content-container">
                            <h3 class=" text-center" >Faster Than the Speed of Light (1927-40)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-0cd2bf42-b012-46be-b7c2-8b7b1b24ff05">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/0cd2bf42-b012-46be-b7c2-8b7b1b24ff05-image__20__j?asset_id=c3ead932-ac2d-48d1-ba32-3d798dd71141&amp;img_etag=%22e323630fb67a48c0811dafc358d973d7%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="0cd2bf42-b012-46be-b7c2-8b7b1b24ff05" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/0cd2bf42-b012-46be-b7c2-8b7b1b24ff05-image__20__j?asset_id=c3ead932-ac2d-48d1-ba32-3d798dd71141&amp;img_etag=%22e323630fb67a48c0811dafc358d973d7%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-0cd2bf42-b012-46be-b7c2-8b7b1b24ff05" class="caption "><i><b>Tesla began to make claims that his inventions could surpass the speed of light, which were met with skepticism by the scientific community.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer top-shadow" data-section-behavior="crisp-spacer" data-layer="1" data-layer-name="over">
      </div>
      <div class="section single-column-section split-layout image-on-right" data-section-behavior="crisp-split-layout" data-layer="0" data-layer-name="over">
        <div class="section-view">
              <div class="section-background">
                <div class="section-background-image" style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/927c1b49-b3b9-4f9f-b1a4-56d364dd9d13-image__21__j?asset_id=39fe44ff-a45f-4b5b-8edc-29eab38a0437&amp;img_etag=%2222e1a6a8f4fa4629be401191143d01aa%22&amp;image_assets=false&amp;size=1024" data-image-width="1024" data-image-height="1024"></a></div>
              </div>
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                            <h3 class=" text-center" >Loose Ends (1931-43)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-e1f103b7-e312-4ef5-9e0e-d2d93c2876e0">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/e1f103b7-e312-4ef5-9e0e-d2d93c2876e0-image__2__jp?asset_id=756fb638-652c-486a-a4a3-2b2085e4e47e&amp;img_etag=%221d222ef2de484b8ba5c2fca3041c9cfe%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="e1f103b7-e312-4ef5-9e0e-d2d93c2876e0" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/e1f103b7-e312-4ef5-9e0e-d2d93c2876e0-image__2__jp?asset_id=756fb638-652c-486a-a4a3-2b2085e4e47e&amp;img_etag=%221d222ef2de484b8ba5c2fca3041c9cfe%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-e1f103b7-e312-4ef5-9e0e-d2d93c2876e0" class="caption "><i><b>Tesla spent his last years working on smaller projects, tying up loose ends from his career, but remained largely isolated.
Interactive Feature: A virtual tour of Tesla’s final New York hotel room, where he spent his last days.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section single-column-section split-layout image-on-left" data-section-behavior="crisp-split-layout" data-layer="0" data-layer-name="over">
        <div class="section-view">
              <div class="section-background">
                <div class="section-background-image" style="background-position: 50% 50%;"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/5b1e640e-3e15-43a9-80ae-95e3b0a85255-image__22__j?asset_id=e9a72481-85f6-48a1-9a5f-d5448e5630ab&amp;img_etag=%22a94338231bae4e2c9eb28b712449c314%22&amp;image_assets=false&amp;size=1024" data-image-width="1024" data-image-height="1024"></a></div>
              </div>
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                            <h3 class=" text-center" >The FBI and the TeslaPapers (1943-56)</h3>
                              <div class="image" role="figure" aria-labelledby="caption-c2f52363-2389-4639-ad9a-2d10c78190fc">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/c2f52363-2389-4639-ad9a-2d10c78190fc-image__24__j?asset_id=92d80973-ed77-48db-ae3a-a03723590f95&amp;img_etag=%2242b42bd79fa64f6b8218aebbf58327bd%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="c2f52363-2389-4639-ad9a-2d10c78190fc" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/c2f52363-2389-4639-ad9a-2d10c78190fc-image__24__j?asset_id=92d80973-ed77-48db-ae3a-a03723590f95&amp;img_etag=%2242b42bd79fa64f6b8218aebbf58327bd%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-c2f52363-2389-4639-ad9a-2d10c78190fc" class="caption "><i><b>After Tesla’s death in 1943, the FBI seized his papers, sparking rumors about the secret nature of his work. This led to enduring mysteries around his final experiments.</b></i></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer bottom-shadow" data-section-behavior="crisp-spacer" data-layer-name="over">
      </div>
      <div class="section card-flipbook-section" data-section-behavior="crisp-column-overlay" data-spacing=".75" data-layer="-1" data-layer-name="under">
        <div class="section-view">
          <div class="section-background">
            <div class="section-background-image" style=" background-position: 50% 50%;" data-pan-and-zoom="zoom-in"><a class="background-image-placeholder-link" href="/webpage/u2O0C695fPwsD/resources/84957ec9-ef08-48a7-a70e-5fa704d326b3-image__23__j?asset_id=b6ab618b-c012-4410-aa6b-161df9dee66f&img_etag=%227cdeb8cea5ff4e65a11a77df469d9178%22&image_assets=false&size=1024" data-image-width="1024" data-image-height="639"></a></div>
          </div>
          <div class="section-content">
            <div class="section-content-view card-center">
              <div class="content-container">
                            <h3 class=" text-center" >The Wizard&#39;s Legacy</h3>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/600cd942-6ad3-4173-ac4e-7edce3051dcb-nikola_tesla?asset_id=7248e22b-ce29-4045-b4dc-e26179c2c0b6&amp;img_etag=%221f0fc625f94d4b519e5b563284d7aee5%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="600cd942-6ad3-4173-ac4e-7edce3051dcb" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/600cd942-6ad3-4173-ac4e-7edce3051dcb-nikola_tesla?asset_id=7248e22b-ce29-4045-b4dc-e26179c2c0b6&amp;img_etag=%221f0fc625f94d4b519e5b563284d7aee5%22&amp;image_assets=false&amp;size=1024" style="width: 600px; padding-top: 67.16666666666666%" data-image-width="600" data-image-height="403"></span>
                      </a>
                    </div>
                  </div>
                              <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/879e5146-5c17-42f4-be9e-a403510bb9f5-v2_5hko5_ygd?asset_id=634a326b-9758-4260-a0b8-748522c62fc4&amp;img_etag=%2253aee8fac2c74ec4b6ba94f3c27a2edf%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="879e5146-5c17-42f4-be9e-a403510bb9f5" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/879e5146-5c17-42f4-be9e-a403510bb9f5-v2_5hko5_ygd?asset_id=634a326b-9758-4260-a0b8-748522c62fc4&amp;img_etag=%2253aee8fac2c74ec4b6ba94f3c27a2edf%22&amp;image_assets=false&amp;size=1024" style="width: 1344px; padding-top: 57.14285714285714%" data-image-width="1344" data-image-height="768"></span>
                      </a>
                    </div>
                  </div>
                              <div class="image" role="figure" aria-labelledby="caption-8f086969-bef7-4c6e-90bf-819a4486ebfd">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/8f086969-bef7-4c6e-90bf-819a4486ebfd-image__25__j?asset_id=b8c9bbe9-64f5-4a41-8727-93895c4191d5&amp;img_etag=%22ce7455f541f542b49319a35283145742%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="8f086969-bef7-4c6e-90bf-819a4486ebfd" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/8f086969-bef7-4c6e-90bf-819a4486ebfd-image__25__j?asset_id=b8c9bbe9-64f5-4a41-8727-93895c4191d5&amp;img_etag=%22ce7455f541f542b49319a35283145742%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                    <div id="caption-8f086969-bef7-4c6e-90bf-819a4486ebfd" class="caption "><b><i>Nikola Tesla’s legacy continued to grow after his death, influencing generations of scientists, engineers, and inventors. His work is celebrated today as foundational to modern electrical engineering.</i></b></div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section spacer-section content-spacer top-shadow" data-section-behavior="crisp-spacer" data-layer="1" data-layer-name="over">
      </div>
      <div class="section full-width-section" data-section-behavior="crisp-full-width-photo" data-layer="0" data-layer-name="over">
        <div class="section-view">
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                        <div class="image">
                    <div class="image-wrapper">
                      <a
                        
                         href="/webpage/u2O0C695fPwsD/resources/04c2584c-8829-41ff-b866-bbafaf3f6975-image__24__j?asset_id=355ef32e-6bc1-47b0-ab15-dc7fca0a5812&amp;img_etag=%227bdcce4d167343eebf5fad209a9276d6%22&amp;image_assets=false&amp;size=1024" class="image-viewer-link" 
                        target="_blank"
                        rel="nofollow noreferrer"
                        
                          
                           aria-label="Large preview" 
                      >
                        <span data-id="04c2584c-8829-41ff-b866-bbafaf3f6975" class="image-placeholder-link" data-href="/webpage/u2O0C695fPwsD/resources/04c2584c-8829-41ff-b866-bbafaf3f6975-image__24__j?asset_id=355ef32e-6bc1-47b0-ab15-dc7fca0a5812&amp;img_etag=%227bdcce4d167343eebf5fad209a9276d6%22&amp;image_assets=false&amp;size=1024" style="width: 1024px; padding-top: 100%" data-image-width="1024" data-image-height="1024"></span>
                      </a>
                    </div>
                  </div>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section single-column-section  large-content-spacing-top large-content-spacing-bottom" data-section-behavior="crisp-single-column" data-layer="0" data-layer-name="over">
        <div class="section-view">
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section author-section" data-section-behavior="crisp-author" data-layer-name="over">
        <div class="section-view">
          <div class="section-content">
            <div class="section-content-view">
              <div class="content-container">
                <div class="author-appreciation-container">
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!--BUMPER-SECTION-TOP-LEVEL-START-->
      <div class="section bumper-section default-bumper-section" data-layer-name="over">
          <div class="section-view">
              <!--FOOTER-START-->
              <nav class="footer" aria-label="Adobe links">
                  <a class="tos" target="_blank" href="http://www.adobe.com/legal/terms.html" rel="nofollow">Terms of Service</a>
                  <a class="privacy" target="_blank" href="http://www.adobe.com/go/privacy" rel="nofollow">Privacy Policy</a>
                  <a class="js-report-abuse" href="#" target="_blank" rel="nofollow">Report Abuse</a>
              </nav>
              <!--FOOTER-END-->
          </div>
      </div>
      <!--BUMPER-SECTION-TOP-LEVEL-END-->
</div>
</div>
          </div>
        </div>
      </div>
      <a href="#" class="publication-viewer-next-link"></a> <a href="#" class="publication-viewer-previous-link"></a>
    </div>
  </div>
  <!-- javascripts go here -->
    <script type="text/javascript">
      window.useNewBumper = true;
      window.hzGneissHostname = 'hz-gneiss.adobe.io';
    </script>

    <script type="text/javascript" src="/webpage/static/runtime/runtime-prod.gz.js" charset="utf-8"></script>
  <!--BEGIN-BUMPER-BEHAVIORS-->
  <!--END-BUMPER-BEHAVIORS-->
</body>
</html>
```
##Credits:- 
This website is created by :-
1) Abhinav Shakya
2) Ayush Kumar Singh
3) Dhruv Kumar
4) Lakshya Saxena
