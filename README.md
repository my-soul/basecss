# basecss
基础css



.bold{ font-weight: bold; font-weight: bold;}
.regular{ font-weight:normal;}
.italic{ font-style:italic;}
.caps{ text-transform:uppercase; letter-spacing: .2em;}

.linethrough{text-decoration: line-through;}    

.justify{ text-align:justify;}
.tal{text-align: left;}
.tar{text-align: right;}
.tac{text-align: center;}

.nowrap{ white-space:nowrap;}
.break-word{ word-wrap:break-word;}
.wordbreak{word-break: break-all;}
.ellipsis{overflow: hidden;text-overflow: ellipsis;white-space: nowrap;}
.ellipsis2{overflow: hidden;text-overflow: ellipsis;display: -webkit-box; -webkit-line-clamp: 2;-webkit-box-orient: vertical;}
.ellipsis3{overflow: hidden;text-overflow: ellipsis;display: -webkit-box; -webkit-line-clamp: 3;-webkit-box-orient: vertical;}

.pointer{cursor:pointer;}
.wait{cursor:wait;}
.notAllowed{cursor:not-allowed;}

.underline{ text-decoration:underline;}

.list-unstyled {  padding-left: 0;  list-style: none;}
.list-inline { padding-left: 0; list-style: none;}
.list-inline-item {display: inline-block;}

.truncate{max-width:100%;overflow:hidden;text-overflow:ellipsis;}
.list-reset{list-style:none;  padding-left:0;}

.inline{ display:inline;}
.block{ display:block;}
.inline-block{ display:inline-block;}
.table{ display:table;}
.table-cell{ display:table-cell;}

.relative{ position:relative;}
.absolute{ position:absolute;}
.fixed{ position:fixed;}

.left{ float:left;}
.right{ float:right;}

.hide{position:absolute !important; height:1px; width:1px; overflow:hidden;clip:rect(1px, 1px, 1px, 1px);}
.display-none{ display:none !important;}

.overflow-hidden{ overflow:hidden;}
.overflow-scroll{ overflow:scroll;}
.overflow-auto{ overflow:auto;}

.border-box{ box-sizing:border-box;}

.align-baseline{ vertical-align:baseline;}
.align-top{ vertical-align:top;}
.align-middle{ vertical-align:middle;}
.align-bottom{ vertical-align:bottom;}


.clearfix:before,.clearfix:after{content:" ";display:table;}
.clearfix:after{clear:both }

.lh-1{ line-height: 1;}
.lh-2{ line-height: 1.125;}
.lh-3{ line-height: 1.25;}
.lh-4{ line-height: 1.5;}

.max-width-1{ max-width: 24rem;}
.max-width-2{ max-width: 32rem;}
.max-width-3{ max-width: 48rem;}
.max-width-4{ max-width: 64rem;}


