{
  "Version": "1.0.0",
  "ReleaseNotes": "Nova Atualização Disponível",
  "UrlUpdate": "https://kiritosshxd.github.io/Conecta4g_site/UrlUpdate",
  "Sms": "https://kiritosshxd.github.io/Conecta4g_site/UrlSms",
  "EmailFeedback": "kiritosshxd5733@gmail.com",
  "UrlContato": "https://t.me/kiritosshxd",
  "UrlTermos": "https://kiritosshxd.github.io/Conecta4g_site/termos.html",
  "CheckUser": "true",
  "Udp": [
    {
      "Porta": "7300"
    }
  ],
  "Servers": [
    {
      "Name": "Servidor BR",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "2.marcionetweb.tk",
      "CheckUser": "http://sua_api",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
  "Networks": [
    {
      "Name": "marcio",
      "FLAG": "vivo",
      "Payload": "MKCOL /? compre.vivo.com.br/ HTTP/1.0[lf]Host: 2.marcionetweb.tk \nUpgrade: minerdso\nConnection: Keep-Alive\nUser-Agent:*\n\n",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.6.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.6.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "Tim",
      "FLAG": "tim",
      "Payload": "GET ws://cdnjs.cloudflare.com HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "cdnjs.cloudflare.com",
      "TlsIP": "104.16.18.94",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Claro",
      "FLAG": "claro",
      "Payload": "GET ws://no.descomplica.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "no.descomplica.com.br",
      "TlsIP": "199.60.103.228",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "Oi",
      "FLAG": "oi",
      "Payload": "GET / HTTP/1.1[crlf]Host: [host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "80",
      "Info": "Proxy"
    }
  ]
}
