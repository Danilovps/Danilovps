{
  "Version": "2..232",
  "ReleaseNotes": "Nova Atualização Disponível",
  "UrlUpdate": "",
  "Sms": "BOTAR LINK DO SMS AQUI",
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
      "Name": "(61)99505-6483",
      "TYPE": "Premium",
      "FLAG": "br.png",
      "ServerIP": "aws.falconet.xyz",
      "CheckUser": "http://149.78.186.58:5454/checkUser",
      "ServerPort": "80",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
"Networks": [
    {
    "Name": "TIM(saldo expirado)",
            "FLAG": "tim",
            "Payload": "HTTP/1.8 200[lf]Host: google.com[lf][lf]",
            "SNI": "[app_host]",
            "TlsIP": "18.228.211.119",
            "ProxyIP": "18.228.211.119",
            "ProxyPort": "80",
            "Info": "Proxy"
     },
     {
          "Name": "TIM(saldo valido)",
            "FLAG": "tim",
            "Payload": "GET /cdn-cgi/trace HTTP/1.1[lf]Host: apf.maisvantagenstim.com.br[crlf][crlf][split][crlf]GET- / HTTP/1.1[crlf]Host: [host][crlf]Upgrade: Websocket[crlf][crlf]",
            "SNI": "[app_host]",
            "TlsIP": "18.228.211.119",
            "ProxyIP": "apf.maisvantagenstim.com.br",
            "ProxyPort": "80",
            "Info": "Proxy"
        
        }
    ]
}
