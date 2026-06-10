# ddalfovo.github.io

<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">

<meta charset="utf-8">
<meta name="generator" content="quarto-1.7.32">

<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">

<meta name="description" content="Analysis of p53, p16, CD44, and CD98 expression shifts between Primary Tumors (PT) and Lymph Node (LN) Metastases, exploring their impact on locoregional control.">

<title>Untitled</title>
<style class="anchorjs"></style><style>
code{white-space: pre-wrap;}
span.smallcaps{font-variant: small-caps;}
div.columns{display: flex; gap: min(4vw, 1.5em);}
div.column{flex: auto; overflow-x: auto;}
div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
ul.task-list{list-style: none;}
ul.task-list li input[type="checkbox"] {
  width: 0.8em;
  margin: 0 0.8em 0.2em -1em; /* quarto-specific, see https://github.com/quarto-dev/quarto-cli/issues/4556 */ 
  vertical-align: middle;
}
</style>


<script src="results_files/clipboard.min.js"></script>
<script src="results_files/quarto.js" type="module"></script>
<script src="results_files/tabsets.js" type="module"></script>
<script src="results_files/popper.min.js"></script>
<script src="results_files/tippy.umd.min.js"></script>
<script src="results_files/anchor.min.js"></script>
<link href="results_files/tippy.css" rel="stylesheet">
<link href="results_files/quarto-syntax-highlighting-37eea08aefeeee20ff55810ff984fec1.css" rel="stylesheet" id="quarto-text-highlighting-styles">
<script src="results_files/bootstrap.min.js"></script>
<link href="results_files/bootstrap-icons.css" rel="stylesheet">
<link href="results_files/bootstrap-97dc76722f99607495a8425499d3bcba.min.css" rel="stylesheet" append-hash="true" id="quarto-bootstrap" data-mode="light">

  <script src="results_files/polyfill.min.js"></script>
  <script src="results_files/tex-chtml-full.js" type="text/javascript"></script><style type="text/css">.CtxtMenu_InfoClose {  top:.2em; right:.2em;}
