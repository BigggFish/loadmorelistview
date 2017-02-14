# 上拉加载更多ListView
可以套在 下拉刷新控件里面，实现上拉加载更多 下拉刷新。

注意：
1. addFooterView 要在setAdapter之前，之后的使用updateFooterView。

2. 数据加载完，调用onFinishLoading()方法。

3. 当没用更多数据， 调用onNoMoreData()方法。

4. 添加onScrollerListener 使用addScrollerListener()方法。

5. 使用setOnLoadMoreListener(OnLoadMoreListener listener)设置监听。

6. setLoadMoreEnable(true)开启监听，默认是不监听。

7. 实现简单
