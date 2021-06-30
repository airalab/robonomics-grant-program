# Robonomics Grant Proposal

## 1. Administrative Information :white_check_mark:

* **Project Name:** IoT Audit Checker
* **Organisation Name:** [Techgethr](https://techgethr.com/)
* **Project Summary:** Real-time sensor data analysis system with Microsoft Azure, using Robonomics through a web app so that a person can validate and sign the information registered by a sensor in a certain time.
* **Total Estimated Duration:** 7 months
* **Expected Project Start / End Dates:** August 2021 - February 2022
* **Requested Funding:** USD $45,000 (19.89 ETH, value for June 30th 2021)
* **Payment Address:** 0xdA3ec0B8BDdd2E8BDedEde3333FbaF938fcC18c5

---

## 2. Project Overview :bookmark_tabs:

> In this section, you reveal the main idea of the project, how you intend to use the Robonomics Network to bring your idea to life, and your motivation. The section should include the following information (max. one A4 page long):

There is an important problem with the integration of the cloud with data in sensors (IoT), and it is that there is not really a real use of the data and a confirmation from someone responsible about the correctness of the data. For example, sending data from sensors (or proxies) to a cloud can be displayed in a report, but that is where the process ends (very little value in the analytical and auditing part of this information).
The project consists of designing a process for when the data reaches the cloud, it can be displayed in a web app in Microsoft Azure. In addition, the web app will be integrated with Azure cognitive services, in particular, with Anomaly Detector (https://azure.microsoft.com/en-us/services/cognitive-services/anomaly-detector/) to complement the data of the sensors and detect with Artificial Intelligence if the registration of a sensor is an anomaly (it escapes the acceptable range), for later, in the same web app, with Robonomics the data can be audited and signed by a person in charge and uploaded to IPFS , through a document that will be automatically generated with the filters selected by the person in charge (for example, which sensors or date ranges) and has information on anomalies or normal data.
In addition, other users within the same website can interact and leave comments on the audited document, using Datalog as an internal message system, also supported by a database.
The result of the project will be an application in Azure ARM template format (https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview) so that the entire application can be deployed by any developer in a few clicks, lifting all the resources in Azure automatically.
In addition, for its proper use, we will generate online documentation, video tutorials (in Spanish and English) and a couple of events / meetups to show the advantages and why they should use this new platform.

Our aspiration is, although as a project it is open, to offer around it a service and consulting for marketing. We have experience in this and we see a market potential for auditing processes in IoT systems, using Robonomics as an accelerator. In addition, it will allow to offer other types of projects using all the functionalities of Robonomics technologies.
Although there are no similar public projects, there are at the private level of some organizations. For example, in Latin America Néstor designed a couple of web systems that allowed the auditing of IoT events, but only using a database approval process, and that is why using Blockchain will be a differentiating factor in addition to making it freely available, build products and services on it.

My motivation to participate in this project is the power of the integration of different technologies in order to generate an end-to-end solution for all types of organizations, in this case, IoT, Blockchain, Artificial Intelligence and Web technologies, everything supported by Cloud technology.

In addition, I have already worked with another technology (WebMonetization), thanks to a grant provided by the Interledger Foundation, publishing applications in an open way and now generating alliances to commercialize services. More info: https://community.webmonetization.org/nescampos/web-monetization-js-helpers-grant-report-3-1n3e

I believe that with Robonomics we can do the same and more.

## 3. Technical Details :pager:

> Please, responsibly indicate if your project is based on third-party development and specify the authorship. The section should include the following information: 

1. An overview of the technology stack to be used. This may include items such as: 
    1. Links to documentation of software, components, protocols, architecture, data models, API specifications, etc. that you based your project on.
    2. Robot Operating System packages to be used (please, indicate them as a separate item).
    3. Description of the robots, devices, sensors, equipment, etc. to be used.
    4. Known studies, methods, algorithms that you want to use.
    5. Previous projects, Proof-of-Concept, MVP that you based this project on.
2. In the case of the prior development, any details about it: publications, repositories, articles, etc.
3. Details of how your project uses Robonomics Network.

---

## 4. Team :busts_in_silhouette:


* **Organization** (if applicable):
    * Official name of organization: Techgethr
    * Legal address of organization: 128 Padre Mariano (apartment 606), Providencia, Chile (postal code: 7500026)
* **Contact person**:
    * Full name of the contact person representing the team: Néstor Nicolás Campos Rojas (https://www.linkedin.com/in/nescampos/)
    * Position at the organisation (if applicable): Founder and Senior Architect.
    * Main contact address (email, Telegram or Element Riot): nestor@techgethr.com
    * Role in the project (if applicable): Team Leader and developer.
    * Experience (if applicable): Néstor has more than 11 years of experience in the development of different Cloud solutions, including Big Data and IoT. He has participated in many Microsoft Azure projects and events, being recognized as Microsoft MVP in 2020 for his contribution to the Latin American communities. He owns the Techgethr company.
* **Team person #1**:
    * Full name: Néstor Nicolás Campos Rojas
    * Role in the project: Team Leader and programmer.
    * Experience: Néstor has more than 11 years of experience in the development of different Cloud solutions, including Big Data and IoT. He has participated in many Microsoft Azure projects and events, being recognized as Microsoft MVP in 2020 for his contribution to the Latin American communities. He owns the Techgethr company.
* **Team person #2**:
    * Full name: María Carolina Vidal
    * Role in the project: Writer. In charge of writing all the documentation (tutorials and documents to Robonomics).
    * Experience: Carolina has more than 4 years of experience in different technology companies, supporting both commercial strategy and project documentation (for consumption by both technical and non-technical people).


For the recordings, it is possible that Carolina or Néstor is the person who records the video tutorials in Spanish, while for English we will look for someone just for such purposes.

---

## 5. Expected results :package:

Our project has 5 deliverables, both for the general public and those in charge of Robonomics, detailed below:

- Web application (source code) published on Github with MIT license for use (with documentation in the same repository).
- Complete video tutorial on using the application in english and spanish, published on YouTube or another platform to select.
- Complete documentation in english (in Gitbook), both of the solution and the details of each component (source code), in order to invite people to extend the project.
- Detail of the work done in PDF format (to present it to the directors and managers of Robonomics).
- At least 2 virtual meetings (meetups) with the Latin American communities of Microsoft Azure and IoT to show the application and publicize Robonomics and its components in detail.

---

## 6. Project Schedule :date:

Here is a list of the 7 main activities in the months of the project:

| No. | Task description | Start/end dates |
|:---:|:----------------:|:---------------:|
| 1 | Platform development (coding and testing) | August 2021 - October 2021|
| 2 | Publish the application as ARM Template and in Github repository | November 2021 |
| 3 | Platform design and documentation in English (installation and use)| December 2021 |
| 4 | Recording and publication of video tutorial in Spanish with the use of the platform. |December 2021 |
| 5 | Recording and publication of video tutorial in English with the use of the platform. |January 2022|
| 6 | Meetups for showing our new library and web app | January 2022 - February 2022 |
| 7 | Document delivery to Robonomics with all the details and project work. | February 2022 |

---

## 7. Project Budget :moneybag:

In the list below, we present a simple table of the breakdown of the requested amount (in USD):

| No. | Expense Item |   Calculation   | Total cost |
|:---:|:------------:|:---------------:|:----------:|
| 1 | Platform programming | 1 person for the development of the bookstore and shows it in the meetup groups, for 7 months | 34000 |
| 2 | Writing the project documentation| 1 person for 1 month of work at US$5000| 5000|
| 3 | Tutorial recording (Spanish and English) and publication | 2 people, native to each language, for US$3000 per month each | 6000|
|     |              |    **TOTAL:**   | 45000 |

The purchase of a paid meetup group, licences (or any other required tool) and the use of a Microsoft Azure environment will be at the expense of Techgethr.

---

## 8. Additional Information :information_source: 

Our intention is to maintain this software over time, beyond the duration of the project (this is how we are doing it with other technologies).
Also, we are going to extend it to other clouds (AWS and Google Cloud).
