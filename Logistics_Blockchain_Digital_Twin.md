# Robonomics Grant Proposal


## 1. Administrative Information :white_check_mark:

* **Project Name:** Blockchain enabled digital twin for preventing product counterfeiting in high-value supply chains
* **Organisation Name:** Dymaxion OÜ, Liiva tn 32, 11615, Tallinn, Harju maakond, Registration code 12954070 and 
Logistics department, University of Applied Sciences Upper Austria (FHOOE), Wehrgrabengasse 1, 4400 Steyr
* **Project Summary:** To show how ROBONOMICS blockchain and IOT related technologies can be applied in a given high-value supply chain to address the problem of fake products identification, verification of authentic products and tracking products ownership using digital twins concepts
* **Total Estimated Duration:** 6 months (plus one month preparatory period)
* **Expected Project Start / End Dates:** 01.12.2021 – 01.05.2021
* **Requested Funding:** DAI 50,000 USD
* **Payment Address:** 0xE358C31500EF2a7e33464C3C513d1f71F92B6BAb

---

## 2. Project Overview :bookmark_tabs:

> In this section, you reveal the main idea of the project, how you intend to use the Robonomics Network to bring your idea to life, and your motivation. The section should include the following information (max. one A4 page long):

1. What are the problems that the project is trying to solve?
Product counterfeiting is a serious and increasing problem in supply chains especially in high-value products. 
It poses economic challenges to manufacturers and poses dangers to the general well-being of customers that use such products. 
Counterfeiting occurs in heavy industries manufacturing, automatises, aviation, pharmaceuticals etc [1]. 
A lot of approaches have been proposed by researchers to address counterfeiting problems and such approaches include trademarking, patenting, improving product quality and the general brand name of legitimate producers [1,2]. 
Still, the problem of counterfeiting continues because customers have no means to independently verify the authenticity of products in a transparent and efficient manner. 

2. Why do you want Robonomics Network to be used for solving those problems? 
To show how ROBONOMICS blockchain and IOT related technologies can be applied in a given supply chain to address the problem of fake products and verification of authentic products. 
With the opportunities which blockchain technologies, IoT and RFID sensors provide, digital twin a high-value physical product can be coded in a data format and stored on blockchain. 
Thus, authenticity and ownership of such products can be tracked on the blockchain. 
The Robonomics platform  provides the possibility for developing systems that involve the interaction of IoT sensors and devices with the information stored on blockchain. 
Therefore, this project seeks to redesign the supply process for high-value products by using the Robonomics platform and related IoT technologies for storing and verifying authenticity of products using digital twin concepts.

3. What are expected main result of the project?
- Development and analysis of the current supply chain process of high-value value
- Redesign of the supply chain process of high-value products by integrating IoT (RFID) sensors and for storing digital twin of products on the Robonomics blockchain platform 
- A simulation of  a redesigned supply chain for high-value products that uses IoT sensors to record digital twins of a product on the Robonomics platform.
- A simulation of the redesigned supply chain for high-value products showing the verification of authentic products and tracking of their ownership on the ROBONOMICS platform
Do you plan to exploit the result in the future (academic, commercial)? 
There is possibility of that.

4. Do you plan to exploit the result in the future (academic, commercial)?
The main results of the project will be fully exploited for publication of research paper(s) that show the application of Robonomics platform in combating products counterfeiting in high value supply chains.

5. What is your personal motivation to implement this project?
The main motivations are as follows: this project shows a real use-case of blockchain addressing problems faced by many business organizations. The project is not necessarily too long with a tangible and measurable  output that can be easily assessed.

6. Are there any other projects similar to yours? 
  - The project  [3] explores the application of digital twins for tracing authenticity of manufactured parts in the aircraft industry.
  - The project  [4] developed a framework for development of digital twins for personalized products for industry 4.0 

