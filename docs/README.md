# Headline

> An awesome project.

>使用命令 *npm i docsify-cli -g* 全局安装docsify，使用命令 *docsify serve ./docs* 启动文档

> 初始使用 *docsify init ./docs* 命令进行初始化会因系统执行策略的问题而失败，以管理员身份执行命令   *set-ExecutionPolicy RemoteSigned* 解决

>制指定 *docsify* 的版本可以通过 *cdn* 引入时指定，比如 */cdn.jsdelivr.net/npm/docsify@4.11.11*

>路径嵌套，层级访问。服务启动时是原始的 *README.md* 文件，可以通过增加md文件增加页面，只需在url中增加页面相对
README.md的路径。*README.md*文件是每一个文件夹的主页面。

>侧边栏，一个文件夹一个，在切换页面时会更换侧边栏显示,当前文件夹没有会向上查找，找到就用

>*.nojekyll* 用来防止GitHub忽略下划线开头的文件

>alias对象用于设置路由别名，支持正则。
