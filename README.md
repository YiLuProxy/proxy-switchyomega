# How to Configure Proxy SwitchyOmega Extension?  
This article will show you how to use [YiLu Proxy](https://yilu.us) with [Proxy SwitchyOmega](https://yilu.us/integration/yilu-proxy-in-switchyomega-chrome-extension) extension in Google Chrome browser.  

SwitchyOmega is a proxy extension that can help you manage and switch multiple proxy settings easily and quickly. This article will show you how to use YiLu Proxy in SwitchyOmega in Google Chrome browser.  

![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/SwitchyOmega-yilu-1024x576.jpg "Proxy SwitchyOmega")

Download YiLuProxy: https://yilu.us/download  

## YiLu Proxy settings  

### 1. Set YiLu Proxy “settings”  
Proxy port (Local port): random or custom, here I set 1080;  
Port forward: set the port range according to your needs, if you want to use 11 IPs at the same time, you can set 5500-5510;  
Bind address: 127.0.0.1;  
Proxy engine settings: select ”YiLu Portable Proxy Engine”;  
Proxy rules: select the second and fourth rules;  
Then don't forget to save!  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87.png "Proxy SwitchyOmega")

### 2. Local fixed port forward  

Right-click an IP and select “Connect” or directly double-click an IP.  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/09/port-forwarding-IP-1024x328.png "Proxy SwitchyOmega")

### 3. Multi-port forward  
Right-click an IP and select a proxy port.  

![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/09/multi-port-forwards-setting.png "Proxy SwitchyOmega")

### 4. Rotating IP port forward  

Select a country, state, city, and the number of refreshing IPs, Then click “Refresh (HTTP/SOCKS5)”.  
Note:  
⦁ Rotating residential IP supports selecting state and city, but rotating datacenter IP only supports selecting country.  
⦁ Rotating IPs support HTTP and Socks5 protocols.  

Then forward an IP to a proxy port:  

![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/08/rotating-IP.png "Proxy SwitchyOmega")

### 5.Port Forward List  
You can check proxy port’s information in “Port Forward List” on the top right.  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/setting-ports-1.png "Proxy SwitchyOmega")


## SwitchyOmega Settings  
Firstly, install proxy SwitchyOmega extension in Google Chrome browser: https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif

### 1. Open SwitchyOmega's Options  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/open-proxy-2.png "Proxy SwitchyOmega")


### 2. Click "New profile"  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/new-profile-3-1024x503.png "Proxy SwitchyOmega")


### 3. Fill in a "Profile name", choose "Proxy Profile" type and click "Create"  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/name-yiluproxy-4.png "Proxy SwitchyOmega")


### 4. Fill in the proxy server details  
Protocol: SOCKS5  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/type-socks5-5-1024x453.png "Proxy SwitchyOmega")


Server: 127.0.0.1  
Port:1080  
The port is set in YiLuProxy, you can also enter another proxy port, such as 5500, 5501, or 5502.  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/ports-6.png "Proxy SwitchyOmega")


5. Click ”Apply changes”.  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/apply-change-7-1024x466.png "Proxy SwitchyOmega")


6. Click the SwitchyOmega extension icon and choose your configured proxy.  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/configuration-yiluproxy-8.png "Proxy SwitchyOmega")


7. Check proxy IP.  

Then you can check the IP on Chrome browser by enter “ipinfo.io”, and that is the IP forward to port 1080 in YiLu Proxy.  
![Proxy SwitchyOmega](https://api.yilu.us/wp-content/uploads/2022/11/check-ip-9.png "Proxy SwitchyOmega")

The article is from https://yilu.us/integration/yilu-proxy-in-switchyomega-chrome-extension
