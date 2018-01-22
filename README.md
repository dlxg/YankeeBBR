<a><h1>魔改版BBR一键脚本 For Debian8/Ubuntu16+</a></h1> 
<strong>部分商家的VPS可能会遇到换内核之后无法启动系统的情况，所以请运行脚本前一定要备份好重要数据！！</strong>
<h2 id="安装脚本">安装脚本</h2>
<pre class="prettyprint linenums" >
wget -N --no-check-certificate https://raw.githubusercontent.com/dlxg/YankeeBBR/master/bbr.sh &amp;&amp; bash bbr.sh install</pre>
安装过程中如果出现这张图片，请选择NO 来删除其他内核：</p>
<img class="aligncenter size-full wp-image-106" src="https://cdn.ylws.me/usr/uploads/2017/06/3363374172.png" width="640" height="420" /></p>
<p>然后根据提示重启系统。<br />
重启完成后，运行</p>
<pre class="prettyprint linenums" >
bash bbr.sh start
</pre>
<p>即可启动魔改版BBR。</p>
<h2 id="查看魔改BBR状态">查看魔改BBR状态</h2>
<pre class="prettyprint linenums" >
sysctl net.ipv4.tcp_available_congestion_control
</pre>
<p>如果看到有 tsunami 就表示开启成功！</p>
<p><img class="aligncenter size-full wp-image-107" src="http://letvps.com/wp-content/uploads/2017/07/2017070602263391.png" width="1009" height="174" /></p>
