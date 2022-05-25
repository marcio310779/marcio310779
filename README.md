{
  "Version": "1.1.1",
  "ReleaseNotes": "",
  "UrlUpdate": "https://kiritosshxd.github.io/Conecta4g_site/UrlUpdate",
  "Sms": "https://kiritosshxd.github .io/Conecta4g_site/UrlSms",
  "EmailFeedback": "",
  "UrlContato": "",
  "UrlTermos": "",
  "CheckUser": "true",
  "Udp": [
    {
      "Porta": "7300"












    }
  ],
  "Servers": [
    {
      "Name": "CONECTA4G | PLUS",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "2.marcionetweb.tk",
      "CheckUser": "http://38.9.119.110:5454/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": "1234"
    },
    {
      "Name": "PREMIUM 02 | PLUS",
      "TYPE": "free",
      "FLAG": "br.png",
      "ServerIP": "2.marcionetweb.tk",
      "CheckUser": "http://38.9.119.110:5454/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": "1234"
    }
  ],
  "Networks": [
    {
      "Name": "VIVO PROXY 01",
      "FLAG": "vivo",
      "Payload": "MKCOL /? compre.vivo.com.br/ HTTP/1.0[lf]Host: 2.marcionetweb.tk \nUpgrade: minerdso\nConnection: Keep-Alive\nUser-Agent:*\n\n",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.6.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO TLS 02",
      "FLAG": "vivo",
      "Payload": "MKCOL /? compre.vivo.com.br/ HTTP/1.0[lf]Host: 2.marcionetweb.tk \nUpgrade: minerdso\nConnection: Keep-Alive\nUser-Agent:*\n\n",
      "SNI": "[app_host]",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM PROXY 01",
      "FLAG": "tim",
      "Payload": "GET wss://mobilidade.cloud.caixa.gov.br [protocol][crlf]Host: [app_host][crlf]X-Forwarded-For: [app_host][crlf]Connection: Keep-Alive[crlf]User-Agent: [ua][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "TIM TLS 02",
      "FLAG": "tim",
      "Payload": "GET ws://mobilidade.cloud.caixa.gov.br HTTP/1.1\nHost: [app_host]\nUpgrade: WebSocket\n\n",
      "SNI": "mobilidade.cloud.caixa.gov.br",
      "TlsIP": "mobilidade.cloud.caixa.gov.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM TLS 03",
      "FLAG": "tim",
      "Payload": "GET wss://m.timbancavirtual.com.br/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "m.timbancavirtual.com.br",
      "TlsIP": "m.timbancavirtual.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM TLS 04",
      "FLAG": "tim",
      "Payload": "GET wss://cdnjs.cloudflare.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "cdnjs.cloudflare.com",
      "TlsIP": "cdnjs.cloudflare.com",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM TLS 05",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.16.19.94",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO TLS 01",
      "FLAG": "claro",
      "Payload": "GET ws://mobilidade.cloud.caixa.gov.br HTTP/1.1\nHost: [app_host]\nUpgrade: WebSocket\n\n",
      "SNI": "mobilidade.cloud.caixa.gov.br",
      "TlsIP": "mobilidade.cloud.caixa.gov.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO TLS 02",
      "FLAG": "claro",
      "Payload": "GET ws://parceirosclaro.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: WebSocket\n\n",
      "SNI": "parceirosclaro.com.br",
      "TlsIP": "parceirosclaro.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO SSL 03",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "dns.web.whatsapp.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "CLARO SSL 04",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "m.waze.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "CLARO SSL 05",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "web.whatsapp.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "CLARO SSL 06",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "m.twitter.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "OI PROXY 01",
      "FLAG": "oi",
      "Payload": "GET / HTTP/1.1[crlf]Host: [host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "OI TLS 02",
      "FLAG": "oi",
      "Payload": "GET ws://mobilidade.cloud.caixa.gov.br HTTP/1.1\nHost: [app_host]\nUpgrade: WebSocket\n\n",
      "SNI": "mobilidade.cloud.caixa.gov.br",
      "TlsIP": "mobilidade.cloud.caixa.gov.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    }
  ]
}
