# China Company Verification

A flat-fee supplier check for anyone buying from China. Send us a company name or an 18-digit Unified Social Credit Code (USCC), we pull the current public records and send back a PDF credit report, usually within 12 hours. The price is $39.99, one report, no subscription.

Website: https://chinacompany.net/

## Why this repo exists

The website is served from outside mainland China and refuses traffic from mainland IPs, so plenty of people who need a check inside China can't open it. This repo keeps the useful parts in plain text: what the report includes, which official systems feed it, what it costs, and where the limits are. If you only want to know whether it is worth $39.99, the pricing section answers that in one table.

## What the report includes

Around 105 fields in total. The short list:

- Registration profile: company name (and former names), USCC, legal representative, registered address, establishment date, operating period, company type
- Capital: registered capital (认缴, subscribed) and paid-in capital (实缴, actually contributed), with shareholder contributions where published
- Shareholders and ownership: holders, their share, their own investments, branch offices, outbound investment
- Operating status and business scope, including licensed items that need separate approval
- Annual report filings, social insurance headcount, staff numbers declared in filings
- Administrative penalties, abnormal operations listing, dishonesty blacklist (失信被执行人)
- Court judgments, hearing announcements, enforcement cases, judicial auction records
- Intellectual property: trademarks, patents, software copyrights, standards
- Import and export records, tax credit rating, government procurement and bidding history where they exist

## Where the data comes from

All of it is public. No private databases, no scraped contact lists, no AI-generated filler. Records are pulled when you order, not from a snapshot taken six months ago.

**Registration and credit**
National Enterprise Credit Information Publicity System (国家企业信用信息公示系统), Credit China, Credit Reference Center under the PBOC.

**Courts**
China Judgements Online (中国裁判文书网), China Open Court Trial Online, People's Court Announcement Network, China Execution Information Disclosure.

**Enforcement and auctions**
People's Court Mediation Platform, Online Judicial Auction Platform, China Procuratorate Network.

**Tax and customs**
State Taxation Administration, General Administration of Customs.

**Intellectual property**
China National Intellectual Property Administration, China Copyright Protection Center, China Standards Information Service Platform.

**Other regulators**
China Government Procurement Network, China Tendering and Bidding Public Service Platform, China Land Market Network, MIIT ICP filing database, Ministry of Ecology and Environment.

Each report states which sources were used for that company and the date the data was collected. What comes back depends on what the registry actually publishes, which is not the same for every company.

## How an order runs

1. Search the company by Chinese name or USCC. The code saves time because names collide.
2. Pay $39.99 by card. Visa, Mastercard and Amex are handled by Creem.
3. An analyst pulls the records and cross-checks the identity details before the report is approved: name, code, status, shareholders, address.
4. The PDF lands in your inbox. Most orders arrive well before the 12-hour mark. Messy cases, usually groups with several related entities, can take up to 24 hours.

The report language is chosen at checkout, currently 5 or more options, so you can forward it to a partner who doesn't read English.

## Pricing

| Package | Reports | Price | Per report |
| --- | --- | --- | --- |
| Single | 1 | $39.99 | $39.99 |
| 20 credits | 20 | $739 | $36.95 |
| 50 credits | 50 | $1,699 | $33.98 |
| 100 credits | 100 | $2,999 | $29.99 |

One credit is one full report. Credits don't expire and can be used one at a time or in a batch. There is no subscription and no per-field charge.

## What this does not do

Worth stating plainly, because a $39.99 report is not a full due diligence engagement:

- **No site visit.** We don't inspect the factory, count production lines, or check product quality. If you need that, hire an inspection company.
- **No bank account confirmation.** A Chinese company's public record doesn't prove which bank account is theirs. Bank detail verification is a separate service.
- **No private financials.** Chinese private companies don't publish profit and loss statements. Paid-in capital and social insurance headcount are the closest available proxies for size, and neither is perfect.
- **No guarantee of good behaviour.** A clean record means nothing was published, not that nothing happened. Settled disputes and private deals often leave no trace.
- **Not an official document.** We are an independent commercial service and not affiliated with any Chinese government body. The report is a compilation of public records, not a certificate issued by an authority.

If a company has almost no public data (newly registered, or a shell with no filings), the report will be thin. That is itself a signal, and it is also the case where we refund rather than pad the file.

## Notes on reading Chinese registry data

A few things that trip up first-time buyers:

- The USCC is 18 characters. Old 15-digit registration numbers still appear in older documents and won't match a current search.
- 认缴 (subscribed capital) is a promise. 实缴 (paid-in capital) is money actually deposited. A company with 10 million subscribed and zero paid-in is legal and common, and it tells you something.
- 存续 and 开业 both mean the company is alive and trading. 吊销 means the licence was revoked but the entity still exists on paper. 注销 means it's gone. A revoked company can still show up in old contracts and quotations.
- Annual reports are filed once a year and lag reality by months. A change of legal representative in March may not appear until the next filing cycle.
- Check former names. A supplier that renamed itself usually did so for a reason, and the penalties often sit under the old name.
- Branches are not the parent. A factory address may belong to a branch with a different registration and different risk record.
- Hong Kong, Macau, Taiwan and offshore entities are not in the mainland registry at all. They need a different search entirely.

## Refunds

Full refund if the company can't be found or matched in the official registries, if the registration data can't be retrieved, if the report isn't delivered within 24 hours, or if core data such as status, legal representative or shareholders turns out to be materially wrong.

Not refundable for a change of mind after delivery, wrong or incomplete company details in the order, disagreement with how public records are interpreted, or business decisions made after reading the report. Requests are handled within 5 business days.

## Links

- Website: https://chinacompany.net/
- Pricing and credit packs: https://chinacompany.net/pricing/
- Who we are and where the data comes from: https://chinacompany.net/about/

Questions before ordering go through the contact details on the site. We usually answer within a few hours, weekends included.