.CtxtMenu_InfoContent {  overflow:auto; text-align:left; font-size:80%;  padding:.4em .6em; border:1px inset; margin:1em 0px;  max-height:20em; max-width:30em; background-color:#EEEEEE;  white-space:normal;}
.CtxtMenu_Info.CtxtMenu_MousePost {outline:none;}
.CtxtMenu_Info {  position:fixed; left:50%; width:auto; text-align:center;  border:3px outset; padding:1em 2em; background-color:#DDDDDD;  color:black;  cursor:default; font-family:message-box; font-size:120%;  font-style:normal; text-indent:0; text-transform:none;  line-height:normal; letter-spacing:normal; word-spacing:normal;  word-wrap:normal; white-space:nowrap; float:none; z-index:201;  border-radius: 15px;                     /* Opera 10.5 and IE9 */  -webkit-border-radius:15px;               /* Safari and Chrome */  -moz-border-radius:15px;                  /* Firefox */  -khtml-border-radius:15px;                /* Konqueror */  box-shadow:0px 10px 20px #808080;         /* Opera 10.5 and IE9 */  -webkit-box-shadow:0px 10px 20px #808080; /* Safari 3 & Chrome */  -moz-box-shadow:0px 10px 20px #808080;    /* Forefox 3.5 */  -khtml-box-shadow:0px 10px 20px #808080;  /* Konqueror */  filter:progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color="gray", Positive="true"); /* IE */}
</style><style type="text/css">.CtxtMenu_MenuClose {  position:absolute;  cursor:pointer;  display:inline-block;  border:2px solid #AAA;  border-radius:18px;  -webkit-border-radius: 18px;             /* Safari and Chrome */  -moz-border-radius: 18px;                /* Firefox */  -khtml-border-radius: 18px;              /* Konqueror */  font-family: "Courier New", Courier;  font-size:24px;  color:#F0F0F0}
.CtxtMenu_MenuClose span {  display:block; background-color:#AAA; border:1.5px solid;  border-radius:18px;  -webkit-border-radius: 18px;             /* Safari and Chrome */  -moz-border-radius: 18px;                /* Firefox */  -khtml-border-radius: 18px;              /* Konqueror */  line-height:0;  padding:8px 0 6px     /* may need to be browser-specific */}
.CtxtMenu_MenuClose:hover {  color:white!important;  border:2px solid #CCC!important}
.CtxtMenu_MenuClose:hover span {  background-color:#CCC!important}
.CtxtMenu_MenuClose:hover:focus {  outline:none}
</style><style type="text/css">.CtxtMenu_Menu {  position:absolute;  background-color:white;  color:black;  width:auto; padding:5px 0px;  border:1px solid #CCCCCC; margin:0; cursor:default;  font: menu; text-align:left; text-indent:0; text-transform:none;  line-height:normal; letter-spacing:normal; word-spacing:normal;  word-wrap:normal; white-space:nowrap; float:none; z-index:201;  border-radius: 5px;                     /* Opera 10.5 and IE9 */  -webkit-border-radius: 5px;             /* Safari and Chrome */  -moz-border-radius: 5px;                /* Firefox */  -khtml-border-radius: 5px;              /* Konqueror */  box-shadow:0px 10px 20px #808080;         /* Opera 10.5 and IE9 */  -webkit-box-shadow:0px 10px 20px #808080; /* Safari 3 & Chrome */  -moz-box-shadow:0px 10px 20px #808080;    /* Forefox 3.5 */  -khtml-box-shadow:0px 10px 20px #808080;  /* Konqueror */}
.CtxtMenu_MenuItem {  padding: 1px 2em;  background:transparent;}
.CtxtMenu_MenuArrow {  position:absolute; right:.5em; padding-top:.25em; color:#666666;  font-family: null; font-size: .75em}
.CtxtMenu_MenuActive .CtxtMenu_MenuArrow {color:white}
.CtxtMenu_MenuArrow.CtxtMenu_RTL {left:.5em; right:auto}
.CtxtMenu_MenuCheck {  position:absolute; left:.7em;  font-family: null}
.CtxtMenu_MenuCheck.CtxtMenu_RTL { right:.7em; left:auto }
.CtxtMenu_MenuRadioCheck {  position:absolute; left: .7em;}
.CtxtMenu_MenuRadioCheck.CtxtMenu_RTL {  right: .7em; left:auto}
.CtxtMenu_MenuInputBox {  padding-left: 1em; right:.5em; color:#666666;  font-family: null;}
.CtxtMenu_MenuInputBox.CtxtMenu_RTL {  left: .1em;}
.CtxtMenu_MenuComboBox {  left:.1em; padding-bottom:.5em;}
.CtxtMenu_MenuSlider {  left: .1em;}
.CtxtMenu_SliderValue {  position:absolute; right:.1em; padding-top:.25em; color:#333333;  font-size: .75em}
.CtxtMenu_SliderBar {  outline: none; background: #d3d3d3}
.CtxtMenu_MenuLabel {  padding: 1px 2em 3px 1.33em;  font-style:italic}
.CtxtMenu_MenuRule {  border-top: 1px solid #DDDDDD;  margin: 4px 3px;}
.CtxtMenu_MenuDisabled {  color:GrayText}
.CtxtMenu_MenuActive {  background-color: #606872;  color: white;}
.CtxtMenu_MenuDisabled:focus {  background-color: #E8E8E8}
.CtxtMenu_MenuLabel:focus {  background-color: #E8E8E8}
.CtxtMenu_ContextMenu:focus {  outline:none}
.CtxtMenu_ContextMenu .CtxtMenu_MenuItem:focus {  outline:none}
.CtxtMenu_SelectionMenu {  position:relative; float:left;  border-bottom: none; -webkit-box-shadow:none; -webkit-border-radius:0px; }
.CtxtMenu_SelectionItem {  padding-right: 1em;}
.CtxtMenu_Selection {  right: 40%; width:50%; }
.CtxtMenu_SelectionBox {  padding: 0em; max-height:20em; max-width: none;  background-color:#FFFFFF;}
.CtxtMenu_SelectionDivider {  clear: both; border-top: 2px solid #000000;}
.CtxtMenu_Menu .CtxtMenu_MenuClose {  top:-10px; left:-10px}
</style>

<script type="text/javascript">
const typesetMath = (el) => {
  if (window.MathJax) {
    // MathJax Typeset
    window.MathJax.typeset([el]);
  } else if (window.katex) {
    // KaTeX Render
    var mathElements = el.getElementsByClassName("math");
    var macros = [];
    for (var i = 0; i < mathElements.length; i++) {
      var texText = mathElements[i].firstChild;
      if (mathElements[i].tagName == "SPAN") {
        window.katex.render(texText.data, mathElements[i], {
          displayMode: mathElements[i].classList.contains('display'),
          throwOnError: false,
          macros: macros,
          fleqn: false
        });
      }
    }
  }
}
window.Quarto = {
  typesetMath
};
</script>

<style id="MJX-CHTML-styles">
mjx-container[jax="CHTML"] {
  line-height: 0;
}

mjx-container [space="1"] {
  margin-left: .111em;
}

mjx-container [space="2"] {
  margin-left: .167em;
}

mjx-container [space="3"] {
  margin-left: .222em;
}

mjx-container [space="4"] {
  margin-left: .278em;
}

mjx-container [space="5"] {
  margin-left: .333em;
}

mjx-container [rspace="1"] {
  margin-right: .111em;
}

mjx-container [rspace="2"] {
  margin-right: .167em;
}

mjx-container [rspace="3"] {
  margin-right: .222em;
}

mjx-container [rspace="4"] {
  margin-right: .278em;
}

mjx-container [rspace="5"] {
  margin-right: .333em;
}

mjx-container [size="s"] {
  font-size: 70.7%;
}

mjx-container [size="ss"] {
  font-size: 50%;
}

mjx-container [size="Tn"] {
  font-size: 60%;
}

mjx-container [size="sm"] {
  font-size: 85%;
}

mjx-container [size="lg"] {
  font-size: 120%;
}

mjx-container [size="Lg"] {
  font-size: 144%;
}

mjx-container [size="LG"] {
  font-size: 173%;
}

mjx-container [size="hg"] {
  font-size: 207%;
}

mjx-container [size="HG"] {
  font-size: 249%;
}

mjx-container [width="full"] {
  width: 100%;
}

mjx-box {
  display: inline-block;
}

mjx-block {
  display: block;
}

mjx-itable {
  display: inline-table;
}

mjx-row {
  display: table-row;
}

mjx-row > * {
  display: table-cell;
}

mjx-mtext {
  display: inline-block;
}

mjx-mstyle {
  display: inline-block;
}

mjx-merror {
  display: inline-block;
  color: red;
  background-color: yellow;
}

mjx-mphantom {
  visibility: hidden;
}

_::-webkit-full-page-media, _:future, :root mjx-container {
  will-change: opacity;
}

mjx-assistive-mml {
  position: absolute !important;
  top: 0px;
  left: 0px;
  clip: rect(1px, 1px, 1px, 1px);
  padding: 1px 0px 0px 0px !important;
  border: 0px !important;
  display: block !important;
  width: auto !important;
  overflow: hidden !important;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

mjx-assistive-mml[display="block"] {
  width: 100% !important;
}

mjx-math {
  display: inline-block;
  text-align: left;
  line-height: 0;
  text-indent: 0;
  font-style: normal;
  font-weight: normal;
  font-size: 100%;
  font-size-adjust: none;
  letter-spacing: normal;
  border-collapse: collapse;
  word-wrap: normal;
  word-spacing: normal;
  white-space: nowrap;
  direction: ltr;
  padding: 1px 0;
}

mjx-container[jax="CHTML"][display="true"] {
  display: block;
  text-align: center;
  margin: 1em 0;
}

mjx-container[jax="CHTML"][display="true"][width="full"] {
  display: flex;
}

mjx-container[jax="CHTML"][display="true"] mjx-math {
  padding: 0;
}

mjx-container[jax="CHTML"][justify="left"] {
  text-align: left;
}

mjx-container[jax="CHTML"][justify="right"] {
  text-align: right;
}

mjx-msup {
  display: inline-block;
  text-align: left;
}

mjx-mi {
  display: inline-block;
  text-align: left;
}

mjx-c {
  display: inline-block;
}

mjx-utext {
  display: inline-block;
  padding: .75em 0 .2em 0;
}

mjx-mn {
  display: inline-block;
  text-align: left;
}

mjx-c::before {
  display: block;
  width: 0;
}

.MJX-TEX {
  font-family: MJXZERO, MJXTEX;
}

.TEX-B {
  font-family: MJXZERO, MJXTEX-B;
}

.TEX-I {
  font-family: MJXZERO, MJXTEX-I;
}

.TEX-MI {
  font-family: MJXZERO, MJXTEX-MI;
}

.TEX-BI {
  font-family: MJXZERO, MJXTEX-BI;
}

.TEX-S1 {
  font-family: MJXZERO, MJXTEX-S1;
}

.TEX-S2 {
  font-family: MJXZERO, MJXTEX-S2;
}

.TEX-S3 {
  font-family: MJXZERO, MJXTEX-S3;
}

.TEX-S4 {
  font-family: MJXZERO, MJXTEX-S4;
}

.TEX-A {
  font-family: MJXZERO, MJXTEX-A;
}

.TEX-C {
  font-family: MJXZERO, MJXTEX-C;
}

.TEX-CB {
  font-family: MJXZERO, MJXTEX-CB;
}

.TEX-FR {
  font-family: MJXZERO, MJXTEX-FR;
}

.TEX-FRB {
  font-family: MJXZERO, MJXTEX-FRB;
}

.TEX-SS {
  font-family: MJXZERO, MJXTEX-SS;
}

.TEX-SSB {
  font-family: MJXZERO, MJXTEX-SSB;
}

.TEX-SSI {
  font-family: MJXZERO, MJXTEX-SSI;
}

.TEX-SC {
  font-family: MJXZERO, MJXTEX-SC;
}

.TEX-T {
  font-family: MJXZERO, MJXTEX-T;
}

.TEX-V {
  font-family: MJXZERO, MJXTEX-V;
}

.TEX-VB {
  font-family: MJXZERO, MJXTEX-VB;
}

mjx-stretchy-v mjx-c, mjx-stretchy-h mjx-c {
  font-family: MJXZERO, MJXTEX-S1, MJXTEX-S4, MJXTEX, MJXTEX-A ! important;
}

@font-face /* 0 */ {
  font-family: MJXZERO;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Zero.woff") format("woff");
}

@font-face /* 1 */ {
  font-family: MJXTEX;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Main-Regular.woff") format("woff");
}

@font-face /* 2 */ {
  font-family: MJXTEX-B;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Main-Bold.woff") format("woff");
}

@font-face /* 3 */ {
  font-family: MJXTEX-I;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Math-Italic.woff") format("woff");
}

@font-face /* 4 */ {
  font-family: MJXTEX-MI;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Main-Italic.woff") format("woff");
}

@font-face /* 5 */ {
  font-family: MJXTEX-BI;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Math-BoldItalic.woff") format("woff");
}

@font-face /* 6 */ {
  font-family: MJXTEX-S1;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Size1-Regular.woff") format("woff");
}

@font-face /* 7 */ {
  font-family: MJXTEX-S2;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Size2-Regular.woff") format("woff");
}

@font-face /* 8 */ {
  font-family: MJXTEX-S3;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Size3-Regular.woff") format("woff");
}

@font-face /* 9 */ {
  font-family: MJXTEX-S4;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Size4-Regular.woff") format("woff");
}

@font-face /* 10 */ {
  font-family: MJXTEX-A;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_AMS-Regular.woff") format("woff");
}

@font-face /* 11 */ {
  font-family: MJXTEX-C;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Calligraphic-Regular.woff") format("woff");
}

@font-face /* 12 */ {
  font-family: MJXTEX-CB;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Calligraphic-Bold.woff") format("woff");
}

@font-face /* 13 */ {
  font-family: MJXTEX-FR;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Fraktur-Regular.woff") format("woff");
}

@font-face /* 14 */ {
  font-family: MJXTEX-FRB;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Fraktur-Bold.woff") format("woff");
}

@font-face /* 15 */ {
  font-family: MJXTEX-SS;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_SansSerif-Regular.woff") format("woff");
}

@font-face /* 16 */ {
  font-family: MJXTEX-SSB;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_SansSerif-Bold.woff") format("woff");
}

@font-face /* 17 */ {
  font-family: MJXTEX-SSI;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_SansSerif-Italic.woff") format("woff");
}

@font-face /* 18 */ {
  font-family: MJXTEX-SC;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Script-Regular.woff") format("woff");
}

@font-face /* 19 */ {
  font-family: MJXTEX-T;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Typewriter-Regular.woff") format("woff");
}

@font-face /* 20 */ {
  font-family: MJXTEX-V;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Vector-Regular.woff") format("woff");
}

@font-face /* 21 */ {
  font-family: MJXTEX-VB;
  src: url("https://cdn.jsdelivr.net/npm/mathjax@3/es5/output/chtml/fonts/woff-v2/MathJax_Vector-Bold.woff") format("woff");
}

mjx-c.mjx-c1D445.TEX-I::before {
  padding: 0.683em 0.759em 0.021em 0;
  content: "R";
}

mjx-c.mjx-c32::before {
  padding: 0.666em 0.5em 0 0;
  content: "2";
}
</style></head>

<body class="fullcontent quarto-light">

<div id="quarto-content" class="page-columns page-rows-contents page-layout-article">

<main class="content" id="quarto-document-content">

<header id="title-block-header" class="quarto-title-block default">
<div class="quarto-title">
<h1 class="title">Untitled</h1>
</div>

<div>
  <div class="description">
    Analysis of p53, p16, CD44, and CD98 expression shifts between 
Primary Tumors (PT) and Lymph Node (LN) Metastases, exploring their 
impact on locoregional control.
  </div>
</div>


<div class="quarto-title-meta">

    
  
    
  </div>
  


</header>


<div class="callout callout-style-default callout-tip callout-titled">
<div class="callout-header d-flex align-content-center">
<div class="callout-icon-container">
<i class="callout-icon"></i>
</div>
<div class="callout-title-container flex-fill">
Note on Metrics Used:
</div>
</div>
<div class="callout-body-container callout-body">
<p>Before detailing the results, it is important to clarify the scoring 
metrics used to evaluate the immunohistochemical data. The primary 
metric across all analyses is Biomarker Expression (the percentage of 
positive cells). We also utilized the H-score, a composite metric 
calculated by multiplying the expression percentage by the staining 
intensity. While the comprehensive statistical pipeline was executed for
 standard expression, supplementary analyses utilizing the H-score are 
also presented alongside these findings to provide a complete view of 
protein abundance.</p>
</div>
</div>
<section id="data-integration-preprocessing" class="level1">
<h1>1. Data Integration &amp; Preprocessing</h1>
<p>This phase consolidates raw Excel data from multiple cohorts, 
standardizes biomarker measurements (Expression %, Intensity, and 
H-Score), and merges clinical outcomes. Crucially, we deduplicate 
Primary Tumor (PT) entries to ensure a precise 1:N mapping with Lymph 
Node (LN) metastases.</p>
<div class="cell">
<div class="cell-output cell-output-stdout">
<pre><code>Final harmonized cohort:</code></pre>
</div>
<div class="cell-output cell-output-stdout">
<pre><code>Total patients: 208 </code></pre>
</div>
<div class="cell-output cell-output-stdout">
<pre><code>Total LN samples (unaggregated): 647 </code></pre>
</div>
<div class="cell-output cell-output-stdout">
<pre><code>Total rows in paired dataset (LN-PT): 647 </code></pre>
</div>
</div>
</section>
<section id="cohort-statistics" class="level1">
<h1>2. Cohort Statistics</h1>
<section id="dataset-distribution" class="level3">
<h3 class="anchored" data-anchor-id="dataset-distribution">Dataset Distribution:<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#dataset-distribution" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table class="caption-top table">
<thead>
<tr class="header">
<th style="text-align: left;">dataset</th>
<th style="text-align: right;">Patients</th>
<th style="text-align: right;">Metastases</th>
<th style="text-align: right;">Ratio</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">DKTKRO1a</td>
<td style="text-align: right;">35</td>
<td style="text-align: right;">132</td>
<td style="text-align: right;">3.77</td>
</tr>
<tr class="even">
<td style="text-align: left;">DKTKRO2a</td>
<td style="text-align: right;">60</td>
<td style="text-align: right;">252</td>
<td style="text-align: right;">4.20</td>
</tr>
<tr class="odd">
<td style="text-align: left;">FK</td>
<td style="text-align: right;">25</td>
<td style="text-align: right;">121</td>
<td style="text-align: right;">4.84</td>
</tr>
<tr class="even">
<td style="text-align: left;">HNLOR</td>
<td style="text-align: right;">88</td>
<td style="text-align: right;">142</td>
<td style="text-align: right;">1.61</td>
</tr>
</tbody>
</table>
</section>
<section id="t-distribution" class="level3">
<h3 class="anchored" data-anchor-id="t-distribution">T Distribution:<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#t-distribution" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table class="caption-top table">
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: right;">1</th>
<th style="text-align: right;">2</th>
<th style="text-align: right;">3</th>
<th style="text-align: right;">4</th>
<th style="text-align: right;">4a</th>
<th style="text-align: right;">5</th>
<th style="text-align: right;">6</th>
<th style="text-align: right;">NA</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">DKTKRO1a</td>
<td style="text-align: right;">6</td>
<td style="text-align: right;">13</td>
<td style="text-align: right;">9</td>
<td style="text-align: right;">6</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
</tr>
<tr class="even">
<td style="text-align: left;">DKTKRO2a</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">11</td>
<td style="text-align: right;">23</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">8</td>
<td style="text-align: right;">13</td>
<td style="text-align: right;">5</td>
</tr>
<tr class="odd">
<td style="text-align: left;">FK</td>
<td style="text-align: right;">8</td>
<td style="text-align: right;">10</td>
<td style="text-align: right;">5</td>
<td style="text-align: right;">2</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
</tr>
<tr class="even">
<td style="text-align: left;">HNLOR</td>
<td style="text-align: right;">5</td>
<td style="text-align: right;">26</td>
<td style="text-align: right;">9</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">48</td>
</tr>
</tbody>
</table>
</section>
<section id="inter-rater-reliability-al-vs-ib" class="level3">
<h3 class="anchored" data-anchor-id="inter-rater-reliability-al-vs-ib">Inter-Rater Reliability: AL vs IB<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#inter-rater-reliability-al-vs-ib" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table class="caption-top table">
<caption>Overlap and Agreement (ICC/Correlation) between Rater AL and Rater IB</caption>
<thead>
<tr class="header">
<th style="text-align: left;">Marker</th>
<th style="text-align: left;">Metric</th>
<th style="text-align: right;">Both_Scored</th>
<th style="text-align: right;">Only_AL</th>
<th style="text-align: right;">Only_IB</th>
<th style="text-align: right;">Correlation</th>
<th style="text-align: right;">ICC</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">p53</td>
<td style="text-align: left;">%</td>
<td style="text-align: right;">860</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">6</td>
<td style="text-align: right;">0.976</td>
<td style="text-align: right;">0.975</td>
</tr>
<tr class="even">
<td style="text-align: left;">p53</td>
<td style="text-align: left;">i</td>
<td style="text-align: right;">860</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">6</td>
<td style="text-align: right;">0.910</td>
<td style="text-align: right;">0.917</td>
</tr>
<tr class="odd">
<td style="text-align: left;">p16</td>
<td style="text-align: left;">%</td>
<td style="text-align: right;">858</td>
<td style="text-align: right;">8</td>
<td style="text-align: right;">15</td>
<td style="text-align: right;">0.990</td>
<td style="text-align: right;">0.990</td>
</tr>
<tr class="even">
<td style="text-align: left;">p16</td>
<td style="text-align: left;">i</td>
<td style="text-align: right;">858</td>
<td style="text-align: right;">8</td>
<td style="text-align: right;">15</td>
<td style="text-align: right;">0.872</td>
<td style="text-align: right;">0.879</td>
</tr>
<tr class="odd">
<td style="text-align: left;">CD44</td>
<td style="text-align: left;">%</td>
<td style="text-align: right;">861</td>
<td style="text-align: right;">2</td>
<td style="text-align: right;">4</td>
<td style="text-align: right;">0.933</td>
<td style="text-align: right;">0.915</td>
</tr>
<tr class="even">
<td style="text-align: left;">CD44</td>
<td style="text-align: left;">i</td>
<td style="text-align: right;">862</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">4</td>
<td style="text-align: right;">0.877</td>
<td style="text-align: right;">0.873</td>
</tr>
<tr class="odd">
<td style="text-align: left;">CD98</td>
<td style="text-align: left;">%</td>
<td style="text-align: right;">863</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">6</td>
<td style="text-align: right;">0.955</td>
<td style="text-align: right;">0.951</td>
</tr>
<tr class="even">
<td style="text-align: left;">CD98</td>
<td style="text-align: left;">i</td>
<td style="text-align: right;">863</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">6</td>
<td style="text-align: right;">0.907</td>
<td style="text-align: right;">0.867</td>
</tr>
</tbody>
</table>
</section>
</section>
<section id="tumormetastasis-biomarker-comparison" class="level1">
<h1>3. Tumor–Metastasis Biomarker Comparison</h1>
<p>We assess whether biomarker levels change significantly when shifting from the Primary Tumor to Lymph Node metastases.</p>
<section id="linear-mixed-effects-model-lmm" class="level2">
<h2 class="anchored" data-anchor-id="linear-mixed-effects-model-lmm">3.1 Linear Mixed-Effects Model (LMM)<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#linear-mixed-effects-model-lmm" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<p>This approach handles multiple LN samples per patient by including a 
random intercept for each patient. We test if the “Tissue Type” (PT vs 
LN) is a significant predictor of marker levels.</p>
<table class="caption-top table">
<caption>LMM: Testing LN vs PT shift across all markers</caption>
<colgroup>
<col style="width: 15%">
<col style="width: 15%">
<col style="width: 13%">
<col style="width: 16%">
<col style="width: 13%">
<col style="width: 12%">
<col style="width: 12%">
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: left;">Marker</th>
<th style="text-align: right;">Estimate</th>
<th style="text-align: right;">Std. Error</th>
<th style="text-align: right;">df</th>
<th style="text-align: right;">t value</th>
<th style="text-align: right;">P_Value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">p53_h</td>
<td style="text-align: left;">p53_h</td>
<td style="text-align: right;">1.5060</td>
<td style="text-align: right;">3.2723</td>
<td style="text-align: right;">649.6683</td>
<td style="text-align: right;">0.4602</td>
<td style="text-align: right;">0.6455</td>
</tr>
<tr class="even">
<td style="text-align: left;">p16_h</td>
<td style="text-align: left;">p16_h</td>
<td style="text-align: right;">1.2366</td>
<td style="text-align: right;">2.2177</td>
<td style="text-align: right;">643.3075</td>
<td style="text-align: right;">0.5576</td>
<td style="text-align: right;">0.5773</td>
</tr>
<tr class="odd">
<td style="text-align: left;">CD44_h</td>
<td style="text-align: left;">CD44_h</td>
<td style="text-align: right;">-0.6229</td>
<td style="text-align: right;">3.0001</td>
<td style="text-align: right;">690.1405</td>
<td style="text-align: right;">-0.2076</td>
<td style="text-align: right;">0.8356</td>
</tr>
<tr class="even">
<td style="text-align: left;">CD98_h</td>
<td style="text-align: left;">CD98_h</td>
<td style="text-align: right;">4.1703</td>
<td style="text-align: right;">3.9454</td>
<td style="text-align: right;">663.4918</td>
<td style="text-align: right;">1.0570</td>
<td style="text-align: right;">0.2909</td>
</tr>
<tr class="odd">
<td style="text-align: left;">p53_expr</td>
<td style="text-align: left;">p53_expr</td>
<td style="text-align: right;">0.0696</td>
<td style="text-align: right;">1.2071</td>
<td style="text-align: right;">650.4469</td>
<td style="text-align: right;">0.0576</td>
<td style="text-align: right;">0.9541</td>
</tr>
<tr class="even">
<td style="text-align: left;">p16_expr</td>
<td style="text-align: left;">p16_expr</td>
<td style="text-align: right;">0.6230</td>
<td style="text-align: right;">0.6416</td>
<td style="text-align: right;">642.4793</td>
<td style="text-align: right;">0.9710</td>
<td style="text-align: right;">0.3319</td>
</tr>
<tr class="odd">
<td style="text-align: left;">CD44_expr</td>
<td style="text-align: left;">CD44_expr</td>
<td style="text-align: right;">-0.2107</td>
<td style="text-align: right;">1.3162</td>
<td style="text-align: right;">683.8260</td>
<td style="text-align: right;">-0.1601</td>
<td style="text-align: right;">0.8729</td>
</tr>
<tr class="even">
<td style="text-align: left;">CD98_expr</td>
<td style="text-align: left;">CD98_expr</td>
<td style="text-align: right;">2.1736</td>
<td style="text-align: right;">1.4094</td>
<td style="text-align: right;">666.3025</td>
<td style="text-align: right;">1.5422</td>
<td style="text-align: right;">0.1235</td>
</tr>
</tbody>
</table>
</section>
<section id="extended-mixed-models-using-latent-classes-lcmm" class="level2">
<h2 class="anchored" data-anchor-id="extended-mixed-models-using-latent-classes-lcmm">3.2 Extended Mixed Models Using Latent Classes (LCMM)<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#extended-mixed-models-using-latent-classes-lcmm" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<p>The objective of this analysis was to determine whether biomarker 
expression follows distinct evolutionary patterns during the transition 
from primary tumor to lymph node metastasis. Because metastatic 
progression is unlikely to be biologically uniform across all patients, 
we applied Latent Class Mixed Models (LCMM) to identify groups of 
patients with similar expression trajectories. By jointly analyzing both
 expression percentage and staining intensity, and accounting for 
repeated samples from the same patient, this approach can uncover 
specific subpopulations exhibiting significant biomarker gains or losses
 that may not be apparent in conventional population-level analyses.</p>
<section id="p53-trajectory" class="level3">
<h3 class="anchored" data-anchor-id="p53-trajectory">p53 Trajectory<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#p53-trajectory" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<section id="information-criteria-entropy-bic-and-aic" class="level4">
<h4 class="anchored" data-anchor-id="information-criteria-entropy-bic-and-aic">Information Criteria (entropy, BIC and AIC)<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#information-criteria-entropy-bic-and-aic" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<table class="caption-top table table-sm table-striped small">
<caption>Model Fit Comparison: 2 to 6 Clusters</caption>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: right;">AIC</th>
<th style="text-align: right;">BIC</th>
<th style="text-align: right;">entropy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">m2_multi_cov</td>
<td style="text-align: right;">9447.79</td>
<td style="text-align: right;">9481.17</td>
<td style="text-align: right;">0.98</td>
</tr>
<tr class="even">
<td style="text-align: left;">m3_multi_cov</td>
<td style="text-align: right;">9427.87</td>
<td style="text-align: right;">9471.26</td>
<td style="text-align: right;">0.97</td>
</tr>
<tr class="odd">
<td style="text-align: left;">m4_multi_cov</td>
<td style="text-align: right;">9372.95</td>
<td style="text-align: right;">9426.35</td>
<td style="text-align: right;">0.81</td>
</tr>
<tr class="even">
<td style="text-align: left;">m5_multi_cov</td>
<td style="text-align: right;">9345.25</td>
<td style="text-align: right;">9408.66</td>
<td style="text-align: right;">0.84</td>
</tr>
<tr class="odd">
<td style="text-align: left;">m6_multi_cov</td>
<td style="text-align: right;">9325.90</td>
<td style="text-align: right;">9399.32</td>
<td style="text-align: right;">0.91</td>
</tr>
</tbody>
</table>
</div>
</div>
</section>
<section id="selected-4-clusters" class="level4">
<h4 class="anchored" data-anchor-id="selected-4-clusters">Selected: 4 clusters<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#selected-4-clusters" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output cell-output-stdout">
<pre><code>                                     coef      Se   Wald p-value
intercept class1 (not estimated)  0.00000      NA     NA      NA
intercept class2                 -1.77106 0.97000 -1.826 0.06788
intercept class3                  1.66039 0.99203  1.674 0.09418
intercept class4                 -7.10732 1.15209 -6.169 0.00000
Tissue_Time class1               -5.65262 0.98882 -5.717 0.00000
Tissue_Time class2                0.43457 0.27753  1.566 0.11737
Tissue_Time class3                0.03652 0.22631  0.161 0.87179
Tissue_Time class4               -0.14200 0.30454 -0.466 0.64101</code></pre>
</div>
</div>
</section>
<section id="visualizing-the-multivariate-evolutionary-trajectories" class="level4">
<h4 class="anchored" data-anchor-id="visualizing-the-multivariate-evolutionary-trajectories">Visualizing the Multivariate Evolutionary Trajectories<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#visualizing-the-multivariate-evolutionary-trajectories" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<div>
<figure class="figure">
<p><img src="results_files/unnamed-chunk-7-1.png" class="img-fluid figure-img" width="960"></p>
</figure>
</div>
</div>
</div>
</section>
<section id="kaplan-meier-survival-by-multivariate-trajectory" class="level4">
<h4 class="anchored" data-anchor-id="kaplan-meier-survival-by-multivariate-trajectory">Kaplan-Meier Survival by Multivariate Trajectory<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#kaplan-meier-survival-by-multivariate-trajectory" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<div>
<figure class="figure">
<p><img src="results_files/unnamed-chunk-8-1.png" class="img-fluid figure-img" width="768"></p>
</figure>
</div>
</div>
</div>
<!-- #### Testing LCMM Clusters for Clinical Confounders -->
<div class="cell">
<div class="cell-output-display">
<div id="nytdvjrnxa" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#nytdvjrnxa table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nytdvjrnxa thead, #nytdvjrnxa tbody, #nytdvjrnxa tfoot, #nytdvjrnxa tr, #nytdvjrnxa td, #nytdvjrnxa th {
  border-style: none;
}

#nytdvjrnxa p {
  margin: 0;
  padding: 0;
}

#nytdvjrnxa .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#nytdvjrnxa .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#nytdvjrnxa .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#nytdvjrnxa .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#nytdvjrnxa .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#nytdvjrnxa .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#nytdvjrnxa .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#nytdvjrnxa .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#nytdvjrnxa .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#nytdvjrnxa .gt_spanner_row {
  border-bottom-style: hidden;
}

#nytdvjrnxa .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#nytdvjrnxa .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#nytdvjrnxa .gt_from_md > :first-child {
  margin-top: 0;
}

#nytdvjrnxa .gt_from_md > :last-child {
  margin-bottom: 0;
}

#nytdvjrnxa .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#nytdvjrnxa .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#nytdvjrnxa .gt_row_group_first td {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_row_group_first th {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#nytdvjrnxa .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#nytdvjrnxa .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#nytdvjrnxa .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_left {
  text-align: left;
}

#nytdvjrnxa .gt_center {
  text-align: center;
}

#nytdvjrnxa .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#nytdvjrnxa .gt_font_normal {
  font-weight: normal;
}

#nytdvjrnxa .gt_font_bold {
  font-weight: bold;
}

#nytdvjrnxa .gt_font_italic {
  font-style: italic;
}

#nytdvjrnxa .gt_super {
  font-size: 65%;
}

#nytdvjrnxa .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#nytdvjrnxa .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#nytdvjrnxa .gt_indent_1 {
  text-indent: 5px;
}

#nytdvjrnxa .gt_indent_2 {
  text-indent: 10px;
}

#nytdvjrnxa .gt_indent_3 {
  text-indent: 15px;
}

#nytdvjrnxa .gt_indent_4 {
  text-indent: 20px;
}

#nytdvjrnxa .gt_indent_5 {
  text-indent: 25px;
}

#nytdvjrnxa .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#nytdvjrnxa div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table caption-top table table-sm table-striped small" data-quarto-postprocess="true" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
<colgroup>
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
</colgroup>
<thead>
<tr class="gt_col_headings header">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left" data-quarto-table-cell-role="th" scope="col"><strong>Characteristic</strong></th>
<th id="stat_1" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 1</strong><br>
N = 9<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 2</strong><br>
N = 70<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_3" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 3</strong><br>
N = 84<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_4" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 4</strong><br>
N = 45<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>p-value</strong><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr class="odd">
<td class="gt_row gt_left" headers="label">Age</td>
<td class="gt_row gt_center" headers="stat_1">56 (52, 61)</td>
<td class="gt_row gt_center" headers="stat_2">58 (53, 66)</td>
<td class="gt_row gt_center" headers="stat_3">54 (49, 61)</td>
<td class="gt_row gt_center" headers="stat_4">57 (50, 64)</td>
<td class="gt_row gt_center" headers="p.value">0.12</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">T Stage</td>
<td class="gt_row gt_center" headers="stat_1"><br>
</td>
<td class="gt_row gt_center" headers="stat_2"><br>
</td>
<td class="gt_row gt_center" headers="stat_3"><br>
</td>
<td class="gt_row gt_center" headers="stat_4"><br>
</td>
<td class="gt_row gt_center" headers="p.value">0.8</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;High T (T3-T4)</td>
<td class="gt_row gt_center" headers="stat_1">3 (43%)</td>
<td class="gt_row gt_center" headers="stat_2">22 (51%)</td>
<td class="gt_row gt_center" headers="stat_3">28 (52%)</td>
<td class="gt_row gt_center" headers="stat_4">12 (41%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;Low T (T1-T2)</td>
<td class="gt_row gt_center" headers="stat_1">4 (57%)</td>
<td class="gt_row gt_center" headers="stat_2">21 (49%)</td>
<td class="gt_row gt_center" headers="stat_3">26 (48%)</td>
<td class="gt_row gt_center" headers="stat_4">17 (59%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">HPV Status</td>
<td class="gt_row gt_center" headers="stat_1"><br>
</td>
<td class="gt_row gt_center" headers="stat_2"><br>
</td>
<td class="gt_row gt_center" headers="stat_3"><br>
</td>
<td class="gt_row gt_center" headers="stat_4"><br>
</td>
<td class="gt_row gt_center" headers="p.value">0.002</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;HPV_Neg</td>
<td class="gt_row gt_center" headers="stat_1">2 (50%)</td>
<td class="gt_row gt_center" headers="stat_2">16 (34%)</td>
<td class="gt_row gt_center" headers="stat_3">30 (61%)</td>
<td class="gt_row gt_center" headers="stat_4">21 (75%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;HPV_Pos</td>
<td class="gt_row gt_center" headers="stat_1">2 (50%)</td>
<td class="gt_row gt_center" headers="stat_2">31 (66%)</td>
<td class="gt_row gt_center" headers="stat_3">19 (39%)</td>
<td class="gt_row gt_center" headers="stat_4">7 (25%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes odd">
<td colspan="6" class="gt_footnote"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span> Median (Q1, Q3); n (%)</td>
</tr>
<tr class="gt_footnotes even">
<td colspan="6" class="gt_footnote"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span> Kruskal-Wallis rank sum test; Fisher’s exact test</td>
</tr>
</tfoot>

</table>

</div>
</div>
</div>
</section>
</section>
<section id="p16-trajectory" class="level3">
<h3 class="anchored" data-anchor-id="p16-trajectory">p16 Trajectory<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#p16-trajectory" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<section id="information-criteria-entropy-bic-and-aic-1" class="level4">
<h4 class="anchored" data-anchor-id="information-criteria-entropy-bic-and-aic-1">Information Criteria (entropy, BIC and AIC)<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#information-criteria-entropy-bic-and-aic-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<table class="caption-top table table-sm table-striped small">
<caption>Model Fit Comparison: 2 to 6 Clusters</caption>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: right;">AIC</th>
<th style="text-align: right;">BIC</th>
<th style="text-align: right;">entropy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">m2_multi_cov</td>
<td style="text-align: right;">8375.60</td>
<td style="text-align: right;">8408.97</td>
<td style="text-align: right;">0.99</td>
</tr>
<tr class="even">
<td style="text-align: left;">m3_multi_cov</td>
<td style="text-align: right;">8357.52</td>
<td style="text-align: right;">8400.91</td>
<td style="text-align: right;">0.98</td>
</tr>
<tr class="odd">
<td style="text-align: left;">m4_multi_cov</td>
<td style="text-align: right;">7774.45</td>
<td style="text-align: right;">7827.85</td>
<td style="text-align: right;">1.00</td>
</tr>
<tr class="even">
<td style="text-align: left;">m5_multi_cov</td>
<td style="text-align: right;">7731.86</td>
<td style="text-align: right;">7795.27</td>
<td style="text-align: right;">1.00</td>
</tr>
<tr class="odd">
<td style="text-align: left;">m6_multi_cov</td>
<td style="text-align: right;">7737.86</td>
<td style="text-align: right;">7811.28</td>
<td style="text-align: right;">0.78</td>
</tr>
</tbody>
</table>
</div>
</div>
</section>
<section id="selected-4-clusters-1" class="level4">
<h4 class="anchored" data-anchor-id="selected-4-clusters-1">Selected: 4 clusters<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#selected-4-clusters-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output cell-output-stdout">
<pre><code>                                     coef      Se   Wald p-value
intercept class1 (not estimated)  0.00000      NA     NA      NA
intercept class2                  5.02343 0.97268  5.165 0.00000
intercept class3                 28.80719 3.52062  8.182 0.00000
intercept class4                 19.34039 2.51150  7.701 0.00000
Tissue_Time class1               -0.35332 0.21170 -1.669 0.09512
Tissue_Time class2               11.83322 1.61287  7.337 0.00000
Tissue_Time class3                0.58288 0.36970  1.577 0.11488
Tissue_Time class4               -7.27974 1.17043 -6.220 0.00000</code></pre>
</div>
</div>
</section>
<section id="visualizing-the-multivariate-evolutionary-trajectories-1" class="level4">
<h4 class="anchored" data-anchor-id="visualizing-the-multivariate-evolutionary-trajectories-1">Visualizing the Multivariate Evolutionary Trajectories<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#visualizing-the-multivariate-evolutionary-trajectories-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<div>
<figure class="figure">
<p><img src="results_files/unnamed-chunk-17-1.png" class="img-fluid figure-img" width="960"></p>
</figure>
</div>
</div>
</div>
</section>
<section id="kaplan-meier-survival-by-multivariate-trajectory-1" class="level4">
<h4 class="anchored" data-anchor-id="kaplan-meier-survival-by-multivariate-trajectory-1">Kaplan-Meier Survival by Multivariate Trajectory<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#kaplan-meier-survival-by-multivariate-trajectory-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<div>
<figure class="figure">
<p><img src="results_files/unnamed-chunk-18-1.png" class="img-fluid figure-img" width="768"></p>
</figure>
</div>
</div>
</div>
<div class="cell">
<div class="cell-output-display">
<div id="nytdvjrnxa" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#nytdvjrnxa table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nytdvjrnxa thead, #nytdvjrnxa tbody, #nytdvjrnxa tfoot, #nytdvjrnxa tr, #nytdvjrnxa td, #nytdvjrnxa th {
  border-style: none;
}

#nytdvjrnxa p {
  margin: 0;
  padding: 0;
}

#nytdvjrnxa .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#nytdvjrnxa .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#nytdvjrnxa .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#nytdvjrnxa .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#nytdvjrnxa .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#nytdvjrnxa .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#nytdvjrnxa .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#nytdvjrnxa .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#nytdvjrnxa .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#nytdvjrnxa .gt_spanner_row {
  border-bottom-style: hidden;
}

#nytdvjrnxa .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#nytdvjrnxa .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#nytdvjrnxa .gt_from_md > :first-child {
  margin-top: 0;
}

#nytdvjrnxa .gt_from_md > :last-child {
  margin-bottom: 0;
}

#nytdvjrnxa .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#nytdvjrnxa .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#nytdvjrnxa .gt_row_group_first td {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_row_group_first th {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#nytdvjrnxa .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#nytdvjrnxa .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#nytdvjrnxa .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_left {
  text-align: left;
}