.hui-80{color: #333;}
.hui-50{color: #808080;}      
.hui-30{color: #999;}       
.hui-25{color: #c0c0c0;}

.blue{color: #528fcc;}
.orange{color:#f7b72d;}
.red{color: #f00;}
.green{color: #38cb3f;}
.white{color: #fff;}
.black{color: #000;}

/*字体*/
.font_24{font-size: 24px;}
.font_b{font-size: 18px;}
.font_h{font-size: 16px;}
.font_t{font-size: 14px;}
.font_c{font-size: 12px;}
.font_s{font-size: 10px;}


.font_w400{font-weight:400;}
.font_w700{font-weight:700;}

/*背景*/
.bg_a{background: #fff;}
.bg_b{background: #538fcd;}
.bg_c{background: #ebebeb;}
.bg_d{background: #f8f8f8;}
.bg_f0{background: #f0f0f0;}
.bg_blue{background: #528fcc;}
.bg_orange{background: #f7b72d;}
.bg_hui{background: #ddd;}
.bg_f8{background: #f8f8f8}

.z1{ z-index: 1;}
.z2{ z-index: 2;}
.z3{ z-index: 3;}
.z4{ z-index: 4;}

.bd{  border: 1px solid #ddd;}
.bd-t{border-top: 1px solid #ddd;}
.bd-r{border-right: 1px solid #ddd;}
.bd-b{border-bottom: 1px solid #ddd;}
.bd-l{border-left: 1px solid #ddd;}
.bd-x{border-right: 1px solid #ddd;border-left: 1px solid #ddd;}
.bd-y{border-bottom: 1px solid #ddd;border-top: 1px solid #ddd;}
.bd-none{ border:0 }

.bdr-none{ border-radius:0 }
.bdr50{border-radius: 50%;}
.bdr2{border-radius: 2px;}
.bdr4{border-radius: 4px;}

.line24{line-height: 24px;}
.line28{height:28px; line-height: 28px;}
.line30{height:30px; line-height: 30px;}
.line32{height:32px; line-height: 32px;}
.line36{height:36px; line-height: 36px;}

.r0{right:0;}
.t0{top:0;}
.b0{bottom: 0;}
.l0{left: 0;}

.r5{right:5px;}
.t5{top:5px;}
.b5{bottom: 5px;}
.l5{left: 5px;}

.r10{right:10px;}
.t10{top:10px;}
.b10{bottom: 10px;}
.l10{left: 10px;}

.r15{right:15px;}
.t15{top:15px;}
.b15{bottom: 15px;}
.l15{left: 15px;}

.r20{right:20px;}
.t20{top:20px;}
.b20{bottom: 20px;}
.l20{left: 20px;}


.w25 {width: 25% !important;}
.w50 {width: 50% !important;}
.w75 {width: 75% !important;}
.w100 {width: 100% !important;}

.h25 {height: 25% !important;}
.h50 {height: 50% !important;}
.h75 {height: 75% !important;}
.h100 {height: 100% !important;}

.mw100 {max-width: 100% !important;}
.mh100 {max-height: 100% !important;}

/**  正方形  **/
.wh10{width: 10px;height: 10px;}
.wh30{width: 30px;height: 30px;}
.wh50{width: 50px;height: 50px;}
.wh70{width: 70px;height: 70px;}
.wh80{width: 80px;height: 80px;}
.wh100{width: 100px;height: 100px;}

/** margin: auto 0px 5px 10px 15px 20px **/

.ml-auto{ margin-left:auto;}
.mr-auto{ margin-right:auto;}
.mx-auto{ margin-left:auto; margin-right:auto; }

.m0{ margin:0;}
.mt0{ margin-top:0;}
.mr0{ margin-right:0;}
.mb0{ margin-bottom:0;}
.ml0{ margin-left:0;}
.mx0{ margin-left:0; margin-right:0;}
.my0{ margin-top:0; margin-bottom:0;}

.m5{ margin: 5px;}
.mt5{ margin-top: 5px;}
.mr5{ margin-right: 5px;}
.mb5{ margin-bottom: 5px}
.ml5{ margin-left: 5px }
.mx5{ margin-left: 5px; margin-right: 5px;}
.my5{ margin-top: 5px; margin-bottom: 5px;}

.m10{ margin: 10px;}
.mt10{ margin-top: 10px;}
.mr10{ margin-right: 10px;}
.mb10{ margin-bottom: 10px;}
.ml10{ margin-left: 10px;}
.mx10{ margin-left: 10px; margin-right: 10px;}
.my10{ margin-top: 10px; margin-bottom: 10px;}

.m15{ margin: 15px;}
.mt15{ margin-top: 15px;}
.mr15{ margin-right: 15px;}
.mb15{ margin-bottom: 15px;}
.ml15{ margin-left: 15px;}
.mx15{ margin-left: 15px; margin-right: 15px;}
.my15{ margin-top: 15px; margin-bottom: 15px;}
.m20{ margin: 20px;}
.mt20{ margin-top: 20px;}
.mr20{ margin-right: 20px;}
.mb20{ margin-bottom: 20px;}
.ml20{ margin-left: 20px;}
.mx20{ margin-left: 20px; margin-right: 20px;}
.my20{ margin-top: 20px; margin-bottom: 2rem;}

/** padding: 0px 5px 10px 15px 20px **/

.p0{ padding:0;}
.pt0{ padding-top:0;}
.pr0{ padding-right:0;}
.pb0{ padding-bottom:0;}
.pl0{ padding-left:0 }
.px0{ padding-left:0; padding-right:0;}
.py0{ padding-top:0;  padding-bottom:0;}

.p5{ padding: 5px;}
.pt5{ padding-top: 5px;}
.pr5{ padding-right: 5px;}
.pb5{ padding-bottom: 5px;}
.pl5{ padding-left: 5px;}
.py5{ padding-top: 5px; padding-bottom: 5px;}
.px5{ padding-left: 5px; padding-right: 5px;}

.p10{ padding: 10px;}
.pt10{ padding-top: 10px;}
.pr10{ padding-right: 10px;}
.pb10{ padding-bottom: 10px;}
.pl10{ padding-left: 10px;}
.py10{ padding-top: 10px; padding-bottom: 10px;}
.px10{ padding-left: 10px; padding-right: 10px;}

.p15{ padding: 15px;}
.pt15{ padding-top: 15px;}
.pr15{ padding-right: 15px;}
.pb15{ padding-bottom: 15px;}
.pl15{ padding-left: 15px;}
.py15{ padding-top: 15px; padding-bottom: 15px;}
.px15{ padding-left: 15px; padding-right: 15px;}

.p20{ padding: 20px;}
.pt20{ padding-top: 20px;}
.pr20{ padding-right: 20px;}
.pb20{ padding-bottom: 20px;}
.pl20{ padding-left: 20px;}
.py20{ padding-top: 20px; padding-bottom: 20px;}
.px20{ padding-left: 20px; padding-right: 2rem;}
