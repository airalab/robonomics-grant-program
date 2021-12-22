# Robonomics Grant Proposal

## 1. Administrative Information :white_check_mark:

* **Project Name:** Location based identities in industry 4.0 production
* **Organisation Name:** Hamburg University of Applied Sciences (HAW Hamburg)
* **Project Summary:** The project aims to transfer the concept of object identities based on the sensorchain for securing authenticity and integrity during the production process in an industry 4.0 environment. To provide a proof of concept, an industry 4.0 training factory will be enhanced with RFID tags to localize the components during the manufacturing process.
* **Total Estimated Duration:** 9 months
* **Expected Project Start / End Dates:** 01/01/2022 - 30/09/2022
* **Requested Funding:** 49990 USD in DAI
* **Payment Address:** 0xbFee06E2020716cb9a719458c1A2af83231f336b

---

## 2. Project Overview :bookmark_tabs:

1. What are the problems that the project is trying to solve?

Data integrity is always an important and crucial issue in automation. While integrity for stored data in a distributed system can be maintained by applying blockchain technology, this projects aims to increase data security during communication in distributed low performance (wireless) IoT networks by adding the object's location information as part of its identity. (Voskobojnikov A. et al. (2021) Balancing Security: A Moving Target. In: Lemieux  V.L., Feng C. (eds) Building Decentralized Trust. Springer, Cham.  https://doi.org/10.1007/978-3-030-54414-0_4)

