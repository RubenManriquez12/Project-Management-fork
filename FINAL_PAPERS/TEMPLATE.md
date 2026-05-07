## FarmLink: Platform for Local Food Transparency
Ruben Manriquez, Spring 2026

| ![](https://github.com/RubenManriquez12/Project-Management-fork/blob/main/FINAL_PAPERS/Screenshot%202026-04-30%20212915.png)

#### Introduction
In many communities across the United States, there is a growing disconnect between consumers and the origins of the food they consume. While local farms and smaller scale producers exist in nearly every region, access to reliable, centralized, and updated information about these sources remains limited. Consumers often rely on large grocery chains and global supply networks, not necessarily because they prefer them, but because they are the most visible and accessible options. At the same time, small farms face ongoing challenges in marketing their products and reaching broader audiences, limiting their ability to compete in an increasingly consolidated food system.

This disconnect is not simply a matter of consumer choice, it is a structural issue rooted in information gaps. Information about local farms is frequently fragmented across individual websites, social media platforms, seasonal farmers markets, and informal community networks. These sources are often inconsistent, outdated, or difficult to navigate, creating barriers for individuals who want to make more intentional decisions about their food consumption. As a result, local food systems remain less utilized despite growing interest in sustainability, ethical sourcing, and community based economies.

FarmLink is a proposed open-source platform designed to address this gap by creating a centralized, transparent, and community driven system for sharing information about local farms and ingredient sources. The platform seeks to connect consumers with nearby producers while empowering communities to actively participate in maintaining and improving the quality of information available. Rather than functioning as a static directory, FarmLink is designed as a dynamic system that evolves through continuous contributions and feedback.

This paper outlines the design, development, and management of FarmLink as an open-source project. It explores the problem, project architecture, community involvement, workflow processes, project management strategies, technical considerations, risks, and long-term sustainability. By applying principles of open-source development and project management methodologies, this project demonstrates how collaborative systems can be used to address real world challenges in local food access and information infrastructure.



#### Defining the Problem

The central problem addressed by FarmLink is not the absence of local farms or food resources, but the lack of accessible, organized, and continuously updated information about them. In most communities, information about farms is decentralized and difficult to locate. Individual farms may maintain their own websites or social media pages, but these platforms vary widely in quality and frequency of updates. Some farms rely entirely on physical presence at farmers markets or oral communication, limiting their reach to individuals already embedded in these networks.

This fragmentation creates significant barriers for consumers. Individuals who are new to a community, such as college students or recent migrants, often lack the local knowledge needed to identify nearby food sources. Even those who are interested in supporting local agriculture may not know where to begin, leading them to default to more accessible but less localized options such as Walmart or Sysco.The issue is further compounded by the dynamic nature of food systems. Product availability changes based on seasonality, weather conditions, and supply constraints. Pricing and distribution methods may also fluctuate. Without a system designed to handle frequent updates, directories quickly become outdated and unreliable. This undermines user trust and reduces the overall effectiveness of information sharing platforms. 

From the perspective of producers, the lack of centralized visibility presents a different but equally significant challenge. Small farms often operate with limited resources and must prioritize production over marketing. Maintaining a consistent digital presence can be time consuming and technically demanding, particularly for individuals who may not have experience with web development or online platforms. As a result, many farms remain invisible to potential customers outside of their immediate networks. These challenges highlight the need for a system that not only aggregates information but also supports continuous updates and community participation. FarmLink addresses this need by creating a structured platform where users, contributors, and maintainers work together to ensure the accuracy and relevance of information.


#### Objectives and Motivation

My motivation for developing FarmLink comes from both personal experience and a broader awareness of how information gaps affect communities. As a first-generation college student, I have often seen how access to information can shape opportunities and decision making. Whether it is finding academic resources, navigating financial systems, or simply identifying affordable and accessible food options, information is often the biggest barrier rather than the actual availability of resources. This same pattern exists within local food systems, where farms and producers exist, but people do not always know how to find or access them.

During my time in college, especially in the large university environment, I have noticed how disconnected many students are from the surrounding community. Even though local farms and markets exist in areas like Champaign-Urbana, many students rely almost entirely on large grocery stores or campus dining options. This is not necessarily because they prefer those options, but because they are the most visible and easiest to access. At the same time, local producers often struggle to reach younger audiences or individuals who are new to the area. This disconnect highlights a larger issue of accessibility and visibility, rather than a lack of supply.

The objective of FarmLink is to reduce this gap by creating a centralized and user friendly platform that makes local food systems more visible and accessible. The goal is not to replace existing systems, but to enhance them by improving the flow of information between producers and consumers. By making it easier to discover local farms, understand what they offer, and learn how to access their products, the platform aims to empower users to make more informed and intentional choices.
Beyond individual use, this project also has broader implications for community development and sustainability. Supporting local farms contributes to local economies, reduces reliance on long supply chains, and promotes more environmentally conscious consumption patterns. Additionally, creating a system that encourages community participation helps build a sense of shared responsibility and engagement.

This project matters not only because it addresses a practical problem, but because it reflects a larger goal of making information more equitable and accessible. By applying open-source principles and community driven design, FarmLink seeks to create a platform that is not only functional, but also inclusive and adaptable to the needs of different communities.


![](https://github.com/RubenManriquez12/Project-Management-fork/blob/a5091a455a3115114b1516ca1ba677555c36dadd/FINAL_PAPERS/Screenshot%202026-05-06%20210504.png)

|
<b>Figure 1.</b> Walmarts Across the USA. Source: [Yahoo Finance](https://finance.yahoo.com/news/walmart-still-reigns-americas-retail-king-now-183700586.html) |   

[Comment_4]: <> (Insert Figure with caption here)

#### Project Overview   

As mentioned, FarmLink is a web based application designed to connect users with local farms and ingredient sources. The platform allows users to search for farms based on location, product categories, and availability, providing detailed information about each listing. This includes farm descriptions, product offerings, operating hours, contact information, and access methods.

The platform is designed with two primary user groups in mind; consumers and producers. Consumers can use FarmLink to discover local food sources and make informed purchasing decisions, while producers can use the platform to increase their visibility and connect with new customers. By bridging this gap, the platform supports both local economies and sustainable food systems. A key feature of FarmLink is its emphasis on usability and accessibility. The interface is designed to be intuitive, allowing users to navigate the platform without requiring advanced technical skills. At the same time, the backend infrastructure is built to support scalability and long-term growth.

The technical foundation of the platform is based on Django and PostgreSQL. Django provides a robust framework for handling application logic, user authentication, and data management, while PostgreSQL offers a reliable and scalable database solution. Together, these tools create a stable environment for managing complex relational data. Rather than prioritizing highly complex features, FarmLink focuses on building a reliable and maintainable system. This approach aligns with the project’s long-term goals of sustainability and community driven development.


[Comment_5]: <> (begin your text here)

__Open Source and Working Open Principles__    

FarmLink is intentionally structured as an open-source project, guided by the principles of transparency, collaboration, and shared ownership. Open-source development allows individuals from diverse backgrounds to contribute to the project, whether through coding, data entry, documentation, or feedback. The concept of “working open” extends beyond simply making the code available. It emphasizes the importance of conducting project activities in a transparent and collaborative manner, with participatory design methods applied when possible. This includes documenting workflows, openly discussing decisions, and creating accessible pathways for participation. By adopting a working open approach, FarmLink ensures that contributors can understand how the project operates and how they can get involved.

Transparency is particularly important for a platform that relies on user generated information. By making data structures, contribution guidelines, and review processes visible, the project builds trust within the community. Users can see how information is verified and updated, reducing concerns about reliability. Additionally, open-source development supports adaptability. Other communities can replicate the FarmLink model and tailor it to their specific needs. This scalability increases the potential impact of the project and aligns with broader goals of knowledge sharing and community empowerment.


[Comment_6]: <> (begin your text two spaces after the last underscore in the previous line)

### Community and Collaboration

Community Composition
The FarmLink community consists of three primary groups: users, contributors, and maintainers. Users are individuals who rely on the platform to access information about local food sources. Contributors include farmers, volunteers, and developers who add and update information. Maintainers are responsible for overseeing the project, reviewing contributions, and ensuring consistency.

Community Participation
Participation is a central component of the platform. Users are encouraged to submit new farm listings, report outdated information, and suggest improvements. This participatory model ensures that the platform remains dynamic and responsive to changes. To accommodate different levels of technical expertise, the project provides multiple contribution pathways. Users who aren't very tech savy can submit updates through structured forms, while more technical contributors can engage through GitHub workflows such as issues and pull requests. This approach lowers barriers to participation and encourages broader involvement.

Community Governance
The governance structure of FarmLink is designed to balance openness with accountability. Maintainers are responsible for reviewing submissions and managing updates, while contributors provide input and improvements. Clear documentation outlines roles, responsibilities, and processes, ensuring that participants understand how to engage with the project.
This governance model addresses common challenges in open-source projects, such as contributor turnover and inconsistent participation. By establishing structured processes, the project maintains continuity and ensures that contributions are effectively integrated.

### Workflow and Process Mapping

![](FINAL_PAPERS/Grey Blue Pink Green Bold Project Status Steps Flowchart (2).png)
The workflow for FarmLink follows a structured cycle of submission, review, and release. This process aligns with workflow mapping principles discussed in class, emphasizing clarity, modularity, and continuous improvement.
The submission stage involves collecting new data from users or contributors. This may include adding new farm listings or updating existing information. The review stage involves verifying the accuracy and completeness of submissions. Maintainers evaluate each entry based on predefined criteria, ensuring consistency and reliability. The release stage involves integrating approved updates into the platform and making them publicly accessible.
This workflow is supported by a Kanban based project management system, where tasks are represented as GitHub issues and move through stages such as Backlog, To Do, Ready, In Progress, In Review, and Done. This structure provides a visual representation of progress and helps contributors understand the current state of the project.


### Conclusion      

[Comment_7]: <> (begin your text here)


### References     

[Comment_8]: <> (begin your reference list here. Cite as author, year in main text. Reference link should correpond with link in Comment 2  Use any format you wish -- MLA, APA, etc.)

Cite as the form (Lastname, 2023) in the body of your text. List reference citation in this section. 
