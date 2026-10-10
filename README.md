<h1 align="center">EVGENIY TROFIMOV</h1>

<p align="center"><b>Security researcher</b></p>

---

I'm a security researcher. I dig into open-source libraries looking for vulnerabilities, and I also cover already-disclosed ones on my blog, but in more concrete detail: root cause, exploitation path, the fix, and the tests that prove it.

My second focus is **AI / LLM security**. I have published articles on the topic and am writing a master's thesis in this area.

## Focus

- **Vulnerability research in open-source libraries:** finding new bugs, reproducing and analysing public ones
- **Write-ups with substance:** root cause, patch review, regression tests
- **AI / LLM security:** attacks on and defences for LLM-based systems, including LLM-assisted penetration testing
- **Open source:** I contribute to open-source projects ([merged PRs](https://github.com/pulls?q=is%3Apr+author%3Ahed1ad+is%3Amerged+-user%3Ahed1ad))

## Projects I'm proud of

| Project | About | Stack |
|---|---|---|
| [CVE-Omarchy-Plugin](https://github.com/hed1ad/CVE-Omarchy-Plugin) | Bar widget for [Omarchy](https://omarchy.org/). Type a CVE ID or a product name and get the vulnerability description, plus the public exploits found in the local ExploitDB mirror, including their local file paths. Exploit search works offline; only the CVE description lookup uses the network. | QML, shell, searchsploit (ExploitDB), CIRCL CVE API |
| [waf](https://github.com/hed1ad/waf) | WAF Dashboard: a product layer around the mature ModSecurity engine. Collects audit and access events, aggregates attack statistics, and shows them in a dashboard with a live stream. Next up: SSO, roles, and rule/policy management. | ModSecurity, nginx, OWASP CRS, ClickHouse, Docker |
| [ICPC-2026-Huawei](https://github.com/hed1ad/ICPC-2026-Huawei) | Solution for the ICPC 2026 Huawei task, with a local test harness and tests. | C++ |

## Research & blog

Blog: **[hed1ad.github.io](https://hed1ad.github.io/)**, with vulnerability write-ups covering the vulnerable code, how to test it, and the fix.

- [Argo CD repo-server command injection via crafted SSH repository SOCKS5 proxy URL](https://hed1ad.github.io/posts/cve-2026-55797/) (CVE-2026-55797, CWE-78): why `url.Parse` is not input validation, a minimal Go test, and a review of the allowlist-based fix

## Publications

- [Application of LLM for Penetration Testing](https://elibrary.ru/item.asp?id=68550299), article on elibrary.ru
- **Master's thesis:** *A Methodology for Monitoring the Cyber Resilience of AI Technologies to Attacks at the Operational Stage* (original title: «Методика мониторинга киберустойчивости технологий ИИ к атакам на этапе эксплуатации»).
  The practical part will be published later, **soon...** Results from it are already used by a company to build a product.

## Contact

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/hed1ad)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:diad.hedi@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/evgeniy-trofimov-953525226)
[![Blog](https://img.shields.io/badge/Blog-hed1ad.github.io-181717?style=for-the-badge&logo=hugo&logoColor=white)](https://hed1ad.github.io/)
