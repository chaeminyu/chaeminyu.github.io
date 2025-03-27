# Chaemin Yu
> **Innovative backend engineer with proven leadership experience and expertise in cloud-native technologies**

<img src="https://github.com/user-attachments/assets/3893a298-a852-45e2-bc1b-1aa52a6f8b8a" alt="profile" width="250">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chaeminyu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chaeminyu/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chaeminyu@sookmyung.ac.kr)

## 📋 About Me

Backend developer and cloud engineering enthusiast with a focus on Spring Boot, container orchestration, and CI/CD pipelines. Experienced in developing robust, scalable web services using cloud-native technologies and microservices architecture. Passionate about DevOps practices and leading technical teams.

- 🎓 **Education**: Sookmyung Women's University, B.S. in Computer Science (Expected Feb 2026)
- 🌐 **Languages**: Korean (Native), English (Native)
- 🚀 **Strengths**: Web Backend development, Cloud-native development, technical team leadership

## 👨‍💻 Professional Experience

### Likelion @ Sookmyung Women's University | Vice President & Backend Developer
**2024.3 ~ Present**

- Led recruitment initiatives resulting in the successful onboarding of 15 junior developers
- Facilitated communication between executive board and general membership to maintain alignment with club objectives
- Organized and led technical training sessions to enhance members' development skills in web backend development
- Created technical curriculum for Spring Boot development workshops
- Mentored junior developers through paired programming and code reviews

### Prior Roles & Affiliations

| Duration | Organization | Role |
|----------|--------------|------|
| 2025.3 ~ Present | AWS Cloud Clubs 3rd SMWU | Member |
| 2024.9 ~ 2024.12 | Google Developers Group on Campus Sookmyung | Machine Learning Member |
| 2024.3 ~ 2024.12 | 멋쟁이사자처럼 Likelion 12th | Backend Developer |
| 2022.3 ~ 2023.12 | 숙명여자대학교 소프트웨어학회 FORZA 27th | C Language Mentor |

## 🏆 Achievements & Events

- **Likelion 12th 4호선 Hackathon Excellence Award** (2024.11.16)
  - Awarded for developing NUGU, a collaborative self-introduction platform
  - Recognized for technical implementation and solution architecture

- **Additional Events & Participation**
  - Likelion 12th 중앙 Hackathon (2024.8.6)
  - AWS AI/ML Ops Foundation Training (2024.5.3~2024.5.19)
  - AWS Cloud Club Camp ML/API Camp in South Korea (2024.1.6)
  - 제2회 신한 빅데이터 해커톤 (2023.10.4~2023.10.8)

## 🚀 Projects

