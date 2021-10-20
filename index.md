<!DOCTYPE html>
<html>

<head>
  <style type="text/css">
    div.output_subarea {
      max-width: 100% !important;
    }
  </style>
  <meta charset="utf-8" />

  <title>Top 100 Prospects</title>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
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
        box-shadow: none !important;
        text-shadow: none !important;
      }

      a,
      a:visited {
        text-decoration: underline;
      }

      a[href]:after {
        content: " ("attr(href) ")";
      }

      abbr[title]:after {
        content: " ("attr(title) ")";
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

      .btn>.caret,
      .dropup>.btn>.caret {
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
      color: #000;
      background-color: #fff;
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
    .thumbnail>img,
    .thumbnail a>img,
    .carousel-inner>.item>img,
    .carousel-inner>.item>a>img {
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
      background-color: #fff;
      border: 1px solid #ddd;
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

    .list-inline>li {
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
      color: #888;
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
      border: 1px solid #ccc;
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

    .col-xs-1,
    .col-sm-1,
    .col-md-1,
    .col-lg-1,
    .col-xs-2,
    .col-sm-2,
    .col-md-2,
    .col-lg-2,
    .col-xs-3,
    .col-sm-3,
    .col-md-3,
    .col-lg-3,
    .col-xs-4,
    .col-sm-4,
    .col-md-4,
    .col-lg-4,
    .col-xs-5,
    .col-sm-5,
    .col-md-5,
    .col-lg-5,
    .col-xs-6,
    .col-sm-6,
    .col-md-6,
    .col-lg-6,
    .col-xs-7,
    .col-sm-7,
    .col-md-7,
    .col-lg-7,
    .col-xs-8,
    .col-sm-8,
    .col-md-8,
    .col-lg-8,
    .col-xs-9,
    .col-sm-9,
    .col-md-9,
    .col-lg-9,
    .col-xs-10,
    .col-sm-10,
    .col-md-10,
    .col-lg-10,
    .col-xs-11,
    .col-sm-11,
    .col-md-11,
    .col-lg-11,
    .col-xs-12,
    .col-sm-12,
    .col-md-12,
    .col-lg-12 {
      position: relative;
      min-height: 1px;
      padding-left: 0px;
      padding-right: 0px;
    }

    .col-xs-1,
    .col-xs-2,
    .col-xs-3,
    .col-xs-4,
    .col-xs-5,
    .col-xs-6,
    .col-xs-7,
    .col-xs-8,
    .col-xs-9,
    .col-xs-10,
    .col-xs-11,
    .col-xs-12 {
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

      .col-sm-1,
      .col-sm-2,
      .col-sm-3,
      .col-sm-4,
      .col-sm-5,
      .col-sm-6,
      .col-sm-7,
      .col-sm-8,
      .col-sm-9,
      .col-sm-10,
      .col-sm-11,
      .col-sm-12 {
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

      .col-md-1,
      .col-md-2,
      .col-md-3,
      .col-md-4,
      .col-md-5,
      .col-md-6,
      .col-md-7,
      .col-md-8,
      .col-md-9,
      .col-md-10,
      .col-md-11,
      .col-md-12 {
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

      .col-lg-1,
      .col-lg-2,
      .col-lg-3,
      .col-lg-4,
      .col-lg-5,
      .col-lg-6,
      .col-lg-7,
      .col-lg-8,
      .col-lg-9,
      .col-lg-10,
      .col-lg-11,
      .col-lg-12 {
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

    .table>thead>tr>th,
    .table>tbody>tr>th,
    .table>tfoot>tr>th,
    .table>thead>tr>td,
    .table>tbody>tr>td,
    .table>tfoot>tr>td {
      padding: 8px;
      line-height: 1.42857143;
      vertical-align: top;
      border-top: 1px solid #ddd;
    }

    .table>thead>tr>th {
      vertical-align: bottom;
      border-bottom: 2px solid #ddd;
    }

    .table>caption+thead>tr:first-child>th,
    .table>colgroup+thead>tr:first-child>th,
    .table>thead:first-child>tr:first-child>th,
    .table>caption+thead>tr:first-child>td,
    .table>colgroup+thead>tr:first-child>td,
    .table>thead:first-child>tr:first-child>td {
      border-top: 0;
    }

    .table>tbody+tbody {
      border-top: 2px solid #ddd;
    }

    .table .table {
      background-color: #fff;
    }

    .table-condensed>thead>tr>th,
    .table-condensed>tbody>tr>th,
    .table-condensed>tfoot>tr>th,
    .table-condensed>thead>tr>td,
    .table-condensed>tbody>tr>td,
    .table-condensed>tfoot>tr>td {
      padding: 5px;
    }

    .table-bordered {
      border: 1px solid #ddd;
    }

    .table-bordered>thead>tr>th,
    .table-bordered>tbody>tr>th,
    .table-bordered>tfoot>tr>th,
    .table-bordered>thead>tr>td,
    .table-bordered>tbody>tr>td,
    .table-bordered>tfoot>tr>td {
      border: 1px solid #ddd;
    }

    .table-bordered>thead>tr>th,
    .table-bordered>thead>tr>td {
      border-bottom-width: 2px;
    }

    .table-striped>tbody>tr:nth-of-type(odd) {
      background-color: #f9f9f9;
    }

    .table-hover>tbody>tr:hover {
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

    .table>thead>tr>td.active,
    .table>tbody>tr>td.active,
    .table>tfoot>tr>td.active,
    .table>thead>tr>th.active,
    .table>tbody>tr>th.active,
    .table>tfoot>tr>th.active,
    .table>thead>tr.active>td,
    .table>tbody>tr.active>td,
    .table>tfoot>tr.active>td,
    .table>thead>tr.active>th,
    .table>tbody>tr.active>th,
    .table>tfoot>tr.active>th {
      background-color: #f5f5f5;
    }

    .table-hover>tbody>tr>td.active:hover,
    .table-hover>tbody>tr>th.active:hover,
    .table-hover>tbody>tr.active:hover>td,
    .table-hover>tbody>tr:hover>.active,
    .table-hover>tbody>tr.active:hover>th {
      background-color: #e8e8e8;
    }

    .table>thead>tr>td.success,
    .table>tbody>tr>td.success,
    .table>tfoot>tr>td.success,
    .table>thead>tr>th.success,
    .table>tbody>tr>th.success,
    .table>tfoot>tr>th.success,
    .table>thead>tr.success>td,
    .table>tbody>tr.success>td,
    .table>tfoot>tr.success>td,
    .table>thead>tr.success>th,
    .table>tbody>tr.success>th,
    .table>tfoot>tr.success>th {
      background-color: #dff0d8;
    }

    .table-hover>tbody>tr>td.success:hover,
    .table-hover>tbody>tr>th.success:hover,
    .table-hover>tbody>tr.success:hover>td,
    .table-hover>tbody>tr:hover>.success,
    .table-hover>tbody>tr.success:hover>th {
      background-color: #d0e9c6;
    }

    .table>thead>tr>td.info,
    .table>tbody>tr>td.info,
    .table>tfoot>tr>td.info,
    .table>thead>tr>th.info,
    .table>tbody>tr>th.info,
    .table>tfoot>tr>th.info,
    .table>thead>tr.info>td,
    .table>tbody>tr.info>td,
    .table>tfoot>tr.info>td,
    .table>thead>tr.info>th,
    .table>tbody>tr.info>th,
    .table>tfoot>tr.info>th {
      background-color: #d9edf7;
    }

    .table-hover>tbody>tr>td.info:hover,
    .table-hover>tbody>tr>th.info:hover,
    .table-hover>tbody>tr.info:hover>td,
    .table-hover>tbody>tr:hover>.info,
    .table-hover>tbody>tr.info:hover>th {
      background-color: #c4e3f3;
    }

    .table>thead>tr>td.warning,
    .table>tbody>tr>td.warning,
    .table>tfoot>tr>td.warning,
    .table>thead>tr>th.warning,
    .table>tbody>tr>th.warning,
    .table>tfoot>tr>th.warning,
    .table>thead>tr.warning>td,
    .table>tbody>tr.warning>td,
    .table>tfoot>tr.warning>td,
    .table>thead>tr.warning>th,
    .table>tbody>tr.warning>th,
    .table>tfoot>tr.warning>th {
      background-color: #fcf8e3;
    }

    .table-hover>tbody>tr>td.warning:hover,
    .table-hover>tbody>tr>th.warning:hover,
    .table-hover>tbody>tr.warning:hover>td,
    .table-hover>tbody>tr:hover>.warning,
    .table-hover>tbody>tr.warning:hover>th {
      background-color: #faf2cc;
    }

    .table>thead>tr>td.danger,
    .table>tbody>tr>td.danger,
    .table>tfoot>tr>td.danger,
    .table>thead>tr>th.danger,
    .table>tbody>tr>th.danger,
    .table>tfoot>tr>th.danger,
    .table>thead>tr.danger>td,
    .table>tbody>tr.danger>td,
    .table>tfoot>tr.danger>td,
    .table>thead>tr.danger>th,
    .table>tbody>tr.danger>th,
    .table>tfoot>tr.danger>th {
      background-color: #f2dede;
    }

    .table-hover>tbody>tr>td.danger:hover,
    .table-hover>tbody>tr>th.danger:hover,
    .table-hover>tbody>tr.danger:hover>td,
    .table-hover>tbody>tr:hover>.danger,
    .table-hover>tbody>tr.danger:hover>th {
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
        border: 1px solid #ddd;
      }

      .table-responsive>.table {
        margin-bottom: 0;
      }

      .table-responsive>.table>thead>tr>th,
      .table-responsive>.table>tbody>tr>th,
      .table-responsive>.table>tfoot>tr>th,
      .table-responsive>.table>thead>tr>td,
      .table-responsive>.table>tbody>tr>td,
      .table-responsive>.table>tfoot>tr>td {
        white-space: nowrap;
      }

      .table-responsive>.table-bordered {
        border: 0;
      }

      .table-responsive>.table-bordered>thead>tr>th:first-child,
      .table-responsive>.table-bordered>tbody>tr>th:first-child,
      .table-responsive>.table-bordered>tfoot>tr>th:first-child,
      .table-responsive>.table-bordered>thead>tr>td:first-child,
      .table-responsive>.table-bordered>tbody>tr>td:first-child,
      .table-responsive>.table-bordered>tfoot>tr>td:first-child {
        border-left: 0;
      }

      .table-responsive>.table-bordered>thead>tr>th:last-child,
      .table-responsive>.table-bordered>tbody>tr>th:last-child,
      .table-responsive>.table-bordered>tfoot>tr>th:last-child,
      .table-responsive>.table-bordered>thead>tr>td:last-child,
      .table-responsive>.table-bordered>tbody>tr>td:last-child,
      .table-responsive>.table-bordered>tfoot>tr>td:last-child {
        border-right: 0;
      }

      .table-responsive>.table-bordered>tbody>tr:last-child>th,
      .table-responsive>.table-bordered>tfoot>tr:last-child>th,
      .table-responsive>.table-bordered>tbody>tr:last-child>td,
      .table-responsive>.table-bordered>tfoot>tr:last-child>td {
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
      background-color: #fff;
      background-image: none;
      border: 1px solid #ccc;
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
      -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, 0.6);
      box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, 0.6);
    }

    .form-control::-moz-placeholder {
      color: #999;
      opacity: 1;
    }

    .form-control:-ms-input-placeholder {
      color: #999;
    }

    .form-control::-webkit-input-placeholder {
      color: #999;
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

    .radio+.radio,
    .checkbox+.checkbox {
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

    .radio-inline+.radio-inline,
    .checkbox-inline+.checkbox-inline {
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

    .input-lg+.form-control-feedback,
    .input-group-lg+.form-control-feedback,
    .form-group-lg .form-control+.form-control-feedback {
      width: 45px;
      height: 45px;
      line-height: 45px;
    }

    .input-sm+.form-control-feedback,
    .input-group-sm+.form-control-feedback,
    .form-group-sm .form-control+.form-control-feedback {
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

    .has-feedback label~.form-control-feedback {
      top: 23px;
    }

    .has-feedback label.sr-only~.form-control-feedback {
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

      .form-inline .input-group>.form-control {
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
      color: #333;
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
      color: #333;
      background-color: #fff;
      border-color: #ccc;
    }

    .btn-default:focus,
    .btn-default.focus {
      color: #333;
      background-color: #e6e6e6;
      border-color: #8c8c8c;
    }

    .btn-default:hover {
      color: #333;
      background-color: #e6e6e6;
      border-color: #adadad;
    }

    .btn-default:active,
    .btn-default.active,
    .open>.dropdown-toggle.btn-default {
      color: #333;
      background-color: #e6e6e6;
      border-color: #adadad;
    }

    .btn-default:active:hover,
    .btn-default.active:hover,
    .open>.dropdown-toggle.btn-default:hover,
    .btn-default:active:focus,
    .btn-default.active:focus,
    .open>.dropdown-toggle.btn-default:focus,
    .btn-default:active.focus,
    .btn-default.active.focus,
    .open>.dropdown-toggle.btn-default.focus {
      color: #333;
      background-color: #d4d4d4;
      border-color: #8c8c8c;
    }

    .btn-default:active,
    .btn-default.active,
    .open>.dropdown-toggle.btn-default {
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
      background-color: #fff;
      border-color: #ccc;
    }

    .btn-default .badge {
      color: #fff;
      background-color: #333;
    }

    .btn-primary {
      color: #fff;
      background-color: #337ab7;
      border-color: #2e6da4;
    }

    .btn-primary:focus,
    .btn-primary.focus {
      color: #fff;
      background-color: #286090;
      border-color: #122b40;
    }

    .btn-primary:hover {
      color: #fff;
      background-color: #286090;
      border-color: #204d74;
    }

    .btn-primary:active,
    .btn-primary.active,
    .open>.dropdown-toggle.btn-primary {
      color: #fff;
      background-color: #286090;
      border-color: #204d74;
    }

    .btn-primary:active:hover,
    .btn-primary.active:hover,
    .open>.dropdown-toggle.btn-primary:hover,
    .btn-primary:active:focus,
    .btn-primary.active:focus,
    .open>.dropdown-toggle.btn-primary:focus,
    .btn-primary:active.focus,
    .btn-primary.active.focus,
    .open>.dropdown-toggle.btn-primary.focus {
      color: #fff;
      background-color: #204d74;
      border-color: #122b40;
    }

    .btn-primary:active,
    .btn-primary.active,
    .open>.dropdown-toggle.btn-primary {
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
      background-color: #fff;
    }

    .btn-success {
      color: #fff;
      background-color: #5cb85c;
      border-color: #4cae4c;
    }

    .btn-success:focus,
    .btn-success.focus {
      color: #fff;
      background-color: #449d44;
      border-color: #255625;
    }

    .btn-success:hover {
      color: #fff;
      background-color: #449d44;
      border-color: #398439;
    }

    .btn-success:active,
    .btn-success.active,
    .open>.dropdown-toggle.btn-success {
      color: #fff;
      background-color: #449d44;
      border-color: #398439;
    }

    .btn-success:active:hover,
    .btn-success.active:hover,
    .open>.dropdown-toggle.btn-success:hover,
    .btn-success:active:focus,
    .btn-success.active:focus,
    .open>.dropdown-toggle.btn-success:focus,
    .btn-success:active.focus,
    .btn-success.active.focus,
    .open>.dropdown-toggle.btn-success.focus {
      color: #fff;
      background-color: #398439;
      border-color: #255625;
    }

    .btn-success:active,
    .btn-success.active,
    .open>.dropdown-toggle.btn-success {
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
      background-color: #fff;
    }

    .btn-info {
      color: #fff;
      background-color: #5bc0de;
      border-color: #46b8da;
    }

    .btn-info:focus,
    .btn-info.focus {
      color: #fff;
      background-color: #31b0d5;
      border-color: #1b6d85;
    }

    .btn-info:hover {
      color: #fff;
      background-color: #31b0d5;
      border-color: #269abc;
    }

    .btn-info:active,
    .btn-info.active,
    .open>.dropdown-toggle.btn-info {
      color: #fff;
      background-color: #31b0d5;
      border-color: #269abc;
    }

    .btn-info:active:hover,
    .btn-info.active:hover,
    .open>.dropdown-toggle.btn-info:hover,
    .btn-info:active:focus,
    .btn-info.active:focus,
    .open>.dropdown-toggle.btn-info:focus,
    .btn-info:active.focus,
    .btn-info.active.focus,
    .open>.dropdown-toggle.btn-info.focus {
      color: #fff;
      background-color: #269abc;
      border-color: #1b6d85;
    }

    .btn-info:active,
    .btn-info.active,
    .open>.dropdown-toggle.btn-info {
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
      background-color: #fff;
    }

    .btn-warning {
      color: #fff;
      background-color: #f0ad4e;
      border-color: #eea236;
    }

    .btn-warning:focus,
    .btn-warning.focus {
      color: #fff;
      background-color: #ec971f;
      border-color: #985f0d;
    }

    .btn-warning:hover {
      color: #fff;
      background-color: #ec971f;
      border-color: #d58512;
    }

    .btn-warning:active,
    .btn-warning.active,
    .open>.dropdown-toggle.btn-warning {
      color: #fff;
      background-color: #ec971f;
      border-color: #d58512;
    }

    .btn-warning:active:hover,
    .btn-warning.active:hover,
    .open>.dropdown-toggle.btn-warning:hover,
    .btn-warning:active:focus,
    .btn-warning.active:focus,
    .open>.dropdown-toggle.btn-warning:focus,
    .btn-warning:active.focus,
    .btn-warning.active.focus,
    .open>.dropdown-toggle.btn-warning.focus {
      color: #fff;
      background-color: #d58512;
      border-color: #985f0d;
    }

    .btn-warning:active,
    .btn-warning.active,
    .open>.dropdown-toggle.btn-warning {
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
      background-color: #fff;
    }

    .btn-danger {
      color: #fff;
      background-color: #d9534f;
      border-color: #d43f3a;
    }

    .btn-danger:focus,
    .btn-danger.focus {
      color: #fff;
      background-color: #c9302c;
      border-color: #761c19;
    }

    .btn-danger:hover {
      color: #fff;
      background-color: #c9302c;
      border-color: #ac2925;
    }

    .btn-danger:active,
    .btn-danger.active,
    .open>.dropdown-toggle.btn-danger {
      color: #fff;
      background-color: #c9302c;
      border-color: #ac2925;
    }

    .btn-danger:active:hover,
    .btn-danger.active:hover,
    .open>.dropdown-toggle.btn-danger:hover,
    .btn-danger:active:focus,
    .btn-danger.active:focus,
    .open>.dropdown-toggle.btn-danger:focus,
    .btn-danger:active.focus,
    .btn-danger.active.focus,
    .open>.dropdown-toggle.btn-danger.focus {
      color: #fff;
      background-color: #ac2925;
      border-color: #761c19;
    }

    .btn-danger:active,
    .btn-danger.active,
    .open>.dropdown-toggle.btn-danger {
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
      background-color: #fff;
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
    .btn-group-lg>.btn {
      padding: 10px 16px;
      font-size: 17px;
      line-height: 1.3333333;
      border-radius: 3px;
    }

    .btn-sm,
    .btn-group-sm>.btn {
      padding: 5px 10px;
      font-size: 12px;
      line-height: 1.5;
      border-radius: 1px;
    }

    .btn-xs,
    .btn-group-xs>.btn {
      padding: 1px 5px;
      font-size: 12px;
      line-height: 1.5;
      border-radius: 1px;
    }

    .btn-block {
      display: block;
      width: 100%;
    }

    .btn-block+.btn-block {
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
      background-color: #fff;
      border: 1px solid #ccc;
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

    .dropdown-menu>li>a {
      display: block;
      padding: 3px 20px;
      clear: both;
      font-weight: normal;
      line-height: 1.42857143;
      color: #333333;
      white-space: nowrap;
    }

    .dropdown-menu>li>a:hover,
    .dropdown-menu>li>a:focus {
      text-decoration: none;
      color: #262626;
      background-color: #f5f5f5;
    }

    .dropdown-menu>.active>a,
    .dropdown-menu>.active>a:hover,
    .dropdown-menu>.active>a:focus {
      color: #fff;
      text-decoration: none;
      outline: 0;
      background-color: #337ab7;
    }

    .dropdown-menu>.disabled>a,
    .dropdown-menu>.disabled>a:hover,
    .dropdown-menu>.disabled>a:focus {
      color: #777777;
    }

    .dropdown-menu>.disabled>a:hover,
    .dropdown-menu>.disabled>a:focus {
      text-decoration: none;
      background-color: transparent;
      background-image: none;
      filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
      cursor: not-allowed;
    }

    .open>.dropdown-menu {
      display: block;
    }

    .open>a {
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

    .pull-right>.dropdown-menu {
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

    .btn-group>.btn,
    .btn-group-vertical>.btn {
      position: relative;
      float: left;
    }

    .btn-group>.btn:hover,
    .btn-group-vertical>.btn:hover,
    .btn-group>.btn:focus,
    .btn-group-vertical>.btn:focus,
    .btn-group>.btn:active,
    .btn-group-vertical>.btn:active,
    .btn-group>.btn.active,
    .btn-group-vertical>.btn.active {
      z-index: 2;
    }

    .btn-group .btn+.btn,
    .btn-group .btn+.btn-group,
    .btn-group .btn-group+.btn,
    .btn-group .btn-group+.btn-group {
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

    .btn-toolbar>.btn,
    .btn-toolbar>.btn-group,
    .btn-toolbar>.input-group {
      margin-left: 5px;
    }

    .btn-group>.btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
      border-radius: 0;
    }

    .btn-group>.btn:first-child {
      margin-left: 0;
    }

    .btn-group>.btn:first-child:not(:last-child):not(.dropdown-toggle) {
      border-bottom-right-radius: 0;
      border-top-right-radius: 0;
    }

    .btn-group>.btn:last-child:not(:first-child),
    .btn-group>.dropdown-toggle:not(:first-child) {
      border-bottom-left-radius: 0;
      border-top-left-radius: 0;
    }

    .btn-group>.btn-group {
      float: left;
    }

    .btn-group>.btn-group:not(:first-child):not(:last-child)>.btn {
      border-radius: 0;
    }

    .btn-group>.btn-group:first-child:not(:last-child)>.btn:last-child,
    .btn-group>.btn-group:first-child:not(:last-child)>.dropdown-toggle {
      border-bottom-right-radius: 0;
      border-top-right-radius: 0;
    }

    .btn-group>.btn-group:last-child:not(:first-child)>.btn:first-child {
      border-bottom-left-radius: 0;
      border-top-left-radius: 0;
    }

    .btn-group .dropdown-toggle:active,
    .btn-group.open .dropdown-toggle {
      outline: 0;
    }

    .btn-group>.btn+.dropdown-toggle {
      padding-left: 8px;
      padding-right: 8px;
    }

    .btn-group>.btn-lg+.dropdown-toggle {
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

    .btn-group-vertical>.btn,
    .btn-group-vertical>.btn-group,
    .btn-group-vertical>.btn-group>.btn {
      display: block;
      float: none;
      width: 100%;
      max-width: 100%;
    }

    .btn-group-vertical>.btn-group>.btn {
      float: none;
    }

    .btn-group-vertical>.btn+.btn,
    .btn-group-vertical>.btn+.btn-group,
    .btn-group-vertical>.btn-group+.btn,
    .btn-group-vertical>.btn-group+.btn-group {
      margin-top: -1px;
      margin-left: 0;
    }

    .btn-group-vertical>.btn:not(:first-child):not(:last-child) {
      border-radius: 0;
    }

    .btn-group-vertical>.btn:first-child:not(:last-child) {
      border-top-right-radius: 2px;
      border-top-left-radius: 2px;
      border-bottom-right-radius: 0;
      border-bottom-left-radius: 0;
    }

    .btn-group-vertical>.btn:last-child:not(:first-child) {
      border-top-right-radius: 0;
      border-top-left-radius: 0;
      border-bottom-right-radius: 2px;
      border-bottom-left-radius: 2px;
    }

    .btn-group-vertical>.btn-group:not(:first-child):not(:last-child)>.btn {
      border-radius: 0;
    }

    .btn-group-vertical>.btn-group:first-child:not(:last-child)>.btn:last-child,
    .btn-group-vertical>.btn-group:first-child:not(:last-child)>.dropdown-toggle {
      border-bottom-right-radius: 0;
      border-bottom-left-radius: 0;
    }

    .btn-group-vertical>.btn-group:last-child:not(:first-child)>.btn:first-child {
      border-top-right-radius: 0;
      border-top-left-radius: 0;
    }

    .btn-group-justified {
      display: table;
      width: 100%;
      table-layout: fixed;
      border-collapse: separate;
    }

    .btn-group-justified>.btn,
    .btn-group-justified>.btn-group {
      float: none;
      display: table-cell;
      width: 1%;
    }

    .btn-group-justified>.btn-group .btn {
      width: 100%;
    }

    .btn-group-justified>.btn-group .dropdown-menu {
      left: auto;
    }

    [data-toggle="buttons"]>.btn input[type="radio"],
    [data-toggle="buttons"]>.btn-group>.btn input[type="radio"],
    [data-toggle="buttons"]>.btn input[type="checkbox"],
    [data-toggle="buttons"]>.btn-group>.btn input[type="checkbox"] {
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

    .input-group-lg>.form-control,
    .input-group-lg>.input-group-addon,
    .input-group-lg>.input-group-btn>.btn {
      height: 45px;
      padding: 10px 16px;
      font-size: 17px;
      line-height: 1.3333333;
      border-radius: 3px;
    }

    select.input-group-lg>.form-control,
    select.input-group-lg>.input-group-addon,
    select.input-group-lg>.input-group-btn>.btn {
      height: 45px;
      line-height: 45px;
    }

    textarea.input-group-lg>.form-control,
    textarea.input-group-lg>.input-group-addon,
    textarea.input-group-lg>.input-group-btn>.btn,
    select[multiple].input-group-lg>.form-control,
    select[multiple].input-group-lg>.input-group-addon,
    select[multiple].input-group-lg>.input-group-btn>.btn {
      height: auto;
    }

    .input-group-sm>.form-control,
    .input-group-sm>.input-group-addon,
    .input-group-sm>.input-group-btn>.btn {
      height: 30px;
      padding: 5px 10px;
      font-size: 12px;
      line-height: 1.5;
      border-radius: 1px;
    }

    select.input-group-sm>.form-control,
    select.input-group-sm>.input-group-addon,
    select.input-group-sm>.input-group-btn>.btn {
      height: 30px;
      line-height: 30px;
    }

    textarea.input-group-sm>.form-control,
    textarea.input-group-sm>.input-group-addon,
    textarea.input-group-sm>.input-group-btn>.btn,
    select[multiple].input-group-sm>.form-control,
    select[multiple].input-group-sm>.input-group-addon,
    select[multiple].input-group-sm>.input-group-btn>.btn {
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
      border: 1px solid #ccc;
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
    .input-group-btn:first-child>.btn,
    .input-group-btn:first-child>.btn-group>.btn,
    .input-group-btn:first-child>.dropdown-toggle,
    .input-group-btn:last-child>.btn:not(:last-child):not(.dropdown-toggle),
    .input-group-btn:last-child>.btn-group:not(:last-child)>.btn {
      border-bottom-right-radius: 0;
      border-top-right-radius: 0;
    }

    .input-group-addon:first-child {
      border-right: 0;
    }

    .input-group .form-control:last-child,
    .input-group-addon:last-child,
    .input-group-btn:last-child>.btn,
    .input-group-btn:last-child>.btn-group>.btn,
    .input-group-btn:last-child>.dropdown-toggle,
    .input-group-btn:first-child>.btn:not(:first-child),
    .input-group-btn:first-child>.btn-group:not(:first-child)>.btn {
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

    .input-group-btn>.btn {
      position: relative;
    }

    .input-group-btn>.btn+.btn {
      margin-left: -1px;
    }

    .input-group-btn>.btn:hover,
    .input-group-btn>.btn:focus,
    .input-group-btn>.btn:active {
      z-index: 2;
    }

    .input-group-btn:first-child>.btn,
    .input-group-btn:first-child>.btn-group {
      margin-right: -1px;
    }

    .input-group-btn:last-child>.btn,
    .input-group-btn:last-child>.btn-group {
      z-index: 2;
      margin-left: -1px;
    }

    .nav {
      margin-bottom: 0;
      padding-left: 0;
      list-style: none;
    }

    .nav>li {
      position: relative;
      display: block;
    }

    .nav>li>a {
      position: relative;
      display: block;
      padding: 10px 15px;
    }

    .nav>li>a:hover,
    .nav>li>a:focus {
      text-decoration: none;
      background-color: #eeeeee;
    }

    .nav>li.disabled>a {
      color: #777777;
    }

    .nav>li.disabled>a:hover,
    .nav>li.disabled>a:focus {
      color: #777777;
      text-decoration: none;
      background-color: transparent;
      cursor: not-allowed;
    }

    .nav .open>a,
    .nav .open>a:hover,
    .nav .open>a:focus {
      background-color: #eeeeee;
      border-color: #337ab7;
    }

    .nav .nav-divider {
      height: 1px;
      margin: 8px 0;
      overflow: hidden;
      background-color: #e5e5e5;
    }

    .nav>li>a>img {
      max-width: none;
    }

    .nav-tabs {
      border-bottom: 1px solid #ddd;
    }

    .nav-tabs>li {
      float: left;
      margin-bottom: -1px;
    }

    .nav-tabs>li>a {
      margin-right: 2px;
      line-height: 1.42857143;
      border: 1px solid transparent;
      border-radius: 2px 2px 0 0;
    }

    .nav-tabs>li>a:hover {
      border-color: #eeeeee #eeeeee #ddd;
    }

    .nav-tabs>li.active>a,
    .nav-tabs>li.active>a:hover,
    .nav-tabs>li.active>a:focus {
      color: #555555;
      background-color: #fff;
      border: 1px solid #ddd;
      border-bottom-color: transparent;
      cursor: default;
    }

    .nav-tabs.nav-justified {
      width: 100%;
      border-bottom: 0;
    }

    .nav-tabs.nav-justified>li {
      float: none;
    }

    .nav-tabs.nav-justified>li>a {
      text-align: center;
      margin-bottom: 5px;
    }

    .nav-tabs.nav-justified>.dropdown .dropdown-menu {
      top: auto;
      left: auto;
    }

    @media (min-width: 768px) {
      .nav-tabs.nav-justified>li {
        display: table-cell;
        width: 1%;
      }

      .nav-tabs.nav-justified>li>a {
        margin-bottom: 0;
      }
    }

    .nav-tabs.nav-justified>li>a {
      margin-right: 0;
      border-radius: 2px;
    }

    .nav-tabs.nav-justified>.active>a,
    .nav-tabs.nav-justified>.active>a:hover,
    .nav-tabs.nav-justified>.active>a:focus {
      border: 1px solid #ddd;
    }

    @media (min-width: 768px) {
      .nav-tabs.nav-justified>li>a {
        border-bottom: 1px solid #ddd;
        border-radius: 2px 2px 0 0;
      }

      .nav-tabs.nav-justified>.active>a,
      .nav-tabs.nav-justified>.active>a:hover,
      .nav-tabs.nav-justified>.active>a:focus {
        border-bottom-color: #fff;
      }
    }

    .nav-pills>li {
      float: left;
    }

    .nav-pills>li>a {
      border-radius: 2px;
    }

    .nav-pills>li+li {
      margin-left: 2px;
    }

    .nav-pills>li.active>a,
    .nav-pills>li.active>a:hover,
    .nav-pills>li.active>a:focus {
      color: #fff;
      background-color: #337ab7;
    }

    .nav-stacked>li {
      float: none;
    }

    .nav-stacked>li+li {
      margin-top: 2px;
      margin-left: 0;
    }

    .nav-justified {
      width: 100%;
    }

    .nav-justified>li {
      float: none;
    }

    .nav-justified>li>a {
      text-align: center;
      margin-bottom: 5px;
    }

    .nav-justified>.dropdown .dropdown-menu {
      top: auto;
      left: auto;
    }

    @media (min-width: 768px) {
      .nav-justified>li {
        display: table-cell;
        width: 1%;
      }

      .nav-justified>li>a {
        margin-bottom: 0;
      }
    }

    .nav-tabs-justified {
      border-bottom: 0;
    }

    .nav-tabs-justified>li>a {
      margin-right: 0;
      border-radius: 2px;
    }

    .nav-tabs-justified>.active>a,
    .nav-tabs-justified>.active>a:hover,
    .nav-tabs-justified>.active>a:focus {
      border: 1px solid #ddd;
    }

    @media (min-width: 768px) {
      .nav-tabs-justified>li>a {
        border-bottom: 1px solid #ddd;
        border-radius: 2px 2px 0 0;
      }

      .nav-tabs-justified>.active>a,
      .nav-tabs-justified>.active>a:hover,
      .nav-tabs-justified>.active>a:focus {
        border-bottom-color: #fff;
      }
    }

    .tab-content>.tab-pane {
      display: none;
    }

    .tab-content>.active {
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

    .container>.navbar-header,
    .container-fluid>.navbar-header,
    .container>.navbar-collapse,
    .container-fluid>.navbar-collapse {
      margin-right: 0px;
      margin-left: 0px;
    }

    @media (min-width: 541px) {

      .container>.navbar-header,
      .container-fluid>.navbar-header,
      .container>.navbar-collapse,
      .container-fluid>.navbar-collapse {
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

    .navbar-brand>img {
      display: block;
    }

    @media (min-width: 541px) {

      .navbar>.container .navbar-brand,
      .navbar>.container-fluid .navbar-brand {
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

    .navbar-toggle .icon-bar+.icon-bar {
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

    .navbar-nav>li>a {
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

      .navbar-nav .open .dropdown-menu>li>a,
      .navbar-nav .open .dropdown-menu .dropdown-header {
        padding: 5px 15px 5px 25px;
      }

      .navbar-nav .open .dropdown-menu>li>a {
        line-height: 18px;
      }

      .navbar-nav .open .dropdown-menu>li>a:hover,
      .navbar-nav .open .dropdown-menu>li>a:focus {
        background-image: none;
      }
    }

    @media (min-width: 541px) {
      .navbar-nav {
        float: left;
        margin: 0;
      }

      .navbar-nav>li {
        float: left;
      }

      .navbar-nav>li>a {
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

      .navbar-form .input-group>.form-control {
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

    .navbar-nav>li>.dropdown-menu {
      margin-top: 0;
      border-top-right-radius: 0;
      border-top-left-radius: 0;
    }

    .navbar-fixed-bottom .navbar-nav>li>.dropdown-menu {
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

      .navbar-right~.navbar-right {
        margin-right: 0;
      }
    }

    .navbar-default {
      background-color: #f8f8f8;
      border-color: #e7e7e7;
    }

    .navbar-default .navbar-brand {
      color: #777;
    }

    .navbar-default .navbar-brand:hover,
    .navbar-default .navbar-brand:focus {
      color: #5e5e5e;
      background-color: transparent;
    }

    .navbar-default .navbar-text {
      color: #777;
    }

    .navbar-default .navbar-nav>li>a {
      color: #777;
    }

    .navbar-default .navbar-nav>li>a:hover,
    .navbar-default .navbar-nav>li>a:focus {
      color: #333;
      background-color: transparent;
    }

    .navbar-default .navbar-nav>.active>a,
    .navbar-default .navbar-nav>.active>a:hover,
    .navbar-default .navbar-nav>.active>a:focus {
      color: #555;
      background-color: #e7e7e7;
    }

    .navbar-default .navbar-nav>.disabled>a,
    .navbar-default .navbar-nav>.disabled>a:hover,
    .navbar-default .navbar-nav>.disabled>a:focus {
      color: #ccc;
      background-color: transparent;
    }

    .navbar-default .navbar-toggle {
      border-color: #ddd;
    }

    .navbar-default .navbar-toggle:hover,
    .navbar-default .navbar-toggle:focus {
      background-color: #ddd;
    }

    .navbar-default .navbar-toggle .icon-bar {
      background-color: #888;
    }

    .navbar-default .navbar-collapse,
    .navbar-default .navbar-form {
      border-color: #e7e7e7;
    }

    .navbar-default .navbar-nav>.open>a,
    .navbar-default .navbar-nav>.open>a:hover,
    .navbar-default .navbar-nav>.open>a:focus {
      background-color: #e7e7e7;
      color: #555;
    }

    @media (max-width: 540px) {
      .navbar-default .navbar-nav .open .dropdown-menu>li>a {
        color: #777;
      }

      .navbar-default .navbar-nav .open .dropdown-menu>li>a:hover,
      .navbar-default .navbar-nav .open .dropdown-menu>li>a:focus {
        color: #333;
        background-color: transparent;
      }

      .navbar-default .navbar-nav .open .dropdown-menu>.active>a,
      .navbar-default .navbar-nav .open .dropdown-menu>.active>a:hover,
      .navbar-default .navbar-nav .open .dropdown-menu>.active>a:focus {
        color: #555;
        background-color: #e7e7e7;
      }

      .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a,
      .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:hover,
      .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:focus {
        color: #ccc;
        background-color: transparent;
      }
    }

    .navbar-default .navbar-link {
      color: #777;
    }

    .navbar-default .navbar-link:hover {
      color: #333;
    }

    .navbar-default .btn-link {
      color: #777;
    }

    .navbar-default .btn-link:hover,
    .navbar-default .btn-link:focus {
      color: #333;
    }

    .navbar-default .btn-link[disabled]:hover,
    fieldset[disabled] .navbar-default .btn-link:hover,
    .navbar-default .btn-link[disabled]:focus,
    fieldset[disabled] .navbar-default .btn-link:focus {
      color: #ccc;
    }

    .navbar-inverse {
      background-color: #222;
      border-color: #080808;
    }

    .navbar-inverse .navbar-brand {
      color: #9d9d9d;
    }

    .navbar-inverse .navbar-brand:hover,
    .navbar-inverse .navbar-brand:focus {
      color: #fff;
      background-color: transparent;
    }

    .navbar-inverse .navbar-text {
      color: #9d9d9d;
    }

    .navbar-inverse .navbar-nav>li>a {
      color: #9d9d9d;
    }

    .navbar-inverse .navbar-nav>li>a:hover,
    .navbar-inverse .navbar-nav>li>a:focus {
      color: #fff;
      background-color: transparent;
    }

    .navbar-inverse .navbar-nav>.active>a,
    .navbar-inverse .navbar-nav>.active>a:hover,
    .navbar-inverse .navbar-nav>.active>a:focus {
      color: #fff;
      background-color: #080808;
    }

    .navbar-inverse .navbar-nav>.disabled>a,
    .navbar-inverse .navbar-nav>.disabled>a:hover,
    .navbar-inverse .navbar-nav>.disabled>a:focus {
      color: #444;
      background-color: transparent;
    }

    .navbar-inverse .navbar-toggle {
      border-color: #333;
    }

    .navbar-inverse .navbar-toggle:hover,
    .navbar-inverse .navbar-toggle:focus {
      background-color: #333;
    }

    .navbar-inverse .navbar-toggle .icon-bar {
      background-color: #fff;
    }

    .navbar-inverse .navbar-collapse,
    .navbar-inverse .navbar-form {
      border-color: #101010;
    }

    .navbar-inverse .navbar-nav>.open>a,
    .navbar-inverse .navbar-nav>.open>a:hover,
    .navbar-inverse .navbar-nav>.open>a:focus {
      background-color: #080808;
      color: #fff;
    }

    @media (max-width: 540px) {
      .navbar-inverse .navbar-nav .open .dropdown-menu>.dropdown-header {
        border-color: #080808;
      }

      .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
        background-color: #080808;
      }

      .navbar-inverse .navbar-nav .open .dropdown-menu>li>a {
        color: #9d9d9d;
      }

      .navbar-inverse .navbar-nav .open .dropdown-menu>li>a:hover,
      .navbar-inverse .navbar-nav .open .dropdown-menu>li>a:focus {
        color: #fff;
        background-color: transparent;
      }

      .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a,
      .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:hover,
      .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:focus {
        color: #fff;
        background-color: #080808;
      }

      .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a,
      .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:hover,
      .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:focus {
        color: #444;
        background-color: transparent;
      }
    }

    .navbar-inverse .navbar-link {
      color: #9d9d9d;
    }

    .navbar-inverse .navbar-link:hover {
      color: #fff;
    }

    .navbar-inverse .btn-link {
      color: #9d9d9d;
    }

    .navbar-inverse .btn-link:hover,
    .navbar-inverse .btn-link:focus {
      color: #fff;
    }

    .navbar-inverse .btn-link[disabled]:hover,
    fieldset[disabled] .navbar-inverse .btn-link:hover,
    .navbar-inverse .btn-link[disabled]:focus,
    fieldset[disabled] .navbar-inverse .btn-link:focus {
      color: #444;
    }

    .breadcrumb {
      padding: 8px 15px;
      margin-bottom: 18px;
      list-style: none;
      background-color: #f5f5f5;
      border-radius: 2px;
    }

    .breadcrumb>li {
      display: inline-block;
    }

    .breadcrumb>li+li:before {
      content: "/\00a0";
      padding: 0 5px;
      color: #5e5e5e;
    }

    .breadcrumb>.active {
      color: #777777;
    }

    .pagination {
      display: inline-block;
      padding-left: 0;
      margin: 18px 0;
      border-radius: 2px;
    }

    .pagination>li {
      display: inline;
    }

    .pagination>li>a,
    .pagination>li>span {
      position: relative;
      float: left;
      padding: 6px 12px;
      line-height: 1.42857143;
      text-decoration: none;
      color: #337ab7;
      background-color: #fff;
      border: 1px solid #ddd;
      margin-left: -1px;
    }

    .pagination>li:first-child>a,
    .pagination>li:first-child>span {
      margin-left: 0;
      border-bottom-left-radius: 2px;
      border-top-left-radius: 2px;
    }

    .pagination>li:last-child>a,
    .pagination>li:last-child>span {
      border-bottom-right-radius: 2px;
      border-top-right-radius: 2px;
    }

    .pagination>li>a:hover,
    .pagination>li>span:hover,
    .pagination>li>a:focus,
    .pagination>li>span:focus {
      z-index: 2;
      color: #23527c;
      background-color: #eeeeee;
      border-color: #ddd;
    }

    .pagination>.active>a,
    .pagination>.active>span,
    .pagination>.active>a:hover,
    .pagination>.active>span:hover,
    .pagination>.active>a:focus,
    .pagination>.active>span:focus {
      z-index: 3;
      color: #fff;
      background-color: #337ab7;
      border-color: #337ab7;
      cursor: default;
    }

    .pagination>.disabled>span,
    .pagination>.disabled>span:hover,
    .pagination>.disabled>span:focus,
    .pagination>.disabled>a,
    .pagination>.disabled>a:hover,
    .pagination>.disabled>a:focus {
      color: #777777;
      background-color: #fff;
      border-color: #ddd;
      cursor: not-allowed;
    }

    .pagination-lg>li>a,
    .pagination-lg>li>span {
      padding: 10px 16px;
      font-size: 17px;
      line-height: 1.3333333;
    }

    .pagination-lg>li:first-child>a,
    .pagination-lg>li:first-child>span {
      border-bottom-left-radius: 3px;
      border-top-left-radius: 3px;
    }

    .pagination-lg>li:last-child>a,
    .pagination-lg>li:last-child>span {
      border-bottom-right-radius: 3px;
      border-top-right-radius: 3px;
    }

    .pagination-sm>li>a,
    .pagination-sm>li>span {
      padding: 5px 10px;
      font-size: 12px;
      line-height: 1.5;
    }

    .pagination-sm>li:first-child>a,
    .pagination-sm>li:first-child>span {
      border-bottom-left-radius: 1px;
      border-top-left-radius: 1px;
    }

    .pagination-sm>li:last-child>a,
    .pagination-sm>li:last-child>span {
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

    .pager li>a,
    .pager li>span {
      display: inline-block;
      padding: 5px 14px;
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 15px;
    }

    .pager li>a:hover,
    .pager li>a:focus {
      text-decoration: none;
      background-color: #eeeeee;
    }

    .pager .next>a,
    .pager .next>span {
      float: right;
    }

    .pager .previous>a,
    .pager .previous>span {
      float: left;
    }

    .pager .disabled>a,
    .pager .disabled>a:hover,
    .pager .disabled>a:focus,
    .pager .disabled>span {
      color: #777777;
      background-color: #fff;
      cursor: not-allowed;
    }

    .label {
      display: inline;
      padding: .2em .6em .3em;
      font-size: 75%;
      font-weight: bold;
      line-height: 1;
      color: #fff;
      text-align: center;
      white-space: nowrap;
      vertical-align: baseline;
      border-radius: .25em;
    }

    a.label:hover,
    a.label:focus {
      color: #fff;
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
      color: #fff;
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
    .btn-group-xs>.btn .badge {
      top: 0;
      padding: 1px 5px;
    }

    a.badge:hover,
    a.badge:focus {
      color: #fff;
      text-decoration: none;
      cursor: pointer;
    }

    .list-group-item.active>.badge,
    .nav-pills>.active>a>.badge {
      color: #337ab7;
      background-color: #fff;
    }

    .list-group-item>.badge {
      float: right;
    }

    .list-group-item>.badge+.badge {
      margin-right: 5px;
    }

    .nav-pills>li>a>.badge {
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

    .jumbotron>hr {
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
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 2px;
      -webkit-transition: border 0.2s ease-in-out;
      -o-transition: border 0.2s ease-in-out;
      transition: border 0.2s ease-in-out;
    }

    .thumbnail>img,
    .thumbnail a>img {
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
      color: #000;
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

    .alert>p,
    .alert>ul {
      margin-bottom: 0;
    }

    .alert>p+p {
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
      color: #fff;
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
    .media>.pull-right {
      padding-left: 10px;
    }

    .media-left,
    .media>.pull-left {
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
      background-color: #fff;
      border: 1px solid #ddd;
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
      color: #555;
    }

    a.list-group-item .list-group-item-heading,
    button.list-group-item .list-group-item-heading {
      color: #333;
    }

    a.list-group-item:hover,
    button.list-group-item:hover,
    a.list-group-item:focus,
    button.list-group-item:focus {
      text-decoration: none;
      color: #555;
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
      color: #fff;
      background-color: #337ab7;
      border-color: #337ab7;
    }

    .list-group-item.active .list-group-item-heading,
    .list-group-item.active:hover .list-group-item-heading,
    .list-group-item.active:focus .list-group-item-heading,
    .list-group-item.active .list-group-item-heading>small,
    .list-group-item.active:hover .list-group-item-heading>small,
    .list-group-item.active:focus .list-group-item-heading>small,
    .list-group-item.active .list-group-item-heading>.small,
    .list-group-item.active:hover .list-group-item-heading>.small,
    .list-group-item.active:focus .list-group-item-heading>.small {
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
      background-color: #fff;
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

    .panel-heading>.dropdown .dropdown-toggle {
      color: inherit;
    }

    .panel-title {
      margin-top: 0;
      margin-bottom: 0;
      font-size: 15px;
      color: inherit;
    }

    .panel-title>a,
    .panel-title>small,
    .panel-title>.small,
    .panel-title>small>a,
    .panel-title>.small>a {
      color: inherit;
    }

    .panel-footer {
      padding: 10px 15px;
      background-color: #f5f5f5;
      border-top: 1px solid #ddd;
      border-bottom-right-radius: 1px;
      border-bottom-left-radius: 1px;
    }

    .panel>.list-group,
    .panel>.panel-collapse>.list-group {
      margin-bottom: 0;
    }

    .panel>.list-group .list-group-item,
    .panel>.panel-collapse>.list-group .list-group-item {
      border-width: 1px 0;
      border-radius: 0;
    }

    .panel>.list-group:first-child .list-group-item:first-child,
    .panel>.panel-collapse>.list-group:first-child .list-group-item:first-child {
      border-top: 0;
      border-top-right-radius: 1px;
      border-top-left-radius: 1px;
    }

    .panel>.list-group:last-child .list-group-item:last-child,
    .panel>.panel-collapse>.list-group:last-child .list-group-item:last-child {
      border-bottom: 0;
      border-bottom-right-radius: 1px;
      border-bottom-left-radius: 1px;
    }

    .panel>.panel-heading+.panel-collapse>.list-group .list-group-item:first-child {
      border-top-right-radius: 0;
      border-top-left-radius: 0;
    }

    .panel-heading+.list-group .list-group-item:first-child {
      border-top-width: 0;
    }

    .list-group+.panel-footer {
      border-top-width: 0;
    }

    .panel>.table,
    .panel>.table-responsive>.table,
    .panel>.panel-collapse>.table {
      margin-bottom: 0;
    }

    .panel>.table caption,
    .panel>.table-responsive>.table caption,
    .panel>.panel-collapse>.table caption {
      padding-left: 15px;
      padding-right: 15px;
    }

    .panel>.table:first-child,
    .panel>.table-responsive:first-child>.table:first-child {
      border-top-right-radius: 1px;
      border-top-left-radius: 1px;
    }

    .panel>.table:first-child>thead:first-child>tr:first-child,
    .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child,
    .panel>.table:first-child>tbody:first-child>tr:first-child,
    .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child {
      border-top-left-radius: 1px;
      border-top-right-radius: 1px;
    }

    .panel>.table:first-child>thead:first-child>tr:first-child td:first-child,
    .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:first-child,
    .panel>.table:first-child>tbody:first-child>tr:first-child td:first-child,
    .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:first-child,
    .panel>.table:first-child>thead:first-child>tr:first-child th:first-child,
    .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:first-child,
    .panel>.table:first-child>tbody:first-child>tr:first-child th:first-child,
    .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:first-child {
      border-top-left-radius: 1px;
    }

    .panel>.table:first-child>thead:first-child>tr:first-child td:last-child,
    .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:last-child,
    .panel>.table:first-child>tbody:first-child>tr:first-child td:last-child,
    .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:last-child,
    .panel>.table:first-child>thead:first-child>tr:first-child th:last-child,
    .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:last-child,
    .panel>.table:first-child>tbody:first-child>tr:first-child th:last-child,
    .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:last-child {
      border-top-right-radius: 1px;
    }

    .panel>.table:last-child,
    .panel>.table-responsive:last-child>.table:last-child {
      border-bottom-right-radius: 1px;
      border-bottom-left-radius: 1px;
    }

    .panel>.table:last-child>tbody:last-child>tr:last-child,
    .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child,
    .panel>.table:last-child>tfoot:last-child>tr:last-child,
    .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child {
      border-bottom-left-radius: 1px;
      border-bottom-right-radius: 1px;
    }

    .panel>.table:last-child>tbody:last-child>tr:last-child td:first-child,
    .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:first-child,
    .panel>.table:last-child>tfoot:last-child>tr:last-child td:first-child,
    .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:first-child,
    .panel>.table:last-child>tbody:last-child>tr:last-child th:first-child,
    .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:first-child,
    .panel>.table:last-child>tfoot:last-child>tr:last-child th:first-child,
    .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:first-child {
      border-bottom-left-radius: 1px;
    }

    .panel>.table:last-child>tbody:last-child>tr:last-child td:last-child,
    .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:last-child,
    .panel>.table:last-child>tfoot:last-child>tr:last-child td:last-child,
    .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:last-child,
    .panel>.table:last-child>tbody:last-child>tr:last-child th:last-child,
    .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:last-child,
    .panel>.table:last-child>tfoot:last-child>tr:last-child th:last-child,
    .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:last-child {
      border-bottom-right-radius: 1px;
    }

    .panel>.panel-body+.table,
    .panel>.panel-body+.table-responsive,
    .panel>.table+.panel-body,
    .panel>.table-responsive+.panel-body {
      border-top: 1px solid #ddd;
    }

    .panel>.table>tbody:first-child>tr:first-child th,
    .panel>.table>tbody:first-child>tr:first-child td {
      border-top: 0;
    }

    .panel>.table-bordered,
    .panel>.table-responsive>.table-bordered {
      border: 0;
    }

    .panel>.table-bordered>thead>tr>th:first-child,
    .panel>.table-responsive>.table-bordered>thead>tr>th:first-child,
    .panel>.table-bordered>tbody>tr>th:first-child,
    .panel>.table-responsive>.table-bordered>tbody>tr>th:first-child,
    .panel>.table-bordered>tfoot>tr>th:first-child,
    .panel>.table-responsive>.table-bordered>tfoot>tr>th:first-child,
    .panel>.table-bordered>thead>tr>td:first-child,
    .panel>.table-responsive>.table-bordered>thead>tr>td:first-child,
    .panel>.table-bordered>tbody>tr>td:first-child,
    .panel>.table-responsive>.table-bordered>tbody>tr>td:first-child,
    .panel>.table-bordered>tfoot>tr>td:first-child,
    .panel>.table-responsive>.table-bordered>tfoot>tr>td:first-child {
      border-left: 0;
    }

    .panel>.table-bordered>thead>tr>th:last-child,
    .panel>.table-responsive>.table-bordered>thead>tr>th:last-child,
    .panel>.table-bordered>tbody>tr>th:last-child,
    .panel>.table-responsive>.table-bordered>tbody>tr>th:last-child,
    .panel>.table-bordered>tfoot>tr>th:last-child,
    .panel>.table-responsive>.table-bordered>tfoot>tr>th:last-child,
    .panel>.table-bordered>thead>tr>td:last-child,
    .panel>.table-responsive>.table-bordered>thead>tr>td:last-child,
    .panel>.table-bordered>tbody>tr>td:last-child,
    .panel>.table-responsive>.table-bordered>tbody>tr>td:last-child,
    .panel>.table-bordered>tfoot>tr>td:last-child,
    .panel>.table-responsive>.table-bordered>tfoot>tr>td:last-child {
      border-right: 0;
    }

    .panel>.table-bordered>thead>tr:first-child>td,
    .panel>.table-responsive>.table-bordered>thead>tr:first-child>td,
    .panel>.table-bordered>tbody>tr:first-child>td,
    .panel>.table-responsive>.table-bordered>tbody>tr:first-child>td,
    .panel>.table-bordered>thead>tr:first-child>th,
    .panel>.table-responsive>.table-bordered>thead>tr:first-child>th,
    .panel>.table-bordered>tbody>tr:first-child>th,
    .panel>.table-responsive>.table-bordered>tbody>tr:first-child>th {
      border-bottom: 0;
    }

    .panel>.table-bordered>tbody>tr:last-child>td,
    .panel>.table-responsive>.table-bordered>tbody>tr:last-child>td,
    .panel>.table-bordered>tfoot>tr:last-child>td,
    .panel>.table-responsive>.table-bordered>tfoot>tr:last-child>td,
    .panel>.table-bordered>tbody>tr:last-child>th,
    .panel>.table-responsive>.table-bordered>tbody>tr:last-child>th,
    .panel>.table-bordered>tfoot>tr:last-child>th,
    .panel>.table-responsive>.table-bordered>tfoot>tr:last-child>th {
      border-bottom: 0;
    }

    .panel>.table-responsive {
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

    .panel-group .panel+.panel {
      margin-top: 5px;
    }

    .panel-group .panel-heading {
      border-bottom: 0;
    }

    .panel-group .panel-heading+.panel-collapse>.panel-body,
    .panel-group .panel-heading+.panel-collapse>.list-group {
      border-top: 1px solid #ddd;
    }

    .panel-group .panel-footer {
      border-top: 0;
    }

    .panel-group .panel-footer+.panel-collapse .panel-body {
      border-bottom: 1px solid #ddd;
    }

    .panel-default {
      border-color: #ddd;
    }

    .panel-default>.panel-heading {
      color: #333333;
      background-color: #f5f5f5;
      border-color: #ddd;
    }

    .panel-default>.panel-heading+.panel-collapse>.panel-body {
      border-top-color: #ddd;
    }

    .panel-default>.panel-heading .badge {
      color: #f5f5f5;
      background-color: #333333;
    }

    .panel-default>.panel-footer+.panel-collapse>.panel-body {
      border-bottom-color: #ddd;
    }

    .panel-primary {
      border-color: #337ab7;
    }

    .panel-primary>.panel-heading {
      color: #fff;
      background-color: #337ab7;
      border-color: #337ab7;
    }

    .panel-primary>.panel-heading+.panel-collapse>.panel-body {
      border-top-color: #337ab7;
    }

    .panel-primary>.panel-heading .badge {
      color: #337ab7;
      background-color: #fff;
    }

    .panel-primary>.panel-footer+.panel-collapse>.panel-body {
      border-bottom-color: #337ab7;
    }

    .panel-success {
      border-color: #d6e9c6;
    }

    .panel-success>.panel-heading {
      color: #3c763d;
      background-color: #dff0d8;
      border-color: #d6e9c6;
    }

    .panel-success>.panel-heading+.panel-collapse>.panel-body {
      border-top-color: #d6e9c6;
    }

    .panel-success>.panel-heading .badge {
      color: #dff0d8;
      background-color: #3c763d;
    }

    .panel-success>.panel-footer+.panel-collapse>.panel-body {
      border-bottom-color: #d6e9c6;
    }

    .panel-info {
      border-color: #bce8f1;
    }

    .panel-info>.panel-heading {
      color: #31708f;
      background-color: #d9edf7;
      border-color: #bce8f1;
    }

    .panel-info>.panel-heading+.panel-collapse>.panel-body {
      border-top-color: #bce8f1;
    }

    .panel-info>.panel-heading .badge {
      color: #d9edf7;
      background-color: #31708f;
    }

    .panel-info>.panel-footer+.panel-collapse>.panel-body {
      border-bottom-color: #bce8f1;
    }

    .panel-warning {
      border-color: #faebcc;
    }

    .panel-warning>.panel-heading {
      color: #8a6d3b;
      background-color: #fcf8e3;
      border-color: #faebcc;
    }

    .panel-warning>.panel-heading+.panel-collapse>.panel-body {
      border-top-color: #faebcc;
    }

    .panel-warning>.panel-heading .badge {
      color: #fcf8e3;
      background-color: #8a6d3b;
    }

    .panel-warning>.panel-footer+.panel-collapse>.panel-body {
      border-bottom-color: #faebcc;
    }

    .panel-danger {
      border-color: #ebccd1;
    }

    .panel-danger>.panel-heading {
      color: #a94442;
      background-color: #f2dede;
      border-color: #ebccd1;
    }

    .panel-danger>.panel-heading+.panel-collapse>.panel-body {
      border-top-color: #ebccd1;
    }

    .panel-danger>.panel-heading .badge {
      color: #f2dede;
      background-color: #a94442;
    }

    .panel-danger>.panel-footer+.panel-collapse>.panel-body {
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
      color: #000;
      text-shadow: 0 1px 0 #fff;
      opacity: 0.2;
      filter: alpha(opacity=20);
    }

    .close:hover,
    .close:focus {
      color: #000;
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
      background-color: #fff;
      border: 1px solid #999;
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
      background-color: #000;
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

    .modal-footer .btn+.btn {
      margin-left: 5px;
      margin-bottom: 0;
    }

    .modal-footer .btn-group .btn+.btn {
      margin-left: -1px;
    }

    .modal-footer .btn-block+.btn-block {
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
      color: #fff;
      text-align: center;
      background-color: #000;
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
      border-top-color: #000;
    }

    .tooltip.top-left .tooltip-arrow {
      bottom: 0;
      right: 5px;
      margin-bottom: -5px;
      border-width: 5px 5px 0;
      border-top-color: #000;
    }

    .tooltip.top-right .tooltip-arrow {
      bottom: 0;
      left: 5px;
      margin-bottom: -5px;
      border-width: 5px 5px 0;
      border-top-color: #000;
    }

    .tooltip.right .tooltip-arrow {
      top: 50%;
      left: 0;
      margin-top: -5px;
      border-width: 5px 5px 5px 0;
      border-right-color: #000;
    }

    .tooltip.left .tooltip-arrow {
      top: 50%;
      right: 0;
      margin-top: -5px;
      border-width: 5px 0 5px 5px;
      border-left-color: #000;
    }

    .tooltip.bottom .tooltip-arrow {
      top: 0;
      left: 50%;
      margin-left: -5px;
      border-width: 0 5px 5px;
      border-bottom-color: #000;
    }

    .tooltip.bottom-left .tooltip-arrow {
      top: 0;
      right: 5px;
      margin-top: -5px;
      border-width: 0 5px 5px;
      border-bottom-color: #000;
    }

    .tooltip.bottom-right .tooltip-arrow {
      top: 0;
      left: 5px;
      margin-top: -5px;
      border-width: 0 5px 5px;
      border-bottom-color: #000;
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
      background-color: #fff;
      background-clip: padding-box;
      border: 1px solid #ccc;
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

    .popover>.arrow,
    .popover>.arrow:after {
      position: absolute;
      display: block;
      width: 0;
      height: 0;
      border-color: transparent;
      border-style: solid;
    }

    .popover>.arrow {
      border-width: 11px;
    }

    .popover>.arrow:after {
      border-width: 10px;
      content: "";
    }

    .popover.top>.arrow {
      left: 50%;
      margin-left: -11px;
      border-bottom-width: 0;
      border-top-color: #999999;
      border-top-color: rgba(0, 0, 0, 0.25);
      bottom: -11px;
    }

    .popover.top>.arrow:after {
      content: " ";
      bottom: 1px;
      margin-left: -10px;
      border-bottom-width: 0;
      border-top-color: #fff;
    }

    .popover.right>.arrow {
      top: 50%;
      left: -11px;
      margin-top: -11px;
      border-left-width: 0;
      border-right-color: #999999;
      border-right-color: rgba(0, 0, 0, 0.25);
    }

    .popover.right>.arrow:after {
      content: " ";
      left: 1px;
      bottom: -10px;
      border-left-width: 0;
      border-right-color: #fff;
    }

    .popover.bottom>.arrow {
      left: 50%;
      margin-left: -11px;
      border-top-width: 0;
      border-bottom-color: #999999;
      border-bottom-color: rgba(0, 0, 0, 0.25);
      top: -11px;
    }

    .popover.bottom>.arrow:after {
      content: " ";
      top: 1px;
      margin-left: -10px;
      border-top-width: 0;
      border-bottom-color: #fff;
    }

    .popover.left>.arrow {
      top: 50%;
      right: -11px;
      margin-top: -11px;
      border-right-width: 0;
      border-left-color: #999999;
      border-left-color: rgba(0, 0, 0, 0.25);
    }

    .popover.left>.arrow:after {
      content: " ";
      right: 1px;
      border-right-width: 0;
      border-left-color: #fff;
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

    .carousel-inner>.item {
      display: none;
      position: relative;
      -webkit-transition: 0.6s ease-in-out left;
      -o-transition: 0.6s ease-in-out left;
      transition: 0.6s ease-in-out left;
    }

    .carousel-inner>.item>img,
    .carousel-inner>.item>a>img {
      line-height: 1;
    }

    @media all and (transform-3d),
    (-webkit-transform-3d) {
      .carousel-inner>.item {
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

      .carousel-inner>.item.next,
      .carousel-inner>.item.active.right {
        -webkit-transform: translate3d(100%, 0, 0);
        transform: translate3d(100%, 0, 0);
        left: 0;
      }

      .carousel-inner>.item.prev,
      .carousel-inner>.item.active.left {
        -webkit-transform: translate3d(-100%, 0, 0);
        transform: translate3d(-100%, 0, 0);
        left: 0;
      }

      .carousel-inner>.item.next.left,
      .carousel-inner>.item.prev.right,
      .carousel-inner>.item.active {
        -webkit-transform: translate3d(0, 0, 0);
        transform: translate3d(0, 0, 0);
        left: 0;
      }
    }

    .carousel-inner>.active,
    .carousel-inner>.next,
    .carousel-inner>.prev {
      display: block;
    }

    .carousel-inner>.active {
      left: 0;
    }

    .carousel-inner>.next,
    .carousel-inner>.prev {
      position: absolute;
      top: 0;
      width: 100%;
    }

    .carousel-inner>.next {
      left: 100%;
    }

    .carousel-inner>.prev {
      left: -100%;
    }

    .carousel-inner>.next.left,
    .carousel-inner>.prev.right {
      left: 0;
    }

    .carousel-inner>.active.left {
      left: -100%;
    }

    .carousel-inner>.active.right {
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
      color: #fff;
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
      color: #fff;
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
      border: 1px solid #fff;
      border-radius: 10px;
      cursor: pointer;
      background-color: #000 \9;
      background-color: rgba(0, 0, 0, 0);
    }

    .carousel-indicators .active {
      margin: 0;
      width: 12px;
      height: 12px;
      background-color: #fff;
    }

    .carousel-caption {
      position: absolute;
      left: 15%;
      right: 15%;
      bottom: 20px;
      z-index: 10;
      padding-top: 20px;
      padding-bottom: 20px;
      color: #fff;
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
    .btn-group-vertical>.btn-group:before,
    .btn-group-vertical>.btn-group:after,
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
    .btn-group-vertical>.btn-group:after,
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

    .fa-ul>li {
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
      border: solid 0.08em #eee;
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
      color: #fff;
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
      color: #000;
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

    .hbox>* {
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

    .vbox>* {
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

    div.error>h1 {
      font-size: 500%;
      line-height: normal;
    }

    div.error>p {
      font-size: 200%;
      line-height: normal;
    }

    div.traceback-wrapper {
      text-align: left;
      max-width: 800px;
      margin: auto;
    }

    div.traceback-wrapper pre.traceback {
      max-height: 600px;
      overflow: auto;
    }

    /**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
    body {
      background-color: #337ab7;
      /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
      position: absolute;
      left: 0px;
      right: 0px;
      top: 0px;
      bottom: 0px;
      overflow: visible;
    }

    body>#header {
      /* Initially hidden to prevent FLOUC */
      display: none;
      background-color: #fff;
      /* Display over codemirror */
      position: relative;
      z-index: 100;
    }

    body>#header #header-container {
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      padding: 5px;
      padding-bottom: 5px;
      padding-top: 5px;
      box-sizing: border-box;
      -moz-box-sizing: border-box;
      -webkit-box-sizing: border-box;
    }

    body>#header .header-bar {
      width: 100%;
      height: 1px;
      background: #e7e7e7;
      margin-bottom: -1px;
    }

    @media print {
      body>#header {
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

    [dir="rtl"] #ipython_notebook {
      margin-right: 10px;
      margin-left: 0;
    }

    [dir="rtl"] #ipython_notebook.pull-left {
      float: right !important;
      float: right;
    }

    .flex-spacer {
      flex: 1;
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

    span#kernel_logo_widget {
      margin: 0 10px;
    }

    span#login_widget {
      float: right;
    }

    [dir="rtl"] span#login_widget {
      float: left;
    }

    span#login_widget>.button,
    #logout {
      color: #333;
      background-color: #fff;
      border-color: #ccc;
    }

    span#login_widget>.button:focus,
    #logout:focus,
    span#login_widget>.button.focus,
    #logout.focus {
      color: #333;
      background-color: #e6e6e6;
      border-color: #8c8c8c;
    }

    span#login_widget>.button:hover,
    #logout:hover {
      color: #333;
      background-color: #e6e6e6;
      border-color: #adadad;
    }

    span#login_widget>.button:active,
    #logout:active,
    span#login_widget>.button.active,
    #logout.active,
    .open>.dropdown-togglespan#login_widget>.button,
    .open>.dropdown-toggle#logout {
      color: #333;
      background-color: #e6e6e6;
      border-color: #adadad;
    }

    span#login_widget>.button:active:hover,
    #logout:active:hover,
    span#login_widget>.button.active:hover,
    #logout.active:hover,
    .open>.dropdown-togglespan#login_widget>.button:hover,
    .open>.dropdown-toggle#logout:hover,
    span#login_widget>.button:active:focus,
    #logout:active:focus,
    span#login_widget>.button.active:focus,
    #logout.active:focus,
    .open>.dropdown-togglespan#login_widget>.button:focus,
    .open>.dropdown-toggle#logout:focus,
    span#login_widget>.button:active.focus,
    #logout:active.focus,
    span#login_widget>.button.active.focus,
    #logout.active.focus,
    .open>.dropdown-togglespan#login_widget>.button.focus,
    .open>.dropdown-toggle#logout.focus {
      color: #333;
      background-color: #d4d4d4;
      border-color: #8c8c8c;
    }

    span#login_widget>.button:active,
    #logout:active,
    span#login_widget>.button.active,
    #logout.active,
    .open>.dropdown-togglespan#login_widget>.button,
    .open>.dropdown-toggle#logout {
      background-image: none;
    }

    span#login_widget>.button.disabled:hover,
    #logout.disabled:hover,
    span#login_widget>.button[disabled]:hover,
    #logout[disabled]:hover,
    fieldset[disabled] span#login_widget>.button:hover,
    fieldset[disabled] #logout:hover,
    span#login_widget>.button.disabled:focus,
    #logout.disabled:focus,
    span#login_widget>.button[disabled]:focus,
    #logout[disabled]:focus,
    fieldset[disabled] span#login_widget>.button:focus,
    fieldset[disabled] #logout:focus,
    span#login_widget>.button.disabled.focus,
    #logout.disabled.focus,
    span#login_widget>.button[disabled].focus,
    #logout[disabled].focus,
    fieldset[disabled] span#login_widget>.button.focus,
    fieldset[disabled] #logout.focus {
      background-color: #fff;
      border-color: #ccc;
    }

    span#login_widget>.button .badge,
    #logout .badge {
      color: #fff;
      background-color: #333;
    }

    .nav-header {
      text-transform: none;
    }

    #header>span {
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
      min-height: 80vh;
    }

    .modal_stretch .modal-dialog .modal-body {
      max-height: calc(100vh - 200px);
      overflow: auto;
      flex: 1;
    }

    .modal-header {
      cursor: move;
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

    [dir="rtl"] .center-nav form.pull-left {
      float: right !important;
      float: right;
    }

    [dir="rtl"] .center-nav .navbar-text {
      float: right;
    }

    [dir="rtl"] .navbar-inner {
      text-align: right;
    }

    [dir="rtl"] div.text-left {
      text-align: right;
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
      position: absolute;
      display: block;
      width: 100%;
      height: 100%;
      overflow: hidden;
      cursor: pointer;
      opacity: 0;
      z-index: 2;
    }

    .alternate_upload .btn-xs>input.fileinput {
      margin: -1px -5px;
    }

    .alternate_upload .btn-upload {
      position: relative;
      height: 22px;
    }

    ::-webkit-file-upload-button {
      cursor: pointer;
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

    [dir="rtl"] ul#tabs.nav-tabs>li {
      float: right;
    }

    [dir="rtl"] ul#tabs.nav.nav-tabs {
      padding-right: 0;
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

    [dir="rtl"] .list_toolbar .tree-buttons .pull-right {
      float: left !important;
      float: left;
    }

    [dir="rtl"] .list_toolbar .col-sm-4,
    [dir="rtl"] .list_toolbar .col-sm-8 {
      float: right;
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
      background-color: #EEE;
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
      border: 1px solid #ddd;
      border-radius: 2px;
    }

    .list_container>div {
      border-bottom: 1px solid #ddd;
    }

    .list_container>div:hover .list-item {
      background-color: red;
    }

    .list_container>div:last-child {
      border: none;
    }

    .list_item:hover .list_item {
      background-color: #ddd;
    }

    .list_item a {
      text-decoration: none;
    }

    .list_item:hover {
      background-color: #fafafa;
    }

    .list_header>div,
    .list_item>div {
      padding-top: 4px;
      padding-bottom: 4px;
      padding-left: 7px;
      padding-right: 7px;
      line-height: 22px;
    }

    .list_header>div input,
    .list_item>div input {
      margin-right: 7px;
      margin-left: 14px;
      vertical-align: text-bottom;
      line-height: 22px;
      position: relative;
      top: -1px;
    }

    .list_header>div .item_link,
    .list_item>div .item_link {
      margin-left: -1px;
      vertical-align: baseline;
      line-height: 22px;
    }

    [dir="rtl"] .list_item>div input {
      margin-right: 0;
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

    .item_modified {
      margin-right: 7px;
      margin-left: 7px;
    }

    [dir="rtl"] .item_modified.pull-right {
      float: left !important;
      float: left;
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

    .item_buttons>.btn,
    .item_buttons>.btn-group,
    .item_buttons>.input-group {
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

    [dir="rtl"] .item_buttons.pull-right {
      float: left !important;
      float: left;
    }

    [dir="rtl"] .item_buttons .kernel-name {
      margin-left: 7px;
      float: right;
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

    #project_name>.breadcrumb {
      padding: 0px;
      margin-bottom: 0px;
      background-color: transparent;
      font-weight: bold;
    }

    .sort_button {
      display: inline-block;
      padding-left: 7px;
    }

    [dir="rtl"] .sort_button.pull-right {
      float: left !important;
      float: left;
    }

    #tree-selector {
      padding-right: 0px;
    }

    #button-select-all {
      min-width: 50px;
    }

    [dir="rtl"] #button-select-all.btn {
      float: right;
    }

    #select-all {
      margin-left: 7px;
      margin-right: 2px;
      margin-top: 2px;
      height: 16px;
    }

    [dir="rtl"] #select-all.pull-left {
      float: right !important;
      float: right;
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

    #new-menu .dropdown-header {
      font-size: 10px;
      border-bottom: 1px solid #e5e5e5;
      padding: 0 0 3px;
      margin: -3px 20px 0;
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
      background-color: #EEE;
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
      border-bottom: 1px solid #ddd;
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

    .move-button {
      display: none;
    }

    .download-button {
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
        background-color: #EEE;
      }
    }

    @media print {

      #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
      #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
        background-color: #fff;
      }
    }

    @media not print {

      #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
      #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
        background-color: #fff;
      }
    }

    @media not print {
      #texteditor-backdrop #texteditor-container {
        padding: 0px;
        background-color: #fff;
        -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
        box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
      }
    }

    .CodeMirror-dialog {
      background-color: #fff;
    }

    /*!
*
* IPython notebook
*
*/
    /* CSS font colors for translated ANSI escape sequences */
    /* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
    .ansi-black-fg {
      color: #3E424D;
    }

    .ansi-black-bg {
      background-color: #3E424D;
    }

    .ansi-black-intense-fg {
      color: #282C36;
    }

    .ansi-black-intense-bg {
      background-color: #282C36;
    }

    .ansi-red-fg {
      color: #E75C58;
    }

    .ansi-red-bg {
      background-color: #E75C58;
    }

    .ansi-red-intense-fg {
      color: #B22B31;
    }

    .ansi-red-intense-bg {
      background-color: #B22B31;
    }

    .ansi-green-fg {
      color: #00A250;
    }

    .ansi-green-bg {
      background-color: #00A250;
    }

    .ansi-green-intense-fg {
      color: #007427;
    }

    .ansi-green-intense-bg {
      background-color: #007427;
    }

    .ansi-yellow-fg {
      color: #DDB62B;
    }

    .ansi-yellow-bg {
      background-color: #DDB62B;
    }

    .ansi-yellow-intense-fg {
      color: #B27D12;
    }

    .ansi-yellow-intense-bg {
      background-color: #B27D12;
    }

    .ansi-blue-fg {
      color: #208FFB;
    }

    .ansi-blue-bg {
      background-color: #208FFB;
    }

    .ansi-blue-intense-fg {
      color: #0065CA;
    }

    .ansi-blue-intense-bg {
      background-color: #0065CA;
    }

    .ansi-magenta-fg {
      color: #D160C4;
    }

    .ansi-magenta-bg {
      background-color: #D160C4;
    }

    .ansi-magenta-intense-fg {
      color: #A03196;
    }

    .ansi-magenta-intense-bg {
      background-color: #A03196;
    }

    .ansi-cyan-fg {
      color: #60C6C8;
    }

    .ansi-cyan-bg {
      background-color: #60C6C8;
    }

    .ansi-cyan-intense-fg {
      color: #258F8F;
    }

    .ansi-cyan-intense-bg {
      background-color: #258F8F;
    }

    .ansi-white-fg {
      color: #C5C1B4;
    }

    .ansi-white-bg {
      background-color: #C5C1B4;
    }

    .ansi-white-intense-fg {
      color: #A1A6B2;
    }

    .ansi-white-intense-bg {
      background-color: #A1A6B2;
    }

    .ansi-default-inverse-fg {
      color: #FFFFFF;
    }

    .ansi-default-inverse-bg {
      background-color: #000000;
    }

    .ansi-bold {
      font-weight: bold;
    }

    .ansi-underline {
      text-decoration: underline;
    }

    /* The following styles are deprecated an will be removed in a future version */
    .ansibold {
      font-weight: bold;
    }

    .ansi-inverse {
      outline: 0.5px dotted;
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
      position: relative;
      overflow: visible;
    }

    div.cell:before {
      position: absolute;
      display: block;
      top: -1px;
      left: -1px;
      width: 5px;
      height: calc(100% + 2px);
      content: '';
      background: transparent;
    }

    div.cell.jupyter-soft-selected {
      border-left-color: #E3F2FD;
      border-left-width: 1px;
      padding-left: 5px;
      border-right-color: #E3F2FD;
      border-right-width: 1px;
      background: #E3F2FD;
    }

    @media print {
      div.cell.jupyter-soft-selected {
        border-color: transparent;
      }
    }

    div.cell.selected,
    div.cell.selected.jupyter-soft-selected {
      border-color: #ababab;
    }

    div.cell.selected:before,
    div.cell.selected.jupyter-soft-selected:before {
      position: absolute;
      display: block;
      top: -1px;
      left: -1px;
      width: 5px;
      height: calc(100% + 2px);
      content: '';
      background: #42A5F5;
    }

    @media print {

      div.cell.selected,
      div.cell.selected.jupyter-soft-selected {
        border-color: transparent;
      }
    }

    .edit_mode div.cell.selected {
      border-color: #66BB6A;
    }

    .edit_mode div.cell.selected:before {
      position: absolute;
      display: block;
      top: -1px;
      left: -1px;
      width: 5px;
      height: calc(100% + 2px);
      content: '';
      background: #66BB6A;
    }

    @media print {
      .edit_mode div.cell.selected {
        border-color: transparent;
      }
    }

    .prompt {
      /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
      /* min-width: 14ex; */
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
      div.unrecognized_cell>div.prompt {
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
      }
    }

    /* input_area and input_prompt must match in top border and margin for alignment */
    div.input_prompt {
      color: #303F9F;
      border-top: 1px solid transparent;
    }

    div.input_area>div.highlight {
      margin: 0.4em;
      border: none;
      padding: 0px;
      background-color: transparent;
    }

    div.input_area>div.highlight>pre {
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
      /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
      padding: 0.4em 0;
    }

    .CodeMirror-linenumber {
      padding: 0 8px 0 4px;
    }

    .CodeMirror-gutters {
      border-bottom-left-radius: 2px;
      border-top-left-radius: 2px;
    }

    .CodeMirror pre {
      /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
      padding: 0 0.4em;
      border: 0;
      border-radius: 0;
    }

    .CodeMirror-cursor {
      border-left: 1.4px solid black;
    }

    @media screen and (min-width: 2138px) and (max-width: 4319px) {
      .CodeMirror-cursor {
        border-left: 2px solid black;
      }
    }

    @media screen and (min-width: 4320px) {
      .CodeMirror-cursor {
        border-left: 4px solid black;
      }
    }

    /*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
    .highlight-base {
      color: #000;
    }

    .highlight-variable {
      color: #000;
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
      color: #000;
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
    }

    div.out_prompt_overlay {
      height: 100%;
      padding: 0px 0.4em;
      position: absolute;
      border-radius: 2px;
    }

    div.out_prompt_overlay:hover {
      /* use inner shadow to get border that is computed the same on WebKit/FF */
      -webkit-box-shadow: inset 0 0 1px #000;
      box-shadow: inset 0 0 1px #000;
      background: rgba(240, 240, 240, 0.5);
    }

    div.output_prompt {
      color: #D84315;
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

    div.output_area .mglyph>img {
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
      }
    }

    div.output_area pre {
      margin: 0;
      padding: 1px 0 1px 0;
      border: 0;
      vertical-align: baseline;
      color: black;
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
      color: #000;
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
      color: #000;
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

    .rendered_html ul:not(.list-inline),
    .rendered_html ol:not(.list-inline) {
      padding-left: 2em;
    }

    .rendered_html ul {
      list-style: disc;
    }

    .rendered_html ul ul {
      list-style: square;
      margin-top: 0;
    }

    .rendered_html ul ul ul {
      list-style: circle;
    }

    .rendered_html ol {
      list-style: decimal;
    }

    .rendered_html ol ol {
      list-style: upper-alpha;
      margin-top: 0;
    }

    .rendered_html ol ol ol {
      list-style: lower-alpha;
    }

    .rendered_html ol ol ol ol {
      list-style: lower-roman;
    }

    .rendered_html ol ol ol ol ol {
      list-style: decimal;
    }

    .rendered_html *+ul {
      margin-top: 1em;
    }

    .rendered_html *+ol {
      margin-top: 1em;
    }

    .rendered_html hr {
      color: black;
      background-color: black;
    }

    .rendered_html pre {
      margin: 1em 2em;
      padding: 0px;
      background-color: #fff;
    }

    .rendered_html code {
      background-color: #eff0f1;
    }

    .rendered_html p code {
      padding: 1px 5px;
    }

    .rendered_html pre code {
      background-color: #fff;
    }

    .rendered_html pre,
    .rendered_html code {
      border: 0;
      color: #000;
      font-size: 100%;
    }

    .rendered_html blockquote {
      margin: 1em 2em;
    }

    .rendered_html table {
      margin-left: auto;
      margin-right: auto;
      border: none;
      border-collapse: collapse;
      border-spacing: 0;
      color: black;
      font-size: 12px;
      table-layout: fixed;
    }

    .rendered_html thead {
      border-bottom: 1px solid black;
      vertical-align: bottom;
    }

    .rendered_html tr,
    .rendered_html th,
    .rendered_html td {
      text-align: right;
      vertical-align: middle;
      padding: 0.5em 0.5em;
      line-height: normal;
      white-space: normal;
      max-width: none;
      border: none;
    }

    .rendered_html th {
      font-weight: bold;
    }

    .rendered_html tbody tr:nth-child(odd) {
      background: #f5f5f5;
    }

    .rendered_html tbody tr:hover {
      background: rgba(66, 165, 245, 0.2);
    }

    .rendered_html *+table {
      margin-top: 1em;
    }

    .rendered_html p {
      text-align: left;
    }

    .rendered_html *+p {
      margin-top: 1em;
    }

    .rendered_html img {
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    .rendered_html *+img {
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

    .rendered_html .alert {
      margin-bottom: initial;
    }

    .rendered_html *+.alert {
      margin-top: 1em;
    }

    [dir="rtl"] .rendered_html p {
      text-align: right;
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
    }

    @media (max-width: 540px) {
      div.text_cell>div.prompt {
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
      color: #000;
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

    .text_cell.rendered .rendered_html tr,
    .text_cell.rendered .rendered_html th,
    .text_cell.rendered .rendered_html td {
      max-width: none;
    }

    .text_cell.unrendered .text_cell_render {
      display: none;
    }

    .text_cell .dropzone .input_area {
      border: 2px dashed #bababa;
      margin: -1px;
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
        background-color: #fff;
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

    .notebook_app>#header {
      -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
      box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    }

    @media not print {
      .notebook_app {
        background-color: #EEE;
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

    .jupyter-keybindings {
      padding: 1px;
      line-height: 24px;
      border-bottom: 1px solid gray;
    }

    .jupyter-keybindings input {
      margin: 0;
      padding: 0;
      border: none;
    }

    .jupyter-keybindings i {
      padding: 6px;
    }

    .well code {
      background-color: #ffffff;
      border-color: #ababab;
      border-width: 1px;
      border-style: solid;
      padding: 2px;
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

    .ctb_global_show .ctb_show+.input_area,
    .ctb_global_show .ctb_show+div.text_cell_input,
    .ctb_global_show .ctb_show~div.text_cell_render {
      border-top-right-radius: 0px;
      border-top-left-radius: 0px;
    }

    .ctb_global_show .ctb_show~div.text_cell_render {
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
      background-color: #fff;
      background-image: none;
      border: 1px solid #ccc;
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
      -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, 0.6);
      box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, 0.6);
    }

    .celltoolbar select::-moz-placeholder {
      color: #999;
      opacity: 1;
    }

    .celltoolbar select:-ms-input-placeholder {
      color: #999;
    }

    .celltoolbar select::-webkit-input-placeholder {
      color: #999;
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

    .tags_button_container {
      width: 100%;
      display: flex;
    }

    .tag-container {
      display: flex;
      flex-direction: row;
      flex-grow: 1;
      overflow: hidden;
      position: relative;
    }

    .tag-container>* {
      margin: 0 4px;
    }

    .remove-tag-btn {
      margin-left: 4px;
    }

    .tags-input {
      display: flex;
    }

    .cell-tag:last-child:after {
      content: "";
      position: absolute;
      right: 0;
      width: 40px;
      height: 100%;
      /* Fade to background color of cell toolbar */
      background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
    }

    .tags-input>* {
      margin-left: 4px;
    }

    .cell-tag,
    .tags-input input,
    .tags-input button {
      display: block;
      width: 100%;
      height: 32px;
      padding: 6px 12px;
      font-size: 13px;
      line-height: 1.42857143;
      color: #555555;
      background-color: #fff;
      background-image: none;
      border: 1px solid #ccc;
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
      box-shadow: none;
      width: inherit;
      font-size: inherit;
      height: 22px;
      line-height: 22px;
      padding: 0px 4px;
      display: inline-block;
    }

    .cell-tag:focus,
    .tags-input input:focus,
    .tags-input button:focus {
      border-color: #66afe9;
      outline: 0;
      -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, 0.6);
      box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, 0.6);
    }

    .cell-tag::-moz-placeholder,
    .tags-input input::-moz-placeholder,
    .tags-input button::-moz-placeholder {
      color: #999;
      opacity: 1;
    }

    .cell-tag:-ms-input-placeholder,
    .tags-input input:-ms-input-placeholder,
    .tags-input button:-ms-input-placeholder {
      color: #999;
    }

    .cell-tag::-webkit-input-placeholder,
    .tags-input input::-webkit-input-placeholder,
    .tags-input button::-webkit-input-placeholder {
      color: #999;
    }

    .cell-tag::-ms-expand,
    .tags-input input::-ms-expand,
    .tags-input button::-ms-expand {
      border: 0;
      background-color: transparent;
    }

    .cell-tag[disabled],
    .tags-input input[disabled],
    .tags-input button[disabled],
    .cell-tag[readonly],
    .tags-input input[readonly],
    .tags-input button[readonly],
    fieldset[disabled] .cell-tag,
    fieldset[disabled] .tags-input input,
    fieldset[disabled] .tags-input button {
      background-color: #eeeeee;
      opacity: 1;
    }

    .cell-tag[disabled],
    .tags-input input[disabled],
    .tags-input button[disabled],
    fieldset[disabled] .cell-tag,
    fieldset[disabled] .tags-input input,
    fieldset[disabled] .tags-input button {
      cursor: not-allowed;
    }

    textarea.cell-tag,
    textarea.tags-input input,
    textarea.tags-input button {
      height: auto;
    }

    select.cell-tag,
    select.tags-input input,
    select.tags-input button {
      height: 30px;
      line-height: 30px;
    }

    textarea.cell-tag,
    textarea.tags-input input,
    textarea.tags-input button,
    select[multiple].cell-tag,
    select[multiple].tags-input input,
    select[multiple].tags-input button {
      height: auto;
    }

    .cell-tag,
    .tags-input button {
      padding: 0px 4px;
    }

    .cell-tag {
      background-color: #fff;
      white-space: nowrap;
    }

    .tags-input input[type=text]:focus {
      outline: none;
      box-shadow: none;
      border-color: #ccc;
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
      color: #000;
      width: auto;
    }

    .completions select option.context {
      color: #286090;
    }

    #kernel_logo_widget .current_kernel_logo {
      display: none;
      margin-top: -1px;
      margin-bottom: -1px;
      width: 32px;
      height: 32px;
    }

    [dir="rtl"] #kernel_logo_widget {
      float: left !important;
      float: left;
    }

    .modal .modal-body .move-path {
      display: flex;
      flex-direction: row;
      justify-content: space;
      align-items: center;
    }

    .modal .modal-body .move-path .server-root {
      padding-right: 20px;
    }

    .modal .modal-body .move-path .path-input {
      flex: 1;
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

    [dir="rtl"] #menubar .navbar-toggle {
      float: right;
    }

    [dir="rtl"] #menubar .navbar-collapse {
      clear: right;
    }

    [dir="rtl"] #menubar .navbar-nav {
      float: right;
    }

    [dir="rtl"] #menubar .nav {
      padding-right: 0px;
    }

    [dir="rtl"] #menubar .navbar-nav>li {
      float: right;
    }

    [dir="rtl"] #menubar .navbar-right {
      float: left !important;
    }

    [dir="rtl"] ul.dropdown-menu {
      text-align: right;
      left: auto;
    }

    [dir="rtl"] ul#new-menu.dropdown-menu {
      right: auto;
      left: 0;
    }

    .nav-wrapper {
      border-bottom: 1px solid #e7e7e7;
    }

    i.menu-icon {
      padding-top: 4px;
    }

    [dir="rtl"] i.menu-icon.pull-right {
      float: left !important;
      float: left;
    }

    ul#help_menu li a {
      overflow: hidden;
      padding-right: 2.2em;
    }

    ul#help_menu li a i {
      margin-right: -1.2em;
    }

    [dir="rtl"] ul#help_menu li a {
      padding-left: 2.2em;
    }

    [dir="rtl"] ul#help_menu li a i {
      margin-right: 0;
      margin-left: -1.2em;
    }

    [dir="rtl"] ul#help_menu li a i.pull-right {
      float: left !important;
      float: left;
    }

    .dropdown-submenu {
      position: relative;
    }

    .dropdown-submenu>.dropdown-menu {
      top: 0;
      left: 100%;
      margin-top: -6px;
      margin-left: -1px;
    }

    [dir="rtl"] .dropdown-submenu>.dropdown-menu {
      right: 100%;
      margin-right: -1px;
    }

    .dropdown-submenu:hover>.dropdown-menu {
      display: block;
    }

    .dropdown-submenu>a:after {
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

    .dropdown-submenu>a:after.fa-pull-left {
      margin-right: .3em;
    }

    .dropdown-submenu>a:after.fa-pull-right {
      margin-left: .3em;
    }

    .dropdown-submenu>a:after.pull-left {
      margin-right: .3em;
    }

    .dropdown-submenu>a:after.pull-right {
      margin-left: .3em;
    }

    [dir="rtl"] .dropdown-submenu>a:after {
      float: left;
      content: "\f0d9";
      margin-right: 0;
      margin-left: -10px;
    }

    .dropdown-submenu:hover>a:after {
      color: #262626;
    }

    .dropdown-submenu.pull-left {
      float: none;
    }

    .dropdown-submenu.pull-left>.dropdown-menu {
      left: -100%;
      margin-left: 10px;
    }

    #notification_area {
      float: right !important;
      float: right;
      z-index: 10;
    }

    [dir="rtl"] #notification_area {
      float: left !important;
      float: left;
    }

    .indicator_area {
      float: right !important;
      float: right;
      color: #777;
      margin-left: 5px;
      margin-right: 5px;
      width: 11px;
      z-index: 10;
      text-align: center;
      width: auto;
    }

    [dir="rtl"] .indicator_area {
      float: left !important;
      float: left;
    }

    #kernel_indicator {
      float: right !important;
      float: right;
      color: #777;
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

    [dir="rtl"] #kernel_indicator {
      float: left !important;
      float: left;
      border-left: 0;
      border-right: 1px solid;
    }

    #modal_indicator {
      float: right !important;
      float: right;
      color: #777;
      margin-left: 5px;
      margin-right: 5px;
      width: 11px;
      z-index: 10;
      text-align: center;
      width: auto;
    }

    [dir="rtl"] #modal_indicator {
      float: left !important;
      float: left;
    }

    #readonly-indicator {
      float: right !important;
      float: right;
      color: #777;
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
      color: #777;
      z-index: 10;
      background: rgba(240, 240, 240, 0.5);
      margin-right: 4px;
      color: #333;
      background-color: #fff;
      border-color: #ccc;
    }

    .notification_widget:focus,
    .notification_widget.focus {
      color: #333;
      background-color: #e6e6e6;
      border-color: #8c8c8c;
    }

    .notification_widget:hover {
      color: #333;
      background-color: #e6e6e6;
      border-color: #adadad;
    }

    .notification_widget:active,
    .notification_widget.active,
    .open>.dropdown-toggle.notification_widget {
      color: #333;
      background-color: #e6e6e6;
      border-color: #adadad;
    }

    .notification_widget:active:hover,
    .notification_widget.active:hover,
    .open>.dropdown-toggle.notification_widget:hover,
    .notification_widget:active:focus,
    .notification_widget.active:focus,
    .open>.dropdown-toggle.notification_widget:focus,
    .notification_widget:active.focus,
    .notification_widget.active.focus,
    .open>.dropdown-toggle.notification_widget.focus {
      color: #333;
      background-color: #d4d4d4;
      border-color: #8c8c8c;
    }

    .notification_widget:active,
    .notification_widget.active,
    .open>.dropdown-toggle.notification_widget {
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
      background-color: #fff;
      border-color: #ccc;
    }

    .notification_widget .badge {
      color: #fff;
      background-color: #333;
    }

    .notification_widget.warning {
      color: #fff;
      background-color: #f0ad4e;
      border-color: #eea236;
    }

    .notification_widget.warning:focus,
    .notification_widget.warning.focus {
      color: #fff;
      background-color: #ec971f;
      border-color: #985f0d;
    }

    .notification_widget.warning:hover {
      color: #fff;
      background-color: #ec971f;
      border-color: #d58512;
    }

    .notification_widget.warning:active,
    .notification_widget.warning.active,
    .open>.dropdown-toggle.notification_widget.warning {
      color: #fff;
      background-color: #ec971f;
      border-color: #d58512;
    }

    .notification_widget.warning:active:hover,
    .notification_widget.warning.active:hover,
    .open>.dropdown-toggle.notification_widget.warning:hover,
    .notification_widget.warning:active:focus,
    .notification_widget.warning.active:focus,
    .open>.dropdown-toggle.notification_widget.warning:focus,
    .notification_widget.warning:active.focus,
    .notification_widget.warning.active.focus,
    .open>.dropdown-toggle.notification_widget.warning.focus {
      color: #fff;
      background-color: #d58512;
      border-color: #985f0d;
    }

    .notification_widget.warning:active,
    .notification_widget.warning.active,
    .open>.dropdown-toggle.notification_widget.warning {
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
      background-color: #fff;
    }

    .notification_widget.success {
      color: #fff;
      background-color: #5cb85c;
      border-color: #4cae4c;
    }

    .notification_widget.success:focus,
    .notification_widget.success.focus {
      color: #fff;
      background-color: #449d44;
      border-color: #255625;
    }

    .notification_widget.success:hover {
      color: #fff;
      background-color: #449d44;
      border-color: #398439;
    }

    .notification_widget.success:active,
    .notification_widget.success.active,
    .open>.dropdown-toggle.notification_widget.success {
      color: #fff;
      background-color: #449d44;
      border-color: #398439;
    }

    .notification_widget.success:active:hover,
    .notification_widget.success.active:hover,
    .open>.dropdown-toggle.notification_widget.success:hover,
    .notification_widget.success:active:focus,
    .notification_widget.success.active:focus,
    .open>.dropdown-toggle.notification_widget.success:focus,
    .notification_widget.success:active.focus,
    .notification_widget.success.active.focus,
    .open>.dropdown-toggle.notification_widget.success.focus {
      color: #fff;
      background-color: #398439;
      border-color: #255625;
    }

    .notification_widget.success:active,
    .notification_widget.success.active,
    .open>.dropdown-toggle.notification_widget.success {
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
      background-color: #fff;
    }

    .notification_widget.info {
      color: #fff;
      background-color: #5bc0de;
      border-color: #46b8da;
    }

    .notification_widget.info:focus,
    .notification_widget.info.focus {
      color: #fff;
      background-color: #31b0d5;
      border-color: #1b6d85;
    }

    .notification_widget.info:hover {
      color: #fff;
      background-color: #31b0d5;
      border-color: #269abc;
    }

    .notification_widget.info:active,
    .notification_widget.info.active,
    .open>.dropdown-toggle.notification_widget.info {
      color: #fff;
      background-color: #31b0d5;
      border-color: #269abc;
    }

    .notification_widget.info:active:hover,
    .notification_widget.info.active:hover,
    .open>.dropdown-toggle.notification_widget.info:hover,
    .notification_widget.info:active:focus,
    .notification_widget.info.active:focus,
    .open>.dropdown-toggle.notification_widget.info:focus,
    .notification_widget.info:active.focus,
    .notification_widget.info.active.focus,
    .open>.dropdown-toggle.notification_widget.info.focus {
      color: #fff;
      background-color: #269abc;
      border-color: #1b6d85;
    }

    .notification_widget.info:active,
    .notification_widget.info.active,
    .open>.dropdown-toggle.notification_widget.info {
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
      background-color: #fff;
    }

    .notification_widget.danger {
      color: #fff;
      background-color: #d9534f;
      border-color: #d43f3a;
    }

    .notification_widget.danger:focus,
    .notification_widget.danger.focus {
      color: #fff;
      background-color: #c9302c;
      border-color: #761c19;
    }

    .notification_widget.danger:hover {
      color: #fff;
      background-color: #c9302c;
      border-color: #ac2925;
    }

    .notification_widget.danger:active,
    .notification_widget.danger.active,
    .open>.dropdown-toggle.notification_widget.danger {
      color: #fff;
      background-color: #c9302c;
      border-color: #ac2925;
    }

    .notification_widget.danger:active:hover,
    .notification_widget.danger.active:hover,
    .open>.dropdown-toggle.notification_widget.danger:hover,
    .notification_widget.danger:active:focus,
    .notification_widget.danger.active:focus,
    .open>.dropdown-toggle.notification_widget.danger:focus,
    .notification_widget.danger:active.focus,
    .notification_widget.danger.active.focus,
    .open>.dropdown-toggle.notification_widget.danger.focus {
      color: #fff;
      background-color: #ac2925;
      border-color: #761c19;
    }

    .notification_widget.danger:active,
    .notification_widget.danger.active,
    .open>.dropdown-toggle.notification_widget.danger {
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
      background-color: #fff;
    }

    div#pager {
      background-color: #fff;
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
      color: #000;
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
      height: 30px;
      margin-top: 4px;
      display: flex;
      justify-content: flex-start;
      align-items: baseline;
      width: 50%;
      flex: 1;
    }

    span.save_widget span.filename {
      height: 100%;
      line-height: 1em;
      margin-left: 16px;
      border: none;
      font-size: 146.5%;
      text-overflow: ellipsis;
      overflow: hidden;
      white-space: nowrap;
      border-radius: 2px;
    }

    span.save_widget span.filename:hover {
      background-color: #e6e6e6;
    }

    [dir="rtl"] span.save_widget.pull-left {
      float: right !important;
      float: right;
    }

    [dir="rtl"] span.save_widget span.filename {
      margin-left: 0;
      margin-right: 16px;
    }

    span.checkpoint_status,
    span.autosave_status {
      font-size: small;
      white-space: nowrap;
      padding: 0 5px;
    }

    @media (max-width: 767px) {
      span.save_widget {
        font-size: small;
        padding: 0 0 0 5px;
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

    .toolbar-btn-label {
      margin-left: 6px;
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

    [dir="rtl"] .btn-group>.btn,
    .btn-group-vertical>.btn {
      float: right;
    }

    .pulse,
    .dropdown-menu>li>a.pulse,
    li.pulse>a.dropdown-toggle,
    li.pulse.open>a.dropdown-toggle {
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

    [dir="rtl"] ul.typeahead-list i {
      margin-left: 0;
      margin-right: -10px;
    }

    ul.typeahead-list {
      max-height: 80vh;
      overflow: auto;
    }

    ul.typeahead-list>li>a {
      /** Firefox bug **/
      /* see https://github.com/jupyter/notebook/issues/559 */
      white-space: normal;
    }

    ul.typeahead-list>li>a.pull-right {
      float: left !important;
      float: left;
    }

    [dir="rtl"] .typeahead-list {
      text-align: right;
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
      min-width: 20px;
      color: transparent;
    }

    [dir="rtl"] .no-shortcut.pull-right {
      float: left !important;
      float: left;
    }

    [dir="rtl"] .command-shortcut.pull-right {
      float: left !important;
      float: left;
    }

    .command-shortcut:before {
      content: "(command mode)";
      padding-right: 3px;
      color: #777777;
    }

    .edit-shortcut:before {
      content: "(edit)";
      padding-right: 3px;
      color: #777777;
    }

    [dir="rtl"] .edit-shortcut.pull-right {
      float: left !important;
      float: left;
    }

    #find-and-replace #replace-preview .match,
    #find-and-replace #replace-preview .insert {
      background-color: #BBDEFB;
      border-color: #90CAF9;
      border-style: solid;
      border-width: 1px;
      border-radius: 0px;
    }

    [dir="ltr"] #find-and-replace .input-group-btn+.form-control {
      border-left: none;
    }

    [dir="rtl"] #find-and-replace .input-group-btn+.form-control {
      border-right: none;
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
      background: #EEE;
    }

    .terminal-app #header {
      background: #fff;
      -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
      box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    }

    .terminal-app .terminal {
      width: 100%;
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

    .terminal-app .terminal .xterm-rows {
      padding: 10px;
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
    pre {
      line-height: 125%;
    }

    td.linenos .normal {
      color: inherit;
      background-color: transparent;
      padding-left: 5px;
      padding-right: 5px;
    }

    span.linenos {
      color: inherit;
      background-color: transparent;
      padding-left: 5px;
      padding-right: 5px;
    }

    td.linenos .special {
      color: #000000;
      background-color: #ffffc0;
      padding-left: 5px;
      padding-right: 5px;
    }

    span.linenos.special {
      color: #000000;
      background-color: #ffffc0;
      padding-left: 5px;
      padding-right: 5px;
    }

    .highlight .hll {
      background-color: #ffffcc
    }

    .highlight {
      background: #f8f8f8;
    }

    .highlight .c {
      color: #408080;
      font-style: italic
    }

    /* Comment */
    .highlight .err {
      border: 1px solid #FF0000
    }

    /* Error */
    .highlight .k {
      color: #008000;
      font-weight: bold
    }

    /* Keyword */
    .highlight .o {
      color: #666666
    }

    /* Operator */
    .highlight .ch {
      color: #408080;
      font-style: italic
    }

    /* Comment.Hashbang */
    .highlight .cm {
      color: #408080;
      font-style: italic
    }

    /* Comment.Multiline */
    .highlight .cp {
      color: #BC7A00
    }

    /* Comment.Preproc */
    .highlight .cpf {
      color: #408080;
      font-style: italic
    }

    /* Comment.PreprocFile */
    .highlight .c1 {
      color: #408080;
      font-style: italic
    }

    /* Comment.Single */
    .highlight .cs {
      color: #408080;
      font-style: italic
    }

    /* Comment.Special */
    .highlight .gd {
      color: #A00000
    }

    /* Generic.Deleted */
    .highlight .ge {
      font-style: italic
    }

    /* Generic.Emph */
    .highlight .gr {
      color: #FF0000
    }

    /* Generic.Error */
    .highlight .gh {
      color: #000080;
      font-weight: bold
    }

    /* Generic.Heading */
    .highlight .gi {
      color: #00A000
    }

    /* Generic.Inserted */
    .highlight .go {
      color: #888888
    }

    /* Generic.Output */
    .highlight .gp {
      color: #000080;
      font-weight: bold
    }

    /* Generic.Prompt */
    .highlight .gs {
      font-weight: bold
    }

    /* Generic.Strong */
    .highlight .gu {
      color: #800080;
      font-weight: bold
    }

    /* Generic.Subheading */
    .highlight .gt {
      color: #0044DD
    }

    /* Generic.Traceback */
    .highlight .kc {
      color: #008000;
      font-weight: bold
    }

    /* Keyword.Constant */
    .highlight .kd {
      color: #008000;
      font-weight: bold
    }

    /* Keyword.Declaration */
    .highlight .kn {
      color: #008000;
      font-weight: bold
    }

    /* Keyword.Namespace */
    .highlight .kp {
      color: #008000
    }

    /* Keyword.Pseudo */
    .highlight .kr {
      color: #008000;
      font-weight: bold
    }

    /* Keyword.Reserved */
    .highlight .kt {
      color: #B00040
    }

    /* Keyword.Type */
    .highlight .m {
      color: #666666
    }

    /* Literal.Number */
    .highlight .s {
      color: #BA2121
    }

    /* Literal.String */
    .highlight .na {
      color: #7D9029
    }

    /* Name.Attribute */
    .highlight .nb {
      color: #008000
    }

    /* Name.Builtin */
    .highlight .nc {
      color: #0000FF;
      font-weight: bold
    }

    /* Name.Class */
    .highlight .no {
      color: #880000
    }

    /* Name.Constant */
    .highlight .nd {
      color: #AA22FF
    }

    /* Name.Decorator */
    .highlight .ni {
      color: #999999;
      font-weight: bold
    }

    /* Name.Entity */
    .highlight .ne {
      color: #D2413A;
      font-weight: bold
    }

    /* Name.Exception */
    .highlight .nf {
      color: #0000FF
    }

    /* Name.Function */
    .highlight .nl {
      color: #A0A000
    }

    /* Name.Label */
    .highlight .nn {
      color: #0000FF;
      font-weight: bold
    }

    /* Name.Namespace */
    .highlight .nt {
      color: #008000;
      font-weight: bold
    }

    /* Name.Tag */
    .highlight .nv {
      color: #19177C
    }

    /* Name.Variable */
    .highlight .ow {
      color: #AA22FF;
      font-weight: bold
    }

    /* Operator.Word */
    .highlight .w {
      color: #bbbbbb
    }

    /* Text.Whitespace */
    .highlight .mb {
      color: #666666
    }

    /* Literal.Number.Bin */
    .highlight .mf {
      color: #666666
    }

    /* Literal.Number.Float */
    .highlight .mh {
      color: #666666
    }

    /* Literal.Number.Hex */
    .highlight .mi {
      color: #666666
    }

    /* Literal.Number.Integer */
    .highlight .mo {
      color: #666666
    }

    /* Literal.Number.Oct */
    .highlight .sa {
      color: #BA2121
    }

    /* Literal.String.Affix */
    .highlight .sb {
      color: #BA2121
    }

    /* Literal.String.Backtick */
    .highlight .sc {
      color: #BA2121
    }

    /* Literal.String.Char */
    .highlight .dl {
      color: #BA2121
    }

    /* Literal.String.Delimiter */
    .highlight .sd {
      color: #BA2121;
      font-style: italic
    }

    /* Literal.String.Doc */
    .highlight .s2 {
      color: #BA2121
    }

    /* Literal.String.Double */
    .highlight .se {
      color: #BB6622;
      font-weight: bold
    }

    /* Literal.String.Escape */
    .highlight .sh {
      color: #BA2121
    }

    /* Literal.String.Heredoc */
    .highlight .si {
      color: #BB6688;
      font-weight: bold
    }

    /* Literal.String.Interpol */
    .highlight .sx {
      color: #008000
    }

    /* Literal.String.Other */
    .highlight .sr {
      color: #BB6688
    }

    /* Literal.String.Regex */
    .highlight .s1 {
      color: #BA2121
    }

    /* Literal.String.Single */
    .highlight .ss {
      color: #19177C
    }

    /* Literal.String.Symbol */
    .highlight .bp {
      color: #008000
    }

    /* Name.Builtin.Pseudo */
    .highlight .fm {
      color: #0000FF
    }

    /* Name.Function.Magic */
    .highlight .vc {
      color: #19177C
    }

    /* Name.Variable.Class */
    .highlight .vg {
      color: #19177C
    }

    /* Name.Variable.Global */
    .highlight .vi {
      color: #19177C
    }

    /* Name.Variable.Instance */
    .highlight .vm {
      color: #19177C
    }

    /* Name.Variable.Magic */
    .highlight .il {
      color: #666666
    }

    /* Literal.Number.Integer.Long */
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
    }

    @media print {
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
  <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
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
  <!-- End of mathjax configuration -->
</head>

<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

      </div>
      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

      </div>
      <div class="cell border-box-sizing text_cell rendered">
        <div class="prompt input_prompt">
        </div>
        <div class="inner_cell">
          <div class="text_cell_render border-box-sizing rendered_html">
            <h1 id="Pitchers-in-Top-100" style="
  padding-left: 400px;
">Pitchers in Top 100<a class="anchor-link" href="#Pitchers-in-Top-100">&#182;</a></h1>
          </div>
        </div>
      </div>
      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

        <div class="output_wrapper">
          <div class="output">


            <div class="output_area">

              <div class="prompt"></div>



              <div class="output_html rendered_html output_subarea output_execute_result">
                <style type="text/css">
                </style>
                <table id="T_ae857_">
                  <thead>
                    <tr>
                      <th class="col_heading level0 col0">rank</th>
                      <th class="col_heading level0 col1">team</th>
                      <th class="col_heading level0 col2">age</th>
                      <th class="col_heading level0 col3">full_name</th>
                      <th class="col_heading level0 col4">gamesPitched</th>
                      <th class="col_heading level0 col5">whip</th>
                      <th class="col_heading level0 col6">inningsPitched</th>
                      <th class="col_heading level0 col7">hits</th>
                      <th class="col_heading level0 col8">runs</th>
                      <th class="col_heading level0 col9">earnedRuns</th>
                      <th class="col_heading level0 col10">baseOnBalls</th>
                      <th class="col_heading level0 col11">strikeOuts</th>
                      <th class="col_heading level0 col12">homeRuns</th>
                      <th class="col_heading level0 col13">outs</th>
                      <th class="col_heading level0 col14">battersFaced</th>
                      <th class="col_heading level0 col15">era</th>
                      <th class="col_heading level0 col16">saves</th>
                      <th class="col_heading level0 col17">holds</th>
                      <th class="col_heading level0 col18">blownSaves</th>
                      <th class="col_heading level0 col19">wins</th>
                      <th class="col_heading level0 col20">losses</th>
                      <th class="col_heading level0 col21">sportAbbrev</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td id="T_ae857_row0_col0" class="data row0 col0">8</td>
                      <td id="T_ae857_row0_col1" class="data row0 col1">Bal</td>
                      <td id="T_ae857_row0_col2" class="data row0 col2">21</td>
                      <td id="T_ae857_row0_col3" class="data row0 col3">Grayson Rodriguez</td>
                      <td id="T_ae857_row0_col4" class="data row0 col4">23</td>
                      <td id="T_ae857_row0_col5" class="data row0 col5">0.830000</td>
                      <td id="T_ae857_row0_col6" class="data row0 col6">103.000000</td>
                      <td id="T_ae857_row0_col7" class="data row0 col7">58</td>
                      <td id="T_ae857_row0_col8" class="data row0 col8">30</td>
                      <td id="T_ae857_row0_col9" class="data row0 col9">27</td>
                      <td id="T_ae857_row0_col10" class="data row0 col10">27</td>
                      <td id="T_ae857_row0_col11" class="data row0 col11">161</td>
                      <td id="T_ae857_row0_col12" class="data row0 col12">10</td>
                      <td id="T_ae857_row0_col13" class="data row0 col13">309</td>
                      <td id="T_ae857_row0_col14" class="data row0 col14">398</td>
                      <td id="T_ae857_row0_col15" class="data row0 col15">2.360000</td>
                      <td id="T_ae857_row0_col16" class="data row0 col16">0</td>
                      <td id="T_ae857_row0_col17" class="data row0 col17">0</td>
                      <td id="T_ae857_row0_col18" class="data row0 col18">0</td>
                      <td id="T_ae857_row0_col19" class="data row0 col19">9</td>
                      <td id="T_ae857_row0_col20" class="data row0 col20">1</td>
                      <td id="T_ae857_row0_col21" class="data row0 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row1_col0" class="data row1 col0">19</td>
                      <td id="T_ae857_row1_col1" class="data row1 col1">Tam</td>
                      <td id="T_ae857_row1_col2" class="data row1 col2">22</td>
                      <td id="T_ae857_row1_col3" class="data row1 col3">Shane Baz</td>
                      <td id="T_ae857_row1_col4" class="data row1 col4">19</td>
                      <td id="T_ae857_row1_col5" class="data row1 col5">0.770000</td>
                      <td id="T_ae857_row1_col6" class="data row1 col6">89.100000</td>
                      <td id="T_ae857_row1_col7" class="data row1 col7">55</td>
                      <td id="T_ae857_row1_col8" class="data row1 col8">21</td>
                      <td id="T_ae857_row1_col9" class="data row1 col9">20</td>
                      <td id="T_ae857_row1_col10" class="data row1 col10">14</td>
                      <td id="T_ae857_row1_col11" class="data row1 col11">127</td>
                      <td id="T_ae857_row1_col12" class="data row1 col12">11</td>
                      <td id="T_ae857_row1_col13" class="data row1 col13">268</td>
                      <td id="T_ae857_row1_col14" class="data row1 col14">336</td>
                      <td id="T_ae857_row1_col15" class="data row1 col15">2.010000</td>
                      <td id="T_ae857_row1_col16" class="data row1 col16">0</td>
                      <td id="T_ae857_row1_col17" class="data row1 col17">0</td>
                      <td id="T_ae857_row1_col18" class="data row1 col18">0</td>
                      <td id="T_ae857_row1_col19" class="data row1 col19">7</td>
                      <td id="T_ae857_row1_col20" class="data row1 col20">4</td>
                      <td id="T_ae857_row1_col21" class="data row1 col21">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row2_col0" class="data row2 col0">23</td>
                      <td id="T_ae857_row2_col1" class="data row2 col1">LAA</td>
                      <td id="T_ae857_row2_col2" class="data row2 col2">22</td>
                      <td id="T_ae857_row2_col3" class="data row2 col3">Reid Detmers</td>
                      <td id="T_ae857_row2_col4" class="data row2 col4">18</td>
                      <td id="T_ae857_row2_col5" class="data row2 col5">1.270000</td>
                      <td id="T_ae857_row2_col6" class="data row2 col6">81.000000</td>
                      <td id="T_ae857_row2_col7" class="data row2 col7">75</td>
                      <td id="T_ae857_row2_col8" class="data row2 col8">40</td>
                      <td id="T_ae857_row2_col9" class="data row2 col9">37</td>
                      <td id="T_ae857_row2_col10" class="data row2 col10">28</td>
                      <td id="T_ae857_row2_col11" class="data row2 col11">125</td>
                      <td id="T_ae857_row2_col12" class="data row2 col12">15</td>
                      <td id="T_ae857_row2_col13" class="data row2 col13">243</td>
                      <td id="T_ae857_row2_col14" class="data row2 col14">348</td>
                      <td id="T_ae857_row2_col15" class="data row2 col15">4.110000</td>
                      <td id="T_ae857_row2_col16" class="data row2 col16">0</td>
                      <td id="T_ae857_row2_col17" class="data row2 col17">0</td>
                      <td id="T_ae857_row2_col18" class="data row2 col18">0</td>
                      <td id="T_ae857_row2_col19" class="data row2 col19">4</td>
                      <td id="T_ae857_row2_col20" class="data row2 col20">7</td>
                      <td id="T_ae857_row2_col21" class="data row2 col21">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row3_col0" class="data row3 col0">26</td>
                      <td id="T_ae857_row3_col1" class="data row3 col1">Cle</td>
                      <td id="T_ae857_row3_col2" class="data row3 col2">22</td>
                      <td id="T_ae857_row3_col3" class="data row3 col3">Hunter Greene</td>
                      <td id="T_ae857_row3_col4" class="data row3 col4">21</td>
                      <td id="T_ae857_row3_col5" class="data row3 col5">1.180000</td>
                      <td id="T_ae857_row3_col6" class="data row3 col6">106.100000</td>
                      <td id="T_ae857_row3_col7" class="data row3 col7">86</td>
                      <td id="T_ae857_row3_col8" class="data row3 col8">44</td>
                      <td id="T_ae857_row3_col9" class="data row3 col9">39</td>
                      <td id="T_ae857_row3_col10" class="data row3 col10">39</td>
                      <td id="T_ae857_row3_col11" class="data row3 col11">139</td>
                      <td id="T_ae857_row3_col12" class="data row3 col12">13</td>
                      <td id="T_ae857_row3_col13" class="data row3 col13">319</td>
                      <td id="T_ae857_row3_col14" class="data row3 col14">438</td>
                      <td id="T_ae857_row3_col15" class="data row3 col15">3.300000</td>
                      <td id="T_ae857_row3_col16" class="data row3 col16">0</td>
                      <td id="T_ae857_row3_col17" class="data row3 col17">0</td>
                      <td id="T_ae857_row3_col18" class="data row3 col18">0</td>
                      <td id="T_ae857_row3_col19" class="data row3 col19">10</td>
                      <td id="T_ae857_row3_col20" class="data row3 col20">8</td>
                      <td id="T_ae857_row3_col21" class="data row3 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row4_col0" class="data row4 col0">29</td>
                      <td id="T_ae857_row4_col1" class="data row4 col1">Mia</td>
                      <td id="T_ae857_row4_col2" class="data row4 col2">23</td>
                      <td id="T_ae857_row4_col3" class="data row4 col3">Edward Cabrera</td>
                      <td id="T_ae857_row4_col4" class="data row4 col4">20</td>
                      <td id="T_ae857_row4_col5" class="data row4 col5">1.290000</td>
                      <td id="T_ae857_row4_col6" class="data row4 col6">87.200000</td>
                      <td id="T_ae857_row4_col7" class="data row4 col7">69</td>
                      <td id="T_ae857_row4_col8" class="data row4 col8">43</td>
                      <td id="T_ae857_row4_col9" class="data row4 col9">37</td>
                      <td id="T_ae857_row4_col10" class="data row4 col10">44</td>
                      <td id="T_ae857_row4_col11" class="data row4 col11">120</td>
                      <td id="T_ae857_row4_col12" class="data row4 col12">13</td>
                      <td id="T_ae857_row4_col13" class="data row4 col13">263</td>
                      <td id="T_ae857_row4_col14" class="data row4 col14">369</td>
                      <td id="T_ae857_row4_col15" class="data row4 col15">3.800000</td>
                      <td id="T_ae857_row4_col16" class="data row4 col16">0</td>
                      <td id="T_ae857_row4_col17" class="data row4 col17">0</td>
                      <td id="T_ae857_row4_col18" class="data row4 col18">0</td>
                      <td id="T_ae857_row4_col19" class="data row4 col19">3</td>
                      <td id="T_ae857_row4_col20" class="data row4 col20">7</td>
                      <td id="T_ae857_row4_col21" class="data row4 col21">ALL (4)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row5_col0" class="data row5 col0">30</td>
                      <td id="T_ae857_row5_col1" class="data row5 col1">Mia</td>
                      <td id="T_ae857_row5_col2" class="data row5 col2">22</td>
                      <td id="T_ae857_row5_col3" class="data row5 col3">Max Meyer</td>
                      <td id="T_ae857_row5_col4" class="data row5 col4">21</td>
                      <td id="T_ae857_row5_col5" class="data row5 col5">1.200000</td>
                      <td id="T_ae857_row5_col6" class="data row5 col6">106.000000</td>
                      <td id="T_ae857_row5_col7" class="data row5 col7">86</td>
                      <td id="T_ae857_row5_col8" class="data row5 col8">36</td>
                      <td id="T_ae857_row5_col9" class="data row5 col9">28</td>
                      <td id="T_ae857_row5_col10" class="data row5 col10">41</td>
                      <td id="T_ae857_row5_col11" class="data row5 col11">123</td>
                      <td id="T_ae857_row5_col12" class="data row5 col12">8</td>
                      <td id="T_ae857_row5_col13" class="data row5 col13">318</td>
                      <td id="T_ae857_row5_col14" class="data row5 col14">434</td>
                      <td id="T_ae857_row5_col15" class="data row5 col15">2.380000</td>
                      <td id="T_ae857_row5_col16" class="data row5 col16">0</td>
                      <td id="T_ae857_row5_col17" class="data row5 col17">0</td>
                      <td id="T_ae857_row5_col18" class="data row5 col18">0</td>
                      <td id="T_ae857_row5_col19" class="data row5 col19">6</td>
                      <td id="T_ae857_row5_col20" class="data row5 col20">3</td>
                      <td id="T_ae857_row5_col21" class="data row5 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row6_col0" class="data row6 col0">31</td>
                      <td id="T_ae857_row6_col1" class="data row6 col1">Cle</td>
                      <td id="T_ae857_row6_col2" class="data row6 col2">23</td>
                      <td id="T_ae857_row6_col3" class="data row6 col3">Nick Lodolo</td>
                      <td id="T_ae857_row6_col4" class="data row6 col4">13</td>
                      <td id="T_ae857_row6_col5" class="data row6 col5">0.970000</td>
                      <td id="T_ae857_row6_col6" class="data row6 col6">50.200000</td>
                      <td id="T_ae857_row6_col7" class="data row6 col7">38</td>
                      <td id="T_ae857_row6_col8" class="data row6 col8">13</td>
                      <td id="T_ae857_row6_col9" class="data row6 col9">13</td>
                      <td id="T_ae857_row6_col10" class="data row6 col10">11</td>
                      <td id="T_ae857_row6_col11" class="data row6 col11">78</td>
                      <td id="T_ae857_row6_col12" class="data row6 col12">3</td>
                      <td id="T_ae857_row6_col13" class="data row6 col13">152</td>
                      <td id="T_ae857_row6_col14" class="data row6 col14">201</td>
                      <td id="T_ae857_row6_col15" class="data row6 col15">2.310000</td>
                      <td id="T_ae857_row6_col16" class="data row6 col16">0</td>
                      <td id="T_ae857_row6_col17" class="data row6 col17">0</td>
                      <td id="T_ae857_row6_col18" class="data row6 col18">0</td>
                      <td id="T_ae857_row6_col19" class="data row6 col19">2</td>
                      <td id="T_ae857_row6_col20" class="data row6 col20">2</td>
                      <td id="T_ae857_row6_col21" class="data row6 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row7_col0" class="data row7 col0">33</td>
                      <td id="T_ae857_row7_col1" class="data row7 col1">Sea</td>
                      <td id="T_ae857_row7_col2" class="data row7 col2">23</td>
                      <td id="T_ae857_row7_col3" class="data row7 col3">George Kirby</td>
                      <td id="T_ae857_row7_col4" class="data row7 col4">15</td>
                      <td id="T_ae857_row7_col5" class="data row7 col5">1.080000</td>
                      <td id="T_ae857_row7_col6" class="data row7 col6">67.200000</td>
                      <td id="T_ae857_row7_col7" class="data row7 col7">58</td>
                      <td id="T_ae857_row7_col8" class="data row7 col8">23</td>
                      <td id="T_ae857_row7_col9" class="data row7 col9">19</td>
                      <td id="T_ae857_row7_col10" class="data row7 col10">15</td>
                      <td id="T_ae857_row7_col11" class="data row7 col11">80</td>
                      <td id="T_ae857_row7_col12" class="data row7 col12">1</td>
                      <td id="T_ae857_row7_col13" class="data row7 col13">203</td>
                      <td id="T_ae857_row7_col14" class="data row7 col14">274</td>
                      <td id="T_ae857_row7_col15" class="data row7 col15">2.530000</td>
                      <td id="T_ae857_row7_col16" class="data row7 col16">0</td>
                      <td id="T_ae857_row7_col17" class="data row7 col17">0</td>
                      <td id="T_ae857_row7_col18" class="data row7 col18">0</td>
                      <td id="T_ae857_row7_col19" class="data row7 col19">5</td>
                      <td id="T_ae857_row7_col20" class="data row7 col20">3</td>
                      <td id="T_ae857_row7_col21" class="data row7 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row8_col0" class="data row8 col0">34</td>
                      <td id="T_ae857_row8_col1" class="data row8 col1">Sea</td>
                      <td id="T_ae857_row8_col2" class="data row8 col2">22</td>
                      <td id="T_ae857_row8_col3" class="data row8 col3">Emerson Hancock</td>
                      <td id="T_ae857_row8_col4" class="data row8 col4">12</td>
                      <td id="T_ae857_row8_col5" class="data row8 col5">1.030000</td>
                      <td id="T_ae857_row8_col6" class="data row8 col6">44.200000</td>
                      <td id="T_ae857_row8_col7" class="data row8 col7">29</td>
                      <td id="T_ae857_row8_col8" class="data row8 col8">17</td>
                      <td id="T_ae857_row8_col9" class="data row8 col9">13</td>
                      <td id="T_ae857_row8_col10" class="data row8 col10">17</td>
                      <td id="T_ae857_row8_col11" class="data row8 col11">43</td>
                      <td id="T_ae857_row8_col12" class="data row8 col12">1</td>
                      <td id="T_ae857_row8_col13" class="data row8 col13">134</td>
                      <td id="T_ae857_row8_col14" class="data row8 col14">179</td>
                      <td id="T_ae857_row8_col15" class="data row8 col15">2.620000</td>
                      <td id="T_ae857_row8_col16" class="data row8 col16">0</td>
                      <td id="T_ae857_row8_col17" class="data row8 col17">0</td>
                      <td id="T_ae857_row8_col18" class="data row8 col18">0</td>
                      <td id="T_ae857_row8_col19" class="data row8 col19">3</td>
                      <td id="T_ae857_row8_col20" class="data row8 col20">1</td>
                      <td id="T_ae857_row8_col21" class="data row8 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row9_col0" class="data row9 col0">39</td>
                      <td id="T_ae857_row9_col1" class="data row9 col1">Was</td>
                      <td id="T_ae857_row9_col2" class="data row9 col2">23</td>
                      <td id="T_ae857_row9_col3" class="data row9 col3">Cade Cavalli</td>
                      <td id="T_ae857_row9_col4" class="data row9 col4">24</td>
                      <td id="T_ae857_row9_col5" class="data row9 col5">1.260000</td>
                      <td id="T_ae857_row9_col6" class="data row9 col6">123.100000</td>
                      <td id="T_ae857_row9_col7" class="data row9 col7">96</td>
                      <td id="T_ae857_row9_col8" class="data row9 col8">49</td>
                      <td id="T_ae857_row9_col9" class="data row9 col9">46</td>
                      <td id="T_ae857_row9_col10" class="data row9 col10">60</td>
                      <td id="T_ae857_row9_col11" class="data row9 col11">175</td>
                      <td id="T_ae857_row9_col12" class="data row9 col12">5</td>
                      <td id="T_ae857_row9_col13" class="data row9 col13">370</td>
                      <td id="T_ae857_row9_col14" class="data row9 col14">522</td>
                      <td id="T_ae857_row9_col15" class="data row9 col15">3.360000</td>
                      <td id="T_ae857_row9_col16" class="data row9 col16">0</td>
                      <td id="T_ae857_row9_col17" class="data row9 col17">0</td>
                      <td id="T_ae857_row9_col18" class="data row9 col18">0</td>
                      <td id="T_ae857_row9_col19" class="data row9 col19">7</td>
                      <td id="T_ae857_row9_col20" class="data row9 col20">9</td>
                      <td id="T_ae857_row9_col21" class="data row9 col21">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row10_col0" class="data row10 col0">47</td>
                      <td id="T_ae857_row10_col1" class="data row10 col1">STL</td>
                      <td id="T_ae857_row10_col2" class="data row10 col2">21</td>
                      <td id="T_ae857_row10_col3" class="data row10 col3">Matthew Liberatore</td>
                      <td id="T_ae857_row10_col4" class="data row10 col4">21</td>
                      <td id="T_ae857_row10_col5" class="data row10 col5">1.280000</td>
                      <td id="T_ae857_row10_col6" class="data row10 col6">121.100000</td>
                      <td id="T_ae857_row10_col7" class="data row10 col7">122</td>
                      <td id="T_ae857_row10_col8" class="data row10 col8">66</td>
                      <td id="T_ae857_row10_col9" class="data row10 col9">56</td>
                      <td id="T_ae857_row10_col10" class="data row10 col10">33</td>
                      <td id="T_ae857_row10_col11" class="data row10 col11">119</td>
                      <td id="T_ae857_row10_col12" class="data row10 col12">19</td>
                      <td id="T_ae857_row10_col13" class="data row10 col13">364</td>
                      <td id="T_ae857_row10_col14" class="data row10 col14">510</td>
                      <td id="T_ae857_row10_col15" class="data row10 col15">4.150000</td>
                      <td id="T_ae857_row10_col16" class="data row10 col16">0</td>
                      <td id="T_ae857_row10_col17" class="data row10 col17">0</td>
                      <td id="T_ae857_row10_col18" class="data row10 col18">0</td>
                      <td id="T_ae857_row10_col19" class="data row10 col19">8</td>
                      <td id="T_ae857_row10_col20" class="data row10 col20">9</td>
                      <td id="T_ae857_row10_col21" class="data row10 col21">AAA</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row11_col0" class="data row11 col0">49</td>
                      <td id="T_ae857_row11_col1" class="data row11 col1">Pit</td>
                      <td id="T_ae857_row11_col2" class="data row11 col2">21</td>
                      <td id="T_ae857_row11_col3" class="data row11 col3">Quinn Priester</td>
                      <td id="T_ae857_row11_col4" class="data row11 col4">20</td>
                      <td id="T_ae857_row11_col5" class="data row11 col5">1.240000</td>
                      <td id="T_ae857_row11_col6" class="data row11 col6">97.200000</td>
                      <td id="T_ae857_row11_col7" class="data row11 col7">82</td>
                      <td id="T_ae857_row11_col8" class="data row11 col8">40</td>
                      <td id="T_ae857_row11_col9" class="data row11 col9">33</td>
                      <td id="T_ae857_row11_col10" class="data row11 col10">39</td>
                      <td id="T_ae857_row11_col11" class="data row11 col11">98</td>
                      <td id="T_ae857_row11_col12" class="data row11 col12">8</td>
                      <td id="T_ae857_row11_col13" class="data row11 col13">293</td>
                      <td id="T_ae857_row11_col14" class="data row11 col14">407</td>
                      <td id="T_ae857_row11_col15" class="data row11 col15">3.040000</td>
                      <td id="T_ae857_row11_col16" class="data row11 col16">0</td>
                      <td id="T_ae857_row11_col17" class="data row11 col17">0</td>
                      <td id="T_ae857_row11_col18" class="data row11 col18">0</td>
                      <td id="T_ae857_row11_col19" class="data row11 col19">7</td>
                      <td id="T_ae857_row11_col20" class="data row11 col20">4</td>
                      <td id="T_ae857_row11_col21" class="data row11 col21">A+</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row12_col0" class="data row12 col0">56</td>
                      <td id="T_ae857_row12_col1" class="data row12 col1">SD</td>
                      <td id="T_ae857_row12_col2" class="data row12 col2">22</td>
                      <td id="T_ae857_row12_col3" class="data row12 col3">MacKenzie Gore</td>
                      <td id="T_ae857_row12_col4" class="data row12 col4">12</td>
                      <td id="T_ae857_row12_col5" class="data row12 col5">1.470000</td>
                      <td id="T_ae857_row12_col6" class="data row12 col6">50.100000</td>
                      <td id="T_ae857_row12_col7" class="data row12 col7">46</td>
                      <td id="T_ae857_row12_col8" class="data row12 col8">26</td>
                      <td id="T_ae857_row12_col9" class="data row12 col9">22</td>
                      <td id="T_ae857_row12_col10" class="data row12 col10">28</td>
                      <td id="T_ae857_row12_col11" class="data row12 col11">61</td>
                      <td id="T_ae857_row12_col12" class="data row12 col12">3</td>
                      <td id="T_ae857_row12_col13" class="data row12 col13">151</td>
                      <td id="T_ae857_row12_col14" class="data row12 col14">223</td>
                      <td id="T_ae857_row12_col15" class="data row12 col15">3.930000</td>
                      <td id="T_ae857_row12_col16" class="data row12 col16">0</td>
                      <td id="T_ae857_row12_col17" class="data row12 col17">0</td>
                      <td id="T_ae857_row12_col18" class="data row12 col18">0</td>
                      <td id="T_ae857_row12_col19" class="data row12 col19">1</td>
                      <td id="T_ae857_row12_col20" class="data row12 col20">3</td>
                      <td id="T_ae857_row12_col21" class="data row12 col21">ALL (4)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row13_col0" class="data row13 col0">60</td>
                      <td id="T_ae857_row13_col1" class="data row13 col1">Tex</td>
                      <td id="T_ae857_row13_col2" class="data row13 col2">21</td>
                      <td id="T_ae857_row13_col3" class="data row13 col3">Cole Winn</td>
                      <td id="T_ae857_row13_col4" class="data row13 col4">21</td>
                      <td id="T_ae857_row13_col5" class="data row13 col5">0.860000</td>
                      <td id="T_ae857_row13_col6" class="data row13 col6">86.000000</td>
                      <td id="T_ae857_row13_col7" class="data row13 col7">43</td>
                      <td id="T_ae857_row13_col8" class="data row13 col8">24</td>
                      <td id="T_ae857_row13_col9" class="data row13 col9">23</td>
                      <td id="T_ae857_row13_col10" class="data row13 col10">31</td>
                      <td id="T_ae857_row13_col11" class="data row13 col11">107</td>
                      <td id="T_ae857_row13_col12" class="data row13 col12">7</td>
                      <td id="T_ae857_row13_col13" class="data row13 col13">258</td>
                      <td id="T_ae857_row13_col14" class="data row13 col14">332</td>
                      <td id="T_ae857_row13_col15" class="data row13 col15">2.410000</td>
                      <td id="T_ae857_row13_col16" class="data row13 col16">0</td>
                      <td id="T_ae857_row13_col17" class="data row13 col17">0</td>
                      <td id="T_ae857_row13_col18" class="data row13 col18">0</td>
                      <td id="T_ae857_row13_col19" class="data row13 col19">4</td>
                      <td id="T_ae857_row13_col20" class="data row13 col20">3</td>
                      <td id="T_ae857_row13_col21" class="data row13 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row14_col0" class="data row14 col0">61</td>
                      <td id="T_ae857_row14_col1" class="data row14 col1">LAD</td>
                      <td id="T_ae857_row14_col2" class="data row14 col2">24</td>
                      <td id="T_ae857_row14_col3" class="data row14 col3">Ryan Pepiot</td>
                      <td id="T_ae857_row14_col4" class="data row14 col4">26</td>
                      <td id="T_ae857_row14_col5" class="data row14 col5">1.290000</td>
                      <td id="T_ae857_row14_col6" class="data row14 col6">101.100000</td>
                      <td id="T_ae857_row14_col7" class="data row14 col7">84</td>
                      <td id="T_ae857_row14_col8" class="data row14 col8">60</td>
                      <td id="T_ae857_row14_col9" class="data row14 col9">52</td>
                      <td id="T_ae857_row14_col10" class="data row14 col10">47</td>
                      <td id="T_ae857_row14_col11" class="data row14 col11">127</td>
                      <td id="T_ae857_row14_col12" class="data row14 col12">19</td>
                      <td id="T_ae857_row14_col13" class="data row14 col13">304</td>
                      <td id="T_ae857_row14_col14" class="data row14 col14">435</td>
                      <td id="T_ae857_row14_col15" class="data row14 col15">4.620000</td>
                      <td id="T_ae857_row14_col16" class="data row14 col16">0</td>
                      <td id="T_ae857_row14_col17" class="data row14 col17">0</td>
                      <td id="T_ae857_row14_col18" class="data row14 col18">0</td>
                      <td id="T_ae857_row14_col19" class="data row14 col19">5</td>
                      <td id="T_ae857_row14_col20" class="data row14 col20">9</td>
                      <td id="T_ae857_row14_col21" class="data row14 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row15_col0" class="data row15 col0">64</td>
                      <td id="T_ae857_row15_col1" class="data row15 col1">Phi</td>
                      <td id="T_ae857_row15_col2" class="data row15 col2">20</td>
                      <td id="T_ae857_row15_col3" class="data row15 col3">Mick Abel</td>
                      <td id="T_ae857_row15_col4" class="data row15 col4">14</td>
                      <td id="T_ae857_row15_col5" class="data row15 col5">1.210000</td>
                      <td id="T_ae857_row15_col6" class="data row15 col6">44.200000</td>
                      <td id="T_ae857_row15_col7" class="data row15 col7">27</td>
                      <td id="T_ae857_row15_col8" class="data row15 col8">23</td>
                      <td id="T_ae857_row15_col9" class="data row15 col9">22</td>
                      <td id="T_ae857_row15_col10" class="data row15 col10">27</td>
                      <td id="T_ae857_row15_col11" class="data row15 col11">66</td>
                      <td id="T_ae857_row15_col12" class="data row15 col12">5</td>
                      <td id="T_ae857_row15_col13" class="data row15 col13">134</td>
                      <td id="T_ae857_row15_col14" class="data row15 col14">189</td>
                      <td id="T_ae857_row15_col15" class="data row15 col15">4.430000</td>
                      <td id="T_ae857_row15_col16" class="data row15 col16">0</td>
                      <td id="T_ae857_row15_col17" class="data row15 col17">0</td>
                      <td id="T_ae857_row15_col18" class="data row15 col18">0</td>
                      <td id="T_ae857_row15_col19" class="data row15 col19">1</td>
                      <td id="T_ae857_row15_col20" class="data row15 col20">3</td>
                      <td id="T_ae857_row15_col21" class="data row15 col21">A</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row16_col0" class="data row16 col0">66</td>
                      <td id="T_ae857_row16_col1" class="data row16 col1">Kan</td>
                      <td id="T_ae857_row16_col2" class="data row16 col2">22</td>
                      <td id="T_ae857_row16_col3" class="data row16 col3">Asa Lacy</td>
                      <td id="T_ae857_row16_col4" class="data row16 col4">14</td>
                      <td id="T_ae857_row16_col5" class="data row16 col5">1.580000</td>
                      <td id="T_ae857_row16_col6" class="data row16 col6">52.000000</td>
                      <td id="T_ae857_row16_col7" class="data row16 col7">41</td>
                      <td id="T_ae857_row16_col8" class="data row16 col8">31</td>
                      <td id="T_ae857_row16_col9" class="data row16 col9">30</td>
                      <td id="T_ae857_row16_col10" class="data row16 col10">41</td>
                      <td id="T_ae857_row16_col11" class="data row16 col11">79</td>
                      <td id="T_ae857_row16_col12" class="data row16 col12">5</td>
                      <td id="T_ae857_row16_col13" class="data row16 col13">156</td>
                      <td id="T_ae857_row16_col14" class="data row16 col14">237</td>
                      <td id="T_ae857_row16_col15" class="data row16 col15">5.190000</td>
                      <td id="T_ae857_row16_col16" class="data row16 col16">0</td>
                      <td id="T_ae857_row16_col17" class="data row16 col17">0</td>
                      <td id="T_ae857_row16_col18" class="data row16 col18">0</td>
                      <td id="T_ae857_row16_col19" class="data row16 col19">2</td>
                      <td id="T_ae857_row16_col20" class="data row16 col20">5</td>
                      <td id="T_ae857_row16_col21" class="data row16 col21">A+</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row17_col0" class="data row17 col0">72</td>
                      <td id="T_ae857_row17_col1" class="data row17 col1">Bal</td>
                      <td id="T_ae857_row17_col2" class="data row17 col2">23</td>
                      <td id="T_ae857_row17_col3" class="data row17 col3">D.L. Hall</td>
                      <td id="T_ae857_row17_col4" class="data row17 col4">7</td>
                      <td id="T_ae857_row17_col5" class="data row17 col5">1.010000</td>
                      <td id="T_ae857_row17_col6" class="data row17 col6">31.200000</td>
                      <td id="T_ae857_row17_col7" class="data row17 col7">16</td>
                      <td id="T_ae857_row17_col8" class="data row17 col8">11</td>
                      <td id="T_ae857_row17_col9" class="data row17 col9">11</td>
                      <td id="T_ae857_row17_col10" class="data row17 col10">16</td>
                      <td id="T_ae857_row17_col11" class="data row17 col11">56</td>
                      <td id="T_ae857_row17_col12" class="data row17 col12">4</td>
                      <td id="T_ae857_row17_col13" class="data row17 col13">95</td>
                      <td id="T_ae857_row17_col14" class="data row17 col14">128</td>
                      <td id="T_ae857_row17_col15" class="data row17 col15">3.130000</td>
                      <td id="T_ae857_row17_col16" class="data row17 col16">0</td>
                      <td id="T_ae857_row17_col17" class="data row17 col17">0</td>
                      <td id="T_ae857_row17_col18" class="data row17 col18">0</td>
                      <td id="T_ae857_row17_col19" class="data row17 col19">2</td>
                      <td id="T_ae857_row17_col20" class="data row17 col20">0</td>
                      <td id="T_ae857_row17_col21" class="data row17 col21">AA</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row18_col0" class="data row18 col0">78</td>
                      <td id="T_ae857_row18_col1" class="data row18 col1">LAD</td>
                      <td id="T_ae857_row18_col2" class="data row18 col2">22</td>
                      <td id="T_ae857_row18_col3" class="data row18 col3">Bobby Miller</td>
                      <td id="T_ae857_row18_col4" class="data row18 col4">17</td>
                      <td id="T_ae857_row18_col5" class="data row18 col5">0.940000</td>
                      <td id="T_ae857_row18_col6" class="data row18 col6">56.100000</td>
                      <td id="T_ae857_row18_col7" class="data row18 col7">40</td>
                      <td id="T_ae857_row18_col8" class="data row18 col8">21</td>
                      <td id="T_ae857_row18_col9" class="data row18 col9">15</td>
                      <td id="T_ae857_row18_col10" class="data row18 col10">13</td>
                      <td id="T_ae857_row18_col11" class="data row18 col11">70</td>
                      <td id="T_ae857_row18_col12" class="data row18 col12">2</td>
                      <td id="T_ae857_row18_col13" class="data row18 col13">169</td>
                      <td id="T_ae857_row18_col14" class="data row18 col14">230</td>
                      <td id="T_ae857_row18_col15" class="data row18 col15">2.400000</td>
                      <td id="T_ae857_row18_col16" class="data row18 col16">0</td>
                      <td id="T_ae857_row18_col17" class="data row18 col17">0</td>
                      <td id="T_ae857_row18_col18" class="data row18 col18">0</td>
                      <td id="T_ae857_row18_col19" class="data row18 col19">2</td>
                      <td id="T_ae857_row18_col20" class="data row18 col20">2</td>
                      <td id="T_ae857_row18_col21" class="data row18 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row19_col0" class="data row19 col0">81</td>
                      <td id="T_ae857_row19_col1" class="data row19 col1">Min</td>
                      <td id="T_ae857_row19_col2" class="data row19 col2">23</td>
                      <td id="T_ae857_row19_col3" class="data row19 col3">Jordan Balazovic</td>
                      <td id="T_ae857_row19_col4" class="data row19 col4">20</td>
                      <td id="T_ae857_row19_col5" class="data row19 col5">1.400000</td>
                      <td id="T_ae857_row19_col6" class="data row19 col6">97.000000</td>
                      <td id="T_ae857_row19_col7" class="data row19 col7">98</td>
                      <td id="T_ae857_row19_col8" class="data row19 col8">48</td>
                      <td id="T_ae857_row19_col9" class="data row19 col9">39</td>
                      <td id="T_ae857_row19_col10" class="data row19 col10">38</td>
                      <td id="T_ae857_row19_col11" class="data row19 col11">102</td>
                      <td id="T_ae857_row19_col12" class="data row19 col12">9</td>
                      <td id="T_ae857_row19_col13" class="data row19 col13">291</td>
                      <td id="T_ae857_row19_col14" class="data row19 col14">429</td>
                      <td id="T_ae857_row19_col15" class="data row19 col15">3.620000</td>
                      <td id="T_ae857_row19_col16" class="data row19 col16">0</td>
                      <td id="T_ae857_row19_col17" class="data row19 col17">0</td>
                      <td id="T_ae857_row19_col18" class="data row19 col18">0</td>
                      <td id="T_ae857_row19_col19" class="data row19 col19">5</td>
                      <td id="T_ae857_row19_col20" class="data row19 col20">4</td>
                      <td id="T_ae857_row19_col21" class="data row19 col21">AA</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row20_col0" class="data row20 col0">87</td>
                      <td id="T_ae857_row20_col1" class="data row20 col1">LAA</td>
                      <td id="T_ae857_row20_col2" class="data row20 col2">22</td>
                      <td id="T_ae857_row20_col3" class="data row20 col3">Sam Bachman</td>
                      <td id="T_ae857_row20_col4" class="data row20 col4">5</td>
                      <td id="T_ae857_row20_col5" class="data row20 col5">1.190000</td>
                      <td id="T_ae857_row20_col6" class="data row20 col6">14.100000</td>
                      <td id="T_ae857_row20_col7" class="data row20 col7">13</td>
                      <td id="T_ae857_row20_col8" class="data row20 col8">7</td>
                      <td id="T_ae857_row20_col9" class="data row20 col9">6</td>
                      <td id="T_ae857_row20_col10" class="data row20 col10">4</td>
                      <td id="T_ae857_row20_col11" class="data row20 col11">15</td>
                      <td id="T_ae857_row20_col12" class="data row20 col12">1</td>
                      <td id="T_ae857_row20_col13" class="data row20 col13">43</td>
                      <td id="T_ae857_row20_col14" class="data row20 col14">58</td>
                      <td id="T_ae857_row20_col15" class="data row20 col15">3.770000</td>
                      <td id="T_ae857_row20_col16" class="data row20 col16">0</td>
                      <td id="T_ae857_row20_col17" class="data row20 col17">0</td>
                      <td id="T_ae857_row20_col18" class="data row20 col18">0</td>
                      <td id="T_ae857_row20_col19" class="data row20 col19">0</td>
                      <td id="T_ae857_row20_col20" class="data row20 col20">2</td>
                      <td id="T_ae857_row20_col21" class="data row20 col21">A+</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row21_col0" class="data row21 col0">92</td>
                      <td id="T_ae857_row21_col1" class="data row21 col1">Cle</td>
                      <td id="T_ae857_row21_col2" class="data row21 col2">20</td>
                      <td id="T_ae857_row21_col3" class="data row21 col3">Daniel Espino</td>
                      <td id="T_ae857_row21_col4" class="data row21 col4">20</td>
                      <td id="T_ae857_row21_col5" class="data row21 col5">1.120000</td>
                      <td id="T_ae857_row21_col6" class="data row21 col6">91.200000</td>
                      <td id="T_ae857_row21_col7" class="data row21 col7">64</td>
                      <td id="T_ae857_row21_col8" class="data row21 col8">40</td>
                      <td id="T_ae857_row21_col9" class="data row21 col9">38</td>
                      <td id="T_ae857_row21_col10" class="data row21 col10">39</td>
                      <td id="T_ae857_row21_col11" class="data row21 col11">152</td>
                      <td id="T_ae857_row21_col12" class="data row21 col12">9</td>
                      <td id="T_ae857_row21_col13" class="data row21 col13">275</td>
                      <td id="T_ae857_row21_col14" class="data row21 col14">375</td>
                      <td id="T_ae857_row21_col15" class="data row21 col15">3.730000</td>
                      <td id="T_ae857_row21_col16" class="data row21 col16">0</td>
                      <td id="T_ae857_row21_col17" class="data row21 col17">0</td>
                      <td id="T_ae857_row21_col18" class="data row21 col18">0</td>
                      <td id="T_ae857_row21_col19" class="data row21 col19">3</td>
                      <td id="T_ae857_row21_col20" class="data row21 col20">8</td>
                      <td id="T_ae857_row21_col21" class="data row21 col21">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row22_col0" class="data row22 col0">94</td>
                      <td id="T_ae857_row22_col1" class="data row22 col1">NYY</td>
                      <td id="T_ae857_row22_col2" class="data row22 col2">23</td>
                      <td id="T_ae857_row22_col3" class="data row22 col3">Luis Gil</td>
                      <td id="T_ae857_row22_col4" class="data row22 col4">26</td>
                      <td id="T_ae857_row22_col5" class="data row22 col5">1.320000</td>
                      <td id="T_ae857_row22_col6" class="data row22 col6">108.200000</td>
                      <td id="T_ae857_row22_col7" class="data row22 col7">79</td>
                      <td id="T_ae857_row22_col8" class="data row22 col8">48</td>
                      <td id="T_ae857_row22_col9" class="data row22 col9">45</td>
                      <td id="T_ae857_row22_col10" class="data row22 col10">64</td>
                      <td id="T_ae857_row22_col11" class="data row22 col11">155</td>
                      <td id="T_ae857_row22_col12" class="data row22 col12">13</td>
                      <td id="T_ae857_row22_col13" class="data row22 col13">326</td>
                      <td id="T_ae857_row22_col14" class="data row22 col14">471</td>
                      <td id="T_ae857_row22_col15" class="data row22 col15">3.730000</td>
                      <td id="T_ae857_row22_col16" class="data row22 col16">1</td>
                      <td id="T_ae857_row22_col17" class="data row22 col17">0</td>
                      <td id="T_ae857_row22_col18" class="data row22 col18">0</td>
                      <td id="T_ae857_row22_col19" class="data row22 col19">6</td>
                      <td id="T_ae857_row22_col20" class="data row22 col20">2</td>
                      <td id="T_ae857_row22_col21" class="data row22 col21">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row23_col0" class="data row23 col0">95</td>
                      <td id="T_ae857_row23_col1" class="data row23 col1">Col</td>
                      <td id="T_ae857_row23_col2" class="data row23 col2">24</td>
                      <td id="T_ae857_row23_col3" class="data row23 col3">Ryan Rolison</td>
                      <td id="T_ae857_row23_col4" class="data row23 col4">16</td>
                      <td id="T_ae857_row23_col5" class="data row23 col5">1.370000</td>
                      <td id="T_ae857_row23_col6" class="data row23 col6">71.200000</td>
                      <td id="T_ae857_row23_col7" class="data row23 col7">76</td>
                      <td id="T_ae857_row23_col8" class="data row23 col8">45</td>
                      <td id="T_ae857_row23_col9" class="data row23 col9">42</td>
                      <td id="T_ae857_row23_col10" class="data row23 col10">22</td>
                      <td id="T_ae857_row23_col11" class="data row23 col11">77</td>
                      <td id="T_ae857_row23_col12" class="data row23 col12">9</td>
                      <td id="T_ae857_row23_col13" class="data row23 col13">215</td>
                      <td id="T_ae857_row23_col14" class="data row23 col14">306</td>
                      <td id="T_ae857_row23_col15" class="data row23 col15">5.270000</td>
                      <td id="T_ae857_row23_col16" class="data row23 col16">0</td>
                      <td id="T_ae857_row23_col17" class="data row23 col17">0</td>
                      <td id="T_ae857_row23_col18" class="data row23 col18">0</td>
                      <td id="T_ae857_row23_col19" class="data row23 col19">4</td>
                      <td id="T_ae857_row23_col20" class="data row23 col20">3</td>
                      <td id="T_ae857_row23_col21" class="data row23 col21">ALL (4)</td>
                    </tr>
                    <tr>
                      <td id="T_ae857_row24_col0" class="data row24 col0">99</td>
                      <td id="T_ae857_row24_col1" class="data row24 col1">SF</td>
                      <td id="T_ae857_row24_col2" class="data row24 col2">20</td>
                      <td id="T_ae857_row24_col3" class="data row24 col3">Kyle Harrison</td>
                      <td id="T_ae857_row24_col4" class="data row24 col4">23</td>
                      <td id="T_ae857_row24_col5" class="data row24 col5">1.400000</td>
                      <td id="T_ae857_row24_col6" class="data row24 col6">98.200000</td>
                      <td id="T_ae857_row24_col7" class="data row24 col7">86</td>
                      <td id="T_ae857_row24_col8" class="data row24 col8">43</td>
                      <td id="T_ae857_row24_col9" class="data row24 col9">35</td>
                      <td id="T_ae857_row24_col10" class="data row24 col10">52</td>
                      <td id="T_ae857_row24_col11" class="data row24 col11">157</td>
                      <td id="T_ae857_row24_col12" class="data row24 col12">3</td>
                      <td id="T_ae857_row24_col13" class="data row24 col13">296</td>
                      <td id="T_ae857_row24_col14" class="data row24 col14">440</td>
                      <td id="T_ae857_row24_col15" class="data row24 col15">3.190000</td>
                      <td id="T_ae857_row24_col16" class="data row24 col16">0</td>
                      <td id="T_ae857_row24_col17" class="data row24 col17">0</td>
                      <td id="T_ae857_row24_col18" class="data row24 col18">0</td>
                      <td id="T_ae857_row24_col19" class="data row24 col19">4</td>
                      <td id="T_ae857_row24_col20" class="data row24 col20">3</td>
                      <td id="T_ae857_row24_col21" class="data row24 col21">A</td>
                    </tr>
                  </tbody>
                </table>
              </div>

            </div>

          </div>
        </div>

      </div>
      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

      </div>
      <div class="cell border-box-sizing text_cell rendered">
        <div class="prompt input_prompt">
        </div>
        <div class="inner_cell">
          <div class="text_cell_render border-box-sizing rendered_html">
            <h1 id="Average-Age-of-Pitchers" style="
  padding-left: 350px;
">Average Age of Pitchers<a class="anchor-link" href="#Average-Age-of-Pitchers">&#182;</a></h1>
          </div>
        </div>
      </div>
      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

        <div class="output_wrapper">
          <div class="output">


            <div class="output_area">

              <div class="prompt"></div>




              <div class="output_text output_subarea output_execute_result">
                <!-- <pre>&lt;AxesSubplot:ylabel=&#39;Frequency&#39;&gt;</pre> -->
              </div>

            </div>

            <div class="output_area">

              <div class="prompt"></div>




              <div class="output_png output_subarea output_execute_result">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAXgAAAD4CAYAAADmWv3KAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjMuNCwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy8QVMy6AAAACXBIWXMAAAsTAAALEwEAmpwYAAAOrklEQVR4nO3de6xlZ13G8e/DDKQX2pQ6Bymlw2kJKVSCaTl4K6KAmtJCsQKKAaIYGI1cVQIDJUBiSAooF6MRBtRwKV5ogYAFKRiKMYbCtLRAOyC3gZZWGPzDIhKGws8/9pr2zHAu65yz37NP3/l+kp3Ze+29zvv0nd3nrFlr7bVTVUiS+nO3WQeQJLVhwUtSpyx4SeqUBS9JnbLgJalT22cdYLEdO3bU/Pz8rGNI0l3GNddc8+2qmlvquS1V8PPz8+zdu3fWMSTpLiPJ15Z7zl00ktQpC16SOmXBS1KnLHhJ6pQFL0mdsuAlqVMWvCR1yoKXpE5Z8JLUqS31SVZpq5rffcVMxt1/yQUzGVd9cAtekjplwUtSpyx4SeqUBS9JnbLgJalTFrwkdcqCl6ROWfCS1CkLXpI6ZcFLUqcseEnqlAUvSZ2y4CWpUxa8JHXKgpekTlnwktQpC16SOmXBS1KnLHhJ6lTTgk/yR0luSPK5JH+f5JiW40mS7tSs4JOcCjwPWKiqhwDbgKe0Gk+SdLjWu2i2A8cm2Q4cB9zSeDxJ0qBZwVfVN4A/A74O3Ar8T1VdeeTrkuxKsjfJ3gMHDrSKI0lHnZa7aO4FPAE4HbgvcHySpx35uqraU1ULVbUwNzfXKo4kHXVa7qL5FeCrVXWgqn4AvAf4hYbjSZIWaVnwXwd+LslxSQI8BtjXcDxJ0iIt98FfDVwGXAt8dhhrT6vxJEmH297yh1fVK4BXtBxDkrQ0P8kqSZ2y4CWpUxa8JHXKgpekTlnwktQpC16SOmXBS1KnLHhJ6pQFL0mdsuAlqVMWvCR1yoKXpE5Z8JLUKQtekjplwUtSpyx4SeqUBS9JnWr6jU6S7rrmd18xk3H3X3LBTMbtkVvwktQpC16SOmXBS1KnLHhJ6pQFL0mdsuAlqVMWvCR1yoKXpE5Z8JLUKQtekjplwUtSpyx4SeqUBS9JnbLgJalTFrwkdcqCl6ROWfCS1CkLXpI6ZcFLUqeaFnySk5JcluTzSfYl+fmW40mS7tT6S7ffCPxLVT0pyT2A4xqPJ0kaNCv4JCcCjwR+F6CqDgIHW40nSTpcy100ZwAHgL9L8ukkb01y/JEvSrIryd4kew8cONAwjiQdXVoW/HbgHOCvq+ps4LvA7iNfVFV7qmqhqhbm5uYaxpGko0vLgr8ZuLmqrh4eX8ak8CVJm6BZwVfVfwE3JTlzWPQY4MZW40mSDtf6LJrnApcOZ9B8BXhG4/EkSYOmBV9V1wELLceQJC1t1C6aJA9pHUSSNF1j98G/Kcknk/xhkpNaBpIkTceogq+qRwBPBU4D9iZ5V5JfbZpMkrQho8+iqaovAi8DXgz8EvAXwzVmfqNVOEnS+o3dB//QJK8H9gGPBh5fVQ8e7r++YT5J0jqNPYvmL4G3AC+tqu8dWlhVtyR5WZNkkqQNGVvw5wPfq6ofAiS5G3BMVf1fVb2jWTpJ0rqN3Qf/UeDYRY+PG5ZJkraosQV/TFX976EHw32v7S5JW9jYgv9ukjsuFJbkYcD3Vni9JGnGxu6DfwHw7iS3DI9PAX6rSSJJ0lSMKviq+lSSBwFnAgE+X1U/aJpMkrQha7nY2MOB+WGds5NQVW9vkkqStGGjCj7JO4AHANcBPxwWF2DBS9IWNXYLfgE4q6qqZRhJ0vSMPYvmc8B9WgaRJE3X2C34HcCNST4JfP/Qwqq6sEkqSdKGjS34V7YMIUmavrGnSX48yf2BB1bVR5McB2xrG02StBFjLxf8LOAy4M3DolOB9zXKJEmagrEHWZ8NnAvcBnd8+ce9W4WSJG3c2IL/flUdPPQgyXYm58FLkraosQX/8SQvBY4dvov13cAH2sWSJG3U2ILfDRwAPgv8PvBBJt/PKknaosaeRfMjJl/Z95a2cSRJ0zL2WjRfZYl97lV1xtQTSZKmYi3XojnkGODJwMnTjyNJmpZR++Cr6r8X3b5RVW8AHt02miRpI8buojln0cO7MdmiP6FJIknSVIzdRfPni+7fDuwHfnPqaSRJUzP2LJpHtQ4iSZqusbto/nil56vqddOJI0malrWcRfNw4P3D48cD/wbc1CKUJGnj1vKFH+dU1XcAkrwSeHdVPbNVMEnSxoy9VMFO4OCixweB+amnkSRNzdgt+HcAn0zyXiafaL0IeHuzVJKkDRt7Fs2rknwI+MVh0TOq6tPtYkmSNmrsLhqA44DbquqNwM1JTh+zUpJtST6d5J/XlVCStC5jv7LvFcCLgZcMi+4OvHPkGM8H9q09miRpI8ZuwV8EXAh8F6CqbmHEpQqS3A+4AHjregNKktZn7EHWg1VVSQogyfEj13sD8CJW+GWQZBewC2Dnzp0jf6wA5ndfMZNx919ywUzGlbQ2Y7fg/ynJm4GTkjwL+CirfPlHkscB36qqa1Z6XVXtqaqFqlqYm5sbGUeStJpVt+CTBPhH4EHAbcCZwMur6iOrrHoucGGS85lcQ/7EJO+sqqdtMLMkaYRVC37YNfO+qnoYsFqpL17vJQwHZZP8MvBCy12SNs/YXTSfSPLwpkkkSVM19iDro4A/SLKfyZk0YbJx/9AxK1fVVcBV68gnSVqnFQs+yc6q+jrw2E3KI0maktW24N/H5CqSX0tyeVU9cRMySZKmYLV98Fl0/4yWQSRJ07Vawdcy9yVJW9xqu2h+OsltTLbkjx3uw50HWU9smk6StG4rFnxVbdusIJKk6VrL5YIlSXchFrwkdcqCl6ROWfCS1CkLXpI6ZcFLUqcseEnqlAUvSZ2y4CWpUxa8JHXKgpekTo39Rqctb373FTMZd/8lF8xkXElajVvwktQpC16SOmXBS1KnLHhJ6pQFL0mdsuAlqVMWvCR1yoKXpE5Z8JLUKQtekjplwUtSpyx4SeqUBS9JnbLgJalTFrwkdcqCl6ROWfCS1CkLXpI6ZcFLUqeaFXyS05J8LMm+JDckeX6rsSRJP67ll27fDvxJVV2b5ATgmiQfqaobG44pSRo024Kvqlur6trh/neAfcCprcaTJB2u5Rb8HZLMA2cDVy/x3C5gF8DOnTs3I44kLWl+9xUzGXf/JRc0+bnND7ImuSdwOfCCqrrtyOerak9VLVTVwtzcXOs4knTUaFrwSe7OpNwvrar3tBxLknS4lmfRBPgbYF9Vva7VOJKkpbXcgj8XeDrw6CTXDbfzG44nSVqk2UHWqvp3IK1+viRpZX6SVZI6ZcFLUqcseEnqlAUvSZ2y4CWpUxa8JHXKgpekTlnwktQpC16SOmXBS1KnLHhJ6pQFL0mdsuAlqVMWvCR1yoKXpE5Z8JLUKQtekjplwUtSpyx4SeqUBS9JnbLgJalTFrwkdcqCl6ROWfCS1CkLXpI6ZcFLUqcseEnqlAUvSZ2y4CWpUxa8JHXKgpekTlnwktQpC16SOmXBS1KnLHhJ6pQFL0mdsuAlqVNNCz7JeUm+kORLSXa3HEuSdLhmBZ9kG/BXwGOBs4DfTnJWq/EkSYdruQX/M8CXquorVXUQ+AfgCQ3HkyQtkqpq84OTJwHnVdUzh8dPB362qp5zxOt2AbuGh2cCX1jnkDuAb69z3ZbMtTbmWhtzrU2Pue5fVXNLPbF9/XlWlSWW/dhvk6raA+zZ8GDJ3qpa2OjPmTZzrY251sZca3O05Wq5i+Zm4LRFj+8H3NJwPEnSIi0L/lPAA5OcnuQewFOA9zccT5K0SLNdNFV1e5LnAB8GtgF/W1U3tBqPKezmacRca2OutTHX2hxVuZodZJUkzZafZJWkTlnwktSpLV3wSU5L8rEk+5LckOT5w/KTk3wkyReHP++1zPpNLpUwhVz7k3w2yXVJ9m5CricPj3+UZNlTsWYwX2NzNZmvVbK9Nsnnk3wmyXuTnLTM+ps9Z2NzbfZ77E+HTNcluTLJfZdZf7Pna2yuTZ2vRc+/MEkl2bHM+hubr6rasjfgFOCc4f4JwH8yuezBa4Ddw/LdwKuXWHcb8GXgDOAewPXAWbPONTy3H9ixifP1YCYfIrsKWFhm3VnM16q5Ws7XKtl+Ddg+LH/1FnqPrZprRu+xExe95nnAm7bIfK2aaxbzNTw+jclJKF9bauxpzNeW3oKvqlur6trh/neAfcCpTC558LbhZW8Dfn2J1ZtdKmGDuZpZLldV7auq1T4hvOnzNTJXUytku7Kqbh9e9gkmn+M40izmbEyuZlbIdduilx3PEh9qZDbzNSZXMyt0BcDrgRetkGnD87WlC36xJPPA2cDVwE9W1a0wmUDg3kuscipw06LHN3PnxM4yF0z+Qq9Mck0ml2qYuiNyjTGL+Rqr+XzBitl+D/jQEqvMes6WywUzeI8leVWSm4CnAi9fYpWZzNeIXLDJ85XkQuAbVXX9CqtseL7uEgWf5J7A5cALjviNvOJqSyyb6m/vdeYCOLeqzmFypc1nJ3nkFsh11M7XStmSXAzcDly61GpLLNuUOVslF8zgPVZVF1fVaUOm5yy12hLLms/XiFywifPF5O/tYpb/ZXPHakssW9N8bfmCT3J3JhNzaVW9Z1j8zSSnDM+fAnxriVWbXiphA7moqluGP78FvJfJP8Va5hpjFvM1Ssv5Wilbkt8BHgc8tYadokeYyZyNyDXr99i7gCcusXzW77Hlcm32fD0AOB24Psl+JvNwbZL7HLHqxudr2gcVpnlj8hvs7cAbjlj+Wg4/mPmaJdbdDnxlmMhDByh+agvkOh44YdH9/2By1c1muRY9fxXLH2Td9PkamavZfK3yd3kecCMwt8K6s3iPjcm16e8x4IGL7j8XuGyLzNeYXDP7f3J4zX6WPsi64fna8H9AyxvwCCb/JPkMcN1wOx/4CeBfgS8Of548vP6+wAcXrX8+k6PWXwYu3gq5mBwRv3643bBJuS5isjXwfeCbwIe3yHytmqvlfK2S7UtM9n8eWvamLTJnq+aa0XvscuBzw/IPMDnAuRXma9Vcs5ivI16zn6Hgpz1fXqpAkjq15ffBS5LWx4KXpE5Z8JLUKQtekjplwUtSpyx4SeqUBS9Jnfp/qmLw+nY842cAAAAASUVORK5CYII=
                " style="
                    padding-left: 275px;
                ">
              </div>

            </div>

          </div>
        </div>

      </div>
      <div class="cell border-box-sizing text_cell rendered">
        <div class="prompt input_prompt">
        </div>
        <div class="inner_cell">
          <div class="text_cell_render border-box-sizing rendered_html">
            <h1 id="Hitters-in-Top-100" style="
  padding-left: 400px;
">Hitters in Top 100<a class="anchor-link" href="#Hitters-in-Top-100">&#182;</a></h1>
          </div>
        </div>
      </div>
      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

        <div class="output_wrapper">
          <div class="output">


            <div class="output_area">

              <div class="prompt"></div>



              <div class="output_html rendered_html output_subarea output_execute_result">
                <style type="text/css">
                </style>
                <table id="T_61bdb_">
                  <thead>
                    <tr>
                      <th class="col_heading level0 col0">rank</th>
                      <th class="col_heading level0 col1">team</th>
                      <th class="col_heading level0 col2">age</th>
                      <th class="col_heading level0 col3">full_name</th>
                      <th class="col_heading level0 col4">atBats</th>
                      <th class="col_heading level0 col5">runs</th>
                      <th class="col_heading level0 col6">hits</th>
                      <th class="col_heading level0 col7">doubles</th>
                      <th class="col_heading level0 col8">triples</th>
                      <th class="col_heading level0 col9">homeRuns</th>
                      <th class="col_heading level0 col10">obp</th>
                      <th class="col_heading level0 col11">ops</th>
                      <th class="col_heading level0 col12">slg</th>
                      <th class="col_heading level0 col13">rbi</th>
                      <th class="col_heading level0 col14">baseOnBalls</th>
                      <th class="col_heading level0 col15">strikeOuts</th>
                      <th class="col_heading level0 col16">stolenBases</th>
                      <th class="col_heading level0 col17">caughtStealing</th>
                      <th class="col_heading level0 col18">leftOnBase</th>
                      <th class="col_heading level0 col19">totalBases</th>
                      <th class="col_heading level0 col20">avg</th>
                      <th class="col_heading level0 col21">position</th>
                      <th class="col_heading level0 col22">sportAbbrev</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td id="T_61bdb_row0_col0" class="data row0 col0">1</td>
                      <td id="T_61bdb_row0_col1" class="data row0 col1">Bal</td>
                      <td id="T_61bdb_row0_col2" class="data row0 col2">23</td>
                      <td id="T_61bdb_row0_col3" class="data row0 col3">Adley Rutschman</td>
                      <td id="T_61bdb_row0_col4" class="data row0 col4">442</td>
                      <td id="T_61bdb_row0_col5" class="data row0 col5">84</td>
                      <td id="T_61bdb_row0_col6" class="data row0 col6">127</td>
                      <td id="T_61bdb_row0_col7" class="data row0 col7">25</td>
                      <td id="T_61bdb_row0_col8" class="data row0 col8">2</td>
                      <td id="T_61bdb_row0_col9" class="data row0 col9">23</td>
                      <td id="T_61bdb_row0_col10" class="data row0 col10">0.398000</td>
                      <td id="T_61bdb_row0_col11" class="data row0 col11">0.907000</td>
                      <td id="T_61bdb_row0_col12" class="data row0 col12">0.509000</td>
                      <td id="T_61bdb_row0_col13" class="data row0 col13">75</td>
                      <td id="T_61bdb_row0_col14" class="data row0 col14">77</td>
                      <td id="T_61bdb_row0_col15" class="data row0 col15">89</td>
                      <td id="T_61bdb_row0_col16" class="data row0 col16">3</td>
                      <td id="T_61bdb_row0_col17" class="data row0 col17">4</td>
                      <td id="T_61bdb_row0_col18" class="data row0 col18">174</td>
                      <td id="T_61bdb_row0_col19" class="data row0 col19">225</td>
                      <td id="T_61bdb_row0_col20" class="data row0 col20">0.287000</td>
                      <td id="T_61bdb_row0_col21" class="data row0 col21">C</td>
                      <td id="T_61bdb_row0_col22" class="data row0 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row1_col0" class="data row1 col0">2</td>
                      <td id="T_61bdb_row1_col1" class="data row1 col1">Sea</td>
                      <td id="T_61bdb_row1_col2" class="data row1 col2">20</td>
                      <td id="T_61bdb_row1_col3" class="data row1 col3">Julio Rodriguez</td>
                      <td id="T_61bdb_row1_col4" class="data row1 col4">291</td>
                      <td id="T_61bdb_row1_col5" class="data row1 col5">64</td>
                      <td id="T_61bdb_row1_col6" class="data row1 col6">101</td>
                      <td id="T_61bdb_row1_col7" class="data row1 col7">19</td>
                      <td id="T_61bdb_row1_col8" class="data row1 col8">2</td>
                      <td id="T_61bdb_row1_col9" class="data row1 col9">13</td>
                      <td id="T_61bdb_row1_col10" class="data row1 col10">0.441000</td>
                      <td id="T_61bdb_row1_col11" class="data row1 col11">1.001000</td>
                      <td id="T_61bdb_row1_col12" class="data row1 col12">0.560000</td>
                      <td id="T_61bdb_row1_col13" class="data row1 col13">47</td>
                      <td id="T_61bdb_row1_col14" class="data row1 col14">43</td>
                      <td id="T_61bdb_row1_col15" class="data row1 col15">66</td>
                      <td id="T_61bdb_row1_col16" class="data row1 col16">21</td>
                      <td id="T_61bdb_row1_col17" class="data row1 col17">5</td>
                      <td id="T_61bdb_row1_col18" class="data row1 col18">104</td>
                      <td id="T_61bdb_row1_col19" class="data row1 col19">163</td>
                      <td id="T_61bdb_row1_col20" class="data row1 col20">0.347000</td>
                      <td id="T_61bdb_row1_col21" class="data row1 col21">RF</td>
                      <td id="T_61bdb_row1_col22" class="data row1 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row2_col0" class="data row2 col0">3</td>
                      <td id="T_61bdb_row2_col1" class="data row2 col1">Kan</td>
                      <td id="T_61bdb_row2_col2" class="data row2 col2">21</td>
                      <td id="T_61bdb_row2_col3" class="data row2 col3">Bobby Witt Jr.</td>
                      <td id="T_61bdb_row2_col4" class="data row2 col4">488</td>
                      <td id="T_61bdb_row2_col5" class="data row2 col5">98</td>
                      <td id="T_61bdb_row2_col6" class="data row2 col6">143</td>
                      <td id="T_61bdb_row2_col7" class="data row2 col7">35</td>
                      <td id="T_61bdb_row2_col8" class="data row2 col8">4</td>
                      <td id="T_61bdb_row2_col9" class="data row2 col9">33</td>
                      <td id="T_61bdb_row2_col10" class="data row2 col10">0.363000</td>
                      <td id="T_61bdb_row2_col11" class="data row2 col11">0.948000</td>
                      <td id="T_61bdb_row2_col12" class="data row2 col12">0.584000</td>
                      <td id="T_61bdb_row2_col13" class="data row2 col13">96</td>
                      <td id="T_61bdb_row2_col14" class="data row2 col14">50</td>
                      <td id="T_61bdb_row2_col15" class="data row2 col15">127</td>
                      <td id="T_61bdb_row2_col16" class="data row2 col16">29</td>
                      <td id="T_61bdb_row2_col17" class="data row2 col17">10</td>
                      <td id="T_61bdb_row2_col18" class="data row2 col18">212</td>
                      <td id="T_61bdb_row2_col19" class="data row2 col19">285</td>
                      <td id="T_61bdb_row2_col20" class="data row2 col20">0.293000</td>
                      <td id="T_61bdb_row2_col21" class="data row2 col21">SS</td>
                      <td id="T_61bdb_row2_col22" class="data row2 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row3_col0" class="data row3 col0">4</td>
                      <td id="T_61bdb_row3_col1" class="data row3 col1">Det</td>
                      <td id="T_61bdb_row3_col2" class="data row3 col2">22</td>
                      <td id="T_61bdb_row3_col3" class="data row3 col3">Spencer Torkelson</td>
                      <td id="T_61bdb_row3_col4" class="data row3 col4">422</td>
                      <td id="T_61bdb_row3_col5" class="data row3 col5">85</td>
                      <td id="T_61bdb_row3_col6" class="data row3 col6">113</td>
                      <td id="T_61bdb_row3_col7" class="data row3 col7">29</td>
                      <td id="T_61bdb_row3_col8" class="data row3 col8">2</td>
                      <td id="T_61bdb_row3_col9" class="data row3 col9">29</td>
                      <td id="T_61bdb_row3_col10" class="data row3 col10">0.380000</td>
                      <td id="T_61bdb_row3_col11" class="data row3 col11">0.932000</td>
                      <td id="T_61bdb_row3_col12" class="data row3 col12">0.552000</td>
                      <td id="T_61bdb_row3_col13" class="data row3 col13">90</td>
                      <td id="T_61bdb_row3_col14" class="data row3 col14">72</td>
                      <td id="T_61bdb_row3_col15" class="data row3 col15">114</td>
                      <td id="T_61bdb_row3_col16" class="data row3 col16">5</td>
                      <td id="T_61bdb_row3_col17" class="data row3 col17">3</td>
                      <td id="T_61bdb_row3_col18" class="data row3 col18">196</td>
                      <td id="T_61bdb_row3_col19" class="data row3 col19">233</td>
                      <td id="T_61bdb_row3_col20" class="data row3 col20">0.268000</td>
                      <td id="T_61bdb_row3_col21" class="data row3 col21">3B</td>
                      <td id="T_61bdb_row3_col22" class="data row3 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row4_col0" class="data row4 col0">5</td>
                      <td id="T_61bdb_row4_col1" class="data row4 col1">SF</td>
                      <td id="T_61bdb_row4_col2" class="data row4 col2">20</td>
                      <td id="T_61bdb_row4_col3" class="data row4 col3">Marco Luciano</td>
                      <td id="T_61bdb_row4_col4" class="data row4 col4">395</td>
                      <td id="T_61bdb_row4_col5" class="data row4 col5">68</td>
                      <td id="T_61bdb_row4_col6" class="data row4 col6">102</td>
                      <td id="T_61bdb_row4_col7" class="data row4 col7">17</td>
                      <td id="T_61bdb_row4_col8" class="data row4 col8">5</td>
                      <td id="T_61bdb_row4_col9" class="data row4 col9">19</td>
                      <td id="T_61bdb_row4_col10" class="data row4 col10">0.344000</td>
                      <td id="T_61bdb_row4_col11" class="data row4 col11">0.815000</td>
                      <td id="T_61bdb_row4_col12" class="data row4 col12">0.471000</td>
                      <td id="T_61bdb_row4_col13" class="data row4 col13">71</td>
                      <td id="T_61bdb_row4_col14" class="data row4 col14">48</td>
                      <td id="T_61bdb_row4_col15" class="data row4 col15">122</td>
                      <td id="T_61bdb_row4_col16" class="data row4 col16">6</td>
                      <td id="T_61bdb_row4_col17" class="data row4 col17">5</td>
                      <td id="T_61bdb_row4_col18" class="data row4 col18">192</td>
                      <td id="T_61bdb_row4_col19" class="data row4 col19">186</td>
                      <td id="T_61bdb_row4_col20" class="data row4 col20">0.258000</td>
                      <td id="T_61bdb_row4_col21" class="data row4 col21">SS</td>
                      <td id="T_61bdb_row4_col22" class="data row4 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row5_col0" class="data row5 col0">6</td>
                      <td id="T_61bdb_row5_col1" class="data row5 col1">SD</td>
                      <td id="T_61bdb_row5_col2" class="data row5 col2">20</td>
                      <td id="T_61bdb_row5_col3" class="data row5 col3">CJ Abrams</td>
                      <td id="T_61bdb_row5_col4" class="data row5 col4">162</td>
                      <td id="T_61bdb_row5_col5" class="data row5 col5">26</td>
                      <td id="T_61bdb_row5_col6" class="data row5 col6">48</td>
                      <td id="T_61bdb_row5_col7" class="data row5 col7">14</td>
                      <td id="T_61bdb_row5_col8" class="data row5 col8">0</td>
                      <td id="T_61bdb_row5_col9" class="data row5 col9">2</td>
                      <td id="T_61bdb_row5_col10" class="data row5 col10">0.363000</td>
                      <td id="T_61bdb_row5_col11" class="data row5 col11">0.782000</td>
                      <td id="T_61bdb_row5_col12" class="data row5 col12">0.420000</td>
                      <td id="T_61bdb_row5_col13" class="data row5 col13">23</td>
                      <td id="T_61bdb_row5_col14" class="data row5 col14">15</td>
                      <td id="T_61bdb_row5_col15" class="data row5 col15">36</td>
                      <td id="T_61bdb_row5_col16" class="data row5 col16">13</td>
                      <td id="T_61bdb_row5_col17" class="data row5 col17">2</td>
                      <td id="T_61bdb_row5_col18" class="data row5 col18">59</td>
                      <td id="T_61bdb_row5_col19" class="data row5 col19">68</td>
                      <td id="T_61bdb_row5_col20" class="data row5 col20">0.296000</td>
                      <td id="T_61bdb_row5_col21" class="data row5 col21">SS</td>
                      <td id="T_61bdb_row5_col22" class="data row5 col22">AA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row6_col0" class="data row6 col0">7</td>
                      <td id="T_61bdb_row6_col1" class="data row6 col1">Det</td>
                      <td id="T_61bdb_row6_col2" class="data row6 col2">21</td>
                      <td id="T_61bdb_row6_col3" class="data row6 col3">Riley Greene</td>
                      <td id="T_61bdb_row6_col4" class="data row6 col4">479</td>
                      <td id="T_61bdb_row6_col5" class="data row6 col5">91</td>
                      <td id="T_61bdb_row6_col6" class="data row6 col6">144</td>
                      <td id="T_61bdb_row6_col7" class="data row6 col7">24</td>
                      <td id="T_61bdb_row6_col8" class="data row6 col8">8</td>
                      <td id="T_61bdb_row6_col9" class="data row6 col9">23</td>
                      <td id="T_61bdb_row6_col10" class="data row6 col10">0.383000</td>
                      <td id="T_61bdb_row6_col11" class="data row6 col11">0.911000</td>
                      <td id="T_61bdb_row6_col12" class="data row6 col12">0.528000</td>
                      <td id="T_61bdb_row6_col13" class="data row6 col13">82</td>
                      <td id="T_61bdb_row6_col14" class="data row6 col14">60</td>
                      <td id="T_61bdb_row6_col15" class="data row6 col15">150</td>
                      <td id="T_61bdb_row6_col16" class="data row6 col16">15</td>
                      <td id="T_61bdb_row6_col17" class="data row6 col17">1</td>
                      <td id="T_61bdb_row6_col18" class="data row6 col18">172</td>
                      <td id="T_61bdb_row6_col19" class="data row6 col19">253</td>
                      <td id="T_61bdb_row6_col20" class="data row6 col20">0.301000</td>
                      <td id="T_61bdb_row6_col21" class="data row6 col21">OF</td>
                      <td id="T_61bdb_row6_col22" class="data row6 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row7_col0" class="data row7 col0">9</td>
                      <td id="T_61bdb_row7_col1" class="data row7 col1">Bos</td>
                      <td id="T_61bdb_row7_col2" class="data row7 col2">18</td>
                      <td id="T_61bdb_row7_col3" class="data row7 col3">Marcelo Mayer</td>
                      <td id="T_61bdb_row7_col4" class="data row7 col4">91</td>
                      <td id="T_61bdb_row7_col5" class="data row7 col5">25</td>
                      <td id="T_61bdb_row7_col6" class="data row7 col6">25</td>
                      <td id="T_61bdb_row7_col7" class="data row7 col7">4</td>
                      <td id="T_61bdb_row7_col8" class="data row7 col8">1</td>
                      <td id="T_61bdb_row7_col9" class="data row7 col9">3</td>
                      <td id="T_61bdb_row7_col10" class="data row7 col10">0.377000</td>
                      <td id="T_61bdb_row7_col11" class="data row7 col11">0.817000</td>
                      <td id="T_61bdb_row7_col12" class="data row7 col12">0.440000</td>
                      <td id="T_61bdb_row7_col13" class="data row7 col13">17</td>
                      <td id="T_61bdb_row7_col14" class="data row7 col14">15</td>
                      <td id="T_61bdb_row7_col15" class="data row7 col15">27</td>
                      <td id="T_61bdb_row7_col16" class="data row7 col16">7</td>
                      <td id="T_61bdb_row7_col17" class="data row7 col17">1</td>
                      <td id="T_61bdb_row7_col18" class="data row7 col18">42</td>
                      <td id="T_61bdb_row7_col19" class="data row7 col19">40</td>
                      <td id="T_61bdb_row7_col20" class="data row7 col20">0.275000</td>
                      <td id="T_61bdb_row7_col21" class="data row7 col21">SS</td>
                      <td id="T_61bdb_row7_col22" class="data row7 col22">ROK</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row8_col0" class="data row8 col0">10</td>
                      <td id="T_61bdb_row8_col1" class="data row8 col1">NYM</td>
                      <td id="T_61bdb_row8_col2" class="data row8 col2">19</td>
                      <td id="T_61bdb_row8_col3" class="data row8 col3">Francisco Alvarez</td>
                      <td id="T_61bdb_row8_col4" class="data row8 col4">327</td>
                      <td id="T_61bdb_row8_col5" class="data row8 col5">67</td>
                      <td id="T_61bdb_row8_col6" class="data row8 col6">89</td>
                      <td id="T_61bdb_row8_col7" class="data row8 col7">18</td>
                      <td id="T_61bdb_row8_col8" class="data row8 col8">1</td>
                      <td id="T_61bdb_row8_col9" class="data row8 col9">24</td>
                      <td id="T_61bdb_row8_col10" class="data row8 col10">0.388000</td>
                      <td id="T_61bdb_row8_col11" class="data row8 col11">0.941000</td>
                      <td id="T_61bdb_row8_col12" class="data row8 col12">0.554000</td>
                      <td id="T_61bdb_row8_col13" class="data row8 col13">70</td>
                      <td id="T_61bdb_row8_col14" class="data row8 col14">55</td>
                      <td id="T_61bdb_row8_col15" class="data row8 col15">89</td>
                      <td id="T_61bdb_row8_col16" class="data row8 col16">8</td>
                      <td id="T_61bdb_row8_col17" class="data row8 col17">5</td>
                      <td id="T_61bdb_row8_col18" class="data row8 col18">152</td>
                      <td id="T_61bdb_row8_col19" class="data row8 col19">181</td>
                      <td id="T_61bdb_row8_col20" class="data row8 col20">0.272000</td>
                      <td id="T_61bdb_row8_col21" class="data row8 col21">C</td>
                      <td id="T_61bdb_row8_col22" class="data row8 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row9_col0" class="data row9 col0">11</td>
                      <td id="T_61bdb_row9_col1" class="data row9 col1">Sea</td>
                      <td id="T_61bdb_row9_col2" class="data row9 col2">19</td>
                      <td id="T_61bdb_row9_col3" class="data row9 col3">Noelvi Marte</td>
                      <td id="T_61bdb_row9_col4" class="data row9 col4">444</td>
                      <td id="T_61bdb_row9_col5" class="data row9 col5">91</td>
                      <td id="T_61bdb_row9_col6" class="data row9 col6">121</td>
                      <td id="T_61bdb_row9_col7" class="data row9 col7">28</td>
                      <td id="T_61bdb_row9_col8" class="data row9 col8">2</td>
                      <td id="T_61bdb_row9_col9" class="data row9 col9">17</td>
                      <td id="T_61bdb_row9_col10" class="data row9 col10">0.366000</td>
                      <td id="T_61bdb_row9_col11" class="data row9 col11">0.825000</td>
                      <td id="T_61bdb_row9_col12" class="data row9 col12">0.459000</td>
                      <td id="T_61bdb_row9_col13" class="data row9 col13">71</td>
                      <td id="T_61bdb_row9_col14" class="data row9 col14">60</td>
                      <td id="T_61bdb_row9_col15" class="data row9 col15">117</td>
                      <td id="T_61bdb_row9_col16" class="data row9 col16">24</td>
                      <td id="T_61bdb_row9_col17" class="data row9 col17">7</td>
                      <td id="T_61bdb_row9_col18" class="data row9 col18">205</td>
                      <td id="T_61bdb_row9_col19" class="data row9 col19">204</td>
                      <td id="T_61bdb_row9_col20" class="data row9 col20">0.273000</td>
                      <td id="T_61bdb_row9_col21" class="data row9 col21">SS</td>
                      <td id="T_61bdb_row9_col22" class="data row9 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row10_col0" class="data row10 col0">13</td>
                      <td id="T_61bdb_row10_col1" class="data row10 col1">Ari</td>
                      <td id="T_61bdb_row10_col2" class="data row10 col2">19</td>
                      <td id="T_61bdb_row10_col3" class="data row10 col3">Jordan Lawlar</td>
                      <td id="T_61bdb_row10_col4" class="data row10 col4">5</td>
                      <td id="T_61bdb_row10_col5" class="data row10 col5">0</td>
                      <td id="T_61bdb_row10_col6" class="data row10 col6">2</td>
                      <td id="T_61bdb_row10_col7" class="data row10 col7">1</td>
                      <td id="T_61bdb_row10_col8" class="data row10 col8">0</td>
                      <td id="T_61bdb_row10_col9" class="data row10 col9">0</td>
                      <td id="T_61bdb_row10_col10" class="data row10 col10">0.500000</td>
                      <td id="T_61bdb_row10_col11" class="data row10 col11">1.100000</td>
                      <td id="T_61bdb_row10_col12" class="data row10 col12">0.600000</td>
                      <td id="T_61bdb_row10_col13" class="data row10 col13">1</td>
                      <td id="T_61bdb_row10_col14" class="data row10 col14">1</td>
                      <td id="T_61bdb_row10_col15" class="data row10 col15">1</td>
                      <td id="T_61bdb_row10_col16" class="data row10 col16">1</td>
                      <td id="T_61bdb_row10_col17" class="data row10 col17">0</td>
                      <td id="T_61bdb_row10_col18" class="data row10 col18">2</td>
                      <td id="T_61bdb_row10_col19" class="data row10 col19">3</td>
                      <td id="T_61bdb_row10_col20" class="data row10 col20">0.400000</td>
                      <td id="T_61bdb_row10_col21" class="data row10 col21">SS</td>
                      <td id="T_61bdb_row10_col22" class="data row10 col22">ROK</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row11_col0" class="data row11 col0">14</td>
                      <td id="T_61bdb_row11_col1" class="data row11 col1">CHC</td>
                      <td id="T_61bdb_row11_col2" class="data row11 col2">21</td>
                      <td id="T_61bdb_row11_col3" class="data row11 col3">Brennen Davis</td>
                      <td id="T_61bdb_row11_col4" class="data row11 col4">339</td>
                      <td id="T_61bdb_row11_col5" class="data row11 col5">66</td>
                      <td id="T_61bdb_row11_col6" class="data row11 col6">91</td>
                      <td id="T_61bdb_row11_col7" class="data row11 col7">25</td>
                      <td id="T_61bdb_row11_col8" class="data row11 col8">0</td>
                      <td id="T_61bdb_row11_col9" class="data row11 col9">19</td>
                      <td id="T_61bdb_row11_col10" class="data row11 col10">0.379000</td>
                      <td id="T_61bdb_row11_col11" class="data row11 col11">0.889000</td>
                      <td id="T_61bdb_row11_col12" class="data row11 col12">0.510000</td>
                      <td id="T_61bdb_row11_col13" class="data row11 col13">51</td>
                      <td id="T_61bdb_row11_col14" class="data row11 col14">47</td>
                      <td id="T_61bdb_row11_col15" class="data row11 col15">115</td>
                      <td id="T_61bdb_row11_col16" class="data row11 col16">8</td>
                      <td id="T_61bdb_row11_col17" class="data row11 col17">4</td>
                      <td id="T_61bdb_row11_col18" class="data row11 col18">161</td>
                      <td id="T_61bdb_row11_col19" class="data row11 col19">173</td>
                      <td id="T_61bdb_row11_col20" class="data row11 col20">0.268000</td>
                      <td id="T_61bdb_row11_col21" class="data row11 col21">CF</td>
                      <td id="T_61bdb_row11_col22" class="data row11 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row12_col0" class="data row12 col0">15</td>
                      <td id="T_61bdb_row12_col1" class="data row12 col1">NYY</td>
                      <td id="T_61bdb_row12_col2" class="data row12 col2">20</td>
                      <td id="T_61bdb_row12_col3" class="data row12 col3">Anthony Volpe</td>
                      <td id="T_61bdb_row12_col4" class="data row12 col4">412</td>
                      <td id="T_61bdb_row12_col5" class="data row12 col5">113</td>
                      <td id="T_61bdb_row12_col6" class="data row12 col6">121</td>
                      <td id="T_61bdb_row12_col7" class="data row12 col7">35</td>
                      <td id="T_61bdb_row12_col8" class="data row12 col8">6</td>
                      <td id="T_61bdb_row12_col9" class="data row12 col9">27</td>
                      <td id="T_61bdb_row12_col10" class="data row12 col10">0.423000</td>
                      <td id="T_61bdb_row12_col11" class="data row12 col11">1.027000</td>
                      <td id="T_61bdb_row12_col12" class="data row12 col12">0.604000</td>
                      <td id="T_61bdb_row12_col13" class="data row12 col13">86</td>
                      <td id="T_61bdb_row12_col14" class="data row12 col14">78</td>
                      <td id="T_61bdb_row12_col15" class="data row12 col15">101</td>
                      <td id="T_61bdb_row12_col16" class="data row12 col16">33</td>
                      <td id="T_61bdb_row12_col17" class="data row12 col17">9</td>
                      <td id="T_61bdb_row12_col18" class="data row12 col18">165</td>
                      <td id="T_61bdb_row12_col19" class="data row12 col19">249</td>
                      <td id="T_61bdb_row12_col20" class="data row12 col20">0.294000</td>
                      <td id="T_61bdb_row12_col21" class="data row12 col21">2B</td>
                      <td id="T_61bdb_row12_col22" class="data row12 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row13_col0" class="data row13 col0">16</td>
                      <td id="T_61bdb_row13_col1" class="data row13 col1">SF</td>
                      <td id="T_61bdb_row13_col2" class="data row13 col2">24</td>
                      <td id="T_61bdb_row13_col3" class="data row13 col3">Joey Bart</td>
                      <td id="T_61bdb_row13_col4" class="data row13 col4">257</td>
                      <td id="T_61bdb_row13_col5" class="data row13 col5">38</td>
                      <td id="T_61bdb_row13_col6" class="data row13 col6">76</td>
                      <td id="T_61bdb_row13_col7" class="data row13 col7">15</td>
                      <td id="T_61bdb_row13_col8" class="data row13 col8">0</td>
                      <td id="T_61bdb_row13_col9" class="data row13 col9">10</td>
                      <td id="T_61bdb_row13_col10" class="data row13 col10">0.359000</td>
                      <td id="T_61bdb_row13_col11" class="data row13 col11">0.830000</td>
                      <td id="T_61bdb_row13_col12" class="data row13 col12">0.471000</td>
                      <td id="T_61bdb_row13_col13" class="data row13 col13">47</td>
                      <td id="T_61bdb_row13_col14" class="data row13 col14">21</td>
                      <td id="T_61bdb_row13_col15" class="data row13 col15">83</td>
                      <td id="T_61bdb_row13_col16" class="data row13 col16">0</td>
                      <td id="T_61bdb_row13_col17" class="data row13 col17">0</td>
                      <td id="T_61bdb_row13_col18" class="data row13 col18">135</td>
                      <td id="T_61bdb_row13_col19" class="data row13 col19">121</td>
                      <td id="T_61bdb_row13_col20" class="data row13 col20">0.296000</td>
                      <td id="T_61bdb_row13_col21" class="data row13 col21">C</td>
                      <td id="T_61bdb_row13_col22" class="data row13 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row14_col0" class="data row14 col0">18</td>
                      <td id="T_61bdb_row14_col1" class="data row14 col1">Bos</td>
                      <td id="T_61bdb_row14_col2" class="data row14 col2">21</td>
                      <td id="T_61bdb_row14_col3" class="data row14 col3">Triston Casas</td>
                      <td id="T_61bdb_row14_col4" class="data row14 col4">299</td>
                      <td id="T_61bdb_row14_col5" class="data row14 col5">61</td>
                      <td id="T_61bdb_row14_col6" class="data row14 col6">84</td>
                      <td id="T_61bdb_row14_col7" class="data row14 col7">14</td>
                      <td id="T_61bdb_row14_col8" class="data row14 col8">3</td>
                      <td id="T_61bdb_row14_col9" class="data row14 col9">14</td>
                      <td id="T_61bdb_row14_col10" class="data row14 col10">0.394000</td>
                      <td id="T_61bdb_row14_col11" class="data row14 col11">0.883000</td>
                      <td id="T_61bdb_row14_col12" class="data row14 col12">0.488000</td>
                      <td id="T_61bdb_row14_col13" class="data row14 col13">59</td>
                      <td id="T_61bdb_row14_col14" class="data row14 col14">55</td>
                      <td id="T_61bdb_row14_col15" class="data row14 col15">70</td>
                      <td id="T_61bdb_row14_col16" class="data row14 col16">7</td>
                      <td id="T_61bdb_row14_col17" class="data row14 col17">3</td>
                      <td id="T_61bdb_row14_col18" class="data row14 col18">151</td>
                      <td id="T_61bdb_row14_col19" class="data row14 col19">146</td>
                      <td id="T_61bdb_row14_col20" class="data row14 col20">0.281000</td>
                      <td id="T_61bdb_row14_col21" class="data row14 col21">3B</td>
                      <td id="T_61bdb_row14_col22" class="data row14 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row15_col0" class="data row15 col0">20</td>
                      <td id="T_61bdb_row15_col1" class="data row15 col1">Ari</td>
                      <td id="T_61bdb_row15_col2" class="data row15 col2">21</td>
                      <td id="T_61bdb_row15_col3" class="data row15 col3">Corbin Carroll</td>
                      <td id="T_61bdb_row15_col4" class="data row15 col4">23</td>
                      <td id="T_61bdb_row15_col5" class="data row15 col5">9</td>
                      <td id="T_61bdb_row15_col6" class="data row15 col6">10</td>
                      <td id="T_61bdb_row15_col7" class="data row15 col7">1</td>
                      <td id="T_61bdb_row15_col8" class="data row15 col8">2</td>
                      <td id="T_61bdb_row15_col9" class="data row15 col9">2</td>
                      <td id="T_61bdb_row15_col10" class="data row15 col10">0.552000</td>
                      <td id="T_61bdb_row15_col11" class="data row15 col11">1.465000</td>
                      <td id="T_61bdb_row15_col12" class="data row15 col12">0.913000</td>
                      <td id="T_61bdb_row15_col13" class="data row15 col13">5</td>
                      <td id="T_61bdb_row15_col14" class="data row15 col14">6</td>
                      <td id="T_61bdb_row15_col15" class="data row15 col15">7</td>
                      <td id="T_61bdb_row15_col16" class="data row15 col16">3</td>
                      <td id="T_61bdb_row15_col17" class="data row15 col17">1</td>
                      <td id="T_61bdb_row15_col18" class="data row15 col18">0</td>
                      <td id="T_61bdb_row15_col19" class="data row15 col19">21</td>
                      <td id="T_61bdb_row15_col20" class="data row15 col20">0.435000</td>
                      <td id="T_61bdb_row15_col21" class="data row15 col21">CF</td>
                      <td id="T_61bdb_row15_col22" class="data row15 col22">A+</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row16_col0" class="data row16 col0">21</td>
                      <td id="T_61bdb_row16_col1" class="data row16 col1">Tam</td>
                      <td id="T_61bdb_row16_col2" class="data row16 col2">23</td>
                      <td id="T_61bdb_row16_col3" class="data row16 col3">Vidal Brujan</td>
                      <td id="T_61bdb_row16_col4" class="data row16 col4">407</td>
                      <td id="T_61bdb_row16_col5" class="data row16 col5">78</td>
                      <td id="T_61bdb_row16_col6" class="data row16 col6">102</td>
                      <td id="T_61bdb_row16_col7" class="data row16 col7">31</td>
                      <td id="T_61bdb_row16_col8" class="data row16 col8">1</td>
                      <td id="T_61bdb_row16_col9" class="data row16 col9">12</td>
                      <td id="T_61bdb_row16_col10" class="data row16 col10">0.332000</td>
                      <td id="T_61bdb_row16_col11" class="data row16 col11">0.752000</td>
                      <td id="T_61bdb_row16_col12" class="data row16 col12">0.420000</td>
                      <td id="T_61bdb_row16_col13" class="data row16 col13">58</td>
                      <td id="T_61bdb_row16_col14" class="data row16 col14">49</td>
                      <td id="T_61bdb_row16_col15" class="data row16 col15">76</td>
                      <td id="T_61bdb_row16_col16" class="data row16 col16">45</td>
                      <td id="T_61bdb_row16_col17" class="data row16 col17">8</td>
                      <td id="T_61bdb_row16_col18" class="data row16 col18">135</td>
                      <td id="T_61bdb_row16_col19" class="data row16 col19">171</td>
                      <td id="T_61bdb_row16_col20" class="data row16 col20">0.251000</td>
                      <td id="T_61bdb_row16_col21" class="data row16 col21">CF</td>
                      <td id="T_61bdb_row16_col22" class="data row16 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row17_col0" class="data row17 col0">22</td>
                      <td id="T_61bdb_row17_col1" class="data row17 col1">Pit</td>
                      <td id="T_61bdb_row17_col2" class="data row17 col2">22</td>
                      <td id="T_61bdb_row17_col3" class="data row17 col3">Henry Davis</td>
                      <td id="T_61bdb_row17_col4" class="data row17 col4">26</td>
                      <td id="T_61bdb_row17_col5" class="data row17 col5">7</td>
                      <td id="T_61bdb_row17_col6" class="data row17 col6">8</td>
                      <td id="T_61bdb_row17_col7" class="data row17 col7">2</td>
                      <td id="T_61bdb_row17_col8" class="data row17 col8">1</td>
                      <td id="T_61bdb_row17_col9" class="data row17 col9">3</td>
                      <td id="T_61bdb_row17_col10" class="data row17 col10">0.387000</td>
                      <td id="T_61bdb_row17_col11" class="data row17 col11">1.195000</td>
                      <td id="T_61bdb_row17_col12" class="data row17 col12">0.808000</td>
                      <td id="T_61bdb_row17_col13" class="data row17 col13">7</td>
                      <td id="T_61bdb_row17_col14" class="data row17 col14">4</td>
                      <td id="T_61bdb_row17_col15" class="data row17 col15">10</td>
                      <td id="T_61bdb_row17_col16" class="data row17 col16">1</td>
                      <td id="T_61bdb_row17_col17" class="data row17 col17">0</td>
                      <td id="T_61bdb_row17_col18" class="data row17 col18">14</td>
                      <td id="T_61bdb_row17_col19" class="data row17 col19">21</td>
                      <td id="T_61bdb_row17_col20" class="data row17 col20">0.308000</td>
                      <td id="T_61bdb_row17_col21" class="data row17 col21">C</td>
                      <td id="T_61bdb_row17_col22" class="data row17 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row18_col0" class="data row18 col0">24</td>
                      <td id="T_61bdb_row18_col1" class="data row18 col1">STL</td>
                      <td id="T_61bdb_row18_col2" class="data row18 col2">21</td>
                      <td id="T_61bdb_row18_col3" class="data row18 col3">Nolan Gorman</td>
                      <td id="T_61bdb_row18_col4" class="data row18 col4">480</td>
                      <td id="T_61bdb_row18_col5" class="data row18 col5">71</td>
                      <td id="T_61bdb_row18_col6" class="data row18 col6">134</td>
                      <td id="T_61bdb_row18_col7" class="data row18 col7">20</td>
                      <td id="T_61bdb_row18_col8" class="data row18 col8">1</td>
                      <td id="T_61bdb_row18_col9" class="data row18 col9">25</td>
                      <td id="T_61bdb_row18_col10" class="data row18 col10">0.333000</td>
                      <td id="T_61bdb_row18_col11" class="data row18 col11">0.814000</td>
                      <td id="T_61bdb_row18_col12" class="data row18 col12">0.481000</td>
                      <td id="T_61bdb_row18_col13" class="data row18 col13">75</td>
                      <td id="T_61bdb_row18_col14" class="data row18 col14">38</td>
                      <td id="T_61bdb_row18_col15" class="data row18 col15">115</td>
                      <td id="T_61bdb_row18_col16" class="data row18 col16">7</td>
                      <td id="T_61bdb_row18_col17" class="data row18 col17">0</td>
                      <td id="T_61bdb_row18_col18" class="data row18 col18">190</td>
                      <td id="T_61bdb_row18_col19" class="data row18 col19">231</td>
                      <td id="T_61bdb_row18_col20" class="data row18 col20">0.279000</td>
                      <td id="T_61bdb_row18_col21" class="data row18 col21">3B</td>
                      <td id="T_61bdb_row18_col22" class="data row18 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row19_col0" class="data row19 col0">25</td>
                      <td id="T_61bdb_row19_col1" class="data row19 col1">Bos</td>
                      <td id="T_61bdb_row19_col2" class="data row19 col2">25</td>
                      <td id="T_61bdb_row19_col3" class="data row19 col3">Jarren Duran</td>
                      <td id="T_61bdb_row19_col4" class="data row19 col4">338</td>
                      <td id="T_61bdb_row19_col5" class="data row19 col5">60</td>
                      <td id="T_61bdb_row19_col6" class="data row19 col6">82</td>
                      <td id="T_61bdb_row19_col7" class="data row19 col7">14</td>
                      <td id="T_61bdb_row19_col8" class="data row19 col8">3</td>
                      <td id="T_61bdb_row19_col9" class="data row19 col9">18</td>
                      <td id="T_61bdb_row19_col10" class="data row19 col10">0.319000</td>
                      <td id="T_61bdb_row19_col11" class="data row19 col11">0.781000</td>
                      <td id="T_61bdb_row19_col12" class="data row19 col12">0.462000</td>
                      <td id="T_61bdb_row19_col13" class="data row19 col13">45</td>
                      <td id="T_61bdb_row19_col14" class="data row19 col14">33</td>
                      <td id="T_61bdb_row19_col15" class="data row19 col15">101</td>
                      <td id="T_61bdb_row19_col16" class="data row19 col16">18</td>
                      <td id="T_61bdb_row19_col17" class="data row19 col17">4</td>
                      <td id="T_61bdb_row19_col18" class="data row19 col18">147</td>
                      <td id="T_61bdb_row19_col19" class="data row19 col19">156</td>
                      <td id="T_61bdb_row19_col20" class="data row19 col20">0.243000</td>
                      <td id="T_61bdb_row19_col21" class="data row19 col21">CF</td>
                      <td id="T_61bdb_row19_col22" class="data row19 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row20_col0" class="data row20 col0">26</td>
                      <td id="T_61bdb_row20_col1" class="data row20 col1">Cin</td>
                      <td id="T_61bdb_row20_col2" class="data row20 col2">22</td>
                      <td id="T_61bdb_row20_col3" class="data row20 col3">Hunter Greene</td>
                      <td id="T_61bdb_row20_col4" class="data row20 col4">19</td>
                      <td id="T_61bdb_row20_col5" class="data row20 col5">0</td>
                      <td id="T_61bdb_row20_col6" class="data row20 col6">3</td>
                      <td id="T_61bdb_row20_col7" class="data row20 col7">0</td>
                      <td id="T_61bdb_row20_col8" class="data row20 col8">0</td>
                      <td id="T_61bdb_row20_col9" class="data row20 col9">0</td>
                      <td id="T_61bdb_row20_col10" class="data row20 col10">0.158000</td>
                      <td id="T_61bdb_row20_col11" class="data row20 col11">0.316000</td>
                      <td id="T_61bdb_row20_col12" class="data row20 col12">0.158000</td>
                      <td id="T_61bdb_row20_col13" class="data row20 col13">1</td>
                      <td id="T_61bdb_row20_col14" class="data row20 col14">0</td>
                      <td id="T_61bdb_row20_col15" class="data row20 col15">6</td>
                      <td id="T_61bdb_row20_col16" class="data row20 col16">0</td>
                      <td id="T_61bdb_row20_col17" class="data row20 col17">0</td>
                      <td id="T_61bdb_row20_col18" class="data row20 col18">5</td>
                      <td id="T_61bdb_row20_col19" class="data row20 col19">3</td>
                      <td id="T_61bdb_row20_col20" class="data row20 col20">0.158000</td>
                      <td id="T_61bdb_row20_col21" class="data row20 col21">RHP</td>
                      <td id="T_61bdb_row20_col22" class="data row20 col22">AAA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row21_col0" class="data row21 col0">27</td>
                      <td id="T_61bdb_row21_col1" class="data row21 col1">Mia</td>
                      <td id="T_61bdb_row21_col2" class="data row21 col2">18</td>
                      <td id="T_61bdb_row21_col3" class="data row21 col3">Kahlil Watson</td>
                      <td id="T_61bdb_row21_col4" class="data row21 col4">33</td>
                      <td id="T_61bdb_row21_col5" class="data row21 col5">13</td>
                      <td id="T_61bdb_row21_col6" class="data row21 col6">13</td>
                      <td id="T_61bdb_row21_col7" class="data row21 col7">3</td>
                      <td id="T_61bdb_row21_col8" class="data row21 col8">2</td>
                      <td id="T_61bdb_row21_col9" class="data row21 col9">0</td>
                      <td id="T_61bdb_row21_col10" class="data row21 col10">0.524000</td>
                      <td id="T_61bdb_row21_col11" class="data row21 col11">1.130000</td>
                      <td id="T_61bdb_row21_col12" class="data row21 col12">0.606000</td>
                      <td id="T_61bdb_row21_col13" class="data row21 col13">5</td>
                      <td id="T_61bdb_row21_col14" class="data row21 col14">8</td>
                      <td id="T_61bdb_row21_col15" class="data row21 col15">7</td>
                      <td id="T_61bdb_row21_col16" class="data row21 col16">4</td>
                      <td id="T_61bdb_row21_col17" class="data row21 col17">1</td>
                      <td id="T_61bdb_row21_col18" class="data row21 col18">6</td>
                      <td id="T_61bdb_row21_col19" class="data row21 col19">20</td>
                      <td id="T_61bdb_row21_col20" class="data row21 col20">0.394000</td>
                      <td id="T_61bdb_row21_col21" class="data row21 col21">SS</td>
                      <td id="T_61bdb_row21_col22" class="data row21 col22">ROK</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row22_col0" class="data row22 col0">28</td>
                      <td id="T_61bdb_row22_col1" class="data row22 col1">LAA</td>
                      <td id="T_61bdb_row22_col2" class="data row22 col2">20</td>
                      <td id="T_61bdb_row22_col3" class="data row22 col3">Diego Cartaya</td>
                      <td id="T_61bdb_row22_col4" class="data row22 col4">114</td>
                      <td id="T_61bdb_row22_col5" class="data row22 col5">31</td>
                      <td id="T_61bdb_row22_col6" class="data row22 col6">34</td>
                      <td id="T_61bdb_row22_col7" class="data row22 col7">6</td>
                      <td id="T_61bdb_row22_col8" class="data row22 col8">0</td>
                      <td id="T_61bdb_row22_col9" class="data row22 col9">10</td>
                      <td id="T_61bdb_row22_col10" class="data row22 col10">0.409000</td>
                      <td id="T_61bdb_row22_col11" class="data row22 col11">1.023000</td>
                      <td id="T_61bdb_row22_col12" class="data row22 col12">0.614000</td>
                      <td id="T_61bdb_row22_col13" class="data row22 col13">31</td>
                      <td id="T_61bdb_row22_col14" class="data row22 col14">18</td>
                      <td id="T_61bdb_row22_col15" class="data row22 col15">37</td>
                      <td id="T_61bdb_row22_col16" class="data row22 col16">0</td>
                      <td id="T_61bdb_row22_col17" class="data row22 col17">0</td>
                      <td id="T_61bdb_row22_col18" class="data row22 col18">56</td>
                      <td id="T_61bdb_row22_col19" class="data row22 col19">70</td>
                      <td id="T_61bdb_row22_col20" class="data row22 col20">0.298000</td>
                      <td id="T_61bdb_row22_col21" class="data row22 col21">C</td>
                      <td id="T_61bdb_row22_col22" class="data row22 col22">A</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row23_col0" class="data row23 col0">32</td>
                      <td id="T_61bdb_row23_col1" class="data row23 col1">Tor</td>
                      <td id="T_61bdb_row23_col2" class="data row23 col2">21</td>
                      <td id="T_61bdb_row23_col3" class="data row23 col3">Gabriel Moreno</td>
                      <td id="T_61bdb_row23_col4" class="data row23 col4">139</td>
                      <td id="T_61bdb_row23_col5" class="data row23 col5">30</td>
                      <td id="T_61bdb_row23_col6" class="data row23 col6">51</td>
                      <td id="T_61bdb_row23_col7" class="data row23 col7">10</td>
                      <td id="T_61bdb_row23_col8" class="data row23 col8">1</td>
                      <td id="T_61bdb_row23_col9" class="data row23 col9">8</td>
                      <td id="T_61bdb_row23_col10" class="data row23 col10">0.434000</td>
                      <td id="T_61bdb_row23_col11" class="data row23 col11">1.060000</td>
                      <td id="T_61bdb_row23_col12" class="data row23 col12">0.626000</td>
                      <td id="T_61bdb_row23_col13" class="data row23 col13">45</td>
                      <td id="T_61bdb_row23_col14" class="data row23 col14">14</td>
                      <td id="T_61bdb_row23_col15" class="data row23 col15">25</td>
                      <td id="T_61bdb_row23_col16" class="data row23 col16">1</td>
                      <td id="T_61bdb_row23_col17" class="data row23 col17">2</td>
                      <td id="T_61bdb_row23_col18" class="data row23 col18">65</td>
                      <td id="T_61bdb_row23_col19" class="data row23 col19">87</td>
                      <td id="T_61bdb_row23_col20" class="data row23 col20">0.367000</td>
                      <td id="T_61bdb_row23_col21" class="data row23 col21">C</td>
                      <td id="T_61bdb_row23_col22" class="data row23 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row24_col0" class="data row24 col0">36</td>
                      <td id="T_61bdb_row24_col1" class="data row24 col1">Min</td>
                      <td id="T_61bdb_row24_col2" class="data row24 col2">22</td>
                      <td id="T_61bdb_row24_col3" class="data row24 col3">Austin Martin</td>
                      <td id="T_61bdb_row24_col4" class="data row24 col4">330</td>
                      <td id="T_61bdb_row24_col5" class="data row24 col5">67</td>
                      <td id="T_61bdb_row24_col6" class="data row24 col6">89</td>
                      <td id="T_61bdb_row24_col7" class="data row24 col7">18</td>
                      <td id="T_61bdb_row24_col8" class="data row24 col8">2</td>
                      <td id="T_61bdb_row24_col9" class="data row24 col9">5</td>
                      <td id="T_61bdb_row24_col10" class="data row24 col10">0.414000</td>
                      <td id="T_61bdb_row24_col11" class="data row24 col11">0.796000</td>
                      <td id="T_61bdb_row24_col12" class="data row24 col12">0.382000</td>
                      <td id="T_61bdb_row24_col13" class="data row24 col13">35</td>
                      <td id="T_61bdb_row24_col14" class="data row24 col14">60</td>
                      <td id="T_61bdb_row24_col15" class="data row24 col15">83</td>
                      <td id="T_61bdb_row24_col16" class="data row24 col16">14</td>
                      <td id="T_61bdb_row24_col17" class="data row24 col17">4</td>
                      <td id="T_61bdb_row24_col18" class="data row24 col18">116</td>
                      <td id="T_61bdb_row24_col19" class="data row24 col19">126</td>
                      <td id="T_61bdb_row24_col20" class="data row24 col20">0.270000</td>
                      <td id="T_61bdb_row24_col21" class="data row24 col21">CF</td>
                      <td id="T_61bdb_row24_col22" class="data row24 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row25_col0" class="data row25 col0">37</td>
                      <td id="T_61bdb_row25_col1" class="data row25 col1">SD</td>
                      <td id="T_61bdb_row25_col2" class="data row25 col2">23</td>
                      <td id="T_61bdb_row25_col3" class="data row25 col3">Luis Campusano</td>
                      <td id="T_61bdb_row25_col4" class="data row25 col4">326</td>
                      <td id="T_61bdb_row25_col5" class="data row25 col5">47</td>
                      <td id="T_61bdb_row25_col6" class="data row25 col6">89</td>
                      <td id="T_61bdb_row25_col7" class="data row25 col7">21</td>
                      <td id="T_61bdb_row25_col8" class="data row25 col8">3</td>
                      <td id="T_61bdb_row25_col9" class="data row25 col9">15</td>
                      <td id="T_61bdb_row25_col10" class="data row25 col10">0.346000</td>
                      <td id="T_61bdb_row25_col11" class="data row25 col11">0.840000</td>
                      <td id="T_61bdb_row25_col12" class="data row25 col12">0.494000</td>
                      <td id="T_61bdb_row25_col13" class="data row25 col13">46</td>
                      <td id="T_61bdb_row25_col14" class="data row25 col14">31</td>
                      <td id="T_61bdb_row25_col15" class="data row25 col15">77</td>
                      <td id="T_61bdb_row25_col16" class="data row25 col16">1</td>
                      <td id="T_61bdb_row25_col17" class="data row25 col17">0</td>
                      <td id="T_61bdb_row25_col18" class="data row25 col18">184</td>
                      <td id="T_61bdb_row25_col19" class="data row25 col19">161</td>
                      <td id="T_61bdb_row25_col20" class="data row25 col20">0.273000</td>
                      <td id="T_61bdb_row25_col21" class="data row25 col21">C</td>
                      <td id="T_61bdb_row25_col22" class="data row25 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row26_col0" class="data row26 col0">38</td>
                      <td id="T_61bdb_row26_col1" class="data row26 col1">Atl</td>
                      <td id="T_61bdb_row26_col2" class="data row26 col2">22</td>
                      <td id="T_61bdb_row26_col3" class="data row26 col3">Cristian Pache</td>
                      <td id="T_61bdb_row26_col4" class="data row26 col4">375</td>
                      <td id="T_61bdb_row26_col5" class="data row26 col5">56</td>
                      <td id="T_61bdb_row26_col6" class="data row26 col6">91</td>
                      <td id="T_61bdb_row26_col7" class="data row26 col7">18</td>
                      <td id="T_61bdb_row26_col8" class="data row26 col8">0</td>
                      <td id="T_61bdb_row26_col9" class="data row26 col9">12</td>
                      <td id="T_61bdb_row26_col10" class="data row26 col10">0.306000</td>
                      <td id="T_61bdb_row26_col11" class="data row26 col11">0.692000</td>
                      <td id="T_61bdb_row26_col12" class="data row26 col12">0.387000</td>
                      <td id="T_61bdb_row26_col13" class="data row26 col13">48</td>
                      <td id="T_61bdb_row26_col14" class="data row26 col14">32</td>
                      <td id="T_61bdb_row26_col15" class="data row26 col15">120</td>
                      <td id="T_61bdb_row26_col16" class="data row26 col16">9</td>
                      <td id="T_61bdb_row26_col17" class="data row26 col17">6</td>
                      <td id="T_61bdb_row26_col18" class="data row26 col18">134</td>
                      <td id="T_61bdb_row26_col19" class="data row26 col19">145</td>
                      <td id="T_61bdb_row26_col20" class="data row26 col20">0.243000</td>
                      <td id="T_61bdb_row26_col21" class="data row26 col21">CF</td>
                      <td id="T_61bdb_row26_col22" class="data row26 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row27_col0" class="data row27 col0">40</td>
                      <td id="T_61bdb_row27_col1" class="data row27 col1">Ari</td>
                      <td id="T_61bdb_row27_col2" class="data row27 col2">21</td>
                      <td id="T_61bdb_row27_col3" class="data row27 col3">Alek Thomas</td>
                      <td id="T_61bdb_row27_col4" class="data row27 col4">435</td>
                      <td id="T_61bdb_row27_col5" class="data row27 col5">86</td>
                      <td id="T_61bdb_row27_col6" class="data row27 col6">136</td>
                      <td id="T_61bdb_row27_col7" class="data row27 col7">29</td>
                      <td id="T_61bdb_row27_col8" class="data row27 col8">12</td>
                      <td id="T_61bdb_row27_col9" class="data row27 col9">18</td>
                      <td id="T_61bdb_row27_col10" class="data row27 col10">0.394000</td>
                      <td id="T_61bdb_row27_col11" class="data row27 col11">0.953000</td>
                      <td id="T_61bdb_row27_col12" class="data row27 col12">0.559000</td>
                      <td id="T_61bdb_row27_col13" class="data row27 col13">59</td>
                      <td id="T_61bdb_row27_col14" class="data row27 col14">52</td>
                      <td id="T_61bdb_row27_col15" class="data row27 col15">99</td>
                      <td id="T_61bdb_row27_col16" class="data row27 col16">13</td>
                      <td id="T_61bdb_row27_col17" class="data row27 col17">9</td>
                      <td id="T_61bdb_row27_col18" class="data row27 col18">122</td>
                      <td id="T_61bdb_row27_col19" class="data row27 col19">243</td>
                      <td id="T_61bdb_row27_col20" class="data row27 col20">0.313000</td>
                      <td id="T_61bdb_row27_col21" class="data row27 col21">CF</td>
                      <td id="T_61bdb_row27_col22" class="data row27 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row28_col0" class="data row28 col0">42</td>
                      <td id="T_61bdb_row28_col1" class="data row28 col1">Oak</td>
                      <td id="T_61bdb_row28_col2" class="data row28 col2">19</td>
                      <td id="T_61bdb_row28_col3" class="data row28 col3">Tyler Soderstrom</td>
                      <td id="T_61bdb_row28_col4" class="data row28 col4">222</td>
                      <td id="T_61bdb_row28_col5" class="data row28 col5">39</td>
                      <td id="T_61bdb_row28_col6" class="data row28 col6">68</td>
                      <td id="T_61bdb_row28_col7" class="data row28 col7">20</td>
                      <td id="T_61bdb_row28_col8" class="data row28 col8">1</td>
                      <td id="T_61bdb_row28_col9" class="data row28 col9">12</td>
                      <td id="T_61bdb_row28_col10" class="data row28 col10">0.390000</td>
                      <td id="T_61bdb_row28_col11" class="data row28 col11">0.957000</td>
                      <td id="T_61bdb_row28_col12" class="data row28 col12">0.568000</td>
                      <td id="T_61bdb_row28_col13" class="data row28 col13">49</td>
                      <td id="T_61bdb_row28_col14" class="data row28 col14">27</td>
                      <td id="T_61bdb_row28_col15" class="data row28 col15">61</td>
                      <td id="T_61bdb_row28_col16" class="data row28 col16">2</td>
                      <td id="T_61bdb_row28_col17" class="data row28 col17">1</td>
                      <td id="T_61bdb_row28_col18" class="data row28 col18">97</td>
                      <td id="T_61bdb_row28_col19" class="data row28 col19">126</td>
                      <td id="T_61bdb_row28_col20" class="data row28 col20">0.306000</td>
                      <td id="T_61bdb_row28_col21" class="data row28 col21">C</td>
                      <td id="T_61bdb_row28_col22" class="data row28 col22">A</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row29_col0" class="data row29 col0">43</td>
                      <td id="T_61bdb_row29_col1" class="data row29 col1">SD</td>
                      <td id="T_61bdb_row29_col2" class="data row29 col2">20</td>
                      <td id="T_61bdb_row29_col3" class="data row29 col3">Robert Hassell III</td>
                      <td id="T_61bdb_row29_col4" class="data row29 col4">443</td>
                      <td id="T_61bdb_row29_col5" class="data row29 col5">87</td>
                      <td id="T_61bdb_row29_col6" class="data row29 col6">134</td>
                      <td id="T_61bdb_row29_col7" class="data row29 col7">33</td>
                      <td id="T_61bdb_row29_col8" class="data row29 col8">4</td>
                      <td id="T_61bdb_row29_col9" class="data row29 col9">11</td>
                      <td id="T_61bdb_row29_col10" class="data row29 col10">0.393000</td>
                      <td id="T_61bdb_row29_col11" class="data row29 col11">0.863000</td>
                      <td id="T_61bdb_row29_col12" class="data row29 col12">0.470000</td>
                      <td id="T_61bdb_row29_col13" class="data row29 col13">76</td>
                      <td id="T_61bdb_row29_col14" class="data row29 col14">66</td>
                      <td id="T_61bdb_row29_col15" class="data row29 col15">99</td>
                      <td id="T_61bdb_row29_col16" class="data row29 col16">34</td>
                      <td id="T_61bdb_row29_col17" class="data row29 col17">6</td>
                      <td id="T_61bdb_row29_col18" class="data row29 col18">190</td>
                      <td id="T_61bdb_row29_col19" class="data row29 col19">208</td>
                      <td id="T_61bdb_row29_col20" class="data row29 col20">0.302000</td>
                      <td id="T_61bdb_row29_col21" class="data row29 col21">OF</td>
                      <td id="T_61bdb_row29_col22" class="data row29 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row30_col0" class="data row30 col0">44</td>
                      <td id="T_61bdb_row30_col1" class="data row30 col1">Tor</td>
                      <td id="T_61bdb_row30_col2" class="data row30 col2">19</td>
                      <td id="T_61bdb_row30_col3" class="data row30 col3">Orelvis Martinez</td>
                      <td id="T_61bdb_row30_col4" class="data row30 col4">395</td>
                      <td id="T_61bdb_row30_col5" class="data row30 col5">66</td>
                      <td id="T_61bdb_row30_col6" class="data row30 col6">103</td>
                      <td id="T_61bdb_row30_col7" class="data row30 col7">26</td>
                      <td id="T_61bdb_row30_col8" class="data row30 col8">2</td>
                      <td id="T_61bdb_row30_col9" class="data row30 col9">28</td>
                      <td id="T_61bdb_row30_col10" class="data row30 col10">0.345000</td>
                      <td id="T_61bdb_row30_col11" class="data row30 col11">0.895000</td>
                      <td id="T_61bdb_row30_col12" class="data row30 col12">0.549000</td>
                      <td id="T_61bdb_row30_col13" class="data row30 col13">87</td>
                      <td id="T_61bdb_row30_col14" class="data row30 col14">43</td>
                      <td id="T_61bdb_row30_col15" class="data row30 col15">113</td>
                      <td id="T_61bdb_row30_col16" class="data row30 col16">4</td>
                      <td id="T_61bdb_row30_col17" class="data row30 col17">2</td>
                      <td id="T_61bdb_row30_col18" class="data row30 col18">235</td>
                      <td id="T_61bdb_row30_col19" class="data row30 col19">217</td>
                      <td id="T_61bdb_row30_col20" class="data row30 col20">0.261000</td>
                      <td id="T_61bdb_row30_col21" class="data row30 col21">SS</td>
                      <td id="T_61bdb_row30_col22" class="data row30 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row31_col0" class="data row31 col0">45</td>
                      <td id="T_61bdb_row31_col1" class="data row31 col1">NYM</td>
                      <td id="T_61bdb_row31_col2" class="data row31 col2">21</td>
                      <td id="T_61bdb_row31_col3" class="data row31 col3">Brett Baty</td>
                      <td id="T_61bdb_row31_col4" class="data row31 col4">332</td>
                      <td id="T_61bdb_row31_col5" class="data row31 col5">43</td>
                      <td id="T_61bdb_row31_col6" class="data row31 col6">97</td>
                      <td id="T_61bdb_row31_col7" class="data row31 col7">22</td>
                      <td id="T_61bdb_row31_col8" class="data row31 col8">1</td>
                      <td id="T_61bdb_row31_col9" class="data row31 col9">12</td>
                      <td id="T_61bdb_row31_col10" class="data row31 col10">0.382000</td>
                      <td id="T_61bdb_row31_col11" class="data row31 col11">0.855000</td>
                      <td id="T_61bdb_row31_col12" class="data row31 col12">0.473000</td>
                      <td id="T_61bdb_row31_col13" class="data row31 col13">56</td>
                      <td id="T_61bdb_row31_col14" class="data row31 col14">46</td>
                      <td id="T_61bdb_row31_col15" class="data row31 col15">98</td>
                      <td id="T_61bdb_row31_col16" class="data row31 col16">6</td>
                      <td id="T_61bdb_row31_col17" class="data row31 col17">3</td>
                      <td id="T_61bdb_row31_col18" class="data row31 col18">140</td>
                      <td id="T_61bdb_row31_col19" class="data row31 col19">157</td>
                      <td id="T_61bdb_row31_col20" class="data row31 col20">0.292000</td>
                      <td id="T_61bdb_row31_col21" class="data row31 col21">3B</td>
                      <td id="T_61bdb_row31_col22" class="data row31 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row32_col0" class="data row32 col0">48</td>
                      <td id="T_61bdb_row32_col1" class="data row32 col1">Tex</td>
                      <td id="T_61bdb_row32_col2" class="data row32 col2">23</td>
                      <td id="T_61bdb_row32_col3" class="data row32 col3">Josh Jung</td>
                      <td id="T_61bdb_row32_col4" class="data row32 col4">299</td>
                      <td id="T_61bdb_row32_col5" class="data row32 col5">53</td>
                      <td id="T_61bdb_row32_col6" class="data row32 col6">96</td>
                      <td id="T_61bdb_row32_col7" class="data row32 col7">22</td>
                      <td id="T_61bdb_row32_col8" class="data row32 col8">1</td>
                      <td id="T_61bdb_row32_col9" class="data row32 col9">18</td>
                      <td id="T_61bdb_row32_col10" class="data row32 col10">0.389000</td>
                      <td id="T_61bdb_row32_col11" class="data row32 col11">0.971000</td>
                      <td id="T_61bdb_row32_col12" class="data row32 col12">0.582000</td>
                      <td id="T_61bdb_row32_col13" class="data row32 col13">60</td>
                      <td id="T_61bdb_row32_col14" class="data row32 col14">29</td>
                      <td id="T_61bdb_row32_col15" class="data row32 col15">74</td>
                      <td id="T_61bdb_row32_col16" class="data row32 col16">2</td>
                      <td id="T_61bdb_row32_col17" class="data row32 col17">2</td>
                      <td id="T_61bdb_row32_col18" class="data row32 col18">118</td>
                      <td id="T_61bdb_row32_col19" class="data row32 col19">174</td>
                      <td id="T_61bdb_row32_col20" class="data row32 col20">0.321000</td>
                      <td id="T_61bdb_row32_col21" class="data row32 col21">3B</td>
                      <td id="T_61bdb_row32_col22" class="data row32 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row33_col0" class="data row33 col0">50</td>
                      <td id="T_61bdb_row33_col1" class="data row33 col1">Col</td>
                      <td id="T_61bdb_row33_col2" class="data row33 col2">19</td>
                      <td id="T_61bdb_row33_col3" class="data row33 col3">Zac Veen</td>
                      <td id="T_61bdb_row33_col4" class="data row33 col4">399</td>
                      <td id="T_61bdb_row33_col5" class="data row33 col5">83</td>
                      <td id="T_61bdb_row33_col6" class="data row33 col6">120</td>
                      <td id="T_61bdb_row33_col7" class="data row33 col7">27</td>
                      <td id="T_61bdb_row33_col8" class="data row33 col8">4</td>
                      <td id="T_61bdb_row33_col9" class="data row33 col9">15</td>
                      <td id="T_61bdb_row33_col10" class="data row33 col10">0.399000</td>
                      <td id="T_61bdb_row33_col11" class="data row33 col11">0.900000</td>
                      <td id="T_61bdb_row33_col12" class="data row33 col12">0.501000</td>
                      <td id="T_61bdb_row33_col13" class="data row33 col13">75</td>
                      <td id="T_61bdb_row33_col14" class="data row33 col14">64</td>
                      <td id="T_61bdb_row33_col15" class="data row33 col15">126</td>
                      <td id="T_61bdb_row33_col16" class="data row33 col16">36</td>
                      <td id="T_61bdb_row33_col17" class="data row33 col17">17</td>
                      <td id="T_61bdb_row33_col18" class="data row33 col18">144</td>
                      <td id="T_61bdb_row33_col19" class="data row33 col19">200</td>
                      <td id="T_61bdb_row33_col20" class="data row33 col20">0.301000</td>
                      <td id="T_61bdb_row33_col21" class="data row33 col21">OF</td>
                      <td id="T_61bdb_row33_col22" class="data row33 col22">A</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row34_col0" class="data row34 col0">51</td>
                      <td id="T_61bdb_row34_col1" class="data row34 col1">Mil</td>
                      <td id="T_61bdb_row34_col2" class="data row34 col2">23</td>
                      <td id="T_61bdb_row34_col3" class="data row34 col3">Garrett Mitchell</td>
                      <td id="T_61bdb_row34_col4" class="data row34 col4">221</td>
                      <td id="T_61bdb_row34_col5" class="data row34 col5">49</td>
                      <td id="T_61bdb_row34_col6" class="data row34 col6">57</td>
                      <td id="T_61bdb_row34_col7" class="data row34 col7">6</td>
                      <td id="T_61bdb_row34_col8" class="data row34 col8">2</td>
                      <td id="T_61bdb_row34_col9" class="data row34 col9">8</td>
                      <td id="T_61bdb_row34_col10" class="data row34 col10">0.388000</td>
                      <td id="T_61bdb_row34_col11" class="data row34 col11">0.800000</td>
                      <td id="T_61bdb_row34_col12" class="data row34 col12">0.412000</td>
                      <td id="T_61bdb_row34_col13" class="data row34 col13">30</td>
                      <td id="T_61bdb_row34_col14" class="data row34 col14">46</td>
                      <td id="T_61bdb_row34_col15" class="data row34 col15">71</td>
                      <td id="T_61bdb_row34_col16" class="data row34 col16">17</td>
                      <td id="T_61bdb_row34_col17" class="data row34 col17">2</td>
                      <td id="T_61bdb_row34_col18" class="data row34 col18">97</td>
                      <td id="T_61bdb_row34_col19" class="data row34 col19">91</td>
                      <td id="T_61bdb_row34_col20" class="data row34 col20">0.258000</td>
                      <td id="T_61bdb_row34_col21" class="data row34 col21">OF</td>
                      <td id="T_61bdb_row34_col22" class="data row34 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row35_col0" class="data row35 col0">52</td>
                      <td id="T_61bdb_row35_col1" class="data row35 col1">Pit</td>
                      <td id="T_61bdb_row35_col2" class="data row35 col2">22</td>
                      <td id="T_61bdb_row35_col3" class="data row35 col3">Oneil Cruz</td>
                      <td id="T_61bdb_row35_col4" class="data row35 col4">271</td>
                      <td id="T_61bdb_row35_col5" class="data row35 col5">62</td>
                      <td id="T_61bdb_row35_col6" class="data row35 col6">84</td>
                      <td id="T_61bdb_row35_col7" class="data row35 col7">16</td>
                      <td id="T_61bdb_row35_col8" class="data row35 col8">5</td>
                      <td id="T_61bdb_row35_col9" class="data row35 col9">17</td>
                      <td id="T_61bdb_row35_col10" class="data row35 col10">0.375000</td>
                      <td id="T_61bdb_row35_col11" class="data row35 col11">0.970000</td>
                      <td id="T_61bdb_row35_col12" class="data row35 col12">0.594000</td>
                      <td id="T_61bdb_row35_col13" class="data row35 col13">47</td>
                      <td id="T_61bdb_row35_col14" class="data row35 col14">28</td>
                      <td id="T_61bdb_row35_col15" class="data row35 col15">69</td>
                      <td id="T_61bdb_row35_col16" class="data row35 col16">19</td>
                      <td id="T_61bdb_row35_col17" class="data row35 col17">3</td>
                      <td id="T_61bdb_row35_col18" class="data row35 col18">94</td>
                      <td id="T_61bdb_row35_col19" class="data row35 col19">161</td>
                      <td id="T_61bdb_row35_col20" class="data row35 col20">0.310000</td>
                      <td id="T_61bdb_row35_col21" class="data row35 col21">SS</td>
                      <td id="T_61bdb_row35_col22" class="data row35 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row36_col0" class="data row36 col0">53</td>
                      <td id="T_61bdb_row36_col1" class="data row36 col1">NYM</td>
                      <td id="T_61bdb_row36_col2" class="data row36 col2">20</td>
                      <td id="T_61bdb_row36_col3" class="data row36 col3">Ronny Mauricio</td>
                      <td id="T_61bdb_row36_col4" class="data row36 col4">423</td>
                      <td id="T_61bdb_row36_col5" class="data row36 col5">58</td>
                      <td id="T_61bdb_row36_col6" class="data row36 col6">105</td>
                      <td id="T_61bdb_row36_col7" class="data row36 col7">15</td>
                      <td id="T_61bdb_row36_col8" class="data row36 col8">5</td>
                      <td id="T_61bdb_row36_col9" class="data row36 col9">20</td>
                      <td id="T_61bdb_row36_col10" class="data row36 col10">0.296000</td>
                      <td id="T_61bdb_row36_col11" class="data row36 col11">0.745000</td>
                      <td id="T_61bdb_row36_col12" class="data row36 col12">0.449000</td>
                      <td id="T_61bdb_row36_col13" class="data row36 col13">64</td>
                      <td id="T_61bdb_row36_col14" class="data row36 col14">26</td>
                      <td id="T_61bdb_row36_col15" class="data row36 col15">112</td>
                      <td id="T_61bdb_row36_col16" class="data row36 col16">11</td>
                      <td id="T_61bdb_row36_col17" class="data row36 col17">7</td>
                      <td id="T_61bdb_row36_col18" class="data row36 col18">177</td>
                      <td id="T_61bdb_row36_col19" class="data row36 col19">190</td>
                      <td id="T_61bdb_row36_col20" class="data row36 col20">0.248000</td>
                      <td id="T_61bdb_row36_col21" class="data row36 col21">SS</td>
                      <td id="T_61bdb_row36_col22" class="data row36 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row37_col0" class="data row37 col0">54</td>
                      <td id="T_61bdb_row37_col1" class="data row37 col1">Was</td>
                      <td id="T_61bdb_row37_col2" class="data row37 col2">18</td>
                      <td id="T_61bdb_row37_col3" class="data row37 col3">Brady House</td>
                      <td id="T_61bdb_row37_col4" class="data row37 col4">59</td>
                      <td id="T_61bdb_row37_col5" class="data row37 col5">14</td>
                      <td id="T_61bdb_row37_col6" class="data row37 col6">19</td>
                      <td id="T_61bdb_row37_col7" class="data row37 col7">3</td>
                      <td id="T_61bdb_row37_col8" class="data row37 col8">0</td>
                      <td id="T_61bdb_row37_col9" class="data row37 col9">4</td>
                      <td id="T_61bdb_row37_col10" class="data row37 col10">0.394000</td>
                      <td id="T_61bdb_row37_col11" class="data row37 col11">0.970000</td>
                      <td id="T_61bdb_row37_col12" class="data row37 col12">0.576000</td>
                      <td id="T_61bdb_row37_col13" class="data row37 col13">12</td>
                      <td id="T_61bdb_row37_col14" class="data row37 col14">7</td>
                      <td id="T_61bdb_row37_col15" class="data row37 col15">13</td>
                      <td id="T_61bdb_row37_col16" class="data row37 col16">0</td>
                      <td id="T_61bdb_row37_col17" class="data row37 col17">0</td>
                      <td id="T_61bdb_row37_col18" class="data row37 col18">32</td>
                      <td id="T_61bdb_row37_col19" class="data row37 col19">34</td>
                      <td id="T_61bdb_row37_col20" class="data row37 col20">0.322000</td>
                      <td id="T_61bdb_row37_col21" class="data row37 col21">SS</td>
                      <td id="T_61bdb_row37_col22" class="data row37 col22">ROK</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row38_col0" class="data row38 col0">55</td>
                      <td id="T_61bdb_row38_col1" class="data row38 col1">Tor</td>
                      <td id="T_61bdb_row38_col2" class="data row38 col2">21</td>
                      <td id="T_61bdb_row38_col3" class="data row38 col3">Jordan Groshans</td>
                      <td id="T_61bdb_row38_col4" class="data row38 col4">278</td>
                      <td id="T_61bdb_row38_col5" class="data row38 col5">46</td>
                      <td id="T_61bdb_row38_col6" class="data row38 col6">81</td>
                      <td id="T_61bdb_row38_col7" class="data row38 col7">23</td>
                      <td id="T_61bdb_row38_col8" class="data row38 col8">0</td>
                      <td id="T_61bdb_row38_col9" class="data row38 col9">7</td>
                      <td id="T_61bdb_row38_col10" class="data row38 col10">0.367000</td>
                      <td id="T_61bdb_row38_col11" class="data row38 col11">0.817000</td>
                      <td id="T_61bdb_row38_col12" class="data row38 col12">0.450000</td>
                      <td id="T_61bdb_row38_col13" class="data row38 col13">40</td>
                      <td id="T_61bdb_row38_col14" class="data row38 col14">34</td>
                      <td id="T_61bdb_row38_col15" class="data row38 col15">61</td>
                      <td id="T_61bdb_row38_col16" class="data row38 col16">0</td>
                      <td id="T_61bdb_row38_col17" class="data row38 col17">0</td>
                      <td id="T_61bdb_row38_col18" class="data row38 col18">142</td>
                      <td id="T_61bdb_row38_col19" class="data row38 col19">125</td>
                      <td id="T_61bdb_row38_col20" class="data row38 col20">0.291000</td>
                      <td id="T_61bdb_row38_col21" class="data row38 col21">SS</td>
                      <td id="T_61bdb_row38_col22" class="data row38 col22">AA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row39_col0" class="data row39 col0">57</td>
                      <td id="T_61bdb_row39_col1" class="data row39 col1">STL</td>
                      <td id="T_61bdb_row39_col2" class="data row39 col2">19</td>
                      <td id="T_61bdb_row39_col3" class="data row39 col3">Jordan Walker</td>
                      <td id="T_61bdb_row39_col4" class="data row39 col4">325</td>
                      <td id="T_61bdb_row39_col5" class="data row39 col5">63</td>
                      <td id="T_61bdb_row39_col6" class="data row39 col6">103</td>
                      <td id="T_61bdb_row39_col7" class="data row39 col7">25</td>
                      <td id="T_61bdb_row39_col8" class="data row39 col8">4</td>
                      <td id="T_61bdb_row39_col9" class="data row39 col9">14</td>
                      <td id="T_61bdb_row39_col10" class="data row39 col10">0.388000</td>
                      <td id="T_61bdb_row39_col11" class="data row39 col11">0.936000</td>
                      <td id="T_61bdb_row39_col12" class="data row39 col12">0.548000</td>
                      <td id="T_61bdb_row39_col13" class="data row39 col13">48</td>
                      <td id="T_61bdb_row39_col14" class="data row39 col14">33</td>
                      <td id="T_61bdb_row39_col15" class="data row39 col15">87</td>
                      <td id="T_61bdb_row39_col16" class="data row39 col16">14</td>
                      <td id="T_61bdb_row39_col17" class="data row39 col17">2</td>
                      <td id="T_61bdb_row39_col18" class="data row39 col18">128</td>
                      <td id="T_61bdb_row39_col19" class="data row39 col19">178</td>
                      <td id="T_61bdb_row39_col20" class="data row39 col20">0.317000</td>
                      <td id="T_61bdb_row39_col21" class="data row39 col21">3B</td>
                      <td id="T_61bdb_row39_col22" class="data row39 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row40_col0" class="data row40 col0">58</td>
                      <td id="T_61bdb_row40_col1" class="data row40 col1">NYY</td>
                      <td id="T_61bdb_row40_col2" class="data row40 col2">21</td>
                      <td id="T_61bdb_row40_col3" class="data row40 col3">Oswald Peraza</td>
                      <td id="T_61bdb_row40_col4" class="data row40 col4">454</td>
                      <td id="T_61bdb_row40_col5" class="data row40 col5">74</td>
                      <td id="T_61bdb_row40_col6" class="data row40 col6">133</td>
                      <td id="T_61bdb_row40_col7" class="data row40 col7">26</td>
                      <td id="T_61bdb_row40_col8" class="data row40 col8">2</td>
                      <td id="T_61bdb_row40_col9" class="data row40 col9">18</td>
                      <td id="T_61bdb_row40_col10" class="data row40 col10">0.355000</td>
                      <td id="T_61bdb_row40_col11" class="data row40 col11">0.833000</td>
                      <td id="T_61bdb_row40_col12" class="data row40 col12">0.478000</td>
                      <td id="T_61bdb_row40_col13" class="data row40 col13">57</td>
                      <td id="T_61bdb_row40_col14" class="data row40 col14">37</td>
                      <td id="T_61bdb_row40_col15" class="data row40 col15">110</td>
                      <td id="T_61bdb_row40_col16" class="data row40 col16">37</td>
                      <td id="T_61bdb_row40_col17" class="data row40 col17">10</td>
                      <td id="T_61bdb_row40_col18" class="data row40 col18">167</td>
                      <td id="T_61bdb_row40_col19" class="data row40 col19">217</td>
                      <td id="T_61bdb_row40_col20" class="data row40 col20">0.293000</td>
                      <td id="T_61bdb_row40_col21" class="data row40 col21">SS</td>
                      <td id="T_61bdb_row40_col22" class="data row40 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row41_col0" class="data row41 col0">59</td>
                      <td id="T_61bdb_row41_col1" class="data row41 col1">Cle</td>
                      <td id="T_61bdb_row41_col2" class="data row41 col2">22</td>
                      <td id="T_61bdb_row41_col3" class="data row41 col3">Tyler Freeman</td>
                      <td id="T_61bdb_row41_col4" class="data row41 col4">164</td>
                      <td id="T_61bdb_row41_col5" class="data row41 col5">26</td>
                      <td id="T_61bdb_row41_col6" class="data row41 col6">53</td>
                      <td id="T_61bdb_row41_col7" class="data row41 col7">14</td>
                      <td id="T_61bdb_row41_col8" class="data row41 col8">2</td>
                      <td id="T_61bdb_row41_col9" class="data row41 col9">2</td>
                      <td id="T_61bdb_row41_col10" class="data row41 col10">0.372000</td>
                      <td id="T_61bdb_row41_col11" class="data row41 col11">0.842000</td>
                      <td id="T_61bdb_row41_col12" class="data row41 col12">0.470000</td>
                      <td id="T_61bdb_row41_col13" class="data row41 col13">19</td>
                      <td id="T_61bdb_row41_col14" class="data row41 col14">8</td>
                      <td id="T_61bdb_row41_col15" class="data row41 col15">21</td>
                      <td id="T_61bdb_row41_col16" class="data row41 col16">4</td>
                      <td id="T_61bdb_row41_col17" class="data row41 col17">2</td>
                      <td id="T_61bdb_row41_col18" class="data row41 col18">41</td>
                      <td id="T_61bdb_row41_col19" class="data row41 col19">77</td>
                      <td id="T_61bdb_row41_col20" class="data row41 col20">0.323000</td>
                      <td id="T_61bdb_row41_col21" class="data row41 col21">SS</td>
                      <td id="T_61bdb_row41_col22" class="data row41 col22">AA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row42_col0" class="data row42 col0">62</td>
                      <td id="T_61bdb_row42_col1" class="data row42 col1">Pit</td>
                      <td id="T_61bdb_row42_col2" class="data row42 col2">22</td>
                      <td id="T_61bdb_row42_col3" class="data row42 col3">Nick Gonzales</td>
                      <td id="T_61bdb_row42_col4" class="data row42 col4">324</td>
                      <td id="T_61bdb_row42_col5" class="data row42 col5">53</td>
                      <td id="T_61bdb_row42_col6" class="data row42 col6">98</td>
                      <td id="T_61bdb_row42_col7" class="data row42 col7">23</td>
                      <td id="T_61bdb_row42_col8" class="data row42 col8">4</td>
                      <td id="T_61bdb_row42_col9" class="data row42 col9">18</td>
                      <td id="T_61bdb_row42_col10" class="data row42 col10">0.385000</td>
                      <td id="T_61bdb_row42_col11" class="data row42 col11">0.950000</td>
                      <td id="T_61bdb_row42_col12" class="data row42 col12">0.565000</td>
                      <td id="T_61bdb_row42_col13" class="data row42 col13">54</td>
                      <td id="T_61bdb_row42_col14" class="data row42 col14">40</td>
                      <td id="T_61bdb_row42_col15" class="data row42 col15">101</td>
                      <td id="T_61bdb_row42_col16" class="data row42 col16">7</td>
                      <td id="T_61bdb_row42_col17" class="data row42 col17">2</td>
                      <td id="T_61bdb_row42_col18" class="data row42 col18">120</td>
                      <td id="T_61bdb_row42_col19" class="data row42 col19">183</td>
                      <td id="T_61bdb_row42_col20" class="data row42 col20">0.302000</td>
                      <td id="T_61bdb_row42_col21" class="data row42 col21">SS</td>
                      <td id="T_61bdb_row42_col22" class="data row42 col22">A+</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row43_col0" class="data row43 col0">63</td>
                      <td id="T_61bdb_row43_col1" class="data row43 col1">Cle</td>
                      <td id="T_61bdb_row43_col2" class="data row43 col2">20</td>
                      <td id="T_61bdb_row43_col3" class="data row43 col3">George Valera</td>
                      <td id="T_61bdb_row43_col4" class="data row43 col4">285</td>
                      <td id="T_61bdb_row43_col5" class="data row43 col5">51</td>
                      <td id="T_61bdb_row43_col6" class="data row43 col6">74</td>
                      <td id="T_61bdb_row43_col7" class="data row43 col7">5</td>
                      <td id="T_61bdb_row43_col8" class="data row43 col8">4</td>
                      <td id="T_61bdb_row43_col9" class="data row43 col9">19</td>
                      <td id="T_61bdb_row43_col10" class="data row43 col10">0.405000</td>
                      <td id="T_61bdb_row43_col11" class="data row43 col11">0.910000</td>
                      <td id="T_61bdb_row43_col12" class="data row43 col12">0.505000</td>
                      <td id="T_61bdb_row43_col13" class="data row43 col13">65</td>
                      <td id="T_61bdb_row43_col14" class="data row43 col14">66</td>
                      <td id="T_61bdb_row43_col15" class="data row43 col15">88</td>
                      <td id="T_61bdb_row43_col16" class="data row43 col16">11</td>
                      <td id="T_61bdb_row43_col17" class="data row43 col17">5</td>
                      <td id="T_61bdb_row43_col18" class="data row43 col18">140</td>
                      <td id="T_61bdb_row43_col19" class="data row43 col19">144</td>
                      <td id="T_61bdb_row43_col20" class="data row43 col20">0.260000</td>
                      <td id="T_61bdb_row43_col21" class="data row43 col21">OF</td>
                      <td id="T_61bdb_row43_col22" class="data row43 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row44_col0" class="data row44 col0">65</td>
                      <td id="T_61bdb_row44_col1" class="data row44 col1">Kan</td>
                      <td id="T_61bdb_row44_col2" class="data row44 col2">22</td>
                      <td id="T_61bdb_row44_col3" class="data row44 col3">Nick Pratto</td>
                      <td id="T_61bdb_row44_col4" class="data row44 col4">435</td>
                      <td id="T_61bdb_row44_col5" class="data row44 col5">92</td>
                      <td id="T_61bdb_row44_col6" class="data row44 col6">114</td>
                      <td id="T_61bdb_row44_col7" class="data row44 col7">27</td>
                      <td id="T_61bdb_row44_col8" class="data row44 col8">7</td>
                      <td id="T_61bdb_row44_col9" class="data row44 col9">34</td>
                      <td id="T_61bdb_row44_col10" class="data row44 col10">0.380000</td>
                      <td id="T_61bdb_row44_col11" class="data row44 col11">0.971000</td>
                      <td id="T_61bdb_row44_col12" class="data row44 col12">0.591000</td>
                      <td id="T_61bdb_row44_col13" class="data row44 col13">93</td>
                      <td id="T_61bdb_row44_col14" class="data row44 col14">79</td>
                      <td id="T_61bdb_row44_col15" class="data row44 col15">152</td>
                      <td id="T_61bdb_row44_col16" class="data row44 col16">11</td>
                      <td id="T_61bdb_row44_col17" class="data row44 col17">5</td>
                      <td id="T_61bdb_row44_col18" class="data row44 col18">197</td>
                      <td id="T_61bdb_row44_col19" class="data row44 col19">257</td>
                      <td id="T_61bdb_row44_col20" class="data row44 col20">0.262000</td>
                      <td id="T_61bdb_row44_col21" class="data row44 col21">1B</td>
                      <td id="T_61bdb_row44_col22" class="data row44 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row45_col0" class="data row45 col0">67</td>
                      <td id="T_61bdb_row45_col1" class="data row45 col1">Kan</td>
                      <td id="T_61bdb_row45_col2" class="data row45 col2">22</td>
                      <td id="T_61bdb_row45_col3" class="data row45 col3">MJ Melendez</td>
                      <td id="T_61bdb_row45_col4" class="data row45 col4">434</td>
                      <td id="T_61bdb_row45_col5" class="data row45 col5">90</td>
                      <td id="T_61bdb_row45_col6" class="data row45 col6">125</td>
                      <td id="T_61bdb_row45_col7" class="data row45 col7">21</td>
                      <td id="T_61bdb_row45_col8" class="data row45 col8">3</td>
                      <td id="T_61bdb_row45_col9" class="data row45 col9">41</td>
                      <td id="T_61bdb_row45_col10" class="data row45 col10">0.386000</td>
                      <td id="T_61bdb_row45_col11" class="data row45 col11">1.020000</td>
                      <td id="T_61bdb_row45_col12" class="data row45 col12">0.634000</td>
                      <td id="T_61bdb_row45_col13" class="data row45 col13">99</td>
                      <td id="T_61bdb_row45_col14" class="data row45 col14">73</td>
                      <td id="T_61bdb_row45_col15" class="data row45 col15">111</td>
                      <td id="T_61bdb_row45_col16" class="data row45 col16">3</td>
                      <td id="T_61bdb_row45_col17" class="data row45 col17">6</td>
                      <td id="T_61bdb_row45_col18" class="data row45 col18">199</td>
                      <td id="T_61bdb_row45_col19" class="data row45 col19">275</td>
                      <td id="T_61bdb_row45_col20" class="data row45 col20">0.288000</td>
                      <td id="T_61bdb_row45_col21" class="data row45 col21">C</td>
                      <td id="T_61bdb_row45_col22" class="data row45 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row46_col0" class="data row46 col0">68</td>
                      <td id="T_61bdb_row46_col1" class="data row46 col1">Cle</td>
                      <td id="T_61bdb_row46_col2" class="data row46 col2">23</td>
                      <td id="T_61bdb_row46_col3" class="data row46 col3">Nolan Jones</td>
                      <td id="T_61bdb_row46_col4" class="data row46 col4">341</td>
                      <td id="T_61bdb_row46_col5" class="data row46 col5">60</td>
                      <td id="T_61bdb_row46_col6" class="data row46 col6">81</td>
                      <td id="T_61bdb_row46_col7" class="data row46 col7">25</td>
                      <td id="T_61bdb_row46_col8" class="data row46 col8">1</td>
                      <td id="T_61bdb_row46_col9" class="data row46 col9">13</td>
                      <td id="T_61bdb_row46_col10" class="data row46 col10">0.356000</td>
                      <td id="T_61bdb_row46_col11" class="data row46 col11">0.787000</td>
                      <td id="T_61bdb_row46_col12" class="data row46 col12">0.431000</td>
                      <td id="T_61bdb_row46_col13" class="data row46 col13">48</td>
                      <td id="T_61bdb_row46_col14" class="data row46 col14">59</td>
                      <td id="T_61bdb_row46_col15" class="data row46 col15">122</td>
                      <td id="T_61bdb_row46_col16" class="data row46 col16">10</td>
                      <td id="T_61bdb_row46_col17" class="data row46 col17">2</td>
                      <td id="T_61bdb_row46_col18" class="data row46 col18">172</td>
                      <td id="T_61bdb_row46_col19" class="data row46 col19">147</td>
                      <td id="T_61bdb_row46_col20" class="data row46 col20">0.238000</td>
                      <td id="T_61bdb_row46_col21" class="data row46 col21">3B</td>
                      <td id="T_61bdb_row46_col22" class="data row46 col22">AAA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row47_col0" class="data row47 col0">69</td>
                      <td id="T_61bdb_row47_col1" class="data row47 col1">Atl</td>
                      <td id="T_61bdb_row47_col2" class="data row47 col2">23</td>
                      <td id="T_61bdb_row47_col3" class="data row47 col3">Shea Langeliers</td>
                      <td id="T_61bdb_row47_col4" class="data row47 col4">332</td>
                      <td id="T_61bdb_row47_col5" class="data row47 col5">57</td>
                      <td id="T_61bdb_row47_col6" class="data row47 col6">85</td>
                      <td id="T_61bdb_row47_col7" class="data row47 col7">13</td>
                      <td id="T_61bdb_row47_col8" class="data row47 col8">0</td>
                      <td id="T_61bdb_row47_col9" class="data row47 col9">22</td>
                      <td id="T_61bdb_row47_col10" class="data row47 col10">0.339000</td>
                      <td id="T_61bdb_row47_col11" class="data row47 col11">0.833000</td>
                      <td id="T_61bdb_row47_col12" class="data row47 col12">0.494000</td>
                      <td id="T_61bdb_row47_col13" class="data row47 col13">52</td>
                      <td id="T_61bdb_row47_col14" class="data row47 col14">38</td>
                      <td id="T_61bdb_row47_col15" class="data row47 col15">99</td>
                      <td id="T_61bdb_row47_col16" class="data row47 col16">1</td>
                      <td id="T_61bdb_row47_col17" class="data row47 col17">0</td>
                      <td id="T_61bdb_row47_col18" class="data row47 col18">133</td>
                      <td id="T_61bdb_row47_col19" class="data row47 col19">164</td>
                      <td id="T_61bdb_row47_col20" class="data row47 col20">0.256000</td>
                      <td id="T_61bdb_row47_col21" class="data row47 col21">C</td>
                      <td id="T_61bdb_row47_col22" class="data row47 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row48_col0" class="data row48 col0">70</td>
                      <td id="T_61bdb_row48_col1" class="data row48 col1">Tam</td>
                      <td id="T_61bdb_row48_col2" class="data row48 col2">22</td>
                      <td id="T_61bdb_row48_col3" class="data row48 col3">Xavier Edwards</td>
                      <td id="T_61bdb_row48_col4" class="data row48 col4">291</td>
                      <td id="T_61bdb_row48_col5" class="data row48 col5">40</td>
                      <td id="T_61bdb_row48_col6" class="data row48 col6">88</td>
                      <td id="T_61bdb_row48_col7" class="data row48 col7">13</td>
                      <td id="T_61bdb_row48_col8" class="data row48 col8">3</td>
                      <td id="T_61bdb_row48_col9" class="data row48 col9">0</td>
                      <td id="T_61bdb_row48_col10" class="data row48 col10">0.377000</td>
                      <td id="T_61bdb_row48_col11" class="data row48 col11">0.744000</td>
                      <td id="T_61bdb_row48_col12" class="data row48 col12">0.368000</td>
                      <td id="T_61bdb_row48_col13" class="data row48 col13">27</td>
                      <td id="T_61bdb_row48_col14" class="data row48 col14">36</td>
                      <td id="T_61bdb_row48_col15" class="data row48 col15">42</td>
                      <td id="T_61bdb_row48_col16" class="data row48 col16">19</td>
                      <td id="T_61bdb_row48_col17" class="data row48 col17">11</td>
                      <td id="T_61bdb_row48_col18" class="data row48 col18">85</td>
                      <td id="T_61bdb_row48_col19" class="data row48 col19">107</td>
                      <td id="T_61bdb_row48_col20" class="data row48 col20">0.302000</td>
                      <td id="T_61bdb_row48_col21" class="data row48 col21">SS</td>
                      <td id="T_61bdb_row48_col22" class="data row48 col22">AA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row49_col0" class="data row49 col0">71</td>
                      <td id="T_61bdb_row49_col1" class="data row49 col1">Mia</td>
                      <td id="T_61bdb_row49_col2" class="data row49 col2">23</td>
                      <td id="T_61bdb_row49_col3" class="data row49 col3">JJ Bleday</td>
                      <td id="T_61bdb_row49_col4" class="data row49 col4">397</td>
                      <td id="T_61bdb_row49_col5" class="data row49 col5">52</td>
                      <td id="T_61bdb_row49_col6" class="data row49 col6">84</td>
                      <td id="T_61bdb_row49_col7" class="data row49 col7">22</td>
                      <td id="T_61bdb_row49_col8" class="data row49 col8">3</td>
                      <td id="T_61bdb_row49_col9" class="data row49 col9">12</td>
                      <td id="T_61bdb_row49_col10" class="data row49 col10">0.323000</td>
                      <td id="T_61bdb_row49_col11" class="data row49 col11">0.695000</td>
                      <td id="T_61bdb_row49_col12" class="data row49 col12">0.373000</td>
                      <td id="T_61bdb_row49_col13" class="data row49 col13">54</td>
                      <td id="T_61bdb_row49_col14" class="data row49 col14">64</td>
                      <td id="T_61bdb_row49_col15" class="data row49 col15">101</td>
                      <td id="T_61bdb_row49_col16" class="data row49 col16">5</td>
                      <td id="T_61bdb_row49_col17" class="data row49 col17">3</td>
                      <td id="T_61bdb_row49_col18" class="data row49 col18">182</td>
                      <td id="T_61bdb_row49_col19" class="data row49 col19">148</td>
                      <td id="T_61bdb_row49_col20" class="data row49 col20">0.212000</td>
                      <td id="T_61bdb_row49_col21" class="data row49 col21">OF</td>
                      <td id="T_61bdb_row49_col22" class="data row49 col22">AA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row50_col0" class="data row50 col0">73</td>
                      <td id="T_61bdb_row50_col1" class="data row50 col1">Tam</td>
                      <td id="T_61bdb_row50_col2" class="data row50 col2">23</td>
                      <td id="T_61bdb_row50_col3" class="data row50 col3">Josh Lowe</td>
                      <td id="T_61bdb_row50_col4" class="data row50 col4">394</td>
                      <td id="T_61bdb_row50_col5" class="data row50 col5">75</td>
                      <td id="T_61bdb_row50_col6" class="data row50 col6">115</td>
                      <td id="T_61bdb_row50_col7" class="data row50 col7">28</td>
                      <td id="T_61bdb_row50_col8" class="data row50 col8">2</td>
                      <td id="T_61bdb_row50_col9" class="data row50 col9">21</td>
                      <td id="T_61bdb_row50_col10" class="data row50 col10">0.384000</td>
                      <td id="T_61bdb_row50_col11" class="data row50 col11">0.917000</td>
                      <td id="T_61bdb_row50_col12" class="data row50 col12">0.533000</td>
                      <td id="T_61bdb_row50_col13" class="data row50 col13">76</td>
                      <td id="T_61bdb_row50_col14" class="data row50 col14">62</td>
                      <td id="T_61bdb_row50_col15" class="data row50 col15">120</td>
                      <td id="T_61bdb_row50_col16" class="data row50 col16">27</td>
                      <td id="T_61bdb_row50_col17" class="data row50 col17">0</td>
                      <td id="T_61bdb_row50_col18" class="data row50 col18">182</td>
                      <td id="T_61bdb_row50_col19" class="data row50 col19">210</td>
                      <td id="T_61bdb_row50_col20" class="data row50 col20">0.292000</td>
                      <td id="T_61bdb_row50_col21" class="data row50 col21">CF</td>
                      <td id="T_61bdb_row50_col22" class="data row50 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row51_col0" class="data row51 col0">74</td>
                      <td id="T_61bdb_row51_col1" class="data row51 col1">Bal</td>
                      <td id="T_61bdb_row51_col2" class="data row51 col2">20</td>
                      <td id="T_61bdb_row51_col3" class="data row51 col3">Gunnar Henderson</td>
                      <td id="T_61bdb_row51_col4" class="data row51 col4">399</td>
                      <td id="T_61bdb_row51_col5" class="data row51 col5">68</td>
                      <td id="T_61bdb_row51_col6" class="data row51 col6">103</td>
                      <td id="T_61bdb_row51_col7" class="data row51 col7">28</td>
                      <td id="T_61bdb_row51_col8" class="data row51 col8">4</td>
                      <td id="T_61bdb_row51_col9" class="data row51 col9">17</td>
                      <td id="T_61bdb_row51_col10" class="data row51 col10">0.350000</td>
                      <td id="T_61bdb_row51_col11" class="data row51 col11">0.826000</td>
                      <td id="T_61bdb_row51_col12" class="data row51 col12">0.476000</td>
                      <td id="T_61bdb_row51_col13" class="data row51 col13">74</td>
                      <td id="T_61bdb_row51_col14" class="data row51 col14">56</td>
                      <td id="T_61bdb_row51_col15" class="data row51 col15">143</td>
                      <td id="T_61bdb_row51_col16" class="data row51 col16">16</td>
                      <td id="T_61bdb_row51_col17" class="data row51 col17">2</td>
                      <td id="T_61bdb_row51_col18" class="data row51 col18">213</td>
                      <td id="T_61bdb_row51_col19" class="data row51 col19">190</td>
                      <td id="T_61bdb_row51_col20" class="data row51 col20">0.258000</td>
                      <td id="T_61bdb_row51_col21" class="data row51 col21">SS</td>
                      <td id="T_61bdb_row51_col22" class="data row51 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row52_col0" class="data row52 col0">75</td>
                      <td id="T_61bdb_row52_col1" class="data row52 col1">LAD</td>
                      <td id="T_61bdb_row52_col2" class="data row52 col2">23</td>
                      <td id="T_61bdb_row52_col3" class="data row52 col3">Michael Busch</td>
                      <td id="T_61bdb_row52_col4" class="data row52 col4">409</td>
                      <td id="T_61bdb_row52_col5" class="data row52 col5">84</td>
                      <td id="T_61bdb_row52_col6" class="data row52 col6">109</td>
                      <td id="T_61bdb_row52_col7" class="data row52 col7">27</td>
                      <td id="T_61bdb_row52_col8" class="data row52 col8">1</td>
                      <td id="T_61bdb_row52_col9" class="data row52 col9">20</td>
                      <td id="T_61bdb_row52_col10" class="data row52 col10">0.386000</td>
                      <td id="T_61bdb_row52_col11" class="data row52 col11">0.870000</td>
                      <td id="T_61bdb_row52_col12" class="data row52 col12">0.484000</td>
                      <td id="T_61bdb_row52_col13" class="data row52 col13">67</td>
                      <td id="T_61bdb_row52_col14" class="data row52 col14">70</td>
                      <td id="T_61bdb_row52_col15" class="data row52 col15">129</td>
                      <td id="T_61bdb_row52_col16" class="data row52 col16">2</td>
                      <td id="T_61bdb_row52_col17" class="data row52 col17">3</td>
                      <td id="T_61bdb_row52_col18" class="data row52 col18">161</td>
                      <td id="T_61bdb_row52_col19" class="data row52 col19">198</td>
                      <td id="T_61bdb_row52_col20" class="data row52 col20">0.267000</td>
                      <td id="T_61bdb_row52_col21" class="data row52 col21">2B</td>
                      <td id="T_61bdb_row52_col22" class="data row52 col22">AA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row53_col0" class="data row53 col0">76</td>
                      <td id="T_61bdb_row53_col1" class="data row53 col1">Bal</td>
                      <td id="T_61bdb_row53_col2" class="data row53 col2">21</td>
                      <td id="T_61bdb_row53_col3" class="data row53 col3">Colton Cowser</td>
                      <td id="T_61bdb_row53_col4" class="data row53 col4">120</td>
                      <td id="T_61bdb_row53_col5" class="data row53 col5">30</td>
                      <td id="T_61bdb_row53_col6" class="data row53 col6">45</td>
                      <td id="T_61bdb_row53_col7" class="data row53 col7">8</td>
                      <td id="T_61bdb_row53_col8" class="data row53 col8">0</td>
                      <td id="T_61bdb_row53_col9" class="data row53 col9">2</td>
                      <td id="T_61bdb_row53_col10" class="data row53 col10">0.490000</td>
                      <td id="T_61bdb_row53_col11" class="data row53 col11">0.982000</td>
                      <td id="T_61bdb_row53_col12" class="data row53 col12">0.492000</td>
                      <td id="T_61bdb_row53_col13" class="data row53 col13">34</td>
                      <td id="T_61bdb_row53_col14" class="data row53 col14">25</td>
                      <td id="T_61bdb_row53_col15" class="data row53 col15">23</td>
                      <td id="T_61bdb_row53_col16" class="data row53 col16">7</td>
                      <td id="T_61bdb_row53_col17" class="data row53 col17">4</td>
                      <td id="T_61bdb_row53_col18" class="data row53 col18">61</td>
                      <td id="T_61bdb_row53_col19" class="data row53 col19">59</td>
                      <td id="T_61bdb_row53_col20" class="data row53 col20">0.375000</td>
                      <td id="T_61bdb_row53_col21" class="data row53 col21">OF</td>
                      <td id="T_61bdb_row53_col22" class="data row53 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row54_col0" class="data row54 col0">77</td>
                      <td id="T_61bdb_row54_col1" class="data row54 col1">San</td>
                      <td id="T_61bdb_row54_col2" class="data row54 col2">19</td>
                      <td id="T_61bdb_row54_col3" class="data row54 col3">Luis Matos</td>
                      <td id="T_61bdb_row54_col4" class="data row54 col4">451</td>
                      <td id="T_61bdb_row54_col5" class="data row54 col5">84</td>
                      <td id="T_61bdb_row54_col6" class="data row54 col6">141</td>
                      <td id="T_61bdb_row54_col7" class="data row54 col7">35</td>
                      <td id="T_61bdb_row54_col8" class="data row54 col8">1</td>
                      <td id="T_61bdb_row54_col9" class="data row54 col9">15</td>
                      <td id="T_61bdb_row54_col10" class="data row54 col10">0.358000</td>
                      <td id="T_61bdb_row54_col11" class="data row54 col11">0.853000</td>
                      <td id="T_61bdb_row54_col12" class="data row54 col12">0.494000</td>
                      <td id="T_61bdb_row54_col13" class="data row54 col13">86</td>
                      <td id="T_61bdb_row54_col14" class="data row54 col14">28</td>
                      <td id="T_61bdb_row54_col15" class="data row54 col15">61</td>
                      <td id="T_61bdb_row54_col16" class="data row54 col16">21</td>
                      <td id="T_61bdb_row54_col17" class="data row54 col17">5</td>
                      <td id="T_61bdb_row54_col18" class="data row54 col18">208</td>
                      <td id="T_61bdb_row54_col19" class="data row54 col19">223</td>
                      <td id="T_61bdb_row54_col20" class="data row54 col20">0.313000</td>
                      <td id="T_61bdb_row54_col21" class="data row54 col21">OF</td>
                      <td id="T_61bdb_row54_col22" class="data row54 col22">A</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row55_col0" class="data row55 col0">79</td>
                      <td id="T_61bdb_row55_col1" class="data row55 col1">Atl</td>
                      <td id="T_61bdb_row55_col2" class="data row55 col2">22</td>
                      <td id="T_61bdb_row55_col3" class="data row55 col3">Drew Waters</td>
                      <td id="T_61bdb_row55_col4" class="data row55 col4">397</td>
                      <td id="T_61bdb_row55_col5" class="data row55 col5">70</td>
                      <td id="T_61bdb_row55_col6" class="data row55 col6">96</td>
                      <td id="T_61bdb_row55_col7" class="data row55 col7">22</td>
                      <td id="T_61bdb_row55_col8" class="data row55 col8">1</td>
                      <td id="T_61bdb_row55_col9" class="data row55 col9">11</td>
                      <td id="T_61bdb_row55_col10" class="data row55 col10">0.330000</td>
                      <td id="T_61bdb_row55_col11" class="data row55 col11">0.716000</td>
                      <td id="T_61bdb_row55_col12" class="data row55 col12">0.385000</td>
                      <td id="T_61bdb_row55_col13" class="data row55 col13">37</td>
                      <td id="T_61bdb_row55_col14" class="data row55 col14">46</td>
                      <td id="T_61bdb_row55_col15" class="data row55 col15">141</td>
                      <td id="T_61bdb_row55_col16" class="data row55 col16">28</td>
                      <td id="T_61bdb_row55_col17" class="data row55 col17">9</td>
                      <td id="T_61bdb_row55_col18" class="data row55 col18">139</td>
                      <td id="T_61bdb_row55_col19" class="data row55 col19">153</td>
                      <td id="T_61bdb_row55_col20" class="data row55 col20">0.242000</td>
                      <td id="T_61bdb_row55_col21" class="data row55 col21">CF</td>
                      <td id="T_61bdb_row55_col22" class="data row55 col22">AAA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row56_col0" class="data row56 col0">80</td>
                      <td id="T_61bdb_row56_col1" class="data row56 col1">San</td>
                      <td id="T_61bdb_row56_col2" class="data row56 col2">22</td>
                      <td id="T_61bdb_row56_col3" class="data row56 col3">Heliot Ramos</td>
                      <td id="T_61bdb_row56_col4" class="data row56 col4">441</td>
                      <td id="T_61bdb_row56_col5" class="data row56 col5">65</td>
                      <td id="T_61bdb_row56_col6" class="data row56 col6">112</td>
                      <td id="T_61bdb_row56_col7" class="data row56 col7">25</td>
                      <td id="T_61bdb_row56_col8" class="data row56 col8">3</td>
                      <td id="T_61bdb_row56_col9" class="data row56 col9">14</td>
                      <td id="T_61bdb_row56_col10" class="data row56 col10">0.324000</td>
                      <td id="T_61bdb_row56_col11" class="data row56 col11">0.744000</td>
                      <td id="T_61bdb_row56_col12" class="data row56 col12">0.420000</td>
                      <td id="T_61bdb_row56_col13" class="data row56 col13">56</td>
                      <td id="T_61bdb_row56_col14" class="data row56 col14">42</td>
                      <td id="T_61bdb_row56_col15" class="data row56 col15">134</td>
                      <td id="T_61bdb_row56_col16" class="data row56 col16">15</td>
                      <td id="T_61bdb_row56_col17" class="data row56 col17">4</td>
                      <td id="T_61bdb_row56_col18" class="data row56 col18">177</td>
                      <td id="T_61bdb_row56_col19" class="data row56 col19">185</td>
                      <td id="T_61bdb_row56_col20" class="data row56 col20">0.254000</td>
                      <td id="T_61bdb_row56_col21" class="data row56 col21">CF</td>
                      <td id="T_61bdb_row56_col22" class="data row56 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row57_col0" class="data row57 col0">82</td>
                      <td id="T_61bdb_row57_col1" class="data row57 col1">Cle</td>
                      <td id="T_61bdb_row57_col2" class="data row57 col2">21</td>
                      <td id="T_61bdb_row57_col3" class="data row57 col3">Gabriel Arias</td>
                      <td id="T_61bdb_row57_col4" class="data row57 col4">434</td>
                      <td id="T_61bdb_row57_col5" class="data row57 col5">64</td>
                      <td id="T_61bdb_row57_col6" class="data row57 col6">124</td>
                      <td id="T_61bdb_row57_col7" class="data row57 col7">29</td>
                      <td id="T_61bdb_row57_col8" class="data row57 col8">3</td>
                      <td id="T_61bdb_row57_col9" class="data row57 col9">13</td>
                      <td id="T_61bdb_row57_col10" class="data row57 col10">0.349000</td>
                      <td id="T_61bdb_row57_col11" class="data row57 col11">0.806000</td>
                      <td id="T_61bdb_row57_col12" class="data row57 col12">0.456000</td>
                      <td id="T_61bdb_row57_col13" class="data row57 col13">55</td>
                      <td id="T_61bdb_row57_col14" class="data row57 col14">39</td>
                      <td id="T_61bdb_row57_col15" class="data row57 col15">110</td>
                      <td id="T_61bdb_row57_col16" class="data row57 col16">5</td>
                      <td id="T_61bdb_row57_col17" class="data row57 col17">1</td>
                      <td id="T_61bdb_row57_col18" class="data row57 col18">188</td>
                      <td id="T_61bdb_row57_col19" class="data row57 col19">198</td>
                      <td id="T_61bdb_row57_col20" class="data row57 col20">0.286000</td>
                      <td id="T_61bdb_row57_col21" class="data row57 col21">SS</td>
                      <td id="T_61bdb_row57_col22" class="data row57 col22">AAA</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row58_col0" class="data row58 col0">83</td>
                      <td id="T_61bdb_row58_col1" class="data row58 col1">Tex</td>
                      <td id="T_61bdb_row58_col2" class="data row58 col2">22</td>
                      <td id="T_61bdb_row58_col3" class="data row58 col3">Justin Foscue</td>
                      <td id="T_61bdb_row58_col4" class="data row58 col4">229</td>
                      <td id="T_61bdb_row58_col5" class="data row58 col5">52</td>
                      <td id="T_61bdb_row58_col6" class="data row58 col6">63</td>
                      <td id="T_61bdb_row58_col7" class="data row58 col7">19</td>
                      <td id="T_61bdb_row58_col8" class="data row58 col8">1</td>
                      <td id="T_61bdb_row58_col9" class="data row58 col9">17</td>
                      <td id="T_61bdb_row58_col10" class="data row58 col10">0.371000</td>
                      <td id="T_61bdb_row58_col11" class="data row58 col11">0.960000</td>
                      <td id="T_61bdb_row58_col12" class="data row58 col12">0.590000</td>
                      <td id="T_61bdb_row58_col13" class="data row58 col13">51</td>
                      <td id="T_61bdb_row58_col14" class="data row58 col14">25</td>
                      <td id="T_61bdb_row58_col15" class="data row58 col15">72</td>
                      <td id="T_61bdb_row58_col16" class="data row58 col16">2</td>
                      <td id="T_61bdb_row58_col17" class="data row58 col17">2</td>
                      <td id="T_61bdb_row58_col18" class="data row58 col18">92</td>
                      <td id="T_61bdb_row58_col19" class="data row58 col19">135</td>
                      <td id="T_61bdb_row58_col20" class="data row58 col20">0.275000</td>
                      <td id="T_61bdb_row58_col21" class="data row58 col21">2B</td>
                      <td id="T_61bdb_row58_col22" class="data row58 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row59_col0" class="data row59 col0">84</td>
                      <td id="T_61bdb_row59_col1" class="data row59 col1">Tam</td>
                      <td id="T_61bdb_row59_col2" class="data row59 col2">23</td>
                      <td id="T_61bdb_row59_col3" class="data row59 col3">Greg Jones</td>
                      <td id="T_61bdb_row59_col4" class="data row59 col4">274</td>
                      <td id="T_61bdb_row59_col5" class="data row59 col5">56</td>
                      <td id="T_61bdb_row59_col6" class="data row59 col6">74</td>
                      <td id="T_61bdb_row59_col7" class="data row59 col7">8</td>
                      <td id="T_61bdb_row59_col8" class="data row59 col8">4</td>
                      <td id="T_61bdb_row59_col9" class="data row59 col9">14</td>
                      <td id="T_61bdb_row59_col10" class="data row59 col10">0.366000</td>
                      <td id="T_61bdb_row59_col11" class="data row59 col11">0.848000</td>
                      <td id="T_61bdb_row59_col12" class="data row59 col12">0.482000</td>
                      <td id="T_61bdb_row59_col13" class="data row59 col13">40</td>
                      <td id="T_61bdb_row59_col14" class="data row59 col14">33</td>
                      <td id="T_61bdb_row59_col15" class="data row59 col15">96</td>
                      <td id="T_61bdb_row59_col16" class="data row59 col16">34</td>
                      <td id="T_61bdb_row59_col17" class="data row59 col17">2</td>
                      <td id="T_61bdb_row59_col18" class="data row59 col18">92</td>
                      <td id="T_61bdb_row59_col19" class="data row59 col19">132</td>
                      <td id="T_61bdb_row59_col20" class="data row59 col20">0.270000</td>
                      <td id="T_61bdb_row59_col21" class="data row59 col21">SS</td>
                      <td id="T_61bdb_row59_col22" class="data row59 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row60_col0" class="data row60 col0">85</td>
                      <td id="T_61bdb_row60_col1" class="data row60 col1">Pit</td>
                      <td id="T_61bdb_row60_col2" class="data row60 col2">20</td>
                      <td id="T_61bdb_row60_col3" class="data row60 col3">Liover Peguero</td>
                      <td id="T_61bdb_row60_col4" class="data row60 col4">374</td>
                      <td id="T_61bdb_row60_col5" class="data row60 col5">67</td>
                      <td id="T_61bdb_row60_col6" class="data row60 col6">101</td>
                      <td id="T_61bdb_row60_col7" class="data row60 col7">19</td>
                      <td id="T_61bdb_row60_col8" class="data row60 col8">2</td>
                      <td id="T_61bdb_row60_col9" class="data row60 col9">14</td>
                      <td id="T_61bdb_row60_col10" class="data row60 col10">0.332000</td>
                      <td id="T_61bdb_row60_col11" class="data row60 col11">0.776000</td>
                      <td id="T_61bdb_row60_col12" class="data row60 col12">0.444000</td>
                      <td id="T_61bdb_row60_col13" class="data row60 col13">45</td>
                      <td id="T_61bdb_row60_col14" class="data row60 col14">33</td>
                      <td id="T_61bdb_row60_col15" class="data row60 col15">105</td>
                      <td id="T_61bdb_row60_col16" class="data row60 col16">28</td>
                      <td id="T_61bdb_row60_col17" class="data row60 col17">6</td>
                      <td id="T_61bdb_row60_col18" class="data row60 col18">155</td>
                      <td id="T_61bdb_row60_col19" class="data row60 col19">166</td>
                      <td id="T_61bdb_row60_col20" class="data row60 col20">0.270000</td>
                      <td id="T_61bdb_row60_col21" class="data row60 col21">SS</td>
                      <td id="T_61bdb_row60_col22" class="data row60 col22">A+</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row61_col0" class="data row61 col0">88</td>
                      <td id="T_61bdb_row61_col1" class="data row61 col1">Mil</td>
                      <td id="T_61bdb_row61_col2" class="data row61 col2">21</td>
                      <td id="T_61bdb_row61_col3" class="data row61 col3">Sal Frelick</td>
                      <td id="T_61bdb_row61_col4" class="data row61 col4">146</td>
                      <td id="T_61bdb_row61_col5" class="data row61 col5">28</td>
                      <td id="T_61bdb_row61_col6" class="data row61 col6">48</td>
                      <td id="T_61bdb_row61_col7" class="data row61 col7">8</td>
                      <td id="T_61bdb_row61_col8" class="data row61 col8">3</td>
                      <td id="T_61bdb_row61_col9" class="data row61 col9">2</td>
                      <td id="T_61bdb_row61_col10" class="data row61 col10">0.414000</td>
                      <td id="T_61bdb_row61_col11" class="data row61 col11">0.880000</td>
                      <td id="T_61bdb_row61_col12" class="data row61 col12">0.466000</td>
                      <td id="T_61bdb_row61_col13" class="data row61 col13">21</td>
                      <td id="T_61bdb_row61_col14" class="data row61 col14">21</td>
                      <td id="T_61bdb_row61_col15" class="data row61 col15">25</td>
                      <td id="T_61bdb_row61_col16" class="data row61 col16">12</td>
                      <td id="T_61bdb_row61_col17" class="data row61 col17">2</td>
                      <td id="T_61bdb_row61_col18" class="data row61 col18">54</td>
                      <td id="T_61bdb_row61_col19" class="data row61 col19">68</td>
                      <td id="T_61bdb_row61_col20" class="data row61 col20">0.329000</td>
                      <td id="T_61bdb_row61_col21" class="data row61 col21">OF</td>
                      <td id="T_61bdb_row61_col22" class="data row61 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row62_col0" class="data row62 col0">89</td>
                      <td id="T_61bdb_row62_col1" class="data row62 col1">Atl</td>
                      <td id="T_61bdb_row62_col2" class="data row62 col2">20</td>
                      <td id="T_61bdb_row62_col3" class="data row62 col3">Michael Harris II</td>
                      <td id="T_61bdb_row62_col4" class="data row62 col4">374</td>
                      <td id="T_61bdb_row62_col5" class="data row62 col5">55</td>
                      <td id="T_61bdb_row62_col6" class="data row62 col6">110</td>
                      <td id="T_61bdb_row62_col7" class="data row62 col7">26</td>
                      <td id="T_61bdb_row62_col8" class="data row62 col8">3</td>
                      <td id="T_61bdb_row62_col9" class="data row62 col9">7</td>
                      <td id="T_61bdb_row62_col10" class="data row62 col10">0.362000</td>
                      <td id="T_61bdb_row62_col11" class="data row62 col11">0.798000</td>
                      <td id="T_61bdb_row62_col12" class="data row62 col12">0.436000</td>
                      <td id="T_61bdb_row62_col13" class="data row62 col13">64</td>
                      <td id="T_61bdb_row62_col14" class="data row62 col14">35</td>
                      <td id="T_61bdb_row62_col15" class="data row62 col15">76</td>
                      <td id="T_61bdb_row62_col16" class="data row62 col16">27</td>
                      <td id="T_61bdb_row62_col17" class="data row62 col17">4</td>
                      <td id="T_61bdb_row62_col18" class="data row62 col18">148</td>
                      <td id="T_61bdb_row62_col19" class="data row62 col19">163</td>
                      <td id="T_61bdb_row62_col20" class="data row62 col20">0.294000</td>
                      <td id="T_61bdb_row62_col21" class="data row62 col21">OF</td>
                      <td id="T_61bdb_row62_col22" class="data row62 col22">A+</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row63_col0" class="data row63 col0">90</td>
                      <td id="T_61bdb_row63_col1" class="data row63 col1">Cin</td>
                      <td id="T_61bdb_row63_col2" class="data row63 col2">22</td>
                      <td id="T_61bdb_row63_col3" class="data row63 col3">Matt McLain</td>
                      <td id="T_61bdb_row63_col4" class="data row63 col4">106</td>
                      <td id="T_61bdb_row63_col5" class="data row63 col5">17</td>
                      <td id="T_61bdb_row63_col6" class="data row63 col6">30</td>
                      <td id="T_61bdb_row63_col7" class="data row63 col7">8</td>
                      <td id="T_61bdb_row63_col8" class="data row63 col8">1</td>
                      <td id="T_61bdb_row63_col9" class="data row63 col9">3</td>
                      <td id="T_61bdb_row63_col10" class="data row63 col10">0.389000</td>
                      <td id="T_61bdb_row63_col11" class="data row63 col11">0.851000</td>
                      <td id="T_61bdb_row63_col12" class="data row63 col12">0.462000</td>
                      <td id="T_61bdb_row63_col13" class="data row63 col13">19</td>
                      <td id="T_61bdb_row63_col14" class="data row63 col14">17</td>
                      <td id="T_61bdb_row63_col15" class="data row63 col15">24</td>
                      <td id="T_61bdb_row63_col16" class="data row63 col16">10</td>
                      <td id="T_61bdb_row63_col17" class="data row63 col17">2</td>
                      <td id="T_61bdb_row63_col18" class="data row63 col18">30</td>
                      <td id="T_61bdb_row63_col19" class="data row63 col19">49</td>
                      <td id="T_61bdb_row63_col20" class="data row63 col20">0.283000</td>
                      <td id="T_61bdb_row63_col21" class="data row63 col21">SS</td>
                      <td id="T_61bdb_row63_col22" class="data row63 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row64_col0" class="data row64 col0">91</td>
                      <td id="T_61bdb_row64_col1" class="data row64 col1">Tex</td>
                      <td id="T_61bdb_row64_col2" class="data row64 col2">23</td>
                      <td id="T_61bdb_row64_col3" class="data row64 col3">Sam Huff</td>
                      <td id="T_61bdb_row64_col4" class="data row64 col4">220</td>
                      <td id="T_61bdb_row64_col5" class="data row64 col5">34</td>
                      <td id="T_61bdb_row64_col6" class="data row64 col6">54</td>
                      <td id="T_61bdb_row64_col7" class="data row64 col7">8</td>
                      <td id="T_61bdb_row64_col8" class="data row64 col8">0</td>
                      <td id="T_61bdb_row64_col9" class="data row64 col9">16</td>
                      <td id="T_61bdb_row64_col10" class="data row64 col10">0.318000</td>
                      <td id="T_61bdb_row64_col11" class="data row64 col11">0.818000</td>
                      <td id="T_61bdb_row64_col12" class="data row64 col12">0.500000</td>
                      <td id="T_61bdb_row64_col13" class="data row64 col13">36</td>
                      <td id="T_61bdb_row64_col14" class="data row64 col14">21</td>
                      <td id="T_61bdb_row64_col15" class="data row64 col15">95</td>
                      <td id="T_61bdb_row64_col16" class="data row64 col16">0</td>
                      <td id="T_61bdb_row64_col17" class="data row64 col17">0</td>
                      <td id="T_61bdb_row64_col18" class="data row64 col18">91</td>
                      <td id="T_61bdb_row64_col19" class="data row64 col19">110</td>
                      <td id="T_61bdb_row64_col20" class="data row64 col20">0.245000</td>
                      <td id="T_61bdb_row64_col21" class="data row64 col21">C</td>
                      <td id="T_61bdb_row64_col22" class="data row64 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row65_col0" class="data row65 col0">93</td>
                      <td id="T_61bdb_row65_col1" class="data row65 col1">Col</td>
                      <td id="T_61bdb_row65_col2" class="data row65 col2">19</td>
                      <td id="T_61bdb_row65_col3" class="data row65 col3">Benny Montgomery</td>
                      <td id="T_61bdb_row65_col4" class="data row65 col4">47</td>
                      <td id="T_61bdb_row65_col5" class="data row65 col5">7</td>
                      <td id="T_61bdb_row65_col6" class="data row65 col6">16</td>
                      <td id="T_61bdb_row65_col7" class="data row65 col7">0</td>
                      <td id="T_61bdb_row65_col8" class="data row65 col8">1</td>
                      <td id="T_61bdb_row65_col9" class="data row65 col9">0</td>
                      <td id="T_61bdb_row65_col10" class="data row65 col10">0.404000</td>
                      <td id="T_61bdb_row65_col11" class="data row65 col11">0.787000</td>
                      <td id="T_61bdb_row65_col12" class="data row65 col12">0.383000</td>
                      <td id="T_61bdb_row65_col13" class="data row65 col13">6</td>
                      <td id="T_61bdb_row65_col14" class="data row65 col14">5</td>
                      <td id="T_61bdb_row65_col15" class="data row65 col15">9</td>
                      <td id="T_61bdb_row65_col16" class="data row65 col16">5</td>
                      <td id="T_61bdb_row65_col17" class="data row65 col17">1</td>
                      <td id="T_61bdb_row65_col18" class="data row65 col18">20</td>
                      <td id="T_61bdb_row65_col19" class="data row65 col19">18</td>
                      <td id="T_61bdb_row65_col20" class="data row65 col20">0.340000</td>
                      <td id="T_61bdb_row65_col21" class="data row65 col21">OF</td>
                      <td id="T_61bdb_row65_col22" class="data row65 col22">ROK</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row66_col0" class="data row66 col0">96</td>
                      <td id="T_61bdb_row66_col1" class="data row66 col1">Bos</td>
                      <td id="T_61bdb_row66_col2" class="data row66 col2">19</td>
                      <td id="T_61bdb_row66_col3" class="data row66 col3">Nick Yorke</td>
                      <td id="T_61bdb_row66_col4" class="data row66 col4">378</td>
                      <td id="T_61bdb_row66_col5" class="data row66 col5">76</td>
                      <td id="T_61bdb_row66_col6" class="data row66 col6">123</td>
                      <td id="T_61bdb_row66_col7" class="data row66 col7">20</td>
                      <td id="T_61bdb_row66_col8" class="data row66 col8">5</td>
                      <td id="T_61bdb_row66_col9" class="data row66 col9">14</td>
                      <td id="T_61bdb_row66_col10" class="data row66 col10">0.412000</td>
                      <td id="T_61bdb_row66_col11" class="data row66 col11">0.928000</td>
                      <td id="T_61bdb_row66_col12" class="data row66 col12">0.516000</td>
                      <td id="T_61bdb_row66_col13" class="data row66 col13">62</td>
                      <td id="T_61bdb_row66_col14" class="data row66 col14">52</td>
                      <td id="T_61bdb_row66_col15" class="data row66 col15">69</td>
                      <td id="T_61bdb_row66_col16" class="data row66 col16">13</td>
                      <td id="T_61bdb_row66_col17" class="data row66 col17">9</td>
                      <td id="T_61bdb_row66_col18" class="data row66 col18">143</td>
                      <td id="T_61bdb_row66_col19" class="data row66 col19">195</td>
                      <td id="T_61bdb_row66_col20" class="data row66 col20">0.325000</td>
                      <td id="T_61bdb_row66_col21" class="data row66 col21">2B</td>
                      <td id="T_61bdb_row66_col22" class="data row66 col22">ALL (2)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row67_col0" class="data row67 col0">97</td>
                      <td id="T_61bdb_row67_col1" class="data row67 col1">Phi</td>
                      <td id="T_61bdb_row67_col2" class="data row67 col2">23</td>
                      <td id="T_61bdb_row67_col3" class="data row67 col3">Bryson Stott</td>
                      <td id="T_61bdb_row67_col4" class="data row67 col4">406</td>
                      <td id="T_61bdb_row67_col5" class="data row67 col5">71</td>
                      <td id="T_61bdb_row67_col6" class="data row67 col6">125</td>
                      <td id="T_61bdb_row67_col7" class="data row67 col7">26</td>
                      <td id="T_61bdb_row67_col8" class="data row67 col8">2</td>
                      <td id="T_61bdb_row67_col9" class="data row67 col9">16</td>
                      <td id="T_61bdb_row67_col10" class="data row67 col10">0.400000</td>
                      <td id="T_61bdb_row67_col11" class="data row67 col11">0.900000</td>
                      <td id="T_61bdb_row67_col12" class="data row67 col12">0.500000</td>
                      <td id="T_61bdb_row67_col13" class="data row67 col13">49</td>
                      <td id="T_61bdb_row67_col14" class="data row67 col14">65</td>
                      <td id="T_61bdb_row67_col15" class="data row67 col15">103</td>
                      <td id="T_61bdb_row67_col16" class="data row67 col16">10</td>
                      <td id="T_61bdb_row67_col17" class="data row67 col17">4</td>
                      <td id="T_61bdb_row67_col18" class="data row67 col18">155</td>
                      <td id="T_61bdb_row67_col19" class="data row67 col19">203</td>
                      <td id="T_61bdb_row67_col20" class="data row67 col20">0.308000</td>
                      <td id="T_61bdb_row67_col21" class="data row67 col21">SS</td>
                      <td id="T_61bdb_row67_col22" class="data row67 col22">ALL (3)</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row68_col0" class="data row68 col0">98</td>
                      <td id="T_61bdb_row68_col1" class="data row68 col1">Sea</td>
                      <td id="T_61bdb_row68_col2" class="data row68 col2">18</td>
                      <td id="T_61bdb_row68_col3" class="data row68 col3">Harry Ford</td>
                      <td id="T_61bdb_row68_col4" class="data row68 col4">55</td>
                      <td id="T_61bdb_row68_col5" class="data row68 col5">12</td>
                      <td id="T_61bdb_row68_col6" class="data row68 col6">16</td>
                      <td id="T_61bdb_row68_col7" class="data row68 col7">7</td>
                      <td id="T_61bdb_row68_col8" class="data row68 col8">0</td>
                      <td id="T_61bdb_row68_col9" class="data row68 col9">3</td>
                      <td id="T_61bdb_row68_col10" class="data row68 col10">0.400000</td>
                      <td id="T_61bdb_row68_col11" class="data row68 col11">0.982000</td>
                      <td id="T_61bdb_row68_col12" class="data row68 col12">0.582000</td>
                      <td id="T_61bdb_row68_col13" class="data row68 col13">10</td>
                      <td id="T_61bdb_row68_col14" class="data row68 col14">9</td>
                      <td id="T_61bdb_row68_col15" class="data row68 col15">14</td>
                      <td id="T_61bdb_row68_col16" class="data row68 col16">3</td>
                      <td id="T_61bdb_row68_col17" class="data row68 col17">0</td>
                      <td id="T_61bdb_row68_col18" class="data row68 col18">27</td>
                      <td id="T_61bdb_row68_col19" class="data row68 col19">32</td>
                      <td id="T_61bdb_row68_col20" class="data row68 col20">0.291000</td>
                      <td id="T_61bdb_row68_col21" class="data row68 col21">C</td>
                      <td id="T_61bdb_row68_col22" class="data row68 col22">ROK</td>
                    </tr>
                    <tr>
                      <td id="T_61bdb_row69_col0" class="data row69 col0">100</td>
                      <td id="T_61bdb_row69_col1" class="data row69 col1">LAD</td>
                      <td id="T_61bdb_row69_col2" class="data row69 col2">20</td>
                      <td id="T_61bdb_row69_col3" class="data row69 col3">Andy Pages</td>
                      <td id="T_61bdb_row69_col4" class="data row69 col4">438</td>
                      <td id="T_61bdb_row69_col5" class="data row69 col5">96</td>
                      <td id="T_61bdb_row69_col6" class="data row69 col6">116</td>
                      <td id="T_61bdb_row69_col7" class="data row69 col7">25</td>
                      <td id="T_61bdb_row69_col8" class="data row69 col8">1</td>
                      <td id="T_61bdb_row69_col9" class="data row69 col9">31</td>
                      <td id="T_61bdb_row69_col10" class="data row69 col10">0.394000</td>
                      <td id="T_61bdb_row69_col11" class="data row69 col11">0.933000</td>
                      <td id="T_61bdb_row69_col12" class="data row69 col12">0.539000</td>
                      <td id="T_61bdb_row69_col13" class="data row69 col13">88</td>
                      <td id="T_61bdb_row69_col14" class="data row69 col14">77</td>
                      <td id="T_61bdb_row69_col15" class="data row69 col15">132</td>
                      <td id="T_61bdb_row69_col16" class="data row69 col16">6</td>
                      <td id="T_61bdb_row69_col17" class="data row69 col17">3</td>
                      <td id="T_61bdb_row69_col18" class="data row69 col18">173</td>
                      <td id="T_61bdb_row69_col19" class="data row69 col19">236</td>
                      <td id="T_61bdb_row69_col20" class="data row69 col20">0.265000</td>
                      <td id="T_61bdb_row69_col21" class="data row69 col21">RF</td>
                      <td id="T_61bdb_row69_col22" class="data row69 col22">A+</td>
                    </tr>
                  </tbody>
                </table>
              </div>

            </div>

          </div>
        </div>

      </div>
      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

      </div>
      <div class="cell border-box-sizing text_cell rendered">
        <div class="prompt input_prompt">
        </div>
        <div class="inner_cell">
          <div class="text_cell_render border-box-sizing rendered_html">
            <h1 id="Average-Age-of-Hitters" style="
  padding-left: 350px;
">Average Age of Hitters<a class="anchor-link" href="#Average-Age-of-Hitters">&#182;</a></h1>
          </div>
        </div>
      </div>
      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

        <div class="output_wrapper">
          <div class="output">


            <div class="output_area">

              <div class="prompt"></div>




              <div class="output_text output_subarea output_execute_result">
                <!-- <pre>&lt;AxesSubplot:ylabel=&#39;Frequency&#39;&gt;</pre> -->
              </div>

            </div>

            <div class="output_area">

              <div class="prompt"></div>




              <div class="output_png output_subarea output_execute_result">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAX4AAAD4CAYAAADrRI2NAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjMuNCwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy8QVMy6AAAACXBIWXMAAAsTAAALEwEAmpwYAAARA0lEQVR4nO3dfYxldX3H8fdHwCKKRcOgCKyDxqKGquBom2pFoVgEBa21lWhjhbpatYrWyCJGSIyJ1gfU2oirUlEpPj8WbUEr0iY8LbDK4oIYXXlUVkldfKh05ds/7t06DDOzd2fn3DMzv/crmcw55565v08usx9+c+4556aqkCS14159B5AkjZfFL0mNsfglqTEWvyQ1xuKXpMbs2neAUey99941OTnZdwxJWlauuOKKn1TVxMzty6L4JycnWbduXd8xJGlZSfLD2bZ7qEeSGmPxS1JjLH5JaozFL0mNsfglqTEWvyQ1xuKXpMZY/JLUGItfkhqzLK7clZaqyTXn9Tb2prce09vYWt6c8UtSYyx+SWqMxS9JjbH4JakxFr8kNcbil6TGWPyS1BiLX5IaY/FLUmM6K/4kZyW5LcmGWR57XZJKsndX40uSZtfljP8jwFEzNyY5ADgSuKHDsSVJc+is+KvqIuD2WR46A3g9UF2NLUma21iP8Sc5Fri5qr41znElSb81trtzJtkDOBV4+oj7rwZWA6xatarDZFoJ+rxLprTcjHPG/3DgQOBbSTYB+wNXJnnwbDtX1dqqmqqqqYmJiTHGlKSVbWwz/qq6Gthn2/qw/Keq6ifjyiBJ6vZ0znOBi4GDktyU5MSuxpIkja6zGX9VHb+dxye7GluSNDev3JWkxlj8ktQYi1+SGmPxS1JjLH5JaozFL0mNsfglqTEWvyQ1Zmy3bJC0MvR5Q7xNbz2mt7FXEmf8ktQYi1+SGmPxS1JjLH5JaozFL0mNsfglqTEWvyQ1xuKXpMZY/JLUGItfkhrT5Yetn5XktiQbpm17e5Jrk3w7yeeT7NXV+JKk2XU54/8IcNSMbRcAB1fVY4DvAqd0OL4kaRadFX9VXQTcPmPb+VW1dbh6CbB/V+NLkmbX5905TwA+OdeDSVYDqwFWrVo1rkwrQl93T/TOidLy0Mubu0lOBbYC58y1T1WtraqpqpqamJgYXzhJWuHGPuNP8iLgmcARVVXjHl+SWjfW4k9yFHAycFhV/XKcY0uSBro8nfNc4GLgoCQ3JTkReB+wJ3BBkvVJzuxqfEnS7Dqb8VfV8bNs/nBX40mSRuOVu5LUGItfkhpj8UtSYyx+SWqMxS9JjbH4JakxFr8kNcbil6TGWPyS1BiLX5IaY/FLUmMsfklqjMUvSY2x+CWpMRa/JDXG4pekxlj8ktQYi1+SGmPxS1Jjuvyw9bOS3JZkw7RtD0xyQZLrh98f0NX4kqTZdTnj/whw1Ixta4CvV9UjgK8P1yVJY9RZ8VfVRcDtMzYfB5w9XD4beHZX40uSZrfrmMd7UFXdClBVtybZZ64dk6wGVgOsWrVqTPEW1+Sa8/qOIEn3sGTf3K2qtVU1VVVTExMTfceRpBVj3MX/4yT7Agy/3zbm8SWpeeMu/i8BLxouvwj44pjHl6TmdXk657nAxcBBSW5KciLwVuDIJNcDRw7XJUlj1Nmbu1V1/BwPHdHVmJKk7Rtpxp/k4K6DSJLGY9RDPWcmuSzJy5Ps1WUgSVK3Rir+qnoy8ALgAGBdkn9JcmSnySRJnRj5zd2quh54I3AycBjw3iTXJvmzrsJJkhbfqMf4H5PkDGAjcDjwrKp61HD5jA7zSZIW2ahn9bwP+CDwhqr61baNVXVLkjd2kkyS1IlRi/9o4FdV9RuAJPcCdq+qX1bVxzpLJ0ladKMe4/8acJ9p63sMt0mSlplRi3/3qvr5tpXh8h7dRJIkdWnU4v9FkkO3rSR5PPCrefaXJC1Rox7jPwn4dJJbhuv7An/ZSSJJUqdGKv6qujzJI4GDgADXVtX/dppMktSJHblJ2xOAyeHPHJKEqvpoJ6kkSZ0ZqfiTfAx4OLAe+M1wcwEWvyQtM6PO+KeAR1dVdRlGktS9Uc/q2QA8uMsgkqTxGHXGvzfwnSSXAb/etrGqju0klSSpM6MW/+ldhpAkjc+o9+P/JrAJ2G24fDlw5UIHTfKaJNck2ZDk3CS7L/S5JEk7ZtTbMr8E+AzwgeGm/YAvLGTAJPsBrwKmqupgYBfg+Qt5LknSjhv1zd1XAE8CtsD/fyjLPjsx7q7AfZLsyuCeP7dsZ39J0iIZtfh/XVV3blsZFvaCTu2sqpuBdwA3ALcCP6uq82ful2R1knVJ1m3evHkhQ0mSZjFq8X8zyRsYzNKPBD4NfHkhAyZ5AHAccCDwEOC+SV44c7+qWltVU1U1NTExsZChJEmzGLX41wCbgauBlwJfYfD5uwvxJ8APqmrz8H4/nwP+aIHPJUnaQaPepO0uBh+9+MFFGPMG4A+T7MHg1s5HAOsW4XklSSMY9V49P2CWY/pV9bAdHbCqLk3yGQang24FrgLW7ujzSJIWZkfu1bPN7sDzgAcudNCqOg04baE/L0lauFEv4PrptK+bq+rdwOHdRpMkdWHUQz2HTlu9F4O/APbsJJEkqVOjHup557TlrQxu3/AXi55GktS5Uc/qeVrXQSRJ4zHqoZ7Xzvd4Vb1rceJIkrq2I2f1PAH40nD9WcBFwI1dhJIkdWdHPojl0Kq6AyDJ6cCnq+pvugomSerGqLdsWAXcOW39TmBy0dNIkjo36oz/Y8BlST7P4Are5wAf7SyVJKkzo57V85YkXwX+eLjpxVV1VXexJEldGfVQDww+MGVLVb0HuCnJgR1lkiR1aNSPXjwNOBk4ZbhpN+DjXYWSJHVn1Bn/c4BjgV8AVNUteMsGSVqWRi3+O6uqGN6aOcl9u4skSerSqMX/qSQfAPZK8hLgayzOh7JIksZsu2f1JAnwSeCRwBbgIOBNVXVBx9kkSR3YbvFXVSX5QlU9HrDsJWmZG/VQzyVJntBpEknSWIx65e7TgJcl2cTgzJ4w+GPgMV0FkyR1Y97iT7Kqqm4AnrGYgybZC/gQcDCDM4VOqKqLF3MMSdLstjfj/wKDu3L+MMlnq+q5izTue4B/q6o/T3JvBlcFS5LGYHvFn2nLD1uMAZPcH3gK8NcAVXUnd7/zpySpQ9t7c7fmWN4ZDwM2A/+c5KokH5rtgrAkq5OsS7Ju8+bNizS0JGl7xf/YJFuS3AE8Zri8JckdSbYscMxdgUOB91fVIQzeLF4zc6eqWltVU1U1NTExscChJEkzzXuop6p26WDMm4CbqurS4fpnmKX4JUnd2JHbMi+KqvoRcGOSg4abjgC+M+4cktSqUc/jX2x/B5wzPKPn+8CLe8ohSc3ppfiraj0w1cfYktS6sR/qkST1y+KXpMZY/JLUGItfkhpj8UtSYyx+SWqMxS9JjbH4JakxFr8kNcbil6TGWPyS1BiLX5IaY/FLUmMsfklqjMUvSY2x+CWpMRa/JDXG4pekxvRW/El2SXJVkn/tK4MktajPGf+rgY09ji9JTeql+JPsDxwDfKiP8SWpZX3N+N8NvB64q6fxJalZu457wCTPBG6rqiuSPHWe/VYDqwFWrVq14PEm15y34J+VpJWojxn/k4Bjk2wCPgEcnuTjM3eqqrVVNVVVUxMTE+POKEkr1tiLv6pOqar9q2oSeD7wH1X1wnHnkKRWeR6/JDVm7Mf4p6uqC4EL+8wgSa1xxi9JjbH4JakxFr8kNcbil6TGWPyS1BiLX5IaY/FLUmMsfklqjMUvSY2x+CWpMRa/JDXG4pekxlj8ktQYi1+SGmPxS1JjLH5JaozFL0mNsfglqTEWvyQ1ZuzFn+SAJN9IsjHJNUlePe4MktSyPj5sfSvw91V1ZZI9gSuSXFBV3+khiyQ1Z+wz/qq6taquHC7fAWwE9ht3DklqVa/H+JNMAocAl87y2Ook65Ks27x589izSdJK1VvxJ7kf8FngpKraMvPxqlpbVVNVNTUxMTH+gJK0QvVS/El2Y1D651TV5/rIIEmt6uOsngAfBjZW1bvGPb4kta6PGf+TgL8CDk+yfvh1dA85JKlJYz+ds6r+C8i4x5UkDXjlriQ1xuKXpMZY/JLUGItfkhpj8UtSYyx+SWqMxS9JjbH4JakxfdyPX5IWZHLNeX1HGLtNbz1m0Z/TGb8kNcbil6TGWPyS1BiLX5IaY/FLUmMsfklqjMUvSY2x+CWpMRa/JDXG4pekxvRS/EmOSnJdku8lWdNHBklq1diLP8kuwD8BzwAeDRyf5NHjziFJrepjxv9E4HtV9f2quhP4BHBcDzkkqUl93J1zP+DGaes3AX8wc6ckq4HVw9WfJ7lugePtDfxkgT/bh+WU925Z87Yek4xm2b62s1lir/eKem2Xkrxtp/I+dLaNfRR/ZtlW99hQtRZYu9ODJeuqampnn2dcllPe5ZQVllfe5ZQVllfe5ZQVusnbx6Gem4ADpq3vD9zSQw5JalIfxX858IgkBya5N/B84Es95JCkJo39UE9VbU3ySuDfgV2As6rqmg6H3OnDRWO2nPIup6ywvPIup6ywvPIup6zQQd5U3ePwuiRpBfPKXUlqjMUvSY1ZUcWf5KwktyXZMG3b45JckmR9knVJnthnxm3myPrYJBcnuTrJl5Pcv8+M0yU5IMk3kmxMck2SVw+3PzDJBUmuH35/wBLO+rzh+l1JlsTpfPNkfXuSa5N8O8nnk+zVc1Rg3rxvHmZdn+T8JA9ZqlmnPf66JJVk774yTjfPa3t6kpuHr+36JEfv9GBVtWK+gKcAhwIbpm07H3jGcPlo4MK+c86T9XLgsOHyCcCb+845Ldu+wKHD5T2B7zK45cY/AGuG29cAb1vCWR8FHARcCEz1nXM7WZ8O7Drc/ral8LpuJ+/9p+3zKuDMpZp1uH4AgxNMfgjs3XfW7by2pwOvW8yxVtSMv6ouAm6fuRnYNnP+XZbINQNzZD0IuGi4fAHw3LGGmkdV3VpVVw6X7wA2MrgK+zjg7OFuZwPP7iXgNHNlraqNVbXQK8A7MU/W86tq63C3Sxhc79K7efJumbbbfZnlosxxm+d3FuAM4PUsgZzbbCfvolpRxT+Hk4C3J7kReAdwSr9x5rUBOHa4/DzufqHbkpFkEjgEuBR4UFXdCoNfXGCfHqPdw4ysS9o8WU8Avjr2QNsxM2+Stwz/nb0AeFOP0e5hetYkxwI3V9W3+k01t1l+F145PJR21mIcTm2h+P8WeE1VHQC8Bvhwz3nmcwLwiiRXMPhT786e89xDkvsBnwVOmjHLW3JWQtYkpwJbgXP6yjab2fJW1anDf2fnAK/sM99007MyeC1PZYn9j2m6WV7b9wMPBx4H3Aq8c6cH6fu4VgfHySa5+3Hzn/Hb6xUCbOk741xZZzz2e8BlfWeckWk3BsdFXztt23XAvsPlfYHr+s45V9Zpj13IEjnGP19W4EXAxcAefWcc9bUdPv7QuX6v+84K/D5wG7Bp+LUVuAF4cN9ZR3xt5+yMHflqYcZ/C3DYcPlw4Poes8wryT7D7/cC3gic2W+i30oSBn8tbayqd0176EsMCorh9y+OO9tM82RdcubKmuQo4GTg2Kr6ZV/5Zpon7yOm7XYscO24s800W9aqurqq9qmqyaqaZHDvsEOr6kc9RgXmfW33nbbbcxgcEt65sYb/F1kRkpwLPJXBbVd/DJzGYEb6Hga3p/gf4OVVdUVfGbeZI+v9gFcMd/kccEotkf9ASZ4M/CdwNXDXcPMbGByD/BSwisHM6XlVNfNN67GaJ+vvAP8ITAD/Dayvqj/tI+M282R9L4O8Px1uu6SqXjb+hHc3T94TGZyccBeDM2VeVlU39xJyaK6sVfWVaftsYvDXX++3aZ7ntT2ewWGeYvBXyktr+L7agsdaIr0iSRqTFg71SJKmsfglqTEWvyQ1xuKXpMZY/JLUGItfkhpj8UtSY/4PGzY9WO2L4r4AAAAASUVORK5CYII=
                "style="
                    padding-left: 275px;
                ">
              </div>

            </div>

          </div>
        </div>

      </div>
      <div class="cell border-box-sizing code_cell rendered">
        <div class="input">
          <div class="prompt input_prompt"></div>
          <div></div>
        </div>

      </div>
    </div>
  </div>
</body>




</html>