{% include sidebar.html %}

## Table of Contents
- [Professional Self-Assessment](#professional-self-assessment)
- [Course Outcomes](#course-outcomes)
- [The Artifact](#the-artifact)
- [Enhancement 1: Software Design and Engineering](#enhancement-1-software-design-and-engineering)
- [Enhancement 2: Algorithms and Data Structures](#enhancement-2-algorithms-and-data-structures)
- [Enhancement 3: Databases](#enhancement-3-databases)
- [The Final Product](#the-final-product)  

# Professional Self-Assessment  

My journey with computer science started in 2018 when I took an introductory course at my local community college. I did not learn how to code but gained an understanding of the most basic concepts. I re-enrolled in college in 2023 at Southern New Hampshire University in the Computer Science program. Since then, I have been rigorously pursuing the curriculum, which has culminated in this ePortfolio.  

Completing my computer science coursework and developing an ePortfolio has strengthened my technical skills, shaped my professional goals, and prepared me for a successful career. Despite being an online program, I have had the opportunity to collaborate with hundreds of other students and learn from them, as well as from professors offering an incredibly wide range of expertise and experience.  

Communicating with stakeholders became a key competency as I presented project proposals, documented code, and explained technical concepts to non-technical audiences. Generally, this stakeholder involvement was in the form of understanding project requirements and asking questions when necessary. My work in Client-Server Development revolved around this communication in understanding the requirements for Grazioso Salvare, an animal rescue/training entity.  

This software engineering and database coursework provided hands-on experience in full-stack development, relational database design, and CRUD operations, ensuring I can build and maintain applications. Security principles, including encryption and authentication, helped me understand how to develop secure software solutions, which I implemented in Full-Stack Development by building a web application for Travlr Getaways, an online travel agency.  

These experiences, beyond the artifacts presented here in my ePortfolio, have refined my ability to collaborate, communicate effectively, and apply core computer science principles, preparing me for more technical work in my field. The enhancements presented here are the culmination of the Computer Science program at SNHU.  

### Course Outcomes  
1. Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science.  
2. Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.  
3. Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices.  
4. Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.  
5. Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.  

# The Artifact  

Selected for enhancements in the areas of Software Design and Engineering, Algorithms and Data Structures, and Databases, this artifact is an Android mobile application developed in the Mobile Architecture and Programming course (CS360). This artifact was selected from a pool of many projects because it provided a good baseline with room for significant improvements that could be revisited after taking additional courses at SNHU. The original intent of the application was to track inventory items, with the app centered around having a main data table visible to the user and giving the user the ability to perform CRUD (Create, Read, Update, Delete) functions within the application, altering the data in the database. An additional requirement of this application was to send an SMS notification to the user’s phone number when any inventory item in the database reached a stock level of zero. This application was created in 2024 for the course and was progressively built with extensive planning, user interface design, and coding functionality using Java.  

The work on this artifact included reviewing the artifact, creating a plan, and conducting a code review.  

#### [Inventory Application Artifact](https://github.com/bcwells24/CS360/tree/main/Inventory%20Management%20App){:target="_blank"}  

#### [Original Enhancement Plan](https://github.com/bcwells24/bcwells24.github.io/blob/main/assets/pdf/Artifact%20Enhancement%20Plan.pdf){:target="_blank"}  

#### [Code Review Video](https://youtu.be/Ts-C0oCHXqg){:target="_blank"}  


# Enhancement 1: Software Design and Engineering  

**Improvements**  
This enhancement significantly improved the artifact by rewriting the code from Java to Kotlin, aligning with Google's Android development standards. The refactoring process restructured the application into distinct data, middleware, and presentation layers, dramatically improving code modularity and scalability. By separating utilities like sorting and SMS management, the code became more organized and maintainable.  

**Challenges Encountered**  
Converting the existing Java codebase to Kotlin presented the primary challenge, as Kotlin was a relatively new language to me. The process required systematic method-by-method conversion to prevent feeling overwhelmed. Deliberately avoiding automated conversion tools ensured a deeper learning experience and more intentional code transformation. The enhancement felt almost like creating a brand-new application, requiring significant mental reframing of the existing project.  

**Skills Demonstrated**  
The enhancement showcased many computer science skills, including full-stack development capabilities, advanced software design and engineering expertise, and multi-language programming proficiency. This enhancement demonstrated the ability to create a comprehensive application connecting presentation and backend layers, refactor complex codebases, and adapt to modern programming languages. Mobile application development skills for the Android platform were also prominently displayed.  

**Course Outcomes**  
The enhancement directly addressed and met course outcomes focused on designing computing solutions following algorithmic principles and implementing computing solutions meeting industry standards. By refactoring the codebase and migrating to Kotlin, this showcased the ability to manage design trade-offs and utilize well-founded techniques in refactoring the code into distinct layers, creating more modularity in the codebase.  

#### [Full Enhancement 1 Narrative](https://github.com/bcwells24/CS499/blob/main/Enhancement%20Narratives/Enhancement%201%20Narrative.pdf){:target="_blank"}  
<iframe src="/assets/pdf/Enhancement%201%20Narrative.pdf" width="100%" height="600px"></iframe>  

# Enhancement 2: Algorithms and Data Structures  

**Improvements**  
This enhancement significantly improved the artifact by adding search and sort functionalities to the inventory management system. A HashMap-based search feature offers fast performance with O(1) average time complexity, ensuring consistent search times regardless of dataset size. The Heap Sort algorithm enables efficient alphabetical sorting of inventory items, reducing user time spent finding items and making the application more user-friendly for large datasets.  

**Challenges Encountered**  
Implementing the enhancement presented multiple challenges, including developing intuitive search logic that allows partial matches, like finding "Green Beans" when searching for "Beans." I also struggled with refreshing algorithmic knowledge after time away from formal data structures studies. Integrating new algorithms with the existing codebase while ensuring a smooth user interface functionality proved complex, requiring careful consideration of time complexity and memory usage trade-offs.  

**Skills Demonstrated**  
The enhancement showcased advanced technical skills in data structure implementation, algorithm design, and problem-solving. By utilizing HashMap for efficient searching and Heap Sort for optimized sorting, proficiency in selecting and implementing appropriate algorithms for specific use cases was demonstrated. The project highlighted abilities in code integration, modular design, and creating user-centric functionality that balances technical performance with practical usability.  

**Course Outcomes**  
The enhancement successfully met course outcomes by demonstrating critical thinking in algorithm selection, creating adaptable solutions, and implementing software engineering practices. The ability to evaluate algorithmic trade-offs, design efficient search solutions, and maintain a security-focused approach to software development was showcased. These outcomes were achieved through thoughtful implementation of HashMap and Heap Sort algorithms, with careful attention to performance and user experience. 

#### [Features Video](https://youtu.be/OMkE3mFA_lc){:target="_blank"}  

#### [Full Enhancement 2 Narrative](https://github.com/bcwells24/CS499/blob/main/Enhancement%20Narratives/Enhancement%202%20Narrative.pdf){:target="_blank"}  

<iframe src="/assets/pdf/Enhancement%202%20Narrative.pdf" width="100%" height="600px"></iframe>  

# Enhancement 3: Databases  

**Improvements**  
The application was significantly improved by replacing the local SQLite database with a cloud-based NoSQL Firestore database. This migration enabled real-time inventory tracking for multiple users, increased schema flexibility, and improved scalability. The enhancement also addressed a critical security vulnerability by implementing AES-GCM encryption for password storage, utilizing Android's Keystore system for secure key management. These changes transformed the application from a device-specific tool into a more versatile, secure, and collaborative platform.  

**Challenges Encountered**  
While migrating to Firestore was relatively straightforward due to Google's well-documented integration process, implementing robust security measures presented challenges. I faced complexities in managing encryption keys, integrating the Android Keystore System, and ensuring secure key storage and retrieval. Debugging issues related to cryptographic operations required revisiting fundamental security principles and Android security APIs. Additionally, testing the application's performance with large datasets necessitated creating a script to seed the database with mock data, which required recalling and applying knowledge from previous coursework in full-stack development.  

**Skills Demonstrated**  
The enhancement showcased a range of advanced skills in mobile and backend development. These include proficiency in database management across relational and non-relational paradigms, cloud integration with Firebase, and implementation of real-time data syncing. The project demonstrated expertise in cryptography by adding AES-GCM encryption for password protection and secure key management. Additionally, the ability to adapt to modern cloud-based architectures was highlighted. The creation of data seeding scripts further demonstrated an understanding of the Software Development Lifecycle and the necessity of adequate test data before deploying to a production environment.  

**Course Outcomes**  
The database enhancement successfully addressed all course outcomes:  
- Outcome 1 was achieved by creating a more collaborative environment through cloud-based data storage.  
- Outcome 2 was demonstrated through clear code documentation and professional communication of the enhancement plan.  
- Outcome 3 was met by evaluating and implementing trade-offs in choosing an appropriate cloud-based database solution.  
- Outcome 4 was fulfilled by employing innovative techniques in modernizing the application's database structure.  
- Outcome 5, while originally unplanned, was also addressed by implementing advanced security measures. This showcased a proactive security mindset by anticipating potential vulnerabilities that were discovered during the enhancement process.  

#### [Features Video](https://youtu.be/DrQfarP1rtg){:target="_blank"}    

#### [Full Enhancement 3 Narrative](https://github.com/bcwells24/CS499/blob/main/Enhancement%20Narratives/Enhancement%203%20Narrative.pdf){:target="_blank"}    

<iframe src="/assets/pdf/Enhancement%203%20Narrative.pdf" width="100%" height="600px"></iframe>


## The Final Product  

#### [Fully Enhanced Inventory Application Artifact](https://github.com/bcwells24/CS499){:target="_blank"}  


##### [Screenshot Demonstrations of the New Application](https://github.com/bcwells24/CS499/blob/main/Enhancement%20Narratives/Feature%20Walkthrough.pdf){:target="_blank"}  
