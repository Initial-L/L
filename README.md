
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/H-Pri3l/v4/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh</code></pre>

<table>
<thead>
<tr>
<th>ALTERNATIF PORT</th>
<th>NETWORK PORT</th>
</tr>
</thead>
<tbody>
<tr>
<td>HTTPS</td>
<td>2053, 2083, 2087, 2096, 8443</td>
</tr>
<tr>
<td>HTTP</td>
<td>8080, 8880, 2052, 2082, 2086, 2095</td>
</tr>
</tbody