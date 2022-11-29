---
title: "Cost-effective acquiring with Cloudflare Workers"
date: 2022-11-10T13:02:50+01:00
draft: false
---

Building a new card acquirer means making some crucial decisions, namely which platform to build on and how to process payments towards card schemes.

In a new acquirer, engineering efforts should without question be invested in adding value for merchants and PSPs, instead of coding Visa protocol messages.

For processing payments, the right choice is rely on a dedicated payment processor (such as 
{{< rawhtml >}}<a href="https://www.silverflow.co" target="_blank">Silverflow</a>{{< /rawhtml >}}) - a partner that is fully dedicated on scheme protocols with a business model based on number of transactions and not the monetary volume.

#### Unit economics of an acquirer
{{< rawhtml >}}<p>{{</rawhtml>}}

With a IC++ pricing model acquiring revenue is always a direct % of the payment amount - it is unaffected by interchange or scheme fees which are passed on to the merchant. 
{{< rawhtml >}}<p>{{</rawhtml>}}
Compared to a blended pricing model, IC++ makes it much easier to project the estimated earnings on the monthly or yearly volume the merchant is expecting.

Simplified formula % of tx amount minus card processor costs minus platform costs.


 #### Cloudflare Workers as the right platform choice

{{< rawhtml >}}

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Reviewing my invoices, my experiment with workers and R2 turned out to be a smashing success:<br><br>💰 Paid Cloudflare $5 for workers, $4.35 for R2 (~300GB)<br>🕺 Cut my AWS bill by $507 <a href="https://t.co/zLsHEQh7FH">pic.twitter.com/zLsHEQh7FH</a></p>&mdash; Jan Klimo (@janklimo) <a href="https://twitter.com/janklimo/status/1590632909182210048?ref_src=twsrc%5Etfw">November 10, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

{{< /rawhtml >}}