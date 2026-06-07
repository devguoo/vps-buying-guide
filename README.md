# VPS Buying Guide

> Archived repository. This page is kept as a historical VPS buying checklist, not as a live pricing or promotion page.

This repository was originally created as a general VPS provider buying guide. It is no longer the main maintained guide, because VPS pricing, stock, datacenter availability and promotions change frequently.

For current tools and guides, start here instead:

| Need | Maintained Resource |
|---|---|
| General VPS tools and server resources | [awesome-vps-tools](https://github.com/devguoo/awesome-vps-tools) |
| BandwagonHost / 搬瓦工 speed test and datacenter notes | [bwg-speed-test](https://github.com/devguoo/bwg-speed-test) |
| Cloudways pricing and billing notes | [cloudways-pricing](https://github.com/devguoo/cloudways-pricing) |
| 中文搬瓦工套餐、库存和购买前判断 | [BWH Guide](https://www.bwhguide.com/?utm_source=github&utm_medium=repo&utm_campaign=vps_buying_guide_archive&utm_content=readme_current_resources) |
| Cloudways English pricing and review notes | [CloudwaysGuide](https://www.cloudwaysguide.com/?utm_source=github&utm_medium=repo&utm_campaign=vps_buying_guide_archive&utm_content=readme_current_resources) |

## Safe VPS Buying Checklist

Use this checklist before choosing any VPS provider:

1. **Use case**: blog, WordPress, development, proxy-like testing, business site, database, or file service.
2. **Audience region**: where your users are, and whether you need Asia, US, Europe or global access.
3. **Network route**: latency, packet loss, peak-hour stability and whether the route matches your target users.
4. **Plan limits**: CPU, RAM, storage, monthly transfer, bandwidth and upgrade path.
5. **Billing model**: hourly, monthly, quarterly, annual, renewal price and refund policy.
6. **Stock and datacenter availability**: final availability should be checked on the actual order page.
7. **Operational work**: whether you want self-managed VPS work or a managed hosting platform.

## Provider Choice Notes

Different providers are useful for different situations:

- **Self-managed VPS providers** are better when you want control, SSH access, custom software and lower operating cost.
- **Managed WordPress / managed cloud providers** are better when you want less server maintenance and more application-level convenience.
- **Asia-focused route providers** can matter when the target users are mainly in China, Hong Kong, Japan, Singapore or nearby regions.
- **Hourly-billing cloud providers** are useful for short tests and temporary workloads.

Avoid choosing only by the cheapest advertised price. The final decision should include route quality, stock, billing cycle, support model and your own maintenance ability.

## Test Before You Buy

For route-sensitive VPS usage, test from the network you care about:

```bash
ping -c 10 TARGET_IP
traceroute TARGET_IP
```

For BandwagonHost / 搬瓦工 route notes, see:

- [bwg-speed-test](https://github.com/devguoo/bwg-speed-test)
- [BandwagonHost speed test docs](https://devguoo.github.io/bwg-speed-test/)

## Repository Status

This repository is intentionally kept small and archived in practice:

- No live price table is maintained here.
- No direct affiliate or referral links are included here.
- No provider ranking is guaranteed to stay current.
- New VPS notes should be added to the maintained repositories listed above.

## License

MIT
