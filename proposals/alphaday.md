# Robonomics Grant Proposal

## 1. Administrative Information :white_check_mark:

* **Project Name:** Alphaday
* **Organisation Name:** Alphabox Solutions Pte. Ltd.
* **Project Summary:** Alphaday is a powerful crypto workflow aggregator that pulls in news, on-chain data, social media, web3 services and much more into one customizable UI.
* **Total Estimated Duration:** 1-2 months initial deployment, plus 12 months maintenance & curation.
* **Expected Project Start / End Dates:** 15/06/2023 - 15/08/2023 (for deployment)
* **Requested Funding:** 3000 DAI
* **Payment Address:** 0x48e239Fa0B364Cd92Fc750A50045c9f9E04DD781

---

## 2. Project Overview :bookmark_tabs:

Alphaday is a powerful crypto workflow aggregator that pulls in news, on-chain data, social media, web3 services and much more into one customizable UI.

We build crypto experience dashboards for enthusiasts, developers, and projects. Users can drag and drop from hundreds of services, news and social feeds, charts, and dapp functionality to create their daily workflows inside a single dashboard. This eliminates the need to have multiple browser tabs open to get different bits of information. i.e. imagine having token prices, gas prices, twitter feed, latest news headlines, TVL, borrowing rates and any other information any user could possibly want, all within one single dashboard. 

Alphaday has no direct competitors as it aims to recreate a crypto user’s daily workflow (i.e. their general experience) inside a single dashboard. i.e. if a Robonomics ecosystem participant wakes up, checks their portfolio, reads twitter, browses the governance forum, listens to the latest podcast featuring team members,  does a bit of on-chain research, instead of having this workflow spread across a dozen tabs, it’s all available within a single screen on Alphaday.

## 3. Technical Details :pager:

Alphaday is a React-Typescript dashboard on the frontend using a Python-Django backend built on distributed infrastructure with Postgres and Redis Databases.

As a data aggregator, our application is blockchain-agnostic.

Project Github Repo: https://github.com/AlphadayHQ / 
Live Product: https://app.alphaday.com/ /
Landing Page: https://alphaday.com/ /
Pitch Deck: https://bit.ly/Alphadaydeck

---

## 4. Team :busts_in_silhouette:

* **Organization** (if applicable):
    * Alphabox Solutions Pte. Ltd.
    * North Canal Road, 059294 Singapore, Singapore

* **Contact person**:
    * Full Name: Michael Hagopian
    * Position at the organisation (if applicable): QA/Testing & Analyst
    * Main contact address (email, Telegram or Element Riot): mike@alphaday.com
    * Role in the project (if applicable): QA/Testing & Analyst
    * Experience (if applicable): I have been involved in Ethereum from mid-2017 onwards and since early last year I've been part of the team building Alphaday.

* **Team Members**:

Name: Deniz Omer \
Position: Founder \
Short Bio: Has been involved in the Ethereum space since early 2016 and joined Kyber Network in 2017 as Head of Ecosystem Growth before quitting to start Alphaday full-time in 2021. Previously he worked at Thomson Reuters for a decade building financial products that rivaled the Bloomberg Terminal. He is currently also a Venture Partner at IOSG.VC. \
https://twitter.com/DenizOmer, https://www.linkedin.com/in/denizomer/ 

Name: Felipe Faraggi \
Position: Co-founder \
Short Bio: Has also been involved in Ethereum since 2016 and was a Developer Advocate at Pegasys and Consensys before quitting to work full time on Alphaday. \
https://github.com/faraggi, https://twitter.com/felipefaraggi, https://www.linkedin.com/in/faraggi/ 

Name: Pablo Palomo \
Position: Technical Lead \
https://github.com/ppalomo, https://twitter.com/ppalomo, https://www.linkedin.com/in/pablo-palomo-07127711/ 

Name: Vicente Almonacid \
Position: Software Engineer \
https://github.com/v-almonacid, https://twitter.com/v_almonacid, https://www.linkedin.com/in/vicente-almonacid/ 

Name: Charles Nwankwo \
Position: Developer \
https://github.com/Xavier-Charles, https://twitter.com/Chadnium, https://www.linkedin.com/in/charles-nwankwo-01/ 

Name: Jonathan Irhodia \
Position: Developer \
https://github.com/elcharitas, https://twitter.com/iamelcharitas, https://linkedin.com/in/elcharitas 

Name: Gideon Anyalewechi \
Position: Developer \
https://github.com/getgiddy, https://twitter.com/get_giddy, https://www.linkedin.com/in/getgiddy/ 

Name: Paris Charanas Giannakou \
Position: Analyst & Content Curation \
https://twitter.com/GrifousG, https://www.linkedin.com/in/paris-charanas-giannakou-788386231/ 

Name: Michael Hagopian \
Position: QA & Analyst \
https://twitter.com/MikeJa33, https://www.linkedin.com/in/mikael-h-87bb4ba4/ 

---

## 5. Expected results :package:

> In this section, you are invited to describe what specific results your team is planning to produce by the end of the project. It can be: setup, launch and test guides, theory and calculations, reports, repositories, ROS modules, articles, videos, blog posts, etc. (max. one page long).


We launched our public beta in August 2022 and have been growing roughly 40% month on month and currently have 10,000 MAU but have in mind this is with minimal marketing and promotion. We expect numbers to significantly increase as we’ve agreed with projects like Aave, Dfinity, Zcash and a dozen others to publicly release dashboards for their communities throughout the next few months. *Note that the dashboards are already built and are live on our app, but not marketed or announced yet.

During the dashboard building process, we create a template for Robonomics, and share it with your team. We then make changes based on your feedback until you deem it ready to be shared with the community. We then set a date on which we publicly announce the dashboard.

Once we deploy the initial Robonomics dashboard, we will promote this across the community and start collecting feedback so that we can keep iterating and improving our dashboard. For us success is if a large number of stakeholders come to the Robonomics dashboard to stay up to date with everything happening within the project and then use the available data as jumping off points into the various parts of the ecosystem. i.e. XRT holders using the board to finding trending topics to participate in, devs using the resource library to dive deeper into the technical documents & API’s, newcomers listening to the latest podcasts and exploring open job positions at Robonomics.

In terms of concrete numbers, considering Robonomics has 30K twitter followers and using this as a very crude proxy for community size, we would consider it a success if we could serve at least 3% of them on a monthly basis (900 MAU).

The grant work will result in a dashboard dedicated to serving the Robonomics community by aggregating all relevant information about Robonomics including media communities, news, on-chain metrics, Robonomics documentation, XRTtokenomics into one place. Our desired outcome is to provide a new end-point for community engagement and to bolster Robonomics’ outreach.

---

## 6. Project Schedule :date:

Milestone 1 — Development and Deployment of initial dashboard:

We would like to create a Robonomics ecosystem dashboard that aggregates the following information into a single community dashboard:

1. The latest Robonomics official announcements and blog post content.
2. A feed of all news mentions of Robonomics from coindesk, cointelegraph and 20+ other news sources aggregated from across the internet.
3. A calendar containing all Robonomics events including Robonomics Governance votes, meetups, hackathons with Robonomics bounties, AMAs.
4. Podcast feed containing the latest appearances and interviews given by Robonomics team members.
5. Youtube stream containing educational Robonomics content.
6. Robonomics Wiki directory.
7. Integration with Robonomics Governance Forum to show the latest and trending discussion topics.
8. Twitter, Discord & Telegram Integration to show a feed of latest discussions.
9. FAQs, Science Papers & Whitepaper, book library, XRT tokenomics information.
10. A widget featuring the Robonomics roadmap with all the descriptions and links included.
11. Links and descriptions of Dapps and other platforms within the Robonomics ecosystem, including exchanges to buy XRT.

We should be able to build and deploy the above dashboard within ~2 months so if this grant is approved we want to launch the Robonomics dashboard by August 2023.

Milestone 2  — Maintenance and curation of dashboard and contents:

Maintenance and Curation: 12 months of maintenance including having an Alphaday content analyst quality-checking the dashboard every day and ensuring the Calendar widget is up-to-date with latest Robonomics events, all news mentions across the internet are captured by the dashboard, any updates not automatically captured by the Alphaday aggregator engine is manually added to the board, and other maintenance tasks.

Further to the above, we will consistently improve the functionality and availability of features in our application as a whole. Our aim in this is to add value to our application for everyday users within the industry.

Please note that we can add and remove widgets and/or contents as required by your team. For a brief idea about other widgets and data that we can provide, please visit our Live product page (Beta) at: https://app.alphaday.com/  

---

## 7. Project Budget :moneybag:

  | Milestone    | Estimated Duration  | Full-time equivalent   | Cost         |
  | ----------- 	 | ------------         | -------------------- | ------------- |
  | Milestone 1  |   60d                |     0.5                |   1500 DAI     |
  | Milestone 2  |   365d              |     0.5                |   1500 DAI     |
  | Total        	 |   425d              |     1                   |   3000 DAI     |

Details:
1,500 DAI upfront costs for development including integrating the discussion forums, blog post, social feed, jobs listing, TVL and other on-chain metrics.

125 DAI per month for 12 months for maintenance including having an Alphaday content analyst quality-checking the dashboard every day and ensuring the Calendar widget is up-to-date with latest Robonomics events, all news mentions across the internet are captured by the dashboard, any updates not automatically captured by the Alphaday aggregator engine is manually added to the board, and other maintenance tasks.

Total Budget Requested: 3,000 DAI.

---

## 8. Additional Information :information_source: 

We found out about the grant via online research, through the Robonomics official website.

Links:
Live Product: https://app.alphaday.com/ \
Landing Page: https://alphaday.com/ \
Twitter: https://twitter.com/AlphadayHQ \
Discord: https://discord.com/invite/8KSmPyT5k8
