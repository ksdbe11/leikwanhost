# 利群主機（LeiKwan Host）評測：上海CN2/9929精品線路 VPS + SDWAN，月付 HK$96 起跑

說到從大陸出去的網絡質量，說真的，用過「爛線」的人都知道那種煎熬——晚上高峰期頁面一卡一卡，視頻轉圈到想砸電腦。利群主機（LeiKwan Host）這家香港公司就是瞄準這個痛點做起來的，主打上海機房直連、CN2 和 9929 精品線路，另外還有 SDWAN 類產品直接幫你解決出口問題。

這篇文章把他們家所有主要套餐都整理了一遍，看完你大概就知道哪款適合自己。

<img width="2745" height="1501" alt="image" src="https://github.com/user-attachments/assets/9525af8d-0835-43c6-80b4-ce2a1e63e306" />

---

## 利群主機是什麼來路

LeiKwan Hosting (Hong Kong) Limited，公司地址在九龍土瓜灣，算是個紮實的香港本地主機商。他們的服務器放在上海機房，接入側用的是中國聯通 IP（部分產品電信入口），主要走 CN2（電信 AS4809）和 9929（聯通 AS9929）這兩條對大陸用戶比較友好的精品線路。

比較特別的是，除了傳統 VPS，他們還有 SDWAN 產品，讓你用上海 IP 進去、從香港/日本/台灣等地出來，給那些需要「國內IP進、境外IP出」場景的人用。

Telegram 頻道 @leikwanhost 會不定期發折扣碼，下單前建議先去看看有沒有最新優惠。

---

## 產品線總覽：你到底需要哪種

利群主機的產品大致分三類：

**VPS（流量計費）** — 上海機房的虛擬服務器，你自己跑服務，CN2 和 9929 各有一個系列。

**SDWAN 經典版** — 國內 IP 入，指定目的地出（日本/香港/台灣/德國/韓國/美國可選），延遲參考 SHA→HKG 27-32ms 左右，比較穩定。

**滬聯網 Hiternet** — SDWAN 的升級版，1024 GiB 流量、400Mbps 雙向，一個 Alpha 套餐就能同時走 HK、JP、KR、DE、TW、US 等多個出口，適合需要靈活出口的用戶。

---

## 上海 CN2 VPS 套餐價格表

全部為 NAT 機型（不設獨立 IPv4 入口），搭載 EPYC 7K62 處理器，聯通入口接入，開通需要實名驗證。

| 套餐名稱 | vCPU | RAM | SSD | 流量/帶寬 | IPv6 | 月費 | 開通費 | 購買 |
|---|---|---|---|---|---|---|---|---|
| Alpha | 1 核 | 1 GB | 10 GB NVMe | 750 GiB @ 150 Mbps（雙向） | /64 | HK$96 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/shanghai-vps/alpha-traffic-1&aff=42) |
| Beta | 1 核 | 1 GB | 10 GB NVMe | — | /64 | HK$138 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/shanghai-vps/beta-traffic-1&aff=42) |
| Sigma | 1 核 | 1 GB | 10 GB NVMe | — | /64 | HK$266 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/shanghai-vps/sigma-traffic&aff=42) |
| Delta | 1 核 | 1 GB | 10 GB NVMe | — | /64 | HK$533 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/shanghai-vps/delta-traffic&aff=42) |
| Epsilon | 1 核 | 1 GB | 10 GB NVMe | — | /64 | HK$1,066 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/shanghai-vps/epsilon-traffic&aff=42) |

> **馬年創始經典套餐（Dev）**：CN2+9929 雙出口，399 GiB @ 100Mbps，附 2 個 IPv6 /64，半年付 HK$280。屬於限量保值品，目前顯示 0 Available，可以守一下補貨。

---

## 上海 9929 VPS 套餐價格表

走聯通 AS9929 線路，同樣 EPYC 7K62 驅動，NAT 機型，獨立 IPv4 可另購。