#nytdvjrnxa .gt_center {
  text-align: center;
}

#nytdvjrnxa .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#nytdvjrnxa .gt_font_normal {
  font-weight: normal;
}

#nytdvjrnxa .gt_font_bold {
  font-weight: bold;
}

#nytdvjrnxa .gt_font_italic {
  font-style: italic;
}

#nytdvjrnxa .gt_super {
  font-size: 65%;
}

#nytdvjrnxa .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#nytdvjrnxa .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#nytdvjrnxa .gt_indent_1 {
  text-indent: 5px;
}

#nytdvjrnxa .gt_indent_2 {
  text-indent: 10px;
}

#nytdvjrnxa .gt_indent_3 {
  text-indent: 15px;
}

#nytdvjrnxa .gt_indent_4 {
  text-indent: 20px;
}

#nytdvjrnxa .gt_indent_5 {
  text-indent: 25px;
}

#nytdvjrnxa .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#nytdvjrnxa div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table caption-top table table-sm table-striped small" data-quarto-postprocess="true" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
<colgroup>
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
</colgroup>
<thead>
<tr class="gt_col_headings header">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left" data-quarto-table-cell-role="th" scope="col"><strong>Characteristic</strong></th>
<th id="stat_1" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 1</strong><br>
N = 140<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 2</strong><br>
N = 10<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_3" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 3</strong><br>
N = 50<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_4" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 4</strong><br>
N = 8<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>p-value</strong><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr class="odd">
<td class="gt_row gt_left" headers="label">Age</td>
<td class="gt_row gt_center" headers="stat_1">55 (49, 61)</td>
<td class="gt_row gt_center" headers="stat_2">59 (50, 65)</td>
<td class="gt_row gt_center" headers="stat_3">60 (52, 66)</td>
<td class="gt_row gt_center" headers="stat_4">60 (53, 64)</td>
<td class="gt_row gt_center" headers="p.value">0.11</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">T Stage</td>
<td class="gt_row gt_center" headers="stat_1"><br>
</td>
<td class="gt_row gt_center" headers="stat_2"><br>
</td>
<td class="gt_row gt_center" headers="stat_3"><br>
</td>
<td class="gt_row gt_center" headers="stat_4"><br>
</td>
<td class="gt_row gt_center" headers="p.value">&gt;0.9</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;High T (T3-T4)</td>
<td class="gt_row gt_center" headers="stat_1">47 (48%)</td>
<td class="gt_row gt_center" headers="stat_2">5 (63%)</td>
<td class="gt_row gt_center" headers="stat_3">11 (46%)</td>
<td class="gt_row gt_center" headers="stat_4">2 (50%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;Low T (T1-T2)</td>
<td class="gt_row gt_center" headers="stat_1">50 (52%)</td>
<td class="gt_row gt_center" headers="stat_2">3 (38%)</td>
<td class="gt_row gt_center" headers="stat_3">13 (54%)</td>
<td class="gt_row gt_center" headers="stat_4">2 (50%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">HPV Status</td>
<td class="gt_row gt_center" headers="stat_1"><br>
</td>
<td class="gt_row gt_center" headers="stat_2"><br>
</td>
<td class="gt_row gt_center" headers="stat_3"><br>
</td>
<td class="gt_row gt_center" headers="stat_4"><br>
</td>
<td class="gt_row gt_center" headers="p.value">&lt;0.001</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;HPV_Neg</td>
<td class="gt_row gt_center" headers="stat_1">61 (90%)</td>
<td class="gt_row gt_center" headers="stat_2">3 (43%)</td>
<td class="gt_row gt_center" headers="stat_3">0 (0%)</td>
<td class="gt_row gt_center" headers="stat_4">5 (83%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;HPV_Pos</td>
<td class="gt_row gt_center" headers="stat_1">7 (10%)</td>
<td class="gt_row gt_center" headers="stat_2">4 (57%)</td>
<td class="gt_row gt_center" headers="stat_3">47 (100%)</td>
<td class="gt_row gt_center" headers="stat_4">1 (17%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes odd">
<td colspan="6" class="gt_footnote"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span> Median (Q1, Q3); n (%)</td>
</tr>
<tr class="gt_footnotes even">
<td colspan="6" class="gt_footnote"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span> Kruskal-Wallis rank sum test; Fisher’s exact test</td>
</tr>
</tfoot>

</table>

</div>
</div>
</div>
</section>
</section>
<section id="cd44-trajectory" class="level3">
<h3 class="anchored" data-anchor-id="cd44-trajectory">CD44 Trajectory<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#cd44-trajectory" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<section id="information-criteria-entropy-bic-and-aic-2" class="level4">
<h4 class="anchored" data-anchor-id="information-criteria-entropy-bic-and-aic-2">Information Criteria (entropy, BIC and AIC)<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#information-criteria-entropy-bic-and-aic-2" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<table class="caption-top table table-sm table-striped small">
<caption>Model Fit Comparison: 2 to 6 Clusters</caption>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: right;">AIC</th>
<th style="text-align: right;">BIC</th>
<th style="text-align: right;">entropy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">m2_multi_cov</td>
<td style="text-align: right;">9080.39</td>
<td style="text-align: right;">9113.76</td>
<td style="text-align: right;">0.66</td>
</tr>
<tr class="even">
<td style="text-align: left;">m3_multi_cov</td>
<td style="text-align: right;">9048.81</td>
<td style="text-align: right;">9092.20</td>
<td style="text-align: right;">0.75</td>
</tr>
<tr class="odd">
<td style="text-align: left;">m4_multi_cov</td>
<td style="text-align: right;">9007.85</td>
<td style="text-align: right;">9061.25</td>
<td style="text-align: right;">0.81</td>
</tr>
<tr class="even">
<td style="text-align: left;">m5_multi_cov</td>
<td style="text-align: right;">9013.85</td>
<td style="text-align: right;">9077.26</td>
<td style="text-align: right;">0.67</td>
</tr>
<tr class="odd">
<td style="text-align: left;">m6_multi_cov</td>
<td style="text-align: right;">9019.85</td>
<td style="text-align: right;">9093.27</td>
<td style="text-align: right;">0.70</td>
</tr>
</tbody>
</table>
</div>
</div>
</section>
<section id="selected-4-clusters-2" class="level4">
<h4 class="anchored" data-anchor-id="selected-4-clusters-2">Selected: 4 clusters<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#selected-4-clusters-2" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output cell-output-stdout">
<pre><code>                                     coef      Se   Wald p-value
intercept class1 (not estimated)  0.00000      NA     NA      NA
intercept class2                 -4.90407 0.77773 -6.306 0.00000
intercept class3                 -4.94284 0.63137 -7.829 0.00000
intercept class4                  0.60441 0.47617  1.269 0.20433
Tissue_Time class1               -3.78615 0.50727 -7.464 0.00000
Tissue_Time class2                5.21829 0.78102  6.681 0.00000
Tissue_Time class3                0.46228 0.25517  1.812 0.07004
Tissue_Time class4               -0.03679 0.24728 -0.149 0.88173</code></pre>
</div>
</div>
</section>
<section id="visualizing-the-multivariate-evolutionary-trajectories-2" class="level4">
<h4 class="anchored" data-anchor-id="visualizing-the-multivariate-evolutionary-trajectories-2">Visualizing the Multivariate Evolutionary Trajectories<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#visualizing-the-multivariate-evolutionary-trajectories-2" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<div>
<figure class="figure">
<p><img src="results_files/unnamed-chunk-27-1.png" class="img-fluid figure-img" width="960"></p>
</figure>
</div>
</div>
</div>
</section>
<section id="kaplan-meier-survival-by-multivariate-trajectory-2" class="level4">
<h4 class="anchored" data-anchor-id="kaplan-meier-survival-by-multivariate-trajectory-2">Kaplan-Meier Survival by Multivariate Trajectory<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#kaplan-meier-survival-by-multivariate-trajectory-2" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<div>
<figure class="figure">
<p><img src="results_files/unnamed-chunk-28-1.png" class="img-fluid figure-img" width="768"></p>
</figure>
</div>
</div>
</div>
<div class="cell">
<div class="cell-output-display">
<div id="nytdvjrnxa" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#nytdvjrnxa table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nytdvjrnxa thead, #nytdvjrnxa tbody, #nytdvjrnxa tfoot, #nytdvjrnxa tr, #nytdvjrnxa td, #nytdvjrnxa th {
  border-style: none;
}

#nytdvjrnxa p {
  margin: 0;
  padding: 0;
}

#nytdvjrnxa .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#nytdvjrnxa .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#nytdvjrnxa .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#nytdvjrnxa .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#nytdvjrnxa .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#nytdvjrnxa .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#nytdvjrnxa .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#nytdvjrnxa .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#nytdvjrnxa .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#nytdvjrnxa .gt_spanner_row {
  border-bottom-style: hidden;
}

#nytdvjrnxa .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#nytdvjrnxa .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#nytdvjrnxa .gt_from_md > :first-child {
  margin-top: 0;
}

