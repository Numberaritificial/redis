<div id="table-of-contents">
<h2>互金平台-分布式缓存服务</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#orgbb9e7ec">1. redis 哨兵集群</a>
<ul>
<li><a href="#org18c458b">1.1. 部署信息</a></li>
</ul>
</li>
</ul>
</div>
</div>

[最新部署信息](http://wiki.cibfintech.com/TechZone/redis_sentinel)
<a id="orgbb9e7ec"></a>

# redis 哨兵集群


<a id="org18c458b"></a>

## 部署信息

<span class="underline">表格中 {a/b/c} 表示 a, b, c 都为可选值</span>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-right" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">环境</th>
<th scope="col" class="org-right">redis 版本</th>
<th scope="col" class="org-left">部署节点</th>
<th scope="col" class="org-left">技术支持</th>
<th scope="col" class="org-left">主从集群信息</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">开发</td>
<td class="org-right">3.2.6</td>
<td class="org-left">10.96.5.{178/179/180}:26379</td>
<td class="org-left">杨起道</td>
<td class="org-left">master name:redis-dev-master</td>
</tr>


<tr>
<td class="org-left">测试</td>
<td class="org-right">3.2.6</td>
<td class="org-left">10.96.5.{3/4/5}:26379</td>
<td class="org-left">杨起道</td>
<td class="org-left">master name:redis-test-master</td>
</tr>


<tr>
<td class="org-left">生产</td>
<td class="org-right">3.2.6</td>
<td class="org-left">10.32.3.{18/19/20}:26379</td>
<td class="org-left">杨起道</td>
<td class="org-left">master name:redis-test-master</td>
</tr>
</tbody>
</table>

