# nagios-plugin-check_dig
URL:http://nagios-plugins.org/doc/man/check_dig.html<br>
<br>
Package:<br>
nagios-plugins-dig-2.0.3-3.el6.x86_64<br>
<br>
---------------------------------------------<br>
Name        : nagios-plugins-dig<br>
Arch        : x86_64<br>
Version     : 2.0.3<br>
Release     : 3.el6<br>
Size        : 56 k<br>
Repo        : installed<br>
From repo   : epel<br>
Summary     : Nagios Plugin - check_dig<br>
URL         : https://www.nagios-plugins.org/<br>
License     : GPLv2+<br>
Description : Provides check_dig support for Nagios.<br>
---------------------------------------------<br>
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