| 套餐名稱 | vCPU | RAM | SSD | 流量/帶寬 | IPv6 | 月費 | 開通費 | 購買 |
|---|---|---|---|---|---|---|---|---|
| Alpha | 1 核 | 1 GB | 10 GB NVMe | 750 GiB @ 150 Mbps（雙向） | /64 | HK$96 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/as9929/shang-hai-9929-vps-liu-liang-ji-fei-alpha&aff=42) |
| Beta | 1 核 | 1 GB | 10 GB NVMe | — | /64 | HK$138 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/as9929/beta-1&aff=42) |
| Sigma | 1 核 | 1 GB | 10 GB NVMe | — | /64 | HK$266 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/as9929/sigma&aff=42) |
| Delta | 1 核 | 1 GB | 10 GB NVMe | — | /64 | HK$533 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/as9929/delta&aff=42) |
| Epsilon | 1 核 | 1 GB | 10 GB NVMe | — | /64 | HK$1,066 | HK$11.50 |  [立即訂購](https://buy.leikwanhost.com/index.php?rp=/store/as9929/epsilon&aff=42) |

CN2 和 9929 的 Alpha 入門款都是 HK$96/月，主要差別在線路——CN2 走電信 AS4809 骨幹，9929 走聯通 AS9929，看你的主要用戶群體和自己的上網運營商來選。

👉 [查看所有 VPS 套餐](https://buy.leikwanhost.com/aff.php?aff=42)

---

## SDWAN 經典版：懶人友好的出口解決方案

SDWAN 是另一種玩法——你不需要自己配路由，直接買一個「上海進、XXX出」的通道，延遲低、配置省心。

產品標注「非 IPLC 非 IEPL 非跨境專線」，請按 SDWAN 的標準預期，別拿專線對比。

| 套餐 | 出口地 | 流量/帶寬 | 月費 | 購買 |
|---|---|---|---|---|
| Alpha (JP) 東京 | 日本 | 648 GiB @ 200 Mbps | HK$100 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/alpha-jp-1&aff=42) |
| Alpha (TW) 台灣 | 台灣苗栗 HINET | — | HK$100 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/shatwn-alpha&aff=42) |
| Alpha (HK) 香港 | 香港 | — | HK$100 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/shhk-alpha&aff=42) |
| Alpha (KR) 韓國 | 韓國首爾 | — | HK$98 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/shang-hai-han-guo-sdwan-alpha-kr&aff=42) |
| Alpha (LA) 美國 | 洛杉磯 | — | HK$98 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/sha-lax-alpha&aff=42) |
| Alpha (DE) 德國 | 紐倫堡 | — | HK$74 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/shang-hai-de-guo-sdwan-alpha-de&aff=42) |
| Beta (JP) 東京 | 日本（不得回國） | — | HK$195 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/beta-jp&aff=42) |
| Beta (HK) 香港 | 香港（不得回國） | — | HK$195 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/shhk-beta&aff=42) |
| Beta (KR) 韓國 | 韓國首爾（不得回國） | — | HK$160 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/shang-hai-han-guo-sdwan-beta-kr&aff=42) |
| Beta (DE) 德國 | 紐倫堡（不得回國） | — | HK$150 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/basictier-sdwan/shang-hai-de-guo-sdwan-beta-de&aff=42) |

Alpha 和 Beta 的主要區別是：Alpha 可雙向通，Beta 標注「不得回國」，也就是只能單向出。選哪個看你的實際用途。

---

## 滬聯網 Hiternet：一台機走全球

如果你不想為每個目的地買一條線，Hiternet 算是個一站式方案。

| 套餐 | vCPU | RAM | SSD | 流量/帶寬 | 出口 | 月費 | 購買 |
|---|---|---|---|---|---|---|---|
| Alpha | 1 核 EPYC 7K62 | 1 GB | 10 GB NVMe | 1,024 GiB @ 400 Mbps | HK/JP/KR/DE/TW/RU/US 等多重出口 | HK$566 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/sdwanstandard-tier/alpha&aff=42) |
| Beta | — | — | — | — | 多重出口 | HK$729 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/sdwanstandard-tier/hu-lian-wang-hiternet-beta&aff=42) |