7. In what way is your project different from the existing ones?
These two projects consist of digital twins proposals and methodologies that have not been implemented or evaluated with actual results from a running application. 
In our proposal, we seek to redesign the current logistic  process of high value products, implement the redesigned process on the Robomics platform, simulate the implemented solution and gather the necessary results. 
Thus, the results will be published in a paper showing the application of Robonomics in stamping out fake products in logistics. 
Aslo, the listed similar projects are specific to a unique type of supply chain - aircraft manufacturing and personalized products manufacturing. Our case is represented by any industry that manufactures or delivers high value products in its supply chain. 
Therefore, we will conduct a series of interviews for practitioners in this type of industry in order to conceptualize the current logistic process of high-value products


## 3. Technical Details :pager:

> Please, responsibly indicate if your project is based on third-party development and specify the authorship. The section should include the following information: 

1. An overview of the technology stack to be used. This may include items such as: 
    1. Links to documentation of software, components, protocols, architecture, data models, API specifications, etc. that you based your project on.
      - LInks to documentations of software, components, protocol etc
      - Getting started - https://wiki.robonomics.network/docs/en/
      - https://wiki.robonomics.network/
      - https://dapp.robonomics.network/#/
      - For technical questions on Robonomics - https://discourse.robonomics.network/
      - White paper- https://static.robonomics.network/docs/presentations/Robonomics.Keypoint.updated.August.2020.pdf
      - R&D based on Robonomics - https://wiki.robonomics.network/docs/en/r-and-d-based-on-robonomics-network/
      - Robonomics Playground -https://wiki.robonomics.network/docs/en/playground-overview/
      - Digital twins - They are digital (software) copies of a physical Asset.
      - https://azure.microsoft.com/en-us/blog/azure-digital-twins-now-generally-available-create-iot-solutions-that-model-the-real-world/
      - Parachain on the Robonomics Network allow user to create digital twins - https://robonomics.network/blog/the-ultimate-guide-to-robonomics-rws-and-robonomics-parachain-on-polkadot/
      - Build a Digital Twin for Thousands of IoT Devices with Apache Kafka and MongoDB - https://www.youtube.com/watch?v=ue_9iFoXhNc
      - Robonomics marketplace - https://dapp.robonomics.network/#/services
      - Robonomic communities - https://robonomics.network/community/#science
      - Aira OS - https://wiki.robonomics.network/docs/en/aira-installation-on-vb/,                             
      - https://wiki.robonomics.network/docs/en/interact-with-aira/
      - Robonomic web service - https://robonomics.cloud/

    2. Robot Operating System packages to be used (please, indicate them as a separate item).
       -  https://www.ros.org/, 
       -  http://wiki.ros.org/rospy
       -  ROS integration - https://github.com/airalab/robonomics#7-robotics-integration
       -  Ros installation - http://wiki.ros.org/action/fullsearch/ROS/Installation?action=fullsearch&context=180&value=linkto%3A%22ROS%2FInstallation%22
       -  https://wiki.robonomics.network/docs/en/robonomics-liability/
       -  IOT Simulation environment: 
          - https://www.simplesoft.com/SimpleIoTSimulator.html 
          - Node-red IOT device simulator - https://flows.nodered.org/flow/de9ad7f94c78343416ccb1ec0d4a5b2b
       -  Process/ Workflow Simulation environment
            - JBoss business process management tool: https://www.jbpm.org/
            - YAWL business process management tool https://www.jbpm.org/

    3. Description of the robots, devices, sensors, equipment, etc. to be used.
      - Tools
         - Robonomics-js is a simple Javascript library for working with Robonomics Network. - https://wiki.robonomics.network/docs/en/robonomics-js/
         - Solidity, Angular, Python, Nodejs, Web3, Ethereum and Polkadot Ipfs version 0.34.0 - IPFS is a distributed system for storing and accessing files, websites, applications, and data".
         - Web3 version 1.2.4
         - Robonomics Network agent - Usually it's represented as a ROS package and it may connect (but not necessarily) a real cyber-physical system to the Robonomics Network.
         - LIGHTHOUSE - A lighthouse is an autonomous workflow that allows us to distribute the running time of providers that serve a single broadcast channel.
         - SENSORS CONNECTIVITY - https://wiki.robonomics.network/docs/en/sensors-connectivity/
         - DIGITAL TWINS - https://wiki.robonomics.network/docs/en/digital-twins/, https://dapp.robonomics.network/#/iot/twins, https://www.youtube.com/watch?v=nRVG4CQY7_4
       - Short Description on technologies
            Robonomics ->  connect your robot as a service -> for end users or digital markets.
            It has support - > Web3 technologies that implement the exchange of technical and economic information between ->  humans and machines
            Robonomics -> linked Ethereum and Polkadot -> with the Robot operating system (ROS)
            ROS (stands for Robot Operating System) is a large set of packages for robotics needs. At the same time, it provides a convenient way of building a package for a robot
            ROS comes with publisher/subscriber architecture that allows dividing a complex system into a set of nodes that can communicate via defined messages. 
            The Robonomics Network supports ROS and it means any ROS-enabled robot could be easily connected to the network.
            Robonomics aims to provide a way to connect different kinds of cyber-physical systems (CPSs) for machine-to-machine or human-to-machine communication.
            A CPS could be one or a number of sensors, a mobile robot, an industrial one, or a whole factory. Robonomics makes it possible to build a robot economy and let those CPS exchange transactions with a task and money at the same time.
            The interaction between Robot and Robonomics is throught Ronomics Io - https://wiki.robonomics.network/docs/en/rio-overview/
            Robot Operating System, a middleware suite that allows us to conveniently deploy software for robotic devices. 
            The three main abstractions in the ROS environment are nodes, topics, and messages. A node is a process / program that performs a certain task and communicates with other nodes through topics. A node subscribes to a topic, waiting for messages, or publishes its own messages to them. In this implementation, the different-type components of the robotic system are able to interact with each other at the same level.
            With business process/ workflow management system, the redesigned logistic process of the high value products can be simulated and ownership and authenticity of high value products can be verified instantly in real-time.

    4. Known studies, methods, algorithms that you want to use.
      - Digital twin standards: https://www.sciencedirect.com/science/article/pii/S2212827116313129
    5. Previous projects, Proof-of-Concept, MVP that you based this project on.
          
