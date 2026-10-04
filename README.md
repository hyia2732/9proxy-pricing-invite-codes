# 9 proxy: How the IP-Based and GB Pricing Really Works, What Every Package Costs, and How to Pay Less With an Invite Code

People usually type "9 proxy" into a search box after spotting the name somewhere they don't fully trust — a forum banner, a Telegram post, an affiliate link in a scraping thread. The actual question behind the query is practical: is this a real residential proxy network, what does it charge, and which package makes sense for a given workload? So let's skip the company origin story and get to what matters: how 9Proxy bills, what changed in the latest price update, and where the numbers get uncomfortable.

## What 9Proxy actually is

9Proxy is a residential proxy provider. Its advertised pool is 20M+ residential IPs across 90+ countries, with targeting down to country, state, city, ZIP code, and ISP level, and support for HTTP(S) and SOCKS5. The company claims 99.95% uptime. Those are vendor figures, not something a third party has confirmed independently.

Two things about the billing model matter more than the pool size:

- **It's not a subscription.** You top up a balance and buy packages from it. There's no recurring monthly charge sitting on your card waiting to renew.
- **Unused IPs don't expire**, per 9Proxy's own documentation. Neither does unused GB balance — GB packages carry 180-day validity, and Enterprise GB packages drop the expiry entirely.

The realistic audiences here are scraping and data collection, SEO and SERP monitoring, ad verification, price intelligence, and multi-accounting. If none of those describe your workflow, you probably don't need this category of tool at all.

## IP-based vs GB-based: this is the decision that sets your bill

9Proxy sells two residential products, and picking wrong is how people end up overpaying. The difference isn't cosmetic.

|  | Residential by IPs | Residential by GB |
| --- | --- | --- |
| Billing unit | Fixed package, priced by number of IPs | Fixed package, priced by total GB |
| Bandwidth | Unlimited while an IP is active | Deducted from the GB you bought |
| How usage is counted | 1 IP = 1 use when forwarded | Generate unlimited endpoints; only traffic is deducted |
| IP lifespan | A few hours up to ~24h, varies per IP | Rotates per request or session (sticky mode selectable) |
| Validity | Unused IPs don't expire | 180 days (unlimited on Enterprise) |
| Authentication | 9Proxy desktop app, with optional proxy auth | Username/password or IP whitelist |
| Where it runs | Desktop app required | Straight from the dashboard |

Source: 9Proxy's own product documentation.

The practical read:

**Pick IP-based if** you need the same IP to survive across many requests — logged-in sessions, cart flows, account management, anything where a mid-session IP swap gets you flagged. You pay for addresses, not bytes, so heavy data transfer doesn't run up a second bill.

**Pick GB-based if** your jobs rotate IPs constantly and each request is small: SERP scraping, ad verification, geo-checks, API polling, distributed requests across thousands of endpoints. Traffic is the scarce resource here, not identity.

**Pick a bundle if** your work is genuinely mixed. Bundles combine both resources in one purchase, and the 180-day validity on the traffic portion means you're not racing a deadline if the project slows down.

One honest limitation on the IP side: each IP typically lives a few hours to around 24 hours before it goes offline, and the IP product requires a desktop app rather than working from the browser dashboard. ITWire's review flagged the mandatory app as a friction point for multi-device setups. The GB product avoids both problems.

## Full 9Proxy pricing: every package currently listed

These are the prices after 9Proxy's June 2026 adjustment on IP-based and bundle packages. GB-based pricing was left untouched. The headline rate on the pricing page is $0.018 per IP and $0.68 per GB, and those entry rates only appear at the very top of the volume ladder.

### Residential proxies by IP (unlimited bandwidth per IP)

| Package | Price per IP | Total | Buy |
| --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | Grab the 100 IP starter package |
| 500 IPs | $0.144 | $72 | Get 500 residential IPs |
| 1,000 IPs + 500 bonus | $0.084 | $126 | Take the 1,000 IP package with 500 free IPs |
| 2,500 IPs | $0.084 | $210 | Buy the 2,500 IP package |
| 5,000 IPs | $0.072 | $360 | Get 5,000 IPs at the volume rate |
| 15,000 IPs | $0.048 | $720 | See the 15,000 IP package |
| 25,000 IPs | $0.035 | $863 | Check the 25,000 IP tier |
| 50,000 IPs | $0.029 | $1,438 | Look at the 50,000 IP package |
| 100,000 IPs (Business) | $0.023 | $2,300 | Compare the 100,000 IP Business package |
| 200,000 IPs (Business) | $0.021 | $4,140 | See the 200,000 IP Business package |
| 500,000 IPs (Business) | $0.018 | $8,625 | Check the 500,000 IP Business tier |

