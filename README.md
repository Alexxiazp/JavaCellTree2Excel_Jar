# xiazpNode
个人日志<br/>
<h1>JavaCellTree2Excel的使用</h1><br/>
<ul><li>解压<code>JavaCellTree2Excel.7z</code> 得到
<code>javacg-0.1-SNAPSHOT-static.jar</code>
<code>JavaCellTree2Excel.jar</code></li>
<li><code>javacg-0.1-SNAPSHOT-static.jar</code><code>JavaCellTree2Excel.jar</code>需要配合使用</li>
<li><code>javacg-0.1-SNAPSHOT-static.jar</code>使用参照:<url>https://github.com/gousiosg/java-callgraph</url><br/></li>
</ul>
<h5>
example <code>javacg-0.1-SNAPSHOT-static.jar</code>
</h5>
<pre><code>java -jar javacg-0.1-SNAPSHOT-static.jar lib1.jar lib2.jar... >> lib.txt
</code></pre>
<h5>
example <code>javaCellTree2Excel.jar</code>
</h5>
<pre><code>java -jar javaCellTree2Excel.jar lib.txt
</code></pre>
