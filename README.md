<!-- saved from url=(0042)https://speechresearch.github.io/lrspeech/ -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<meta name="generator" content="Hugo 0.66.0">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/css" rel="stylesheet" type="text/css">
<link rel="stylesheet" href="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/github.min.css">
<link rel="stylesheet" href="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/normalize.css">
<link rel="stylesheet" href="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/skeleton.css">
<link rel="stylesheet" href="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/custom.css">
<link rel="alternate" href="https://speechresearch.github.io/lrspeech/index.xml" type="application/rss+xml" title="SpeechResearch">
<link rel="shortcut icon" href="https://speechresearch.github.io/lrspeech/favicon.png" type="image/x-icon">
<title>LRSpeech: Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch</title>
<style type="text/css">.MathJax_Hover_Frame {border-radius: .25em; -webkit-border-radius: .25em; -moz-border-radius: .25em; -khtml-border-radius: .25em; box-shadow: 0px 0px 15px #83A; -webkit-box-shadow: 0px 0px 15px #83A; -moz-box-shadow: 0px 0px 15px #83A; -khtml-box-shadow: 0px 0px 15px #83A; border: 1px solid #A6D ! important; display: inline-block; position: absolute}
.MathJax_Menu_Button .MathJax_Hover_Arrow {position: absolute; cursor: pointer; display: inline-block; border: 2px solid #AAA; border-radius: 4px; -webkit-border-radius: 4px; -moz-border-radius: 4px; -khtml-border-radius: 4px; font-family: 'Courier New',Courier; font-size: 9px; color: #F0F0F0}
.MathJax_Menu_Button .MathJax_Hover_Arrow span {display: block; background-color: #AAA; border: 1px solid; border-radius: 3px; line-height: 0; padding: 4px}
.MathJax_Hover_Arrow:hover {color: white!important; border: 2px solid #CCC!important}
.MathJax_Hover_Arrow:hover span {background-color: #CCC!important}
</style><style type="text/css">#MathJax_About {position: fixed; left: 50%; width: auto; text-align: center; border: 3px outset; padding: 1em 2em; background-color: #DDDDDD; color: black; cursor: default; font-family: message-box; font-size: 120%; font-style: normal; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; z-index: 201; border-radius: 15px; -webkit-border-radius: 15px; -moz-border-radius: 15px; -khtml-border-radius: 15px; box-shadow: 0px 10px 20px #808080; -webkit-box-shadow: 0px 10px 20px #808080; -moz-box-shadow: 0px 10px 20px #808080; -khtml-box-shadow: 0px 10px 20px #808080; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
#MathJax_About.MathJax_MousePost {outline: none}
.MathJax_Menu {position: absolute; background-color: white; color: black; width: auto; padding: 2px; border: 1px solid #CCCCCC; margin: 0; cursor: default; font: menu; text-align: left; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; z-index: 201; box-shadow: 0px 10px 20px #808080; -webkit-box-shadow: 0px 10px 20px #808080; -moz-box-shadow: 0px 10px 20px #808080; -khtml-box-shadow: 0px 10px 20px #808080; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
.MathJax_MenuItem {padding: 2px 2em; background: transparent}
.MathJax_MenuArrow {position: absolute; right: .5em; padding-top: .25em; color: #666666; font-size: .75em}
.MathJax_MenuActive .MathJax_MenuArrow {color: white}
.MathJax_MenuArrow.RTL {left: .5em; right: auto}
.MathJax_MenuCheck {position: absolute; left: .7em}
.MathJax_MenuCheck.RTL {right: .7em; left: auto}
.MathJax_MenuRadioCheck {position: absolute; left: 1em}
.MathJax_MenuRadioCheck.RTL {right: 1em; left: auto}
.MathJax_MenuLabel {padding: 2px 2em 4px 1.33em; font-style: italic}
.MathJax_MenuRule {border-top: 1px solid #CCCCCC; margin: 4px 1px 0px}
.MathJax_MenuDisabled {color: GrayText}
.MathJax_MenuActive {background-color: Highlight; color: HighlightText}
.MathJax_MenuDisabled:focus, .MathJax_MenuLabel:focus {background-color: #E8E8E8}
.MathJax_ContextMenu:focus {outline: none}
.MathJax_ContextMenu .MathJax_MenuItem:focus {outline: none}
#MathJax_AboutClose {top: .2em; right: .2em}
.MathJax_Menu .MathJax_MenuClose {top: -10px; left: -10px}
.MathJax_MenuClose {position: absolute; cursor: pointer; display: inline-block; border: 2px solid #AAA; border-radius: 18px; -webkit-border-radius: 18px; -moz-border-radius: 18px; -khtml-border-radius: 18px; font-family: 'Courier New',Courier; font-size: 24px; color: #F0F0F0}
.MathJax_MenuClose span {display: block; background-color: #AAA; border: 1.5px solid; border-radius: 18px; -webkit-border-radius: 18px; -moz-border-radius: 18px; -khtml-border-radius: 18px; line-height: 0; padding: 8px 0 6px}
.MathJax_MenuClose:hover {color: white!important; border: 2px solid #CCC!important}
.MathJax_MenuClose:hover span {background-color: #CCC!important}
.MathJax_MenuClose:hover:focus {outline: none}
</style><style type="text/css">.MathJax_Preview .MJXf-math {color: inherit!important}
</style><style type="text/css">.MJX_Assistive_MathML {position: absolute!important; top: 0; left: 0; clip: rect(1px, 1px, 1px, 1px); padding: 1px 0 0 0!important; border: 0!important; height: 1px!important; width: 1px!important; overflow: hidden!important; display: block!important; -webkit-touch-callout: none; -webkit-user-select: none; -khtml-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none}
.MJX_Assistive_MathML.MJX_Assistive_MathML_Block {width: 100%!important}
</style><style type="text/css">#MathJax_Zoom {position: absolute; background-color: #F0F0F0; overflow: auto; display: block; z-index: 301; padding: .5em; border: 1px solid black; margin: 0; font-weight: normal; font-style: normal; text-align: left; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; -webkit-box-sizing: content-box; -moz-box-sizing: content-box; box-sizing: content-box; box-shadow: 5px 5px 15px #AAAAAA; -webkit-box-shadow: 5px 5px 15px #AAAAAA; -moz-box-shadow: 5px 5px 15px #AAAAAA; -khtml-box-shadow: 5px 5px 15px #AAAAAA; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
#MathJax_ZoomOverlay {position: absolute; left: 0; top: 0; z-index: 300; display: inline-block; width: 100%; height: 100%; border: 0; padding: 0; margin: 0; background-color: white; opacity: 0; filter: alpha(opacity=0)}
#MathJax_ZoomFrame {position: relative; display: inline-block; height: 0; width: 0}
#MathJax_ZoomEventTrap {position: absolute; left: 0; top: 0; z-index: 302; display: inline-block; border: 0; padding: 0; margin: 0; background-color: white; opacity: 0; filter: alpha(opacity=0)}
</style><style type="text/css">.MathJax_Preview {color: #888}
#MathJax_Message {position: fixed; left: 1em; bottom: 1.5em; background-color: #E6E6E6; border: 1px solid #959595; margin: 0px; padding: 2px 8px; z-index: 102; color: black; font-size: 80%; width: auto; white-space: nowrap}
#MathJax_MSIE_Frame {position: absolute; top: 0; left: 0; width: 0px; z-index: 101; border: 0px; margin: 0px; padding: 0px}
.MathJax_Error {color: #CC0000; font-style: italic}
</style><style type="text/css">.MJXp-script {font-size: .8em}
.MJXp-right {-webkit-transform-origin: right; -moz-transform-origin: right; -ms-transform-origin: right; -o-transform-origin: right; transform-origin: right}
.MJXp-bold {font-weight: bold}
.MJXp-italic {font-style: italic}
.MJXp-scr {font-family: MathJax_Script,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-frak {font-family: MathJax_Fraktur,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-sf {font-family: MathJax_SansSerif,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-cal {font-family: MathJax_Caligraphic,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-mono {font-family: MathJax_Typewriter,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-largeop {font-size: 150%}
.MJXp-largeop.MJXp-int {vertical-align: -.2em}
.MJXp-math {display: inline-block; line-height: 1.2; text-indent: 0; font-family: 'Times New Roman',Times,STIXGeneral,serif; white-space: nowrap; border-collapse: collapse}
.MJXp-display {display: block; text-align: center; margin: 1em 0}
.MJXp-math span {display: inline-block}
.MJXp-box {display: block!important; text-align: center}
.MJXp-box:after {content: " "}
.MJXp-rule {display: block!important; margin-top: .1em}
.MJXp-char {display: block!important}
.MJXp-mo {margin: 0 .15em}
.MJXp-mfrac {margin: 0 .125em; vertical-align: .25em}
.MJXp-denom {display: inline-table!important; width: 100%}
.MJXp-denom > * {display: table-row!important}
.MJXp-surd {vertical-align: top}
.MJXp-surd > * {display: block!important}
.MJXp-script-box > *  {display: table!important; height: 50%}
.MJXp-script-box > * > * {display: table-cell!important; vertical-align: top}
.MJXp-script-box > *:last-child > * {vertical-align: bottom}
.MJXp-script-box > * > * > * {display: block!important}
.MJXp-mphantom {visibility: hidden}
.MJXp-munderover {display: inline-table!important}
.MJXp-over {display: inline-block!important; text-align: center}
.MJXp-over > * {display: block!important}
.MJXp-munderover > * {display: table-row!important}
.MJXp-mtable {vertical-align: .25em; margin: 0 .125em}
.MJXp-mtable > * {display: inline-table!important; vertical-align: middle}
.MJXp-mtr {display: table-row!important}
.MJXp-mtd {display: table-cell!important; text-align: center; padding: .5em 0 0 .5em}
.MJXp-mtr > .MJXp-mtd:first-child {padding-left: 0}
.MJXp-mtr:first-child > .MJXp-mtd {padding-top: 0}
.MJXp-mlabeledtr {display: table-row!important}
.MJXp-mlabeledtr > .MJXp-mtd:first-child {padding-left: 0}
.MJXp-mlabeledtr:first-child > .MJXp-mtd {padding-top: 0}
.MJXp-merror {background-color: #FFFF88; color: #CC0000; border: 1px solid #CC0000; padding: 1px 3px; font-style: normal; font-size: 90%}
.MJXp-scale0 {-webkit-transform: scaleX(.0); -moz-transform: scaleX(.0); -ms-transform: scaleX(.0); -o-transform: scaleX(.0); transform: scaleX(.0)}
.MJXp-scale1 {-webkit-transform: scaleX(.1); -moz-transform: scaleX(.1); -ms-transform: scaleX(.1); -o-transform: scaleX(.1); transform: scaleX(.1)}
.MJXp-scale2 {-webkit-transform: scaleX(.2); -moz-transform: scaleX(.2); -ms-transform: scaleX(.2); -o-transform: scaleX(.2); transform: scaleX(.2)}
.MJXp-scale3 {-webkit-transform: scaleX(.3); -moz-transform: scaleX(.3); -ms-transform: scaleX(.3); -o-transform: scaleX(.3); transform: scaleX(.3)}
.MJXp-scale4 {-webkit-transform: scaleX(.4); -moz-transform: scaleX(.4); -ms-transform: scaleX(.4); -o-transform: scaleX(.4); transform: scaleX(.4)}
.MJXp-scale5 {-webkit-transform: scaleX(.5); -moz-transform: scaleX(.5); -ms-transform: scaleX(.5); -o-transform: scaleX(.5); transform: scaleX(.5)}
.MJXp-scale6 {-webkit-transform: scaleX(.6); -moz-transform: scaleX(.6); -ms-transform: scaleX(.6); -o-transform: scaleX(.6); transform: scaleX(.6)}
.MJXp-scale7 {-webkit-transform: scaleX(.7); -moz-transform: scaleX(.7); -ms-transform: scaleX(.7); -o-transform: scaleX(.7); transform: scaleX(.7)}
.MJXp-scale8 {-webkit-transform: scaleX(.8); -moz-transform: scaleX(.8); -ms-transform: scaleX(.8); -o-transform: scaleX(.8); transform: scaleX(.8)}
.MJXp-scale9 {-webkit-transform: scaleX(.9); -moz-transform: scaleX(.9); -ms-transform: scaleX(.9); -o-transform: scaleX(.9); transform: scaleX(.9)}
.MathJax_PHTML .noError {vertical-align: ; font-size: 90%; text-align: left; color: black; padding: 1px 3px; border: 1px solid}
</style><style type="text/css">.mjx-chtml {display: inline-block; line-height: 0; text-indent: 0; text-align: left; text-transform: none; font-style: normal; font-weight: normal; font-size: 100%; font-size-adjust: none; letter-spacing: normal; word-wrap: normal; word-spacing: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0; min-height: 0; border: 0; margin: 0; padding: 1px 0}
.MJXc-display {display: block; text-align: center; margin: 1em 0; padding: 0}
.mjx-chtml[tabindex]:focus, body :focus .mjx-chtml[tabindex] {display: inline-table}
.mjx-full-width {text-align: center; display: table-cell!important; width: 10000em}
.mjx-math {display: inline-block; border-collapse: separate; border-spacing: 0}
.mjx-math * {display: inline-block; -webkit-box-sizing: content-box!important; -moz-box-sizing: content-box!important; box-sizing: content-box!important; text-align: left}
.mjx-numerator {display: block; text-align: center}
.mjx-denominator {display: block; text-align: center}
.MJXc-stacked {height: 0; position: relative}
.MJXc-stacked > * {position: absolute}
.MJXc-bevelled > * {display: inline-block}
.mjx-stack {display: inline-block}
.mjx-op {display: block}
.mjx-under {display: table-cell}
.mjx-over {display: block}
.mjx-over > * {padding-left: 0px!important; padding-right: 0px!important}
.mjx-under > * {padding-left: 0px!important; padding-right: 0px!important}
.mjx-stack > .mjx-sup {display: block}
.mjx-stack > .mjx-sub {display: block}
.mjx-prestack > .mjx-presup {display: block}
.mjx-prestack > .mjx-presub {display: block}
.mjx-delim-h > .mjx-char {display: inline-block}
.mjx-surd {vertical-align: top}
.mjx-mphantom * {visibility: hidden}
.mjx-merror {background-color: #FFFF88; color: #CC0000; border: 1px solid #CC0000; padding: 2px 3px; font-style: normal; font-size: 90%}
.mjx-annotation-xml {line-height: normal}
.mjx-menclose > svg {fill: none; stroke: currentColor}
.mjx-mtr {display: table-row}
.mjx-mlabeledtr {display: table-row}
.mjx-mtd {display: table-cell; text-align: center}
.mjx-label {display: table-row}
.mjx-box {display: inline-block}
.mjx-block {display: block}
.mjx-span {display: inline}
.mjx-char {display: block; white-space: pre}
.mjx-itable {display: inline-table; width: auto}
.mjx-row {display: table-row}
.mjx-cell {display: table-cell}
.mjx-table {display: table; width: 100%}
.mjx-line {display: block; height: 0}
.mjx-strut {width: 0; padding-top: 1em}
.mjx-vsize {width: 0}
.MJXc-space1 {margin-left: .167em}
.MJXc-space2 {margin-left: .222em}
.MJXc-space3 {margin-left: .278em}
.mjx-chartest {display: block; visibility: hidden; position: absolute; top: 0; line-height: normal; font-size: 500%}
.mjx-chartest .mjx-char {display: inline}
.mjx-chartest .mjx-box {padding-top: 1000px}
.MJXc-processing {visibility: hidden; position: fixed; width: 0; height: 0; overflow: hidden}
.MJXc-processed {display: none}
.mjx-test {display: block; font-style: normal; font-weight: normal; font-size: 100%; font-size-adjust: none; text-indent: 0; text-transform: none; letter-spacing: normal; word-spacing: normal; overflow: hidden; height: 1px}
.mjx-ex-box-test {position: absolute; overflow: hidden; width: 1px; height: 60ex}
.mjx-line-box-test {display: table!important}
.mjx-line-box-test span {display: table-cell!important; width: 10000em!important; min-width: 0; max-width: none; padding: 0; border: 0; margin: 0}
#MathJax_CHTML_Tooltip {background-color: InfoBackground; color: InfoText; border: 1px solid black; box-shadow: 2px 2px 5px #AAAAAA; -webkit-box-shadow: 2px 2px 5px #AAAAAA; -moz-box-shadow: 2px 2px 5px #AAAAAA; -khtml-box-shadow: 2px 2px 5px #AAAAAA; padding: 3px 4px; z-index: 401; position: absolute; left: 0; top: 0; width: auto; height: auto; display: none}
.mjx-chtml .mjx-noError {line-height: 1.2; vertical-align: ; font-size: 90%; text-align: left; color: black; padding: 1px 3px; border: 1px solid}
.MJXc-TeX-unknown-R {font-family: STIXGeneral,'Cambria Math','Arial Unicode MS',serif; font-style: normal; font-weight: normal}
.MJXc-TeX-unknown-I {font-family: STIXGeneral,'Cambria Math','Arial Unicode MS',serif; font-style: italic; font-weight: normal}
.MJXc-TeX-unknown-B {font-family: STIXGeneral,'Cambria Math','Arial Unicode MS',serif; font-style: normal; font-weight: bold}
.MJXc-TeX-unknown-BI {font-family: STIXGeneral,'Cambria Math','Arial Unicode MS',serif; font-style: italic; font-weight: bold}
.MJXc-TeX-ams-R {font-family: MJXc-TeX-ams-R,MJXc-TeX-ams-Rw}
.MJXc-TeX-cal-B {font-family: MJXc-TeX-cal-B,MJXc-TeX-cal-Bx,MJXc-TeX-cal-Bw}
.MJXc-TeX-frak-R {font-family: MJXc-TeX-frak-R,MJXc-TeX-frak-Rw}
.MJXc-TeX-frak-B {font-family: MJXc-TeX-frak-B,MJXc-TeX-frak-Bx,MJXc-TeX-frak-Bw}
.MJXc-TeX-math-BI {font-family: MJXc-TeX-math-BI,MJXc-TeX-math-BIx,MJXc-TeX-math-BIw}
.MJXc-TeX-sans-R {font-family: MJXc-TeX-sans-R,MJXc-TeX-sans-Rw}
.MJXc-TeX-sans-B {font-family: MJXc-TeX-sans-B,MJXc-TeX-sans-Bx,MJXc-TeX-sans-Bw}
.MJXc-TeX-sans-I {font-family: MJXc-TeX-sans-I,MJXc-TeX-sans-Ix,MJXc-TeX-sans-Iw}
.MJXc-TeX-script-R {font-family: MJXc-TeX-script-R,MJXc-TeX-script-Rw}
.MJXc-TeX-type-R {font-family: MJXc-TeX-type-R,MJXc-TeX-type-Rw}
.MJXc-TeX-cal-R {font-family: MJXc-TeX-cal-R,MJXc-TeX-cal-Rw}
.MJXc-TeX-main-B {font-family: MJXc-TeX-main-B,MJXc-TeX-main-Bx,MJXc-TeX-main-Bw}
.MJXc-TeX-main-I {font-family: MJXc-TeX-main-I,MJXc-TeX-main-Ix,MJXc-TeX-main-Iw}
.MJXc-TeX-main-R {font-family: MJXc-TeX-main-R,MJXc-TeX-main-Rw}
.MJXc-TeX-math-I {font-family: MJXc-TeX-math-I,MJXc-TeX-math-Ix,MJXc-TeX-math-Iw}
.MJXc-TeX-size1-R {font-family: MJXc-TeX-size1-R,MJXc-TeX-size1-Rw}
.MJXc-TeX-size2-R {font-family: MJXc-TeX-size2-R,MJXc-TeX-size2-Rw}
.MJXc-TeX-size3-R {font-family: MJXc-TeX-size3-R,MJXc-TeX-size3-Rw}
.MJXc-TeX-size4-R {font-family: MJXc-TeX-size4-R,MJXc-TeX-size4-Rw}
.MJXc-TeX-vec-R {font-family: MJXc-TeX-vec-R,MJXc-TeX-vec-Rw}
.MJXc-TeX-vec-B {font-family: MJXc-TeX-vec-B,MJXc-TeX-vec-Bx,MJXc-TeX-vec-Bw}
@font-face {font-family: MJXc-TeX-ams-R; src: local('MathJax_AMS'), local('MathJax_AMS-Regular')}
@font-face {font-family: MJXc-TeX-ams-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_AMS-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_AMS-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_AMS-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-cal-B; src: local('MathJax_Caligraphic Bold'), local('MathJax_Caligraphic-Bold')}
@font-face {font-family: MJXc-TeX-cal-Bx; src: local('MathJax_Caligraphic'); font-weight: bold}
@font-face {font-family: MJXc-TeX-cal-Bw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Caligraphic-Bold.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Caligraphic-Bold.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Caligraphic-Bold.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-frak-R; src: local('MathJax_Fraktur'), local('MathJax_Fraktur-Regular')}
@font-face {font-family: MJXc-TeX-frak-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Fraktur-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Fraktur-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Fraktur-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-frak-B; src: local('MathJax_Fraktur Bold'), local('MathJax_Fraktur-Bold')}
@font-face {font-family: MJXc-TeX-frak-Bx; src: local('MathJax_Fraktur'); font-weight: bold}
@font-face {font-family: MJXc-TeX-frak-Bw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Fraktur-Bold.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Fraktur-Bold.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Fraktur-Bold.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-math-BI; src: local('MathJax_Math BoldItalic'), local('MathJax_Math-BoldItalic')}
@font-face {font-family: MJXc-TeX-math-BIx; src: local('MathJax_Math'); font-weight: bold; font-style: italic}
@font-face {font-family: MJXc-TeX-math-BIw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Math-BoldItalic.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Math-BoldItalic.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Math-BoldItalic.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-sans-R; src: local('MathJax_SansSerif'), local('MathJax_SansSerif-Regular')}
@font-face {font-family: MJXc-TeX-sans-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_SansSerif-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_SansSerif-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_SansSerif-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-sans-B; src: local('MathJax_SansSerif Bold'), local('MathJax_SansSerif-Bold')}
@font-face {font-family: MJXc-TeX-sans-Bx; src: local('MathJax_SansSerif'); font-weight: bold}
@font-face {font-family: MJXc-TeX-sans-Bw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_SansSerif-Bold.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_SansSerif-Bold.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_SansSerif-Bold.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-sans-I; src: local('MathJax_SansSerif Italic'), local('MathJax_SansSerif-Italic')}
@font-face {font-family: MJXc-TeX-sans-Ix; src: local('MathJax_SansSerif'); font-style: italic}
@font-face {font-family: MJXc-TeX-sans-Iw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_SansSerif-Italic.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_SansSerif-Italic.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_SansSerif-Italic.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-script-R; src: local('MathJax_Script'), local('MathJax_Script-Regular')}
@font-face {font-family: MJXc-TeX-script-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Script-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Script-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Script-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-type-R; src: local('MathJax_Typewriter'), local('MathJax_Typewriter-Regular')}
@font-face {font-family: MJXc-TeX-type-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Typewriter-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Typewriter-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Typewriter-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-cal-R; src: local('MathJax_Caligraphic'), local('MathJax_Caligraphic-Regular')}
@font-face {font-family: MJXc-TeX-cal-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Caligraphic-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Caligraphic-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Caligraphic-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-main-B; src: local('MathJax_Main Bold'), local('MathJax_Main-Bold')}
@font-face {font-family: MJXc-TeX-main-Bx; src: local('MathJax_Main'); font-weight: bold}
@font-face {font-family: MJXc-TeX-main-Bw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Main-Bold.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Main-Bold.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Main-Bold.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-main-I; src: local('MathJax_Main Italic'), local('MathJax_Main-Italic')}
@font-face {font-family: MJXc-TeX-main-Ix; src: local('MathJax_Main'); font-style: italic}
@font-face {font-family: MJXc-TeX-main-Iw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Main-Italic.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Main-Italic.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Main-Italic.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-main-R; src: local('MathJax_Main'), local('MathJax_Main-Regular')}
@font-face {font-family: MJXc-TeX-main-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Main-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Main-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Main-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-math-I; src: local('MathJax_Math Italic'), local('MathJax_Math-Italic')}
@font-face {font-family: MJXc-TeX-math-Ix; src: local('MathJax_Math'); font-style: italic}
@font-face {font-family: MJXc-TeX-math-Iw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Math-Italic.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Math-Italic.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Math-Italic.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-size1-R; src: local('MathJax_Size1'), local('MathJax_Size1-Regular')}
@font-face {font-family: MJXc-TeX-size1-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Size1-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Size1-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Size1-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-size2-R; src: local('MathJax_Size2'), local('MathJax_Size2-Regular')}
@font-face {font-family: MJXc-TeX-size2-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Size2-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Size2-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Size2-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-size3-R; src: local('MathJax_Size3'), local('MathJax_Size3-Regular')}
@font-face {font-family: MJXc-TeX-size3-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Size3-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Size3-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Size3-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-size4-R; src: local('MathJax_Size4'), local('MathJax_Size4-Regular')}
@font-face {font-family: MJXc-TeX-size4-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Size4-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Size4-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Size4-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-vec-R; src: local('MathJax_Vector'), local('MathJax_Vector-Regular')}
@font-face {font-family: MJXc-TeX-vec-Rw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Vector-Regular.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Vector-Regular.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Vector-Regular.otf') format('opentype')}
@font-face {font-family: MJXc-TeX-vec-B; src: local('MathJax_Vector Bold'), local('MathJax_Vector-Bold')}
@font-face {font-family: MJXc-TeX-vec-Bx; src: local('MathJax_Vector'); font-weight: bold}
@font-face {font-family: MJXc-TeX-vec-Bw; src /*1*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/eot/MathJax_Vector-Bold.eot'); src /*2*/: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/woff/MathJax_Vector-Bold.woff') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/fonts/HTML-CSS/TeX/otf/MathJax_Vector-Bold.otf') format('opentype')}
</style></head>
<body><div id="MathJax_Message" style="display: none;"></div>

<div class="container">

	<header role="banner">
		
			
		
		
	</header>


	<main role="main">
		<article itemscope="" itemtype="https://schema.org/BlogPosting">
            <h1 class="entry-title" itemprop="headline">LRSpeech: Extremely Low-Resource Speech Synthesis and Recognition</h1>
			
			<section itemprop="entry-text">
				<br>
<img src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/2.png" width="90%" height="40px" alt="LRSpeech_pipline">
<br>
<img src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/3.png" width="90%" height="40px" alt="LRSpeech_model">
<p>ArXiv: <a href="https://arxiv.org/pdf/2008.03687.pdf">arXiv:2008.03687</a></p>
<!-- Reddit Discussions: [Click me](https://www.reddit.com/r/MachineLearning/comments/brzwi5/r_fastspeech_fast_robust_and_controllable_text_to/) -->
<h2 id="authors">Authors</h2>
<ul>
<li>Jin Xu (Tsinghua University) <a href="mailto:j-xu18@mails.tsinghua.edu.cn">j-xu18@mails.tsinghua.edu.cn</a></li>
<li>Xu Tan (Microsoft Research) <a href="mailto:xuta@microsoft.com">xuta@microsoft.com</a></li>
<li>Yi Ren (Zhejiang University) <a href="mailto:rayeren@zju.edu.cn">rayeren@zju.edu.cn</a></li>
<li>Tao Qin (Microsoft Research) <a href="mailto:taoqin@microsoft.com">taoqin@microsoft.com</a></li>
<li>Jian Li (Tsinghua University) <a href="mailto:lijian83@mail.tsinghua.edu.cn">lijian83@mail.tsinghua.edu.cn</a></li>
<li>Sheng Zhao (Microsoft STC Asia) <a href="mailto:Sheng.Zhao@microsoft.com">Sheng.Zhao@microsoft.com</a></li>
<li>Tie-Yan Liu (Microsoft Research) <a href="mailto:tyliu@microsoft.com">tyliu@microsoft.com</a></li>
</ul>
<h2 id="abstract">Abstract</h2>
<p>Speech synthesis (text to speech, TTS) and recognition (automatic speech recognition, ASR) are important speech tasks, and require a large amount of text and speech pairs for model training. However, there are more than 6,000 languages in the world and most languages are lack of speech training data, which poses significant challenges when building TTS and ASR systems for extremely low-resource languages. In this paper, we develop LRSpeech, a TTS and ASR system under the extremely low-resource setting, which can support rare languages with low data cost. LRSpeech consists of three key techniques: 1) pre-training on rich-resource languages and fine-tuning on low-resource languages; 2) dual transformation between TTS and ASR to iteratively boost the accuracy of each other; 3) knowledge distillation to customize the TTS model on a high-quality target-speaker voice and improve the ASR model on multiple voices. We conduct experiments on an experimental language (English) and a truly low-resource language (Lithuanian) to verify the effectiveness of LRSpeech. Experimental results show that LRSpeech 1) achieves high quality for TTS in terms of both intelligibility (more than <span class="MathJax_Preview" style="color: inherit; display: none;"></span><span id="MathJax-Element-1-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;&gt;&lt;mn&gt;98&lt;/mn&gt;&lt;/math&gt;" role="presentation" style="font-size: 119%; position: relative;"><span id="MJXc-Node-1" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-2" class="mjx-mrow"><span id="MJXc-Node-3" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.376em; padding-bottom: 0.376em;">98</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>98</mn></math></span></span><script type="math/tex" id="MathJax-Element-1">98%</script> intelligibility rate) and naturalness (above 3.5 mean opinion score (MOS)) of the synthesized speech, which satisfy the requirements for industrial deployment, 2) achieves promising recognition accuracy for ASR, and 3) last but not least, uses extremely low-resource training data. We also conduct comprehensive analyses on LRSpeech with different amounts of data resources, and provide valuable insights and guidances for industrial deployment. We are currently deploying LRSpeech into a commercialized cloud speech service to support TTS on more rare languages.</p>
<h2 id="training-audio-samples">Training Audio Samples</h2>
<h3 id="english">English</h3>
<!-- #### Target Speaker  -->
<p><b>SPEECH 1</b> : *Printing in the only sense with which we are at present concerned differs from most if not from all the arts and crafts represented in the exhibition.*<br>
<b>SPEECH 2</b> : <em>Anne walked in silence phil chattered of many things suddenly she said.</em> <br>
<b>SPEECH 3</b> : <em>And this sir gringamores arms were all black and that to him longeth</em></p>
<table><thead>
<tr>
<th style="text-align: center">High-Quality Speaker</th>
<th style="text-align: center">Low-Quality Speaker 1</th>
<th style="text-align: center">Low-Quality Speaker 2</th>
<!-- <th style="text-align: center">GT (Parallel WaveGAN)</th> -->
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/train_samples/english/00001.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/train_samples/english/112-123216-0023.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/train_samples/english/1536-137608-0021.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<!-- <td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/train_samples/english/00001_wavegan.wav" autoplay/>Your browser does not support the audio element.</audio></td> -->
</tr>
</tbody></table>
<h3 id="lithuanian">Lithuanian</h3>
<p><b>SPEECH 1</b> : *Bengalinis tigras katinių šeimos plėšrūnas.*<br>
<b>SPEECH 2</b> : <em>Taip gimė Prancūzijos restoranų tradicija.</em> <br>
<b>SPEECH 3</b> : <em>Kai kurios linijos yra seniai tapusios neatskiriama šios vietos kraštovaizdžio ir topografijos dalimi.</em></p>
<table><thead>
<tr>
<th style="text-align: center">High-Quality Speaker</th>
<th style="text-align: center">Low-Quality Speaker 1</th>
<th style="text-align: center">Low-Quality Speaker 2</th>
<!-- <th style="text-align: center">GT (Parallel WaveGAN)</th> -->
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/train_samples/lithuania/raw_0.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/train_samples/lithuania/S200Vl_039_17.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/train_samples/lithuania/S563Vg_004_04.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<!-- <td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/train_samples/lithuania/0_gen.wav" autoplay/>Your browser does not support the audio element.</audio></td> -->
</tr>
</tbody></table>
<h2 id="tts-audio-samples-in-the-paper">TTS Audio Samples in the Paper</h2>
<h3 id="table-3---the-accuracy-comparison-for-tts-and-asr">Table 3  : the Accuracy Comparison for TTS and ASR</h3>
<p><em>The paper’s author is alistair evans of monash university in australia.</em> <br>
(Figure 3 in the paper)</p>
<table><thead>
<tr>
<th style="text-align: center">Baseline 1</th>
<th style="text-align: center">Baseline 2</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/baseline1/[48]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/baseline2/[48]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<table><thead>
<tr>
<th style="text-align: center">+ PF</th>
<th style="text-align: center">+ PF + DT</th>
<th style="text-align: center">+ PF + DT + KD</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_pretrain/[48]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_BT/[48]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_KD/[48]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<!-- *This incensed Paul campaign official blogger Jack Hunter, so he produced a video to explain to doubters how 29 is a bigger number than 26.* <br>

<table><thead>
<tr>

<th style="text-align: center">Baseline 1</th>
<th style="text-align: center">Baseline 2</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/ablation/baseline1/[184]_gen.wav" autoplay/>Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/ablation/baseline2/[184]_gen.wav" autoplay/>Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<table><thead>
<tr>
<th style="text-align: center">+ PF</th>
<th style="text-align: center">+ PF + DT</th>
<th style="text-align: center">+ PF + DT + KD</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/ablation/add_pretrain/[184]_gen.wav" autoplay/>Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/ablation/add_BT/[184]_gen.wav" autoplay/>Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/ablation/add_KD/[184]_gen.wav" autoplay/>Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table> -->
<p><em>Michigan Theatre tabs Steve Tucker as new executive director.</em></p>
<table><thead>
<tr>
<th style="text-align: center">Baseline 1</th>
<th style="text-align: center">Baseline 2</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/baseline1/[3]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/baseline2/[3]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<table><thead>
<tr>
<th style="text-align: center">+ PF</th>
<th style="text-align: center">+ PF + DT</th>
<th style="text-align: center">+ PF + DT + KD</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_pretrain/[3]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_BT/[3]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_KD/[3]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<p><em>Tucker taught and coached baseball for Vandercook Lake schools from the late nineteen seventys until retiring in 2008.</em></p>
<table><thead>
<tr>
<th style="text-align: center">Baseline 1</th>
<th style="text-align: center">Baseline 2</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/baseline1/[188]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/baseline2/[188]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<table><thead>
<tr>
<th style="text-align: center">+ PF</th>
<th style="text-align: center">+ PF + DT</th>
<th style="text-align: center">+ PF + DT + KD</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_pretrain/[188]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_BT/[188]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_KD/[188]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<p><em>The Commonwealth Fund recently released its first ever Scorecard on Local Health System Performance.</em></p>
<table><thead>
<tr>
<th style="text-align: center">Baseline 1</th>
<th style="text-align: center">Baseline 2</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/baseline1/[139]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/baseline2/[139]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<table><thead>
<tr>
<th style="text-align: center">+ PF</th>
<th style="text-align: center">+ PF + DT</th>
<th style="text-align: center">+ PF + DT + KD</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_pretrain/[139]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_BT/[139]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/ablation/add_KD/[139]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<!-- ### Table 5 : High-quality samples (without KD)

*I wanted my own trolley and Henrietta Pussycat and Daniel the Lion.* 

<table><thead>
<tr>

<th style="text-align: center">20</th>
<th style="text-align: center">50</th>
<th style="text-align: center">100</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/high_quality/20/00007.wav" autoplay/>Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/high_quality/50/00007.wav" autoplay/>Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls" ><source src="../audio/lrspeech/high_quality/100/00007.wav" autoplay/>Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table> -->
<h3 id="fig-4-a--low-quality-paireds-samples-without-kd">Fig 4 (a) : Low-Quality Paireds Samples (Without KD)</h3>
<p><b>(1) Experimental Results</b><br>
<img src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/2_low.png" width="40%" height="20px" alt="LRSpeech_pipline">
<br>
<b>(2) Audio Samples</b>
<br></p>
<p><em>The soap opera that begat Java deserved to be written as a novel.</em></p>
<table><thead>
<tr>
<th style="text-align: center">200</th>
<th style="text-align: center">500</th>
<th style="text-align: center">1000</th>
<th style="text-align: center">5000</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/low_quality_pair/200/00012.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/low_quality_pair/500/00012.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/low_quality_pair/1000/00012.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/low_quality_pair/5000/00012.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<h3 id="fig-4-b--low-quality-unpaireds-samples-without-kd">Fig 4 (b) : Low-Quality Unpaireds Samples (Without KD)</h3>
<p><b>(1) Experimental Results</b><br>
<img src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/3_low.png" width="40%" height="20px" alt="LRSpeech_pipline">
<br></p>
<p><b>(2) Audio Samples</b>
<br>
<em>Their pure lines appeal to people who embrace minimalism in fashion, design, and architecture.</em></p>
<table><thead>
<tr>
<th style="text-align: center">PF</th>
<th style="text-align: center">+ Seen</th>
<th style="text-align: center">+ Seen + Unseen</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/low_quality_unpair/baseline2/00018.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/low_quality_unpair/seen/00018.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/low_quality_unpair/unseen/00018.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<h3 id="fig-4-c--knowledge-distillation-for-tts">Fig 4 (c) : Knowledge Distillation for TTS</h3>
<p><b>(1) Experimental Results</b><br>
<img src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/4_tts.png" width="40%" height="20px" alt="LRSpeech_pipline">
<br>
<b>(2) Audio Samples</b>
<br>
<em>I remembered that school, so I went back through my book keepings from college and sure enough, I still had the program and score book from that game.</em></p>
<table><thead>
<tr>
<th style="text-align: center">1000</th>
<th style="text-align: center">3000</th>
<th style="text-align: center">5000</th>
<th style="text-align: center">20000</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/distill/1000/[110]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/distill/3000/[110]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/distill/5000/[110]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/distill/20000/[110]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<h3 id="table-5--synthesized-lithuanian-speech-of-lrspeech">Table 5 : Synthesized Lithuanian Speech of LRSpeech</h3>
<p><b>SPEECH 1</b> : *Sveria iki dešimties kilogramų.*<br>
<b>SPEECH 2</b> : <em>Taip pat medžioja vandens paukščius ir vabzdžius varles net kiškių jauniklius.</em> <br>
<b>SPEECH 3</b> : <em>Po vandeniu neįkvėpusi gali nuplaukti keturis šimtus metrų kartais išvysto net iki keturiolikos kilometru per valandą greitį.</em></p>
<table><thead>
<tr>
<th style="text-align: center">SPEECH 1</th>
<th style="text-align: center">SPEECH 2</th>
<th style="text-align: center">SPEECH 3</th>
<!-- <th style="text-align: center">GT (Parallel WaveGAN)</th> -->
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/lithuanian/[3]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/lithuanian/[9]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/lithuanian/[2]_gen.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<h2 id="part-of-mos-and-ir-test-report">Part of MOS and IR Test Report</h2>
<p><a href="https://speechresearch.github.io/audio/lrspeech/report/MOS.xlsx" download="">MOS_en_US.xlsx</a>
<br>
<a href="https://speechresearch.github.io/audio/lrspeech/report/IR.xlsx" download="">IR_en_US.xlsx</a></p>
<h2 id="test-sentences-for-tts">Test sentences for TTS</h2>
<p><a href="https://speechresearch.github.io/audio/lrspeech/report/MOS_test.txt" download="">MOS_en_US.txt</a>
<br>
<a href="https://speechresearch.github.io/audio/lrspeech/report/IR_test.txt" download="">IR_en_US.txt</a></p>
<h2 id="other-experiments">Other Experiments</h2>
<h3 id="varing-high-quality-target-speaker-pairded-data-without-kd">Varing High-Quality Target Speaker Pairded Data (Without KD)</h3>
<p><b>(1) Experimental Results</b><br>
<img src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/1_high.png" width="40%" height="20px" alt="LRSpeech_pipline">
<br></p>
<p><b>(2) Audio Samples</b>
<br>
<em>I wanted my own trolley and Henrietta Pussycat and Daniel the Lion.</em></p>
<table><thead>
<tr>
<th style="text-align: center">20</th>
<th style="text-align: center">50</th>
<th style="text-align: center">100</th>
</tr></thead><tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/high_quality/20/00007.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/high_quality/50/00007.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="../audio/lrspeech/high_quality/100/00007.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody></table>
<!-- ## Code

Code will be released after the paper is accepted by the conference. -->
<h2 id="our-related-works">Our Related Works</h2>
<p><a href="https://speechresearch.github.io/unsuper/">Almost Unsupervised Text to Speech and Automatic Speech Recognition</a><br>
<a href="https://speechresearch.github.io/fastspeech/">FastSpeech: Fast, Robust and Controllable Text to Speech</a><br>
<a href="https://speechresearch.github.io/seminas/">Semi-Supervised Neural Architecture Search</a><br>
<a href="https://speechresearch.github.io/multispeech/">MultiSpeech: Multi-Speaker Text to Speech with Transformer</a><br>
<a href="https://speechresearch.github.io/deepsinger/">DeepSinger: Singing Voice Synthesis with Data Mined From the Web</a><br>
<a href="https://speechresearch.github.io/fastspeech2/">FastSpeech 2: Fast and High-Quality End-to-End Text-to-Speech</a><br>
<a href="https://speechresearch.github.io/uwspeech/">UWSpeech: Speech to Speech Translation for Unwritten Languages</a><br></p>

			</section>
		</article>
	</main>


	

</div>

<script async="" src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/analytics.js.下载"></script><script>
	(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
	(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
	m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
	})(window,document,'script','//www.google-analytics.com/analytics.js','ga');
	ga('create', 'UA-139981676-1', 'auto');
	ga('send', 'pageview');
</script>

<script src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/highlight.min.js.下载"></script>
<script>hljs.initHighlightingOnLoad();</script>



<script type="text/x-mathjax-config;executed=true">
     MathJax.Hub.Config({
         HTML: ["input/TeX","output/HTML-CSS"],
         TeX: {
                Macros: {
                         bm: ["\\boldsymbol{#1}", 1],
                         argmax: ["\\mathop{\\rm arg\\,max}\\limits"],
                         argmin: ["\\mathop{\\rm arg\\,min}\\limits"]},
                extensions: ["AMSmath.js","AMSsymbols.js"],
                equationNumbers: { autoNumber: "AMS" } },
         extensions: ["tex2jax.js"],
         jax: ["input/TeX","output/HTML-CSS"],
         tex2jax: { inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true },
         "HTML-CSS": { availableFonts: ["TeX"],
                       linebreaks: { automatic: true } }
     });
 </script>

 <script type="text/x-mathjax-config;executed=true">
     MathJax.Hub.Config({
       tex2jax: {
         skipTags: ['script', 'noscript', 'style', 'textarea', 'pre', 'code']
       }
     });
 </script>

 <script type="text/javascript" async="" src="./LRSpeech_ Extremely Low-Resource Speech Synthesis and Recognition - SpeechResearch_files/MathJax.js.下载">
 </script>