### Coffee Chat Web App for SMWU Developers
**2025.1 ~ Present** | [GitHub Repository](https://github.com/sooktin/backend_repository)

![Spring Boot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

A platform connecting SMWU developers for mentorship and networking opportunities.

**Key Features:**
- Secure user authentication and profile management
- Mentor-mentee matching algorithm
- Real-time appointment scheduling system
- Interactive community forums

**Technical Contributions:**
- Enhanced developer productivity by transforming manual EC2 deployments into an automated CI/CD pipeline with GitHub Actions, cutting deployment cycles by 83%
- Implemented containerized deployment architecture using Docker, ensuring consistent environment across development and production
- Configured secure HTTPS communication with Nginx and SSL certificates
- Engineered secure credential management system using AWS Parameter Store to eliminate exposed credentials in codebase
- Managed backend services (app, grafana, redis, prometheus) with Docker Compose for comprehensive monitoring

### FinEdu AI - Cloud-Native Financial Literacy Platform
**2024.10 ~ 2025.1** | [GitHub Repository](https://github.com/chaeminyu/FinEdu-Backend.git)

![Spring Boot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

A cloud-native platform that provides AI-generated financial education content from web-crawled news.

**Objectives:**
- Deliver easy-to-understand summaries of recently web-crawled news using OpenAI API
- Use Docker containers for environment consistency and deployment ease
- Leverage Kubernetes' autoscaling capabilities to ensure uninterrupted service during market fluctuations

**Technical Contributions:**
- Created web crawler with auto cleaning service (deletes news that are 30+ days old) that parses news content using BeautifulSoup
- Developed news summarizer using Spring Boot with @Scheduled annotation for periodic summarization
- Designed MSA Architecture with common module for entities, OpenAI API configuration and repositories
- Implemented Docker containers for crawler, summarizer, and quiz module components
- Created Kubernetes CronJob for crawler and PersistentVolume for MySQL data persistence
- Arranged communication tools and managed project schedule from start to finish
- Deployed AWS RDS server as test-database during development phases

### NUGU - Collaborative Self Introduction Platform 🏆
**2024.10 ~ 2024.11** | [GitHub Repository](https://github.com/Line4Thon-Nugu/Nugu-Backend)

![Spring Boot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![AWS Route53](https://img.shields.io/badge/Route53-8C4FFF?style=for-the-badge&logo=amazonroute53&logoColor=white)

A web platform allowing users to create and share personalized tests for self-introduction. Won Excellence Award at Likelion 12th 4호선 Hackathon.

**Objectives:**
- Create secure website with data encryption (UUID) and HTTPS
- Deploy using Amazon EC2, Amazon RDS, Amazon Route53
- Provide intuitive test creation and sharing functionality

**Technical Contributions:**
- Implemented custom converter for array of quiz answers to String to prevent creating middle table in database
- Managed deployment process including SSL certificate for HTTPS
- Configured and managed Amazon EC2 server, Amazon RDS server, and Amazon Route53 for domain management
- Developed test service where users can create custom tests, website visitors can take tests, with results rating and ranking
- Optimized database queries using custom @Query annotations in TestRepository.java
- Coordinated weekly development calls between frontend and backend teams

### 식집사 - Android App for Plant Care
**2024.10 ~ 2024.12** | [GitHub Repository](https://github.com/chaeminyu/android-shick-jip)

![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)

A mobile application helping users care for their indoor plants with reminders and guidance.

**Key Features:**
- Plant identification and care recommendations
- Community feature for sharing plant care tips
- Local storage for offline functionality

**Technical Contributions:**
- Designed and implemented the application UI/UX with Material Design principles
- Developed backend services using Room Database for local storage
- Created camera integration for plant photo capture
- Implemented notification system for watering reminders

### VOYAGE - Intergenerational Mentoring Platform
**2024.7 ~ 2024.8** | [GitHub Repository](https://github.com/Likelion-at-SMWU-12th/CheongpaGamja-Server)

![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-red?style=for-the-badge&logo=django&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)

A platform connecting generations for knowledge sharing and mentorship.

**Key Features:**
- User profiles with expertise tagging
- Message board for community interaction
- Experience level matching algorithm

**Technical Contributions:**
- Developed RESTful API using Django REST Framework
- Implemented Django ORM for efficient data querying and relationship management
- Created user authentication and authorization system
- Deployed application on AWS EC2 instance

## 💻 Technical Skills

### Backend Development
- **Languages**: Java, Python
- **Frameworks**: Spring Boot, Django/DRF
- **Databases**: MySQL, PostgreSQL
- **APIs**: RESTful API design, OpenAI API integration

### Cloud & DevOps
- **Cloud Services**: AWS (EC2, RDS, Route53, IAM, Systems Manager)
- **Containerization**: Docker, Kubernetes
- **CI/CD**: GitHub Actions, GitOps workflows

### Tools & Others
- **Version Control**: Git, GitHub
- **Project Management**: Notion
- **Design**: Figma
- **Communication**: Slack, Discord

## 📚 Education

### Sookmyung Women's University
**B.S. in Computer Science**
Seoul, South Korea | Expected February 2026

### International Community School (Singapore)
Singapore | 2014 - 2016

## 🌐 Languages

- **Korean**: Native proficiency
- **English**: Native proficiency

## 📜 Certificates & Awards

- 멋쟁이사자처럼 13th 부회장 임명장
  ![Likelion 13th](https://github.com/user-attachments/assets/45ce3347-83f9-40b6-934e-863bba1cec0c)

  

- 멋쟁이사자처럼 12기 수료증
  ![Likelion 12th](https://github.com/user-attachments/assets/9291cd32-b363-4939-89c4-f9b0bc775fb7)

  

- 멋쟁이사자처럼 12기 4호선톤 우수상장
  ![4호선톤 우수상](https://github.com/user-attachments/assets/8fe6a1cc-4578-4f26-a7a3-24b2548540e3)

## 📞 Contact Me

- **Email**: chaeminyu@sookmyung.ac.kr
- **LinkedIn**: [linkedin.com/in/chaeminyu](https://www.linkedin.com/in/chaeminyu/)
- **GitHub**: [github.com/chaeminyu](https://github.com/chaeminyu)
