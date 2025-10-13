# Update-Hagezi-wildcard-list-strip-
將Hagezi wildcard list 移除* 讓SURGE可用
## 自動產生的清單
本 repo 會每天自動抓取：
https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/ultimate.txt

並將每行前綴的 `*`（以及 `*.`）移除，輸出至：
`output/ultimate.txt`
