# GitHub Search Tips
(1). 基本搜索(Basic search)：
    A．查找stars数超过100的”cat”仓库：cat stars:>100
    B．搜索用户名为fengbingchun的所有仓库：user:fengbingchun
    C. 搜索地址在” San Francisco, CA”的用户名包含tom的所有仓库：tom location:"San Francisco, CA"
    D. 搜索不包含”cat”的所有仓库：NOT cat
(2). 仓库搜索(Repository search)：
    A. 查找stars数超过100的”cat”仓库：cat stars:>100
    B. 搜索用户名为fengbingchun的所有仓库：user:fengbingchun
    C. 搜索名为”node.js”并fork数少于200的所有仓库：node.js forks:<200
    D. 搜索名为”jquery”并库大小在1024至4089KB之间的所有仓库：jquery size:1024..4089
    E. 搜索用户名为fengbingchun并且开发语言为C++的所有仓库：language:c++ user:fengbingchun
    F. 搜索用户名为fengbingchun并且stars数大于等于10的所有仓库：user:fengbingchun followers:>=10
    G. 搜索开发语言为C++且stars数大于10000的所有仓库：language:c++ stars:>10000
    H. 搜索用户名为fengbingchun并且仓库在2019年1月1日后有更新的所有仓库：user:fengbingchun pushed:>2019-01-01
(3). 代码搜索(Code search)：
    A. 搜索用户名为fengbingchun并且文件中含有”cv::Mat”的所有文件：cv::Mat user:fengbingchun
    B. 搜索文件大小大于1000KB并文件中包含”system”的所有文件：system size:>1000
    C. 搜索在/docs/路径下文件中含有”examples”的所有文件：examples path:/docs/
(4). (问题搜索)Issue search：
    A. 搜索用户名为fengbingchun并issue中含有”opencv”字段的所有issues：opencv user:fengbingchun
    B. 搜索issue是open状态并且issue中含有”fengbingchun”字段的所有issues：fengbingchun is:open
    C. 搜素issue中comments数大于4次且含有”fengbingchun”字段的所有issues：fengbingchun comments:>4
    D. 搜索issue创建者是fengbingchun的所有issues：author:fengbingchun
    E. 搜索issue在2019年2月15日后创建的且含有”opencv”字段的所有issues：opencv created:>2019-03-15
(5). 用户名搜索(User search)：
    A. 搜索用户全名为”Bingchun Feng”的用户：fullname:"Bingchun Feng"
    B. 搜索地址在” San Francisco, CA”的用户名包含tom的所有仓库：tom location:"San Francisco, CA"
