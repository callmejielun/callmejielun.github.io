# STL-algorithm

>一些算法的简便算法
>::for_each(ite,ite,&func)按照func规则遍历<br/>
ite=::find(ite,ite,val)查找val值，返回迭代器

>::random_shuffle(ite,ite)打乱顺序排列，需要种子<br/>
::sort(ite,ite);默认从小到大排序<br/>
::sort(ite,ite,&func)按照func规则排，例如：<br/>
bool func(int a, int b)<br/>
	return a>b;<br/>
此时就从大到小了

>::reverse(ite,ite)内容倒置<br/>
int::count(ite,ite,val)两个迭代器之间有几个val<br/>
