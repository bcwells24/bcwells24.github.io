## Professional Self Assessment  

My journey with computer science started in 2018 when I took an introductory course at my local community college. I did not learn how to code but learned about the most basic concepts. I re-enrolled in college in 2023 at Southern New Hampshire University, in the Computer Science Program. Since then, I have been rigorously pursuing the curriculum, which has culminated in this ePortfolio. 

Completing my computer science coursework and developing an ePortfolio has strengthened my technical skills, shaped my professional goals, and prepared me for a successful career. Despite being an online program, I have had the opportunity to collaborate with hundreds of other students and learn from them as well as professors offering an incredibly wide range of expertise and experience. 

Communicating with stakeholders became a key competency as I presented project proposals, documented code, and explained technical concepts to non-technical audiences. Generally, this stakeholder involvement was in the form of understanding project requirements and asking questions when necessary. My work in Client Server Development revolved around this communication in understanding the requirements for Grazioso Salvare, an animal rescue/training entity. 

This software engineering and database coursework provided hands-on experience in full-stack development, relational database design, and CRUD operations, ensuring I can build and maintain applications. Security principles, including encryption and authentication, helped me understand how to develop secure software solutions and implement them in Full-Stack Development by building a web application for Travlr Getaways, an online travel agency. 

These experiences, beyond the artifact presented here in my ePortfolio, have refined my ability to collaborate, communicate effectively, and apply core computer science principles, preparing me for more technical work in my field. The enhancements presented here are the culmination of the Computer Science Program at SNHU.


## The Artifact

