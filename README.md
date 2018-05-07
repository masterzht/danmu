简介
----

通过selenium自动发送斗鱼弹幕，模仿真实操作，避免封禁风险。首次运行需要采用二维码扫描登陆，提高安全性，便捷性，提供登陆成功概率。以后运行会自动读取保存到本地的cookie文件，实现真正的免人为操作。安装测试环境：python3；Ubuntu 16.10/WIN10；Chrome/Firefox

安装运行
----

1. 下载代码（Windows用户请在git-bash里执行）

        git clone git://github.com/masterzht/Danmu.git

2. 安装Python 3.x

        https://www.python.org/getit/

3. 目前支持的浏览器有firefox，chrome，默认选择的webdriver是windows下的chrome驱动，如需修改，请更改executable_path。

        driver = webdriver.Chrome(executable_path="./driver/win/chromedriver", chrome_options=options)
4. 在命令行里运行

        python DouyuDanmu.py

附
----

chrome驱动下载位置：http://chromedriver.chromium.org/downloads

firefox驱动下载位置：https://github.com/mozilla/geckodriver/releases

edge驱动下载位置：https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/

selenium使用参考：https://github.com/lmz2932/learnselenium
