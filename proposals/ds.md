# Robonomics Grant Proposal

> The Proposal document will contain information about the project you would like to implement using the Robonomics grant. We recommend to provide full and comprehensive information to speed up the proposal review process. Comments in the lines starting with a `>` can be deleted.

> NB: The main cryptocurrency for funding is **Robonomics** token ([XRT](https://www.coingecko.com/en/coins/robonomics-network)). Also, the grant can be provided in **Dai Stablecoin** ([DAI](https://www.coingecko.com/en/coins/dai)) or **Ethereum** tokens ([ETH](https://www.coingecko.com/en/coins/ethereum)), but applicants need to provide a reasoned explanation to different cryptocurrency in Additional Information. For the calculation, we use the exchange rate on the date when you proposal is being approved.

## 1. Administrative Information :white_check_mark:

* **Project Name:** Drone selfie
* **Organisation Name:** LLC «DRON SOTRUDNIK»
* **Project Summary:** Solution for automatic creation of video content including content flying cameras, action cameras and  telemetry data. Transmitting data by wireless via IoT nodes to the video editing platform, followed by providing the results to the user via the Robonimics network.
* **Total Estimated Duration:** 9 months
* **Expected Project Start / End Dates:** 1 April 2022 / 31 December 2022
* **Requested Funding:** 36 910 USD in DAI
* **Payment Address:** 0xa7a0332cf5d0a3f20a8031c58eac75f105834006 (Erc20)

---

## 2. Project Overview :bookmark_tabs:

> In this section, you reveal the main idea of the project, how you intend to use the Robonomics Network to bring your idea to life, and your motivation. 

> You might want to put images in the text. To do this, create a subdirectory in the `/src` directory and name it similar to the `.md` file of your proposal. In this subdirectory you can store the images required for your proposal. Use the following construction to place an image in the text:

> `<p align="center">`

> `   <img src="src/project_name_directory/your_image.jpg">`

> `</p>`

> The section should include the following information (max. one A4 page long):

1. What are the problems that the project is trying to solve?
    
We solve the problem of obtaining high-quality personalized video content for visitors of amusement parks in the open air using multiple video sources and quickly obtaining the finished result, this is the best moment after the users receives emotions.
    
3. Why do you want Robonomics Network to be used for solving those problems? 

The Robonomics network provides opportunities for setting up work when each camera or content transfer point provides an autonomous unit that transmits economic and technical data in an agreed form in both directions. As well as the ability to organize the storage of all involved data in a distributed network.

5. What are expected main result of the project?

The main results of the project are a solution with rapid deployment in any new location, which only requires the presence of cameras to capture content and Internet of Things nodes to sort and transfer the necessary content to a cloud video editing server and to the Robonomics platform for storing and transferring all user data.

7. Do you plan to exploit the result in the future (academic, commercial)?

Yes, commercial. The project has already had successful commercial operation at several facilities in Russia and Europe since 2018.

9. What is your personal motivation to implement this project?

Long-term growing profit as a co-founder of the project.

11. Are there any other projects similar to yours? 

Yes, but only for action/cable cam use:
	
	https://actioncam.video
	https://www.actionphotosystems.com
    
13. In what way is your project different from the existing ones?

	a. The possibility of using drones from different manufacturers and automatic data transmission from them.

	b. Availability "out of the box". Rapid deployment to new locations does not require the involvement of qualified engineers.

	c. Providing the result to the user via IPFS network.


## 3. Technical Details :pager:

> Please, responsibly indicate if your project is based on third-party development and specify the authorship. The section should include the following information: 

1. Details of how your project uses Robonomics Network.
    1. An overview of how you use the Robonomics technology stack in the development of your project.
    
    Within the project, the Robonomics platform will be used to create and store the digital twins of the production components. Work on the platform should ensure the constant storage and transfer of user data at the stages: storage user personal data, data ID of user content, storage final user video and hash data, providing user access to final video.

    2. Description of the planned load on the Robonomics network: **indicate the period (3-9 months)** and briefly describe the intended purpose of the transactions.
    
    As part of the project, traffic on the Robonomics platform will be generated during the last six months (July-December). Most of the traffic is generated during the testing phase in July and August. Traffic consists of creating multiple units of products (media packages). Average sum of transactions per month - 950, for all months - 5700.

2. An overview of the rest technology stack to be used (except Robonomics). This may include items such as: 
    1. Links to documentation of software, components, protocols, architecture, data models, API specifications, etc. that you based your project on.
    
	Python3 (3.6+)
	Docker
	Git
	Shell Linux
	FastAPI
	PostgreSQL
	Flask
	Nginx
	FFmpeg
	Android mobile app stack (Java, Kotlin, etc)
    3. Robot Operating System packages to be used (please, indicate them as a separate item).
    4. Description of the robots, devices, sensors, equipment, etc. to be used. 

Raspberry Pi 4 Model B
Barcode Scanner Module 1D / 2D
WiFi ASUS AC1300 USB Adapter Model; USB-AC54
Android mobile device

    6. Known studies, methods, algorithms that you want to use.
    7. Previous projects, Proof-of-Concept, MVP that you based this project on.
3. In the case of the prior development, any details about it: publications, repositories, articles, etc.

---

## 4. Team :busts_in_silhouette:

> In this section, you can describe your team and indicate your scientific and professional experience (scientific papers, blog posts, PhD thesis, GitHub repositories, links to projects’ sites and videos and any other information).

* **Organization** (if applicable):
    * Official name of organization.
    * Legal address of organization.
* **Contact person**:
    * Full name of the contact person representing the team.
    * Position at the organisation (if applicable).
    * Main contact address (email, Telegram or Element Riot).
    * Role in the project (if applicable).
    * Experience (if applicable).
* **Team person #1**:
    * Full name.
    * Role in the project.
    * Experience.
* **Team person #N**:
    * Full name.
    * Role in the project.
    * Experience.

---

## 5. Expected results :package:

> In this section, you are invited to describe what specific results your team is planning to produce by the end of the project. It can be: setup, launch and test guides, theory and calculations, reports, repositories, ROS modules, articles, videos, blog posts, etc. (max. one page long).

---

## 6. Project Schedule :date:

> Here you can provide the table of expected tasks with a short description of every task. This list is not strict, and you are free to adhere to a different schedule during the grant implementation. First of all, the list is needed so that you can orientate yourself on the upcoming project. Secondly, such a list will demonstrate to us that you have a clear understanding of the goals and objectives.

> Alternatively, if your table is too large, you can upload the table as a image. How to upload and use images is described in section 2.

| No. | Task description | Start/end dates |
|:---:|:----------------:|:---------------:|
| ... |        ...       |       ...       |
| ... |        ...       |       ...       |
| ... |        ...       |       ...       |

---

## 7. Project Budget :moneybag:

> Here you can specify how you plan to use the Robonomics grant. Again, this list is not strict and is intended to help you and us better understand the project.

> You also need to calculate the approximate total costs of transactions to Robonomics Network yourself. Please keep these costs in mind when planning your budget.

| No. |       Expense Item      |   Calculation   |   Total cost    |
|:---:|:-----------------------:|:---------------:|:---------------:|
| ... |           ...           |       ...       |     ...         |
| ... |           ...           |       ...       |     ...         |
| ... |Network transaction costs|       ...       |     ... (in XRT)|
|     |                         |    **TOTAL:**   |                 |

---

## 8. Additional Information :information_source: 

> Please indicate here the source (our site, ads, social network, colleagues advice, etc.) from which you found out about the Robonomics Grant Program.

> If you chose a cryptocurrency for funding other than XRT, please describe the reasons for your choice here.

> Also, feel free to share any other relevant information on the project. 
