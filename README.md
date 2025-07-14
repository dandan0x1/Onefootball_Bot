# Onefootball
注册rf:
https://ofc.onefootball.com/s2?referral=EK8Oz3yfre1z


# onefootball 脚本使用教程

## 目录分布说明
```log
config 配置目录
log 日志目录
```

## config目录

### config/config.json 主脚本配置
```json
# 常规配置
sleep = 15 # 请求之间的延迟时间（秒）

# 钱包配置
num_wallets = 15 # 每批处理的钱包数量（考虑自己的并发情况）
sleep_wallets = 200 # 钱包批次之间的休眠时间（秒）
max_concurrent_wallets = 15 # 同时运行的钱包数量

# 推荐码
ref = 'ajPumDYOs8XU' # 推荐码已设置

# 重试配置
retray = 3 # 发生错误时重试的次数
base_delay = 3.0 # 初始延迟时间
backoff_factor = 2.0 # 延迟乘数
max_delay = 50.0 # 最大延迟时间
auto_run = true # 启用自动运行模式 false 可以切换回手动模式
run_interval_hours = 24, # 运行间隔（小时）
retry_interval_hours = 1 # 错误重试间隔（小时）
```

### config/private_keys.txt 钱包密钥配置

```txt
密钥一行一个
```

### config/proxy.txt 代理配置
```txt
代理一行一个
```

### config/twitter_tokens.txt x的token配置

```txt
一行一个
```

怎么抓取

``F12 → 应用程序选项卡 → Cookies → https://x.com → auth_token``


<img width="1582" height="994" alt="1752455733935" src="https://github.com/user-attachments/assets/5c029baf-0d58-4d53-bee5-0c02f18ba165" />

## log目录
自动生成