### Residential proxies by GB

| Package | Price per GB | Total | Validity | Buy |
| --- | --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days | Start with the 5 GB package |
| 50 GB + 5 bonus GB | $2.10 | $105 | 180 days | Buy 50 GB plus 5 dedicated GB |
| 100 GB | $1.50 | $150 | 180 days | Get the 100 GB package |
| 200 GB | $1.00 | $200 | 180 days | Take 200 GB of residential traffic |
| 1,000 GB | $0.80 | $800 | 180 days | Look at the 1,000 GB tier |
| 2,000 GB | $0.75 | $1,500 | 180 days | See 2,000 GB of rotating traffic |
| 3,000 GB (Enterprise) | $0.72 | $2,160 | Unlimited | Check the 3,000 GB Enterprise package |
| 6,000 GB (Enterprise) | $0.70 | $4,200 | Unlimited | Compare the 6,000 GB Enterprise tier |
| 10,000 GB (Enterprise) | $0.68 | $6,800 | Unlimited | Get the 10,000 GB Enterprise package |

### Bundle packages (IPs + bandwidth in one purchase)

| Bundle contents | Total | Traffic validity | Buy |
| --- | --- | --- | --- |
| 100 IPs + 5 GB | $30 | 180 days | Buy the 100 IP + 5 GB bundle |
| 1,500 IPs + 50 GB | $180 | 180 days | Get the 1,500 IP + 50 GB bundle |
| 5,000 IPs + 500 GB | $720 | 180 days | See the 5,000 IP + 500 GB bundle |

A quick sanity check on the arithmetic, because the per-unit rounding hides the real spread. Moving from 100 IPs to 500 IPs cuts your cost per address from $0.24 to $0.144. Jumping to 5,000 IPs gets you to $0.072. The gap between the smallest and largest tier is roughly 13x on a per-IP basis. If you're running a small pilot, buying 100 IPs and then buying 5,000 later costs you more than starting at 500 — but only if you actually have 5,000 addresses worth of work.

On the GB side, the 5 GB package at $3.00/GB is an expensive way to test. The 100 GB tier at $1.50/GB is where the pricing starts looking like the budget-provider numbers people quote, and $0.80/GB at 1,000 GB is a different product class from where you started.

## What changed in the June 2026 price update

9Proxy announced its first-ever price adjustment on 18 May 2026, effective 1 June 2026, and it wasn't evenly distributed:

- **IP-based packages went up.** The 100 IP tier moved from $20 to $24; the 500 IP tier from $60 to $72; the 1,000 IP tier from $105 to $126 with the same 500-IP bonus.
- **Bundle packages went up too.** The entry bundle moved from $25 to $30, the mid bundle from $150 to $180, and the large bundle from $600 to $720.
- **GB-based packages didn't move at all.** The 5 GB through 10,000 GB ladder is identical to what it was before.

The company's stated reason was infrastructure upgrades for connection stability and throughput. Take the marketing framing for what it's worth — the useful part is that the GB model is now noticeably better value relative to the IP model than it was a year ago. If you were choosing between the two on price alone, the June adjustment tilted the comparison further toward traffic-based billing for rotation-heavy work.

There's a second detail worth knowing: because 9Proxy runs on a balance, IPs you purchased earlier stay at the rate you paid and don't expire. Anyone holding a large IP balance from before June 2026 is sitting on cheaper inventory than a new buyer.

## The invite code: 5% off, and it's not a mystery coupon

If you arrived here from an invite link, the code attached to that link is doing something concrete. 9Proxy's affiliate FAQ states that when a referred user signs up with a referral code or link, they receive a **5% discount on their purchases**. That's the referral mechanic itself, not a limited-time promotion that expires on a random Tuesday.

The surrounding affiliate program, for anyone curious about the other side of it:

- Commission rates run 5% / 10% / 15% depending on total referred sales volume (up to $15,000, $15,000–$40,000, and above $40,000 respectively).
- Commissions are lifetime — the referral stays tied to the affiliate account permanently.
- Withdrawals require a $100 minimum balance, paid in crypto, converted to IPs or GB, or moved to a 9Proxy wallet balance. Credit-card-funded referrals sit under a 60-day hold to cover chargebacks.

So the 5% is real, it applies at purchase, and it stacks with whatever your chosen package already costs. On the $126 IP package that's a few dollars; on a $2,300 Business package it's $115. Not transformative, but it's free money for using a link you were going to click anyway.

👉 Sign up with the invite code attached and the 5% referral discount applies at checkout.

## Free trials and testing before you commit