2. In the case of the prior development, any details about it: publications, repositories, articles, etc.
  - Blockchain based certificate verification system: Implementation code on Github: https://github.com/Dynamic-Flakes/E-Cert-Dapp
	- Blockchain based KYC system: Whitepaper: https://scholar.google.com/citations?view_op=view_citation&hl=en&user=0fKaTa8AAAAJ&cstart=20&pagesize=80&citation_for_view=0fKaTa8AAAAJ:zYLM7Y9cAGgC

3. your project uses Robonomics Network.
    High valued products in a  Simulated logistics supply chain will be encoded with RFID/IoT sensors that contain digital twin information about the product. Each manufacturer of such a product will maintain a Robonomics account to read and store the digital twin information of the products on the Robonomics/ Ethereum blockchain. As the encoded product moves along the supply chain logistic, each product can be verified by scanning RFID data and verifying their authenticity on the Robonomics/ Ethereum platform. The ownership of the digital asset (digital twin) can be transferred as the high value product moves along the supply chain using smart contracts. The current ownership of the product can be confirmed instantly by checking the last account associated with the digital twin on the blockchain.
    Figure 1 shows a high level description of the digital twin manager for high valued products. The first layer shows the process part that outlines logistic activities in the supply chain of high-value products. The second layer shows the main components that enable the creation, verification and tracking of digital twin of high valued products. The three main components include Robonomics platform account manager, digital twin web interface and ethereum blockchain component.
    The robonomics platform account enables the creation of accounts and management of digital assets linked to the accounts. This component enables interaction of physical objects (attached with IoT/Rfid sensors) with their digital twin representatives on the blockchain.
    The ethereum blockchain component enables the storage of digital assets on the blockchain and also provides smart contract interface for verifying the authenticity of objects and  transferring their ownership to different account as the product moves along the supply chain.
    The web interface provides the possibility for the participants in the supply chain to track ownership and verify authenticity of high value products as they move along the supply chain. The web interface interacts directly with the smart contract component of the blockchain in verifying and tracking high value products.


