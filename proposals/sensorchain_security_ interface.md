# Robonomics Grant Proposal

## 1. Administrative Information :white_check_mark:

* **Project Name:** Sensorchain Security Interface
* **Project Summary:** The project aims to transfer the concept of object identities basing on the sensorchain for securing authenticity and integrity among stationary and mobile robots. To provide a proof of concept, autonomous and distributed swarm robots will perform simple tasks and detect attackers.
* **Total Estimated Duration:** 9 months
* **Expected Project Start / End Dates:** 01/01/2022 - 30/09/2022
* **Requested Funding:** 49050 USD in ETH or DAI
* **Payment Address:** 0xbFee06E2020716cb9a719458c1A2af83231f336b

---

## 2. Project Overview :bookmark_tabs:

1. What are the problems that the project is trying to solve?

Data integrity is always an important and crucial issue in automation. It is one of the three the major attack types „destruction”, „stealing” and „manipulation”. While integrity for stored data in a distributed system can be maintained by applying blockchain technology, this projects targets at data security during communication in distributed low performance (wireless) IoT networks - here especially for robots. (Voskobojnikov A. et al. (2021) Balancing Security: A Moving Target. In: Lemieux  V.L., Feng C. (eds) Building Decentralized Trust. Springer, Cham.  https://doi.org/10.1007/978-3-030-54414-0_4)

As a key concept, the integrity of the communication will be mapped to their recognized identities by behaviour based identification. This reduces every participant in the network to a detectable and verifiable set of attributes which represent its identity. During communication the identity will be permanently monitored regarding relevant changes with measures to be taken accordingly. (Kai Hendrik Wöhnert et al.: Secure Cyber-Physical Object Identification in Industrial IoT-Systems, in: Procedia Manufacturing, Volume 51, 2020, pp.1221-1228, ISSN 2351-9789,
https://doi.org/10.1016/j.promfg.2020.10.171)

In the proposed project we will apply our distributed communication method with this identity verification called „sensorchain” on autonomous and distributed robots. ([Skwarek, V.](https://www.emerald.com/insight/search?q=Volker Skwarek) (2017), "Blockchains as security-enabler for industrial IoT-applications", *[Asia Pacific Journal of Innovation and Entrepreneurship](https://www.emerald.com/insight/publication/issn/2398-7812)*, Vol. 11 No. 3, pp. 301-311. [https://doi.org/10.1108/APJIE-12-2017-035 ](https://doi.org/10.1108/APJIE-12-2017-035))

For mobile and stationary robots we will interface to our technology by the identity concept „proof-of-location (PoL)”, where an identity is mapped to its (verifiable) position as the highest relevance. The PoL uses a trust mechanism consisting of a combination of redundant localization of sensor nodes and consensus generation within a WSN. (S. Kaven et al.: "Authentication by RSSI-Position Based Localization in a LoRa LPWAN," *2020 6th IEEE Congress on Information Science and Technology (CiSt)*, 2020, pp. 448-454, doi: 10.1109/CiSt49399.2021.9357283)

The proof of location is already used in two research projects, and corresponding proofs of concept have been provided. However, this only applies to stationary networks, i.e. networks in which the network nodes have a fixed position and usually do not move relative to the other nodes. A proof of concept for a dynamic network with moving nodes has not been provided yet. The goal of the project is to provide a proof of concept for such moving nodes, to apply the robonomics library and to interface it to the concept of the identity based integrity detection. 

As a use case for this project application, an autonomous warehouse in which robots transport goods independently is proposed. Malicious robots will be attacking the system with faulty behaviour and wrong messages. PoL makes it possible to identify and isolate the attacker.

2. Why do you want Robonomics Network to be used for solving those problems?

Robonomics provides a very good platform and use case to interface with in terms of security sensitive appliations - here: autonomous market places for load sharing and distribution within industrie4.0. As industrie4.0 is an important economic area for sustainable ressource usage, it has to work safely and security. With as interface to the PoL principle such as developed within our research group,  we provide this required security for data integrity, authenticity and accountability.

3. What are expected main result of the project?

- A secure communication between robots of the robonomics platform will be provided by interfacing to the sensorchain.
- The system will be optimized to mobile robots with wireless communication.
- Identity theft and data integrity towards the robots are the core aims of the development.
- As a proof-of-concept multiple mobile robots will be used to autonomously fill a shelf storage without central coordinating instance. Malicious robots try to fill wrong spaces or prevent other robots from filling the shelf by intruding and confusing the communication. As a security target, these robots shall be excluded and blacklisted from communication.

4. Do you plan to exploit the result in the future (academic, commercial)?

As our research has its foundations within security and the basic rule for security is "security by design", we need applications as use cases. Most prominent use cases for security research are either those which require secure infrastructure by regulation or due the economic impact. Industrie4.0 is very vulnerable to attacks due to its high degree of automation - a reason why about 1/3  of our research applications are within this area. 

This research project provides us an excellent infrastructure for decentralized automation among robots which we will reuse for further developments of our security protocols within upcoming public and private funded projects as far as possible. Additionally, the results will be published on conferences and in journals.

5. What is your personal motivation to implement this project?

We see a huge potential for both sides if distributed security and industrie4.0 concepts merge. As we have many security use cases for industrial automation in our project, the impact could be of advantage for both sides.

6. Are there any other projects similar to yours? and 7. In what way is your project different from the existing ones?

* One other known project is the FOAM project (https://foam.space/), which provides a tool to enable a crowdsourced map and decentralized location services. The FOAM project also uses the term *proof of location* with another meaning: They proof a location of mobile devices - e.g. cars - by cross referencing to multiple GPS base stations. Our proof-of-location is a security measure in terms of behaviour-based identities. A PoL in regards to our understanding is one of many identity attributes which are not claimed but discovered (= proven) by other participants and observers.

* [Secure and secret cooperation in robot swarms](https://robotics.sciencemag.org/content/6/56/eabf1538): That project focuses on secure and verifiable order execution whereas our application works on a more abstract security layer. We proof, that the robot the system talks to is really the robot which it is assumed  to be.

## 3. Technical Details :pager:


1. An overview of the technology stack to be used. This may include items such as: 
    1. Links to documentation of software, components, protocols, architecture, data models, API specifications, etc. that you based your project on.
        * rviz (http://wiki.ros.org/rviz)
    2. Robot Operating System packages to be used (please, indicate them as a separate item).
        * ROS Melodic (https://wiki.ros.org/melodic)
        * NXT-ROS (http://wiki.ros.org/nxt)
    3. Description of the robots, devices, sensors, equipment, etc. to be used.
        *  The LEGO NXT robots will be used to implement the project. 
    4. Known studies, methods, algorithms that you want to use.
        * 
    5. Previous projects, Proof-of-Concept, MVP that you based this project on.
        * The proof of location for static networks has already been used in two research projects for different use cases, and a proof of concept has been archived. In the WaterGridSense4.0 (https://www.watergridsense40.de/) project, proof of location was used to secure communication between sensors for monitoring street inlets. The water utilities could then use the data collected in this way to determine maintenance intervals of the street inlets and thus prevent flooded street sections during heavy rain. In the second project, HanseBloc (https://www.hamburg-logistik.net/hansebloc/), the proof of location was successfully used to ensure the correctness of the temperature values of networked refrigerated containers for freight delivery. 
2. In the case of the prior development, any details about it: publications, repositories, articles, etc.
    * The concept of the Proof of location has already been tested for static sensor networks and described in the following publications:
        - Bornholdt, Lorenz, Julian Reher, and Volker Skwarek. "Proof-of-Location: A method for securing sensor-data-communication in a Byzantine fault tolerant way." Mobile Communication-Technologies and Applications; 24. ITG-Symposium. VDE, 2019.
        - Kaven, Sascha, Lorenz Bornholdt, and Volker Skwarek. "Authentication by RSSI-Position Based Localization in a LoRa LPWAN." 2020 6th IEEE Congress on Information Science and Technology (CiSt). IEEE, 2021.
        - Tschirner, Simon, Katharina Zeuch, Sascha Kaven, Lorenz Bornholdt, and Volker Skwarek. "Security in Distributed Systems by VerifiableLocation-Based Identities" Transactions on Computational Science and Computational Intelligence. Springer, 2021.
3. Details of how your project uses Robonomics Network.

    Within the project, the Robonomics platform will be used in two ways. On the one hand, the robots will be instructed via the platform. For this purpose, a small DApp is to be developed that can be used to tell the robots which letter they are to reproduce. On the other hand, the platform will be used to store the measurements and position information shared by the robots and information about possible attackers in an unalterable form and make it available to the users.
---

## 4. Team :busts_in_silhouette:

* **Contact person**:
    * Sascha Kaven, Research Assistant, sascha.kaven@haw-hamburg.de
    
* **Team person #1**:

    * Sascha Kaven, Developer
    * 3 years of experience in trusted communication and communication protocols  
    * Publications:
      - Kaven, Sascha, Lorenz Bornholdt, and Volker Skwarek. "Authentication by RSSI-Position Based Localization in a LoRa LPWAN." 2020 6th IEEE Congress on Information Science and Technology (CiSt). IEEE, 2021.
      - Tschirner, Simon, Katharina Zeuch, Sascha Kaven, Lorenz Bornholdt, and Volker Skwarek. "Security in Distributed Systems by VerifiableLocation-Based Identities" Transactions on Computational Science and Computational Intelligence. Springer, 2021.
      - Bornholdt, Lorenz, Sascha Kaven and Volker Skwarek. "Adaptive procedure for indoor localization using LoRa devices" International Conference on Indoor Positioning and Indoor Navigation. IEEE, 2021.

* **Team person #2**:
  
    * Prof. Dr. Ing. Volker Skwarek, scientist, system architect, embedded system protocol developer
    
    * Experience: 
    
      * academia: 11 years. 7 years as a professor, 4 years as a researcher.
      * automotive industry: hard- and software developer for sensor systems, head of electronics development , global head of research, 11 years
      * others (energy, medical): technical marketing, head of technology, 6 years
    
    * Publications (more than 50 including proceedings, journals and books). Most relevant within the last 3 years:
    
      * Voskobojnikov A., Skwarek V., Mashatan A., Matsuo S., Rowell C.,  Weingärtner T. (2021) Balancing Security: A Moving Target. In: Lemieux  V.L., Feng C. (eds) Building Decentralized Trust. Springer, Cham.  https://doi.org/10.1007/978-3-030-54414-0_4 
      * Kai Hendrik Wöhnert, Sven-Jannik Wöhnert, Tobias Thiel, Rüdiger Weißbach, Volker Skwarek: Secure Cyber-Physical Object Identification. In: Industrial IoT-Systems, Procedia Manufacturing, Volume 51, 2020, Pages 1221-1228, ISSN 2351-9789, https://doi.org/10.1016/j.promfg.2020.10.171.
        L. Bornholdt, J. Reher and V. Skwarek, "Proof-of-Location: A method for  securing sensor-data-communication in a Byzantine fault tolerant way," *Mobile Communication - Technologies and Applications; 24. ITG-Symposium*, 2019, pp. 1-6.
      

---

## 5. Expected results :package:


The goal is to use swarm robots to provide a proof of concept of the proof of location in dynamic sensor networks. For this purpose, it shall be shown that the network can identify and isolate an attacker in the network. The test setup will be recorded by video and published. Furthermore, the program code for the interface between the Robonomics platform and the Proof of Location will be made available to the general public in a public repository. For the project's scientific evaluation, an open access publication in a thematically appropriate journal or conference will be published to make the results available to the community.

---

## 6. Project Schedule :date:


| No. | Task description | Start/end dates |
|:---:|:----------------:|:---------------:|
| 1 |        requirements analysis       |       01/01/2022 - 31/01/2022       |
| 2 |        Setup of the robots       |       01/02/2022 -  28/02/2022      |
| 3 |        Design of POL for dynamic sensor networks      |      01/02/2022 - 30/04/2022       |
| 4 |        Implementation      |      01/05/2022 - 30/06/2022       |
| 5 |        Testing: Implementation and evaluation of the targeted test setups.      |      01/07/2022 - 31/08/2022       |
| 6 |        Documentation: writing open access publication, creating and editing the demo video.      |      01/09/2022 - 30/09/2022       |

---

## 7. Project Budget :moneybag:


| No. | Expense Item |   Calculation   | Total cost |
|:---:|:------------:|----------------:|-----------:|
| 1 |     LEGO NXT Robot      |       7x500 USD       |     3500 USD    |
| 2 |     personnel costs, 9 months 50% researcher     |       9x 3350 USD      |     30150 USD    |
| 3 |     Tax      |       10000 USD      |     10000 USD    |
| 4 |   Network transactions (300 XRT)   |   300 XRT x 18 USD   |   5400 USD
|     |              |    **TOTAL:**   |   49050 USD         |

---

## 8. Additional Information :information_source:

> Please indicate here the source (our site, ads, social network, colleagues advice, etc.) from which you found out about the Robonomics Grant Program.

> Also, feel free to share any other relevant information on the project. 