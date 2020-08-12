# TelegramBotShell
Envio de mensagens para o telegram por meio de shell script para grupo/usuário <br>

<b>Requerimentos</b>

Debian/Ubuntu:
<pre>apt install curl wget zip</pre>

CentOS / Fedora / Red hat
<pre>yum install curl wget zip</pre>

<b>Instalacação:</b>
<pre>
wget https://raw.githubusercontent.com/remontti/telegramBotShell/master/telegram -O /bin/telegram
chmod +x /bin/telegram</pre>

<b>Modelo de uso:</b>

- -m: Para enviar uma mensagem
     <pre>ex: telegram -m "ID Chat" "Mensagem linha 1" "Mensagem linha 2" "Mensagem linha 3"
  ex: telegram -m "ID Usuário" "Mensagem linha 1" "Mensagem linha 2" "Mensagem linha 3"</pre>

- -f: Para enviar um arquivo
     <pre>ex: telegram -f "-100000000" "/diretorio/arquivo" "nome do arquivo compactado" "Comentário"
  ex: telegram -f "12345689" "/var/log/syslog" "syslog" "Logs do sistema"</pre>
