<h1 align=center> v2ray parser </h1>
<p align="center">Made with 💝</p>


<h2>Motivation</h2>
Coz Im lazy to write out the <code>proxy-provider.yaml</code> on <a href="https://github.com/Dreamacro/clash/wiki/configuration#proxy-providers">Openclash</a> if server expired or dead. So I create this tools to simplify rewrite <code>proxy-provider.yaml</code> on openclash dir.


<h3>TODO</h3>

- Added other v2ray type
- Auto detect v2ray type
- A web app for openwrt


<h3>Requirements</h3>

- ruby
- base64

For OpenWrt can install through command below
    
    opkg update \
    opkg install ruby-base64 ruby-optparse


<h3>Usage</h3>

    v2c --help

Example usage:

<img src=res/example.png alt="example">


<h3>Credits</h3>

- [ruby-optparse](https://ruby-doc.org/stdlib-2.7.1/libdoc/optparse/rdoc/OptionParser.html)
- [base64](https://github.com/ruby/base64.git)