# Overview
| Date | URL |
| ---- | --- |
| 18.03.2026 | https://www.securityweek.com/darksword-ios-exploit-kit-used-by-state-sponsored-hackers-spyware-vendors/ |
| 18.03.2026 | https://www.lookout.com/threat-intelligence/article/darksword |
| 18.03.2026 | https://techcrunch.com/2026/03/18/russians-caught-stealing-personal-data-from-ukrainians-with-new-advanced-iphone-hacking-tools/ |
| 18.03.2026 | https://cloud.google.com/blog/topics/threat-intelligence/darksword-ios-exploit-chain |
| 10.03.2026 | https://techcrunch.com/2026/03/10/us-military-contractor-likely-built-iphone-hacking-tools-used-by-russian-spies-in-ukraine/ |
| 05.03.2026 | https://www.esecurityplanet.com/threats/coruna-ios-exploit-kit-compromises-thousands-of-iphones/ |
| 04.03.2026 | https://thehackernews.com/2026/03/coruna-ios-exploit-kit-uses-23-exploits.html |
| 04.03.2026 | https://cybersecuritynews.com/coruna-ios-exploit-kit/ |
| 03.03.2026 | https://cloud.google.com/blog/topics/threat-intelligence/coruna-powerful-ios-exploit-kit |

# Referenced CVEs
| CVE | Affected Product | Description |
| --- | ---------------- | ----------- |
CVE-2021-30952 | Apple OS Products | Integer overflow, processing maliciously crafted web content may lead to arbitrary code execution. |
CVE-2022-48503 | Apple OS Products | Processing of web content may lead to arbitrary code execution. |
CVE-2023-43000 | Apple OS Products | Use-after-free issue. |
CVE-2024-23222 | Apple OS Products | Type confusion issue. |
CVE-2023-32409 | Apple OS Products | Bounds-checking issue allowing attackers to break out of Web Content sandboxing. |
CVE-2023-32434 | Apple OS Products | Integer overflow issue leading to arbitrary code execution with kernel privileges. |
CVE-2023-38606 | Apple OS Products | State management issue potentially allowing applications to modify sensitive kernel state. |
CVE-2024-23225 | Apple OS Products | Memory corruption issue allowing an attacker with arbitrary kernal read/write to bypass memory protections. |
CVE-2024-23296 | Apple OS Products | Memory corruption issue allowing an attacker with arbitrary kernal read/write to bypass memory protections. |

# Indicators of Compromise
| Type | Indicator |
| ---- | --------- |
| URL Delivering Coruna | http[://]cdn[.]uacounter[.]com/stat[.]html |
| BundleID: com.apple.springboard | 18394fcc096344e0730e49a0098970b1c53c137f679cff5c7ff8902e651cd8a3 |
| BundleID: com.bitkeep.os | 6eafd742f58db21fbaf5fd7636e6653446df04b4a5c9bca9104e5dfad34f547c |
| BundleID: com.bitpie.wallet | 42cc02cecd65f22a3658354c5a5efa6a6ec3d716c7fbbcd12df1d1b077d2591b |
| BundleID: coin98.crypto.finance.insights | 0dff17e3aa12c4928273c70a2e0a6fff25d3e43c0d1b71056abad34a22b03495 |
| BundleID: org.toshi.distribution | 05b5e4070b3b8a130b12ea96c5526b4615fcae121bb802b1a10c3a7a70f39901 |
| BundleID: exodus-movement.exodus | 10bd8f2f8bb9595664bb9160fbc4136f1d796cb5705c551f7ab8b9b1e658085c |
| BundleID: im.token.app | 91d44c1f62fd863556aac0190cbef3b46abc4cbe880f80c580a1d258f0484c30 |
| BundleID: com.kyrd.krystal.ios | 721b46b43b7084b98e51ab00606f08a6ccd30b23bef5e542088f0b5706a8f780 |
| BundleID: io.metamask.MetaMask | 25a9b004cf61fb251c8d4024a8c7383a86cb30f60aa7d59ca53ce9460fcfb7de |
| BundleID: org.mytonwallet.app | be28b40df919d3fa87ed49e51135a719bd0616c9ac346ea5f20095cb78031ed9 |
| BundleID: app.phantom | 3c297829353778857edfeaed3ceeeca1bf8b60534f1979f7d442a0b03c56e541 |
| BundleID: com.skymavis.Genesis | 499f6b1e012d9bc947eea8e23635dfe6464cd7c9d99eb11d5874bd7b613297b1 |
| BundleID: com.solflare.mobile | d517c3868c5e7808202f53fa78d827a308d94500ae9051db0a62e11f7852e802 |
| BundleID: com.global.wallet.ios | 4dfcf5a71e5a8f27f748ac7fd7760dec0099ce338722215b4a5862b60c5b2bfd |
| BundleID: com.tonhub.app | d371e3bed18ee355438b166bbf3bdaf2e7c6a3af8931181b9649020553b07e7a |
| BundleID: com.jbig.tonkeeper | 023e5fb71923cfa2088b9a48ad8566ff7ac92a99630add0629a5edf4679888de |
| BundleID: com.tronlink.hdwallet | f218068ea943a511b230f2a99991f6d1fbc2ac0aec7c796b261e2a26744929ac |
| BundleID: com.sixdays.trust |1fb9dedf1de81d387eff4bd5e747f730dd03c440157a66f20fdb5e95f64318c0 |
| BundleID: com.uniswap.mobile | 4dc255504a6c3ea8714ccdc95cc04138dc6c92130887274c8582b4a96ebab4a8 |
| BundleID: com.apple.assistd | 2a9d21ca07244932939c6c58699448f2147992c1f49cd3bc7d067bd92cb54f3a |