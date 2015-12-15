# nagios-plugin-check_dig
URL:http://nagios-plugins.org/doc/man/check_dig.html<br>
<br>
ゾーンの正常性チェック用<br>
下手に自作するよりこれ流用するが吉<br>
<br>
キャッシュDNSに対して<br>
/usr/lib64/nagios/plugins/check_dig -H 8.8.8.8 -l google.com SOA<br>
<br>
権威DNSに対して<br>
/usr/lib64/nagios/plugins/check_dig -H ns1.google.com -l google.com +norec SOA<br>
<br>