9Proxy doesn't run a permanent public free tier. What it does offer is a limited trial for new users depending on availability, which you have to request from support — the company's own reps describe it as availability-dependent and ask whether you want an IP-based or GB-based trial. On top of that, 9Proxy runs periodic promo campaigns: 1 GB free codes dropped through community channels, 10 free IPs for testing, and holiday offers like the Lunar New Year promotion that applied an 8% discount to regular packages with code LNY2026 plus oversized limited packages.

Two caveats worth stating plainly:

1. **Promo codes don't live forever.** The Lunar New Year code expired on 23 February. Anything you find listed on a coupon aggregator site may already be dead — several of those pages are visibly stale, still showing the pre-June-2026 bundle prices of $25 instead of $30.
2. **The trial is a test, not an evaluation period.** If you're trying to check whether 9Proxy works on a specific target site, bring that target to the trial rather than testing against google.com and calling it a day.

If support offers you a trial, use it on the actual domain and the actual request rate you care about. Success rates vary a lot by target tier — that's true across budget providers, not just this one.

## How it stacks up against the field

Third-party coverage puts 9Proxy in the budget bracket, which matches the pricing above:

- A June 2026 cost comparison from traffic-creator.com places 9Proxy in the $0.70–$2/GB budget tier alongside DataImpulse, noting it's the next-cheapest option and that some users report better success rates on specific targets at this price point. The same comparison rates budget providers as capable for Tier 1 and Tier 2 targets but weak on Tier 3 (70–85% success), and notes limited city-level targeting and basic sticky sessions.
- Geekflare's 2026 review describes the IP model as strongest when predictable access matters more than per-request cost, and the GB model as the better fit for high-rotation work.
- ProxyLook's directory scores 9Proxy around 3.9 stars, characterizing it as a budget residential provider.
- ITWire's review is broadly positive on clean IPs and automation compatibility, while flagging two things: the mandatory desktop app complicates multi-device use, and streaming services can detect the IPs even where e-commerce sites don't.

Read those together and the profile is consistent: clean-enough IPs, aggressive bulk pricing, and a product that's built for automation rather than for streaming or casual browsing. The 90+ country coverage with city and ZIP targeting is 9Proxy's own claim, and at least one third-party comparison characterizes the city-level targeting as limited relative to larger competitors — worth testing on your target geo before you commit to a large package.

👉 Check the current live pricing before you buy, since package prices and bonus structures have changed once already this year.

## Common questions

**Do my IPs expire?**
No. Unused IPs stay on your balance indefinitely. Individual IPs go offline after a few hours to around 24 hours once activated — that's the lifespan, not an expiration of your purchase.

**Is there a monthly subscription?**
No. Everything is prepaid against a balance. You buy packages when you need them.

**What payment methods are accepted?**
Credit cards, bank cards, crypto including USDT, BTC, ETH, LTC and DOGE, plus Alipay, Apple Pay, and Google Pay.

**Can I share the account with a team?**
Yes. There's a share code / sub-account system, and the Enterprise program adds team mode with one owner plus up to five members, per-member traffic controls, no-expiration bandwidth sharing inside the team, and activity logs.

**What happens if an IP dies?**
9Proxy advertises a replacement policy triggered within 60 seconds when a proxy fails, and a "Today List" feature that lets you reuse proxies you've already pulled rather than burning new ones.

**Which package should a first-time buyer start with?**
Depends entirely on the workload. Rotation-heavy scraping with small requests: start with 100 GB at $1.50/GB rather than 5 GB at $3.00/GB — the entry tier is priced as a sample. Session-based multi-accounting: 100 IPs at $24 is a reasonable test. Mixed work: the $30 entry bundle gets you both resource types in one purchase and 180 days to use the traffic.

## Getting started

1. Sign up through an invite link so the 5% referral discount attaches to your account. Codes can't be applied retroactively after a purchase.
2. Top up a balance and pick your model — IPs, GB, or a bundle.
3. For IP-based work, install the desktop app, select your country and city, and pull the endpoints into your automation tool.
4. For GB-based work, generate endpoints in the dashboard, choose sticky or rotating sessions, and authenticate with username/password or IP whitelisting.
5. Test on your real target before scaling. Volume discounts only pay off if the success rate holds.

The short version: 9Proxy is a legitimately cheap residential proxy network with two billing models that behave very differently, a referral discount that's genuinely attached to the link you came from, and a June 2026 price increase that made the traffic-based model the more attractive half of the catalog. Buy the smallest package that covers your real test, confirm it works on your targets, then scale into the tiers where the per-unit price drops.

👉 Start with the invite code and pick your package here.