#nytdvjrnxa .gt_from_md > :last-child {
  margin-bottom: 0;
}

#nytdvjrnxa .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#nytdvjrnxa .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#nytdvjrnxa .gt_row_group_first td {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_row_group_first th {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#nytdvjrnxa .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#nytdvjrnxa .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#nytdvjrnxa .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_left {
  text-align: left;
}

#nytdvjrnxa .gt_center {
  text-align: center;
}

#nytdvjrnxa .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#nytdvjrnxa .gt_font_normal {
  font-weight: normal;
}

#nytdvjrnxa .gt_font_bold {
  font-weight: bold;
}

#nytdvjrnxa .gt_font_italic {
  font-style: italic;
}

#nytdvjrnxa .gt_super {
  font-size: 65%;
}

#nytdvjrnxa .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#nytdvjrnxa .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#nytdvjrnxa .gt_indent_1 {
  text-indent: 5px;
}

#nytdvjrnxa .gt_indent_2 {
  text-indent: 10px;
}

#nytdvjrnxa .gt_indent_3 {
  text-indent: 15px;
}

#nytdvjrnxa .gt_indent_4 {
  text-indent: 20px;
}

#nytdvjrnxa .gt_indent_5 {
  text-indent: 25px;
}

#nytdvjrnxa .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#nytdvjrnxa div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table caption-top table table-sm table-striped small" data-quarto-postprocess="true" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
<colgroup>
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
</colgroup>
<thead>
<tr class="gt_col_headings header">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left" data-quarto-table-cell-role="th" scope="col"><strong>Characteristic</strong></th>
<th id="stat_1" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 1</strong><br>
N = 39<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 2</strong><br>
N = 16<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_3" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 3</strong><br>
N = 82<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_4" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 4</strong><br>
N = 71<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>p-value</strong><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr class="odd">
<td class="gt_row gt_left" headers="label">Age</td>
<td class="gt_row gt_center" headers="stat_1">57 (52, 63)</td>
<td class="gt_row gt_center" headers="stat_2">53 (47, 59)</td>
<td class="gt_row gt_center" headers="stat_3">57 (50, 65)</td>
<td class="gt_row gt_center" headers="stat_4">55 (51, 64)</td>
<td class="gt_row gt_center" headers="p.value">0.3</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">T Stage</td>
<td class="gt_row gt_center" headers="stat_1"><br>
</td>
<td class="gt_row gt_center" headers="stat_2"><br>
</td>
<td class="gt_row gt_center" headers="stat_3"><br>
</td>
<td class="gt_row gt_center" headers="stat_4"><br>
</td>
<td class="gt_row gt_center" headers="p.value">0.13</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;High T (T3-T4)</td>
<td class="gt_row gt_center" headers="stat_1">17 (57%)</td>
<td class="gt_row gt_center" headers="stat_2">3 (33%)</td>
<td class="gt_row gt_center" headers="stat_3">22 (39%)</td>
<td class="gt_row gt_center" headers="stat_4">23 (61%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;Low T (T1-T2)</td>
<td class="gt_row gt_center" headers="stat_1">13 (43%)</td>
<td class="gt_row gt_center" headers="stat_2">6 (67%)</td>
<td class="gt_row gt_center" headers="stat_3">34 (61%)</td>
<td class="gt_row gt_center" headers="stat_4">15 (39%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">HPV Status</td>
<td class="gt_row gt_center" headers="stat_1"><br>
</td>
<td class="gt_row gt_center" headers="stat_2"><br>
</td>
<td class="gt_row gt_center" headers="stat_3"><br>
</td>
<td class="gt_row gt_center" headers="stat_4"><br>
</td>
<td class="gt_row gt_center" headers="p.value">0.018</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;HPV_Neg</td>
<td class="gt_row gt_center" headers="stat_1">16 (64%)</td>
<td class="gt_row gt_center" headers="stat_2">3 (50%)</td>
<td class="gt_row gt_center" headers="stat_3">24 (40%)</td>
<td class="gt_row gt_center" headers="stat_4">26 (70%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;HPV_Pos</td>
<td class="gt_row gt_center" headers="stat_1">9 (36%)</td>
<td class="gt_row gt_center" headers="stat_2">3 (50%)</td>
<td class="gt_row gt_center" headers="stat_3">36 (60%)</td>
<td class="gt_row gt_center" headers="stat_4">11 (30%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes odd">
<td colspan="6" class="gt_footnote"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span> Median (Q1, Q3); n (%)</td>
</tr>
<tr class="gt_footnotes even">
<td colspan="6" class="gt_footnote"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span> Kruskal-Wallis rank sum test; Fisher’s exact test</td>
</tr>
</tfoot>

</table>

</div>
</div>
</div>
</section>
</section>
<section id="cd98-trajectory" class="level3">
<h3 class="anchored" data-anchor-id="cd98-trajectory">CD98 Trajectory<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#cd98-trajectory" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<section id="information-criteria-entropy-bic-and-aic-3" class="level4">
<h4 class="anchored" data-anchor-id="information-criteria-entropy-bic-and-aic-3">Information Criteria (entropy, BIC and AIC)<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#information-criteria-entropy-bic-and-aic-3" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<table class="caption-top table table-sm table-striped small">
<caption>Model Fit Comparison: 2 to 6 Clusters</caption>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: right;">AIC</th>
<th style="text-align: right;">BIC</th>
<th style="text-align: right;">entropy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">m2_multi_cov</td>
<td style="text-align: right;">9164.54</td>
<td style="text-align: right;">9197.91</td>
<td style="text-align: right;">0.63</td>
</tr>
<tr class="even">
<td style="text-align: left;">m3_multi_cov</td>
<td style="text-align: right;">9167.66</td>
<td style="text-align: right;">9211.05</td>
<td style="text-align: right;">0.48</td>
</tr>
<tr class="odd">
<td style="text-align: left;">m4_multi_cov</td>
<td style="text-align: right;">9161.63</td>
<td style="text-align: right;">9215.03</td>
<td style="text-align: right;">0.70</td>
</tr>
<tr class="even">
<td style="text-align: left;">m5_multi_cov</td>
<td style="text-align: right;">9158.90</td>
<td style="text-align: right;">9222.31</td>
<td style="text-align: right;">0.68</td>
</tr>
<tr class="odd">
<td style="text-align: left;">m6_multi_cov</td>
<td style="text-align: right;">9162.93</td>
<td style="text-align: right;">9236.36</td>
<td style="text-align: right;">0.61</td>
</tr>
</tbody>
</table>
</div>
</div>
</section>
<section id="selected-4-clusters-3" class="level4">
<h4 class="anchored" data-anchor-id="selected-4-clusters-3">Selected: 4 clusters<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#selected-4-clusters-3" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output cell-output-stdout">
<pre><code>                                     coef      Se   Wald p-value
intercept class1 (not estimated)  0.00000      NA     NA      NA
intercept class2                  5.79826 1.54435  3.755 0.00017
intercept class3                 -1.91037 1.68330 -1.135 0.25642
intercept class4                  3.77791 1.00695  3.752 0.00018
Tissue_Time class1               -1.46018 0.61803 -2.363 0.01815
Tissue_Time class2                0.57385 0.28492  2.014 0.04400
Tissue_Time class3                4.28452 1.83388  2.336 0.01948
Tissue_Time class4               -0.87635 0.46271 -1.894 0.05823</code></pre>
</div>
</div>
</section>
<section id="visualizing-the-multivariate-evolutionary-trajectories-3" class="level4">
<h4 class="anchored" data-anchor-id="visualizing-the-multivariate-evolutionary-trajectories-3">Visualizing the Multivariate Evolutionary Trajectories<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#visualizing-the-multivariate-evolutionary-trajectories-3" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<div>
<figure class="figure">
<p><img src="results_files/unnamed-chunk-37-1.png" class="img-fluid figure-img" width="960"></p>
</figure>
</div>
</div>
</div>
</section>
<section id="kaplan-meier-survival-by-multivariate-trajectory-3" class="level4">
<h4 class="anchored" data-anchor-id="kaplan-meier-survival-by-multivariate-trajectory-3">Kaplan-Meier Survival by Multivariate Trajectory<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#kaplan-meier-survival-by-multivariate-trajectory-3" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<div class="cell">
<div class="cell-output-display">
<div>
<figure class="figure">
<p><img src="results_files/unnamed-chunk-38-1.png" class="img-fluid figure-img" width="768"></p>
</figure>
</div>
</div>
</div>
<div class="cell">
<div class="cell-output-display">
<div id="nytdvjrnxa" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#nytdvjrnxa table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nytdvjrnxa thead, #nytdvjrnxa tbody, #nytdvjrnxa tfoot, #nytdvjrnxa tr, #nytdvjrnxa td, #nytdvjrnxa th {
  border-style: none;
}

#nytdvjrnxa p {
  margin: 0;
  padding: 0;
}

#nytdvjrnxa .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#nytdvjrnxa .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#nytdvjrnxa .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#nytdvjrnxa .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#nytdvjrnxa .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#nytdvjrnxa .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#nytdvjrnxa .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#nytdvjrnxa .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#nytdvjrnxa .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#nytdvjrnxa .gt_spanner_row {
  border-bottom-style: hidden;
}

#nytdvjrnxa .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#nytdvjrnxa .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#nytdvjrnxa .gt_from_md > :first-child {
  margin-top: 0;
}

