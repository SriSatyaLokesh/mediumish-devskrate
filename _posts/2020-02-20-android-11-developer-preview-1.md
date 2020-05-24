---
layout: post
title:  "7 Cool New Android 11 Features"
author: puneeth
categories: [ android ]
image: assets/images/android11.png
tags: [google, android]
---


<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<title>Series</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>

<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000000;
  background-color: #ffffff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #ffffff;
  border: 1px solid #dddddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #cccccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #dddddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #dddddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #dddddd;
}
.table .table {
  background-color: #ffffff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #dddddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #dddddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #dddddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #ffffff;
  background-image: none;
  border: 1px solid #cccccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999999;
}
.form-control::-webkit-input-placeholder {
  color: #999999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333333;
  background-color: #ffffff;
  border-color: #cccccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #ffffff;
  border-color: #cccccc;
}
.btn-default .badge {
  color: #ffffff;
  background-color: #333333;
}
.btn-primary {
  color: #ffffff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #ffffff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #ffffff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #ffffff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #ffffff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #ffffff;
}
.btn-success {
  color: #ffffff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #ffffff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #ffffff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #ffffff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #ffffff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #ffffff;
}
.btn-info {
  color: #ffffff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #ffffff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #ffffff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #ffffff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #ffffff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #ffffff;
}
.btn-warning {
  color: #ffffff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #ffffff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #ffffff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #ffffff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #ffffff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #ffffff;
}
.btn-danger {
  color: #ffffff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #ffffff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #ffffff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #ffffff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #ffffff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #ffffff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #ffffff;
  border: 1px solid #cccccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #ffffff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #cccccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #dddddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #dddddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #ffffff;
  border: 1px solid #dddddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #dddddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #dddddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #ffffff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #ffffff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #dddddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #dddddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #ffffff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777777;
}
.navbar-default .navbar-nav > li > a {
  color: #777777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #cccccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #dddddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #dddddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #cccccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777777;
}
.navbar-default .navbar-link:hover {
  color: #333333;
}
.navbar-default .btn-link {
  color: #777777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #cccccc;
}
.navbar-inverse {
  background-color: #222222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #ffffff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #ffffff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #ffffff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #ffffff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #ffffff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #ffffff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #ffffff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #ffffff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #ffffff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #ffffff;
  border: 1px solid #dddddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #dddddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #ffffff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #ffffff;
  border-color: #dddddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #ffffff;
  border: 1px solid #dddddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #ffffff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #ffffff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #ffffff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #ffffff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #ffffff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #ffffff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #ffffff;
  border: 1px solid #dddddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #ffffff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #ffffff;
  border: 1px solid #dddddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #ffffff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #ffffff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #dddddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #dddddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #dddddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #dddddd;
}
.panel-default {
  border-color: #dddddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #dddddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #dddddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #dddddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #ffffff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #ffffff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000000;
  text-shadow: 0 1px 0 #ffffff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #ffffff;
  border: 1px solid #999999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #ffffff;
  text-align: center;
  background-color: #000000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #ffffff;
  background-clip: padding-box;
  border: 1px solid #cccccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #ffffff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #ffffff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #ffffff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #ffffff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #ffffff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #ffffff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #ffffff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #ffffff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #ffffff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eeeeee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #ffffff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #ffffff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #ffffff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#login_widget {
  float: right;
}
span#login_widget > .button,
#logout {
  color: #333333;
  background-color: #ffffff;
  border-color: #cccccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #ffffff;
  border-color: #cccccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #ffffff;
  background-color: #333333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #eeeeee;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #dddddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #dddddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #dddddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: baseline;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #eeeeee;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #dddddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #eeeeee;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #ffffff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #ffffff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #ffffff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90caf9;
  border-left-color: #e3f2fd;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #e3f2fd;
  border-right-width: 1px;
  background: #e3f2fd;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42a5f5 -40px, #42a5f5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42a5f5 -40px, #42a5f5 7px, #e3f2fd 7px, #e3f2fd 100%);
}
.edit_mode div.cell.selected {
  border-color: #66bb6a;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66bb6a -40px, #66bb6a 5px, transparent 5px, transparent 100%);
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
    /* Old browsers */
    -webkit-box-flex: 0;
    -moz-box-flex: 0;
    box-flex: 0;
    /* Modern browsers */
    flex: none;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303f9f;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000000;
}
.highlight-variable {
  color: #000000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000000;
  box-shadow: inset 0 0 1px #000000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #d84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
    /* Old browsers */
    -webkit-box-flex: 0;
    -moz-box-flex: 0;
    box-flex: 0;
    /* Modern browsers */
    flex: none;
  }
}
div.output_area pre {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  color: #000000;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: #000000;
  background-color: #000000;
}
.rendered_html pre {
  margin: 1em 2em;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #ffffff;
  color: #000000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid #000000;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid #000000;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #ffffff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #eeeeee;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #ffffff;
  background-image: none;
  border: 1px solid #cccccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333333;
  background-color: #ffffff;
  border-color: #cccccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #ffffff;
  border-color: #cccccc;
}
.notification_widget .badge {
  color: #ffffff;
  background-color: #333333;
}
.notification_widget.warning {
  color: #ffffff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #ffffff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #ffffff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #ffffff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #ffffff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #ffffff;
}
.notification_widget.success {
  color: #ffffff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #ffffff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #ffffff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #ffffff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #ffffff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #ffffff;
}
.notification_widget.info {
  color: #ffffff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #ffffff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #ffffff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #ffffff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #ffffff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #ffffff;
}
.notification_widget.danger {
  color: #ffffff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #ffffff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #ffffff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #ffffff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #ffffff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #ffffff;
}
div#pager {
  background-color: #ffffff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #eeeeee;
}
.terminal-app #header {
  background: #ffffff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="kn">as</span> <span class="nn">pd</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Create-A-Series-Object-from-A-Python-List">Create A <code>Series</code> Object from A Python List<a class="anchor-link" href="#Create-A-Series-Object-from-A-Python-List">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">ice_cream</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Chocolate&quot;</span><span class="p">,</span> <span class="s2">&quot;Vanilla&quot;</span><span class="p">,</span> <span class="s2">&quot;Strawberry&quot;</span><span class="p">,</span> <span class="s2">&quot;Rum Raisin&quot;</span><span class="p">]</span>

<span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">ice_cream</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[5]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0     Chocolate
1       Vanilla
2    Strawberry
3    Rum Raisin
dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">lottery</span> <span class="o">=</span> <span class="p">[</span><span class="mi">4</span><span class="p">,</span> <span class="mi">8</span><span class="p">,</span> <span class="mi">15</span><span class="p">,</span> <span class="mi">16</span><span class="p">,</span> <span class="mi">23</span><span class="p">,</span> <span class="mi">42</span><span class="p">]</span>

<span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">lottery</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[6]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0     4
1     8
2    15
3    16
4    23
5    42
dtype: int64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">registrations</span> <span class="o">=</span> <span class="p">[</span><span class="bp">True</span><span class="p">,</span> <span class="bp">False</span><span class="p">,</span> <span class="bp">False</span><span class="p">,</span> <span class="bp">False</span><span class="p">,</span> <span class="bp">True</span><span class="p">]</span>

<span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">registrations</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[7]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0     True
1    False
2    False
3    False
4     True
dtype: bool</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Create-A-Series-Object-from-a-Dictionary">Create A <code>Series</code> Object from a Dictionary<a class="anchor-link" href="#Create-A-Series-Object-from-a-Dictionary">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">webster</span> <span class="o">=</span> <span class="p">{</span><span class="s2">&quot;Aardvark&quot;</span> <span class="p">:</span> <span class="s2">&quot;An animal&quot;</span><span class="p">,</span>
           <span class="s2">&quot;Banana&quot;</span> <span class="p">:</span> <span class="s2">&quot;A delicious fruit&quot;</span><span class="p">,</span>
           <span class="s2">&quot;Cyan&quot;</span> <span class="p">:</span> <span class="s2">&quot;A color&quot;</span><span class="p">}</span>

<span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">webster</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[5]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Aardvark            An animal
Banana      A delicious fruit
Cyan                  A color
dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Intro-to-Attributes">Intro to Attributes<a class="anchor-link" href="#Intro-to-Attributes">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">about_me</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Smart&quot;</span><span class="p">,</span> <span class="s2">&quot;Handsome&quot;</span><span class="p">,</span> <span class="s2">&quot;Charming&quot;</span><span class="p">,</span> <span class="s2">&quot;Brilliant&quot;</span><span class="p">,</span> <span class="s2">&quot;Humble&quot;</span><span class="p">]</span>
<span class="n">s</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">about_me</span><span class="p">)</span>
<span class="n">s</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[8]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0        Smart
1     Handsome
2     Charming
3    Brilliant
4       Humble
dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">s</span><span class="o">.</span><span class="n">values</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[9]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>array([&#39;Smart&#39;, &#39;Handsome&#39;, &#39;Charming&#39;, &#39;Brilliant&#39;, &#39;Humble&#39;], dtype=object)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[10]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">s</span><span class="o">.</span><span class="n">index</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[10]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>RangeIndex(start=0, stop=5, step=1)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[11]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">s</span><span class="o">.</span><span class="n">dtype</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[11]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>dtype(&#39;O&#39;)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Intro-to-Methods">Intro to Methods<a class="anchor-link" href="#Intro-to-Methods">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[13]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">prices</span> <span class="o">=</span> <span class="p">[</span><span class="mf">2.99</span><span class="p">,</span> <span class="mf">4.45</span><span class="p">,</span> <span class="mf">1.36</span><span class="p">]</span>
<span class="n">s</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">prices</span><span class="p">)</span>
<span class="n">s</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[13]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    2.99
1    4.45
2    1.36
dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[14]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">s</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[14]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>8.8</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[15]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">s</span><span class="o">.</span><span class="n">product</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[15]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>18.095480000000006</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[16]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">s</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[16]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>2.9333333333333336</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Parameters-and-Arguments">Parameters and Arguments<a class="anchor-link" href="#Parameters-and-Arguments">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1"># Difficulty - Easy, Medium, Hard</span>
<span class="c1"># Volume - 1 through 10</span>
<span class="c1"># Subtitles - True / False</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[21]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">fruits</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Apple&quot;</span><span class="p">,</span> <span class="s2">&quot;Orange&quot;</span><span class="p">,</span> <span class="s2">&quot;Plum&quot;</span><span class="p">,</span> <span class="s2">&quot;Grape&quot;</span><span class="p">,</span> <span class="s2">&quot;Blueberry&quot;</span><span class="p">]</span>
<span class="n">weekdays</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Monday&quot;</span><span class="p">,</span> <span class="s2">&quot;Tuesday&quot;</span><span class="p">,</span> <span class="s2">&quot;Wednesday&quot;</span><span class="p">,</span> <span class="s2">&quot;Thursday&quot;</span><span class="p">,</span> <span class="s2">&quot;Friday&quot;</span><span class="p">]</span>

<span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">fruits</span><span class="p">,</span> <span class="n">weekdays</span><span class="p">)</span>
<span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">fruits</span><span class="p">,</span> <span class="n">index</span> <span class="o">=</span> <span class="n">weekdays</span><span class="p">)</span>
<span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">fruits</span><span class="p">,</span> <span class="n">index</span> <span class="o">=</span> <span class="n">weekdays</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[21]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Monday           Apple
Tuesday         Orange
Wednesday         Plum
Thursday         Grape
Friday       Blueberry
dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[22]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">fruits</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Apple&quot;</span><span class="p">,</span> <span class="s2">&quot;Orange&quot;</span><span class="p">,</span> <span class="s2">&quot;Plum&quot;</span><span class="p">,</span> <span class="s2">&quot;Grape&quot;</span><span class="p">,</span> <span class="s2">&quot;Blueberry&quot;</span><span class="p">,</span> <span class="s2">&quot;Watermelon&quot;</span><span class="p">]</span>
<span class="n">weekdays</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Monday&quot;</span><span class="p">,</span> <span class="s2">&quot;Tuesday&quot;</span><span class="p">,</span> <span class="s2">&quot;Wednesday&quot;</span><span class="p">,</span> <span class="s2">&quot;Thursday&quot;</span><span class="p">,</span> <span class="s2">&quot;Friday&quot;</span><span class="p">,</span> <span class="s2">&quot;Monday&quot;</span><span class="p">]</span>

<span class="n">pd</span><span class="o">.</span><span class="n">Series</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">fruits</span><span class="p">,</span> <span class="n">index</span> <span class="o">=</span> <span class="n">weekdays</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[22]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Monday            Apple
Tuesday          Orange
Wednesday          Plum
Thursday          Grape
Friday        Blueberry
Monday       Watermelon
dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Import-Series-with-the-read_csv-Method">Import <code>Series</code> with the <code>read_csv</code> Method<a class="anchor-link" href="#Import-Series-with-the-read_csv-Method">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[27]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">pokemon</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[27]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0       Bulbasaur
1         Ivysaur
2        Venusaur
3      Charmander
4      Charmeleon
5       Charizard
6        Squirtle
7       Wartortle
8       Blastoise
9        Caterpie
10        Metapod
11     Butterfree
12         Weedle
13         Kakuna
14       Beedrill
15         Pidgey
16      Pidgeotto
17        Pidgeot
18        Rattata
19       Raticate
20        Spearow
21         Fearow
22          Ekans
23          Arbok
24        Pikachu
25         Raichu
26      Sandshrew
27      Sandslash
28        Nidoran
29       Nidorina
          ...    
691     Clauncher
692     Clawitzer
693    Helioptile
694     Heliolisk
695        Tyrunt
696     Tyrantrum
697        Amaura
698       Aurorus
699       Sylveon
700      Hawlucha
701       Dedenne
702       Carbink
703         Goomy
704       Sliggoo
705        Goodra
706        Klefki
707      Phantump
708     Trevenant
709     Pumpkaboo
710     Gourgeist
711      Bergmite
712       Avalugg
713        Noibat
714       Noivern
715       Xerneas
716       Yveltal
717       Zygarde
718       Diancie
719         Hoopa
720     Volcanion
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[30]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[30]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0        50.12
1        54.10
2        54.65
3        52.38
4        52.95
5        53.90
6        53.02
7        50.95
8        51.13
9        50.07
10       50.70
11       49.95
12       50.74
13       51.10
14       51.10
15       52.61
16       53.70
17       55.69
18       55.94
19       56.93
20       58.69
21       59.62
22       58.86
23       59.13
24       60.35
25       59.86
26       59.07
27       63.37
28       65.47
29       64.74
         ...  
