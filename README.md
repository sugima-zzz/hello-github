# hello-github
this is repositry to try github feature.
いつも大変お世話になっております。

思慮が至らず、申し訳ございません。
度々のお願いで恐縮ですが、状況を把握するため、いくつかの情報提供とご確認をお願いいたします。

cacheserve-stats による qps は、 1/15 のご提供資料では ～ の間、1/17 のご提供資料では ～ の間、
ほぼ 0 ですが、この時間帯に CacheServeサーバにクエリパケットが着信していることを
CacheServeサーバ上の tcpdump でご確認されたということでよろしいでしょうか？
ご確認された時間帯のPCAPファイルをご提供願います。

dnsperf が継続してクエリを送信している間に、CacheServeサーバの cacheserve-stats で
qps が 0 を記録したため、cacheserveサービスを再起動したところ、
cacheserve-stats の qps から CacheServe による送受信を確認できた。
（dnsperf は 事象発生中、一度も停止していない想定です）
というとこでよろしいでしょうか？
前述のとおり、1/15 のご提供資料では ～ の間、qps はほぼ 0 ですが、
その後の cacheserveサービスの再起動は、ジャーナルログから、mm:dd xx:xx 頃と記録されています。
ですが、dnsperf は xx:xx から 300 秒（ｘｘ：ｘｘまで）の実行で、一旦終了しており、
ご提供いただいた資料には、上記事象を示す記録はございませんでした。
上記事象をご確認いただきました時間帯の、tcpdump、dnsperf、cacheserve-stats のログが
ございましたらご提供願います。

＜ジャーナルログのご提供依頼＞

先のメールで dnsperf の -b オプションをご案内させていただきましたが、お試しいただけましたでしょうか？
状況をお知らせいただけましたならば幸いです。


繰り返しとなり恐縮ですが、これまでご提供いただきました資料からは、
CacheServe の問題を示す情報は確認できておりません。
ご迷惑をおかけしますが、新たな情報をご提供いただけましたなら、
調査、解析が終了するまでの間、お待ちいただけますようお願い申し上げます。






aa
bb
cc
あ
い

う
working repository for git article
- [x] update readme
- [x] default branch
- [x] **epic branch**
- [x] pull request template
- [x] add pull request to project