As a key concept, the integrity of the communication will be achieved by mapping the communication to their recognized identities by behaviour based identification. This reduces every participant in the network to a detectable and verifiable set of attributes which represent its identity. During communication the identity will be permanently monitored regarding relevant changes with measures to be taken accordingly. (Kai Hendrik Wöhnert et al.: Secure Cyber-Physical Object Identification in Industrial IoT-Systems, in: Procedia Manufacturing, Volume 51, 2020, pp.1221-1228, ISSN 2351-9789,
https://doi.org/10.1016/j.promfg.2020.10.171)

In the proposed project we will apply our distributed communication method with this identity verification called „sensorchain” on the different parts of the production chain in the industry 4.0 training facility. ([Skwarek, V.](https://www.emerald.com/insight/search?q=Volker Skwarek) (2017), "Blockchains as security-enabler for industrial IoT-applications", *[Asia Pacific Journal of Innovation and Entrepreneurship](https://www.emerald.com/insight/publication/issn/2398-7812)*, Vol. 11 No. 3, pp. 301-311. [https://doi.org/10.1108/APJIE-12-2017-035 ](https://doi.org/10.1108/APJIE-12-2017-035))

To achieve these goals, we will build an RFID network surrounding the simulation facility as well as add passive RFID tags to each production component. To secure the correctness of the position used for the object's identity, we will implement technology based on our identity concept "proof-of-location (PoL)", where an identity is mapped to its (verifiable) position as the highest relevance. The PoL uses a trust mechanism consisting of a combination of redundant localization of sensor nodes and consensus generation within the WSN. (S. Kaven et al.: "Authentication by RSSI-Position Based Localization in a LoRa LPWAN," *2020 6th IEEE Congress on Information Science and Technology (CiSt)*, 2020, pp. 448-454, doi: 10.1109/CiSt49399.2021.9357283)

The proof of location is already used in two research projects, and corresponding proofs of concept have been provided. However, this only applies to stationary networks, i.e. networks in which the network nodes have a fixed position and usually do not move relative to the other nodes. A proof of concept for a dynamic network with moving nodes has not been provided yet. The goal of the project is to provide a proof of concept for such moving nodes applying the robonomics library. 

As a use case for this project application, a smart factory is proposed where each component will be fitted with an object identity containing its position, which is being monitored by their RFID tags. To simulate an attack on the object's identity, the object's position can either be manually changed or a corrupted sensor can try to change the object's identity in an illegitimate fashion. PoL makes it possible to identify and isolate the attacker.

2. Why do you want Robonomics Network to be used for solving those problems?

The Robonomics platform offers easy ways of implementing digital twins on a blockchain based system, as well as providing the opportunity to dynamically supply and receive information relevant to the object's identities. As industry 4.0 is an important economic area for sustainable ressource usage, it has to work safely and securely. By using the aforementioned digital twin system combined with the PoL principle developed by our research group, the authenticity of the object's identity can be secured during the whole production process.

3. What are expected main result of the project?

We aim to have a working platform to demonstrate the PoL for securing object's identities as described above. To achieve this goal, we aim to build a RFID network covering the training factory to monitor the object's location in every production step, which is then reproduced on the digital twin of the objects. Furthermore, manipulations of the object's identities will be recognised and reported to the network.

4. Do you plan to exploit the result in the future (academic, commercial)?

As our research has its foundations within security and the basic rule for security is "security by design", we need applications as use cases. Most prominent use cases for security research are either those which require secure infrastructure by regulation or due to the economic impact. Industry 4.0 is very vulnerable to attacks due to its high degree of automation - a reason why about 1/3  of our research applications are within this area. 

This research project provides us with an excellent infrastructure which we will reuse for further developments of our security protocols within upcoming public and private funded projects as far as possible. Additionally, the results will be published on conferences and in journals.

5. What is your personal motivation to implement this project?

We see a huge potential for both sides if distributed security and industry 4.0 concepts merge. As we have many security use cases for industrial automation in our project, the impact could be of advantage for both sides.

6. Are there any other projects similar to yours? and 7. In what way is your project different from the existing ones?

* One other known project is the FOAM project (https://foam.space/), which provides a tool to enable a crowdsourced map and decentralized location services. The FOAM project also uses the term *proof of location* with another meaning: They proof a location of mobile devices - e.g. cars - by cross referencing to multiple GPS base stations. Our proof-of-location is a security measure in terms of behaviour-based identities. A PoL in regards to our understanding is one of many identity attributes which are not claimed but discovered (= proven) by other participants and observers.

* [Secure and secret cooperation in robot swarms](https://robotics.sciencemag.org/content/6/56/eabf1538): That project focuses on secure and verifiable order execution whereas our application works on a more abstract security layer. We proof, that the robot the system talks to is really the robot which it is assumed  to be.

## 3. Technical Details :pager:

1. Details of how your project uses Robonomics Network.
    1. An overview of how you use the Robonomics technology stack in the development of your project.

    Within the project, the Robonomics platform will be used to create and store the digital twins of the production components and the sensor network. Additionally, the Robonomics platform will be used to supply the training factory with fabrication instructions. For this purpose, a small DApp is to be developed that can be used to tell the factory which production steps are to be conducted with the according components. Furthermore, the platform will be used to store the position information shared by the sensor network and information about possible attackers in an unalterable form, making it available to the users.

    2. Description of the planned load on the Robonomics network: **indicate the period (3-9 months)** and briefly describe the intended purpose of the transactions.
    
    Within the project, traffic on the Robonomics platform will be generated during the last five months (may-september). Most of the traffic is generated during the testing phase in July and August. The traffic consists of the creation and communication with the digital twins concerning its location and manufacturing status. Moreover, traffic is generated via the manufacturing instructions sent to the training factory.

2. An overview of the technology stack to be used (except Robonomics). This may include items such as: 
    1. Links to documentation of software, components, protocols, architecture, data models, API specifications, etc. that you based your project on.
        * Software stack fischertechnik TXT-Controller (https://github.com/fischertechnik/FT-TXT)
        * Demo application for the fischertechnik Training Factory (https://github.com/fischertechnik/txt_training_factory)
        * Manual for using the Training Factory (https://www.fischertechnik.de/en/service/elearning/teaching/lernfabrik-4)
    2. Robot Operating System packages to be used (please, indicate them as a separate item).
    3. Description of the robots, devices, sensors, equipment, etc. to be used.
        * fischertechnik Training Factory Industry 4.0 (https://www.fischertechnik.de/en/products/simulating/training-models/551584-sim-training-factory-industry-4-0-9v). 
        * Invengo XC-RF850 RFID Reader (https://channel.invengo.com/rfid-product-line/readers-antennas/rain-rfid-uhf-readers/xc-rf850-integrated-reader/)
    4. Known studies, methods, algorithms that you want to use.
        * RFID positioning:
            * Zhang, Yimin, Moeness G. Amin, and Shashank Kaushik. "Localization and tracking of passive RFID tags based on direction estimation." International Journal of Antennas and    Propagation 2007 (2007).
            * Sasikala, M., J. Athena, and A. Sheela Rini. "Received Signal Strength based Indoor Positioning with RFID." 2021 IEEE International Conference on RFID Technology and Applications (RFID-TA). IEEE, 2021.
    5. Previous projects, Proof-of-Concept, MVP that you based this project on.
        * The proof of location for static networks has already been used in two research projects for different use cases, and a proof of concept has been archived. In the WaterGridSense4.0 (https://www.watergridsense40.de/) project, proof of location was used to secure communication between sensors for monitoring street inlets. The water utilities could then use the data collected in this way to determine maintenance intervals of the street inlets and thus prevent flooded street sections during heavy rain. In the second project, HanseBloc (https://www.hamburg-logistik.net/hansebloc/), the proof of location was successfully used to ensure the correctness of the temperature values of networked refrigerated containers for freight delivery. 
2. In the case of the prior development, any details about it: publications, repositories, articles, etc.
    * The concept of the Proof of location has already been tested for static sensor networks and described in the following publications:
        - Bornholdt, Lorenz, Julian Reher, and Volker Skwarek. "Proof-of-Location: A method for securing sensor-data-communication in a Byzantine fault tolerant way." Mobile Communication-Technologies and Applications; 24. ITG-Symposium. VDE, 2019.
        - Kaven, Sascha, Lorenz Bornholdt, and Volker Skwarek. "Authentication by RSSI-Position Based Localization in a LoRa LPWAN." 2020 6th IEEE Congress on Information Science and Technology (CiSt). IEEE, 2021.
        - Tschirner, Simon, Katharina Zeuch, Sascha Kaven, Lorenz Bornholdt, and Volker Skwarek. "Security in Distributed Systems by VerifiableLocation-Based Identities" Transactions on Computational Science and Computational Intelligence. Springer, 2021.
        - Bornholdt, Lorenz, Sascha Kaven, Volker Skwarek. "Adaptive procedure for indoor localization usingLoRa devices" International Conference on Indoor Positioning and Indoor Navigation (IPIN). IEEE, 2021.



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

    * Moritz Volkmann, Developer
    * Experience in programming (Python, C++, Java, etc.) and hardware prototyping
    
    
      
* **Team person #3**:
  
    * Prof. Dr. Ing. Volker Skwarek, scientist, system architect, embedded system protocol developer
    
    * Experience: 
    
      * academia: 11 years. 7 years as a professor, 4 years as a researcher.
      * automotive industry: hard- and software developer for sensor systems, head of electronics development , global head of research, 11 years
      * others (energy, medical): technical marketing, head of technology, 6 years
    
    * Publications (more than 50 including proceedings, journals and books). Most relevant within the last 3 years:
    
      * Voskobojnikov A., Skwarek V., Mashatan A., Matsuo S., Rowell C.,  Weingärtner T. (2021) Balancing Security: A Moving Target. In: Lemieux  V.L., Feng C. (eds) Building Decentralized Trust. Springer, Cham.  https://doi.org/10.1007/978-3-030-54414-0_4 
      * Kai Hendrik Wöhnert, Sven-Jannik Wöhnert, Tobias Thiel, Rüdiger Weißbach, Volker Skwarek: Secure Cyber-Physical Object Identification. In: Industrial IoT-Systems, Procedia Manufacturing, Volume 51, 2020, Pages 1221-1228, ISSN 2351-9789, https://doi.org/10.1016/j.promfg.2020.10.171.
        L. Bornholdt, J. Reher and V. Skwarek, "Proof-of-Location: A method for  securing sensor-data-communication in a Byzantine fault tolerant way," *Mobile Communication - Technologies and Applications; 24. ITG-Symposium*, 2019, pp. 1-6.

* **Auxiliary Team**:

    * Our research team consists of 12 researchers in the area of secure communication and object identities and will be included in the project, although not explicitly mentioned as team members.

---

## 5. Expected results :package:


The goal is to use the sensor network in the training factory to provide a proof of concept of the proof of location in dynamic sensor networks. For this purpose, it shall be shown that the network can identify and isolate an attacker in the network. The test setup will be recorded by video and published. Furthermore, the program code for the interface between the Robonomics platform and the Proof of Location will be made available to the general public in a public repository. For the project's scientific evaluation, an open access publication in a thematically appropriate journal or conference will be published to make the results available to the community.

---

## 6. Project Schedule :date:


| No. | Task description | Start/end dates |
|:---:|:----------------:|:---------------:|
| 1 |        Requirements analysis       |       01/01/2022 - 31/01/2022       |
| 2 |        Setup of the Industry 4.0 training factory and implementation of necessary adaptations.       |       01/02/2022 -  28/02/2022      |
| 3 |        Design of POL for dynamic sensor networks      |      01/02/2022 - 30/04/2022       |
| 4 |        Implementation of the concept and creation of digital twins      |      01/05/2022 - 30/06/2022       |
| 5 |        Testing and evaluation of the targeted test setups.      |      01/07/2022 - 31/08/2022       |
| 6 |        Documentation: writing open access publication, creating and editing the demo video.      |      01/09/2022 - 30/09/2022       |

---

## 7. Project Budget :moneybag:


| No. | Expense Item |   Calculation   | Total cost |
|:---:|:------------:|----------------:|-----------:|
| 1 |     Hardware material      |       1000 USD       |     1000 USD    |
| 2 |     personnel costs, 9 months 50% researcher     |       9x 3350 USD      |     30150 USD    |
| 3 |     personnel costs, 4 months 50% research assistant     |       4x 2160 USD      |     8640 USD    |
| 4 |     Tax and administrative costs      |       10000 USD      |     10000 USD    |
| 5 |   Network transactions   |   10 XRT x 20 USD   |   200 USD
|     |              |    **TOTAL:**   |   49990 USD         |

---

## 8. Additional Information :information_source:

1. Please indicate here the source (our site, ads, social network, colleagues advice, etc.) from which you found out about the Robonomics Grant Program.

We learned about the Robonomics Grand Proposal through our contact with Maria Sigutina and Aleksandr Kapitonov.

2. If you chose a cryptocurrency for funding other than XRT, please describe the reasons for your choice here.

As HAW Hamburg is a public institution it is legally not allowed to accept speculative payments for financing or securing salaries or other contractual obligations. Therefore a fiat-backing is required and DAI is needed for the payment.

3. Additional Information:

The already submitted application "Logistics Blockchain Digital Twin" by Alexander Norta, with a project working on the object identity ownership of manufactured goods could bear the opportunity of future synergies and projects for working on secure object identities from the start of production to the end user, which would be an interesting use case for the Robonomics platform as well.