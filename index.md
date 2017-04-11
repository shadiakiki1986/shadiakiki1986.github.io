### About me
I am a financial engineer, and I focus on automation by leveraging upon open-source technology to achieve goals while minimizing costs.

## Internships (2017)
ATM (2017-04-11) I am looking for interns to help me with my work.
[Here](https://github.com/search?q=label%3Abounty+author%3Ashadiakiki1986&type=Issues&utf8=%E2%9C%93)
is my list of issues for which I'm offering bounties.
I try to set the bounties such that it's almost a 10$/hour pay.
Coincidently, I'm also getting married next week (wish me luck),
so it'll be around 2 months before I get back to actively adding issues to the list.

### Products
Here are some products that I've built
* [The Allocator](http://shadiakiki1986.github.io/the-allocator/): platform in which a user sets up strategies and distributes accounts to those strategies .. the system calculates what trades are required for accounts to be in-line with the strategy .. can save locally or interact with a server
* [Options strategy visualizer](http://shadiakiki1986.github.io/options-strategy-visualizer/): based on Black-Scholes option price calculation, this visualizes the P&L of a combination of options .. also provides API end-points
* [IDES Receiver](http://shadiakiki1986.github.io/IDES-Receiver): for [FATCA](https://www.irs.gov/Businesses/Corporations/Foreign-Account-Tax-Compliance-Act-FATCA) compliance, this is a Single-Page Application that can read an institution's private key and use it to decompress and decrypt zip files received from the IRS via the [IDES](https://www.ides-support.com/) gateway
* [IDES Data Preparation](https://github.com/shadiakiki1986/IDES-Data-Preparation-Php): for [FATCA](https://www.irs.gov/Businesses/Corporations/Foreign-Account-Tax-Compliance-Act-FATCA) compliance, this is a back-end that fetches data from the institution's database and generates files submittable to the [IDES](https://www.ides-support.com/) gateway
* __Mobile application for financial institution__: built and published server-side and client-side app for a bank's clients to log in and check their accounts. Brokers can also log in and manage their clients' accounts. The bank already had a regular website for logins. I wrote an HTML scraper that extracted the data that formed the basis of my server-side and client-side applications.
* __Database augmenter__: stands between an existing read-only database and an application and augments the original database tables with more fields without modifying the database itself
* __Factsheet downloader__: downloads fund fact sheets weekly and sends out a small email listing which fact sheets were updated from the week before or not
* __Database API__: wrote up an API to access a proprietary undocumented database
* __Reconciliation__: tool that reconciles positions with miscellaneous custodians and highlights price differences or missing positions
* __CME/CFTC large-trader reports__: daily emails to risk/control department with clients holding positions reportable as per the [CFTC large-trader reporting program](http://www.cftc.gov/IndustryOversight/MarketSurveillance/LargeTraderReportingProgram/index.htm)
* __Miscellaneous financial accounting reports__: credit risk report (Basel II), liquidity risk report, merged trial balances between two related financial institutions, ...
* __Miscellaneous compliance reports__: automatic notifications of dormant accounts, significant trades, large client NAV jumps due to market moves, ...
* __Price feeder__: centralized storage of close prices that come from various sources. Can also scrape some exchanges' websites and store daily close prices for usage in further reports. Can also feed prices directly into Microsoft Excel via weblinks

Here are some data pipelines I've set up between a bank's core system and 3rd party software
* __Banking system-SironAML link__: automatic daily import of trades and client information from a banking system's database into [SironAML](http://www.tonbeller.com/en/solutions/anti-money-laundering/anti-money-laundering-for-banks/) (3rd party anti-money laundering software). Also performed analysis to set up the proper scenarios required for the program
* __Banking system - CRM link__: Mirroring of banking system client data to Microsoft CRM, done in collaboration with the providers of the Microsoft CRM system
* __Banking system-Fingerprints machine lock__: linked a fingerprints machine to a banking system such that when a user leaves a building, his/her username is logged out and locked from using the system
* __Banking system-BDL CDR credit risk application__: the [BDL CDR](http://www.banqueduliban.gov.lb/tabs/index/4/293/CENTRALE-DES-RISQUES.html) requires banks registered with it to report monthly on all client loans beyond a particular threshold. This tool makes the necessary calculation to generate a file with the relevant data that is importable into the CDR's tool

Here are some mobile apps that I've built for fun
* [Yet another zboota app](http://shadiakiki1986.github.io/zboota-server/): front-end + back-end for tracking driving tickets in Lebanon in the app and by automatic email notification .. as of 2015-10-10 there are more than 1000 cars registered in the app
* [Yolo bear](http://shadiakiki1986.github.io/yolo-bear): live tournament results broadcasting
* __Remote controller of electrical equipment__: mobile application that communicates via [Pusher](https://pusher.com/) and redundantly by [Sync](https://www.getsync.com/) to a [Raspberry Pi](https://www.raspberrypi.org/) to turn on and off electrical equipment connected to it

### Services
Here are some services that I've provided
* Intermediation between financial institution and software providers
 * Managing the project of modifications needed to be made to the main banking software so that being FATCA-compliant would be easy
 * Reverse-engineering the margin calculator tool made by [Eurex](http://www.eurexchange.com/exchange-en/trading/trading-tools/margin-calculators/risk-based-margincalculator/) which calculates [strategy-based margin calculation](http://www.cboe.com/micro/margin/strategy.aspx). Writing up the documentation and calculations to explain to the banking software providers how to implement this. I also wrote the [Options strategy visualizer](http://shadiakiki1986.github.io/options-strategy-visualizer/) (mentioned in my list of products above) for this
* Custom reporting based on a banking system's database
* Data analysis of financial transaction data to answer various questions posed by management
* Organized data cleaning of database using fuzzy string matching to aggregate accounts belonging to the same client in preparation for FATCA reporting and automated CDR reporting (both mentioned in list of products above)
* Asset management: I didn't give financial advice, but I helped a high-net-worth individual to use [Horizon](http://www.qnesssoftware.com/our_product.html) (an accounting tool that consolidates multiple bank accounts into one platform) to understand how his money was being invested

### Development tools
Here are some of my favorite tools for development, data analysis, shared documentation, etc.
* [Ubuntu server](http://www.ubuntu.com/server): server operating system
* containers: docker
* web app framework: django
* server-side: [php](http://php.net/), python, nodejs, golang
* inter-services messaging: [nats](http://nats.io)
* web server: [Apache HTTP server](https://httpd.apache.org/), nginx
* [AWS EC2](https://aws.amazon.com/ec2/): server hosting
* [AngularJS](https://angularjs.org/): client-side application
* [R](https://www.r-project.org/): data analysis
* [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki): shared documentation
* [Wink](http://www.debugmode.com/wink/): screen capturing
* [Apache Cordova](https://cordova.apache.org/): cross-platform mobile app development

### Contact
* You can download my most recent CV [here](https://www.dropbox.com/s/2iw1d9w0dg3rshb/CV-ShadiAkiki-201510.pdf?dl=0). It includes my contact information.
* I am also listed on <a  style="color:#0E77B0" href="http://www.datadubai.com/">Dubai Classifieds & Business Directory</a>.  under <a  style="color:#0E77B0" href="http://www.datadubai.com/United_Arab_Emirates/Dubai/Dubai_Business_and_Economy/Finance/Banking_Equipment/1434.html">Banking Equipment</a> category

Last edited on: 2017-04-11
