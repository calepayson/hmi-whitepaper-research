# Notes

## The Cloud

X as a service. The key is compute.

### [The NIST Definition of Cloud Computing](https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-145.pdf)

**Essential Characteristics of Cloud Computing:**
- **On-Demand Self-Service** - "A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction with each service provider."
- **Broad Network Acceess** - "Capabilities are available over the network and accessed through standard mechanisms that promote use by heterogeneous thin or thick client platforms (e.g., mobile phones, tablets, laptops, and workstations)."
- **Resource Pooling** - "The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically assigned and reassigned according to consumer demand. There is a sense of location independence in that the customer generally has no control or knowledge over the exact location of the provided resources but may be able to specify location at a higher level of abstraction (e.g., country, state, or datacenter). Examples of resources include storage, processing, memory, and network bandwidth."
- **Rapid Elasticity** - "Capabilities can be elastically provisioned and released, in some cases automatically, to scale rapidly outward and inward commensurate with demand. To the consumer, the capabilities available for provisioning often appear to be unlimited and can be appropriated in any quantity at any time."
- **Measured Service** - "Cloud systems automatically control and optimize resource use by leveraging a metering capability1 at some level of abstraction appropriate to the type of service (e.g., storage, processing, bandwidth, and active user accounts). Resource usage can be monitored, controlled, and reported, providing transparency for both the provider and consumer of the utilized service."

### [ELI5 - what makes "the cloud" different from "the internet](https://www.reddit.com/r/explainlikeimfive/comments/mxkpp/eli5_what_makes_the_cloud_different_from_the/)

