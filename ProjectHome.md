一个基于AIR的FTP客户端, AS3代码, 有使用flash.flashsystem包, 易于使用和扩展



&lt;hr&gt;



<p><b>使用示例:</b><a href='http://code.google.com/p/fishtp/downloads/detail?name=FishTP.air&can=2&q='>Demo AIR</a></p>



&lt;/hr&gt;



<b>起因</b>

<p>一直很想研究一下SOCKET这一块的API, 为以后的开发做准备, 就直接拿FTP练手了, 搜了一下网络上的资源, 只有一个FlexFTP的开源项目是相关的, 但那个项目使用的阿波罗, 版本太低现在编译的话, 报好多问题, 所以就自己动手来做一个了. 还有另外一个资源是09年年底的时候, 在天地会某堂主发布的一个FTP软件, 下载试用了一下, 很顺手, 但是目的与我的不太一样.</p>

<p>希望得到大家的支持, 并且多多提意见, 一直相信:好东西是需要耐心的.</p>



&lt;hr/&gt;



邮箱:darkty2009@gmail.com



&lt;hr/&gt;



<font color='#f00'><b>最近更新:</b></font>

<ul>

<li><b>fishtp</b> version:1.0.0.1 2010-06-10 14:25</li>

</ul>



&lt;hr/&gt;



<font color='#f00'><b>最新下载:</b></font>

<p><a href='http://code.google.com/p/fishtp/downloads/detail?name=FishTP-v1.0.zip&can=2&q='><b>FishTP</b> version:1.0.0.1</a></p>
<p><a href='http://code.google.com/p/fishtp/downloads/detail?name=FishTP-v1.0-doc.zip&can=2&q='><b>FishTP</b> version:1.0.0.1 doc</a></p>
<p>
包含主要的FTP通信代码以及几个自定义流程,能在一般情况下正常使用,如功能不够,请发邮件与我联系,将会尽快丰富该库,或者自行添加<br />
文档里包含了所有类的说明,源码里的main.mxml文件里包含了使用方法,给出的Demo是模拟一个DOS控制台的形式<br />
初始输入示例:<br>
<pre><code>connect 127.0.0.1 21 username password</code></pre>
可以连接服务器<br />
连接成功后,<br>
输入<br>
<pre><code>help</code></pre>
可以查询可使用的命令<br>
</p>
<p>
更新 FishTP-1.0.1<br>
针对大文件（1G以上）上传下载过程中出现内存消耗导致程序崩溃实现了一种解决方法，可供参考<br>
</p>


