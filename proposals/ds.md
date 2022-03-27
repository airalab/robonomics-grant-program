# Robonomics Grant Proposal

> The Proposal document will contain information about the project you would like to implement using the Robonomics grant. We recommend to provide full and comprehensive information to speed up the proposal review process. Comments in the lines starting with a `>` can be deleted.

> NB: The main cryptocurrency for funding is **Robonomics** token ([XRT](https://www.coingecko.com/en/coins/robonomics-network)). Also, the grant can be provided in **Dai Stablecoin** ([DAI](https://www.coingecko.com/en/coins/dai)) or **Ethereum** tokens ([ETH](https://www.coingecko.com/en/coins/ethereum)), but applicants need to provide a reasoned explanation to different cryptocurrency in Additional Information. For the calculation, we use the exchange rate on the date when you proposal is being approved.

## 1. Administrative Information :white_check_mark:

* **Project Name:** Drone selfie
* **Organization Name:** Not used
* **Project Summary:** Solution for automatic creation of video content including content flying cameras, action cameras and  telemetry data. Transmitting data by wireless via IoT nodes to the video editing platform, followed by providing the results to the user via the Robonimics network.
* **Total Estimated Duration:** 7 months
* **Expected Project Start / End Dates:** 1 April 2022 / 31 October 2022
* **Requested Funding:** 27 950 USD in DAI
* **Payment Address:**  0x92737E96f945c936EF4eCEde83eae75bf52ccD48

---

## 2. Project Overview :bookmark_tabs:


1. What are the problems that the project is trying to solve?
    
We solve the problem of obtaining high-quality personalized video content for visitors of amusement parks in the open air using multiple video sources and quickly obtaining the finished result, this is the best moment after the users receives emotions.
    
2. Why do you want Robonomics Network to be used for solving those problems? 

The Robonomics network provides opportunities for setting up work when each camera or content transfer point provides an autonomous unit that transmits economic and technical data in an agreed form in both directions. As well as the ability to organize the storage of all involved data in a distributed network.

3. What are expected main result of the project?

The main results of the project are a solution with rapid deployment in any new location, which only requires the presence of cameras to capture content and Internet of Things nodes to sort and transfer the necessary content to a cloud video editing server and to the Robonomics platform for storing and transferring all user data.

4. Do you plan to exploit the result in the future (academic, commercial)?

Yes, commercial. The project has already had successful commercial operation at several facilities in Russia and Europe since 2018.

5. What is your personal motivation to implement this project?

Long-term growing profit as a co-founder of the project.

6. Are there any other projects similar to yours? 

Yes, but only for action/cable cam use:
	
	https://actioncam.video
	https://www.actionphotosystems.com
    
7. In what way is your project different from the existing ones?

	a. The possibility of using drones from different manufacturers and automatic data transmission from them.

	b. Availability "out of the box". Rapid deployment to new locations does not require the involvement of qualified engineers.

	c. Providing the result to the user via IPFS network.


## 3. Technical Details :pager:


1. Details of how your project uses Robonomics Network.
    1. An overview of how you use the Robonomics technology stack in the development of your project.
    
    Within the project, the Robonomics platform will be used to create and store the digital twins of the production components. Work on the platform should ensure the constant storage and transfer of user data at the stages: storage user personal data, data ID of user content, storage final user video and hash data, providing user access to final video.

    2. Description of the planned load on the Robonomics network: **indicate the period (3-9 months)** and briefly describe the intended purpose of the transactions.
    
    As part of the project, traffic on the Robonomics platform will be generated during the last six months (July-December). Most of the traffic is generated during the testing phase in July and August. Traffic consists of creating multiple units of products (media packages). Average sum of transactions per month - 950, for all months - 5700.

2. An overview of the rest technology stack to be used (except Robonomics). This may include items such as: 
    1. Links to documentation of software, components, protocols, architecture, data models, API specifications, etc. that you based your project on.
    
	Python3 (3.6+), Docker, Git, Shell Linux, FastAPI, PostgreSQL, Flask, Nginx, FFmpeg, Android mobile app stack (Java, Kotlin, etc)
	
    3. Robot Operating System packages to be used (please, indicate them as a separate item).
    4. Description of the robots, devices, sensors, equipment, etc. to be used. 

	Raspberry Pi 4 Model B, Barcode Scanner Module 1D / 2D, WiFi ASUS AC1300 USB Adapter Model; USB-AC54, Android mobile device

    6. Known studies, methods, algorithms that you want to use.
    7. Previous projects, Proof-of-Concept, MVP that you based this project on.
3. In the case of the prior development, any details about it: publications, repositories, articles, etc.

---

## 4. Team :busts_in_silhouette:

* **Organization** (if applicable):
    * Not used
* **Contact person**:
    * Rostislav Stepanov, CEO at Drone selfie.
    * rost.stepanov@gmail.com.
 
* **Team person №1**:
    * Rostislav Stepanov, CEO.
    * 2018 till now - CEO at Drone selfie.
    * 12 years of head’s experience in a few technical and Internet companies.
* **Team person №2**:
    * Edward Kaminskiy, Developer.
    * 5 years of experience in programming (Python, FastAPI, PostgreSQL, Docker, etc).
* **Team person №3**:
    * Vyacheslav Tievskiy, Developer.
    * 6 years of experience in programming (React, Ext JS, Angular).

---

## 5. Expected results :package:

During 2022 and beyond, the team plans further commercial implementation of the product 

with the following achievements: 
integration with Robonomics platform for operating user personal data, ID for videos
storing and delivery results to users based on IPFS
user's personal account with content management functions

Also for the new partnerships:
ready set of standard IoT devices for operation at new facilities
launch & use instructions

---

## 6. Project Schedule :date:


| No. | Task description | Start/end dates |
|:---:|:----------------:|:---------------:|
| 1 |        Preparing documentation of the existing project code base       |       April 2022       |
| 2 |        Launching the user's personal account       |       May 2022       |
| 3 |        Integrating with Robonomics platform for:  storage personal user information, ID user’s video content       |       June - July 2022     |
| 4 |        Integrating with Robonomics platform for: - IPFS storage for final media content - delivery final media content to user via IPFS       |       August - September 2022       |
| 5 |        Prototyping, production and testing samples IoT devices necessary for product       |       September 2022       |
| 6 |        Manufacture first series of IoT devices for commercial use       |       October 2022       |
| 7 |        Writing documentation for the launch and use product by new partners       |       October 2022       |

---

## 7. Project Budget :moneybag:

> Here you can specify how you plan to use the Robonomics grant. Again, this list is not strict and is intended to help you and us better understand the project.

> You also need to calculate the approximate total costs of transactions to Robonomics Network yourself. Please keep these costs in mind when planning your budget.

| No. |       Expense Item      |   Calculation   |   Total cost    |
|:---:|:-----------------------:|:---------------:|:---------------:|
| 1 |           Hardware material (2 sets for location)           |       2 x 500 USD        |     1000 USD         |
| 2 |           Personnel costs (7 months)           |       9 x 3850 USD       |     26950 USD         |
|     |                         |    **TOTAL:**   |         27950 USD        |

---

## 8. Additional Information :information_source: 

1.Please indicate here the source (our site, ads, social network, colleagues advice, etc.) from which you found out about the Robonomics Grant Program.

   We learned about the Robonomics Grand Proposal through our contact with Sergey Lonshakov

2.If you chose a cryptocurrency for funding other than XRT, please describe the reasons for your choice here.

   Since the Drone selfie company is a tax resident of Russia, by law it is not allowed to accept payments in cryptocurrency to finance or secure wages or other contractual obligations. Therefore, fiat support is required, and DAI is required for payment.

3.Also, feel free to share any other relevant information on the project. 

   Drone selfie project in integration with the Robonomics platform is a great opportunity to demonstrate possibilities in market use. Transferring to a decentralized network is a good step to minimize the risks of a single failure center in access to technology and finance.
