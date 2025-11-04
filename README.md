
### INSTALL SCRIPT >2
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/nexus-bot-dev/nexust/main/main.sh && chmod +x main.sh && sed -i -e 's/\r$//' main.sh && screen -S main ./main.sh
</code></pre>