#nytdvjrnxa .gt_from_md > :last-child {
  margin-bottom: 0;
}

#nytdvjrnxa .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#nytdvjrnxa .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#nytdvjrnxa .gt_row_group_first td {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_row_group_first th {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#nytdvjrnxa .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#nytdvjrnxa .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#nytdvjrnxa .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#nytdvjrnxa .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#nytdvjrnxa .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#nytdvjrnxa .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#nytdvjrnxa .gt_left {
  text-align: left;
}

#nytdvjrnxa .gt_center {
  text-align: center;
}

#nytdvjrnxa .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#nytdvjrnxa .gt_font_normal {
  font-weight: normal;
}

#nytdvjrnxa .gt_font_bold {
  font-weight: bold;
}

#nytdvjrnxa .gt_font_italic {
  font-style: italic;
}

#nytdvjrnxa .gt_super {
  font-size: 65%;
}

#nytdvjrnxa .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#nytdvjrnxa .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#nytdvjrnxa .gt_indent_1 {
  text-indent: 5px;
}

#nytdvjrnxa .gt_indent_2 {
  text-indent: 10px;
}

#nytdvjrnxa .gt_indent_3 {
  text-indent: 15px;
}

#nytdvjrnxa .gt_indent_4 {
  text-indent: 20px;
}

#nytdvjrnxa .gt_indent_5 {
  text-indent: 25px;
}

#nytdvjrnxa .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#nytdvjrnxa div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>

