# dsh-web-search-bing

Bing HTML web search provider for the ctx.web seam (keyless, registers search provider id 'bing')

由 dsh-super-injector dev_scaffold_plugin 生成。

## 构建与注入

```bash
(prebuilt - no build step required)
# 注入器环境内：dev_inject_plugin <本目录>
```

## Configuration

- DSH_BING_RELAY_IPS - comma-separated local relay IPs the relay fetch provider treats as allowed egress (in addition to public IPs). Default: empty.
- DSH_BING_INTERCEPT_HOSTS - comma-separated network intercept gateway hosts; when a fetch redirect lands on one, the fetch errors out immediately instead of returning the block page. Default: empty.
