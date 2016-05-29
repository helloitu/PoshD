# PoshD
Simple python example for torrent downloads using a RSS feed
<hr>
# Instalando .......
<br>
 <font color="red">1.</font> <code>git clone https://github.com/helloitu/PoshD.git</code><br>
 <font color="red">2.</font> <code> sudo chmod +x setup.sh</code><br>
 <font color="red">3.</font> <code> ./setup.sh</code>
<br>
#Configurando suas Series preferidas para Download .....
<hr>
Vá até <code>https://showrss.info/?cs=feeds</code> e escolha sua serie preferida .....
<br>
Copie e cole o link no lugar de <code> feedRSS = "http://showrss.info/feeds/62.rss"</code>
<br>
Feito!
#Configurando o Script para rodar no background
<hr>
Como Uso um Debian , o comando é simples ....
<br>
<code>  echo 'python /home/root/PoshD/PoshD.py & ' >> /etc/rc.local</code>
