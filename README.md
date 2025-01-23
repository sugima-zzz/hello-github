# hello-github
this is repositry to try github feature.
いつも大変お世話になっております。

思慮が至らず、申し訳ございません。
度々のお願いで恐縮ですが、状況を把握するため、いくつかの情報提供とご確認をお願いいたします。

cacheserve-stats による qps は、 1/15 のご提供資料では ～ の間、1/17 のご提供資料では ～ の間、
ほぼ 0 ですが、この時間帯に CacheServeサーバにクエリパケットが着信していることを
CacheServeサーバ上の tcpdump でご確認されたということでよろしいでしょうか？
1/17 のご提供資料になりますが、dnsperf の送信件数がｘｘ、CacheServe の処理件数がｘｘと、
数字を見る限り特に矛盾もなく、クエリの lost もございません。
（dnsperf が送信し続けているにもかかわらず、CacheServe が未処理となりますと、dnsperf の件数がはるかに多くなると考えられます。）
こちらでも確認させていただきたく、事象をご確認された時間帯のPCAPファイルをご提供いただけないでしょうか。

ご確認内容ですが、
dnsperf が継続してクエリを送信している間に、CacheServeサーバの cacheserve-stats で
qps が 0 を記録したため、cacheserveサービスを再起動したところ、
cacheserve-stats の qps から CacheServe による送受信を確認できた。
（dnsperf は 事象発生中、一度も停止していない想定です）
というとこでよろしいでしょうか？
前述のとおり、1/15 のご提供資料では ～ の間、qps はほぼ 0 ですが、
その後の cacheserveサービスの再起動は、ジャーナルログ()から、mm:dd xx:xx 頃と記録されています。
ですが、dnsperf は xx:xx から 300 秒（ｘｘ：ｘｘまで）の実行で、一旦終了しており、
ご提供いただいた資料には、上記事象を示す記録はございませんでした。
上記事象をご確認いただきました時間帯の、tcpdump、dnsperf、cacheserve-stats のログが
ございましたらご提供いただけないでしょうか。

＜ジャーナルログのご提供依頼＞
再度、最新のジャーナルログの取得をお願いいたします。

先のメールで dnsperf の -b オプションをご案内させていただきましたが、お試しいただけましたでしょうか？
切り分けのため状況をお知らせいただけましたならば幸いです。


ご提供いただきました資料から、CacheServe の問題を示す情報がないかを主眼に調査、解析を進めさせていただいております。
繰り返しとなり恐縮ですが、これまでご提供いただきました資料からは、
CacheServe の問題を示す情報は確認できておりません。
ご不便をおかけしますが、新たな情報をご提供いただけましたなら、
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
