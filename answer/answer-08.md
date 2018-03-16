比赛的提交方式主要有两种：**K-Lab Notebook内提交**和**直接上传文件提交**，具体要求请查看【比赛页面】详情。
* K-Lab Notebook内提交的方法

    * 点击比赛页面下的【提交】按钮，查看团队提交token，每个团队的提交token唯一。
   * 打开参赛的K-Lab项目，在最后执行如下命令：
    ```
    # 下载提交工具至当前目录，仅需执行一次
    !wget -nv -O kesci_submit https://cdn.kesci.com/submit_tool/v1/kesci_submit&&chmod +x kesci_submit
    # 提交文件
    ！./kesci_submit -token xxx -file submission_file
    ```
    * 完成上述步骤后，出现如下信息则表示提交成功
    ```
    Kesci Submit Tool
    Working...
    Success.
    OK
    ```
    * 耐心等待1-2分钟，移步至【我的提交】查看评审结果。

* 直接上传文件提交

    * 在提交页面下按照提示上传文件
    * 完成提交后移步至【我的提交】查看评审结果