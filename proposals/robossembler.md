# Robonomics Grant Proposal

> This file will contain the main information hub of your Robonomics grant proposal. We recommend to provide full and comprehensive information to speed up the proposal review process. Comments in the lines starting with a `>` and can be deleted.

* **Project Name:** Robossembler
* **Team Name:** Robossembler Team
* **Summary:** Creating Gazebo-based simulation of Self-Replicated Robotics Infrastructure for Manipulators
* **Total Estimated Duration:** 9-12 months
* **Requested Funding:** 40000 DAI
* **Payment Address:** 0xC27502Bf5E1f5032C5923B1B5be83ddb7BC770fF

> Do not forget that we provide funding in in **Robonomics** ([XRT](https://www.coingecko.com/en/coins/robonomics-network)) or **Dai Stablecoin** ([DAI](https://www.coingecko.com/en/coins/dai)) or Ethereum ([ETH](https://www.coingecko.com/en/coins/ethereum)) tokens at the price at the time of proposal approval.

---

## :bookmark_tabs: Project Overview

> In this section, you reveal the project, technical details, and how you intend to use the Robonomics Network to bring your idea to life. To help you, we have listed possible questions that you would like to answer.

### :mechanical_arm: Motivation

>
* It is proposed to create a digital twin of a partially self-replicating robotic factory, temporarily abandoning the study of resource-extracting subsystems, the chemical industry, the production of microelectronics, and energy. The demonstration of a dynamic model of a factory that can create complete copies of its production units will draw the attention of the world engineering community to the need to apply special approaches to creating fully automated systems and will start the process of further development. Since the key element of the deserted production is robot manipulators, it is proposed to focus on their reproduction in the framework of creating a model.
* Modern production systems are complex software and hardware complexes consisting of a large number of components with varying degrees of interdependence, which are developed, manufactured and supplied by various companies. On the one hand, a deep division of labor increases quality, but on the other hand, it makes it difficult to integrate components into fully automated super - systems. In turn, the task of developing autonomous (light's out) or self-replicating (self-replication) technical systems requires close integration of life cycle data within the framework of the common requirement of "desolation" for all its subsystems. This requirement also imposes a number of significant restrictions on the design of all components of the system and makes it almost impossible to develop and implement within a single company. Even the most automated industries cannot escape manual labor; especially in assembly operations.
* However, fully automated production also has a number of advantages, because it allows you to achieve a high synergistic effect by eliminating human-machine interfaces and aesthetic requirements (including special labeling); human-adapted operating conditions (air, humidity, lighting, temperature); compliance with safety standards, interchangeability within the existing range of components, maintainability. That is, the development of such systems requires a revision of the basics of technical systems and the principles of the production process, which is currently focused on assembly, commissioning and operation by humans.
* However, what is not possible for a single company may be possible for the international open source movement, which can facilitate the continuous integration of the data of the life cycle of subsystems developed by individual teams, which is difficult in the conditions of classical engineering firms. Also, the current level of computing systems at the current stage of their development makes it possible to create digital twins (digital twin) productions, the behavior of which in the framework of simulation can be approximated to real physical objects. In the future, it will be possible not to wait for pilot production to test some hypothesis, but to limit ourselves to physical and simulation modeling. Developers will not be constrained by the limitations of the existing component base and the resulting inertia of thinking. It is acceptable to come up with everything from scratch-taking into account the requirement of full automation, ensuring transparency of the development process and the contribution of everyone.
* Robossembler will not be just academic research - it is first step to self-replicating industrial systems and fully robotics economics
* There are no other similar projects


### :pager: Technical Details

> Please, responsibly indicate if your project is based on third-party development and specify the authorship.

>
* **Short Disrciption of expected tasks** - technology/material research, 3D-model, programming robotics arm, simulations
* **An overview of the technology stack to be used** - Gazebo/Ignition, ROS, Unity3D/Godot, Python/Haskell/bash.
* **Robot Operating System packages to be used** - all needed Open-licensed packages
* **Description of the used robots, devices, sensors, equipment, etc.** - none
* **Documentation of software, components, protocols, architecture, etc. that you based your project.** - ...
* **Data models / API specifications.** - ...
* **Known studies, methods, algorithms that you want to use.** - ...
* **Previous projects, Proof-of-Concept, MVP that you based this project.** - self-replication-oriented brushless servo project
* **In the case of the prior development, any details about it: publications, repositories, articles, etc.** - https://github.com/movefasta/articles/blob/master/robosphere/robossembler_en.md
* **An indication of how your project uses Robonomics Network.** - Gazebo simulation with ROS/Robonomics distro

---

## :busts_in_silhouette: Team

### :speaking_head: Contact
* **Contact Name:** Igor Brylyov
* **Contact Address:** https://t.me/brylev 

### :bust_in_silhouette: Team members
* Igor Brylyov, Team Lead
* Stanislav Sgonov, Tech Lead/3D-modeling (Solidworks)
* Mikhail Tarantsov, System/MCU Programming (Linux)

> If you are a representative of an organization / university and participate in a grant on its behalf, then indicate the following information.

### :office: Organization
* **Registered Organization Name:** None
* **Registered Address:** None

### :trophy: Experience of Team

> Please describe the team's relevant experience. In this section, you can indicate scientific and professional experience, scientific papers, blog posts, PhD thesis, GitHub repositories, links to projects' sites and videos and any other information.

* PLC developement project management
* Robotics Arm Design
* Brushless Servodrive Design
* Linux server management

---

## :package: Expected results

> In this section, you are invited to describe what specific deliverables will be obtained in final. It can be: setup, launch and test guides, theory and calculations, reports, repositories, ROS modules, articles, videos, blog posts, etc.

* Blog posts
* Video tutorials
* Gazebo/Ignition simulation repositories
* Technology stack repositories

---

## :information_source: Additional Information

> Feel free to share any other relevant information on the project. 

At the moment, manipulators cannot be produced in fully automatic mode due to the following restrictions:
1. The technical complexity or impossibility of automating individual operations - for example, the installation of drive belts and fasteners of structural components that require stretching cables, connectors. Cable connections require standardized elements of a specific nomenclature. The use of custom items is difficult due to the high cost and long delivery times.
2. A set of deviations, the accumulation of which in its sum levels the very ability to perform accurate operations, which leads to a progressive decrease in the quality of reproduction until the processes stop completely. The inability to provide a mechanism for error compensation without a person.
3. The need to provide a marketable appearance and a wide range of products at the expense of the convenience of copying samples. Which should work "out of the box", without finishing them by the user, which may be necessary with even minimal, random design differences.

In this regard, it is proposed to use a different approach:
1. The rejection of the global assembly of robots in one workplace. Intermediate modular subassemblies are created;
2. No complex assembly elements - for example, drive belts that stretch through 2-3 flexible joints;
3. The use of another criterion for the effectiveness of the technical system — not compliance with certain requirements for the product, but ensuring self-reproduction; avoiding rejection by including defective products in the repeated production cycle, taking into account the changed parameters;
4. Revision of the housing design. The housing should become a three-dimensional structure with cables and tubes already held inside, with toothed crowns, bearings, axles, conductive cores, electronic boards, sensors, and contact pads fused into it. It is possible to make it in an injection mold with conductors. The body itself can be cast. The most promising may be glass foam with fillers that improve the dynamic characteristics.
5. The robot will be assembled from complementary blocks-segments with all-in-one connections or mounting collets. If a node fails – the connection is destroyed, the module is replaced, and the connection is restored.
6. Robots undergo mandatory calibration aimed at accounting for and compensating for deviations in its mathematical model of kinematics.

The assembly cell of the self-replicating automated system (SRAS) will be a complex consisting of a desktop in the form of a honeycomb, having 6 pylons for docking robots, 6-7-axis manipulators, machine adapters and other working tables. The next step after designing the production of servos and robot manipulators is to develop a model of self-reproduction of the automated control system as an elementary unit of the production system. It is proposed to provide the interaction of the automated control systems with the help of adapters – remote interfaces for controlling the CNC machine by the automated control system complex. The adapter will also have a pylon for docking the robot manipulator and servicing the CNC machine. The use of adapters will greatly facilitate the transition from the classic factory to the automatic one.

In preparation for the implementation of the plan described above, a model and prototype of a servo drive adapted for self-replication was developed in the period 2013-2019.
