# MacOSX10.11.sdk.tar.gz
BTC Gitian building Mac OS SDK

```bash
cd && \
git clone https://github.com/cryptozeny/MacOSX10.11.sdk.tar.gz.git && \
cd MacOSX10.11.sdk.tar.gz/ && \
echo "fc65dd34a3665a549cf2dc005c1d13fcead9ba17cadac6dfd0ebc46435729898" MacOSX10.11.sdk.tar.gz | sha256sum -c && \
mkdir -p ~/gitian-builder/inputs && \
cp MacOSX10.11.sdk.tar.gz ~/gitian-builder/inputs/MacOSX10.11.sdk.tar.gz
```
