# fanqie
番茄
#DOMAIN,i.snssdk.com,REJECT
#DOMAIN,i-lq.snssdk.com,REJECT
#DOMAIN,dig.bdurl.net,REJECT

# 番茄小说去章末广告
^https?:\/\/.+\.pangolin-sdk-toutiao\.com\/api\/ad\/union\/sdk\/(get_ads|stats|settings)\/ url reject
^https?:\/\/.+\.pglstatp-toutiao\.com\/.+\/toutiao\.mp4  url reject
^https?:\/\/.+\.(pglstatp-toutiao|pstatp)\.com\/(obj|img)\/(ad-app-package|ad)\/.+ url reject
^https?:\/\/.+\.(pglstatp-toutiao|pstatp)\.com\/(obj|img)\/web\.business\.image\/.+  url reject
^https?:\/\/.+\.(pglstatp-toutiao|pstatp)\.com\/obj\/ad-pattern\/renderer url reject
^https?:\/\/gurd\.snssdk\.com\/src\/server\/v3\/package url reject
^https?:\/\/.+\.byteimg.com/tos-cn-i-1yzifmftcy\/(.+)-jpeg\.jpeg  url reject
^https?:\/\/.+\.pstatp\.com\/obj\/mosaic-legacy\/.+\?from\=ad  url reject
^https?:\/\/.+\.pstatp\.com\/bytecom\/resource\/track_log\/src\/.+  url reject
^https?:\/\/.+\.snssdk\.com\/video\/play\/1\/toutiao\/.+\/mp4 url reject
^https?:\/\/.+\.snssdk.com\/api\/ad\/.+ url reject
^http:\/\/.+\.byteimg\.com\/ad-app-package url reject
^http:\/\/.+\.byteimg\.com\/web\.business\.image url reject
# .+web\.business\.image url reject

^https?:\/\/.+\.(pglstatp-toutiao|pstatp)\.com\/(ad-app-package|ad)\/.+ url reject
^https?:\/\/adim\.pinduoduo\.com\/.+\/toutiao\?.+ url reject
^https?:\/\/.+novelapp\.fqnovelvod\.com\/.+\/video\/.+ url reject
^http:\/\/·+\.douyincdn\.com\/stage\/·+\.flv url reject

hostname = *.pangolin-sdk-toutiao,*.pangolin-sdk-toutiao.*,*.pstatp.com,*.pstatp.com.*,*.pglstatp-toutiao.com.*,*.pglstatp-toutiao.com,gurd.snssdk.com,gurd.snssdk.com.*,*default.ixigua.com,adim.pinduoduo.com,v6-novelapp.fqnovelvod.com
