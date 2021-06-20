---
title: Cloudflare
description:
published: true
date: Thu Jun 03 2021 14:35:00 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Jun 03 2021 14:35:00 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

在這裡您將找到有關 Filo 與 Cloudflare 的關聯.

# 什麼是 Cloudflare？

Cloudflare 是互聯網上最大的網路之一。人們使用 Cloudflare 服務的目的是使其網站和服務更安全、更高效.

# 那 Cloudflare 與 Filo 又有什麼關聯？

Cloudflare 幫助 Filo 遠離惡意之人。它幫忙保護官方網站和 API 存取.

# Cloudflare bans

我們必須保護我們的網站免受惡意人士的侵害，為此我們 Cloudflare Ban。 您將在下方找到有關這些禁令以及它們如何影響您.

## 什麼是 Cloudflare Ban？

Cloudflare Ban 是一項臨時或永久制裁，它將拒絕您訪問我們的網站。 它會通過以下方式發出禁令：.
- 您的 IP 位址.
- 您的 ISP (AKA: 網路業者).
- 您的 IP 位址範圍.
- 您的 User-Agent.
- 您的國家.

## 識別 Cloudflare Ban的步驟

您將能夠快速識別 Cloudflare Ban，因為您會收到 403 錯誤，或是標題為"拒絕訪問"的錯誤頁面.

> <p align=center><img src="https://raw.githubusercontent.com/filobot/docs/main/resources/Cloudflare%20ban.png" alt="If the image doesn't load, please contact us." /><br>
> <i>一張顯示「您的 IP 位址 已經被 Ban 並無法訪問內容」的圖片範例.</i></p>
{.is-image}

# 什麼行為會被 Cloudflare Ban？

下面指出了有關 Cloudflare 禁止的操作，但是出於安全原因，此文檔可能沒有 100% 準確.

## API 中的 429（過度請求）

429 錯誤將告訴瀏覽器和應用程序向我們的網站發出任何類型的請求，您的速率限制已被超出.

此 API 有兩種速率限制:
- 個人或特定.
- 全球或通用.

個人或特定的速率限制更加嚴格，但結果是超過此限制不會導致 Cloudflare Ban (不過最好不要超過這些限制)。 這些限制取至於每個 API 端點.

全球或通用的速率限制是從長遠來看的，也就是說，如果您每分鐘發出大量請求，您可能會收到全局速率限制（在速率限制期間，您將不被允許訪問任何其他 API 端點）.

如果您在不到1小時內收到超過警告或超過全球請求配額的5倍，您的IP位地址將被暫時禁止1小時r.

請注意，Cloudflare Ban 會影響與 Filo 相關的所有功能.

## 其餘服務中的 429（過度請求）

429 錯誤將告訴瀏覽器和應用程序向我們的網站發出任何類型的請求，您的速率限制已被超出

其餘的 Filo 服務有兩種類型的速率限制:
- 全球或通用.

個人或特定的速率限制更加嚴格，但結果是超過此限制不會導致 Cloudflare Ban (不過最好不要超過這些限制)。 這些限制取至於每個 API 端點

全球或通用的速率限制是從長遠來看的，也就是說，如果您每分鐘發出大量請求，您可能會收到全局速率限制（在速率限制期間，您將不被允許訪問任何其他 API 端點）.

如果您在不到1小時內收到超過警告或超過全球請求配額的5倍，您的IP位地址將被暫時禁止1小時r

請注意，Cloudflare Ban 會影響與 Filo 相關的所有功能

## 對 Cloudflare Ban 提出上訴

您將在下方找到有關如何對 Cloudflare Ban 提出上訴的方法.

## 根據禁令期限上訴

- : 不可用的.
- 永久: 您可以通過 **[點擊這裡](https://forms.gle/Pdig38H5gn6XfyW76)** 來對永久禁令提出上訴.

## 根據禁令類型上訴

您將在下方找到有關如何對禁令類型提出上訴的信息:

> 請注意！某些禁令因其性質無法上訴.
{is-warning}

- **IP 位址**: IP 位址.
- **ISP (AKA: 網路業者)**: ISP (AKA: 網路業者).
- **IP 位址範圍**: IP 位址範圍.
- **User-Agent**: User-Agent.
- **國家**: .

# 制裁次數過多

我們自動制裁通常是暫時的，但是，如果 IP 位址或 ISP 受到持續制裁，我們的團隊可以永久禁止以下：
- **IP 位址**.
- **IP 位址範圍**.
- **ISP (AKA: 網路業者)**.

# 永久的禁止訪問

永久 Cloudflare 禁令是我們服務的最後一項保護措施。 雖然在 ISP 禁止的情況下，其所有客戶都被拒絕訪問我們的網站，但事實並非如此.

## ISP 禁令

為了保護我們的網站，我們禁止 ISP 並不完全正確，而是強制該 ISP 的所有客戶執行驗證碼。 這會驗證請求，並可以拒絕有惡意的人訪問.

## IP 位址範圍 Ban

視情況而定，如果某個 IP 位址範圍已被永久禁止，在特殊情況下，可能不會執行任何類型的驗證碼來驗證請求。 同樣，我們團隊的首要任務是以拒絕惡意請求為主要措施.

## User-Agent Ban

通常，那些修改其瀏覽器或應用程序的用戶代理以向網站發出請求的人知道他們在做什麼。 對未知用戶代理的修改可能被解釋為威脅並受到我們的製裁.

我們的建議是保留瀏覽器的默認 User-Agent 或指定一個已知的 User-Agent.

## 國家 Ban

我們禁止發出惡意請求的國家/地區並不完全正確（至少如果我們認為惡意請求的數量可以容忍的話）。 作為優先事項，我們將對來自這些國家/地區的所有請求請求驗證碼，並拒絕所有惡意請求，以確保善意的人可以訪問我們的服務.

# hCaptcha

驗證碼由 **[hCaptcha](https://www.hcaptcha.com)** 管理，他們有著 **[條款和條件](https://www.hcaptcha.com/terms)** 和 **[隱私政策](https://www.hcaptcha.com/privacy)**.

> <p align=center><img src="https://raw.githubusercontent.com/filobot/docs/main/resources/hCaptcha.png" alt="If the image doesn't load, please contact us." /><br>
> <i>一張顯示「hCaptcha 」的範例圖片.</i></p>
{.is-image}
