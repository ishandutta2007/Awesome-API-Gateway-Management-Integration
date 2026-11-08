# Awesome-API-Gateway-Management-Integration

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag the data problem before you publish this. **Your list mixes two different layers of the stack**, and the search results contain usable pricing for some vendors but not others.



## The category problem



**Postman API Gateway Integrations** is not an API gateway. Postman is an API client and platform; its "gateway integrations" are connectors that let Postman talk to gateways like Kong or AWS. It belongs in an "API client" list, not a "gateway management" list.



**Traefik** is an edge router and reverse proxy, not a full API management platform. Its open-source core (Traefik Proxy) is MIT-licensed, but the commercial Hub tiers are gated behind sales . It is a different product class from Kong, Apigee, or MuleSoft.



## What the search results actually contain



**Pricing (usable):**



- **Kong Konnect Plus**: **$500/month per dedicated cloud gateway control plane**, including up to 1M API requests; overages **$200/month per additional 1M requests**; serverless control plane **$25/month**; hybrid control plane **$200/month** . Vendr benchmarks show small-to-mid deployments at **$40K–$80K/year**, mid-market at **$80K–$180K**, large enterprise at **$200K–$500K+** . Kong's initial quotes often start **30–50% above** what buyers ultimately pay .



- **AWS API Gateway**: Pay-per-use, no minimums. Free tier includes **1M REST API calls and 1M HTTP API calls per month for 12 months** . China region HTTP API pricing: **¥10.55 per million** for first 300M requests .



- **Apigee pay-as-you-go**: Standard API Proxy calls **$20 per million** (first 50M), dropping to **$13 per million** above 500M; environment usage **$0.5–$4.7 per hour per region** depending on environment type . Subscription plans also available .



- **Tyk**: **No public list prices by design**. Core plan is usage-based (priced by APIs managed); Professional is architecture-based (data planes, environments, control planes). Gateway and Pump are **MPL 2.0 free**; Dashboard, Developer Portal, Operator, and MDCB require a license .



- **Azure API Management**: Basic v2 with **1 instance, 10M requests/month, 100 GB egress, 1 region** listed at **€129.02/month** in a Spanish public procurement document . Azure's own cost planning page shows a **Basic tier with 1 unit at $0.07/hour (~$48.03/month)** .



- **Gravitee**: **Planet $2,500/month** (1 production + 1 non-production gateway, 1 module, unlimited users); Galaxy and Universe are custom-priced . Gartner Magic Quadrant 2026 leader .



- **WSO2 API Platform**: **Pay-as-you-go from $119/month** (up to 10 managed interfaces, 10M gateway events); **30-day free trial** with 5 interfaces and 10M events; Enterprise is custom with self-hosted option . WSO2 API Manager is **Apache 2.0** and fully self-hostable .



- **MuleSoft**: Vendr median contract **$68,695**; implementation services typically **20–40% of first-year software costs**; renewal escalations standard, uncapped renewals can see larger increases .



- **Traefik**: Commercial Hub tiers are **gated behind sales contact**; 30-day free trial for API Gateway tier . Traefik Proxy is **MIT** .



**What is missing:**

- **No pricing** for Postman API Gateway Integrations (it is not a gateway; pricing would be Postman's plans, which were not surfaced).

- **No star counts** for any open-source gateway in the results.

- **No revenue or valuation data** for Kong, Tyk, Gravitee, WSO2, MuleSoft, Apigee, or Traefik.



## What I recommend



**Split the list into three honest categories:**



**1. Full API Management Platforms** (proprietary or open-core): Kong, Apigee, Azure API Management, Gravitee, WSO2, MuleSoft, Tyk.



**2. Open-Source Gateways** (genuinely free): **Tyk Gateway** (MPL 2.0) , **Traefik Proxy** (MIT) , **WSO2 API Manager** (Apache 2.0, full platform) .



**3. Outliers to remove or reframe:** Postman (API client, not gateway); Traefik (edge router, not full APIM).



**The open-source section is genuinely strong** for gateways—Tyk Gateway, Traefik Proxy, and WSO2 API Manager are all free with real licenses. The proprietary section has usable pricing for Kong, Apigee, Azure, Gravitee, WSO2, and MuleSoft. AWS API Gateway is pay-per-use with a free tier.



If you paste your current `README.md` and confirm you want the split framing, I will produce the complete file as text for you to save. I will not fabricate star counts, valuations, or pricing for Postman or Traefik's commercial tiers that the results do not support.