---

## 4. Team :busts_in_silhouette:

> In this section, you can describe your team and indicate your scientific and professional experience (scientific papers, blog posts, PhD thesis, GitHub repositories, links to projects’ sites and videos and any other information).

* **Organization** (if applicable):
      **organization 1: Dymaxion OÜ
        * Legal address of organization. Liiva tn 32, 11615, Tallinn, Harju maakond, Registration code 12954070
        * Contact person:
          * Full name of the contact person representing the team. Alexander Norta
          * Position at the organisation (if applicable). CEO and owner of Dymaxion OÜ
          * Main contact address (email, Telegram or Element Riot). 
          * Email: alex.norta.phd@ieee.org
          * Telegram: @alexbafana
          * Role in the project (if applicable). Principal investigator
          * Experience (if applicable). Associate Professor, PhD, IEEE Blockchain Estonia lead
          * Publications: Google Scholar Profile: https://scholar.google.com/citations?hl=en&user=1_wDRvsAAAAJ

     **Organization 2: University of Applied Sciences Upper Austria, Steyr (FHOOE- Steyr)
        * Address: FH Upper Austria Campus Steyr, Fachhochschule Steyr Altbau, Wehrgrabengasse, Steyr, Steyr, Oberosterreich
        * Team person #2:
          * Full name: Chibuzor Udokwu
          * Role in the project: Blockchain Engineer and system requirement specialist
          * Experience: PhD researcher in developing custom framework for building blockchain applications and Researcher in building data systems for retail supply chains (Organization- FHOOE)
          * Publications: Google Scholar Profile: https://scholar.google.com/citations?hl=en&user=0fKaTa8AAAAJ
        * Team person #3:
          * Full name: Patrick Brandtner
          * Role in the project: overseeing the process specifications in high-value supply chains 
          * Experience: Professor of Supply Chain and Logistic Retail group lead FHOOE
          * Publications: Google Scholar Profile: https://scholar.google.com/citations?user=c-vtRgcAAAAJ&hl=en&oi=ao


---

## 5. Expected results :package:
> In this section, you are invited to describe what specific results your team is planning to produce by the end of the project. It can be: setup, launch and test guides, theory and calculations, reports, repositories, ROS modules, articles, videos, blog posts, etc. (max. one page long).
    - Process description of high-value supply chains
    - Blockchain and IOT integrated process specification of high-value supply chains
    - Implemented interfaces for interaction with the Blockchain and IOT integrated process specification of high-value supply chains
    - Simulation of the Blockchain and IOT integrated process specification of high-value supply chains
    - Paper publication of the results from the project

---

## 6. Project Schedule :date:

> Here you can provide the table of expected tasks with a short description of every task. This list is not strict, and you are free to adhere to a different schedule during the grant implementation. First of all, the list is needed so that you can orientate yourself on the upcoming project. Secondly, such a list will demonstrate to us that you have a clear understanding of the goals and objectives.



ID  |     Task Label            | Task Description                                                                            | Responsibility     |Start date| end date
---:|:-------------------------:|:-------------------------------------------------------------------------------------------:|:------------------:||:--------|---------:|
1   |     Preparation           |Time needed to prepare for the project and set up the required resources for case development| FHOOE/ Dymaxion OÜ | 01.11.21 | 30.11.21
2   | Case Development          |Development of the actual case of high-value supply chain to show counterfeiting problems    | FHOOE              | 01.12.21 | 30.01.22
3   |Implementation & simulation|Development of the blockchain interfaces & simulation of the IoT integrated business process |Dymaxion OÜ/        | 01.02.22 |30.05.22
                                                                                                                               Consulting partners 