入口是上海浦東電信 v4，包含全球多個出口節點，路由繞路可聯繫技術支援調配。價格相對不低，但對需要多出口靈活切換的用戶來說，比單獨買幾條 SDWAN 合算。

---

## 當前特價區（活動特價，不設退款）

買之前想省錢的可以看看促銷區，目前有幾個庫存：

| 套餐 | 配置 | 月費 | 購買 |
|---|---|---|---|
| Promo-Sigma 雙線路 | 2c 1GB 15GB NVMe，1,024 GiB @ 300 Mbps，CN2+9929 港日雙拉 | HK$139 + HK$35 開通費 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/promo-zone/promo-sigma-dual-route&aff=42) |
| Promo-Delta 雙線路 | 同系列升級版 | HK$232 + HK$35 開通費 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/promo-zone/promo-delta-dual-route&aff=42) |
| SDWAN 雙子星 | 上海入口，港日雙出口 | HK$150 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/promo-zone/promo-sdwan-hkjp1&aff=42) |
| SDWAN 三傑 | 上海入口，三出口 | HK$222 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/promo-zone/promo-sdwan-san-jie&aff=42) |

Promo-Sigma 雙線路值得特別注意：HK$139/月就能跑 CN2+9929 雙出口，港日兩個方向都有，庫存只剩兩個，手快有手慢冇。

👉 [查看全部特價套餐](https://buy.leikwanhost.com/index.php?rp=/store/promo-zone&aff=42)

---

## 廣州電信/廣州三線 Canton Network

新增的廣東地區產品，針對廣州用戶，需要二步實名后開通，人工開通速度較慢，急著用的別下單。

| 套餐 | 配置 | 月費 | 購買 |
|---|---|---|---|
| Canton CT-A | 廣東電信 IPv4，1c 1g 20GB，512 GB @ 500 Mbps | HK$99.99 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/20251212partone/guang-zhou-dian-xin-canton-ct&aff=42) |
| Canton CT-B | 升級版 | HK$155.55 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/20251212partone/guang-zhou-dian-xin-canton-ct-b&aff=42) |
| 廣州三線 CT+CU+CM | 預售款，三網通 | HK$248.88 |  [訂購](https://buy.leikwanhost.com/index.php?rp=/store/20251212partone/ctcucm-canton&aff=42) |

---

## 需要注意的幾件事

**實名驗證**：所有大陸入口產品都需要 KYC 實名，沒打算配合這一步的就不用考慮了。

**機場/多人共享**：明確標注不支持，一旦被發現直接清退無退款，規矩說得很清楚。

**工單時間**：週一到週五 11:00-20:30，週六日及假期 13:00-18:30，非工時支援屬於加值服務要額外付費。要求全天候響應的話需要提前了解。

**折扣碼**：官方提示在 Telegram 群聊裡可獲取折扣代碼，訂閱 @leikwanhost 頻道是獲取最新優惠的正確姿勢。

**Beta 系列 SDWAN 不得回國**：這點很多人買完才發現，Alpha 可以雙向，Beta 只能出不能回，選之前看清楚需求。

---

## 總結：適合誰買

利群主機的定位比較清晰——給需要從中國大陸走精品線路出去的用戶用的。如果你在上海或者附近，聯通/電信用戶，需要低延遲到日本、香港、台灣這些目的地，入門的 CN2 或 9929 Alpha 套餐 HK$96/月算是相對實在的價格。

SDWAN 系列對於懶得自己折騰路由的人很友好，直接買個通道就行，Alpha 系列三位數起步，不算貴。Hiternet 適合進階玩法，需要多出口靈活切換的場景。

特價區的 Promo-Sigma 雙線路 HK$139/月庫存只剩兩台，如果用量合適直接衝就對了。

👉 [前往利群主機選購最適合你的套餐](https://buy.leikwanhost.com/aff.php?aff=42)
