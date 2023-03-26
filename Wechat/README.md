# 微信配置

默认配置模式下，微信的两个分流域名qlogo.cn qpic.cn会走proxy，可能会造成微信卡顿现象，建议把这两个域名，添加到配置文件的domain-suffix direct规则下，为了方便起见，将这两个域名打包成规则集。
