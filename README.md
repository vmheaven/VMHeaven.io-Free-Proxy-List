# VMHeaven.io Free Proxy Lists

Welcome to **VMHeaven.io Free Proxy List**, a repository dedicated to providing continuously updated and tested lists of proxy servers.

## 🚀 Why Choose Fresh Proxy List?

- **Frequent Updates**: Lists are rebuilt every 15 minutes from independent test servers.
- **Tested Lists**: Every entry passed a live check on at least one of our test servers in its latest run. Use `verified/` for entries confirmed by several servers.
- **Filtered Networks:** AWS, Akamai and Cloudflare address ranges are excluded.
- **Community-Driven**: Star 🌟 this repo and join the growing community supporting open-access proxy resources.
- **Optimized for Developers**: Easily integrate with your tools and workflows.

## 🌟 Show Your Support!

If you find this project helpful:
- **Give us a star** ⭐ on GitHub.
- **Share** this repo with friends and colleagues.
- Contribute by submitting issues, feedback, or proxy sources.

## 💡 Features

- **Free Proxy List**: Access to HTTP, HTTPS, SOCKS4, and SOCKS5 proxies for various use cases.
- **Many Uses**: Useful for web scraping, testing and checking geo-restricted content.
- **Geolocation Support**: Choose proxies by country, see below.

## ⚠️ What to Expect

Public proxies are unstable and are run by strangers. In spot checks from an outside server in November 2026, a single try succeeded for about 25-50 % of the entries in the main lists, about 25-60 % in `verified/` and about 97 % in `tls.txt`, so try several entries and expect failures.

Our test servers also fetch a test page of their own through HTTP and SOCKS proxies and drop those caught changing it, for example by injecting scripts. This only catches what shows up during the test and many proxies do not answer it at all, so it does not make a listed proxy trustworthy.

Whoever runs a proxy can read and change unencrypted traffic. Use HTTPS, and do not send passwords or personal data through these proxies.

## 🛠 How to Use

Follow the instructions below to download the proxy lists.

### Download by Type

#### HTTP
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/http.txt -o http.txt
```

#### HTTPS
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/https.txt -o https.txt
```

#### SOCKS4
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/socks4.txt -o socks4.txt
```

#### SOCKS5
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/socks5.txt -o socks5.txt
```

#### TLS
Proxies that speak TLS themselves, confirmed by at least three test servers. Connect to them
with TLS, for example `curl -x https://IP:PORT --proxy-insecure https://example.com`.
They usually use self-signed certificates, so the connection to the proxy is encrypted but
does not prove who runs it.
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/tls.txt -o tls.txt
```

### Verified Lists

Want fewer but more reliable proxies? The `verified/` folder only contains proxies
confirmed by at least three independent test servers in their latest run. Public
proxies come and go quickly, so no list can promise that every entry still works.

```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/verified/http.txt -o http.txt
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/verified/https.txt -o https.txt
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/verified/socks4.txt -o socks4.txt
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/verified/socks5.txt -o socks5.txt
```

### Download by Country

Country-based lists follow the pattern `Country/{COUNTRY_CODE}/{type}.txt`.
Just replace `US` with the country code you need (e.g. `DE`, `GB`, `FR`, `NL`).

#### HTTP
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/Country/US/http.txt -o us-http.txt
```

#### HTTPS
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/Country/US/https.txt -o us-https.txt
```

#### SOCKS4
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/Country/US/socks4.txt -o us-socks4.txt
```

#### SOCKS5
```bash
curl -sL https://raw.githubusercontent.com/vmheaven/VMHeaven.io-Free-Proxy-List/refs/heads/main/Country/US/socks5.txt -o us-socks5.txt
```

> 💡 **Tip:** To use a different country, just swap the country code in the path. Example for Germany:
> `.../Country/DE/https.txt`

## 📣 Stay Updated

- **Open an Issue**: Share your ideas, use cases, or challenges.
- **Follow Updates**: Keep an eye on upcoming features and enhancements.

### ⭐ Don't forget to star this repo to show your support and encourage development!

[⭐ Star this repo](https://github.com/vmheaven/VMHeaven.io-Free-Proxy-List/stargazers)

## 🏆 Contributors

We welcome contributions! Submit a pull request or suggest improvements to make this project even better.

## 📢 Spread the Word

Help us grow this project:
- Tweet about it 🐦
- Mention it in your blog posts 📚
- Recommend it on forums 📢

## Disclaimer

These listings are provided for informational purposes only. Please use them for viewing purposes only. I do not encourage or support anything illegal or unlawful.