<table class="gt_table caption-top table table-sm table-striped small" data-quarto-postprocess="true" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
<colgroup>
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
<col style="width: 16%">
</colgroup>
<thead>
<tr class="gt_col_headings header">
<th id="label" class="gt_col_heading gt_columns_bottom_border gt_left" data-quarto-table-cell-role="th" scope="col"><strong>Characteristic</strong></th>
<th id="stat_1" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 1</strong><br>
N = 26<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_2" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 2</strong><br>
N = 104<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_3" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 3</strong><br>
N = 8<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="stat_4" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>Class 4</strong><br>
N = 70<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span></th>
<th id="p.value" class="gt_col_heading gt_columns_bottom_border gt_center" data-quarto-table-cell-role="th" scope="col"><strong>p-value</strong><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span></th>
</tr>
</thead>
<tbody class="gt_table_body">
<tr class="odd">
<td class="gt_row gt_left" headers="label">Age</td>
<td class="gt_row gt_center" headers="stat_1">61 (52, 64)</td>
<td class="gt_row gt_center" headers="stat_2">55 (48, 61)</td>
<td class="gt_row gt_center" headers="stat_3">62 (58, 66)</td>
<td class="gt_row gt_center" headers="stat_4">56 (51, 66)</td>
<td class="gt_row gt_center" headers="p.value">0.031</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">T Stage</td>
<td class="gt_row gt_center" headers="stat_1"><br>
</td>
<td class="gt_row gt_center" headers="stat_2"><br>
</td>
<td class="gt_row gt_center" headers="stat_3"><br>
</td>
<td class="gt_row gt_center" headers="stat_4"><br>
</td>
<td class="gt_row gt_center" headers="p.value">0.061</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;High T (T3-T4)</td>
<td class="gt_row gt_center" headers="stat_1">2 (15%)</td>
<td class="gt_row gt_center" headers="stat_2">36 (52%)</td>
<td class="gt_row gt_center" headers="stat_3">2 (67%)</td>
<td class="gt_row gt_center" headers="stat_4">25 (52%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;Low T (T1-T2)</td>
<td class="gt_row gt_center" headers="stat_1">11 (85%)</td>
<td class="gt_row gt_center" headers="stat_2">33 (48%)</td>
<td class="gt_row gt_center" headers="stat_3">1 (33%)</td>
<td class="gt_row gt_center" headers="stat_4">23 (48%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">HPV Status</td>
<td class="gt_row gt_center" headers="stat_1"><br>
</td>
<td class="gt_row gt_center" headers="stat_2"><br>
</td>
<td class="gt_row gt_center" headers="stat_3"><br>
</td>
<td class="gt_row gt_center" headers="stat_4"><br>
</td>
<td class="gt_row gt_center" headers="p.value">&lt;0.001</td>
</tr>
<tr class="even">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;HPV_Neg</td>
<td class="gt_row gt_center" headers="stat_1">1 (5.0%)</td>
<td class="gt_row gt_center" headers="stat_2">38 (75%)</td>
<td class="gt_row gt_center" headers="stat_3">1 (17%)</td>
<td class="gt_row gt_center" headers="stat_4">29 (57%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
<tr class="odd">
<td class="gt_row gt_left" headers="label">&nbsp;&nbsp;&nbsp;&nbsp;HPV_Pos</td>
<td class="gt_row gt_center" headers="stat_1">19 (95%)</td>
<td class="gt_row gt_center" headers="stat_2">13 (25%)</td>
<td class="gt_row gt_center" headers="stat_3">5 (83%)</td>
<td class="gt_row gt_center" headers="stat_4">22 (43%)</td>
<td class="gt_row gt_center" headers="p.value"><br>
</td>
</tr>
</tbody><tfoot>
<tr class="gt_footnotes odd">
<td colspan="6" class="gt_footnote"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>1</sup></span> Median (Q1, Q3); n (%)</td>
</tr>
<tr class="gt_footnotes even">
<td colspan="6" class="gt_footnote"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;line-height:0;"><sup>2</sup></span> Kruskal-Wallis rank sum test; Fisher’s exact test</td>
</tr>
</tfoot>

</table>

</div>
</div>
</div>
</section>
</section>
</section>
<section id="discordance-rate" class="level2">
<h2 class="anchored" data-anchor-id="discordance-rate">Discordance rate<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#discordance-rate" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<div class="cell">
<div class="cell-output cell-output-stdout">
<pre><code>     Marker   N Percent
p53     p53   9    4.33
p16     p16  18    8.65
CD44   CD44  55   26.44
CD98   CD98 138   66.35</code></pre>
</div>
<div class="cell-output cell-output-stdout">
<pre><code>
Global results:</code></pre>
</div>
<div class="cell-output cell-output-stdout">
<pre><code>Unique patients = 165 </code></pre>
</div>
<div class="cell-output cell-output-stdout">
<pre><code>Percent = 79.33 %</code></pre>
</div>
</div>
</section>
<section id="takeaway-biomarker-expression-exhibits-high-inter-patient-instability-rather-than-a-uniform-directional-shift." class="level2">
<h2 class="anchored" data-anchor-id="takeaway-biomarker-expression-exhibits-high-inter-patient-instability-rather-than-a-uniform-directional-shift.">3. Takeaway: Biomarker expression exhibits high inter-patient instability rather than a uniform directional shift.<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#takeaway-biomarker-expression-exhibits-high-inter-patient-instability-rather-than-a-uniform-directional-shift." style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<p>The multivariate latent class mixed model simultaneously incorporates
 both biomarker expression percentage and staining intensity, allowing 
the identification of patient subgroups that share similar evolutionary 
trajectories during metastatic progression for each of the markers 
considered. This approach reveals substantial heterogeneity in biomarker
 evolution across patients. The analysis identified distinct trajectory 
classes characterized by different patterns of expression. Patients from
 statistically significant clusters are identified as Discordant 
(different expression of the marker between PT and LN).</p>
</section>
</section>
<section id="metastatic-co-evolution" class="level1">
<h1>5. Metastatic Co-Evolution</h1>
<p>We investigate whether the evaluated biomarkers adapt independently 
during metastasis, or if they co-evolve as coupled biological pathways. 
To capture this evolutionary transition, we modeled the exact 
mathematical shift (the delta) of each marker between the Primary Tumor 
and its paired Lymph Node metastasis using Linear Mixed-Effects Models.</p>
<p>This approach isolates the active process of metastatic seeding, 
answering the question: If a specific marker significantly increases or 
decreases during the transition to the lymph node, does another marker 
predictably shift alongside it? Identifying these coupled adaptations 
can highlight shared biological drivers or coordinated resistance 
mechanisms in the metastatic niche.</p>
<section id="mixed-models-on-metastatic-shifts" class="level2">
<h2 class="anchored" data-anchor-id="mixed-models-on-metastatic-shifts">5.1 Mixed Models on Metastatic Shifts<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#mixed-models-on-metastatic-shifts" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<section id="mixed-model-predicting-cd98-shift-via-cd44-shift" class="level3">
<h3 class="anchored" data-anchor-id="mixed-model-predicting-cd98-shift-via-cd44-shift">Mixed Model: Predicting CD98 Shift via CD44 Shift<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#mixed-model-predicting-cd98-shift-via-cd44-shift" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table>
<thead>
<tr>
<th style="empty-cells: hide;border-bottom:hidden;" colspan="1">
</th>
<th style="border-bottom:hidden;padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="3">
<div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">
CD98 Shift (LN - PT)
</div>
</th>
</tr>
<tr>
<th style="text-align:left;">
Predictors
</th>
<th style="text-align:left;">
Estimates
</th>
<th style="text-align:left;">
CI
</th>
<th style="text-align:left;">
p
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
(Intercept)
</td>
<td style="text-align:left;">
1.93
</td>
<td style="text-align:left;">
-1.12&nbsp;–&nbsp;4.99
</td>
<td style="text-align:left;">
0.215
</td>
</tr>
<tr>
<td style="text-align:left;">
CD44 Shift
</td>
<td style="text-align:left;">
0.15
</td>
<td style="text-align:left;">
0.07&nbsp;–&nbsp;0.23
</td>
<td style="text-align:left;">
&lt;0.001
</td>
</tr>
<tr>
<td style="text-align:left;">
Random Effects
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
σ2
</td>
<td style="text-align:left;">
245.34
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
τ00patient_ID
</td>
<td style="text-align:left;">
362.93
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
ICC
</td>
<td style="text-align:left;">
0.60
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
N patient_ID
</td>
<td style="text-align:left;">
205
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Observations
</td>
<td style="text-align:left;">
633
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Marginal <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="0"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span> / Conditional <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="1"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span>
</td>
<td style="text-align:left;">
0.019 / 0.604
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>
<p><img src="results_files/coevo-lmm-1.png" class="img-fluid" width="672"></p>
<p><br></p>
</section>
<section id="mixed-model-predicting-p53-shift-via-p16-shift" class="level3">
<h3 class="anchored" data-anchor-id="mixed-model-predicting-p53-shift-via-p16-shift">Mixed Model: Predicting p53 Shift via p16 Shift<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#mixed-model-predicting-p53-shift-via-p16-shift" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table>
<thead>
<tr>
<th style="empty-cells: hide;border-bottom:hidden;" colspan="1">
</th>
<th style="border-bottom:hidden;padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="3">
<div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">
p53 Shift (LN - PT)
</div>
</th>
</tr>
<tr>
<th style="text-align:left;">
Predictors
</th>
<th style="text-align:left;">
Estimates
</th>
<th style="text-align:left;">
CI
</th>
<th style="text-align:left;">
p
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
(Intercept)
</td>
<td style="text-align:left;">
-0.08
</td>
<td style="text-align:left;">
-3.10&nbsp;–&nbsp;2.94
</td>
<td style="text-align:left;">
0.957
</td>
</tr>
<tr>
<td style="text-align:left;">
p16 Shift
</td>
<td style="text-align:left;">
0.03
</td>
<td style="text-align:left;">
-0.11&nbsp;–&nbsp;0.18
</td>
<td style="text-align:left;">
0.681
</td>
</tr>
<tr>
<td style="text-align:left;">
Random Effects
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
σ2
</td>
<td style="text-align:left;">
143.16
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
τ00patient_ID
</td>
<td style="text-align:left;">
398.66
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
ICC
</td>
<td style="text-align:left;">
0.74
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
N patient_ID
</td>
<td style="text-align:left;">
203
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Observations
</td>
<td style="text-align:left;">
630
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Marginal <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="2"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span> / Conditional <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="3"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span>
</td>
<td style="text-align:left;">
0.000 / 0.736
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>
<p><img src="results_files/coevo-lmm-2.png" class="img-fluid" width="672"></p>
<p><br></p>
</section>
<section id="mixed-model-predicting-p16-shift-via-cd98-shift" class="level3">
<h3 class="anchored" data-anchor-id="mixed-model-predicting-p16-shift-via-cd98-shift">Mixed Model: Predicting p16 Shift via CD98 Shift<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#mixed-model-predicting-p16-shift-via-cd98-shift" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table>
<thead>
<tr>
<th style="empty-cells: hide;border-bottom:hidden;" colspan="1">
</th>
<th style="border-bottom:hidden;padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="3">
<div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">
p16 Shift (LN - PT)
</div>
</th>
</tr>
<tr>
<th style="text-align:left;">
Predictors
</th>
<th style="text-align:left;">
Estimates
</th>
<th style="text-align:left;">
CI
</th>
<th style="text-align:left;">
p
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
(Intercept)
</td>
<td style="text-align:left;">
0.64
</td>
<td style="text-align:left;">
-0.98&nbsp;–&nbsp;2.27
</td>
<td style="text-align:left;">
0.437
</td>
</tr>
<tr>
<td style="text-align:left;">
CD98 Shift
</td>
<td style="text-align:left;">
0.02
</td>
<td style="text-align:left;">
-0.01&nbsp;–&nbsp;0.06
</td>
<td style="text-align:left;">
0.164
</td>
</tr>
<tr>
<td style="text-align:left;">
Random Effects
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
σ2
</td>
<td style="text-align:left;">
41.48
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
τ00patient_ID
</td>
<td style="text-align:left;">
117.44
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
ICC
</td>
<td style="text-align:left;">
0.74
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
N patient_ID
</td>
<td style="text-align:left;">
205
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Observations
</td>
<td style="text-align:left;">
634
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Marginal <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="4"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span> / Conditional <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="5"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span>
</td>
<td style="text-align:left;">
0.002 / 0.740
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>
<p><img src="results_files/coevo-lmm-3.png" class="img-fluid" width="672"></p>
<p><br></p>
</section>
<section id="mixed-model-predicting-p53-shift-via-cd98-shift" class="level3">
<h3 class="anchored" data-anchor-id="mixed-model-predicting-p53-shift-via-cd98-shift">Mixed Model: Predicting p53 Shift via CD98 Shift<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#mixed-model-predicting-p53-shift-via-cd98-shift" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table>
<thead>
<tr>
<th style="empty-cells: hide;border-bottom:hidden;" colspan="1">
</th>
<th style="border-bottom:hidden;padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="3">
<div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">
p53 Shift (LN - PT)
</div>
</th>
</tr>
<tr>
<th style="text-align:left;">
Predictors
</th>
<th style="text-align:left;">
Estimates
</th>
<th style="text-align:left;">
CI
</th>
<th style="text-align:left;">
p
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
(Intercept)
</td>
<td style="text-align:left;">
-0.16
</td>
<td style="text-align:left;">
-3.12&nbsp;–&nbsp;2.79
</td>
<td style="text-align:left;">
0.915
</td>
</tr>
<tr>
<td style="text-align:left;">
CD98 Shift
</td>
<td style="text-align:left;">
0.06
</td>
<td style="text-align:left;">
-0.01&nbsp;–&nbsp;0.12
</td>
<td style="text-align:left;">
0.081
</td>
</tr>
<tr>
<td style="text-align:left;">
Random Effects
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
σ2
</td>
<td style="text-align:left;">
143.87
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
τ00patient_ID
</td>
<td style="text-align:left;">
382.30
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
ICC
</td>
<td style="text-align:left;">
0.73
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
N patient_ID
</td>
<td style="text-align:left;">
205
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Observations
</td>
<td style="text-align:left;">
632
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Marginal <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="6"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span> / Conditional <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="7"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span>
</td>
<td style="text-align:left;">
0.004 / 0.728
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>
<p><img src="results_files/coevo-lmm-4.png" class="img-fluid" width="672"></p>
<p><br></p>
</section>
<section id="mixed-model-predicting-p16-shift-via-cd44-shift" class="level3">
<h3 class="anchored" data-anchor-id="mixed-model-predicting-p16-shift-via-cd44-shift">Mixed Model: Predicting p16 Shift via CD44 Shift<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#mixed-model-predicting-p16-shift-via-cd44-shift" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table>
<thead>
<tr>
<th style="empty-cells: hide;border-bottom:hidden;" colspan="1">
</th>
<th style="border-bottom:hidden;padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="3">
<div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">
p16 Shift (LN - PT)
</div>
</th>
</tr>
<tr>
<th style="text-align:left;">
Predictors
</th>
<th style="text-align:left;">
Estimates
</th>
<th style="text-align:left;">
CI
</th>
<th style="text-align:left;">
p
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
(Intercept)
</td>
<td style="text-align:left;">
0.61
</td>
<td style="text-align:left;">
-1.00&nbsp;–&nbsp;2.22
</td>
<td style="text-align:left;">
0.455
</td>
</tr>
<tr>
<td style="text-align:left;">
CD44 Shift
</td>
<td style="text-align:left;">
0.04
</td>
<td style="text-align:left;">
0.00&nbsp;–&nbsp;0.08
</td>
<td style="text-align:left;">
0.027
</td>
</tr>
<tr>
<td style="text-align:left;">
Random Effects
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
σ2
</td>
<td style="text-align:left;">
41.59
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
τ00patient_ID
</td>
<td style="text-align:left;">
112.40
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
ICC
</td>
<td style="text-align:left;">
0.73
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
N patient_ID
</td>
<td style="text-align:left;">
203
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Observations
</td>
<td style="text-align:left;">
630
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Marginal <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="8"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span> / Conditional <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="9"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span>
</td>
<td style="text-align:left;">
0.006 / 0.731
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>
<p><img src="results_files/coevo-lmm-5.png" class="img-fluid" width="672"></p>
<p><br></p>
</section>
<section id="mixed-model-predicting-p53-shift-via-cd44-shift" class="level3">
<h3 class="anchored" data-anchor-id="mixed-model-predicting-p53-shift-via-cd44-shift">Mixed Model: Predicting p53 Shift via CD44 Shift<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#mixed-model-predicting-p53-shift-via-cd44-shift" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<table>
<thead>
<tr>
<th style="empty-cells: hide;border-bottom:hidden;" colspan="1">
</th>
<th style="border-bottom:hidden;padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="3">
<div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">
p53 Shift (LN - PT)
</div>
</th>
</tr>
<tr>
<th style="text-align:left;">
Predictors
</th>
<th style="text-align:left;">
Estimates
</th>
<th style="text-align:left;">
CI
</th>
<th style="text-align:left;">
p
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
(Intercept)
</td>
<td style="text-align:left;">
-0.02
</td>
<td style="text-align:left;">
-3.00&nbsp;–&nbsp;2.95
</td>
<td style="text-align:left;">
0.987
</td>
</tr>
<tr>
<td style="text-align:left;">
CD44 Shift
</td>
<td style="text-align:left;">
0.06
</td>
<td style="text-align:left;">
-0.01&nbsp;–&nbsp;0.13
</td>
<td style="text-align:left;">
0.089
</td>
</tr>
<tr>
<td style="text-align:left;">
Random Effects
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
σ2
</td>
<td style="text-align:left;">
142.82
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
τ00patient_ID
</td>
<td style="text-align:left;">
390.34
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
ICC
</td>
<td style="text-align:left;">
0.73
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
N patient_ID
</td>
<td style="text-align:left;">
205
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Observations
</td>
<td style="text-align:left;">
632
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
Marginal <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="10"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span> / Conditional <span class="math inline"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" style="font-size: 117.1%; position: relative;" tabindex="0" ctxtmenu_counter="11"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msup><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D445 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: 0.363em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c32"></mjx-c></mjx-mn></mjx-script></mjx-msup></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>R</mi><mn>2</mn></msup></math></mjx-assistive-mml></mjx-container></span>
</td>
<td style="text-align:left;">
0.003 / 0.733
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>
<p><img src="results_files/coevo-lmm-6.png" class="img-fluid" width="672"></p>
<p><br></p>
</section>
</section>
<section id="takeaway-biomarkers-evolve-in-coupled-not-in-isolation." class="level2">
<h2 class="anchored" data-anchor-id="takeaway-biomarkers-evolve-in-coupled-not-in-isolation.">5. Takeaway: Biomarkers evolve in coupled, not in isolation.<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#takeaway-biomarkers-evolve-in-coupled-not-in-isolation." style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<p>The mixed-shift models demonstrate significant co-evolutionary 
dynamics, most notably between CD44 and CD98. Rather than adapting 
independently, when CD44 expression shifts during metastasis, CD98 
shifts in a predictable, correlated direction. This coupled adaptation 
points toward shared regulatory networks in the metastatic environment, 
suggesting that these proteins may be driven by similar environmental 
pressures or represent joint therapeutic vulnerabilities. Statistically 
significant also the shift betwwen p16 andCD44 expression shift.</p>
</section>
</section>
<section id="prognostic-impact-recurrence-analysis" class="level1">
<h1>6. Prognostic Impact (Recurrence Analysis)</h1>
<p>We evaluate the prognostic relevance of biomarker expression on LRC. 
To account for underlying baseline differences between the original 
patient groups, all survival models are stratified by the cohort of 
origin. For models evaluating Lymph Node (LN) metastases, a robust 
variance estimator (patient-level clustering) is included to account for
 intra-patient correlation when multiple nodes are present.</p>
<p>The evaluation strategy is tailored to the nature of each biomarker:</p>
<ul>
<li><p>Established Clinical Markers (p16 &amp; p53): Evaluated across 
the pooled cohort using strict, predefined clinical thresholds (≥ 70% 
for p16 as an HPV surrogate; established mutation archetypes for p53).</p></li>
<li><p>Exploratory Biomarkers (CD44 &amp; CD98): Evaluated using a two-step hybrid approach:</p>
<ul>
<li>Continuous Analysis (Pooled Cohort): The markers are first evaluated
 continuously across all available samples to establish robust 
biological associations without the bias of threshold selection.</li>
<li>Categorical Validation (Discovery/Validation Split): To provide 
clinically actionable thresholds, an optimal cut-off is mathematically 
derived strictly within a discovery subset (DKTKRO2a). This derived 
threshold is then independently tested in a distinct validation cohort 
(DKTKRO1a, FK, HNLOR) to confirm its prognostic utility and avoid 
overfitting.</li>
</ul></li>
</ul>
<section id="primary-tumor-pt-survival-analysis" class="level3">
<h3 class="anchored" data-anchor-id="primary-tumor-pt-survival-analysis">6.1 Primary Tumor (PT) Survival Analysis<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#primary-tumor-pt-survival-analysis" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<section id="pt-survival-analysis-p53" class="level4">
<h4 class="anchored" data-anchor-id="pt-survival-analysis-p53">PT Survival Analysis: p53<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#pt-survival-analysis-p53" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Using mutation archetypes: Wild-Type (6-79%) vs Aberrant (&lt;=5% or &gt;=80%) on Pooled Cohort</p>
<table class="caption-top table">
<caption>PT Biological p53 Archetypes</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupAberrant_Pattern</td>
<td style="text-align: right;">0.661</td>
<td style="text-align: right;">0.339</td>
<td style="text-align: right;">-1.224</td>
<td style="text-align: right;">0.221</td>
</tr>
</tbody>
</table>
</section>
<section id="pt-survival-analysis-p16" class="level4">
<h4 class="anchored" data-anchor-id="pt-survival-analysis-p16">PT Survival Analysis: p16<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#pt-survival-analysis-p16" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Using clinical cut-off: &gt;= 70% (HPV surrogate) on Pooled Cohort</p>
<table class="caption-top table">
<caption>PT Clinical p16 (70% cut-off)</caption>
<colgroup>
<col style="width: 44%">
<col style="width: 13%">
<col style="width: 14%">
<col style="width: 14%">
<col style="width: 11%">
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupLow/Negative (&lt;70%)</td>
<td style="text-align: right;">8.799</td>
<td style="text-align: right;">0.731</td>
<td style="text-align: right;">2.974</td>
<td style="text-align: right;">0.003</td>
</tr>
</tbody>
</table>
</section>
<section id="pt-survival-analysis-cd44" class="level4">
<h4 class="anchored" data-anchor-id="pt-survival-analysis-cd44">PT Survival Analysis: CD44<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#pt-survival-analysis-cd44" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Exploratory Marker: Pooled Continuous Risk followed by Independent Validation of Cut-off</p>
<table class="caption-top table">
<caption>PT Continuous Risk (Pooled Cohort): CD44</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Marker_Value</td>
<td style="text-align: right;">1.01</td>
<td style="text-align: right;">0.007</td>
<td style="text-align: right;">1.405</td>
<td style="text-align: right;">0.16</td>
</tr>
</tbody>
</table>
<p>Discovered Cut-off (Discovery Cohort only): &gt;= 5 %</p>
<table class="caption-top table">
<caption>PT Validation Cohort (Cut-off: 5 %)</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupHigh</td>
<td style="text-align: right;">1.234</td>
<td style="text-align: right;">0.395</td>
<td style="text-align: right;">0.532</td>
<td style="text-align: right;">0.595</td>
</tr>
</tbody>
</table>
</section>
<section id="pt-survival-analysis-cd98" class="level4">
<h4 class="anchored" data-anchor-id="pt-survival-analysis-cd98">PT Survival Analysis: CD98<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#pt-survival-analysis-cd98" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Exploratory Marker: Pooled Continuous Risk followed by Independent Validation of Cut-off</p>
<table class="caption-top table">
<caption>PT Continuous Risk (Pooled Cohort): CD98</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Marker_Value</td>
<td style="text-align: right;">1.021</td>
<td style="text-align: right;">0.006</td>
<td style="text-align: right;">3.238</td>
<td style="text-align: right;">0.001</td>
</tr>
</tbody>
</table>
<p>Discovered Cut-off (Discovery Cohort only): &gt;= 40 %</p>
<table class="caption-top table">
<caption>PT Validation Cohort (Cut-off: 40 %)</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupHigh</td>
<td style="text-align: right;">3.442</td>
<td style="text-align: right;">0.435</td>
<td style="text-align: right;">2.844</td>
<td style="text-align: right;">0.004</td>
</tr>
</tbody>
</table>
</section>
</section>
<section id="lymph-node-ln-metastases-survival-analysis" class="level3">
<h3 class="anchored" data-anchor-id="lymph-node-ln-metastases-survival-analysis">6.2 Lymph Node (LN) Metastases Survival Analysis<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#lymph-node-ln-metastases-survival-analysis" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<section id="ln-survival-analysis-p53" class="level4">
<h4 class="anchored" data-anchor-id="ln-survival-analysis-p53">LN Survival Analysis: p53<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ln-survival-analysis-p53" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Using mutation archetypes: Wild-Type (6-79%) vs Aberrant (&lt;=5% or &gt;=80%) on Pooled Cohort</p>
<table class="caption-top table">
<caption>LN Biological p53 Archetypes</caption>
<colgroup>
<col style="width: 36%">
<col style="width: 12%">
<col style="width: 13%">
<col style="width: 13%">
<col style="width: 13%">
<col style="width: 10%">
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupAberrant_Pattern</td>
<td style="text-align: right;">0.711</td>
<td style="text-align: right;">0.178</td>
<td style="text-align: right;">0.355</td>
<td style="text-align: right;">-0.963</td>
<td style="text-align: right;">0.336</td>
</tr>
</tbody>
</table>
</section>
<section id="ln-survival-analysis-p16" class="level4">
<h4 class="anchored" data-anchor-id="ln-survival-analysis-p16">LN Survival Analysis: p16<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ln-survival-analysis-p16" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Using clinical cut-off: &gt;= 70% (HPV surrogate) on Pooled Cohort</p>
<table class="caption-top table">
<caption>LN Clinical p16 (70% cut-off)</caption>
<colgroup>
<col style="width: 38%">
<col style="width: 11%">
<col style="width: 12%">
<col style="width: 12%">
<col style="width: 12%">
<col style="width: 10%">
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupLow/Negative (&lt;70%)</td>
<td style="text-align: right;">7.281</td>
<td style="text-align: right;">0.394</td>
<td style="text-align: right;">0.677</td>
<td style="text-align: right;">2.931</td>
<td style="text-align: right;">0.003</td>
</tr>
</tbody>
</table>
</section>
<section id="ln-survival-analysis-cd44" class="level4">
<h4 class="anchored" data-anchor-id="ln-survival-analysis-cd44">LN Survival Analysis: CD44<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ln-survival-analysis-cd44" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Exploratory Marker: Pooled Continuous Risk followed by Independent Validation of Cut-off</p>
<table class="caption-top table">
<caption>LN Continuous Risk (Pooled Cohort): CD44</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Marker_Value</td>
<td style="text-align: right;">1.018</td>
<td style="text-align: right;">0.003</td>
<td style="text-align: right;">0.005</td>
<td style="text-align: right;">3.529</td>
<td style="text-align: right;">0</td>
</tr>
</tbody>
</table>
<p>Discovered Cut-off (Discovery Cohort only): &gt;= 25 %</p>
<table class="caption-top table">
<caption>LN Validation Cohort (Cut-off: 25 %)</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupHigh</td>
<td style="text-align: right;">2.123</td>
<td style="text-align: right;">0.261</td>
<td style="text-align: right;">0.393</td>
<td style="text-align: right;">1.915</td>
<td style="text-align: right;">0.056</td>
</tr>
</tbody>
</table>
</section>
<section id="ln-survival-analysis-cd98" class="level4">
<h4 class="anchored" data-anchor-id="ln-survival-analysis-cd98">LN Survival Analysis: CD98<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ln-survival-analysis-cd98" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Exploratory Marker: Pooled Continuous Risk followed by Independent Validation of Cut-off</p>
<table class="caption-top table">
<caption>LN Continuous Risk (Pooled Cohort): CD98</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Marker_Value</td>
<td style="text-align: right;">1.016</td>
<td style="text-align: right;">0.003</td>
<td style="text-align: right;">0.005</td>
<td style="text-align: right;">3.123</td>
<td style="text-align: right;">0.002</td>
</tr>
</tbody>
</table>
<p>Discovered Cut-off (Discovery Cohort only): &gt;= 30 %</p>
<table class="caption-top table">
<caption>LN Validation Cohort (Cut-off: 30 %)</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupHigh</td>
<td style="text-align: right;">5.639</td>
<td style="text-align: right;">0.361</td>
<td style="text-align: right;">0.493</td>
<td style="text-align: right;">3.51</td>
<td style="text-align: right;">0</td>
</tr>
</tbody>
</table>
</section>
</section>
<section id="primary-tumor-pt-survival-analysis-1" class="level3">
<h3 class="anchored" data-anchor-id="primary-tumor-pt-survival-analysis-1">6.1 Primary Tumor (PT) Survival Analysis<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#primary-tumor-pt-survival-analysis-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<section id="pt-survival-analysis-p53-1" class="level4">
<h4 class="anchored" data-anchor-id="pt-survival-analysis-p53-1">PT Survival Analysis: p53<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#pt-survival-analysis-p53-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Using mutation archetypes: Wild-Type (6-79%) vs Aberrant (&lt;=5% or &gt;=80%) on Pooled Cohort</p>
<table class="caption-top table">
<caption>PT Biological p53 Archetypes</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupAberrant_Pattern</td>
<td style="text-align: right;">0.661</td>
<td style="text-align: right;">0.339</td>
<td style="text-align: right;">-1.224</td>
<td style="text-align: right;">0.221</td>
</tr>
</tbody>
</table>
</section>
<section id="pt-survival-analysis-p16-1" class="level4">
<h4 class="anchored" data-anchor-id="pt-survival-analysis-p16-1">PT Survival Analysis: p16<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#pt-survival-analysis-p16-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Using clinical cut-off: &gt;= 70% (HPV surrogate) on Pooled Cohort</p>
<table class="caption-top table">
<caption>PT Clinical p16 (70% cut-off)</caption>
<colgroup>
<col style="width: 44%">
<col style="width: 13%">
<col style="width: 14%">
<col style="width: 14%">
<col style="width: 11%">
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupLow/Negative (&lt;70%)</td>
<td style="text-align: right;">8.799</td>
<td style="text-align: right;">0.731</td>
<td style="text-align: right;">2.974</td>
<td style="text-align: right;">0.003</td>
</tr>
</tbody>
</table>
</section>
<section id="pt-survival-analysis-cd44-1" class="level4">
<h4 class="anchored" data-anchor-id="pt-survival-analysis-cd44-1">PT Survival Analysis: CD44<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#pt-survival-analysis-cd44-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Exploratory Marker: Pooled Cross-Validated Predictions</p>
<p><strong>Final Pooled Cross-Validated Cox Model</strong></p>
<table class="caption-top table">
<caption>PT Pooled CV Performance: CD44</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupHigh</td>
<td style="text-align: right;">1.638</td>
<td style="text-align: right;">0.356</td>
<td style="text-align: right;">1.386</td>
<td style="text-align: right;">0.166</td>
</tr>
</tbody>
</table>
</section>
<section id="pt-survival-analysis-cd98-1" class="level4">
<h4 class="anchored" data-anchor-id="pt-survival-analysis-cd98-1">PT Survival Analysis: CD98<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#pt-survival-analysis-cd98-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Exploratory Marker: Pooled Cross-Validated Predictions</p>
<p><strong>Final Pooled Cross-Validated Cox Model</strong></p>
<table class="caption-top table">
<caption>PT Pooled CV Performance: CD98</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupHigh</td>
<td style="text-align: right;">2.014</td>
<td style="text-align: right;">0.379</td>
<td style="text-align: right;">1.849</td>
<td style="text-align: right;">0.064</td>
</tr>
</tbody>
</table>
</section>
</section>
<section id="lymph-node-ln-metastases-survival-analysis-1" class="level3">
<h3 class="anchored" data-anchor-id="lymph-node-ln-metastases-survival-analysis-1">6.2 Lymph Node (LN) Metastases Survival Analysis<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#lymph-node-ln-metastases-survival-analysis-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
<section id="ln-survival-analysis-p53-1" class="level4">
<h4 class="anchored" data-anchor-id="ln-survival-analysis-p53-1">LN Survival Analysis: p53<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ln-survival-analysis-p53-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Using mutation archetypes: Wild-Type (6-79%) vs Aberrant (&lt;=5% or &gt;=80%) on Pooled Cohort</p>
<table class="caption-top table">
<caption>LN Biological p53 Archetypes</caption>
<colgroup>
<col style="width: 36%">
<col style="width: 12%">
<col style="width: 13%">
<col style="width: 13%">
<col style="width: 13%">
<col style="width: 10%">
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupAberrant_Pattern</td>
<td style="text-align: right;">0.711</td>
<td style="text-align: right;">0.178</td>
<td style="text-align: right;">0.355</td>
<td style="text-align: right;">-0.963</td>
<td style="text-align: right;">0.336</td>
</tr>
</tbody>
</table>
</section>
<section id="ln-survival-analysis-p16-1" class="level4">
<h4 class="anchored" data-anchor-id="ln-survival-analysis-p16-1">LN Survival Analysis: p16<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ln-survival-analysis-p16-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Using clinical cut-off: &gt;= 70% (HPV surrogate) on Pooled Cohort</p>
<table class="caption-top table">
<caption>LN Clinical p16 (70% cut-off)</caption>
<colgroup>
<col style="width: 38%">
<col style="width: 11%">
<col style="width: 12%">
<col style="width: 12%">
<col style="width: 12%">
<col style="width: 10%">
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupLow/Negative (&lt;70%)</td>
<td style="text-align: right;">7.281</td>
<td style="text-align: right;">0.394</td>
<td style="text-align: right;">0.677</td>
<td style="text-align: right;">2.931</td>
<td style="text-align: right;">0.003</td>
</tr>
</tbody>
</table>
</section>
<section id="ln-survival-analysis-cd44-1" class="level4">
<h4 class="anchored" data-anchor-id="ln-survival-analysis-cd44-1">LN Survival Analysis: CD44<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ln-survival-analysis-cd44-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Exploratory Marker: Pooled Cross-Validated Predictions Optimal cutoffs 10 25 25 10</p>
<p><strong>Final Pooled Cross-Validated Cox Model</strong></p>
<table class="caption-top table">
<caption>LN Pooled CV Performance: CD44</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupHigh</td>
<td style="text-align: right;">2.452</td>
<td style="text-align: right;">0.211</td>
<td style="text-align: right;">0.312</td>
<td style="text-align: right;">2.872</td>
<td style="text-align: right;">0.004</td>
</tr>
</tbody>
</table>
</section>
<section id="ln-survival-analysis-cd98-1" class="level4">
<h4 class="anchored" data-anchor-id="ln-survival-analysis-cd98-1">LN Survival Analysis: CD98<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#ln-survival-analysis-cd98-1" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h4>
<p>Exploratory Marker: Pooled Cross-Validated Predictions Optimal cutoffs 25 30 25 25</p>
<p><strong>Final Pooled Cross-Validated Cox Model</strong></p>
<table class="caption-top table">
<caption>LN Pooled CV Performance: CD98</caption>
<thead>
<tr class="header">
<th style="text-align: left;">term</th>
<th style="text-align: right;">estimate</th>
<th style="text-align: right;">std.error</th>
<th style="text-align: right;">robust.se</th>
<th style="text-align: right;">statistic</th>
<th style="text-align: right;">p.value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Risk_GroupHigh</td>
<td style="text-align: right;">6.487</td>
<td style="text-align: right;">0.351</td>
<td style="text-align: right;">0.41</td>
<td style="text-align: right;">4.559</td>
<td style="text-align: right;">0</td>
</tr>
</tbody>
</table>
</section>
</section>
<section id="takeaway-lymph-node-biomarker-profiles-are-robust-biologically-grounded-predictors-of-locoregional-recurrence." class="level2">
<h2 class="anchored" data-anchor-id="takeaway-lymph-node-biomarker-profiles-are-robust-biologically-grounded-predictors-of-locoregional-recurrence.">6. Takeaway: Lymph node biomarker profiles are robust, biologically grounded predictors of locoregional recurrence.<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#takeaway-lymph-node-biomarker-profiles-are-robust-biologically-grounded-predictors-of-locoregional-recurrence." style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<p>The survival analysis reveals a critical divergence in prognostic 
power between the primary tumor and the metastatic niche. While the 
established clinical marker p16 strongly predicts locoregional control 
across both (with p16-negativity driving high risk), and CD98 indicates 
general tumor aggressiveness in both the primary and nodal disease, CD44
 tells a highly site-specific story. CD44 expression holds significant 
prognostic value only when evaluated within the lymph node metastasis 
(Continuous p &lt; 0.001; Categorical Validation p = 0.032). It fails to
 show any significant association with recurrence when measured in the 
primary tumor. This strongly reinforces that metastatic deposits 
establish an adapted biological phenotype, and evaluating the lymph node
 directly provides critical risk stratification for locoregional 
recurrence that the primary biopsy misses. (Note: p53 mutational 
archetypes did not stratify risk significantly in either tissue 
compartment for this cohort).</p>
</section>
<section id="joint-multivariable-cox-models-unaggregated-clustered" class="level2">
<h2 class="anchored" data-anchor-id="joint-multivariable-cox-models-unaggregated-clustered">7 Joint Multivariable Cox Models (Unaggregated / Clustered)<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#joint-multivariable-cox-models-unaggregated-clustered" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<p>We utilized Joint Multivariable Cox Proportional-Hazards Models. By 
placing the paired PT and LN expression values into direct statistical 
competition within the same model, we test for independent prognostic 
relevance. This analysis determines whether the primary biopsy is 
sufficient for risk estimation, or if the biology of the metastatic 
lymph node supersedes the primary tumor to act as the primary driver of 
locoregional recurrence. To robustly handle data from patients with 
multiple evaluated lymph nodes, all models incorporate patient-level 
clustering.</p>
<p><strong>Marker: p53_expr </strong>( 606 LN samples across 201 patients)</p>
<p>PT Effect -&gt; HR: 1 | p-val: 0.967</p>
<p>LN Effect -&gt; HR: 1 | p-val: 0.6981</p>
<p>CONCLUSION: Neither is significantly prognostic in the joint model (likely collinearity or lack of power).</p>
<p><strong>Marker: p16_expr </strong>( 608 LN samples across 201 patients)</p>
<p>PT Effect -&gt; HR: 1.02 | p-val: 0.1824</p>
<p>LN Effect -&gt; HR: 0.97 | p-val: 0.0037</p>
<p>CONCLUSION: Metastasis (LN) is a stronger, independent predictor. PT loses relevance.</p>
<p><strong>Marker: CD44_expr </strong>( 608 LN samples across 201 patients)</p>
<p>PT Effect -&gt; HR: 1.01 | p-val: 0.0755</p>
<p>LN Effect -&gt; HR: 1.01 | p-val: 0.0042</p>
<p>CONCLUSION: Metastasis (LN) is a stronger, independent predictor. PT loses relevance.</p>
<p><strong>Marker: CD98_expr </strong>( 611 LN samples across 203 patients)</p>
<p>PT Effect -&gt; HR: 1.01 | p-val: 0.4027</p>
<p>LN Effect -&gt; HR: 1.01 | p-val: 0.0497</p>
<p>CONCLUSION: Metastasis (LN) is a stronger, independent predictor. PT loses relevance.</p>
</section>
<section id="takeaway" class="level2">
<h2 class="anchored" data-anchor-id="takeaway">7. Takeaway<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#takeaway" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<p>When placed in direct statistical competition, the expression of p16,
 CD44, and CD98 in the lymph node emerges as the stronger, independent 
predictor of locoregional control, while the prognostic relevance of the
 primary tumor diminishes.</p>
<hr>
<p><strong>End of Analysis Document</strong></p>
</section>
</section>

</main>
<!-- /main column -->
<script id="quarto-html-after-body" type="application/javascript">
  window.document.addEventListener("DOMContentLoaded", function (event) {
    const icon = "";
    const anchorJS = new window.AnchorJS();
    anchorJS.options = {
      placement: 'right',
      icon: icon
    };
    anchorJS.add('.anchored');
    const isCodeAnnotation = (el) => {
      for (const clz of el.classList) {
        if (clz.startsWith('code-annotation-')) {                     
          return true;
        }
      }
      return false;
    }
    const onCopySuccess = function(e) {
      // button target
      const button = e.trigger;
      // don't keep focus
      button.blur();
      // flash "checked"
      button.classList.add('code-copy-button-checked');
      var currentTitle = button.getAttribute("title");
      button.setAttribute("title", "Copied!");
      let tooltip;
      if (window.bootstrap) {
        button.setAttribute("data-bs-toggle", "tooltip");
        button.setAttribute("data-bs-placement", "left");
        button.setAttribute("data-bs-title", "Copied!");
        tooltip = new bootstrap.Tooltip(button, 
          { trigger: "manual", 
            customClass: "code-copy-button-tooltip",
            offset: [0, -8]});
        tooltip.show();    
      }
      setTimeout(function() {
        if (tooltip) {
          tooltip.hide();
          button.removeAttribute("data-bs-title");
          button.removeAttribute("data-bs-toggle");
          button.removeAttribute("data-bs-placement");
        }
        button.setAttribute("title", currentTitle);
        button.classList.remove('code-copy-button-checked');
      }, 1000);
      // clear code selection
      e.clearSelection();
    }
    const getTextToCopy = function(trigger) {
        const codeEl = trigger.previousElementSibling.cloneNode(true);
        for (const childEl of codeEl.children) {
          if (isCodeAnnotation(childEl)) {
            childEl.remove();
          }
        }
        return codeEl.innerText;
    }
    const clipboard = new window.ClipboardJS('.code-copy-button:not([data-in-quarto-modal])', {
      text: getTextToCopy
    });
    clipboard.on('success', onCopySuccess);
    if (window.document.getElementById('quarto-embedded-source-code-modal')) {
      const clipboardModal = new window.ClipboardJS('.code-copy-button[data-in-quarto-modal]', {
        text: getTextToCopy,
        container: window.document.getElementById('quarto-embedded-source-code-modal')
      });
      clipboardModal.on('success', onCopySuccess);
    }
      var localhostRegex = new RegExp(/^(?:http|https):\/\/localhost\:?[0-9]*\//);
      var mailtoRegex = new RegExp(/^mailto:/);
        var filterRegex = new RegExp('/' + window.location.host + '/');
      var isInternal = (href) => {
          return filterRegex.test(href) || localhostRegex.test(href) || mailtoRegex.test(href);
      }
      // Inspect non-navigation links and adorn them if external
     var links = window.document.querySelectorAll('a[href]:not(.nav-link):not(.navbar-brand):not(.toc-action):not(.sidebar-link):not(.sidebar-item-toggle):not(.pagination-link):not(.no-external):not([aria-hidden]):not(.dropdown-item):not(.quarto-navigation-tool):not(.about-link)');
      for (var i=0; i<links.length; i++) {
        const link = links[i];
        if (!isInternal(link.href)) {
          // undo the damage that might have been done by quarto-nav.js in the case of
          // links that we want to consider external
          if (link.dataset.originalHref !== undefined) {
            link.href = link.dataset.originalHref;
          }
        }
      }
    function tippyHover(el, contentFn, onTriggerFn, onUntriggerFn) {
      const config = {
        allowHTML: true,
        maxWidth: 500,
        delay: 100,
        arrow: false,
        appendTo: function(el) {
            return el.parentElement;
        },
        interactive: true,
        interactiveBorder: 10,
        theme: 'quarto',
        placement: 'bottom-start',
      };
      if (contentFn) {
        config.content = contentFn;
      }
      if (onTriggerFn) {
        config.onTrigger = onTriggerFn;
      }
      if (onUntriggerFn) {
        config.onUntrigger = onUntriggerFn;
      }
      window.tippy(el, config); 
    }
    const noterefs = window.document.querySelectorAll('a[role="doc-noteref"]');
    for (var i=0; i<noterefs.length; i++) {
      const ref = noterefs[i];
      tippyHover(ref, function() {
        // use id or data attribute instead here
        let href = ref.getAttribute('data-footnote-href') || ref.getAttribute('href');
        try { href = new URL(href).hash; } catch {}
        const id = href.replace(/^#\/?/, "");
        const note = window.document.getElementById(id);
        if (note) {
          return note.innerHTML;
        } else {
          return "";
        }
      });
    }
    const xrefs = window.document.querySelectorAll('a.quarto-xref');
    const processXRef = (id, note) => {
      // Strip column container classes
      const stripColumnClz = (el) => {
        el.classList.remove("page-full", "page-columns");
        if (el.children) {
          for (const child of el.children) {
            stripColumnClz(child);
          }
        }
      }
      stripColumnClz(note)
      if (id === null || id.startsWith('sec-')) {
        // Special case sections, only their first couple elements
        const container = document.createElement("div");
        if (note.children && note.children.length > 2) {
          container.appendChild(note.children[0].cloneNode(true));
          for (let i = 1; i < note.children.length; i++) {
            const child = note.children[i];
            if (child.tagName === "P" && child.innerText === "") {
              continue;
            } else {
              container.appendChild(child.cloneNode(true));
              break;
            }
          }
          if (window.Quarto?.typesetMath) {
            window.Quarto.typesetMath(container);
          }
          return container.innerHTML
        } else {
          if (window.Quarto?.typesetMath) {
            window.Quarto.typesetMath(note);
          }
          return note.innerHTML;
        }
      } else {
        // Remove any anchor links if they are present
        const anchorLink = note.querySelector('a.anchorjs-link');
        if (anchorLink) {
          anchorLink.remove();
        }
        if (window.Quarto?.typesetMath) {
          window.Quarto.typesetMath(note);
        }
        if (note.classList.contains("callout")) {
          return note.outerHTML;
        } else {
          return note.innerHTML;
        }
      }
    }
    for (var i=0; i<xrefs.length; i++) {
      const xref = xrefs[i];
      tippyHover(xref, undefined, function(instance) {
        instance.disable();
        let url = xref.getAttribute('href');
        let hash = undefined; 
        if (url.startsWith('#')) {
          hash = url;
        } else {
          try { hash = new URL(url).hash; } catch {}
        }
        if (hash) {
          const id = hash.replace(/^#\/?/, "");
          const note = window.document.getElementById(id);
          if (note !== null) {
            try {
              const html = processXRef(id, note.cloneNode(true));
              instance.setContent(html);
            } finally {
              instance.enable();
              instance.show();
            }
          } else {
            // See if we can fetch this
            fetch(url.split('#')[0])
            .then(res => res.text())
            .then(html => {
              const parser = new DOMParser();
              const htmlDoc = parser.parseFromString(html, "text/html");
              const note = htmlDoc.getElementById(id);
              if (note !== null) {
                const html = processXRef(id, note);
                instance.setContent(html);
              } 
            }).finally(() => {
              instance.enable();
              instance.show();
            });
          }
        } else {
          // See if we can fetch a full url (with no hash to target)
          // This is a special case and we should probably do some content thinning / targeting
          fetch(url)
          .then(res => res.text())
          .then(html => {
            const parser = new DOMParser();
            const htmlDoc = parser.parseFromString(html, "text/html");
            const note = htmlDoc.querySelector('main.content');
            if (note !== null) {
              // This should only happen for chapter cross references
              // (since there is no id in the URL)
              // remove the first header
              if (note.children.length > 0 && note.children[0].tagName === "HEADER") {
                note.children[0].remove();
              }
              const html = processXRef(null, note);
              instance.setContent(html);
            } 
          }).finally(() => {
            instance.enable();
            instance.show();
          });
        }
      }, function(instance) {
      });
    }
        let selectedAnnoteEl;
        const selectorForAnnotation = ( cell, annotation) => {
          let cellAttr = 'data-code-cell="' + cell + '"';
          let lineAttr = 'data-code-annotation="' +  annotation + '"';
          const selector = 'span[' + cellAttr + '][' + lineAttr + ']';
          return selector;
        }
        const selectCodeLines = (annoteEl) => {
          const doc = window.document;
          const targetCell = annoteEl.getAttribute("data-target-cell");
          const targetAnnotation = annoteEl.getAttribute("data-target-annotation");
          const annoteSpan = window.document.querySelector(selectorForAnnotation(targetCell, targetAnnotation));
          const lines = annoteSpan.getAttribute("data-code-lines").split(",");
          const lineIds = lines.map((line) => {
            return targetCell + "-" + line;
          })
          let top = null;
          let height = null;
          let parent = null;
          if (lineIds.length > 0) {
              //compute the position of the single el (top and bottom and make a div)
              const el = window.document.getElementById(lineIds[0]);
              top = el.offsetTop;
              height = el.offsetHeight;
              parent = el.parentElement.parentElement;
            if (lineIds.length > 1) {
              const lastEl = window.document.getElementById(lineIds[lineIds.length - 1]);
              const bottom = lastEl.offsetTop + lastEl.offsetHeight;
              height = bottom - top;
            }
            if (top !== null && height !== null && parent !== null) {
              // cook up a div (if necessary) and position it 
              let div = window.document.getElementById("code-annotation-line-highlight");
              if (div === null) {
                div = window.document.createElement("div");
                div.setAttribute("id", "code-annotation-line-highlight");
                div.style.position = 'absolute';
                parent.appendChild(div);
              }
              div.style.top = top - 2 + "px";
              div.style.height = height + 4 + "px";
              div.style.left = 0;
              let gutterDiv = window.document.getElementById("code-annotation-line-highlight-gutter");
              if (gutterDiv === null) {
                gutterDiv = window.document.createElement("div");
                gutterDiv.setAttribute("id", "code-annotation-line-highlight-gutter");
                gutterDiv.style.position = 'absolute';
                const codeCell = window.document.getElementById(targetCell);
                const gutter = codeCell.querySelector('.code-annotation-gutter');
                gutter.appendChild(gutterDiv);
              }
              gutterDiv.style.top = top - 2 + "px";
              gutterDiv.style.height = height + 4 + "px";
            }
            selectedAnnoteEl = annoteEl;
          }
        };
        const unselectCodeLines = () => {
          const elementsIds = ["code-annotation-line-highlight", "code-annotation-line-highlight-gutter"];
          elementsIds.forEach((elId) => {
            const div = window.document.getElementById(elId);
            if (div) {
              div.remove();
            }
          });
          selectedAnnoteEl = undefined;
        };
          // Handle positioning of the toggle
      window.addEventListener(
        "resize",
        throttle(() => {
          elRect = undefined;
          if (selectedAnnoteEl) {
            selectCodeLines(selectedAnnoteEl);
          }
        }, 10)
      );
      function throttle(fn, ms) {
      let throttle = false;
      let timer;
        return (...args) => {
          if(!throttle) { // first call gets through
              fn.apply(this, args);
              throttle = true;
          } else { // all the others get throttled
              if(timer) clearTimeout(timer); // cancel #2
              timer = setTimeout(() => {
                fn.apply(this, args);
                timer = throttle = false;
              }, ms);
          }
        };
      }
        // Attach click handler to the DT
        const annoteDls = window.document.querySelectorAll('dt[data-target-cell]');
        for (const annoteDlNode of annoteDls) {
          annoteDlNode.addEventListener('click', (event) => {
            const clickedEl = event.target;
            if (clickedEl !== selectedAnnoteEl) {
              unselectCodeLines();
              const activeEl = window.document.querySelector('dt[data-target-cell].code-annotation-active');
              if (activeEl) {
                activeEl.classList.remove('code-annotation-active');
              }
              selectCodeLines(clickedEl);
              clickedEl.classList.add('code-annotation-active');
            } else {
              // Unselect the line
              unselectCodeLines();
              clickedEl.classList.remove('code-annotation-active');
            }
          });
        }
    const findCites = (el) => {
      const parentEl = el.parentElement;
      if (parentEl) {
        const cites = parentEl.dataset.cites;
        if (cites) {
          return {
            el,
            cites: cites.split(' ')
          };
        } else {
          return findCites(el.parentElement)
        }
      } else {
        return undefined;
      }
    };
    var bibliorefs = window.document.querySelectorAll('a[role="doc-biblioref"]');
    for (var i=0; i<bibliorefs.length; i++) {
      const ref = bibliorefs[i];
      const citeInfo = findCites(ref);
      if (citeInfo) {
        tippyHover(citeInfo.el, function() {
          var popup = window.document.createElement('div');
          citeInfo.cites.forEach(function(cite) {
            var citeDiv = window.document.createElement('div');
            citeDiv.classList.add('hanging-indent');
            citeDiv.classList.add('csl-entry');
            var biblioDiv = window.document.getElementById('ref-' + cite);
            if (biblioDiv) {
              citeDiv.innerHTML = biblioDiv.innerHTML;
            }
            popup.appendChild(citeDiv);
          });
          return popup.innerHTML;
        });
      }
    }
  });
  </script>
</div> <!-- /content -->




</body></html>
