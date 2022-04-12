# Robonomics Grant Proposal

> The Proposal document will contain information about the project you would like to implement using the Robonomics grant. We recommend to provide full and comprehensive information to speed up the proposal review process. Comments in the lines starting with a `>` can be deleted.

> NB: The main cryptocurrency for funding is **Robonomics** token ([XRT](https://www.coingecko.com/en/coins/robonomics-network)). Also, the grant can be provided in **Dai Stablecoin** ([DAI](https://www.coingecko.com/en/coins/dai)) or **Ethereum** tokens ([ETH](https://www.coingecko.com/en/coins/ethereum)), but applicants need to provide a reasoned explanation to different cryptocurrency in Additional Information. For the calculation, we use the exchange rate on the date when you proposal is being approved.

## 1. Administrative Information :white_check_mark:

* **Project Name:** Smart Bin W2V
* **Organisation Name:** W2V Eco Solutions LLC
* **Project Summary:** Smart container as a part of or whole project.  Our team sees great potential of a circular model economy for producers and companies, which use plastic for their package, such as PET-bottles recyclables in a production cycle, and for consumers & local communities from the other hand - as a financial value from sorting waste.
* **Total Estimated Duration:** 5 months
* **Expected Project Start / End Dates:** Place start and end dates here
* **Requested Funding:** 50k in XRT
* **Payment Address:** 0xe88f58a6d55882d5C1347Dd2F67E5Bf0e0F57d2A

---

## 2. Project Overview :bookmark_tabs:

<p align="center">

<img src="src/robonomics-grant-program
/smart_bin_w2v/schema-website.jpg">

</p>

1. What are the problems that the project is trying to solve?
W2V Eco solutions solves problem of incentivizing usage of recycling materials in production cycle & collecting big data for analyzing market sentiment by:
 - creating recycling cryptoexchange 
 - smart bin solution
 - metaverse game for recycling/plogging activists
Smartbin is a proprietary hardware & software solution, that:
 - sorts pet plastic by color & transparency - electronic device
 - shreds it into flake (as prepared raw product for production) - hardware device
 - sends every recycling action into blockchain & rewards consumer - robonomics
Data on blockchain is shared with recycling crypto exchange.
The global network of installed smartbins is considered as a member of exchange as a network of IOT devices, providing truthful data of market sentiment & supply.

2. Why do you want Robonomics Network to be used for solving those problems? 
Network of smartbins globally is aimed to record all transactions in robonomics network to collect big data & shape a real time supply for recycling cryptoexchange parties & reward consumer with cryptocurrency to his wallet.

3. What are expected main result of the project?
Smartbin phase 1 development phase is aimed to complete full recycling cycle by:
 - color/transparency PET bottle detection & sorting
 - shredding a PET bottle
 - recording all data relating to recycling action to blockchain
 - rewarding consumers with crypto currency based on transactions recorded via Robonomics network.
Initially one device should be fully functional prototype according to cycle described above.

4. Do you plan to exploit the result in the future (academic, commercial)?
Yes, by completing working prototype smartbin device our company has plans to build a network of smart bin devices - an IOT network of robotics solutions for supplying chains for recycling crypto exchange.

5. What is your personal motivation to implement this project?
As a member of W2V recycling solutions company I am motivated to be a game changer for more sustainable society,that values recyclables as an economical value for building future infrastructure, leaving green grass & clean air for next generations.

6. Are there any other projects similar to yours? 
Alibaba launched their own network of recycling machines which use artificial intelligence in partnership with Unilever in China.
Tomra recycling machines are widely in usage across Europe.

7. In what way is your project different from the existing ones?
Smartbin unit not only collects PET bottle, but also turns pet plastic bottle into non-reversable secondary raw material - flake. 
Smartbin unit is a compact solution (a cube with 1m side dimension) comparing to Tomra (which represents a conveyor line with sorting devices)
Smartbin unit is going to use cryptocurrency as reward comparing to competition
Smartbin unit is compatible with game app, where user can spend his/her rewards as discounts, NFT or game/metaverse artifacts.


## 3. Technical Details :pager:

1. Details of how your project uses Robonomics Network.
    1. An overview of how you use the Robonomics technology stack in the development of your project.
    Each recycling action is recorded into blockchain, indicating timestamp, robot device id (smartbin id), number of items recycled, characteristics of recycled items (color, transparency - collected from sensor chips) & user id (user reference id in our mobile application). Robonomics blockchain transaction is a prove, that user should get a crypto reward in exchange of recycling action inside our app. 
Since Robonomics allows to use robots as autonomous agents connected between each other & shaping network of devices, we at W2V, use this feature to optimize our logistics.
We plan to record each recycling cycle performed by smartbin into transactions & calculating remaining space in the smartbin after each transaction. Since our devices are connected into a network of smart bins in a given locality - we can optimize our logistics process in a given location, by knowing each smartbin free remaining space & a volume our truck can collect from this location, therefore by reaching some threshold, all generated material should be collected in a location.
For storing recycling transactions we plan to use Robonomics datalog module
For sensors connectivity we plan to use Autonomous Intelligent Robot Agent package
https://wiki.robonomics.network/docs/en/rio-datalog/

    2. Description of the planned load on the Robonomics network: **indicate the period (3-9 months)** and briefly describe the intended purpose of the transactions.
    Planned load - one transaction per day or 90 transactions per 3 months.  Each transaction record includes: indicating timestamp, robot device id (smartbin id), number of items recycled, characteristics of recycled items (color, transparency - collected from sensor chips) & user id (user reference id in our mobile application)

2. An overview of the rest technology stack to be used (except Robonomics). This may include items such as: 
    1. Links to documentation of software, components, protocols, architecture, data models, API specifications, etc. that you based your project on.
 - Radioelectronic scheme https://drive.google.com/file/d/1vf_qDbprsdlulMvwlVKpbXyF36naQJ3P/view?usp=sharing
 - Arduino bottle detection & qr transaction generation code (https://drive.google.com/file/d/1FZ2G04zfXsQEe6BA2aA1nae7ntAOvy0y/view?usp=sharing)
 - visual concept https://drive.google.com/file/d/1ZTpc8G2wfMm2lLiRFy1lNe54spgmjNVT/view?usp=drivesdk
 - smartbin concept documents https://drive.google.com/drive/folders/1AqU_5HJV5J7CYp7e8BplREvAugpK6u96?usp=sharing
 - technical drawings https://drive.google.com/drive/folders/1euILH1rLinwgm6qdepWIgU8RJee7QG8j?usp=sharing
 - video reports of working concept (!! to be updated)

   2. Robot Operating System packages to be used (please, indicate them as a separate item).
 At the current stage of our project, we do not use ROS
   
   3. Description of the robots, devices, sensors, equipment, etc. to be used.
   Arduino Mega - Controls nodes according to the specified algorithm
    IR sensors, photocells - React to changes in the medium and determine the color chromakey of the bottle.
    
   4. Known studies, methods, algorithms that you want to use.
    Machine Learning Method for Identifying Plastic Bottles
    
   5. Previous projects, Proof-of-Concept, MVP that you based this project on.
BeEko - Creating economic value from a product that is seen as "waste"
https://ua.w2v.io/
Application - https://play.google.com/store/apps/details?id=com.beeko.beekoapp2
Recereum - Recereum is blockchain-based platform for turning waste and recyclables to real value
https://recereum.com/

3. In the case of the prior development, any details about it: publications, repositories, articles, etc.
https://w2v.io/component/content/article/18-posts/65-waste-to-value-travel-to-ukraine.html?Itemid=279
https://korosten.today/inshe/sortuj-smittya-grayuchi-v-korosteni-zapuskayut-unikalnij-startap.html


---

## 4. Team :busts_in_silhouette:

> In this section, you can describe your team and indicate your scientific and professional experience (scientific papers, blog posts, PhD thesis, GitHub repositories, links to projects’ sites and videos and any other information).

* **Organization** (if applicable):
    * W2V Eco Solutions LLC
    * 1804 Scarlett Drive, Hackettstown, NJ, 07840, USA
    * https://w2v.io/
* **Contact person**:
    * Grigoryi Shegeda
    * Co-Founder
    * email - grishaaz1@gmail.com, Telegram - @batmanislive
    * CIO
    * Extensive experience in blockchain and smart contracts development, independent contractor; 10 years of work experience as a leading engineer in the energy industry; experienced social media marketing manager and content creator.

* **Team person #1**:
    * Valentine Zimnitsky
    * CEO & Founder
    * A visionary, strategic thinker, cryptocurrency/blockchain/ environmental protection enthusiast, with over 20 years of international business and consulting experience working for several S&P 500 Top 50 Companies globally.

* **Team person #2**:
    * Klym Shabalin
    * CTO & Co-Founder
    * Experience in development of web applications & APIs, 10 years as leading developer and 6 years - as webstudio owner; marketing and research for startups; founder of social projects
    
* **Team person #3**:
    * Alexey Babyshanov
    * Engineer 
    * Engineer, structural designer; 20 years of experience in the design of production lines and assemblies.
  
*  **Team person #4**:
    * Yevhen Dudkin
    * Engineer 
    * Engineer, structural designer; 12 years of experience in the design of production lines and assemblies.


---

## 5. Expected results :package:

In the end of project we expect to launch full operational Smart Container.

---

## 6. Project Schedule :date:

> Here you can provide the table of expected tasks with a short description of every task. This list is not strict, and you are free to adhere to a different schedule during the grant implementation. First of all, the list is needed so that you can orientate yourself on the upcoming project. Secondly, such a list will demonstrate to us that you have a clear understanding of the goals and objectives.

> Alternatively, if your table is too large, you can upload the table as a image. How to upload and use images is described in section 2.

| No. | Task description                       | Start/end dates |
|:---:|:--------------------------------------:|:---------------:|
| 1 |Initiation Opportunity and Risk Analysis|      01.21 - 02.21      |
| 2 |Formulation Concept and Feasibility     |       02.21 - 04.21       |
| 3 |Design and Development|       05.21 - 12.21      |
| 4 |Product Launch Preperation|       02.22 - 04.22      |
| 5 |Product Launch and Post Launch Assessment|      05.22 - 07.22      |

---

## 7. Project Budget :moneybag:

> Here you can specify how you plan to use the Robonomics grant. Again, this list is not strict and is intended to help you and us better understand the project.

> You also need to calculate the approximate total costs of transactions to Robonomics Network yourself. Please keep these costs in mind when planning your budget.

| No. |       Expense Item      |   Calculation   |   Total cost    |
|:---:|:-----------------------:|:---------------:|:---------------:|
| 1 |           Electronics part           |       120hrs*25usd       |     ...         |
| 2 |           IOS/Android APP          |       100hrs*25usd       |     ...         |
| ... |           Hardware part           |       ...       |     ...         |
| 3 |           Materials:
- metal part of the hull including laser cutting
           |       1200       |     ...         |
| ... |           polycarbonate viewports           |       400       |     ...         |
| ... |           65T steel for shredder          |       300       |     ...         |
| ... |gearmotor|       500      |     ... |
| ... |shredder converter|       300       |     ... |
| ... |worm mini-motor gearbox|       400       |     ... |
| ... |proximity switches|       400       |     ... |
| ... |pulleys for machinery|       200       |     ... |
| ... |painting, anodizing|       230       |     ... |
| ... |arduino Mega|       75       |     ... |
| ... |Welding, assembling|      1100       |     ... |
| ... |Network transaction costs|       ...       |     ... |
|     |                         |    **TOTAL:**   |                 |

---

## 8. Additional Information :information_source: 

We find out about Robonomics Grant Program From Twitter

Hardware solution is a part of whole W2V Ecosystem, which consists of:
1. Application for incentivizing people for proper sorting recyclables
2. Hardware smart container
3. Tokenized recyclables exchange
Our solution is based on several major principal such as:
- Creation of the incentive mechanism that is designed to reward economically an improved attitude for a proper PET bottles recycling
- Creation of an additional economic value by applying a blockchain-based platform and crypto currency token that generates intrinsic economic value for the platform users
- Transformation of the plastic as raw material into other real and digital commodities.
