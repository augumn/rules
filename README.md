# Rules

Public rule sets for Clash, Mihomo, Surge, and compatible clients.

Raw URL format:

```text
https://raw.githubusercontent.com/augumn/rules/refs/heads/main/<file>
```

Example:

```text
https://raw.githubusercontent.com/augumn/rules/refs/heads/main/github.txt
```

## File Types

- `*.txt`: Classic Clash/Mihomo rule lines, usually consumed by `rule-providers`.
- `*.list`: Plain rule list files.
- `2.clash.rule.yaml`: Clash/Mihomo rule-provider bundle.
- `1.surgerule.conf`: Surge rule-set bundle.
- `unlockmediaAll.txt`: Plain domain list. Convert it before using it as a classic Clash/Mihomo rule-provider if your client requires classic rule syntax.

## Rule Sets

- `adult.txt`: Adult media and adult live-site domains.
- `bbc.txt`: BBC related domains.
- `cloud-storage.txt`: Cloud storage services such as MEGA, Terabox, and PikPak.
- `cloudflare.txt`: Cloudflare related domains.
- `crypto.txt`: Crypto exchange and crypto asset domains such as Binance and Coinbase.
- `docker.txt`: Docker Hub, Docker Desktop downloads, and common container registry domains.
- `facebook.txt`: Meta/Facebook/Instagram/WhatsApp related domains.
- `github.txt`: GitHub main domains.
- `githubusercontent.txt`: GitHub asset and user-content domains.
- `huggingface.txt`: Hugging Face, Spaces, model download, LFS, and Xet transfer domains.
- `google.txt`: Google service domains.
- `googleother.txt`: Additional Google domains.
- `googlevideo.txt`: YouTube/Google video domains.
- `microsoft.txt`: Microsoft service domains.
- `microsoftmedia.txt`: Microsoft media domains.
- `nodejs.txt`: Node.js download and distribution domains.
- `npm.txt`: npm registry and package distribution domains.
- `openai.txt`: OpenAI related domains.
- `python.txt`: Python, PyPI, and Python package distribution domains.
- `java-dev.txt`: Maven and Java build ecosystem domains.
- `shared-infra.txt`: Shared CDN, certificate validation, and cloud object-storage infrastructure.
- `twitter.txt`: X/Twitter related domains.
- `others.txt`: Remaining rules that have not yet been split into a dedicated category.

## Maintenance

- Keep service-specific files focused on domains owned by or strongly tied to that service.
- Put shared CDN, certificate validation, and object-storage infrastructure in `shared-infra.txt`.
- Add new categories when a group of domains needs its own proxy policy.
- Keep generated raw URLs public and stable.
