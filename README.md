<html>

<head>

<title>HTML网页制作实例</title>

<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<style type="text/css">
body {
	background-color: #CCC;
}
</style>
<script type="text/javascript">
function MM_swapImgRestore() { //v3.0
  var i,x,a=document.MM_sr; for(i=0;a&&i<a.length&&(x=a[i])&&x.oSrc;i++) x.src=x.oSrc;
}
function MM_preloadImages() { //v3.0
  var d=document; if(d.images){ if(!d.MM_p) d.MM_p=new Array();
    var i,j=d.MM_p.length,a=MM_preloadImages.arguments; for(i=0; i<a.length; i++)
    if (a[i].indexOf("#")!=0){ d.MM_p[j]=new Image; d.MM_p[j++].src=a[i];}}
}

function MM_findObj(n, d) { //v4.01
  var p,i,x;  if(!d) d=document; if((p=n.indexOf("?"))>0&&parent.frames.length) {
    d=parent.frames[n.substring(p+1)].document; n=n.substring(0,p);}
  if(!(x=d[n])&&d.all) x=d.all[n]; for (i=0;!x&&i<d.forms.length;i++) x=d.forms[i][n];
  for(i=0;!x&&d.layers&&i<d.layers.length;i++) x=MM_findObj(n,d.layers[i].document);
  if(!x && d.getElementById) x=d.getElementById(n); return x;
}

function MM_swapImage() { //v3.0
  var i,j=0,x,a=MM_swapImage.arguments; document.MM_sr=new Array; for(i=0;i<(a.length-2);i+=3)
   if ((x=MM_findObj(a[i]))!=null){document.MM_sr[j++]=x; if(!x.oSrc) x.oSrc=x.src; x.src=a[i+2];}
}
</script>
</head>

<body onLoad="MM_preloadImages('images/11.jpg')">
welcome
<h1>实验标题</h1>
<h2>实验标题</h2>
<h3>实验标题</h3>
<h4>实验标题</h4>
<h5>实验标题</h5>
<h6>实验标题</h6>
<p>段落文本</p>
<p align="left">段落文本</p>
<p align="center">段落文本</p>
<p align="right">段落文本</p>
强制换行标记</br>强制换行标记
<font size="6" color="#00FF00" face="黑体">这是size=6，color=#00FF00，face=宋体的文本</font>
<p><b>文本加粗</b></p>
<p><i>文本倾斜</i></p>
<p><u>文本下划线</u></p>
<p><strong>文本加重显示</strong></p>
<!--图像显示
<imgsrc="images/top.gif" alt="顶部图片" width="770" height="200"
-->
<a href="URL"target="_blank">链接</a>
<!--href控制链接到的文件地址，target控制目标窗口，blank表示在新窗口打开链接的文件-->
<a href="http://www.baidu.com">百度搜索</a>//绝对超链接</br>
<a href="test2.htm">网页 test2</a>//相对超链接</br>
<a href="http://www.jxau.edu.cn">江西农业大学</a>

<table border="0" width="100%" cellpadding="10">
<tr>

<td width="40%" valign="top">
This is some text. This is some text. This is some text. This is some text. This is some text.
</td>

<td width="60%" valign="top">
Another text. Another text. Another text. Another text. Another text. Another text. Another text.
</td>

</tr>
</table>

</body>
</html>