4   |Paper publication          | Paper publication based on the results generated from the project                           |FHOOE/ Dymaxion OÜ  | 01.05.22 |30.06.22

---


## 7. Project Budget :moneybag:

> Here you can specify how you plan to use the Robonomics grant. Again, this list is not strict and is intended to help you and us better understand the project.

                                Task  | Expense Item | Calculation (usd) | No of persons |  month | overhead cost (usd)  | Total cost | 
-------------------------------------:|:------------:|:-----------------:|:-------------:|:------:|:--------------------:|:----------:|
Task1 : Preparation                  | Month: Novemeber  |cost $0
------------------------------------- ------------------:|:--------------:|:------------:|:------:|:--------------------:|:----------:|:-------------------------------
            -Task2 : Case Development | Conduct interviews in companies that develop high value products to develop the business process of the AS-IS | $2,500 |1 masters student |1: December
                                      |Perform AS-IS analyses to identify factors and tasks that potentially causes product counterfeiting in the supply chain|$2,500|1 masters student|2: January
                                      |Development of TO-BE process by redesigning the process model and integrate IOT or RFID sensors that enables storage and verification of digital twin of products on blockchain |2: January

                                       overhead cost: administration and logistics support( $5,000)
                                       Total cost: $10,000
------------------------------------:|:----------------------------------------------------------------------------:|:------:|:---------------------:|:---------------
Task3: Implementation and simulation | Development of digital twin of products and storing on ROBONOMICS blockchain | $5,000 | 2 software engineers |3: February
                                      |Verification interface for digital twin products stored on ROBONOMICS blockchain|$5,000| 2 software engineers |4: March
                                      |Integration of developed interfaces with TO-BE BPMN process tasks             |$5,000  | 2 software engineers |5: April
                                      |Simulation of blockchain integrated process and collection of simulation results|$5,000| 2 software engineers |6: May

                                       overhead: administratio, software & hardware purchases ($10,000)
                                       total cost: $30,000
------------------------------------:|:--------------------------------------------------------:|:-------:|:------------:|:-------------------
Task4: Paper publication             | Collection and preparation of AS-IS Process and analyses | 0$      | 1 researcher | 5: April

                                     | Collection  and preparation of TO-BE process             | 0$      | 1 researcher | 5: April
                                     | Collection  and preparation of simulation results        | 0$      | 1 researcher | 6: May
                                     | Template preparation and Paper(s) writing                | 5,000   |3 researchers | 6: May
                                     
                                     overhead: conference fees and participation logistics($3,000)
                                               Network fees for onchain related simulations($2000) 
                                     total cost: 10,000                                     
-----------------------------------:|:---------------------------------------------------------:|:-------:|:------------:|:-----------------
                                     Gross total: $50,000

---

## 8. Additional Information :information_source: 

> Please indicate here the source (our site, ads, social network, colleagues advice, etc.) from which you found out about the Robonomics Grant Program.

> If you chose a cryptocurrency for funding other than XRT, please describe the reasons for your choice here.

> Also, feel free to share any other relevant information on the project. 

References
1. Stevenson, Mark, and Jerry Busby. "An exploratory analysis of counterfeiting strategies: Towards counterfeit-resilient supply chains." International Journal of Operations & Production Management (2015).
2.  Cho, Soo-Haeng, Xin Fang, and Sridhar Tayur. "Combating strategic counterfeiters in licit and illicit supply chains." Manufacturing & Service Operations Management 17.3 (2015): 273-289.
3. Mandolla, Claudio, et al. "Building a digital twin for additive manufacturing through the exploitation of blockchain: A case analysis of the aircraft industry." Computers in Industry 109 (2019): 134-152.
4. Guo, Daqiang, et al. "A framework for personalized production based on digital twin, blockchain and additive manufacturing in the context of Industry 4.0." 2020 IEEE 16th International Conference on Automation Science and Engineering (CASE). IEEE, 2020.