Selected for enhancements in the areas of Software Deisgn and Engineering, Algorithms and Data Structures, and Databases this artifact is an Android mobile application developed in the Mobile Architecture and Programming course (CS360). This artifact is selected from a pool of many projects becuase it provided a good baseline with room for many imporvements that could be revisited after taking additional courses at SNHU. The original intent of the application was to track inventory items, with the app centered around having a main data table visible to the user and give the user the ability to perform CRUD (Create, Read, Update, Delete) functions within the application, altering the data in the database. An additional requirement of this application was to send an SMS notification to the user’s phone number when any inventory item in the database reached a stock level of zero. This application was created in 2024 for the course and was progressively built with robust planning, User Interface design, and coding functionality into the application with Java. <br>  
The original application can be seen here:  
[Inventory Application Artifact](https://github.com/bcwells24/CS360/tree/main/Inventory%20Management%20App)

### Code Review
[View on YouTube](https://youtu.be/Ts-C0oCHXqg)



## Enhancement 1: Software Design and Engineering
**Improvements**  
This enhancement significantly improved the artifact by rewriting the code from Java to Kotlin, aligning with Google's Android development standards. The refactoring process restructured the application into distinct data, middleware, and presentation layers, dramatically improving code modularity and scalability. By separating utilities like sorting and SMS management, the code became more organized and maintainable.  
<br>
**Challenges Encountered**  
Converting the existing Java codebase to Kotlin presented the primary challenge, as Kotlin was a relatively new language to me. The process required systematic method-by-method conversion to prevent feeling overwhelmed. Deliberately avoiding automated conversion tools ensured a deeper learning experience and more intentional code transformation. The enhancement felt almost like creating a brand new application, requiring significant mental reframing of the existing project. 
<br>  
**Skills Demonstrated**  
The enhancement showcased many computer science skills, including full-stack development capabilities, advanced software design and engineering expertise, and multi-language programming proficiency. This enhancement demonstrated the ability to create a comprehensive application connecting presentation and backend layers, refactor complex codebases, and adapt to modern programming languages. Mobile application development skills for the Android platform were also prominently displayed through this enhancement.  
<br>
**Course Outcomes**  
The enhancement directly addressed and met course outcomes focused on designing computing solutions following algorithmic principles and implementing computing solutions meeting industry standards. By refactoring the codebase and migrating to Kotlin, this showcased the ability to manage design trade-offs and utilize well-founded techniques in refactoring the code into distinct layers creating more modularity in the code base.

[Full Enhancement 1 Narrative](https://github.com/bcwells24/CS499/blob/main/Enhancement%20Narratives/Enhancement%201%20Narrative.pdf)
## Enhancement 2: Algorithms and Data Structures

**Improvements**  
This enhancement significantly improved the artifact by adding search and sort functionalities to the inventory management system. A HashMap-based search feature offers fast performance with O(1) average time complexity, ensuring consistent search times regardless of dataset size. The Heap Sort algorithm enables efficient alphabetical sorting of inventory items, reducing user time spent finding items and making the application more user-friendly for large datasets.  
<br>
**Challenges Encountered**  
Implementing the enhancement presented multiple challenges, including developing intuitive search logic that allows partial matches like finding "Green Beans" when searching "Beans". I also struggled with refreshing algorithmic knowledge after time away from formal data structures studies. Integrating new algorithms with the existing codebase while ensuring seamless user interface functionality proved complex, requiring careful consideration of time complexity and memory usage trade-offs.  
<br>
**Skills Demonstrated**  
The enhancement showcased advanced technical skills in data structure implementation, algorithm design, and problem-solving. By utilizing HashMap for efficient searching and Heap Sort for optimized sorting, proficiency in selecting and implementing appropriate algorithms for specific use cases was demonstrated. The project highlighted abilities in code integration, modular design, and creating user-centric functionality that balances technical performance with practical usability.  
<br>
**Course Outcomes**  
The enhancement successfully met course outcomes by demonstrating critical thinking in algorithm selection, creating adaptable solutions, and implementing strong software engineering practices. The project showcased the ability to evaluate algorithmic trade-offs, design efficient search solutions, and maintain a security-focused approach to software development. These outcomes were achieved through thoughtful implementation of HashMap and Heap Sort algorithms, with careful attention to performance and user experience.  

[Full Enhancement 2 Narrative](https://github.com/bcwells24/CS499/blob/main/Enhancement%20Narratives/Enhancement%202%20Narrative.pdf)
## Enhancement 3: Databases

**Improvements**  
The application was significantly improved by replacing the local SQLite database with a cloud-based NoSQL Firestore database. This migration enabled real-time inventory tracking for multiple users, increased schema flexibility, and improved scalability. The enhancement also addressed a critical security vulnerability by implementing AES/GCM encryption for password storage, utilizing Android's Keystore system for secure key management. These changes transformed the application from a device-specific tool to a more versatile, secure, and collaborative platform.  
<br>
**Challenges Encountered**  
While migrating to Firestore was relatively straightforward due to Google's easy to follow documentation, implementing robust security measures presented challenges. I faced complexities in managing encryption keys, integrating the Android Keystore System, and ensuring secure key storage and retrieval. Debugging issues related to cryptographic operations required revisiting fundamental security principles and Android security APIs. Additionally, testing the application's performance with large datasets necessitated creating a script to seed the database with mock data, requiring the developer to recall and apply knowledge from previous coursework in full-stack development.  
<br>
**Skills Demonstrated**  
The enhancement showcased a range of advanced skills in mobile and backend development. These include proficiency in database management across relational and non-relational paradigms, cloud integration with Firebase, and implementation of real-time data syncing. Proficiency in cryptography by adding AES/GCM encryption for password protection was demonstrated with this enhancement. The project also highlighted skills in cloud computing, mobile-backend integration, and the ability to adapt to modern cloud-based architectures. Furthermore, the creation of data seeding scripts demonstrated versatility in full-stack development techniques.  
<br>
**Course Outcomes**  
The database enhancement successfully addressed all course outcomes. Outcome 1 was achieved by creating a more collaborative environment through cloud-based data storage. Outcome 2 was demonstrated through clear code documentation and professional communication of the enhancement plan. Outcome 3 was met by evaluating and implementing trade-offs in choosing a cloud-based database solution. Outcome 4 was fulfilled by employing innovative techniques in modernizing the application's database structure. Unexpectedly, Outcome 5 was also addressed by implementing advanced security measures, showcasing a proactive security mindset in anticipating potential vulnerabilities. 

[Full Enhancement 3 Narrative](https://github.com/bcwells24/CS499/blob/main/Enhancement%20Narratives/Enhancement%203%20Narrative.pdf)
## Fully Enhanced Artifact

The enhanced application is avaiable here:  
[Enhanced Inventory Application Artifact](https://github.com/bcwells24/CS499)

Screenshot demonstrations of the new application can be seen here:  
[Enhanced Application Walkthrough](https://github.com/bcwells24/CS499/blob/main/Enhancement%20Narratives/Feature%20Walkthrough.pdf)


