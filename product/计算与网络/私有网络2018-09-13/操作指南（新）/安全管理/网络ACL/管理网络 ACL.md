## 增加网络 ACL 规则
1. 登录 [腾讯云控制台](https://console.cloud.tencent.com/) ，选择【云产品】>【网络】>【私有网络】，进入私有网络控制台。
2. 单击左侧目录中的【安全】>【网络 ACL】，进入管理页面。
3. 在列表中，找到需要修改的网络 ACL，单击其 ID，进入详情页。
4. 新增出/入站规则，单击【出站规则】或【入站规则】>【编辑】>【新增一行】，选择协议类型并输入端口、源 IP，以及选择策略。
![](https://main.qcloudimg.com/raw/e24739da05d191661024a92d3738a3d4.png)
5. 单击【保存】即可。

## 删除网络 ACL 规则
1. 登录 [腾讯云控制台](https://console.cloud.tencent.com/) ，选择【云产品】>【网络】>【私有网络】，进入私有网络控制台。
2. 单击左侧目录中的【安全】>【网络 ACL】，进入管理页面。
3. 在列表中，找到需要删除的网络 ACL，单击其 ID，进入"基本信息"页面。
4. 单击【入站规则】或【出站规则】选项卡，进入"规则列表"页面。
![1](https://main.qcloudimg.com/raw/82eb2e498aee5d82d1a6d7a321610fac.png)
5. 单击【编辑】。删除入站规则与删除出站规则步骤一致，本文以删除入站规则为例。
![](https://main.qcloudimg.com/raw/2cfa0c2dea110d2f2fe830e6b4208430.png)
6. 在列表中，找到需要删除的规则所在行，单击操作栏中【删除】。
![3](https://main.qcloudimg.com/raw/693c4ea822673f9c29e61320f8a8e772.png)
7. 此时本条 ACL 规则置灰。若本次删除属于误操作，您可单击【恢复删除】，将其恢复。
 ![](https://main.qcloudimg.com/raw/dca5294bec96645dce76b098bcee6782.png)
8. 单击【保存】，保存上述操作。
>!ACL规则的删除或恢复删除操作，必须保存后才会生效。

## 子网关联网络 ACL
1. 登录 [腾讯云控制台](https://console.cloud.tencent.com/) ，选择【云产品】>【网络】>【私有网络】，进入私有网络控制台。
2. 单击左侧目录中的【安全】>【网络 ACL】，进入管理页面。
3. 在列表中，找到需要关联的网络 ACL，单击其 ID，进入详情页。
4. 在“基本信息”页面的“关联子网”模块，单击【新增关联】。
![](https://main.qcloudimg.com/raw/a6113f7b3c76b6b1be07d6edd26f3530.png)
5. 在弹出框中，选择需要关联的子网，单击【确定】即可。
![2](https://main.qcloudimg.com/raw/a7a608ebaf447a6fc24a6f9f313d14e6.png)

## 子网解关联网络 ACL
1. 登录 [腾讯云控制台](https://console.cloud.tencent.com/) ，选择【云产品】>【网络】>【私有网络】，进入私有网络控制台。
2. 单击左侧目录中的【安全】>【网络 ACL】，进入管理页面。
3. 在列表中，找到需要解除关联的网络 ACL，单击其 ID，进入详情页。
4. 解除关联子网有以下方法：
 - 方法一：在“基本信息”页面的“关联子网”模块，找到需要解除关联的子网，单击【解绑】。
![1](https://main.qcloudimg.com/raw/beb96d3bea157af5f5c9c76c85b1cc7f.png)
 - 方法二：在“基本信息”页面的“关联子网”模块，勾选所有需要解除关联的子网，单击【批量解绑】。
![2](https://main.qcloudimg.com/raw/ab35d623e1d61749dcb6594b8de21901.png)
5. 在弹出框中单击【确认】即可。
![3](https://main.qcloudimg.com/raw/93c7ebc3980f072d1194e87538ab1a79.png)

## 删除网络 ACL
1. 登录 [腾讯云控制台](https://console.cloud.tencent.com/) ，选择【云产品】>【网络】>【私有网络】，进入私有网络控制台。
2. 单击左侧目录中的【安全】>【网络 ACL】，进入管理页面。
3. 选择地域和私有网络。
4. 在列表中，找到需要删除的网络 ACL，单击其 ID，进入详情页。
5. 单击【删除】并确认操作，即可删除该网络 ACL 及该网络 ACL 的所有规则。
![](https://main.qcloudimg.com/raw/52d13aac33e609dc59d132ffa4c71171.png)
>!若【删除】按钮置灰，如上图中的网络 ACL`testEg`，表示该网络 ACL 正与子网相关联，您需要先解除子网关联后，才能进行删除操作。

