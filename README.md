# saharalabs ai bot 1.0 自动化脚本
## saharalabs.ai的项目介绍
融资4900万美元的Sahara卷起来

https://legends.saharalabs.ai/?code=HDFD0H

Sahara Legends开放积攒碎片活动，并不局限于白名单用户，简单来说就是参与任务获取碎片，积攒碎片铸造5个Sahara守护者NFT，5个守护者NFT最终合成一个终极Bitsy Soulbound NFT，模式竟然跟move很相似，Sahara融资高，投资机构厉害，前面又有move高收益的案例，大家可以冲！

## saharalabs ai bot 1.0 脚本教程

### 1、配置目录说明
#### 1.1、config目录为用户序列号
``credentials.txt`` 自动生成
#### 1.2、log目录为脚本运行日志目录
``log.txt `` 自动生成
#### 1.3 faucet目录为领水配置目录
``solver_key.txt`` 绕开cf验证的key存放,在 https://2captcha.com/ 网站申请key
``wallet_proxy.txt`` 领水钱包，格式如下：
```txt
钱包||||代理
```
#### 1.4 swap目录为交互配置目录
``private_keys.txt`` 钱包私钥
``proxy.txt``代理
``wallet_address.txt``转水地址，支持多行地址，随机抽取
``settings.json``转水设置,配置说明如下：
```json
{
  "min_value": 0.00000000001, #最小转水
  "max_value": 0.00000000002, #最大转水
  "min_delay": 1, #最小优先等级
  "max_delay": 5, #最大优先等级
  "provider_url": "https://testnet.saharalabs.ai", #转水rpc
  "proxy": "", #为空
  "flows": 10   #最大交互量
}
```
#### 1.5 sahara目录为主网任务配置目录
``token.txt`` 抓取token存放文件，配置如下
![image](https://github.com/user-attachments/assets/4eee511e-929a-40a7-8589-7cf24ebafdf7)

```txt
token1||||代理
```
### 1.6 galxe目录为银河任务配置目录
1.0版本暂时不用设置

### 2、脚本运行
