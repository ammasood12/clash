# Free Clash Nodes

> I am just organizing and documenting nodes' performance while residing in China. <br/>
> All these nodes don't provide stable connections. so you have to tweak

### Testing
`General websites usually not work`<br/>
[Speed Test](https://www.highspeedinternet.com/tools/speed-test)<br/>
[Stream Test](https://www.highspeedinternet.com/tools/speed-test/streaming)

### One Click Subscription
`Mannually Build from Alvin9999 nodes`
| Type     | Status | Provider | Subscription 1 | Subscription 2 | Note |
| -------- | ------ | -------  | -------------- | -------------- | ---- |
| OneClick | Good⭐ | [Website](https://github.com/ammasood12/nodes/) | [Load Balance](https://raw.githubusercontent.com/ammasood12/nodes/refs/heads/main/clash/Load_Balance.yaml) | [Filtered](https://raw.githubusercontent.com/ammasood12/nodes/refs/heads/main/clash/Alvin9999.yaml) | Based on Alvin9999

Load Balance: Every connection will be gone through the proxy while distributing traffic through different nodes. (similar to global access, but through multiple nodes)
Filtered: Traffic will be filtered out according to rules.

`OneClick: Copy the subscription link and add it as profile in Clash`
| Type     | Status | Provider | Subscription 1 | Subscription 2 | Note |
| -------- | ------ | -------  | -------------- | -------------- | ---- |
| OneClick | Good   | [XrayVIP]( https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash) | [Direct](https://www.xrayvip.com/free.yaml) | [tt.vg](https://tt.vg/freeclash)⭐ | |
| OneClick | Poor   | [proxypool](https://proxypool.link/) | [proxypool](https://proxypool.link/clash/config)  | | |
| OneClick | Good   | [Datiya](https://free.datiya.com/) | [Link](https://free.datiya.com/uploads/20250302-clash.yaml)  | | visit website or change url to current date to update |
| OneClick | Good   | [Mahdibland](https://github.com/mahdibland/V2RayAggregator) | [Eternity](https://raw.githubusercontent.com/mahdibland/ShadowsocksAggregator/master/Eternity.yml) ⭐ | [EternityAir](https://raw.githubusercontent.com/mahdibland/ShadowsocksAggregator/master/EternityAir.yml) | |
| OneClick | Good   | [Anaer](https://github.com/anaer/Sub) | [Link](https://raw.githubusercontent.com/anaer/Sub/main/clash.yaml) | | |
| OneClick | Good   | [Nodefree.org](https://nodefree.org/) | [Link](https://nodefree.githubrowcontent.com/2025/02/20250227.yaml) | | visit website or change url to current date to update |
| OneClick | Good   | [Ermaozi](https://github.com/ermaozi/get_subscribe) | [Link](https://raw.githubusercontent.com/ermaozi/get_subscribe/main/subscribe/clash.yml) | [Link](https://git.io/emzclash) ⭐ | |
| OneClick | Slow   | [SnapdragonLee](https://github.com/SnapdragonLee/SystemProxy) | [Link](https://raw.githubusercontent.com/SnapdragonLee/SystemProxy/master/dist/clash_config.yaml) | | |
| OneClick | Poor   | [vxiaov](https://github.com/vxiaov/free_proxies) | [Link](https://cdn.jsdelivr.net/gh/vxiaov/free_proxies@main/clash/clash.provider.yaml) | | |
| OneClick | Poor   | [AiboBoxx](https://github.com/aiboboxx/clashfree) | [Link](https://github.com/aiboboxx/clashfree/blob/main/clash.yml) | | Note |
| OneClick | Good | [ZhangKaiTuGitHub](https://github.com/zhangkaiitugithub/passcro) | [SpeedNodes](https://raw.githubusercontent.com/zhangkaiitugithub/passcro/main/speednodes.yaml)⭐ | [Meta](https://raw.githubusercontent.com/zhangkaiitugithub/passcro/main/meta.yaml) | |
| OneClick | Good | [ronghuaxueleng](https://github.com/ronghuaxueleng/get_v2/tree/main/pub) | [PawDroid](https://raw.githubusercontent.com/ronghuaxueleng/get_v2/refs/heads/main/pub/pawdroid.yaml) <br/><br/> [Combine](https://raw.githubusercontent.com/ronghuaxueleng/get_v2/refs/heads/main/pub/combine.yaml)⭐ | [cfmem](https://raw.githubusercontent.com/ronghuaxueleng/get_v2/refs/heads/main/pub/cfmem.yaml) <br/><br/> [NoMoreWalls](https://raw.githubusercontent.com/ronghuaxueleng/get_v2/refs/heads/main/pub/NoMoreWalls.yaml) | Note |

Useage Tips: 
1. Update Proxy: select Profile > right click > Update
2. Stable Connection: Proxies > Global > refresh wifi icon > select node with lesser number

### Bookmarks to find nodes
`Bookmarks to find nodes`
| Type      | Provider     | Website | Note |
| --------- | ------------ | ------- | ---- |
| Manual    | freefq.com   | [Website](https://freefq.com/) | Multiple types of nodes |
| Manual    | free-ss.site | [Website](https://free-ss.site/) | provide vless, vmess nodes |
| Manual    | [Alvin9999](https://github.com/Alvin9999/new-pac) | [Link](https://github.com/Alvin9999/new-pac/wiki/v2ray%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7) | vless, vmess | 
| Manual    | [Alvin9999](https://github.com/Alvin9999/new-pac) | [Link](https://github.com/Alvin9999/new-pac/wiki/ss%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7) | ssr, ss |
| Links     | [Mermeroo](https://github.com/mermeroo/) | [Website](https://github.com/mermeroo/V2RAY-CLASH-BASE64-Subscription.Links/blob/main/SUB%20LINKS) | Links to Other nodes |
| Links     | Links        | [Website](https://github.com/VPN-Subcription-Links/ClashX-V2Ray-TopFreeProxy) | Note |

### Convert SSR, SS, VLess, VMess
| Type      | Website        | Config | Notes |
| --------- | -------------- | ------ | ----- |
|ss, ssr, vmess | https://acl4ssr-sub.github.io/ |  Client: Clash --> Remote Configuration: None --> Backend Address: sub.xeton.dev
|multiple | https://v2rayse.com/node-convert |
|vmess, trojan | https://sshkit.com/subconverter/ | output: Load Balance (Only Clash) | Produce plain connection, no proxy filtering |

Personal Tips: 
1. Use [v2rayse](https://v2rayse.com/node-convert) for making a template file filters including how many proxies are required in total by using same address multiple times. (vmess links don't work properly)
2. Use [SSHkit](https://sshkit.com/subconverter/) for making plain YAML file and add all other proxies in that. simple direct connections with load balance.