2982    675.22
2983    668.26
2984    680.04
2985    684.11
2986    692.10
2987    699.21
2988    694.49
2989    697.77
2990    695.36
2991    705.63
2992    715.09
2993    720.64
2994    716.98
2995    720.95
2996    719.85
2997    733.78
2998    736.96
2999    741.19
3000    738.63
3001    742.74
3002    739.77
3003    738.42
3004    741.77
3005    745.91
3006    768.79
3007    772.88
3008    771.07
3009    773.18
3010    771.61
3011    782.22
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-.head()-and-.tail()-Methods">The <code>.head()</code> and <code>.tail()</code> Methods<a class="anchor-link" href="#The-.head()-and-.tail()-Methods">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[31]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[36]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[36]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    Bulbasaur
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[40]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">tail</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[40]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3011    782.22
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Python-Built-In-Functions">Python Built-In Functions<a class="anchor-link" href="#Python-Built-In-Functions">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[54]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[56]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">len</span><span class="p">(</span><span class="n">pokemon</span><span class="p">)</span>
<span class="nb">len</span><span class="p">(</span><span class="n">google</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[56]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3012</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[57]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">type</span><span class="p">(</span><span class="n">pokemon</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[57]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>pandas.core.series.Series</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[58]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">dir</span><span class="p">(</span><span class="n">pokemon</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[58]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>[&#39;T&#39;,
 &#39;_AXIS_ALIASES&#39;,
 &#39;_AXIS_IALIASES&#39;,
 &#39;_AXIS_LEN&#39;,
 &#39;_AXIS_NAMES&#39;,
 &#39;_AXIS_NUMBERS&#39;,
 &#39;_AXIS_ORDERS&#39;,
 &#39;_AXIS_REVERSED&#39;,
 &#39;_AXIS_SLICEMAP&#39;,
 &#39;__abs__&#39;,
 &#39;__add__&#39;,
 &#39;__and__&#39;,
 &#39;__array__&#39;,
 &#39;__array_prepare__&#39;,
 &#39;__array_priority__&#39;,
 &#39;__array_wrap__&#39;,
 &#39;__bool__&#39;,
 &#39;__bytes__&#39;,
 &#39;__class__&#39;,
 &#39;__contains__&#39;,
 &#39;__delattr__&#39;,
 &#39;__delitem__&#39;,
 &#39;__dict__&#39;,
 &#39;__dir__&#39;,
 &#39;__div__&#39;,
 &#39;__doc__&#39;,
 &#39;__eq__&#39;,
 &#39;__finalize__&#39;,
 &#39;__float__&#39;,
 &#39;__floordiv__&#39;,
 &#39;__format__&#39;,
 &#39;__ge__&#39;,
 &#39;__getattr__&#39;,
 &#39;__getattribute__&#39;,
 &#39;__getitem__&#39;,
 &#39;__getstate__&#39;,
 &#39;__gt__&#39;,
 &#39;__hash__&#39;,
 &#39;__iadd__&#39;,
 &#39;__imul__&#39;,
 &#39;__init__&#39;,
 &#39;__int__&#39;,
 &#39;__invert__&#39;,
 &#39;__ipow__&#39;,
 &#39;__isub__&#39;,
 &#39;__iter__&#39;,
 &#39;__itruediv__&#39;,
 &#39;__le__&#39;,
 &#39;__len__&#39;,
 &#39;__long__&#39;,
 &#39;__lt__&#39;,
 &#39;__mod__&#39;,
 &#39;__module__&#39;,
 &#39;__mul__&#39;,
 &#39;__ne__&#39;,
 &#39;__neg__&#39;,
 &#39;__new__&#39;,
 &#39;__nonzero__&#39;,
 &#39;__or__&#39;,
 &#39;__pow__&#39;,
 &#39;__radd__&#39;,
 &#39;__rand__&#39;,
 &#39;__rdiv__&#39;,
 &#39;__reduce__&#39;,
 &#39;__reduce_ex__&#39;,
 &#39;__repr__&#39;,
 &#39;__rfloordiv__&#39;,
 &#39;__rmod__&#39;,
 &#39;__rmul__&#39;,
 &#39;__ror__&#39;,
 &#39;__round__&#39;,
 &#39;__rpow__&#39;,
 &#39;__rsub__&#39;,
 &#39;__rtruediv__&#39;,
 &#39;__rxor__&#39;,
 &#39;__setattr__&#39;,
 &#39;__setitem__&#39;,
 &#39;__setstate__&#39;,
 &#39;__sizeof__&#39;,
 &#39;__str__&#39;,
 &#39;__sub__&#39;,
 &#39;__subclasshook__&#39;,
 &#39;__truediv__&#39;,
 &#39;__unicode__&#39;,
 &#39;__weakref__&#39;,
 &#39;__xor__&#39;,
 &#39;_accessors&#39;,
 &#39;_add_numeric_operations&#39;,
 &#39;_add_series_only_operations&#39;,
 &#39;_add_series_or_dataframe_operations&#39;,
 &#39;_agg_by_level&#39;,
 &#39;_align_frame&#39;,
 &#39;_align_series&#39;,
 &#39;_allow_index_ops&#39;,
 &#39;_at&#39;,
 &#39;_binop&#39;,
 &#39;_box_item_values&#39;,
 &#39;_can_hold_na&#39;,
 &#39;_check_inplace_setting&#39;,
 &#39;_check_is_chained_assignment_possible&#39;,
 &#39;_check_percentile&#39;,
 &#39;_check_setitem_copy&#39;,
 &#39;_clear_item_cache&#39;,
 &#39;_consolidate_inplace&#39;,
 &#39;_construct_axes_dict&#39;,
 &#39;_construct_axes_dict_for_slice&#39;,
 &#39;_construct_axes_dict_from&#39;,
 &#39;_construct_axes_from_arguments&#39;,
 &#39;_constructor&#39;,
 &#39;_constructor_expanddim&#39;,
 &#39;_constructor_sliced&#39;,
 &#39;_convert&#39;,
 &#39;_create_indexer&#39;,
 &#39;_dir_additions&#39;,
 &#39;_dir_deletions&#39;,
 &#39;_expand_axes&#39;,
 &#39;_from_axes&#39;,
 &#39;_get_axis&#39;,
 &#39;_get_axis_name&#39;,
 &#39;_get_axis_number&#39;,
 &#39;_get_axis_resolvers&#39;,
 &#39;_get_block_manager_axis&#39;,
 &#39;_get_bool_data&#39;,
 &#39;_get_cacher&#39;,
 &#39;_get_index_resolvers&#39;,
 &#39;_get_item_cache&#39;,
 &#39;_get_numeric_data&#39;,
 &#39;_get_repr&#39;,
 &#39;_get_values&#39;,
 &#39;_get_values_tuple&#39;,
 &#39;_get_with&#39;,
 &#39;_iat&#39;,
 &#39;_iget_item_cache&#39;,
 &#39;_iloc&#39;,
 &#39;_index&#39;,
 &#39;_indexed_same&#39;,
 &#39;_info_axis&#39;,
 &#39;_info_axis_name&#39;,
 &#39;_info_axis_number&#39;,
 &#39;_init_mgr&#39;,
 &#39;_internal_names&#39;,
 &#39;_internal_names_set&#39;,
 &#39;_is_cached&#39;,
 &#39;_is_datelike_mixed_type&#39;,
 &#39;_is_mixed_type&#39;,
 &#39;_is_numeric_mixed_type&#39;,
 &#39;_is_view&#39;,
 &#39;_ix&#39;,
 &#39;_ixs&#39;,
 &#39;_loc&#39;,
 &#39;_make_cat_accessor&#39;,
 &#39;_make_dt_accessor&#39;,
 &#39;_make_str_accessor&#39;,
 &#39;_maybe_cache_changed&#39;,
 &#39;_maybe_update_cacher&#39;,
 &#39;_metadata&#39;,
 &#39;_needs_reindex_multi&#39;,
 &#39;_protect_consolidate&#39;,
 &#39;_reduce&#39;,
 &#39;_reindex_axes&#39;,
 &#39;_reindex_axis&#39;,
 &#39;_reindex_indexer&#39;,
 &#39;_reindex_multi&#39;,
 &#39;_reindex_with_indexers&#39;,
 &#39;_reset_cache&#39;,
 &#39;_reset_cacher&#39;,
 &#39;_set_as_cached&#39;,
 &#39;_set_axis&#39;,
 &#39;_set_axis_name&#39;,
 &#39;_set_is_copy&#39;,
 &#39;_set_item&#39;,
 &#39;_set_labels&#39;,
 &#39;_set_name&#39;,
 &#39;_set_subtyp&#39;,
 &#39;_set_values&#39;,
 &#39;_set_with&#39;,
 &#39;_set_with_engine&#39;,
 &#39;_setup_axes&#39;,
 &#39;_slice&#39;,
 &#39;_stat_axis&#39;,
 &#39;_stat_axis_name&#39;,
 &#39;_stat_axis_number&#39;,
 &#39;_typ&#39;,
 &#39;_unpickle_series_compat&#39;,
 &#39;_update_inplace&#39;,
 &#39;_validate_dtype&#39;,
 &#39;_values&#39;,
 &#39;_xs&#39;,
 &#39;abs&#39;,
 &#39;add&#39;,
 &#39;add_prefix&#39;,
 &#39;add_suffix&#39;,
 &#39;align&#39;,
 &#39;all&#39;,
 &#39;any&#39;,
 &#39;append&#39;,
 &#39;apply&#39;,
 &#39;argmax&#39;,
 &#39;argmin&#39;,
 &#39;argsort&#39;,
 &#39;as_blocks&#39;,
 &#39;as_matrix&#39;,
 &#39;asfreq&#39;,
 &#39;asobject&#39;,
 &#39;asof&#39;,
 &#39;astype&#39;,
 &#39;at&#39;,
 &#39;at_time&#39;,
 &#39;autocorr&#39;,
 &#39;axes&#39;,
 &#39;base&#39;,
 &#39;between&#39;,
 &#39;between_time&#39;,
 &#39;bfill&#39;,
 &#39;blocks&#39;,
 &#39;bool&#39;,
 &#39;clip&#39;,
 &#39;clip_lower&#39;,
 &#39;clip_upper&#39;,
 &#39;combine&#39;,
 &#39;combine_first&#39;,
 &#39;compound&#39;,
 &#39;compress&#39;,
 &#39;consolidate&#39;,
 &#39;convert_objects&#39;,
 &#39;copy&#39;,
 &#39;corr&#39;,
 &#39;count&#39;,
 &#39;cov&#39;,
 &#39;cummax&#39;,
 &#39;cummin&#39;,
 &#39;cumprod&#39;,
 &#39;cumsum&#39;,
 &#39;data&#39;,
 &#39;describe&#39;,
 &#39;diff&#39;,
 &#39;div&#39;,
 &#39;divide&#39;,
 &#39;dot&#39;,
 &#39;drop&#39;,
 &#39;drop_duplicates&#39;,
 &#39;dropna&#39;,
 &#39;dtype&#39;,
 &#39;dtypes&#39;,
 &#39;duplicated&#39;,
 &#39;empty&#39;,
 &#39;eq&#39;,
 &#39;equals&#39;,
 &#39;ewm&#39;,
 &#39;expanding&#39;,
 &#39;factorize&#39;,
 &#39;ffill&#39;,
 &#39;fillna&#39;,
 &#39;filter&#39;,
 &#39;first&#39;,
 &#39;first_valid_index&#39;,
 &#39;flags&#39;,
 &#39;floordiv&#39;,
 &#39;from_array&#39;,
 &#39;from_csv&#39;,
 &#39;ftype&#39;,
 &#39;ftypes&#39;,
 &#39;ge&#39;,
 &#39;get&#39;,
 &#39;get_dtype_counts&#39;,
 &#39;get_ftype_counts&#39;,
 &#39;get_value&#39;,
 &#39;get_values&#39;,
 &#39;groupby&#39;,
 &#39;gt&#39;,
 &#39;hasnans&#39;,
 &#39;head&#39;,
 &#39;hist&#39;,
 &#39;iat&#39;,
 &#39;idxmax&#39;,
 &#39;idxmin&#39;,
 &#39;iget&#39;,
 &#39;iget_value&#39;,
 &#39;iloc&#39;,
 &#39;imag&#39;,
 &#39;index&#39;,
 &#39;interpolate&#39;,
 &#39;irow&#39;,
 &#39;is_copy&#39;,
 &#39;is_time_series&#39;,
 &#39;is_unique&#39;,
 &#39;isin&#39;,
 &#39;isnull&#39;,
 &#39;item&#39;,
 &#39;items&#39;,
 &#39;itemsize&#39;,
 &#39;iteritems&#39;,
 &#39;iterkv&#39;,
 &#39;ix&#39;,
 &#39;keys&#39;,
 &#39;kurt&#39;,
 &#39;kurtosis&#39;,
 &#39;last&#39;,
 &#39;last_valid_index&#39;,
 &#39;le&#39;,
 &#39;loc&#39;,
 &#39;lt&#39;,
 &#39;mad&#39;,
 &#39;map&#39;,
 &#39;mask&#39;,
 &#39;max&#39;,
 &#39;mean&#39;,
 &#39;median&#39;,
 &#39;memory_usage&#39;,
 &#39;min&#39;,
 &#39;mod&#39;,
 &#39;mode&#39;,
 &#39;mul&#39;,
 &#39;multiply&#39;,
 &#39;name&#39;,
 &#39;nbytes&#39;,
 &#39;ndim&#39;,
 &#39;ne&#39;,
 &#39;nlargest&#39;,
 &#39;nonzero&#39;,
 &#39;notnull&#39;,
 &#39;nsmallest&#39;,
 &#39;nunique&#39;,
 &#39;order&#39;,
 &#39;pct_change&#39;,
 &#39;pipe&#39;,
 &#39;plot&#39;,
 &#39;pop&#39;,
 &#39;pow&#39;,
 &#39;prod&#39;,
 &#39;product&#39;,
 &#39;ptp&#39;,
 &#39;put&#39;,
 &#39;quantile&#39;,
 &#39;radd&#39;,
 &#39;rank&#39;,
 &#39;ravel&#39;,
 &#39;rdiv&#39;,
 &#39;real&#39;,
 &#39;reindex&#39;,
 &#39;reindex_axis&#39;,
 &#39;reindex_like&#39;,
 &#39;rename&#39;,
 &#39;rename_axis&#39;,
 &#39;reorder_levels&#39;,
 &#39;repeat&#39;,
 &#39;replace&#39;,
 &#39;resample&#39;,
 &#39;reset_index&#39;,
 &#39;reshape&#39;,
 &#39;rfloordiv&#39;,
 &#39;rmod&#39;,
 &#39;rmul&#39;,
 &#39;rolling&#39;,
 &#39;round&#39;,
 &#39;rpow&#39;,
 &#39;rsub&#39;,
 &#39;rtruediv&#39;,
 &#39;sample&#39;,
 &#39;searchsorted&#39;,
 &#39;select&#39;,
 &#39;sem&#39;,
 &#39;set_axis&#39;,
 &#39;set_value&#39;,
 &#39;shape&#39;,
 &#39;shift&#39;,
 &#39;size&#39;,
 &#39;skew&#39;,
 &#39;slice_shift&#39;,
 &#39;sort&#39;,
 &#39;sort_index&#39;,
 &#39;sort_values&#39;,
 &#39;sortlevel&#39;,
 &#39;squeeze&#39;,
 &#39;std&#39;,
 &#39;str&#39;,
 &#39;strides&#39;,
 &#39;sub&#39;,
 &#39;subtract&#39;,
 &#39;sum&#39;,
 &#39;swapaxes&#39;,
 &#39;swaplevel&#39;,
 &#39;tail&#39;,
 &#39;take&#39;,
 &#39;to_clipboard&#39;,
 &#39;to_csv&#39;,
 &#39;to_dense&#39;,
 &#39;to_dict&#39;,
 &#39;to_frame&#39;,
 &#39;to_hdf&#39;,
 &#39;to_json&#39;,
 &#39;to_msgpack&#39;,
 &#39;to_period&#39;,
 &#39;to_pickle&#39;,
 &#39;to_sparse&#39;,
 &#39;to_sql&#39;,
 &#39;to_string&#39;,
 &#39;to_timestamp&#39;,
 &#39;to_xarray&#39;,
 &#39;tolist&#39;,
 &#39;transpose&#39;,
 &#39;truediv&#39;,
 &#39;truncate&#39;,
 &#39;tshift&#39;,
 &#39;tz_convert&#39;,
 &#39;tz_localize&#39;,
 &#39;unique&#39;,
 &#39;unstack&#39;,
 &#39;update&#39;,
 &#39;valid&#39;,
 &#39;value_counts&#39;,
 &#39;values&#39;,
 &#39;var&#39;,
 &#39;view&#39;,
 &#39;where&#39;,
 &#39;xs&#39;]</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[60]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">sorted</span><span class="p">(</span><span class="n">pokemon</span><span class="p">)</span>
<span class="nb">sorted</span><span class="p">(</span><span class="n">google</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[60]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>[49.950000000000003,
 50.07,
 50.119999999999997,
 50.700000000000003,
 50.740000000000002,
 50.950000000000003,
 51.100000000000001,
 51.100000000000001,
 51.130000000000003,
 52.380000000000003,
 52.609999999999999,
 52.950000000000003,
 53.020000000000003,
 53.700000000000003,
 53.899999999999999,
 54.100000000000001,
 54.649999999999999,
 55.689999999999998,
 55.939999999999998,
 56.93,
 58.689999999999998,
 58.859999999999999,
 59.07,
 59.130000000000003,
 59.619999999999997,
 59.859999999999999,
 60.350000000000001,
 63.369999999999997,
 64.739999999999995,
 65.469999999999999,
 66.219999999999999,
 67.459999999999994,
 67.560000000000002,
 68.469999999999999,
 68.629999999999995,
 68.799999999999997,
 69.120000000000005,
 69.359999999999999,
 70.170000000000002,
 70.379999999999995,
 70.930000000000007,
 71.980000000000004,
 73.900000000000006,
 74.510000000000005,
 74.620000000000005,
 82.469999999999999,
 83.680000000000007,
 83.689999999999998,
 83.849999999999994,
 84.269999999999996,
 84.590000000000003,
 84.620000000000005,
 84.909999999999997,
 85.140000000000001,
 85.629999999999995,
 85.739999999999995,
 86.129999999999995,
 86.159999999999997,
 86.189999999999998,
 86.189999999999998,
 86.629999999999995,
 87.290000000000006,
 87.409999999999997,
 87.709999999999994,
 88.060000000000002,
 88.150000000000006,
 88.469999999999999,
 88.810000000000002,
 89.209999999999994,
 89.219999999999999,
 89.260000000000005,
 89.400000000000006,
 89.540000000000006,
 89.560000000000002,
 89.609999999999999,
 89.609999999999999,
 89.700000000000003,
 89.799999999999997,
 89.890000000000001,
 89.900000000000006,
 89.930000000000007,
 89.930000000000007,
 89.950000000000003,
 90.109999999999999,
 90.129999999999995,
 90.159999999999997,
 90.269999999999996,
 90.349999999999994,
 90.430000000000007,
 90.579999999999998,
 90.620000000000005,
 90.810000000000002,
 90.900000000000006,
 90.909999999999997,
 91.420000000000002,
 91.780000000000001,
 92.260000000000005,
 92.340000000000003,
 92.409999999999997,
 92.420000000000002,
 92.5,
 92.510000000000005,
 92.549999999999997,
 92.840000000000003,
 92.859999999999999,
 92.890000000000001,
 92.939999999999998,
 93.060000000000002,
 93.390000000000001,
 93.409999999999997,
 93.609999999999999,
 93.609999999999999,
 93.859999999999999,
 93.900000000000006,
 93.900000000000006,
 93.950000000000003,
 94.049999999999997,
 94.180000000000007,
 94.189999999999998,
 94.310000000000002,
 94.349999999999994,
 94.519999999999996,
 94.530000000000001,
 95.069999999999993,
 95.219999999999999,
 95.590000000000003,
 95.599999999999994,
 95.629999999999995,
 95.689999999999998,
 95.739999999999995,
 95.849999999999994,
 95.859999999999999,
 95.930000000000007,
 96.280000000000001,
 96.299999999999997,
 96.349999999999994,
 96.370000000000005,
 96.400000000000006,
 96.519999999999996,
 96.549999999999997,
 96.659999999999997,
 96.670000000000002,
 96.780000000000001,
 96.829999999999998,
 96.859999999999999,
 96.879999999999995,
 96.879999999999995,
 97.150000000000006,
 97.340000000000003,
 97.430000000000007,
 97.519999999999996,
 97.569999999999993,
 97.590000000000003,
 97.709999999999994,
 97.920000000000002,
 97.920000000000002,
 98.549999999999997,
 98.700000000000003,
 98.849999999999994,
 98.879999999999995,
 98.950000000000003,
 99.109999999999999,
 99.219999999999999,
 99.890000000000001,
 101.25,
 101.84999999999999,
 102.01000000000001,
 102.08,
 102.88,
 105.31999999999999,
 107.8,
 109.27,
 109.62,
 109.78,
 109.89,
 111.03,
 111.65000000000001,
 112.90000000000001,
 112.98,
 113.38,
 113.79000000000001,
 113.90000000000001,
 114.14,
 114.25,
 114.51000000000001,
 115.41,
 115.53,
 116.45,
 119.45999999999999,
 119.47,
 120.68000000000001,
 127.59999999999999,
 127.87,
 128.59,
 129.47,
 129.65000000000001,
 130.27000000000001,
 131.08000000000001,
 132.86000000000001,
 132.87,
 136.87,
 137.03,
 137.25999999999999,
 137.41999999999999,
 138.5,
 138.58000000000001,
 139.03999999999999,
 139.58000000000001,
 139.63999999999999,
 139.65000000000001,
 139.86000000000001,
 139.86000000000001,
 139.94999999999999,
 139.99000000000001,
 140.0,
 140.88,
 141.11000000000001,
 141.13999999999999,
 141.15000000000001,
 141.22999999999999,
 141.22999999999999,
 141.65000000000001,
 141.84999999999999,
 141.86000000000001,
 141.88,
 142.41,
 142.68000000000001,
 142.69999999999999,
 142.86000000000001,
 142.97999999999999,
 143.00999999999999,
 143.21000000000001,
 143.41,
 143.49000000000001,
 143.74000000000001,
 143.78,
 143.81,
 143.86000000000001,
 144.08000000000001,
 144.08000000000001,
 144.50999999999999,
 144.71000000000001,
 144.72,
 145.30000000000001,
 145.31999999999999,
 145.34999999999999,
 145.47999999999999,
 145.47999999999999,
 145.62,
 145.63999999999999,
 145.66,
 145.75,
 145.90000000000001,
 146.03,
 146.21000000000001,
 146.33000000000001,
 146.41,
 146.53,
 146.59999999999999,
 146.93000000000001,
 147.28999999999999,
 147.55000000000001,
 147.62,
 147.71000000000001,
 147.78,
 147.90000000000001,
 147.91999999999999,
 147.97,
 148.31999999999999,
 148.41,
 148.47999999999999,
 148.5,
 148.56,
 148.56,
 148.56999999999999,
 148.72,
 148.86000000000001,
 149.28,
 149.34999999999999,
 149.40000000000001,
 149.44999999999999,
 149.62,
 149.69,
 149.91,
 149.94999999999999,
 149.96000000000001,
 150.03,
 150.28999999999999,
 150.33000000000001,
 150.33000000000001,
 150.44,
 150.84999999999999,
 150.90000000000001,
 151.05000000000001,
 151.16,
 151.31999999999999,
 151.34999999999999,
 151.38999999999999,
 151.40000000000001,
 151.44999999999999,
 151.49000000000001,
 151.74000000000001,
 151.90000000000001,
 152.34999999999999,
 152.66999999999999,
 152.83000000000001,
 152.84999999999999,
 152.90000000000001,
 153.09999999999999,
 153.66999999999999,
 153.80000000000001,
 153.93000000000001,
 154.13,
 154.19999999999999,
 154.25999999999999,
 154.66,
 154.72,
 154.80000000000001,
 154.84999999999999,
 154.93000000000001,
 154.97999999999999,
 155.16999999999999,
 155.18000000000001,
 155.19999999999999,
 155.34,
 155.53,
 155.56999999999999,
 155.68000000000001,
 155.78999999999999,
 155.84,
 155.88,
 156.19,
 156.22,
 156.34,
 156.81,
 156.81,
 156.97999999999999,
 157.0,
 157.38,
 157.46000000000001,
 157.52000000000001,
 157.72,
 158.06999999999999,
 158.80000000000001,
 159.18000000000001,
 159.22999999999999,
 159.30000000000001,
 159.69,
 160.5,
 160.84,
 161.59999999999999,
 161.77000000000001,
 162.05000000000001,
 162.19,
 162.43000000000001,
 162.47999999999999,
 162.58000000000001,
 163.41999999999999,
 163.86000000000001,
 164.33000000000001,
 164.58000000000001,
 164.81,
 164.86000000000001,
 164.91,
 165.40000000000001,
 165.44,
 165.56999999999999,
 165.83000000000001,
 166.38,
 166.86000000000001,
 167.5,
 168.36000000000001,
 168.41999999999999,
 168.58000000000001,
 168.83000000000001,
 168.88999999999999,
 169.09999999999999,
 169.22,
 169.41999999999999,
 169.47999999999999,
 169.72999999999999,
 169.78,
 169.78999999999999,
 169.94,
 170.05000000000001,
 170.11000000000001,
 170.65000000000001,
 170.77000000000001,
 170.94999999999999,
 171.02000000000001,
 171.15000000000001,
 171.16,
 171.16999999999999,
 171.33000000000001,
 171.33000000000001,
 171.49000000000001,
 171.49000000000001,
 171.86000000000001,
 172.08000000000001,
 172.55000000000001,
 172.68000000000001,
 172.83000000000001,
 173.05000000000001,
 173.06999999999999,
 173.28,
 173.41,
 173.68000000000001,
 173.86000000000001,
 173.91999999999999,
 174.13,
 174.15000000000001,
 174.16,
 175.40000000000001,
 175.97999999999999,
 176.33000000000001,
 176.34999999999999,
 176.38,
 176.47,
 176.68000000000001,
 176.75999999999999,
 176.87,
 177.53999999999999,
 177.66,
 178.66,
 178.81999999999999,
 178.84,
 178.91,
 179.08000000000001,
 179.15000000000001,
 179.21000000000001,
 179.5,
 179.66999999999999,
 180.81999999999999,
 181.06999999999999,
 181.12,
 181.13,
 181.16999999999999,
 181.19,
 181.34,
 182.03999999999999,
 182.22,
 182.56,
 182.72,
 183.05000000000001,
 183.11000000000001,
 183.28999999999999,
 183.43000000000001,
 183.78,
 183.87,
 183.94,
 184.06999999999999,
 184.19,
 184.19,
 184.27000000000001,
 184.36000000000001,
 184.53,
 184.66,
 184.71000000000001,
 184.81999999999999,
 185.28999999999999,
 185.31,
 185.41999999999999,
 185.44999999999999,
 185.46000000000001,
 185.72,
 185.78,
 185.88,
 186.06,
 186.08000000000001,
 186.44,
 186.53,
 186.68000000000001,
 186.74000000000001,
 186.88,
 186.91,
 187.03,
 187.06,
 187.50999999999999,
 187.56999999999999,
 187.59999999999999,
 187.91,
 188.03999999999999,
 188.28,
 188.41,
 188.46000000000001,
 188.50999999999999,
 188.74000000000001,
 188.78999999999999,
 188.84999999999999,
 188.87,
 188.90000000000001,
 188.96000000000001,
 189.06,
 189.08000000000001,
 189.11000000000001,
 189.19999999999999,
 189.28999999999999,
 189.38999999999999,
 189.46000000000001,
 189.47,
 189.5,
 189.53,
 189.56,
 189.65000000000001,
 189.88,
 190.18000000000001,
 190.28,
 190.28999999999999,
 190.31,
 190.31,
 190.31999999999999,
 190.43000000000001,
 190.47999999999999,
 190.53999999999999,
 190.58000000000001,
 190.59,
 191.00999999999999,
 191.12,
 191.30000000000001,
 191.49000000000001,
 191.66,
 191.74000000000001,
 191.84999999999999,
 191.99000000000001,
 192.0,
 192.15000000000001,
 192.36000000000001,
 192.56,
 192.71000000000001,
 192.78,
 192.78,
 193.06,
 193.06999999999999,
 193.09,
 193.11000000000001,
 193.25999999999999,
 193.31,
 193.37,
 193.38999999999999,
 193.56,
 193.66999999999999,
 193.87,
 193.88,
 194.03,
 194.18000000000001,
 194.49000000000001,
 194.55000000000001,
 194.58000000000001,
 194.66,
 194.75999999999999,
 194.80000000000001,
 194.80000000000001,
 194.80000000000001,
 194.86000000000001,
 194.99000000000001,
 195.0,
 195.02000000000001,
 195.05000000000001,
 195.15000000000001,
 195.25,
 195.30000000000001,
 195.34999999999999,
 195.53999999999999,
 195.75,
 195.91999999999999,
 196.19999999999999,
 196.44999999999999,
 196.55000000000001,
 196.65000000000001,
 196.88999999999999,
 196.94999999999999,
 197.18000000000001,
 197.19,
 197.19999999999999,
 197.28999999999999,
 197.31999999999999,
 197.78999999999999,
 197.81999999999999,
 198.05000000000001,
 198.11000000000001,
 198.12,
 198.22,
 198.28999999999999,
 198.30000000000001,
 198.38999999999999,
 198.88,
 199.24000000000001,
 199.25,
 199.30000000000001,
 199.31,
 199.53,
 199.78,
 199.90000000000001,
 200.06,
 200.52000000000001,
 200.69,
 200.75,
 200.78999999999999,
 200.86000000000001,
 200.88,
 200.96000000000001,
 201.03999999999999,
 201.25999999999999,
 201.28999999999999,
 201.28999999999999,
 201.31999999999999,
 201.52000000000001,
 201.53,
 201.55000000000001,
 201.56999999999999,
 201.59,
 201.69,
 201.69999999999999,
 201.78999999999999,
 201.78999999999999,
 201.81999999999999,
 201.91,
 201.91,
 201.91999999999999,
 201.97,
 201.97999999999999,
 202.06999999999999,
 202.22999999999999,
 202.25,
 202.58000000000001,
 202.63999999999999,
 202.72,
 202.84999999999999,
 202.88,
 203.08000000000001,
 203.21000000000001,
 203.22,
 203.22999999999999,
 203.46000000000001,
 203.47,
 203.74000000000001,
 203.78999999999999,
 203.78999999999999,
 204.03999999999999,
 204.19999999999999,
 204.21000000000001,
 204.27000000000001,
 204.40000000000001,
 204.44,
 204.47999999999999,
 204.59999999999999,
 204.63,
 204.74000000000001,
 204.99000000000001,
 204.99000000000001,
 205.03999999999999,
 205.12,
 205.38,
 205.65000000000001,
 205.69999999999999,
 206.09999999999999,
 206.59999999999999,
 206.81999999999999,
 206.84,
 206.87,
 206.99000000000001,
 207.03999999999999,
 207.13999999999999,
 207.22,
 207.28999999999999,
 207.37,
 207.63999999999999,
 207.68000000000001,
 207.78999999999999,
 207.97999999999999,
 208.03,
 208.18000000000001,
 208.41,
 208.41999999999999,
 208.53999999999999,
 208.63999999999999,
 208.69999999999999,
 208.75999999999999,
 208.88999999999999,
 209.12,
 209.27000000000001,
 209.28999999999999,
 209.44,
 209.46000000000001,
 209.72999999999999,
 209.75999999999999,
 209.80000000000001,
 209.83000000000001,
 209.86000000000001,
 210.00999999999999,
 210.03999999999999,
 210.11000000000001,
 210.52000000000001,
 210.58000000000001,
 210.66,
 211.05000000000001,
 211.22,
 211.38,
 211.38999999999999,
 211.53,
 211.86000000000001,
 211.94,
 212.06999999999999,
 212.09,
 212.11000000000001,
 212.13,
 212.21000000000001,
 212.44999999999999,
 212.77000000000001,
 212.81999999999999,
 212.94999999999999,
 213.03999999999999,
 213.06999999999999,
 213.11000000000001,
 213.13,
 213.19999999999999,
 213.37,
 213.44,
 213.50999999999999,
 213.53999999999999,
 213.63,
 213.74000000000001,
 213.99000000000001,
 214.09999999999999,
 214.28999999999999,
 214.28999999999999,
 214.41999999999999,
 214.66,
 214.84999999999999,
 214.86000000000001,
 214.87,
 214.91,
 215.25,
 215.30000000000001,
 215.61000000000001,
 215.78,
 215.80000000000001,
 216.08000000000001,
 216.11000000000001,
 216.13,
 216.28,
 216.46000000000001,
 216.53,
 216.56,
 216.66,
 216.71000000000001,
 216.91999999999999,
 217.34,
 217.40000000000001,
 217.59,
 217.81999999999999,
 217.90000000000001,
 218.0,
 218.06,
 218.33000000000001,
 218.44999999999999,
 218.61000000000001,
 218.74000000000001,
 218.81999999999999,
 218.87,
 219.12,
 219.16999999999999,
 219.31999999999999,
 219.36000000000001,
 219.53,
 219.58000000000001,
 219.69999999999999,
 219.71000000000001,
 219.87,
 219.91999999999999,
 220.00999999999999,
 220.03,
 220.19999999999999,
 220.25,
 221.08000000000001,
 221.24000000000001,
 221.28,
 221.28999999999999,
 221.28999999999999,
 221.30000000000001,
 221.75999999999999,
 221.81999999999999,
 221.90000000000001,
 221.94,
 222.08000000000001,
 222.18000000000001,
 222.22,
 222.22999999999999,
 222.25,
 222.40000000000001,
 222.41999999999999,
 222.41999999999999,
 222.59999999999999,
 222.87,
 223.13999999999999,
 223.19999999999999,
 223.38999999999999,
 223.63,
 223.78,
 223.88999999999999,
 224.16,
 224.34999999999999,
 224.5,
 224.55000000000001,
 224.78,
 224.87,
 224.90000000000001,
 224.94999999999999,
 225.16,
 225.25999999999999,
 225.34,
 225.38999999999999,
 225.47,
 225.59999999999999,
 225.88,
 226.12,
 226.25,
 226.28,
 226.63999999999999,
 226.74000000000001,
 226.90000000000001,
 227.08000000000001,
 227.13,
 227.15000000000001,
 227.28999999999999,
 227.33000000000001,
 227.56,
 227.59,
 227.65000000000001,
 227.87,
 228.05000000000001,
 228.05000000000001,
 228.08000000000001,
 228.28,
 228.31999999999999,
 228.5,
 228.53,
 228.53999999999999,
 228.55000000000001,
 228.77000000000001,
 228.84999999999999,
 228.87,
 228.91999999999999,
 229.03999999999999,
 229.06,
 229.08000000000001,
 229.19,
 229.31999999999999,
 229.56999999999999,
 229.61000000000001,
 229.77000000000001,
 229.94,
 229.97,
 230.00999999999999,
 230.05000000000001,
 230.22999999999999,
 230.41999999999999,
 230.5,
 230.5,
 230.59999999999999,
 230.66,
 230.68000000000001,
 230.71000000000001,
 230.71000000000001,
 230.78,
 230.78999999999999,
 230.91,
 231.05000000000001,
 231.16999999999999,
 231.22,
 231.27000000000001,
 231.36000000000001,
 231.41,
 231.58000000000001,
 231.58000000000001,
 231.75,
 231.80000000000001,
 231.86000000000001,
 231.86000000000001,
 231.97,
 231.97,
 232.03,
 232.13999999999999,
 232.22999999999999,
 232.27000000000001,
 232.38999999999999,
 232.38999999999999,
 232.59999999999999,
 232.62,
 232.62,
 232.66,
 232.72999999999999,
 232.80000000000001,
 232.86000000000001,
 232.88999999999999,
 232.91,
 233.02000000000001,
 233.13999999999999,
 233.16999999999999,
 233.22,
 233.31999999999999,
 233.34999999999999,
 233.40000000000001,
 233.46000000000001,
 233.50999999999999,
 233.52000000000001,
 233.56,
 233.66999999999999,
 233.69999999999999,
 233.75,
 233.77000000000001,
 233.78,
 233.87,
 234.06,
 234.08000000000001,
 234.13,
 234.16999999999999,
 234.27000000000001,
 234.30000000000001,
 234.38999999999999,
 234.65000000000001,
 234.72,
 234.74000000000001,
 234.77000000000001,
 234.91,
 234.91999999999999,
 235.05000000000001,
 235.06,
 235.06999999999999,
 235.22999999999999,
 235.24000000000001,
 235.27000000000001,
 235.28,
 235.31,
 235.31999999999999,
 235.34999999999999,
 235.44999999999999,
 235.44999999999999,
 235.5,
 235.52000000000001,
 235.58000000000001,
 235.59,
 235.66,
 235.78999999999999,
 235.80000000000001,
 235.81,
 235.83000000000001,
 236.05000000000001,
 236.06,
 236.06999999999999,
 236.08000000000001,
 236.09999999999999,
 236.16,
 236.19,
 236.38,
 236.41999999999999,
 236.53999999999999,
 236.63999999999999,
 236.65000000000001,
 236.75,
 236.77000000000001,
 236.84,
 236.90000000000001,
 236.93000000000001,
 237.19999999999999,
 237.25999999999999,
 237.27000000000001,
 237.31,
 237.31999999999999,
 237.36000000000001,
 237.46000000000001,
 237.5,
 237.56999999999999,
 237.68000000000001,
 237.69,
 237.69,
 237.69,
 237.77000000000001,
 237.83000000000001,
 237.84999999999999,
 237.96000000000001,
 238.05000000000001,
 238.16999999999999,
 238.24000000000001,
 238.30000000000001,
 238.31999999999999,
 238.31999999999999,
 238.34,
 238.50999999999999,
 238.53,
 238.53,
 238.75999999999999,
 239.25999999999999,
 239.27000000000001,
 239.28999999999999,
 239.30000000000001,
 239.31999999999999,
 239.69,
 239.87,
 239.91,
 ...]</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[61]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">list</span><span class="p">(</span><span class="n">pokemon</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[61]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>[&#39;Bulbasaur&#39;,
 &#39;Ivysaur&#39;,
 &#39;Venusaur&#39;,
 &#39;Charmander&#39;,
 &#39;Charmeleon&#39;,
 &#39;Charizard&#39;,
 &#39;Squirtle&#39;,
 &#39;Wartortle&#39;,
 &#39;Blastoise&#39;,
 &#39;Caterpie&#39;,
 &#39;Metapod&#39;,
 &#39;Butterfree&#39;,
 &#39;Weedle&#39;,
 &#39;Kakuna&#39;,
 &#39;Beedrill&#39;,
 &#39;Pidgey&#39;,
 &#39;Pidgeotto&#39;,
 &#39;Pidgeot&#39;,
 &#39;Rattata&#39;,
 &#39;Raticate&#39;,
 &#39;Spearow&#39;,
 &#39;Fearow&#39;,
 &#39;Ekans&#39;,
 &#39;Arbok&#39;,
 &#39;Pikachu&#39;,
 &#39;Raichu&#39;,
 &#39;Sandshrew&#39;,
 &#39;Sandslash&#39;,
 &#39;Nidoran&#39;,
 &#39;Nidorina&#39;,
 &#39;Nidoqueen&#39;,
 &#39;Nidoran♂&#39;,
 &#39;Nidorino&#39;,
 &#39;Nidoking&#39;,
 &#39;Clefairy&#39;,
 &#39;Clefable&#39;,
 &#39;Vulpix&#39;,
 &#39;Ninetales&#39;,
 &#39;Jigglypuff&#39;,
 &#39;Wigglytuff&#39;,
 &#39;Zubat&#39;,
 &#39;Golbat&#39;,
 &#39;Oddish&#39;,
 &#39;Gloom&#39;,
 &#39;Vileplume&#39;,
 &#39;Paras&#39;,
 &#39;Parasect&#39;,
 &#39;Venonat&#39;,
 &#39;Venomoth&#39;,
 &#39;Diglett&#39;,
 &#39;Dugtrio&#39;,
 &#39;Meowth&#39;,
 &#39;Persian&#39;,
 &#39;Psyduck&#39;,
 &#39;Golduck&#39;,
 &#39;Mankey&#39;,
 &#39;Primeape&#39;,
 &#39;Growlithe&#39;,
 &#39;Arcanine&#39;,
 &#39;Poliwag&#39;,
 &#39;Poliwhirl&#39;,
 &#39;Poliwrath&#39;,
 &#39;Abra&#39;,
 &#39;Kadabra&#39;,
 &#39;Alakazam&#39;,
 &#39;Machop&#39;,
 &#39;Machoke&#39;,
 &#39;Machamp&#39;,
 &#39;Bellsprout&#39;,
 &#39;Weepinbell&#39;,
 &#39;Victreebel&#39;,
 &#39;Tentacool&#39;,
 &#39;Tentacruel&#39;,
 &#39;Geodude&#39;,
 &#39;Graveler&#39;,
 &#39;Golem&#39;,
 &#39;Ponyta&#39;,
 &#39;Rapidash&#39;,
 &#39;Slowpoke&#39;,
 &#39;Slowbro&#39;,
 &#39;Magnemite&#39;,
 &#39;Magneton&#39;,
 &#34;Farfetch&#39;d&#34;,
 &#39;Doduo&#39;,
 &#39;Dodrio&#39;,
 &#39;Seel&#39;,
 &#39;Dewgong&#39;,
 &#39;Grimer&#39;,
 &#39;Muk&#39;,
 &#39;Shellder&#39;,
 &#39;Cloyster&#39;,
 &#39;Gastly&#39;,
 &#39;Haunter&#39;,
 &#39;Gengar&#39;,
 &#39;Onix&#39;,
 &#39;Drowzee&#39;,
 &#39;Hypno&#39;,
 &#39;Krabby&#39;,
 &#39;Kingler&#39;,
 &#39;Voltorb&#39;,
 &#39;Electrode&#39;,
 &#39;Exeggcute&#39;,
 &#39;Exeggutor&#39;,
 &#39;Cubone&#39;,
 &#39;Marowak&#39;,
 &#39;Hitmonlee&#39;,
 &#39;Hitmonchan&#39;,
 &#39;Lickitung&#39;,
 &#39;Koffing&#39;,
 &#39;Weezing&#39;,
 &#39;Rhyhorn&#39;,
 &#39;Rhydon&#39;,
 &#39;Chansey&#39;,
 &#39;Tangela&#39;,
 &#39;Kangaskhan&#39;,
 &#39;Horsea&#39;,
 &#39;Seadra&#39;,
 &#39;Goldeen&#39;,
 &#39;Seaking&#39;,
 &#39;Staryu&#39;,
 &#39;Starmie&#39;,
 &#39;Mr. Mime&#39;,
 &#39;Scyther&#39;,
 &#39;Jynx&#39;,
 &#39;Electabuzz&#39;,
 &#39;Magmar&#39;,
 &#39;Pinsir&#39;,
 &#39;Tauros&#39;,
 &#39;Magikarp&#39;,
 &#39;Gyarados&#39;,
 &#39;Lapras&#39;,
 &#39;Ditto&#39;,
 &#39;Eevee&#39;,
 &#39;Vaporeon&#39;,
 &#39;Jolteon&#39;,
 &#39;Flareon&#39;,
 &#39;Porygon&#39;,
 &#39;Omanyte&#39;,
 &#39;Omastar&#39;,
 &#39;Kabuto&#39;,
 &#39;Kabutops&#39;,
 &#39;Aerodactyl&#39;,
 &#39;Snorlax&#39;,
 &#39;Articuno&#39;,
 &#39;Zapdos&#39;,
 &#39;Moltres&#39;,
 &#39;Dratini&#39;,
 &#39;Dragonair&#39;,
 &#39;Dragonite&#39;,
 &#39;Mewtwo&#39;,
 &#39;Mew&#39;,
 &#39;Chikorita&#39;,
 &#39;Bayleef&#39;,
 &#39;Meganium&#39;,
 &#39;Cyndaquil&#39;,
 &#39;Quilava&#39;,
 &#39;Typhlosion&#39;,
 &#39;Totodile&#39;,
 &#39;Croconaw&#39;,
 &#39;Feraligatr&#39;,
 &#39;Sentret&#39;,
 &#39;Furret&#39;,
 &#39;Hoothoot&#39;,
 &#39;Noctowl&#39;,
 &#39;Ledyba&#39;,
 &#39;Ledian&#39;,
 &#39;Spinarak&#39;,
 &#39;Ariados&#39;,
 &#39;Crobat&#39;,
 &#39;Chinchou&#39;,
 &#39;Lanturn&#39;,
 &#39;Pichu&#39;,
 &#39;Cleffa&#39;,
 &#39;Igglybuff&#39;,
 &#39;Togepi&#39;,
 &#39;Togetic&#39;,
 &#39;Natu&#39;,
 &#39;Xatu&#39;,
 &#39;Mareep&#39;,
 &#39;Flaaffy&#39;,
 &#39;Ampharos&#39;,
 &#39;Bellossom&#39;,
 &#39;Marill&#39;,
 &#39;Azumarill&#39;,
 &#39;Sudowoodo&#39;,
 &#39;Politoed&#39;,
 &#39;Hoppip&#39;,
 &#39;Skiploom&#39;,
 &#39;Jumpluff&#39;,
 &#39;Aipom&#39;,
 &#39;Sunkern&#39;,
 &#39;Sunflora&#39;,
 &#39;Yanma&#39;,
 &#39;Wooper&#39;,
 &#39;Quagsire&#39;,
 &#39;Espeon&#39;,
 &#39;Umbreon&#39;,
 &#39;Murkrow&#39;,
 &#39;Slowking&#39;,
 &#39;Misdreavus&#39;,
 &#39;Unown&#39;,
 &#39;Wobbuffet&#39;,
 &#39;Girafarig&#39;,
 &#39;Pineco&#39;,
 &#39;Forretress&#39;,
 &#39;Dunsparce&#39;,
 &#39;Gligar&#39;,
 &#39;Steelix&#39;,
 &#39;Snubbull&#39;,
 &#39;Granbull&#39;,
 &#39;Qwilfish&#39;,
 &#39;Scizor&#39;,
 &#39;Shuckle&#39;,
 &#39;Heracross&#39;,
 &#39;Sneasel&#39;,
 &#39;Teddiursa&#39;,
 &#39;Ursaring&#39;,
 &#39;Slugma&#39;,
 &#39;Magcargo&#39;,
 &#39;Swinub&#39;,
 &#39;Piloswine&#39;,
 &#39;Corsola&#39;,
 &#39;Remoraid&#39;,
 &#39;Octillery&#39;,
 &#39;Delibird&#39;,
 &#39;Mantine&#39;,
 &#39;Skarmory&#39;,
 &#39;Houndour&#39;,
 &#39;Houndoom&#39;,
 &#39;Kingdra&#39;,
 &#39;Phanpy&#39;,
 &#39;Donphan&#39;,
 &#39;Porygon2&#39;,
 &#39;Stantler&#39;,
 &#39;Smeargle&#39;,
 &#39;Tyrogue&#39;,
 &#39;Hitmontop&#39;,
 &#39;Smoochum&#39;,
 &#39;Elekid&#39;,
 &#39;Magby&#39;,
 &#39;Miltank&#39;,
 &#39;Blissey&#39;,
 &#39;Raikou&#39;,
 &#39;Entei&#39;,
 &#39;Suicune&#39;,
 &#39;Larvitar&#39;,
 &#39;Pupitar&#39;,
 &#39;Tyranitar&#39;,
 &#39;Lugia&#39;,
 &#39;Ho-oh&#39;,
 &#39;Celebi&#39;,
 &#39;Treecko&#39;,
 &#39;Grovyle&#39;,
 &#39;Sceptile&#39;,
 &#39;Torchic&#39;,
 &#39;Combusken&#39;,
 &#39;Blaziken&#39;,
 &#39;Mudkip&#39;,
 &#39;Marshtomp&#39;,
 &#39;Swampert&#39;,
 &#39;Poochyena&#39;,
 &#39;Mightyena&#39;,
 &#39;Zigzagoon&#39;,
 &#39;Linoone&#39;,
 &#39;Wurmple&#39;,
 &#39;Silcoon&#39;,
 &#39;Beautifly&#39;,
 &#39;Cascoon&#39;,
 &#39;Dustox&#39;,
 &#39;Lotad&#39;,
 &#39;Lombre&#39;,
 &#39;Ludicolo&#39;,
 &#39;Seedot&#39;,
 &#39;Nuzleaf&#39;,
 &#39;Shiftry&#39;,
 &#39;Taillow&#39;,
 &#39;Swellow&#39;,
 &#39;Wingull&#39;,
 &#39;Pelipper&#39;,
 &#39;Ralts&#39;,
 &#39;Kirlia&#39;,
 &#39;Gardevoir&#39;,
 &#39;Surskit&#39;,
 &#39;Masquerain&#39;,
 &#39;Shroomish&#39;,
 &#39;Breloom&#39;,
 &#39;Slakoth&#39;,
 &#39;Vigoroth&#39;,
 &#39;Slaking&#39;,
 &#39;Nincada&#39;,
 &#39;Ninjask&#39;,
 &#39;Shedinja&#39;,
 &#39;Whismur&#39;,
 &#39;Loudred&#39;,
 &#39;Exploud&#39;,
 &#39;Makuhita&#39;,
 &#39;Hariyama&#39;,
 &#39;Azurill&#39;,
 &#39;Nosepass&#39;,
 &#39;Skitty&#39;,
 &#39;Delcatty&#39;,
 &#39;Sableye&#39;,
 &#39;Mawile&#39;,
 &#39;Aron&#39;,
 &#39;Lairon&#39;,
 &#39;Aggron&#39;,
 &#39;Meditite&#39;,
 &#39;Medicham&#39;,
 &#39;Electrike&#39;,
 &#39;Manectric&#39;,
 &#39;Plusle&#39;,
 &#39;Minun&#39;,
 &#39;Volbeat&#39;,
 &#39;Illumise&#39;,
 &#39;Roselia&#39;,
 &#39;Gulpin&#39;,
 &#39;Swalot&#39;,
 &#39;Carvanha&#39;,
 &#39;Sharpedo&#39;,
 &#39;Wailmer&#39;,
 &#39;Wailord&#39;,
 &#39;Numel&#39;,
 &#39;Camerupt&#39;,
 &#39;Torkoal&#39;,
 &#39;Spoink&#39;,
 &#39;Grumpig&#39;,
 &#39;Spinda&#39;,
 &#39;Trapinch&#39;,
 &#39;Vibrava&#39;,
 &#39;Flygon&#39;,
 &#39;Cacnea&#39;,
 &#39;Cacturne&#39;,
 &#39;Swablu&#39;,
 &#39;Altaria&#39;,
 &#39;Zangoose&#39;,
 &#39;Seviper&#39;,
 &#39;Lunatone&#39;,
 &#39;Solrock&#39;,
 &#39;Barboach&#39;,
 &#39;Whiscash&#39;,
 &#39;Corphish&#39;,
 &#39;Crawdaunt&#39;,
 &#39;Baltoy&#39;,
 &#39;Claydol&#39;,
 &#39;Lileep&#39;,
 &#39;Cradily&#39;,
 &#39;Anorith&#39;,
 &#39;Armaldo&#39;,
 &#39;Feebas&#39;,
 &#39;Milotic&#39;,
 &#39;Castform&#39;,
 &#39;Kecleon&#39;,
 &#39;Shuppet&#39;,
 &#39;Banette&#39;,
 &#39;Duskull&#39;,
 &#39;Dusclops&#39;,
 &#39;Tropius&#39;,
 &#39;Chimecho&#39;,
 &#39;Absol&#39;,
 &#39;Wynaut&#39;,
 &#39;Snorunt&#39;,
 &#39;Glalie&#39;,
 &#39;Spheal&#39;,
 &#39;Sealeo&#39;,
 &#39;Walrein&#39;,
 &#39;Clamperl&#39;,
 &#39;Huntail&#39;,
 &#39;Gorebyss&#39;,
 &#39;Relicanth&#39;,
 &#39;Luvdisc&#39;,
 &#39;Bagon&#39;,
 &#39;Shelgon&#39;,
 &#39;Salamence&#39;,
 &#39;Beldum&#39;,
 &#39;Metang&#39;,
 &#39;Metagross&#39;,
 &#39;Regirock&#39;,
 &#39;Regice&#39;,
 &#39;Registeel&#39;,
 &#39;Latias&#39;,
 &#39;Latios&#39;,
 &#39;Kyogre&#39;,
 &#39;Groudon&#39;,
 &#39;Rayquaza&#39;,
 &#39;Jirachi&#39;,
 &#39;Deoxys&#39;,
 &#39;Turtwig&#39;,
 &#39;Grotle&#39;,
 &#39;Torterra&#39;,
 &#39;Chimchar&#39;,
 &#39;Monferno&#39;,
 &#39;Infernape&#39;,
 &#39;Piplup&#39;,
 &#39;Prinplup&#39;,
 &#39;Empoleon&#39;,
 &#39;Starly&#39;,
 &#39;Staravia&#39;,
 &#39;Staraptor&#39;,
 &#39;Bidoof&#39;,
 &#39;Bibarel&#39;,
 &#39;Kricketot&#39;,
 &#39;Kricketune&#39;,
 &#39;Shinx&#39;,
 &#39;Luxio&#39;,
 &#39;Luxray&#39;,
 &#39;Budew&#39;,
 &#39;Roserade&#39;,
 &#39;Cranidos&#39;,
 &#39;Rampardos&#39;,
 &#39;Shieldon&#39;,
 &#39;Bastiodon&#39;,
 &#39;Burmy&#39;,
 &#39;Wormadam&#39;,
 &#39;Mothim&#39;,
 &#39;Combee&#39;,
 &#39;Vespiquen&#39;,
 &#39;Pachirisu&#39;,
 &#39;Buizel&#39;,
 &#39;Floatzel&#39;,
 &#39;Cherubi&#39;,
 &#39;Cherrim&#39;,
 &#39;Shellos&#39;,
 &#39;Gastrodon&#39;,
 &#39;Ambipom&#39;,
 &#39;Drifloon&#39;,
 &#39;Drifblim&#39;,
 &#39;Buneary&#39;,
 &#39;Lopunny&#39;,
 &#39;Mismagius&#39;,
 &#39;Honchkrow&#39;,
 &#39;Glameow&#39;,
 &#39;Purugly&#39;,
 &#39;Chingling&#39;,
 &#39;Stunky&#39;,
 &#39;Skuntank&#39;,
 &#39;Bronzor&#39;,
 &#39;Bronzong&#39;,
 &#39;Bonsly&#39;,
 &#39;Mime Jr.&#39;,
 &#39;Happiny&#39;,
 &#39;Chatot&#39;,
 &#39;Spiritomb&#39;,
 &#39;Gible&#39;,
 &#39;Gabite&#39;,
 &#39;Garchomp&#39;,
 &#39;Munchlax&#39;,
 &#39;Riolu&#39;,
 &#39;Lucario&#39;,
 &#39;Hippopotas&#39;,
 &#39;Hippowdon&#39;,
 &#39;Skorupi&#39;,
 &#39;Drapion&#39;,
 &#39;Croagunk&#39;,
 &#39;Toxicroak&#39;,
 &#39;Carnivine&#39;,
 &#39;Finneon&#39;,
 &#39;Lumineon&#39;,
 &#39;Mantyke&#39;,
 &#39;Snover&#39;,
 &#39;Abomasnow&#39;,
 &#39;Weavile&#39;,
 &#39;Magnezone&#39;,
 &#39;Lickilicky&#39;,
 &#39;Rhyperior&#39;,
 &#39;Tangrowth&#39;,
 &#39;Electivire&#39;,
 &#39;Magmortar&#39;,
 &#39;Togekiss&#39;,
 &#39;Yanmega&#39;,
 &#39;Leafeon&#39;,
 &#39;Glaceon&#39;,
 &#39;Gliscor&#39;,
 &#39;Mamoswine&#39;,
 &#39;Porygon-Z&#39;,
 &#39;Gallade&#39;,
 &#39;Probopass&#39;,
 &#39;Dusknoir&#39;,
 &#39;Froslass&#39;,
 &#39;Rotom&#39;,
 &#39;Uxie&#39;,
 &#39;Mesprit&#39;,
 &#39;Azelf&#39;,
 &#39;Dialga&#39;,
 &#39;Palkia&#39;,
 &#39;Heatran&#39;,
 &#39;Regigigas&#39;,
 &#39;Giratina&#39;,
 &#39;Cresselia&#39;,
 &#39;Phione&#39;,
 &#39;Manaphy&#39;,
 &#39;Darkrai&#39;,
 &#39;Shaymin&#39;,
 &#39;Arceus&#39;,
 &#39;Victini&#39;,
 &#39;Snivy&#39;,
 &#39;Servine&#39;,
 &#39;Serperior&#39;,
 &#39;Tepig&#39;,
 &#39;Pignite&#39;,
 &#39;Emboar&#39;,
 &#39;Oshawott&#39;,
 &#39;Dewott&#39;,
 &#39;Samurott&#39;,
 &#39;Patrat&#39;,
 &#39;Watchog&#39;,
 &#39;Lillipup&#39;,
 &#39;Herdier&#39;,
 &#39;Stoutland&#39;,
 &#39;Purrloin&#39;,
 &#39;Liepard&#39;,
 &#39;Pansage&#39;,
 &#39;Simisage&#39;,
 &#39;Pansear&#39;,
 &#39;Simisear&#39;,
 &#39;Panpour&#39;,
 &#39;Simipour&#39;,
 &#39;Munna&#39;,
 &#39;Musharna&#39;,
 &#39;Pidove&#39;,
 &#39;Tranquill&#39;,
 &#39;Unfezant&#39;,
 &#39;Blitzle&#39;,
 &#39;Zebstrika&#39;,
 &#39;Roggenrola&#39;,
 &#39;Boldore&#39;,
 &#39;Gigalith&#39;,
 &#39;Woobat&#39;,
 &#39;Swoobat&#39;,
 &#39;Drilbur&#39;,
 &#39;Excadrill&#39;,
 &#39;Audino&#39;,
 &#39;Timburr&#39;,
 &#39;Gurdurr&#39;,
 &#39;Conkeldurr&#39;,
 &#39;Tympole&#39;,
 &#39;Palpitoad&#39;,
 &#39;Seismitoad&#39;,
 &#39;Throh&#39;,
 &#39;Sawk&#39;,
 &#39;Sewaddle&#39;,
 &#39;Swadloon&#39;,
 &#39;Leavanny&#39;,
 &#39;Venipede&#39;,
 &#39;Whirlipede&#39;,
 &#39;Scolipede&#39;,
 &#39;Cottonee&#39;,
 &#39;Whimsicott&#39;,
 &#39;Petilil&#39;,
 &#39;Lilligant&#39;,
 &#39;Basculin&#39;,
 &#39;Sandile&#39;,
 &#39;Krokorok&#39;,
 &#39;Krookodile&#39;,
 &#39;Darumaka&#39;,
 &#39;Darmanitan&#39;,
 &#39;Maractus&#39;,
 &#39;Dwebble&#39;,
 &#39;Crustle&#39;,
 &#39;Scraggy&#39;,
 &#39;Scrafty&#39;,
 &#39;Sigilyph&#39;,
 &#39;Yamask&#39;,
 &#39;Cofagrigus&#39;,
 &#39;Tirtouga&#39;,
 &#39;Carracosta&#39;,
 &#39;Archen&#39;,
 &#39;Archeops&#39;,
 &#39;Trubbish&#39;,
 &#39;Garbodor&#39;,
 &#39;Zorua&#39;,
 &#39;Zoroark&#39;,
 &#39;Minccino&#39;,
 &#39;Cinccino&#39;,
 &#39;Gothita&#39;,
 &#39;Gothorita&#39;,
 &#39;Gothitelle&#39;,
 &#39;Solosis&#39;,
 &#39;Duosion&#39;,
 &#39;Reuniclus&#39;,
 &#39;Ducklett&#39;,
 &#39;Swanna&#39;,
 &#39;Vanillite&#39;,
 &#39;Vanillish&#39;,
 &#39;Vanilluxe&#39;,
 &#39;Deerling&#39;,
 &#39;Sawsbuck&#39;,
 &#39;Emolga&#39;,
 &#39;Karrablast&#39;,
 &#39;Escavalier&#39;,
 &#39;Foongus&#39;,
 &#39;Amoonguss&#39;,
 &#39;Frillish&#39;,
 &#39;Jellicent&#39;,
 &#39;Alomomola&#39;,
 &#39;Joltik&#39;,
 &#39;Galvantula&#39;,
 &#39;Ferroseed&#39;,
 &#39;Ferrothorn&#39;,
 &#39;Klink&#39;,
 &#39;Klang&#39;,
 &#39;Klinklang&#39;,
 &#39;Tynamo&#39;,
 &#39;Eelektrik&#39;,
 &#39;Eelektross&#39;,
 &#39;Elgyem&#39;,
 &#39;Beheeyem&#39;,
 &#39;Litwick&#39;,
 &#39;Lampent&#39;,
 &#39;Chandelure&#39;,
 &#39;Axew&#39;,
 &#39;Fraxure&#39;,
 &#39;Haxorus&#39;,
 &#39;Cubchoo&#39;,
 &#39;Beartic&#39;,
 &#39;Cryogonal&#39;,
 &#39;Shelmet&#39;,
 &#39;Accelgor&#39;,
 &#39;Stunfisk&#39;,
 &#39;Mienfoo&#39;,
 &#39;Mienshao&#39;,
 &#39;Druddigon&#39;,
 &#39;Golett&#39;,
 &#39;Golurk&#39;,
 &#39;Pawniard&#39;,
 &#39;Bisharp&#39;,
 &#39;Bouffalant&#39;,
 &#39;Rufflet&#39;,
 &#39;Braviary&#39;,
 &#39;Vullaby&#39;,
 &#39;Mandibuzz&#39;,
 &#39;Heatmor&#39;,
 &#39;Durant&#39;,
 &#39;Deino&#39;,
 &#39;Zweilous&#39;,
 &#39;Hydreigon&#39;,
 &#39;Larvesta&#39;,
 &#39;Volcarona&#39;,
 &#39;Cobalion&#39;,
 &#39;Terrakion&#39;,
 &#39;Virizion&#39;,
 &#39;Tornadus&#39;,
 &#39;Thundurus&#39;,
 &#39;Reshiram&#39;,
 &#39;Zekrom&#39;,
 &#39;Landorus&#39;,
 &#39;Kyurem&#39;,
 &#39;Keldeo&#39;,
 &#39;Meloetta&#39;,
 &#39;Genesect&#39;,
 &#39;Chespin&#39;,
 &#39;Quilladin&#39;,
 &#39;Chesnaught&#39;,
 &#39;Fennekin&#39;,
 &#39;Braixen&#39;,
 &#39;Delphox&#39;,
 &#39;Froakie&#39;,
 &#39;Frogadier&#39;,
 &#39;Greninja&#39;,
 &#39;Bunnelby&#39;,
 &#39;Diggersby&#39;,
 &#39;Fletchling&#39;,
 &#39;Fletchinder&#39;,
 &#39;Talonflame&#39;,
 &#39;Scatterbug&#39;,
 &#39;Spewpa&#39;,
 &#39;Vivillon&#39;,
 &#39;Litleo&#39;,
 &#39;Pyroar&#39;,
 &#39;Flabébé&#39;,
 &#39;Floette&#39;,
 &#39;Florges&#39;,
 &#39;Skiddo&#39;,
 &#39;Gogoat&#39;,
 &#39;Pancham&#39;,
 &#39;Pangoro&#39;,
 &#39;Furfrou&#39;,
 &#39;Espurr&#39;,
 &#39;Meowstic&#39;,
 &#39;Honedge&#39;,
 &#39;Doublade&#39;,
 &#39;Aegislash&#39;,
 &#39;Spritzee&#39;,
 &#39;Aromatisse&#39;,
 &#39;Swirlix&#39;,
 &#39;Slurpuff&#39;,
 &#39;Inkay&#39;,
 &#39;Malamar&#39;,
 &#39;Binacle&#39;,
 &#39;Barbaracle&#39;,
 &#39;Skrelp&#39;,
 &#39;Dragalge&#39;,
 &#39;Clauncher&#39;,
 &#39;Clawitzer&#39;,
 &#39;Helioptile&#39;,
 &#39;Heliolisk&#39;,
 &#39;Tyrunt&#39;,
 &#39;Tyrantrum&#39;,
 &#39;Amaura&#39;,
 &#39;Aurorus&#39;,
 &#39;Sylveon&#39;,
 &#39;Hawlucha&#39;,
 &#39;Dedenne&#39;,
 &#39;Carbink&#39;,
 &#39;Goomy&#39;,
 &#39;Sliggoo&#39;,
 &#39;Goodra&#39;,
 &#39;Klefki&#39;,
 &#39;Phantump&#39;,
 &#39;Trevenant&#39;,
 &#39;Pumpkaboo&#39;,
 &#39;Gourgeist&#39;,
 &#39;Bergmite&#39;,
 &#39;Avalugg&#39;,
 &#39;Noibat&#39;,
 &#39;Noivern&#39;,
 &#39;Xerneas&#39;,
 &#39;Yveltal&#39;,
 &#39;Zygarde&#39;,
 &#39;Diancie&#39;,
 &#39;Hoopa&#39;,
 &#39;Volcanion&#39;]</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[62]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">dict</span><span class="p">(</span><span class="n">google</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[62]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>{0: 50.119999999999997,
 1: 54.100000000000001,
 2: 54.649999999999999,
 3: 52.380000000000003,
 4: 52.950000000000003,
 5: 53.899999999999999,
 6: 53.020000000000003,
 7: 50.950000000000003,
 8: 51.130000000000003,
 9: 50.07,
 10: 50.700000000000003,
 11: 49.950000000000003,
 12: 50.740000000000002,
 13: 51.100000000000001,
 14: 51.100000000000001,
 15: 52.609999999999999,
 16: 53.700000000000003,
 17: 55.689999999999998,
 18: 55.939999999999998,
 19: 56.93,
 20: 58.689999999999998,
 21: 59.619999999999997,
 22: 58.859999999999999,
 23: 59.130000000000003,
 24: 60.350000000000001,
 25: 59.859999999999999,
 26: 59.07,
 27: 63.369999999999997,
 28: 65.469999999999999,
 29: 64.739999999999995,
 30: 66.219999999999999,
 31: 67.459999999999994,
 32: 69.120000000000005,
 33: 68.469999999999999,
 34: 69.359999999999999,
 35: 68.799999999999997,
 36: 67.560000000000002,
 37: 68.629999999999995,
 38: 70.379999999999995,
 39: 70.930000000000007,
 40: 71.980000000000004,
 41: 74.510000000000005,
 42: 73.900000000000006,
 43: 70.170000000000002,
 44: 74.620000000000005,
 45: 86.129999999999995,
 46: 93.609999999999999,
 47: 90.810000000000002,
 48: 92.890000000000001,
 49: 96.549999999999997,
 50: 95.219999999999999,
 51: 97.920000000000002,
 52: 97.340000000000003,
 53: 95.739999999999995,
 54: 92.260000000000005,
 55: 84.590000000000003,
 56: 86.189999999999998,
 57: 84.269999999999996,
 58: 83.849999999999994,
 59: 91.420000000000002,
 60: 90.909999999999997,
 61: 92.340000000000003,
 62: 86.189999999999998,
 63: 86.159999999999997,
 64: 83.689999999999998,
 65: 84.620000000000005,
 66: 82.469999999999999,
 67: 83.680000000000007,
 68: 87.290000000000006,
 69: 89.609999999999999,
 70: 90.430000000000007,
 71: 90.900000000000006,
 72: 89.890000000000001,
 73: 89.609999999999999,
 74: 90.109999999999999,
 75: 88.060000000000002,
 76: 85.629999999999995,
 77: 84.909999999999997,
 78: 86.629999999999995,
 79: 85.739999999999995,
 80: 85.140000000000001,
 81: 89.260000000000005,
 82: 89.799999999999997,
 83: 88.150000000000006,
 84: 89.950000000000003,
 85: 92.420000000000002,
 86: 91.780000000000001,
 87: 93.060000000000002,
 88: 93.859999999999999,
 89: 95.859999999999999,
 90: 96.280000000000001,
 91: 96.349999999999994,
 92: 98.700000000000003,
 93: 96.299999999999997,
 94: 101.25,
 95: 97.150000000000006,
 96: 96.659999999999997,
 97: 94.180000000000007,
 98: 96.829999999999998,
 99: 97.430000000000007,
 100: 96.670000000000002,
 101: 97.590000000000003,
 102: 97.569999999999993,
 103: 99.890000000000001,
 104: 101.84999999999999,
 105: 98.549999999999997,
 106: 96.859999999999999,
 107: 94.049999999999997,
 108: 90.269999999999996,
 109: 88.469999999999999,
 110: 94.530000000000001,
 111: 93.950000000000003,
 112: 95.069999999999993,
 113: 97.709999999999994,
 114: 95.849999999999994,
 115: 102.88,
 116: 105.31999999999999,
 117: 102.08,
 118: 97.920000000000002,
 119: 99.219999999999999,
 120: 95.689999999999998,
 121: 93.900000000000006,
 122: 93.609999999999999,
 123: 96.400000000000006,
 124: 97.519999999999996,
 125: 99.109999999999999,
 126: 98.849999999999994,
 127: 98.879999999999995,
 128: 95.590000000000003,
 129: 96.879999999999995,
 130: 94.349999999999994,
 131: 92.840000000000003,
 132: 93.900000000000006,
 133: 92.939999999999998,
 134: 92.5,
 135: 93.409999999999997,
 136: 92.859999999999999,
 137: 94.310000000000002,
 138: 92.510000000000005,
 139: 90.579999999999998,
 140: 89.900000000000006,
 141: 88.810000000000002,
 142: 87.409999999999997,
 143: 89.219999999999999,
 144: 87.709999999999994,
 145: 89.560000000000002,
 146: 89.930000000000007,
 147: 90.349999999999994,
 148: 89.209999999999994,
 149: 89.400000000000006,
 150: 89.540000000000006,
 151: 90.620000000000005,
 152: 89.700000000000003,
 153: 90.129999999999995,
 154: 90.159999999999997,
 155: 89.930000000000007,
 156: 92.549999999999997,
 157: 94.189999999999998,
 158: 94.519999999999996,
 159: 96.780000000000001,
 160: 95.930000000000007,
 161: 96.519999999999996,
 162: 96.879999999999995,
 163: 96.370000000000005,
 164: 95.629999999999995,
 165: 92.409999999999997,
 166: 93.390000000000001,
 167: 95.599999999999994,
 168: 98.950000000000003,
 169: 102.01000000000001,
 170: 107.8,
 171: 111.65000000000001,
 172: 109.27,
 173: 109.78,
 174: 109.62,
 175: 109.89,
 176: 111.03,
 177: 112.98,
 178: 114.14,
 179: 113.38,
 180: 113.90000000000001,
 181: 112.90000000000001,
 182: 113.79000000000001,
 183: 115.53,
 184: 114.25,
 185: 114.51000000000001,
 186: 115.41,
 187: 116.45,
 188: 119.45999999999999,
 189: 119.47,
 190: 120.68000000000001,
 191: 127.59999999999999,
 192: 127.87,
 193: 130.27000000000001,
 194: 129.47,
 195: 132.87,
 196: 138.5,
 197: 143.86000000000001,
 198: 143.81,
 199: 139.99000000000001,
 200: 145.31999999999999,
 201: 146.41,
 202: 139.63999999999999,
 203: 143.00999999999999,
 204: 141.11000000000001,
 205: 141.22999999999999,
 206: 139.03999999999999,
 207: 137.25999999999999,
 208: 138.58000000000001,
 209: 140.0,
 210: 143.21000000000001,
 211: 143.78,
 212: 144.50999999999999,
 213: 144.71000000000001,
 214: 148.47999999999999,
 215: 151.90000000000001,
 216: 150.84999999999999,
 217: 146.21000000000001,
 218: 146.93000000000001,
 219: 145.47999999999999,
 220: 147.71000000000001,
 221: 145.62,
 222: 147.62,
 223: 147.97,
 224: 146.53,
 225: 145.75,
 226: 149.28,
 227: 150.28999999999999,
 228: 150.44,
 229: 149.62,
 230: 154.80000000000001,
 231: 155.84,
 232: 156.81,
 233: 151.05000000000001,
 234: 147.78,
 235: 147.90000000000001,
 236: 148.31999999999999,
 237: 146.59999999999999,
 238: 143.74000000000001,
 239: 145.66,
 240: 149.44999999999999,
 241: 148.5,
 242: 148.72,
 243: 146.03,
 244: 145.47999999999999,
 245: 145.63999999999999,
 246: 142.69999999999999,
 247: 141.88,
 248: 144.72,
 249: 141.86000000000001,
 250: 142.68000000000001,
 251: 142.41,
 252: 139.86000000000001,
 253: 139.86000000000001,
 254: 136.87,
 255: 139.65000000000001,
 256: 141.13999999999999,
 257: 141.15000000000001,
 258: 141.65000000000001,
 259: 144.08000000000001,
 260: 143.49000000000001,
 261: 142.86000000000001,
 262: 142.97999999999999,
 263: 144.08000000000001,
 264: 143.41,
 265: 147.28999999999999,
 266: 147.55000000000001,
 267: 149.40000000000001,
 268: 154.72,
 269: 155.68000000000001,
 270: 151.34999999999999,
 271: 151.16,
 272: 149.94999999999999,
 273: 151.74000000000001,
 274: 153.80000000000001,
 275: 155.78999999999999,
 276: 155.53,
 277: 157.52000000000001,
 278: 156.97999999999999,
 279: 156.81,
 280: 152.84999999999999,
 281: 154.66,
 282: 158.06999999999999,
 283: 159.18000000000001,
 284: 155.34,
 285: 155.19999999999999,
 286: 156.22,
 287: 156.34,
 288: 155.16999999999999,
 289: 152.90000000000001,
 290: 150.33000000000001,
 291: 148.56999999999999,
 292: 147.91999999999999,
 293: 152.34999999999999,
 294: 151.49000000000001,
 295: 154.19999999999999,
 296: 151.44999999999999,
 297: 169.78,
 298: 174.15000000000001,
 299: 173.28,
 300: 177.53999999999999,
 301: 176.34999999999999,
 302: 178.91,
 303: 185.88,
 304: 189.5,
 305: 189.65000000000001,
 306: 192.78,
 307: 195.02000000000001,
 308: 197.31999999999999,
 309: 194.75999999999999,
 310: 189.38999999999999,
 311: 195.34999999999999,
 312: 195.0,
 313: 198.28999999999999,
 314: 196.19999999999999,
 315: 198.88,
 316: 201.52000000000001,
 317: 199.90000000000001,
 318: 204.47999999999999,
 319: 208.03,
 320: 211.22,
 321: 214.09999999999999,
 322: 211.53,
 323: 201.56999999999999,
 324: 202.25,
 325: 206.84,
 326: 208.63999999999999,
 327: 202.72,
 328: 202.06999999999999,
 329: 201.91,
 330: 205.12,
 331: 204.40000000000001,
 332: 206.09999999999999,
 333: 208.53999999999999,
 334: 209.27000000000001,
 335: 211.05000000000001,
 336: 214.86000000000001,
 337: 212.09,
 338: 214.66,
 339: 212.94999999999999,
 340: 215.80000000000001,
 341: 215.25,
 342: 212.11000000000001,
 343: 213.13,
 344: 209.86000000000001,
 345: 207.22,
 346: 217.40000000000001,
 347: 222.40000000000001,
 348: 225.38999999999999,
 349: 232.59999999999999,
 350: 233.22,
 351: 234.65000000000001,
 352: 235.58000000000001,
 353: 231.58000000000001,
 354: 232.88999999999999,
 355: 233.31999999999999,
 356: 222.22999999999999,
 357: 218.0,
 358: 199.53,
 359: 213.53999999999999,
 360: 221.28999999999999,
 361: 216.28,
 362: 216.91999999999999,
 363: 216.53,
 364: 213.19999999999999,
 365: 216.11000000000001,
 366: 200.69,
 367: 197.81999999999999,
 368: 190.59,
 369: 192.36000000000001,
 370: 183.78,
 371: 184.36000000000001,
 372: 179.21000000000001,
 373: 181.12,
 374: 172.68000000000001,
 375: 171.49000000000001,
 376: 171.02000000000001,
 377: 183.05000000000001,
 378: 184.19,
 379: 183.11000000000001,
 380: 182.56,
 381: 188.84999999999999,
 382: 188.50999999999999,
 383: 194.99000000000001,
 384: 181.13,
 385: 182.22,
 386: 188.03999999999999,
 387: 188.90000000000001,
 388: 183.87,
 389: 182.03999999999999,
 390: 176.75999999999999,
 391: 171.33000000000001,
 392: 168.58000000000001,
 393: 168.36000000000001,
 394: 175.40000000000001,
 395: 172.08000000000001,
 396: 169.22,
 397: 169.72999999999999,
 398: 173.91999999999999,
 399: 169.78999999999999,
 400: 169.94,
 401: 170.77000000000001,
 402: 182.72,
 403: 184.66,
 404: 188.41,
 405: 197.28999999999999,
 406: 194.03,
 407: 194.80000000000001,
 408: 194.66,
 409: 201.97,
 410: 203.78999999999999,
 411: 205.38,
 412: 202.88,
 413: 207.97999999999999,
 414: 204.63,
 415: 204.27000000000001,
 416: 200.88,
 417: 203.21000000000001,
 418: 201.91999999999999,
 419: 205.03999999999999,
 420: 207.28999999999999,
 421: 218.33000000000001,
 422: 220.03,
 423: 213.37,
 424: 212.77000000000001,
 425: 209.80000000000001,
 426: 208.75999999999999,
 427: 199.25,
 428: 197.19999999999999,
 429: 196.88999999999999,
 430: 197.18000000000001,
 431: 196.94999999999999,
 432: 197.19,
 433: 204.19999999999999,
 434: 201.28999999999999,
 435: 193.31,
 436: 186.88,
 437: 187.91,
 438: 185.46000000000001,
 439: 187.06,
 440: 185.31,
 441: 184.81999999999999,
 442: 185.28999999999999,
 443: 187.59999999999999,
 444: 190.43000000000001,
 445: 191.30000000000001,
 446: 190.47999999999999,
 447: 185.78,
 448: 185.72,
 449: 191.12,
 450: 189.53,
 451: 187.03,
 452: 194.80000000000001,
 453: 193.06,
 454: 196.44999999999999,
 455: 193.09,
 456: 190.58000000000001,
 457: 193.06999999999999,
 458: 192.0,
 459: 195.30000000000001,
 460: 195.15000000000001,
 461: 193.88,
 462: 193.38999999999999,
 463: 200.86000000000001,
 464: 199.78,
 465: 202.22999999999999,
 466: 201.91,
 467: 200.96000000000001,
 468: 202.84999999999999,
 469: 208.69999999999999,
 470: 209.46000000000001,
 471: 211.38999999999999,
 472: 210.52000000000001,
 473: 211.38,
 474: 210.00999999999999,
 475: 208.88999999999999,
 476: 212.06999999999999,
 477: 208.41999999999999,
 478: 204.21000000000001,
 479: 201.55000000000001,
 480: 203.74000000000001,
 481: 201.31999999999999,
 482: 199.30000000000001,
 483: 193.37,
 484: 194.86000000000001,
 485: 195.25,
 486: 194.49000000000001,
 487: 192.56,
 488: 191.00999999999999,
 489: 193.87,
 490: 193.11000000000001,
 491: 187.56999999999999,
 492: 183.43000000000001,
 493: 187.50999999999999,
 494: 186.74000000000001,
 495: 188.78999999999999,
 496: 190.31,
 497: 188.28,
 498: 186.91,
 499: 184.06999999999999,
 500: 184.53,
 501: 190.28999999999999,
 502: 193.66999999999999,
 503: 192.71000000000001,
 504: 191.49000000000001,
 505: 188.46000000000001,
 506: 188.96000000000001,
 507: 186.53,
 508: 186.68000000000001,
 509: 186.44,
 510: 190.28,
 511: 189.28999999999999,
 512: 190.18000000000001,
 513: 189.08000000000001,
 514: 189.11000000000001,
 515: 191.99000000000001,
 516: 189.88,
 517: 189.06,
 518: 188.74000000000001,
 519: 191.84999999999999,
 520: 195.75,
 521: 203.08000000000001,
 522: 201.78999999999999,
 523: 204.74000000000001,
 524: 207.13999999999999,
 525: 201.69999999999999,
 526: 198.30000000000001,
 527: 203.22,
 528: 201.69,
 529: 201.78999999999999,
 530: 203.22999999999999,
 531: 201.25999999999999,
 532: 201.59,
 533: 200.75,
 534: 200.52000000000001,
 535: 201.81999999999999,
 536: 207.63999999999999,
 537: 205.69999999999999,
 538: 210.03999999999999,
 539: 214.28999999999999,
 540: 213.11000000000001,
 541: 213.03999999999999,
 542: 213.50999999999999,
 543: 213.44,
 544: 210.66,
 545: 210.11000000000001,
 546: 209.44,
 547: 212.81999999999999,
 548: 229.61000000000001,
 549: 240.15000000000001,
 550: 236.41999999999999,
 551: 243.06,
 552: 242.31,
 553: 237.36000000000001,
 554: 238.05000000000001,
 555: 237.96000000000001,
 556: 233.52000000000001,
 557: 234.72,
 558: 235.66,
 559: 238.24000000000001,
 560: 236.05000000000001,
 561: 237.25999999999999,
 562: 236.08000000000001,
 563: 236.53999999999999,
 564: 240.27000000000001,
 565: 244.41,
 566: 245.72,
 567: 247.69999999999999,
 568: 249.15000000000001,
 569: 247.28,
 570: 254.56999999999999,
 571: 253.75,
 572: 252.19999999999999,
 573: 242.13,
 574: 244.50999999999999,
 575: 242.08000000000001,
 576: 242.16,
 577: 240.16,
 578: 242.18000000000001,
 579: 243.25999999999999,
 580: 244.11000000000001,
 581: 241.08000000000001,
 582: 241.81,
 583: 241.72,
 584: 240.65000000000001,
 585: 239.25999999999999,
 586: 240.81999999999999,
 587: 239.91,
 588: 231.16999999999999,
 589: 234.08000000000001,
 590: 231.22,
 591: 227.87,
 592: 227.56,
 593: 228.53999999999999,
 594: 233.78,
 595: 231.05000000000001,
 596: 230.00999999999999,
 597: 233.56,
 598: 241.38999999999999,
 599: 243.34999999999999,
 600: 241.55000000000001,
 601: 242.50999999999999,
 602: 244.49000000000001,
 603: 249.61000000000001,
 604: 252.25,
 605: 251.88999999999999,
 606: 248.38999999999999,
 607: 243.66999999999999,
 608: 244.63,
 609: 240.18000000000001,
 610: 239.28999999999999,
 611: 249.28,
 612: 243.80000000000001,
 613: 247.66999999999999,
 614: 245.99000000000001,
 615: 246.91,
 616: 250.5,
 617: 240.63,
 618: 240.50999999999999,
 619: 233.34999999999999,
 620: 235.5,
 621: 234.77000000000001,
 622: 235.28,
 623: 230.71000000000001,
 624: 228.91999999999999,
 625: 229.31999999999999,
 626: 232.72999999999999,
 627: 230.5,
 628: 234.74000000000001,
 629: 235.81,
 630: 237.69,
 631: 237.69,
 632: 235.06999999999999,
 633: 232.22999999999999,
 634: 224.16,
 635: 224.5,
 636: 223.88999999999999,
 637: 219.12,
 638: 220.25,
 639: 228.55000000000001,
 640: 227.59,
 641: 227.13,
 642: 226.25,
 643: 227.15000000000001,
 644: 221.28999999999999,
 645: 223.78,
 646: 222.87,
 647: 220.19999999999999,
 648: 223.38999999999999,
 649: 222.41999999999999,
 650: 228.05000000000001,
 651: 230.78999999999999,
 652: 230.68000000000001,
 653: 232.27000000000001,
 654: 231.58000000000001,
 655: 230.71000000000001,
 656: 230.22999999999999,
 657: 228.84999999999999,
 658: 229.03999999999999,
 659: 236.06,
 660: 235.27000000000001,
 661: 235.52000000000001,
 662: 233.87,
 663: 233.02000000000001,
 664: 232.03,
 665: 233.46000000000001,
 666: 232.91,
 667: 236.90000000000001,
 668: 236.16,
 669: 237.77000000000001,
 670: 235.59,
 671: 241.0,
 672: 239.30000000000001,
 673: 238.53,
 674: 238.75999999999999,
 675: 240.34999999999999,
 676: 239.27000000000001,
 677: 235.44999999999999,
 678: 234.27000000000001,
 679: 232.66,
 680: 236.38,
 681: 235.31999999999999,
 682: 233.40000000000001,
 683: 233.16999999999999,
 684: 234.38999999999999,
 685: 230.5,
 686: 233.13999999999999,
 687: 230.66,
 688: 228.77000000000001,
 689: 236.06999999999999,
 690: 235.24000000000001,
 691: 234.91999999999999,
 692: 235.06,
 693: 237.69,
 694: 236.75,
 695: 236.93000000000001,
 696: 241.52000000000001,
 697: 243.31,
 698: 249.05000000000001,
 699: 248.71000000000001,
 700: 249.94999999999999,
 701: 253.28,
 702: 259.16000000000003,
 703: 258.87,
 704: 257.26999999999998,
 705: 257.49000000000001,
 706: 255.41,
 707: 252.13,
 708: 252.37,
 709: 251.16999999999999,
 710: 252.69,
 711: 257.33999999999997,
 712: 256.89999999999998,
 713: 254.72999999999999,
 714: 256.80000000000001,
 715: 262.23000000000002,
 716: 263.44999999999999,
 717: 264.86000000000001,
 718: 262.88,
 719: 262.24000000000001,
 720: 261.08999999999997,
 721: 264.92000000000002,
 722: 266.89999999999998,
 723: 270.54000000000002,
 724: 269.43000000000001,
 725: 271.00999999999999,
 726: 271.39999999999998,
 727: 271.95999999999998,
 728: 272.38999999999999,
 729: 275.80000000000001,
 730: 276.22000000000003,
 731: 277.22000000000003,
 732: 274.48000000000002,
 733: 274.01999999999998,
 734: 259.80000000000001,
 735: 256.0,
 736: 256.74000000000001,
 737: 254.63,
 738: 253.75,
 739: 255.69,
 740: 257.80000000000001,
 741: 254.74000000000001,
 742: 256.20999999999998,
 743: 255.25,
 744: 251.25,
 745: 254.74000000000001,
 746: 257.75,
 747: 262.63,
 748: 257.11000000000001,
 749: 257.62,
 750: 257.49000000000001,
 751: 254.05000000000001,
 752: 248.53,
 753: 245.50999999999999,
 754: 249.77000000000001,
 755: 248.71000000000001,
 756: 253.05000000000001,
 757: 256.12,
 758: 255.84,
 759: 257.24000000000001,
 760: 256.37,
 761: 252.94999999999999,
 762: 256.18000000000001,
 763: 255.44,
 764: 257.37,
 765: 262.31,
 766: 263.63999999999999,
 767: 261.5,
 768: 259.42000000000002,
 769: 256.98000000000002,
 770: 260.39999999999998,
 771: 261.06,
 772: 262.13,
 773: 264.11000000000001,
 774: 262.38999999999999,
 775: 267.37,
 776: 273.14999999999998,
 777: 276.13999999999999,
 778: 279.76999999999998,
 779: 283.73000000000002,
 780: 284.22000000000003,
 781: 283.80000000000001,
 782: 283.47000000000003,
 783: 283.35000000000002,
 784: 290.98000000000002,
 785: 291.89999999999998,
 786: 291.72000000000003,
 787: 289.23000000000002,
 788: 296.73000000000002,
 789: 304.50999999999999,
 790: 307.27999999999997,
 791: 312.38,
 792: 310.69,
 793: 318.38,
 794: 309.74000000000001,
 795: 307.69,
 796: 316.42000000000002,
 797: 319.49000000000001,
 798: 322.02999999999997,
 799: 325.05000000000001,
 800: 337.55000000000001,
 801: 337.56999999999999,
 802: 333.92000000000002,
 803: 336.95999999999998,
 804: 339.27999999999997,
 805: 347.04000000000002,
 806: 353.14999999999998,
 807: 351.25,
 808: 355.26999999999998,
 809: 362.45999999999998,
 810: 370.51999999999998,
 811: 366.10000000000002,
 812: 346.56999999999999,
 813: 331.64999999999998,
 814: 315.72000000000003,
 815: 329.94,
 816: 320.51999999999998,
 817: 314.50999999999999,
 818: 316.5,
 819: 312.61000000000001,
 820: 323.94999999999999,
 821: 329.93000000000001,
 822: 338.00999999999999,
 823: 332.69999999999999,
 824: 336.44999999999999,
 825: 345.77999999999997,
 826: 348.14999999999998,
 827: 346.14999999999998,
 828: 340.42000000000002,
 829: 341.74000000000001,
 830: 348.91000000000003,
 831: 357.26999999999998,
 832: 357.07999999999998,
 833: 358.85000000000002,
 834: 349.25,
 835: 349.32999999999998,
 836: 346.68000000000001,
 837: 344.63999999999999,
 838: 334.27999999999997,
 839: 336.33999999999997,
 840: 338.35000000000002,
 841: 344.5,
 842: 348.0,
 843: 350.00999999999999,
 844: 355.06,
 845: 350.01999999999998,
 846: 350.91000000000003,
 847: 345.38999999999999,
 848: 342.25,
 849: 342.31999999999999,
 850: 328.17000000000002,
 851: 324.30000000000001,
 852: 315.51999999999998,
 853: 326.26999999999998,
 854: 323.04000000000002,
 855: 318.81,
 856: 326.57999999999998,
 857: 318.50999999999999,
 858: 307.67000000000002,
 859: 300.08999999999997,
 860: 299.81999999999999,
 861: 291.88,
 862: 274.04000000000002,
 863: 286.95999999999998,
 864: 282.92000000000002,
 865: 277.70999999999998,
 866: 274.98000000000002,
 867: 273.86000000000001,
 868: 281.87,
 869: 257.69,
 870: 247.47,
 871: 253.15000000000001,
 872: 250.59999999999999,
 873: 252.22,
 874: 258.08999999999997,
 875: 260.31999999999999,
 876: 258.79000000000002,
 877: 267.04000000000002,
 878: 265.86000000000001,
 879: 264.56,
 880: 254.22,
 881: 254.25,
 882: 251.18000000000001,
 883: 253.65000000000001,
 884: 242.97999999999999,
 885: 231.86000000000001,
 886: 236.19,
 887: 237.46000000000001,
 888: 235.34999999999999,
 889: 228.28,
 890: 222.08000000000001,
 891: 223.63,
 892: 216.13,
 893: 216.46000000000001,
 894: 206.59999999999999,
 895: 219.69999999999999,
 896: 219.87,
 897: 221.28,
 898: 218.74000000000001,
 899: 209.72999999999999,
 900: 219.36000000000001,
 901: 215.78,
 902: 216.56,
 903: 230.05000000000001,
 904: 225.16,
 905: 228.87,
 906: 221.81999999999999,
 907: 218.81999999999999,
 908: 220.00999999999999,
 909: 232.62,
 910: 232.62,
 911: 227.33000000000001,
 912: 235.31,
 913: 238.16999999999999,
 914: 233.66999999999999,
 915: 231.86000000000001,
 916: 234.30000000000001,
 917: 228.5,
 918: 225.59999999999999,
 919: 223.19999999999999,
 920: 227.28999999999999,
 921: 224.55000000000001,
 922: 269.44,
 923: 268.63,
 924: 277.22000000000003,
 925: 272.97000000000003,
 926: 271.25,
 927: 271.75999999999999,
 928: 275.77999999999997,
 929: 278.95999999999998,
 930: 286.86000000000001,
 931: 296.24000000000001,
 932: 290.35000000000002,
 933: 297.14999999999998,
 934: 292.88999999999999,
 935: 289.20999999999998,
 936: 291.20999999999998,
 937: 286.30000000000001,
 938: 292.18000000000001,
 939: 291.20999999999998,
 940: 287.86000000000001,
 941: 290.20999999999998,
 942: 289.74000000000001,
 943: 288.47000000000003,
 944: 289.00999999999999,
 945: 274.72000000000003,
 946: 274.45999999999998,
 947: 272.04000000000002,
 948: 280.17000000000002,
 949: 283.83999999999997,
 950: 291.20999999999998,
 951: 292.61000000000001,
 952: 287.20999999999998,
 953: 283.37,
 954: 285.81999999999999,
 955: 292.86000000000001,
 956: 283.22000000000003,
 957: 278.66000000000003,
 958: 276.81,
 959: 272.32999999999998,
 960: 276.19999999999999,
 961: 285.47000000000003,
 962: 286.12,
 963: 284.44999999999999,
 964: 280.91000000000003,
 965: 279.81999999999999,
 966: 272.94,
 967: 272.32999999999998,
 968: 270.88,
 969: 275.22000000000003,
 970: 264.14999999999998,
 971: 263.76999999999998,
 972: 262.94999999999999,
 973: 267.10000000000002,
 974: 263.25999999999999,
 975: 268.23000000000002,
 976: 271.68000000000001,
 977: 276.99000000000001,
 978: 270.5,
 979: 270.01999999999998,
 980: 266.63,
 981: 260.55000000000001,
 982: 257.79000000000002,
 983: 267.52999999999997,
 984: 266.44999999999999,
 985: 240.41999999999999,
 986: 234.16999999999999,
 987: 238.31999999999999,
 988: 244.37,
 989: 237.56999999999999,
 990: 245.74000000000001,
 991: 238.31999999999999,
 992: 241.31,
 993: 241.11000000000001,
 994: 236.63999999999999,
 995: 233.69999999999999,
 996: 231.27000000000001,
 997: 239.69,
 998: 242.93000000000001,
 999: 239.31999999999999,
 ...}</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[64]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">max</span><span class="p">(</span><span class="n">pokemon</span><span class="p">)</span>
<span class="nb">min</span><span class="p">(</span><span class="n">pokemon</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[64]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&#39;Abomasnow&#39;</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[65]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">max</span><span class="p">(</span><span class="n">google</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[65]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>782.22000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[66]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">min</span><span class="p">(</span><span class="n">google</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[66]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>49.950000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="More-Series-Attributes">More <code>Series</code> Attributes<a class="anchor-link" href="#More-Series-Attributes">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[75]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[77]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">values</span>
<span class="n">google</span><span class="o">.</span><span class="n">values</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[77]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>array([  50.12,   54.1 ,   54.65, ...,  773.18,  771.61,  782.22])</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[79]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">index</span>
<span class="n">google</span><span class="o">.</span><span class="n">index</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[79]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>RangeIndex(start=0, stop=3012, step=1)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[81]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">dtype</span>
<span class="n">google</span><span class="o">.</span><span class="n">dtype</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[81]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>dtype(&#39;float64&#39;)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[83]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">is_unique</span>
<span class="n">google</span><span class="o">.</span><span class="n">is_unique</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[83]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>False</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[85]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">ndim</span>
<span class="n">google</span><span class="o">.</span><span class="n">ndim</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[85]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>1</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[87]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">shape</span>
<span class="n">google</span><span class="o">.</span><span class="n">shape</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[87]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>(3012,)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[89]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">size</span>
<span class="n">google</span><span class="o">.</span><span class="n">size</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[89]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3012</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[93]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">name</span> <span class="o">=</span> <span class="s2">&quot;Pocket Monsters&quot;</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[94]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[94]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0     Bulbasaur
1       Ivysaur
2      Venusaur
3    Charmander
4    Charmeleon
Name: Pocket Monsters, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-.sort_values()-Method">The <code>.sort_values()</code> Method<a class="anchor-link" href="#The-.sort_values()-Method">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[95]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[97]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">sort_values</span><span class="p">()</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[97]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>459    Abomasnow
62          Abra
358        Absol
616     Accelgor
680    Aegislash
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[100]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">ascending</span> <span class="o">=</span> <span class="bp">False</span><span class="p">)</span><span class="o">.</span><span class="n">tail</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[100]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>680    Aegislash
616     Accelgor
358        Absol
62          Abra
459    Abomasnow
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[104]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">ascending</span> <span class="o">=</span> <span class="bp">False</span><span class="p">)</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[104]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3011    782.22
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[106]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[106]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0        50.12
1        54.10
2        54.65
3        52.38
4        52.95
5        53.90
6        53.02
7        50.95
8        51.13
9        50.07
10       50.70
11       49.95
12       50.74
13       51.10
14       51.10
15       52.61
16       53.70
17       55.69
18       55.94
19       56.93
20       58.69
21       59.62
22       58.86
23       59.13
24       60.35
25       59.86
26       59.07
27       63.37
28       65.47
29       64.74
         ...  
2982    675.22
2983    668.26
2984    680.04
2985    684.11
2986    692.10
2987    699.21
2988    694.49
2989    697.77
2990    695.36
2991    705.63
2992    715.09
2993    720.64
2994    716.98
2995    720.95
2996    719.85
2997    733.78
2998    736.96
2999    741.19
3000    738.63
3001    742.74
3002    739.77
3003    738.42
3004    741.77
3005    745.91
3006    768.79
3007    772.88
3008    771.07
3009    773.18
3010    771.61
3011    782.22
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-inplace-Parameter">The <code>inplace</code> Parameter<a class="anchor-link" href="#The-inplace-Parameter">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[112]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[113]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[113]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    50.12
1    54.10
2    54.65
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[115]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span> <span class="o">=</span> <span class="n">google</span><span class="o">.</span><span class="n">sort_values</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[118]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[118]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>11    49.95
9     50.07
0     50.12
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[119]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">ascending</span> <span class="o">=</span> <span class="bp">False</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[120]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[120]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3011    782.22
2859    776.60
3009    773.18
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-.sort_index()-Method">The <code>.sort_index()</code> Method<a class="anchor-link" href="#The-.sort_index()-Method">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[129]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[133]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">ascending</span> <span class="o">=</span> <span class="bp">False</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[139]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[139]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    Bulbasaur
1      Ivysaur
2     Venusaur
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[138]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">sort_index</span><span class="p">(</span><span class="n">ascending</span> <span class="o">=</span> <span class="bp">True</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Python's-in-Keyword">Python's <code>in</code> Keyword<a class="anchor-link" href="#Python's-in-Keyword">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[149]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[151]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="mi">100</span> <span class="ow">in</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="mi">5</span><span class="p">]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[151]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>False</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[152]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[152]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    Bulbasaur
1      Ivysaur
2     Venusaur
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[155]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="mi">100</span> <span class="ow">in</span> <span class="n">pokemon</span>
<span class="mi">100</span> <span class="ow">in</span> <span class="n">pokemon</span><span class="o">.</span><span class="n">index</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[155]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>True</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[156]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">index</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[156]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>RangeIndex(start=0, stop=721, step=1)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[161]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="s2">&quot;Digimon&quot;</span> <span class="ow">in</span> <span class="n">pokemon</span><span class="o">.</span><span class="n">values</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[161]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>False</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Extract-Values-by-Index-Position">Extract Values by Index Position<a class="anchor-link" href="#Extract-Values-by-Index-Position">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[162]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[163]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[163]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    Bulbasaur
1      Ivysaur
2     Venusaur
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[172]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span>

<span class="n">pokemon</span><span class="p">[[</span><span class="mi">100</span><span class="p">,</span> <span class="mi">200</span><span class="p">,</span> <span class="mi">300</span><span class="p">]]</span>

<span class="n">pokemon</span><span class="p">[</span><span class="mi">50</span><span class="p">:</span><span class="mi">101</span><span class="p">]</span>

<span class="n">pokemon</span><span class="p">[:</span><span class="mi">50</span><span class="p">]</span>

<span class="n">pokemon</span><span class="p">[</span><span class="o">-</span><span class="mi">30</span><span class="p">:]</span>

<span class="n">pokemon</span><span class="p">[</span><span class="o">-</span><span class="mi">30</span> <span class="p">:</span> <span class="o">-</span><span class="mi">10</span><span class="p">]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[172]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>691     Clauncher
692     Clawitzer
693    Helioptile
694     Heliolisk
695        Tyrunt
696     Tyrantrum
697        Amaura
698       Aurorus
699       Sylveon
700      Hawlucha
701       Dedenne
702       Carbink
703         Goomy
704       Sliggoo
705        Goodra
706        Klefki
707      Phantump
708     Trevenant
709     Pumpkaboo
710     Gourgeist
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Extract-Values-by-Index-Label">Extract Values by Index Label<a class="anchor-link" href="#Extract-Values-by-Index-Label">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[176]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">index_col</span> <span class="o">=</span> <span class="s2">&quot;Pokemon&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">pokemon</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[176]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Pokemon
Bulbasaur    Grass
Ivysaur      Grass
Venusaur     Grass
Name: Type, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[178]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="p">[[</span><span class="mi">100</span><span class="p">,</span> <span class="mi">134</span><span class="p">]]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[178]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Pokemon
Electrode    Electric
Jolteon      Electric
Name: Type, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[185]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="p">[</span><span class="s2">&quot;Bulbasaur&quot;</span><span class="p">]</span>
<span class="n">pokemon</span><span class="p">[</span><span class="s2">&quot;Ditto&quot;</span><span class="p">]</span>
<span class="n">pokemon</span><span class="p">[[</span><span class="s2">&quot;Charizard&quot;</span><span class="p">,</span> <span class="s2">&quot;Jolteon&quot;</span><span class="p">]]</span>
<span class="n">pokemon</span><span class="p">[[</span><span class="s2">&quot;Blastoise&quot;</span><span class="p">,</span> <span class="s2">&quot;Venusaur&quot;</span><span class="p">,</span> <span class="s2">&quot;Meowth&quot;</span><span class="p">]]</span>

<span class="n">pokemon</span><span class="p">[[</span><span class="s2">&quot;Pikachu&quot;</span><span class="p">,</span> <span class="s2">&quot;Digimon&quot;</span><span class="p">]]</span>

<span class="n">pokemon</span><span class="p">[</span><span class="s2">&quot;Bulbasaur&quot;</span> <span class="p">:</span> <span class="s2">&quot;Pikachu&quot;</span><span class="p">]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[185]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Pokemon
Bulbasaur        Grass
Ivysaur          Grass
Venusaur         Grass
Charmander        Fire
Charmeleon        Fire
Charizard         Fire
Squirtle         Water
Wartortle        Water
Blastoise        Water
Caterpie           Bug
Metapod            Bug
Butterfree         Bug
Weedle             Bug
Kakuna             Bug
Beedrill           Bug
Pidgey          Normal
Pidgeotto       Normal
Pidgeot         Normal
Rattata         Normal
Raticate        Normal
Spearow         Normal
Fearow          Normal
Ekans           Poison
Arbok           Poison
Pikachu       Electric
Name: Type, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-.get()-Method-on-a-Series">The <code>.get()</code> Method on a <code>Series</code><a class="anchor-link" href="#The-.get()-Method-on-a-Series">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[192]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">index_col</span> <span class="o">=</span> <span class="s2">&quot;Pokemon&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">pokemon</span><span class="o">.</span><span class="n">sort_index</span><span class="p">(</span><span class="n">inplace</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">pokemon</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[192]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Pokemon
Abomasnow      Grass
Abra         Psychic
Absol           Dark
Name: Type, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[195]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">get</span><span class="p">(</span><span class="n">key</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Moltres&quot;</span><span class="p">,</span> <span class="s2">&quot;Meowth&quot;</span><span class="p">])</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[195]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Pokemon
Moltres      Fire
Meowth     Normal
Name: Type, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[199]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">get</span><span class="p">(</span><span class="n">key</span> <span class="o">=</span> <span class="s2">&quot;Charizard&quot;</span><span class="p">,</span> <span class="n">default</span> <span class="o">=</span> <span class="s2">&quot;This is not a Pokemon&quot;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[199]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&#39;Fire&#39;</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[202]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">get</span><span class="p">(</span><span class="n">key</span> <span class="o">=</span> <span class="s2">&quot;jksajk&quot;</span><span class="p">,</span> <span class="n">default</span> <span class="o">=</span> <span class="s2">&quot;This is not a Pokemon&quot;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[202]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&#39;This is not a Pokemon&#39;</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Math-Methods-on-Series-Objects">Math Methods on <code>Series</code> Objects<a class="anchor-link" href="#Math-Methods-on-Series-Objects">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[219]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[219]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    50.12
1    54.10
2    54.65
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[220]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">count</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[220]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3012</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[221]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="nb">len</span><span class="p">(</span><span class="n">google</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[221]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3012</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[222]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[222]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>1006942.0000000002</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[223]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[223]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>334.31009296148744</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[224]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span> <span class="o">/</span> <span class="n">google</span><span class="o">.</span><span class="n">count</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[224]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>334.31009296148744</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[225]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">std</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[225]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>173.18720477113106</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[226]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">min</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[226]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>49.950000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[227]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">max</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[227]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>782.22000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[228]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">median</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[228]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>283.315</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[229]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">mode</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[229]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    291.21
dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[230]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[230]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>count    3012.000000
mean      334.310093
std       173.187205
min        49.950000
25%       218.045000
50%       283.315000
75%       443.000000
max       782.220000
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-.idxmax()-and-.idxmin()-Methods">The <code>.idxmax()</code> and <code>.idxmin()</code> Methods<a class="anchor-link" href="#The-.idxmax()-and-.idxmin()-Methods">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[232]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[233]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">max</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[233]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>782.22000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[234]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">min</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[234]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>49.950000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[235]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">idxmax</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[235]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3011</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[236]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="p">[</span><span class="mi">3011</span><span class="p">]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[236]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>782.22000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[237]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">idxmin</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[237]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>11</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[238]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="p">[</span><span class="mi">11</span><span class="p">]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[238]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>49.950000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[239]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="p">[</span><span class="n">google</span><span class="o">.</span><span class="n">idxmin</span><span class="p">()]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[239]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>49.950000000000003</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-.value_counts()-Method">The <code>.value_counts()</code> Method<a class="anchor-link" href="#The-.value_counts()-Method">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[240]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">index_col</span> <span class="o">=</span> <span class="s2">&quot;Pokemon&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">pokemon</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[240]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Pokemon
Bulbasaur    Grass
Ivysaur      Grass
Venusaur     Grass
Name: Type, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[242]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[242]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>721</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[243]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">count</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[243]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>721</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[246]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon</span><span class="o">.</span><span class="n">value_counts</span><span class="p">(</span><span class="n">ascending</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[246]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Flying        3
Fairy        17
Steel        22
Ice          23
Ghost        23
Dragon       24
Fighting     25
Dark         28
Poison       28
Ground       30
Electric     36
Rock         41
Psychic      47
Fire         47
Bug          63
Grass        66
Normal       93
Water       105
Name: Type, dtype: int64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-.apply()-Method">The <code>.apply()</code> Method<a class="anchor-link" href="#The-.apply()-Method">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[255]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;google_stock_price.csv&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">google</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">6</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[255]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    50.12
1    54.10
2    54.65
3    52.38
4    52.95
5    53.90
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[256]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="k">def</span> <span class="nf">classify_performance</span><span class="p">(</span><span class="n">number</span><span class="p">):</span>
    <span class="k">if</span> <span class="n">number</span> <span class="o">&lt;</span> <span class="mi">300</span><span class="p">:</span>
        <span class="k">return</span> <span class="s2">&quot;OK&quot;</span>
    <span class="k">elif</span> <span class="n">number</span> <span class="o">&gt;=</span> <span class="mi">300</span> <span class="ow">and</span> <span class="n">number</span> <span class="o">&lt;</span> <span class="mi">650</span><span class="p">:</span>
        <span class="k">return</span> <span class="s2">&quot;Satisfactory&quot;</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="k">return</span> <span class="s2">&quot;Incredible!&quot;</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[258]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">apply</span><span class="p">(</span><span class="n">classify_performance</span><span class="p">)</span><span class="o">.</span><span class="n">tail</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[258]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>3007    Incredible!
3008    Incredible!
3009    Incredible!
3010    Incredible!
3011    Incredible!
Name: Stock Price, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[259]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">6</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[259]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    50.12
1    54.10
2    54.65
3    52.38
4    52.95
5    53.90
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[260]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">google</span><span class="o">.</span><span class="n">apply</span><span class="p">(</span><span class="k">lambda</span> <span class="n">stock_price</span> <span class="p">:</span> <span class="n">stock_price</span> <span class="o">+</span> <span class="mi">1</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[260]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0        51.12
1        55.10
2        55.65
3        53.38
4        53.95
5        54.90
6        54.02
7        51.95
8        52.13
9        51.07
10       51.70
11       50.95
12       51.74
13       52.10
14       52.10
15       53.61
16       54.70
17       56.69
18       56.94
19       57.93
20       59.69
21       60.62
22       59.86
23       60.13
24       61.35
25       60.86
26       60.07
27       64.37
28       66.47
29       65.74
         ...  
2982    676.22
2983    669.26
2984    681.04
2985    685.11
2986    693.10
2987    700.21
2988    695.49
2989    698.77
2990    696.36
2991    706.63
2992    716.09
2993    721.64
2994    717.98
2995    721.95
2996    720.85
2997    734.78
2998    737.96
2999    742.19
3000    739.63
3001    743.74
3002    740.77
3003    739.42
3004    742.77
3005    746.91
3006    769.79
3007    773.88
3008    772.07
3009    774.18
3010    772.61
3011    783.22
Name: Stock Price, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-.map()-Method">The <code>.map()</code> Method<a class="anchor-link" href="#The-.map()-Method">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[261]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon_names</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">pokemon_names</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[261]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0    Bulbasaur
1      Ivysaur
2     Venusaur
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[262]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon_types</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">index_col</span> <span class="o">=</span> <span class="s2">&quot;Pokemon&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">pokemon_types</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[262]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Pokemon
Bulbasaur    Grass
Ivysaur      Grass
Venusaur     Grass
Name: Type, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[263]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon_names</span><span class="o">.</span><span class="n">map</span><span class="p">(</span><span class="n">pokemon_types</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[263]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0         Grass
1         Grass
2         Grass
3          Fire
4          Fire
5          Fire
6         Water
7         Water
8         Water
9           Bug
10          Bug
11          Bug
12          Bug
13          Bug
14          Bug
15       Normal
16       Normal
17       Normal
18       Normal
19       Normal
20       Normal
21       Normal
22       Poison
23       Poison
24     Electric
25     Electric
26       Ground
27       Ground
28       Poison
29       Poison
         ...   
691       Water
692       Water
693    Electric
694    Electric
695        Rock
696        Rock
697        Rock
698        Rock
699       Fairy
700    Fighting
701    Electric
702        Rock
703      Dragon
704      Dragon
705      Dragon
706       Steel
707       Ghost
708       Ghost
709       Ghost
710       Ghost
711         Ice
712         Ice
713      Flying
714      Flying
715       Fairy
716        Dark
717      Dragon
718        Rock
719     Psychic
720        Fire
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[264]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon_names</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">usecols</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Pokemon&quot;</span><span class="p">],</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span>
<span class="n">pokemon_types</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;pokemon.csv&quot;</span><span class="p">,</span> <span class="n">index_col</span> <span class="o">=</span> <span class="s2">&quot;Pokemon&quot;</span><span class="p">,</span> <span class="n">squeeze</span> <span class="o">=</span> <span class="bp">True</span><span class="p">)</span><span class="o">.</span><span class="n">to_dict</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[265]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon_names</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[265]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0     Bulbasaur
1       Ivysaur
2      Venusaur
3    Charmander
4    Charmeleon
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[266]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon_types</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[266]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>{&#39;Abomasnow&#39;: &#39;Grass&#39;,
 &#39;Abra&#39;: &#39;Psychic&#39;,
 &#39;Absol&#39;: &#39;Dark&#39;,
 &#39;Accelgor&#39;: &#39;Bug&#39;,
 &#39;Aegislash&#39;: &#39;Steel&#39;,
 &#39;Aerodactyl&#39;: &#39;Rock&#39;,
 &#39;Aggron&#39;: &#39;Steel&#39;,
 &#39;Aipom&#39;: &#39;Normal&#39;,
 &#39;Alakazam&#39;: &#39;Psychic&#39;,
 &#39;Alomomola&#39;: &#39;Water&#39;,
 &#39;Altaria&#39;: &#39;Dragon&#39;,
 &#39;Amaura&#39;: &#39;Rock&#39;,
 &#39;Ambipom&#39;: &#39;Normal&#39;,
 &#39;Amoonguss&#39;: &#39;Grass&#39;,
 &#39;Ampharos&#39;: &#39;Electric&#39;,
 &#39;Anorith&#39;: &#39;Rock&#39;,
 &#39;Arbok&#39;: &#39;Poison&#39;,
 &#39;Arcanine&#39;: &#39;Fire&#39;,
 &#39;Arceus&#39;: &#39;Normal&#39;,
 &#39;Archen&#39;: &#39;Rock&#39;,
 &#39;Archeops&#39;: &#39;Rock&#39;,
 &#39;Ariados&#39;: &#39;Bug&#39;,
 &#39;Armaldo&#39;: &#39;Rock&#39;,
 &#39;Aromatisse&#39;: &#39;Fairy&#39;,
 &#39;Aron&#39;: &#39;Steel&#39;,
 &#39;Articuno&#39;: &#39;Ice&#39;,
 &#39;Audino&#39;: &#39;Normal&#39;,
 &#39;Aurorus&#39;: &#39;Rock&#39;,
 &#39;Avalugg&#39;: &#39;Ice&#39;,
 &#39;Axew&#39;: &#39;Dragon&#39;,
 &#39;Azelf&#39;: &#39;Psychic&#39;,
 &#39;Azumarill&#39;: &#39;Water&#39;,
 &#39;Azurill&#39;: &#39;Normal&#39;,
 &#39;Bagon&#39;: &#39;Dragon&#39;,
 &#39;Baltoy&#39;: &#39;Ground&#39;,
 &#39;Banette&#39;: &#39;Ghost&#39;,
 &#39;Barbaracle&#39;: &#39;Rock&#39;,
 &#39;Barboach&#39;: &#39;Water&#39;,
 &#39;Basculin&#39;: &#39;Water&#39;,
 &#39;Bastiodon&#39;: &#39;Rock&#39;,
 &#39;Bayleef&#39;: &#39;Grass&#39;,
 &#39;Beartic&#39;: &#39;Ice&#39;,
 &#39;Beautifly&#39;: &#39;Bug&#39;,
 &#39;Beedrill&#39;: &#39;Bug&#39;,
 &#39;Beheeyem&#39;: &#39;Psychic&#39;,
 &#39;Beldum&#39;: &#39;Steel&#39;,
 &#39;Bellossom&#39;: &#39;Grass&#39;,
 &#39;Bellsprout&#39;: &#39;Grass&#39;,
 &#39;Bergmite&#39;: &#39;Ice&#39;,
 &#39;Bibarel&#39;: &#39;Normal&#39;,
 &#39;Bidoof&#39;: &#39;Normal&#39;,
 &#39;Binacle&#39;: &#39;Rock&#39;,
 &#39;Bisharp&#39;: &#39;Dark&#39;,
 &#39;Blastoise&#39;: &#39;Water&#39;,
 &#39;Blaziken&#39;: &#39;Fire&#39;,
 &#39;Blissey&#39;: &#39;Normal&#39;,
 &#39;Blitzle&#39;: &#39;Electric&#39;,
 &#39;Boldore&#39;: &#39;Rock&#39;,
 &#39;Bonsly&#39;: &#39;Rock&#39;,
 &#39;Bouffalant&#39;: &#39;Normal&#39;,
 &#39;Braixen&#39;: &#39;Fire&#39;,
 &#39;Braviary&#39;: &#39;Normal&#39;,
 &#39;Breloom&#39;: &#39;Grass&#39;,
 &#39;Bronzong&#39;: &#39;Steel&#39;,
 &#39;Bronzor&#39;: &#39;Steel&#39;,
 &#39;Budew&#39;: &#39;Grass&#39;,
 &#39;Buizel&#39;: &#39;Water&#39;,
 &#39;Bulbasaur&#39;: &#39;Grass&#39;,
 &#39;Buneary&#39;: &#39;Normal&#39;,
 &#39;Bunnelby&#39;: &#39;Normal&#39;,
 &#39;Burmy&#39;: &#39;Bug&#39;,
 &#39;Butterfree&#39;: &#39;Bug&#39;,
 &#39;Cacnea&#39;: &#39;Grass&#39;,
 &#39;Cacturne&#39;: &#39;Grass&#39;,
 &#39;Camerupt&#39;: &#39;Fire&#39;,
 &#39;Carbink&#39;: &#39;Rock&#39;,
 &#39;Carnivine&#39;: &#39;Grass&#39;,
 &#39;Carracosta&#39;: &#39;Water&#39;,
 &#39;Carvanha&#39;: &#39;Water&#39;,
 &#39;Cascoon&#39;: &#39;Bug&#39;,
 &#39;Castform&#39;: &#39;Normal&#39;,
 &#39;Caterpie&#39;: &#39;Bug&#39;,
 &#39;Celebi&#39;: &#39;Psychic&#39;,
 &#39;Chandelure&#39;: &#39;Ghost&#39;,
 &#39;Chansey&#39;: &#39;Normal&#39;,
 &#39;Charizard&#39;: &#39;Fire&#39;,
 &#39;Charmander&#39;: &#39;Fire&#39;,
 &#39;Charmeleon&#39;: &#39;Fire&#39;,
 &#39;Chatot&#39;: &#39;Normal&#39;,
 &#39;Cherrim&#39;: &#39;Grass&#39;,
 &#39;Cherubi&#39;: &#39;Grass&#39;,
 &#39;Chesnaught&#39;: &#39;Grass&#39;,
 &#39;Chespin&#39;: &#39;Grass&#39;,
 &#39;Chikorita&#39;: &#39;Grass&#39;,
 &#39;Chimchar&#39;: &#39;Fire&#39;,
 &#39;Chimecho&#39;: &#39;Psychic&#39;,
 &#39;Chinchou&#39;: &#39;Water&#39;,
 &#39;Chingling&#39;: &#39;Psychic&#39;,
 &#39;Cinccino&#39;: &#39;Normal&#39;,
 &#39;Clamperl&#39;: &#39;Water&#39;,
 &#39;Clauncher&#39;: &#39;Water&#39;,
 &#39;Clawitzer&#39;: &#39;Water&#39;,
 &#39;Claydol&#39;: &#39;Ground&#39;,
 &#39;Clefable&#39;: &#39;Fairy&#39;,
 &#39;Clefairy&#39;: &#39;Fairy&#39;,
 &#39;Cleffa&#39;: &#39;Fairy&#39;,
 &#39;Cloyster&#39;: &#39;Water&#39;,
 &#39;Cobalion&#39;: &#39;Steel&#39;,
 &#39;Cofagrigus&#39;: &#39;Ghost&#39;,
 &#39;Combee&#39;: &#39;Bug&#39;,
 &#39;Combusken&#39;: &#39;Fire&#39;,
 &#39;Conkeldurr&#39;: &#39;Fighting&#39;,
 &#39;Corphish&#39;: &#39;Water&#39;,
 &#39;Corsola&#39;: &#39;Water&#39;,
 &#39;Cottonee&#39;: &#39;Grass&#39;,
 &#39;Cradily&#39;: &#39;Rock&#39;,
 &#39;Cranidos&#39;: &#39;Rock&#39;,
 &#39;Crawdaunt&#39;: &#39;Water&#39;,
 &#39;Cresselia&#39;: &#39;Psychic&#39;,
 &#39;Croagunk&#39;: &#39;Poison&#39;,
 &#39;Crobat&#39;: &#39;Poison&#39;,
 &#39;Croconaw&#39;: &#39;Water&#39;,
 &#39;Crustle&#39;: &#39;Bug&#39;,
 &#39;Cryogonal&#39;: &#39;Ice&#39;,
 &#39;Cubchoo&#39;: &#39;Ice&#39;,
 &#39;Cubone&#39;: &#39;Ground&#39;,
 &#39;Cyndaquil&#39;: &#39;Fire&#39;,
 &#39;Darkrai&#39;: &#39;Dark&#39;,
 &#39;Darmanitan&#39;: &#39;Fire&#39;,
 &#39;Darumaka&#39;: &#39;Fire&#39;,
 &#39;Dedenne&#39;: &#39;Electric&#39;,
 &#39;Deerling&#39;: &#39;Normal&#39;,
 &#39;Deino&#39;: &#39;Dark&#39;,
 &#39;Delcatty&#39;: &#39;Normal&#39;,
 &#39;Delibird&#39;: &#39;Ice&#39;,
 &#39;Delphox&#39;: &#39;Fire&#39;,
 &#39;Deoxys&#39;: &#39;Psychic&#39;,
 &#39;Dewgong&#39;: &#39;Water&#39;,
 &#39;Dewott&#39;: &#39;Water&#39;,
 &#39;Dialga&#39;: &#39;Steel&#39;,
 &#39;Diancie&#39;: &#39;Rock&#39;,
 &#39;Diggersby&#39;: &#39;Normal&#39;,
 &#39;Diglett&#39;: &#39;Ground&#39;,
 &#39;Ditto&#39;: &#39;Normal&#39;,
 &#39;Dodrio&#39;: &#39;Normal&#39;,
 &#39;Doduo&#39;: &#39;Normal&#39;,
 &#39;Donphan&#39;: &#39;Ground&#39;,
 &#39;Doublade&#39;: &#39;Steel&#39;,
 &#39;Dragalge&#39;: &#39;Poison&#39;,
 &#39;Dragonair&#39;: &#39;Dragon&#39;,
 &#39;Dragonite&#39;: &#39;Dragon&#39;,
 &#39;Drapion&#39;: &#39;Poison&#39;,
 &#39;Dratini&#39;: &#39;Dragon&#39;,
 &#39;Drifblim&#39;: &#39;Ghost&#39;,
 &#39;Drifloon&#39;: &#39;Ghost&#39;,
 &#39;Drilbur&#39;: &#39;Ground&#39;,
 &#39;Drowzee&#39;: &#39;Psychic&#39;,
 &#39;Druddigon&#39;: &#39;Dragon&#39;,
 &#39;Ducklett&#39;: &#39;Water&#39;,
 &#39;Dugtrio&#39;: &#39;Ground&#39;,
 &#39;Dunsparce&#39;: &#39;Normal&#39;,
 &#39;Duosion&#39;: &#39;Psychic&#39;,
 &#39;Durant&#39;: &#39;Bug&#39;,
 &#39;Dusclops&#39;: &#39;Ghost&#39;,
 &#39;Dusknoir&#39;: &#39;Ghost&#39;,
 &#39;Duskull&#39;: &#39;Ghost&#39;,
 &#39;Dustox&#39;: &#39;Bug&#39;,
 &#39;Dwebble&#39;: &#39;Bug&#39;,
 &#39;Eelektrik&#39;: &#39;Electric&#39;,
 &#39;Eelektross&#39;: &#39;Electric&#39;,
 &#39;Eevee&#39;: &#39;Normal&#39;,
 &#39;Ekans&#39;: &#39;Poison&#39;,
 &#39;Electabuzz&#39;: &#39;Electric&#39;,
 &#39;Electivire&#39;: &#39;Electric&#39;,
 &#39;Electrike&#39;: &#39;Electric&#39;,
 &#39;Electrode&#39;: &#39;Electric&#39;,
 &#39;Elekid&#39;: &#39;Electric&#39;,
 &#39;Elgyem&#39;: &#39;Psychic&#39;,
 &#39;Emboar&#39;: &#39;Fire&#39;,
 &#39;Emolga&#39;: &#39;Electric&#39;,
 &#39;Empoleon&#39;: &#39;Water&#39;,
 &#39;Entei&#39;: &#39;Fire&#39;,
 &#39;Escavalier&#39;: &#39;Bug&#39;,
 &#39;Espeon&#39;: &#39;Psychic&#39;,
 &#39;Espurr&#39;: &#39;Psychic&#39;,
 &#39;Excadrill&#39;: &#39;Ground&#39;,
 &#39;Exeggcute&#39;: &#39;Grass&#39;,
 &#39;Exeggutor&#39;: &#39;Grass&#39;,
 &#39;Exploud&#39;: &#39;Normal&#39;,
 &#34;Farfetch&#39;d&#34;: &#39;Normal&#39;,
 &#39;Fearow&#39;: &#39;Normal&#39;,
 &#39;Feebas&#39;: &#39;Water&#39;,
 &#39;Fennekin&#39;: &#39;Fire&#39;,
 &#39;Feraligatr&#39;: &#39;Water&#39;,
 &#39;Ferroseed&#39;: &#39;Grass&#39;,
 &#39;Ferrothorn&#39;: &#39;Grass&#39;,
 &#39;Finneon&#39;: &#39;Water&#39;,
 &#39;Flaaffy&#39;: &#39;Electric&#39;,
 &#39;Flabébé&#39;: &#39;Fairy&#39;,
 &#39;Flareon&#39;: &#39;Fire&#39;,
 &#39;Fletchinder&#39;: &#39;Fire&#39;,
 &#39;Fletchling&#39;: &#39;Normal&#39;,
 &#39;Floatzel&#39;: &#39;Water&#39;,
 &#39;Floette&#39;: &#39;Fairy&#39;,
 &#39;Florges&#39;: &#39;Fairy&#39;,
 &#39;Flygon&#39;: &#39;Ground&#39;,
 &#39;Foongus&#39;: &#39;Grass&#39;,
 &#39;Forretress&#39;: &#39;Bug&#39;,
 &#39;Fraxure&#39;: &#39;Dragon&#39;,
 &#39;Frillish&#39;: &#39;Water&#39;,
 &#39;Froakie&#39;: &#39;Water&#39;,
 &#39;Frogadier&#39;: &#39;Water&#39;,
 &#39;Froslass&#39;: &#39;Ice&#39;,
 &#39;Furfrou&#39;: &#39;Normal&#39;,
 &#39;Furret&#39;: &#39;Normal&#39;,
 &#39;Gabite&#39;: &#39;Dragon&#39;,
 &#39;Gallade&#39;: &#39;Psychic&#39;,
 &#39;Galvantula&#39;: &#39;Bug&#39;,
 &#39;Garbodor&#39;: &#39;Poison&#39;,
 &#39;Garchomp&#39;: &#39;Dragon&#39;,
 &#39;Gardevoir&#39;: &#39;Psychic&#39;,
 &#39;Gastly&#39;: &#39;Ghost&#39;,
 &#39;Gastrodon&#39;: &#39;Water&#39;,
 &#39;Genesect&#39;: &#39;Bug&#39;,
 &#39;Gengar&#39;: &#39;Ghost&#39;,
 &#39;Geodude&#39;: &#39;Rock&#39;,
 &#39;Gible&#39;: &#39;Dragon&#39;,
 &#39;Gigalith&#39;: &#39;Rock&#39;,
 &#39;Girafarig&#39;: &#39;Normal&#39;,
 &#39;Giratina&#39;: &#39;Ghost&#39;,
 &#39;Glaceon&#39;: &#39;Ice&#39;,
 &#39;Glalie&#39;: &#39;Ice&#39;,
 &#39;Glameow&#39;: &#39;Normal&#39;,
 &#39;Gligar&#39;: &#39;Ground&#39;,
 &#39;Gliscor&#39;: &#39;Ground&#39;,
 &#39;Gloom&#39;: &#39;Grass&#39;,
 &#39;Gogoat&#39;: &#39;Grass&#39;,
 &#39;Golbat&#39;: &#39;Poison&#39;,
 &#39;Goldeen&#39;: &#39;Water&#39;,
 &#39;Golduck&#39;: &#39;Water&#39;,
 &#39;Golem&#39;: &#39;Rock&#39;,
 &#39;Golett&#39;: &#39;Ground&#39;,
 &#39;Golurk&#39;: &#39;Ground&#39;,
 &#39;Goodra&#39;: &#39;Dragon&#39;,
 &#39;Goomy&#39;: &#39;Dragon&#39;,
 &#39;Gorebyss&#39;: &#39;Water&#39;,
 &#39;Gothita&#39;: &#39;Psychic&#39;,
 &#39;Gothitelle&#39;: &#39;Psychic&#39;,
 &#39;Gothorita&#39;: &#39;Psychic&#39;,
 &#39;Gourgeist&#39;: &#39;Ghost&#39;,
 &#39;Granbull&#39;: &#39;Fairy&#39;,
 &#39;Graveler&#39;: &#39;Rock&#39;,
 &#39;Greninja&#39;: &#39;Water&#39;,
 &#39;Grimer&#39;: &#39;Poison&#39;,
 &#39;Grotle&#39;: &#39;Grass&#39;,
 &#39;Groudon&#39;: &#39;Ground&#39;,
 &#39;Grovyle&#39;: &#39;Grass&#39;,
 &#39;Growlithe&#39;: &#39;Fire&#39;,
 &#39;Grumpig&#39;: &#39;Psychic&#39;,
 &#39;Gulpin&#39;: &#39;Poison&#39;,
 &#39;Gurdurr&#39;: &#39;Fighting&#39;,
 &#39;Gyarados&#39;: &#39;Water&#39;,
 &#39;Happiny&#39;: &#39;Normal&#39;,
 &#39;Hariyama&#39;: &#39;Fighting&#39;,
 &#39;Haunter&#39;: &#39;Ghost&#39;,
 &#39;Hawlucha&#39;: &#39;Fighting&#39;,
 &#39;Haxorus&#39;: &#39;Dragon&#39;,
 &#39;Heatmor&#39;: &#39;Fire&#39;,
 &#39;Heatran&#39;: &#39;Fire&#39;,
 &#39;Heliolisk&#39;: &#39;Electric&#39;,
 &#39;Helioptile&#39;: &#39;Electric&#39;,
 &#39;Heracross&#39;: &#39;Bug&#39;,
 &#39;Herdier&#39;: &#39;Normal&#39;,
 &#39;Hippopotas&#39;: &#39;Ground&#39;,
 &#39;Hippowdon&#39;: &#39;Ground&#39;,
 &#39;Hitmonchan&#39;: &#39;Fighting&#39;,
 &#39;Hitmonlee&#39;: &#39;Fighting&#39;,
 &#39;Hitmontop&#39;: &#39;Fighting&#39;,
 &#39;Ho-oh&#39;: &#39;Fire&#39;,
 &#39;Honchkrow&#39;: &#39;Dark&#39;,
 &#39;Honedge&#39;: &#39;Steel&#39;,
 &#39;Hoopa&#39;: &#39;Psychic&#39;,
 &#39;Hoothoot&#39;: &#39;Normal&#39;,
 &#39;Hoppip&#39;: &#39;Grass&#39;,
 &#39;Horsea&#39;: &#39;Water&#39;,
 &#39;Houndoom&#39;: &#39;Dark&#39;,
 &#39;Houndour&#39;: &#39;Dark&#39;,
 &#39;Huntail&#39;: &#39;Water&#39;,
 &#39;Hydreigon&#39;: &#39;Dark&#39;,
 &#39;Hypno&#39;: &#39;Psychic&#39;,
 &#39;Igglybuff&#39;: &#39;Normal&#39;,
 &#39;Illumise&#39;: &#39;Bug&#39;,
 &#39;Infernape&#39;: &#39;Fire&#39;,
 &#39;Inkay&#39;: &#39;Dark&#39;,
 &#39;Ivysaur&#39;: &#39;Grass&#39;,
 &#39;Jellicent&#39;: &#39;Water&#39;,
 &#39;Jigglypuff&#39;: &#39;Normal&#39;,
 &#39;Jirachi&#39;: &#39;Steel&#39;,
 &#39;Jolteon&#39;: &#39;Electric&#39;,
 &#39;Joltik&#39;: &#39;Bug&#39;,
 &#39;Jumpluff&#39;: &#39;Grass&#39;,
 &#39;Jynx&#39;: &#39;Ice&#39;,
 &#39;Kabuto&#39;: &#39;Rock&#39;,
 &#39;Kabutops&#39;: &#39;Rock&#39;,
 &#39;Kadabra&#39;: &#39;Psychic&#39;,
 &#39;Kakuna&#39;: &#39;Bug&#39;,
 &#39;Kangaskhan&#39;: &#39;Normal&#39;,
 &#39;Karrablast&#39;: &#39;Bug&#39;,
 &#39;Kecleon&#39;: &#39;Normal&#39;,
 &#39;Keldeo&#39;: &#39;Water&#39;,
 &#39;Kingdra&#39;: &#39;Water&#39;,
 &#39;Kingler&#39;: &#39;Water&#39;,
 &#39;Kirlia&#39;: &#39;Psychic&#39;,
 &#39;Klang&#39;: &#39;Steel&#39;,
 &#39;Klefki&#39;: &#39;Steel&#39;,
 &#39;Klink&#39;: &#39;Steel&#39;,
 &#39;Klinklang&#39;: &#39;Steel&#39;,
 &#39;Koffing&#39;: &#39;Poison&#39;,
 &#39;Krabby&#39;: &#39;Water&#39;,
 &#39;Kricketot&#39;: &#39;Bug&#39;,
 &#39;Kricketune&#39;: &#39;Bug&#39;,
 &#39;Krokorok&#39;: &#39;Ground&#39;,
 &#39;Krookodile&#39;: &#39;Ground&#39;,
 &#39;Kyogre&#39;: &#39;Water&#39;,
 &#39;Kyurem&#39;: &#39;Dragon&#39;,
 &#39;Lairon&#39;: &#39;Steel&#39;,
 &#39;Lampent&#39;: &#39;Ghost&#39;,
 &#39;Landorus&#39;: &#39;Ground&#39;,
 &#39;Lanturn&#39;: &#39;Water&#39;,
 &#39;Lapras&#39;: &#39;Water&#39;,
 &#39;Larvesta&#39;: &#39;Bug&#39;,
 &#39;Larvitar&#39;: &#39;Rock&#39;,
 &#39;Latias&#39;: &#39;Dragon&#39;,
 &#39;Latios&#39;: &#39;Dragon&#39;,
 &#39;Leafeon&#39;: &#39;Grass&#39;,
 &#39;Leavanny&#39;: &#39;Bug&#39;,
 &#39;Ledian&#39;: &#39;Bug&#39;,
 &#39;Ledyba&#39;: &#39;Bug&#39;,
 &#39;Lickilicky&#39;: &#39;Normal&#39;,
 &#39;Lickitung&#39;: &#39;Normal&#39;,
 &#39;Liepard&#39;: &#39;Dark&#39;,
 &#39;Lileep&#39;: &#39;Rock&#39;,
 &#39;Lilligant&#39;: &#39;Grass&#39;,
 &#39;Lillipup&#39;: &#39;Normal&#39;,
 &#39;Linoone&#39;: &#39;Normal&#39;,
 &#39;Litleo&#39;: &#39;Fire&#39;,
 &#39;Litwick&#39;: &#39;Ghost&#39;,
 &#39;Lombre&#39;: &#39;Water&#39;,
 &#39;Lopunny&#39;: &#39;Normal&#39;,
 &#39;Lotad&#39;: &#39;Water&#39;,
 &#39;Loudred&#39;: &#39;Normal&#39;,
 &#39;Lucario&#39;: &#39;Fighting&#39;,
 &#39;Ludicolo&#39;: &#39;Water&#39;,
 &#39;Lugia&#39;: &#39;Psychic&#39;,
 &#39;Lumineon&#39;: &#39;Water&#39;,
 &#39;Lunatone&#39;: &#39;Rock&#39;,
 &#39;Luvdisc&#39;: &#39;Water&#39;,
 &#39;Luxio&#39;: &#39;Electric&#39;,
 &#39;Luxray&#39;: &#39;Electric&#39;,
 &#39;Machamp&#39;: &#39;Fighting&#39;,
 &#39;Machoke&#39;: &#39;Fighting&#39;,
 &#39;Machop&#39;: &#39;Fighting&#39;,
 &#39;Magby&#39;: &#39;Fire&#39;,
 &#39;Magcargo&#39;: &#39;Fire&#39;,
 &#39;Magikarp&#39;: &#39;Water&#39;,
 &#39;Magmar&#39;: &#39;Fire&#39;,
 &#39;Magmortar&#39;: &#39;Fire&#39;,
 &#39;Magnemite&#39;: &#39;Electric&#39;,
 &#39;Magneton&#39;: &#39;Electric&#39;,
 &#39;Magnezone&#39;: &#39;Electric&#39;,
 &#39;Makuhita&#39;: &#39;Fighting&#39;,
 &#39;Malamar&#39;: &#39;Dark&#39;,
 &#39;Mamoswine&#39;: &#39;Ice&#39;,
 &#39;Manaphy&#39;: &#39;Water&#39;,
 &#39;Mandibuzz&#39;: &#39;Dark&#39;,
 &#39;Manectric&#39;: &#39;Electric&#39;,
 &#39;Mankey&#39;: &#39;Fighting&#39;,
 &#39;Mantine&#39;: &#39;Water&#39;,
 &#39;Mantyke&#39;: &#39;Water&#39;,
 &#39;Maractus&#39;: &#39;Grass&#39;,
 &#39;Mareep&#39;: &#39;Electric&#39;,
 &#39;Marill&#39;: &#39;Water&#39;,
 &#39;Marowak&#39;: &#39;Ground&#39;,
 &#39;Marshtomp&#39;: &#39;Water&#39;,
 &#39;Masquerain&#39;: &#39;Bug&#39;,
 &#39;Mawile&#39;: &#39;Steel&#39;,
 &#39;Medicham&#39;: &#39;Fighting&#39;,
 &#39;Meditite&#39;: &#39;Fighting&#39;,
 &#39;Meganium&#39;: &#39;Grass&#39;,
 &#39;Meloetta&#39;: &#39;Normal&#39;,
 &#39;Meowstic&#39;: &#39;Psychic&#39;,
 &#39;Meowth&#39;: &#39;Normal&#39;,
 &#39;Mesprit&#39;: &#39;Psychic&#39;,
 &#39;Metagross&#39;: &#39;Steel&#39;,
 &#39;Metang&#39;: &#39;Steel&#39;,
 &#39;Metapod&#39;: &#39;Bug&#39;,
 &#39;Mew&#39;: &#39;Psychic&#39;,
 &#39;Mewtwo&#39;: &#39;Psychic&#39;,
 &#39;Mienfoo&#39;: &#39;Fighting&#39;,
 &#39;Mienshao&#39;: &#39;Fighting&#39;,
 &#39;Mightyena&#39;: &#39;Dark&#39;,
 &#39;Milotic&#39;: &#39;Water&#39;,
 &#39;Miltank&#39;: &#39;Normal&#39;,
 &#39;Mime Jr.&#39;: &#39;Psychic&#39;,
 &#39;Minccino&#39;: &#39;Normal&#39;,
 &#39;Minun&#39;: &#39;Electric&#39;,
 &#39;Misdreavus&#39;: &#39;Ghost&#39;,
 &#39;Mismagius&#39;: &#39;Ghost&#39;,
 &#39;Moltres&#39;: &#39;Fire&#39;,
 &#39;Monferno&#39;: &#39;Fire&#39;,
 &#39;Mothim&#39;: &#39;Bug&#39;,
 &#39;Mr. Mime&#39;: &#39;Psychic&#39;,
 &#39;Mudkip&#39;: &#39;Water&#39;,
 &#39;Muk&#39;: &#39;Poison&#39;,
 &#39;Munchlax&#39;: &#39;Normal&#39;,
 &#39;Munna&#39;: &#39;Psychic&#39;,
 &#39;Murkrow&#39;: &#39;Dark&#39;,
 &#39;Musharna&#39;: &#39;Psychic&#39;,
 &#39;Natu&#39;: &#39;Psychic&#39;,
 &#39;Nidoking&#39;: &#39;Poison&#39;,
 &#39;Nidoqueen&#39;: &#39;Poison&#39;,
 &#39;Nidoran&#39;: &#39;Poison&#39;,
 &#39;Nidoran♂&#39;: &#39;Poison&#39;,
 &#39;Nidorina&#39;: &#39;Poison&#39;,
 &#39;Nidorino&#39;: &#39;Poison&#39;,
 &#39;Nincada&#39;: &#39;Bug&#39;,
 &#39;Ninetales&#39;: &#39;Fire&#39;,
 &#39;Ninjask&#39;: &#39;Bug&#39;,
 &#39;Noctowl&#39;: &#39;Normal&#39;,
 &#39;Noibat&#39;: &#39;Flying&#39;,
 &#39;Noivern&#39;: &#39;Flying&#39;,
 &#39;Nosepass&#39;: &#39;Rock&#39;,
 &#39;Numel&#39;: &#39;Fire&#39;,
 &#39;Nuzleaf&#39;: &#39;Grass&#39;,
 &#39;Octillery&#39;: &#39;Water&#39;,
 &#39;Oddish&#39;: &#39;Grass&#39;,
 &#39;Omanyte&#39;: &#39;Rock&#39;,
 &#39;Omastar&#39;: &#39;Rock&#39;,
 &#39;Onix&#39;: &#39;Rock&#39;,
 &#39;Oshawott&#39;: &#39;Water&#39;,
 &#39;Pachirisu&#39;: &#39;Electric&#39;,
 &#39;Palkia&#39;: &#39;Water&#39;,
 &#39;Palpitoad&#39;: &#39;Water&#39;,
 &#39;Pancham&#39;: &#39;Fighting&#39;,
 &#39;Pangoro&#39;: &#39;Fighting&#39;,
 &#39;Panpour&#39;: &#39;Water&#39;,
 &#39;Pansage&#39;: &#39;Grass&#39;,
 &#39;Pansear&#39;: &#39;Fire&#39;,
 &#39;Paras&#39;: &#39;Bug&#39;,
 &#39;Parasect&#39;: &#39;Bug&#39;,
 &#39;Patrat&#39;: &#39;Normal&#39;,
 &#39;Pawniard&#39;: &#39;Dark&#39;,
 &#39;Pelipper&#39;: &#39;Water&#39;,
 &#39;Persian&#39;: &#39;Normal&#39;,
 &#39;Petilil&#39;: &#39;Grass&#39;,
 &#39;Phanpy&#39;: &#39;Ground&#39;,
 &#39;Phantump&#39;: &#39;Ghost&#39;,
 &#39;Phione&#39;: &#39;Water&#39;,
 &#39;Pichu&#39;: &#39;Electric&#39;,
 &#39;Pidgeot&#39;: &#39;Normal&#39;,
 &#39;Pidgeotto&#39;: &#39;Normal&#39;,
 &#39;Pidgey&#39;: &#39;Normal&#39;,
 &#39;Pidove&#39;: &#39;Normal&#39;,
 &#39;Pignite&#39;: &#39;Fire&#39;,
 &#39;Pikachu&#39;: &#39;Electric&#39;,
 &#39;Piloswine&#39;: &#39;Ice&#39;,
 &#39;Pineco&#39;: &#39;Bug&#39;,
 &#39;Pinsir&#39;: &#39;Bug&#39;,
 &#39;Piplup&#39;: &#39;Water&#39;,
 &#39;Plusle&#39;: &#39;Electric&#39;,
 &#39;Politoed&#39;: &#39;Water&#39;,
 &#39;Poliwag&#39;: &#39;Water&#39;,
 &#39;Poliwhirl&#39;: &#39;Water&#39;,
 &#39;Poliwrath&#39;: &#39;Water&#39;,
 &#39;Ponyta&#39;: &#39;Fire&#39;,
 &#39;Poochyena&#39;: &#39;Dark&#39;,
 &#39;Porygon&#39;: &#39;Normal&#39;,
 &#39;Porygon-Z&#39;: &#39;Normal&#39;,
 &#39;Porygon2&#39;: &#39;Normal&#39;,
 &#39;Primeape&#39;: &#39;Fighting&#39;,
 &#39;Prinplup&#39;: &#39;Water&#39;,
 &#39;Probopass&#39;: &#39;Rock&#39;,
 &#39;Psyduck&#39;: &#39;Water&#39;,
 &#39;Pumpkaboo&#39;: &#39;Ghost&#39;,
 &#39;Pupitar&#39;: &#39;Rock&#39;,
 &#39;Purrloin&#39;: &#39;Dark&#39;,
 &#39;Purugly&#39;: &#39;Normal&#39;,
 &#39;Pyroar&#39;: &#39;Fire&#39;,
 &#39;Quagsire&#39;: &#39;Water&#39;,
 &#39;Quilava&#39;: &#39;Fire&#39;,
 &#39;Quilladin&#39;: &#39;Grass&#39;,
 &#39;Qwilfish&#39;: &#39;Water&#39;,
 &#39;Raichu&#39;: &#39;Electric&#39;,
 &#39;Raikou&#39;: &#39;Electric&#39;,
 &#39;Ralts&#39;: &#39;Psychic&#39;,
 &#39;Rampardos&#39;: &#39;Rock&#39;,
 &#39;Rapidash&#39;: &#39;Fire&#39;,
 &#39;Raticate&#39;: &#39;Normal&#39;,
 &#39;Rattata&#39;: &#39;Normal&#39;,
 &#39;Rayquaza&#39;: &#39;Dragon&#39;,
 &#39;Regice&#39;: &#39;Ice&#39;,
 &#39;Regigigas&#39;: &#39;Normal&#39;,
 &#39;Regirock&#39;: &#39;Rock&#39;,
 &#39;Registeel&#39;: &#39;Steel&#39;,
 &#39;Relicanth&#39;: &#39;Water&#39;,
 &#39;Remoraid&#39;: &#39;Water&#39;,
 &#39;Reshiram&#39;: &#39;Dragon&#39;,
 &#39;Reuniclus&#39;: &#39;Psychic&#39;,
 &#39;Rhydon&#39;: &#39;Ground&#39;,
 &#39;Rhyhorn&#39;: &#39;Ground&#39;,
 &#39;Rhyperior&#39;: &#39;Ground&#39;,
 &#39;Riolu&#39;: &#39;Fighting&#39;,
 &#39;Roggenrola&#39;: &#39;Rock&#39;,
 &#39;Roselia&#39;: &#39;Grass&#39;,
 &#39;Roserade&#39;: &#39;Grass&#39;,
 &#39;Rotom&#39;: &#39;Electric&#39;,
 &#39;Rufflet&#39;: &#39;Normal&#39;,
 &#39;Sableye&#39;: &#39;Dark&#39;,
 &#39;Salamence&#39;: &#39;Dragon&#39;,
 &#39;Samurott&#39;: &#39;Water&#39;,
 &#39;Sandile&#39;: &#39;Ground&#39;,
 &#39;Sandshrew&#39;: &#39;Ground&#39;,
 &#39;Sandslash&#39;: &#39;Ground&#39;,
 &#39;Sawk&#39;: &#39;Fighting&#39;,
 &#39;Sawsbuck&#39;: &#39;Normal&#39;,
 &#39;Scatterbug&#39;: &#39;Bug&#39;,
 &#39;Sceptile&#39;: &#39;Grass&#39;,
 &#39;Scizor&#39;: &#39;Bug&#39;,
 &#39;Scolipede&#39;: &#39;Bug&#39;,
 &#39;Scrafty&#39;: &#39;Dark&#39;,
 &#39;Scraggy&#39;: &#39;Dark&#39;,
 &#39;Scyther&#39;: &#39;Bug&#39;,
 &#39;Seadra&#39;: &#39;Water&#39;,
 &#39;Seaking&#39;: &#39;Water&#39;,
 &#39;Sealeo&#39;: &#39;Ice&#39;,
 &#39;Seedot&#39;: &#39;Grass&#39;,
 &#39;Seel&#39;: &#39;Water&#39;,
 &#39;Seismitoad&#39;: &#39;Water&#39;,
 &#39;Sentret&#39;: &#39;Normal&#39;,
 &#39;Serperior&#39;: &#39;Grass&#39;,
 &#39;Servine&#39;: &#39;Grass&#39;,
 &#39;Seviper&#39;: &#39;Poison&#39;,
 &#39;Sewaddle&#39;: &#39;Bug&#39;,
 &#39;Sharpedo&#39;: &#39;Water&#39;,
 &#39;Shaymin&#39;: &#39;Grass&#39;,
 &#39;Shedinja&#39;: &#39;Bug&#39;,
 &#39;Shelgon&#39;: &#39;Dragon&#39;,
 &#39;Shellder&#39;: &#39;Water&#39;,
 &#39;Shellos&#39;: &#39;Water&#39;,
 &#39;Shelmet&#39;: &#39;Bug&#39;,
 &#39;Shieldon&#39;: &#39;Rock&#39;,
 &#39;Shiftry&#39;: &#39;Grass&#39;,
 &#39;Shinx&#39;: &#39;Electric&#39;,
 &#39;Shroomish&#39;: &#39;Grass&#39;,
 &#39;Shuckle&#39;: &#39;Bug&#39;,
 &#39;Shuppet&#39;: &#39;Ghost&#39;,
 &#39;Sigilyph&#39;: &#39;Psychic&#39;,
 &#39;Silcoon&#39;: &#39;Bug&#39;,
 &#39;Simipour&#39;: &#39;Water&#39;,
 &#39;Simisage&#39;: &#39;Grass&#39;,
 &#39;Simisear&#39;: &#39;Fire&#39;,
 &#39;Skarmory&#39;: &#39;Steel&#39;,
 &#39;Skiddo&#39;: &#39;Grass&#39;,
 &#39;Skiploom&#39;: &#39;Grass&#39;,
 &#39;Skitty&#39;: &#39;Normal&#39;,
 &#39;Skorupi&#39;: &#39;Poison&#39;,
 &#39;Skrelp&#39;: &#39;Poison&#39;,
 &#39;Skuntank&#39;: &#39;Poison&#39;,
 &#39;Slaking&#39;: &#39;Normal&#39;,
 &#39;Slakoth&#39;: &#39;Normal&#39;,
 &#39;Sliggoo&#39;: &#39;Dragon&#39;,
 &#39;Slowbro&#39;: &#39;Water&#39;,
 &#39;Slowking&#39;: &#39;Water&#39;,
 &#39;Slowpoke&#39;: &#39;Water&#39;,
 &#39;Slugma&#39;: &#39;Fire&#39;,
 &#39;Slurpuff&#39;: &#39;Fairy&#39;,
 &#39;Smeargle&#39;: &#39;Normal&#39;,
 &#39;Smoochum&#39;: &#39;Ice&#39;,
 &#39;Sneasel&#39;: &#39;Dark&#39;,
 &#39;Snivy&#39;: &#39;Grass&#39;,
 &#39;Snorlax&#39;: &#39;Normal&#39;,
 &#39;Snorunt&#39;: &#39;Ice&#39;,
 &#39;Snover&#39;: &#39;Grass&#39;,
 &#39;Snubbull&#39;: &#39;Fairy&#39;,
 &#39;Solosis&#39;: &#39;Psychic&#39;,
 &#39;Solrock&#39;: &#39;Rock&#39;,
 &#39;Spearow&#39;: &#39;Normal&#39;,
 &#39;Spewpa&#39;: &#39;Bug&#39;,
 &#39;Spheal&#39;: &#39;Ice&#39;,
 &#39;Spinarak&#39;: &#39;Bug&#39;,
 &#39;Spinda&#39;: &#39;Normal&#39;,
 &#39;Spiritomb&#39;: &#39;Ghost&#39;,
 &#39;Spoink&#39;: &#39;Psychic&#39;,
 &#39;Spritzee&#39;: &#39;Fairy&#39;,
 &#39;Squirtle&#39;: &#39;Water&#39;,
 &#39;Stantler&#39;: &#39;Normal&#39;,
 &#39;Staraptor&#39;: &#39;Normal&#39;,
 &#39;Staravia&#39;: &#39;Normal&#39;,
 &#39;Starly&#39;: &#39;Normal&#39;,
 &#39;Starmie&#39;: &#39;Water&#39;,
 &#39;Staryu&#39;: &#39;Water&#39;,
 &#39;Steelix&#39;: &#39;Steel&#39;,
 &#39;Stoutland&#39;: &#39;Normal&#39;,
 &#39;Stunfisk&#39;: &#39;Ground&#39;,
 &#39;Stunky&#39;: &#39;Poison&#39;,
 &#39;Sudowoodo&#39;: &#39;Rock&#39;,
 &#39;Suicune&#39;: &#39;Water&#39;,
 &#39;Sunflora&#39;: &#39;Grass&#39;,
 &#39;Sunkern&#39;: &#39;Grass&#39;,
 &#39;Surskit&#39;: &#39;Bug&#39;,
 &#39;Swablu&#39;: &#39;Normal&#39;,
 &#39;Swadloon&#39;: &#39;Bug&#39;,
 &#39;Swalot&#39;: &#39;Poison&#39;,
 &#39;Swampert&#39;: &#39;Water&#39;,
 &#39;Swanna&#39;: &#39;Water&#39;,
 &#39;Swellow&#39;: &#39;Normal&#39;,
 &#39;Swinub&#39;: &#39;Ice&#39;,
 &#39;Swirlix&#39;: &#39;Fairy&#39;,
 &#39;Swoobat&#39;: &#39;Psychic&#39;,
 &#39;Sylveon&#39;: &#39;Fairy&#39;,
 &#39;Taillow&#39;: &#39;Normal&#39;,
 &#39;Talonflame&#39;: &#39;Fire&#39;,
 &#39;Tangela&#39;: &#39;Grass&#39;,
 &#39;Tangrowth&#39;: &#39;Grass&#39;,
 &#39;Tauros&#39;: &#39;Normal&#39;,
 &#39;Teddiursa&#39;: &#39;Normal&#39;,
 &#39;Tentacool&#39;: &#39;Water&#39;,
 &#39;Tentacruel&#39;: &#39;Water&#39;,
 &#39;Tepig&#39;: &#39;Fire&#39;,
 &#39;Terrakion&#39;: &#39;Rock&#39;,
 &#39;Throh&#39;: &#39;Fighting&#39;,
 &#39;Thundurus&#39;: &#39;Electric&#39;,
 &#39;Timburr&#39;: &#39;Fighting&#39;,
 &#39;Tirtouga&#39;: &#39;Water&#39;,
 &#39;Togekiss&#39;: &#39;Fairy&#39;,
 &#39;Togepi&#39;: &#39;Fairy&#39;,
 &#39;Togetic&#39;: &#39;Fairy&#39;,
 &#39;Torchic&#39;: &#39;Fire&#39;,
 &#39;Torkoal&#39;: &#39;Fire&#39;,
 &#39;Tornadus&#39;: &#39;Flying&#39;,
 &#39;Torterra&#39;: &#39;Grass&#39;,
 &#39;Totodile&#39;: &#39;Water&#39;,
 &#39;Toxicroak&#39;: &#39;Poison&#39;,
 &#39;Tranquill&#39;: &#39;Normal&#39;,
 &#39;Trapinch&#39;: &#39;Ground&#39;,
 &#39;Treecko&#39;: &#39;Grass&#39;,
 &#39;Trevenant&#39;: &#39;Ghost&#39;,
 &#39;Tropius&#39;: &#39;Grass&#39;,
 &#39;Trubbish&#39;: &#39;Poison&#39;,
 &#39;Turtwig&#39;: &#39;Grass&#39;,
 &#39;Tympole&#39;: &#39;Water&#39;,
 &#39;Tynamo&#39;: &#39;Electric&#39;,
 &#39;Typhlosion&#39;: &#39;Fire&#39;,
 &#39;Tyranitar&#39;: &#39;Rock&#39;,
 &#39;Tyrantrum&#39;: &#39;Rock&#39;,
 &#39;Tyrogue&#39;: &#39;Fighting&#39;,
 &#39;Tyrunt&#39;: &#39;Rock&#39;,
 &#39;Umbreon&#39;: &#39;Dark&#39;,
 &#39;Unfezant&#39;: &#39;Normal&#39;,
 &#39;Unown&#39;: &#39;Psychic&#39;,
 &#39;Ursaring&#39;: &#39;Normal&#39;,
 &#39;Uxie&#39;: &#39;Psychic&#39;,
 &#39;Vanillish&#39;: &#39;Ice&#39;,
 &#39;Vanillite&#39;: &#39;Ice&#39;,
 &#39;Vanilluxe&#39;: &#39;Ice&#39;,
 &#39;Vaporeon&#39;: &#39;Water&#39;,
 &#39;Venipede&#39;: &#39;Bug&#39;,
 &#39;Venomoth&#39;: &#39;Bug&#39;,
 &#39;Venonat&#39;: &#39;Bug&#39;,
 &#39;Venusaur&#39;: &#39;Grass&#39;,
 &#39;Vespiquen&#39;: &#39;Bug&#39;,
 &#39;Vibrava&#39;: &#39;Ground&#39;,
 &#39;Victini&#39;: &#39;Psychic&#39;,
 &#39;Victreebel&#39;: &#39;Grass&#39;,
 &#39;Vigoroth&#39;: &#39;Normal&#39;,
 &#39;Vileplume&#39;: &#39;Grass&#39;,
 &#39;Virizion&#39;: &#39;Grass&#39;,
 &#39;Vivillon&#39;: &#39;Bug&#39;,
 &#39;Volbeat&#39;: &#39;Bug&#39;,
 &#39;Volcanion&#39;: &#39;Fire&#39;,
 &#39;Volcarona&#39;: &#39;Bug&#39;,
 &#39;Voltorb&#39;: &#39;Electric&#39;,
 &#39;Vullaby&#39;: &#39;Dark&#39;,
 &#39;Vulpix&#39;: &#39;Fire&#39;,
 &#39;Wailmer&#39;: &#39;Water&#39;,
 &#39;Wailord&#39;: &#39;Water&#39;,
 &#39;Walrein&#39;: &#39;Ice&#39;,
 &#39;Wartortle&#39;: &#39;Water&#39;,
 &#39;Watchog&#39;: &#39;Normal&#39;,
 &#39;Weavile&#39;: &#39;Dark&#39;,
 &#39;Weedle&#39;: &#39;Bug&#39;,
 &#39;Weepinbell&#39;: &#39;Grass&#39;,
 &#39;Weezing&#39;: &#39;Poison&#39;,
 &#39;Whimsicott&#39;: &#39;Grass&#39;,
 &#39;Whirlipede&#39;: &#39;Bug&#39;,
 &#39;Whiscash&#39;: &#39;Water&#39;,
 &#39;Whismur&#39;: &#39;Normal&#39;,
 &#39;Wigglytuff&#39;: &#39;Normal&#39;,
 &#39;Wingull&#39;: &#39;Water&#39;,
 &#39;Wobbuffet&#39;: &#39;Psychic&#39;,
 &#39;Woobat&#39;: &#39;Psychic&#39;,
 &#39;Wooper&#39;: &#39;Water&#39;,
 &#39;Wormadam&#39;: &#39;Bug&#39;,
 &#39;Wurmple&#39;: &#39;Bug&#39;,
 &#39;Wynaut&#39;: &#39;Psychic&#39;,
 &#39;Xatu&#39;: &#39;Psychic&#39;,
 &#39;Xerneas&#39;: &#39;Fairy&#39;,
 &#39;Yamask&#39;: &#39;Ghost&#39;,
 &#39;Yanma&#39;: &#39;Bug&#39;,
 &#39;Yanmega&#39;: &#39;Bug&#39;,
 &#39;Yveltal&#39;: &#39;Dark&#39;,
 &#39;Zangoose&#39;: &#39;Normal&#39;,
 &#39;Zapdos&#39;: &#39;Electric&#39;,
 &#39;Zebstrika&#39;: &#39;Electric&#39;,
 &#39;Zekrom&#39;: &#39;Dragon&#39;,
 &#39;Zigzagoon&#39;: &#39;Normal&#39;,
 &#39;Zoroark&#39;: &#39;Dark&#39;,
 &#39;Zorua&#39;: &#39;Dark&#39;,
 &#39;Zubat&#39;: &#39;Poison&#39;,
 &#39;Zweilous&#39;: &#39;Dark&#39;,
 &#39;Zygarde&#39;: &#39;Dragon&#39;}</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[267]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">pokemon_names</span><span class="o">.</span><span class="n">map</span><span class="p">(</span><span class="n">pokemon_types</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[267]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0         Grass
1         Grass
2         Grass
3          Fire
4          Fire
5          Fire
6         Water
7         Water
8         Water
9           Bug
10          Bug
11          Bug
12          Bug
13          Bug
14          Bug
15       Normal
16       Normal
17       Normal
18       Normal
19       Normal
20       Normal
21       Normal
22       Poison
23       Poison
24     Electric
25     Electric
26       Ground
27       Ground
28       Poison
29       Poison
         ...   
691       Water
692       Water
693    Electric
694    Electric
695        Rock
696        Rock
697        Rock
698        Rock
699       Fairy
700    Fighting
701    Electric
702        Rock
703      Dragon
704      Dragon
705      Dragon
706       Steel
707       Ghost
708       Ghost
709       Ghost
710       Ghost
711         Ice
712         Ice
713      Flying
714      Flying
715       Fairy
716        Dark
717      Dragon
718        Rock
719     Psychic
720        Fire
Name: Pokemon, dtype: object</pre>
</div>

</div>

</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>
