## Surge

[Host]

i.scdn.co = 117.18.232.151

p.scdn.co = 117.18.232.151

r.scdn.co = 117.18.232.151

t.scdn.co = 117.18.232.151

u.scdn.co = 117.18.232.151

audio-ec.spotify.com = 117.18.232.151


[Rule]

// Spotify

IP-CIDR,43.249.72.0/22,DIRECT

IP-CIDR,117.18.232.151/32,DIRECT

IP-CIDR,151.101.76.246/32,DIRECT

DOMAIN-SUFFIX,e.scdn.co,Proxy

DOMAIN-SUFFIX,o.scdn.co,Proxy

DOMAIN-SUFFIX,audio-ec.spotify.com,DIRECT

DOMAIN-SUFFIX,scdn.co,DIRECT

DOMAIN-SUFFIX,spotify.com,DIRECT

DOMAIN-SUFFIX,www.spotify.com,Proxy

## Dnsmasq

address=/i.scdn.co/117.18.232.151

address=/p.scdn.co/117.18.232.151

address=/r.scdn.co/117.18.232.151

address=/t.scdn.co/117.18.232.151

address=/u.scdn.co/117.18.232.151

address=/audio-ec.spotify.com/117.18.232.151


(117.18.232.151 无需代理 )

## hosts
117.18.232.151 i.scdn.co

117.18.232.151 p.scdn.co

117.18.232.151 r.scdn.co

117.18.232.151 t.scdn.co

117.18.232.151 u.scdn.co

117.18.232.151 audio-ec.spotify.com

(117.18.232.151 无需代理 )
