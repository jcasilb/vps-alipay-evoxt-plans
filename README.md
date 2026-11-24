# VPS Alipay Guide: Can You Pay With Alipay, What Do the Fees Add Up To, and Which Evoxt Plan Is Worth Buying? (All 11 Plans Compared)

Evoxt's cheapest machine, VM-0.5, is **$2.99/month** for 1 core running at up to 6.0 GHz, 512 MB RAM, 5 GB disk and 250 GB of monthly transfer. Evoxt's own deployment guide lists Alipay among its payment options and describes it as the route aimed at China users, with generally lower service fees than the other methods it accepts. The checkout wall that stops most people at foreign hosts is not the problem here.

Three things decide whether the purchase goes well: what the Alipay route adds to the total, whether the region you pick suits the people using the server, and how much a wrong choice costs to undo. All three are covered below, along with every plan Evoxt currently lists.

> **Quick pick**
>
> First VPS, small site, bot, proxy node or Docker project: **VM-1 at $5.99/mo** (1 core, 2 GB RAM, 20 GB disk, 500 GB transfer).
> Cheapest way to test the platform: **VM-0.5 at $2.99/mo**.
> Want a second core for under a dollar more: **VM-1.5 at $6.95/mo**.
>
> 👉 [Pick a plan and pay with Alipay on Evoxt](https://bit.ly/EvoXt)

## All 11 Evoxt plans, side by side

Every plan below runs on the same platform: KVM, up to 6.0 GHz per core, weekly offsite backup included at no extra cost, and monthly billing you can extend to 3 years.

| Plan | vCPU / RAM | Disk | Monthly transfer | Price (USD/mo) | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB | 250 GB | **$2.99** | [Deploy VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core / 1 GB | 10 GB | 250 GB | **$4.99** | [Deploy VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core / 2 GB | 20 GB | 500 GB | **$5.99** | [Deploy VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores / 2 GB | 20 GB | 500 GB | **$6.95** | [Deploy VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores / 4 GB | 30 GB | 1,000 GB | **$11.99** | [Deploy VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores / 4 GB | 30 GB | 1,000 GB | **$14.99** | [Deploy VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores / 8 GB | 60 GB | 2,000 GB | **$23.99** | [Deploy VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores / 8 GB | 60 GB | 2,000 GB | **$29.99** | [Deploy VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores / 16 GB | 80 GB | 3,000 GB | **$47.99** | [Deploy VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores / 16 GB | 80 GB | 3,000 GB | **$60.95** | [Deploy VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores / 32 GB | 100 GB | 5,000 GB | **$95.99** | [Deploy VM-16](https://bit.ly/EvoXt) |

The same prices appear on Evoxt's card payment page, so the figure you see in the table is the figure you pay, not a card-only discount. All amounts are in USD.

Beyond the plans themselves, a few line items affect the real bill:

- Extra IPv4 address: **$3/month** each.
- You can add individual CPU cores, RAM or transfer to an existing VM without switching plans, which is cheaper than jumping a tier if only one resource is tight.
- Prepaying is allowed from monthly up to 3 years, and you can top up account credits and let the system apply them to invoices automatically. Three years of credits on a $2.99 plan is a lot of money parked at one vendor; monthly is the sane default until you know the machine earns its keep.
- The deployment guide lists 9 regions. You choose one at deploy time, and changes to IP or region afterwards are free through a support ticket, which is worth knowing before you agonise over the map.
- The control panel includes a browser VNC console, VM cloning, floating IP management, and one-click images for WordPress, Docker, GitLab, Nextcloud, cPanel and similar, plus Windows Server images alongside the Linux distributions.

## What Alipay actually adds to the bill

Fees depend entirely on the merchant, and the gap between hosts is wide enough to change which plan is worth buying. Infrawire charges **3% on top of the invoice** for Alipay and says so before you confirm; its card, PayPal, crypto and bank transfer options carry no fee. Cloudzy states the opposite policy: no surcharge for Alipay, same price as paying by card.

Evoxt sits closer to the Cloudzy end. Its deployment guide flags PayPal as carrying a fee and describes Alipay as generally having lower service fees than the other options it lists, which is the reverse of what most people assume about the two. Treat that as the vendor's own wording rather than a promise of zero: the number on the confirmation screen is the only one that matters, and it is the number your Alipay balance gets debited by after conversion from USD.

One thing to check at the payment step. Evoxt's older FAQ lists cards, PayPal, Bitcoin and USDt Tron as accepted methods, while the deployment guide also lists Alipay. Confirm the Alipay button is actually on the invoice page for your order before you plan around it. If it isn't there, USDt on Tron and Bitcoin are both documented as fee-free, which makes them the cheapest fallback rather than cards.

👉 [Start an Evoxt order and check the Alipay option on the invoice](https://bit.ly/EvoXt)

## Paying with Alipay and getting low latency from China are two different problems

Most articles treat "supports Alipay" as if it also meant "fast from Shanghai". It doesn't. rdp.monster states plainly that its servers sit in Europe and the US with no China-optimised routes such as CN2 GIA, and points anyone whose users are in mainland China towards a China-optimised line instead. Cloudzy's Asia-Pacific presence covers Singapore and Sydney only. Infrawire offers Hong Kong on Equinix HK1, and LightNode runs the densest Asia list of the four, with Hong Kong, Taiwan, Japan, Korea, Singapore, Vietnam, Thailand, Malaysia and Indonesia among its 40-plus locations.

Evoxt spreads across 9 regions, and the practical move is to measure before you commit: the deployment guide invites you to contact support for test IPs in the region you're considering, and region changes after the fact are free by ticket. If your users are all in one country, ping the test IP from that country first. If nobody in mainland China is hitting the box, the whole question is moot and you should pick whichever region is closest to your own working machine.

## How much does picking the wrong plan or region cost?

Evoxt bills monthly by default, so a mistake costs one month, not one hour. LightNode goes the other way and bills every server hourly, which makes it the cheaper place to experiment if you genuinely don't know what size you need. Cloudzy refunds in full within 14 days and sends the money back to the Alipay account you paid from; Infrawire offers 7 days. Evoxt's pricing page and deployment guide don't state a money-back window, so if refundability is the deciding factor, ask support before paying rather than assuming.

The free region and IP change is the detail that shrinks this risk most. On Evoxt you can order in one location, test it, and move without buying a second server. What you can't undo is buying a plan three times bigger than the workload needs.

## Which plans most people should skip

**VM-8, VM-12 and VM-16** exist for people running something specific: a Minecraft server with a crowd on it, a CI runner, a virtualisation lab. At $47.99 to $95.99 a month they cost more than most readers of this page spend on hosting in a year, and a blog or a bot will never touch 16 cores.

Two upgrades are worth doing on price alone. **VM-1 to VM-1.5 costs $0.96 more** and doubles you from 1 core to 2 with everything else unchanged, which is the cheapest meaningful performance step in the lineup. **VM-2 to VM-3 costs $3 more** and doubles cores from 2 to 4 while keeping 4 GB and the same 30 GB disk and 1 TB transfer. By contrast, **VM-4 to VM-6 costs $6** for the same 8 GB and the same 60 GB, adding only cores and nothing else; only buy that if you know the workload is CPU-bound.

Watch the RAM ceiling before you get attached to a low price. 512 MB on VM-0.5 runs a static site or a tiny proxy, and little else. 1 GB on VM-0.75 is the floor for a database-backed site. 2 GB on VM-1 is where most people should start.

## A note on privacy

Alipay accounts are verified under a real name, and a payment through Alipay is tied to that account. rdp.monster says this outright and points privacy-focused buyers to USDT or Monero. Evoxt accepts Bitcoin and USDt on Tron, both documented as fee-free, so if you'd rather the invoice not carry your name, you have a working option on the same platform without switching hosts.

## Before you pay

Match the plan to the job, not to the price list:

- **One small site, a bot, or a proxy node** → VM-1 at $5.99.
- **Testing whether Evoxt works for you** → VM-0.5 at $2.99 for a month.
- **Anything with a database and real traffic** → VM-2 at $11.99 for the 4 GB, or VM-3 at $14.99 if CPU is the bottleneck.
- **Users concentrated in one country** → request a test IP for that region first, then order there.

Two checks at the final step: read the RMB amount on the Alipay confirmation page rather than converting the dollar figure in your head, and confirm whether the invoice total already includes any payment-method fee before you approve it.

👉 [Compare Evoxt's plans and complete the order with Alipay](https://bit.ly/EvoXt)
