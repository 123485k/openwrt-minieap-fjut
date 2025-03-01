# minieap-fjut for OpenWrt 
适用于福建理工大学校园网认证的minieap
### 修改 
修改默认服务为 `校园网`,
### 构建
下载适合你设备的[OpenWrt SDK](https://downloads.openwrt.org/).

```sh
cd /path/to/your/sdk
git clone https://github.com/123485k/openwrt-minieap-fjut.git package/minieap
make menuconfig # choose `minieap` in section `Network`
make package/minieap/compile V=s
```
