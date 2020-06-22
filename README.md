# eros uiwebview去除

* WXWebComponent 里面的uiviwebview改成了wkwebview
* eros里面提供的bmnative方法已经放入了<web>标签，使用方法和eros一样的
* 删除了eros的webView，不能在使用了this.$router.openWebview了，没有对它的webView进行改造， 如果需要可以自己修改