- A reddit thread on the cloud that aged wonderfully.
- [u/mehughes124 provides a great history of the significance](https://www.reddit.com/r/explainlikeimfive/comments/mxkpp/eli5_what_makes_the_cloud_different_from_the/c34ox39/)
- [A solid example of what the cloud solved](https://www.reddit.com/r/explainlikeimfive/comments/mxkpp/eli5_what_makes_the_cloud_different_from_the/c34ozik/)
- [A nice translation of the NIST definition](https://www.reddit.com/r/explainlikeimfive/comments/mxkpp/eli5_what_makes_the_cloud_different_from_the/c34osvj/)

## Mainframes and Time Sharing

... (IBM?) ...

## Internet Based Services

... 

## Loudcloud

The first true cloud company. Loudcloud was founded on 1999-09-09 by Marc Andreessen, Ben Horowitz, and others. They supplied companies with plug-and-play "clouds" for common webdev jobs like building a database. Internally they managed these clouds with a proprietary software, Opsware, that automated generating, managing, and allocating resources for the clouds. 

They scaled insanely quickly (averaged an employee a day initially). Their fundraising, revenue, and burn matched this. They were racing to carve out market share and the dot-com crash caught them to far out over their skis. Many of their customers (dot-com companies) went bankrupt or churned and Loudcloud had no buffer. Deep underwater, they pivoted from a cloud company (Loudcloud) to a software company (Opsware). They sold their cloud business and refactored their internal software in order to sell it to other companies. 

There is not a lot of detail available about Loudcloud but it seems like it failed because of an overemphasis on growth at all costs coupled with a massive industry-wide recession.

### [Crank It Up](https://www.wired.com/2000/08/loudcloud/)

- Loudcloud (now Opsware) was founded in late 1999 by Marc Andreessen, Ben Horowitz, Tim Howes, and Sik Rhee.
- It was conceived of by Sik Rhee, former CTO of the ecommerce platform division at AOL, when the founding team was looking to build a new company together. He noticed that when a company was initially listed on AOL, the traffic to their website would 10X-100X and the site would inevitably crash. Rather than building a new website, he proposed building a company that built scalable web infrastructure.
- There were plenty of companies building websites for other companies but Loudcloud stood out for an emphasis on scalability through automation. Other companies scaled linearly, they had to hire a new team to build a new site. Loudcloud was able to do it with a few keystrokes and little extra manpower.
- They also automated the sites' ability to scale during increased or reduced traffic.
- Loudcloud offered a number of "clouds" like a Database Cloud or a Mail Cloud and users paid a monthly fee based on the cloud capacity they used.
- If a customer wanted to add functionality, Loudcloud would drop in a new "cloud"
- Loudcloud was the first known cloud provider to hit all the NIST criteria.

### [Update: Loudcloud now Opsware, sells part of business to EDS](https://www.computerworld.com/article/2576654/update--loudcloud-now-opsware--sells-part-of-business-to-eds.html)

- Loudcloud renamed itself to Opsware in 2002 and sold its managed services business.
- Opsware was the name of Loudcloud's IT automation software.
- This meant loudcloud pivoted from building websites to selling software that allowed companies to build them.
- Editorial note: this seems like the death blow for Loudcloud as a cloud company. At this point they supplied software to companies that helped them develop an "internal" cloud instead of cloud computing and storage as a service.

### [The Hard Thing About Hard Things](http://library.lol/main/77F9C848EC4403E988972C467FC17949)

- Loudcloud was initially financed by Benchmark Capital and Marc Andreessen. Benchmark put in $15m at a pre-money valuation of $45m. Andreessen invested an additional $6m.
- After two months they raised an additional $45m from Morgan Stanley in debts with no payment for three years.
- Advice from Andy Rachleff of Benchmark Capital: "Think about how you might run the business if capital were free".
- Initially they averaged hiring 30 employees a month.
- Nine months in they booked $27m of new contracts in a quarter.
- This is about when the dot-com crash hit.
- They had spent $66m to build a cloud service and needed to raise money again
- Raised a series C at $700m pre-money and raised $120m in Q1 2000. 
- In Q2 2000 they expected $100m in sales but only booked $37m.
- Needed to raise more in Q4 2000 but couldn't find an investor.
- The only option was to go public.
- Business model:
	- Signed customers to two-year contracts, and recognized revenue monthly
	- Focused on Unix applications
- Wanted to offer at $10 per share at a total valuation of $700m
- Ended up selling at $6 a share and raised $162.5m
- Remember, this is in the middle of the dot-com crash
- Due to churn and declining sales prospects it became clear they wouldn't hit their forecasts for the year
- The stock dropped to $2
- Exodus, their largest competitor went bankrupt on Sep 26 2001.
	- 9 months before had been valued at $50b and had raised $800m
- Shit was hitting the fan.
- “What would I do if we went bankrupt?” The answer that I came up with surprised me: “I’d buy our software, Opsware, which runs in Loudcloud, out of bankruptcy and start a software company.” Opsware was the software that we’d written to automate all the tasks of running the cloud: provisioning servers and networking equipment, deploying applications, recovering the environment in case of disaster, and so forth.”
- their biggest client went bankrupt in Q1 2002, a loss of $25m revenue.
- This prompted Loudcloud's shift to Opsware.
- 440 of 450 were working in the cloud business. 10 were working to make the opsware software a viable product.
- "The only way out of the cloud business without going bankrupt was through higher sales, because even if we laid off 100 percent of the employees, the infrastructure costs would still kill us without a sharper sales ramp"
- Started thinking about selling the company
- Sold Loudcloud to EDS for $64.5m in cash
	- Opsware retained the intellectual property and became a software company
	- EDS agreed to license the software to run Loudcloud and EDS for $20m a year
- Stock price fell to $0.35 per share then slowly rose to $1 / share
- Now they had to refactor the software to make it market ready.
- The rest is all about opsware. The moral is, they left the cloud business.

## Amazon Web Services

### [How Amazon grew an awkward side project into AWS, a behemoth that's now 4 times bigger than its original shopping business](https://fortune.com/longform/amazon-web-services-ceo-adam-selipsky-cloud-computing/)

- Amazon seems quite secretive. Won't mention number of employees working on AWS
- Folklore suggests AWS started when Amazon started renting spare computer capacity to other companies.
- AWS was born from two problems
	- Amazon had built a massive website from scratch but was deploying tons of resources on building the foundational infrastructure. 
		- Each project team was building this same infrastructure for their project. 
		- Bezos called it undifferentiated heavy lifting
		- To deal with this they started building a shared infrastructure layer that every team could use. Things like storage, compute, capabilities, and databases.
	- Other websites wanted to add amazon links but amazon had write a code snippet for every site.
		- In 2002 Amazon released a piece of software that allowed these websites to build a custom link by writing code. 
		- On the release of the free version of this software, Amazon noticed that their own developers were using it. 
- AWS seems like a hard pivot for Amazon until you realize that they saw themselves as a technology company that happened to dive into retail first.
- In March 2006 AWS launched S3 (Simple Storage Service). 12,000 developers signed up.
- Around August 2006 it launched EC2 (Elastic Compute Cloud).
- Both were massive successes because they were built for individual developers while allowing the them to scale to the size of a massive company.
- “A business miracle happened,” Bezos told a conference years later. “This is the greatest piece of business luck in the history of business so far as I know. We faced no like-minded competition for seven years. I think the big established enterprise software companies did not see Amazon as a credible enterprise software company, so we had this incredible runway.”
- Amazon does not have a "competitive strategy" it has a "customer strategy"

### [How AWS came to be](https://techcrunch.com/2016/07/02/andy-jassys-brief-history-of-the-genesis-of-aws/)

- In the 2000s Amazon was having a hard time scaling which forced them to build scalable internal systems.
- In 2000 they wanted to launch a service called Merchant.com so that retailers could build shopping sites with Amazon's e-commerce engine.
- This proved nearly impossible due to technical debt
- They solved their technical debt by turning it all into a set of well-documented API's
- These API's proved valuable to internal developers
- decoupled, API-access design became the standard
- At this time Amazon was seeing delays when building new applications
- The issue was that it took months to spin up the infrastructure for each project
- They set out to solve this with the decoupled, API access design and stumbled into a product
- In 2003 they began to articulate the idea of AWS thinking of it as an operating system for the internet

### [A Brief History Of AWS - And How Computing Has Changed](https://digitalcloud.training/a-brief-history-of-aws-and-how-computing-has-changed/)

...

### [The Everything Store](http://library.lol/main/587CF274189E03927340B6448315440D)

...

## Google Cloud

...

## Microsoft Azure

...

