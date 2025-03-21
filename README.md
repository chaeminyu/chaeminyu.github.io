# Chaemin Yu
<img src="https://github.com/user-attachments/assets/3893a298-a852-45e2-bc1b-1aa52a6f8b8a" alt="82ACF533-BEC4-4442-9B14-122C66BC0115_1_105_c" width="200">

## About
> 🏫 Sookmyung Women's University
> 
> 💻 Computer Science Major
> 
> 👩🏻‍💻 4th Year

## Currently Associated
- ```2022.3 ~ 2023.12``` 숙명여자대학교 소프트웨어학회 FORZA 27th C Language mentor                 
- ```2024.3 ~ 2024.12``` Likelion 12th: Backend Development                                 
- ```2024.9 ~ 2024.12``` Google Developers Group on Campus Sookmyung: Machine Learning      
- ```2025.1 ~ current``` Likelion 13th: Vice President & Backend Dev Mentor
- ```2025.3 ~ current``` AWS Cloud Clubs 3rd SMWU Member                            

## Experience
- 제2회 신한 빅데이터 해커톤 참여 (2023.10.4~2023.10.8)                             
- AWS Cloud Club Camp ML/API Camp in South Korea 참여 (2024.1.6)
- Likelion 12th IdeaThon 참여 (2024.5.14)
- Likelion 12th 중앙 Hackathon 참여 (2024.8.6)
- Likelion 12th 4호선 Hackathon **Excellence Award** 🏆 (2024.11.16)

## Projects Overview

|   Duration    | Project    |  Role | Stack|
| ------------- | ------------- | ---- | ---- |
| 2024.7 ~ 2024.8  | [Likelion 12th Hackathon: VOYAGE](https://github.com/Likelion-at-SMWU-12th/CheongpaGamja-Server)  | Backend Developer | <img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white"> |
| 2024.10 ~ 2024.11 | [Likelion 12th 4호선 Hackathon: 여긴어디, 나는 누구](https://github.com/Line4Thon-Nugu/Nugu-Backend) | Backend Developer | <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> |
| 2024.10 ~ 2024.12| [Android App: 식집사](https://github.com/chaeminyu/android-shick-jip) | Full Stack Developer | ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) |
| 2024.10 ~ 2025.1| [Cloud Native App: FinEdu AI](https://github.com/chaeminyu/FinEdu-Backend.git) | Backend & Cloud Developer | <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) |
| 2025.1 ~ | Coffee Chat Web App for SMWU Developers | Backend Developer | <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> |

### Project 1) FinEdu AI : Cloud Native Financial Literacy Platform
---
#### stacks
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)

#### objective
- Deliver easy-to-understand summaries of recently web-crawled news using OpenAI API
- Use Docker containers for environment consistency and deployment ease
- Leveraging Kubernetes' autoscaling capabilities to ensure uninterrupted service even during dramatic market fluctuations

#### contributions
🛠️ Technical:
- Created web crawler with auto cleaning service (deletes news that are 30+ days old) that parses news content and connects to MySQL database using BeautifulSoup
- Created news summarizer using Spring Boot
  - ```NewsSummarizeService```: @Scheduled annotation used for summarizing news content
  - ```NewsSummaryService```: returns random summarization based on keyword-based search
- MSA Architecture
  - Common module used for scanning entities, OpenAI API configuration and repositories
  - Configured build.gradle to work as MSA architecture
- Docker
  - Created Dockerfiles for crawler, summarizer, and quiz module
- Kubernetes
  - Created CronJob for crawler and PersistentVolume for MySQL

📅 Process Improvement:
- Arranged communication tools such as Notion and GitHub
- Managed project schedule from start to finish
- Deployed AWS RDS server as test-database during testing for easier development / created MySQL server for actual deployment

### Project 2) NUGU : Collaborative Self Introduction Platform
---
#### stacks
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">

#### objective
- secure website by data encryption(UUID) and HTTPS
- deployed using Amazon EC2, Amazon RDS, Amazon Route53

#### contriubtions
🛠️ Technical:
- custom converter for array of quiz answers to String in order to prevent creating middle table in database
- managed deployment process
  - SSL certificate for HTTPS
  - deployed and managed Amazon EC2 server, Amazon RDS server, and Amazon Route53
- developed test service
  - user can create own test
  - website visitors can take test that user made
  - rates & ranks test results
  - finds user tests using @Query in ```TestRepository.java```
 
📅 Process Improvement:
- Arranged communication tools such as Notion and GitHub
- Managed weekly dev calls between frontend team and backend team

### Project 3) Coffee Chat Web Application for SMWU Developers
---
#### stacks
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

#### objective
- secure website by HTTPS, Spring Cloud AWS and AWS Systems Manager Parameter Store
- deployed using Amazon EC2, Amazon RDS
- create CI/CD pipeline for deployment automation using Github Actions

#### contriubtions
🛠️ Technical:
- managed system variables with AWS Systems Manager Parameter Store
- deployed backend instance using AWS EC2
- managed backend services (app, grafana, redis, prometheus) with Docker Compose
- configured Nginx and implemented SSL certificate for HTTPS
 
📅 Process Improvement:
- automated backend deployment process using Github Actions

<!--

### Project 3) IMFINE : Financial Education Platform for Children
---
#### stacks
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">


### Project 4) VOYAGE : Intergenerational Mentoring Platform
--- 
#### stacks
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)

-->

## Stacks

### Actively Using...
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

<img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)

![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)

![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### Have Experience in...
![C](https://img.shields.io/badge/c-%2300599C.svg?style=plastic&logo=c&logoColor=white)<img src="https://img.shields.io/badge/HTML-e34c26?style=flat&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/CSS-563d7c?&style=flat&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-323330?style=flat&logo=javascript&logoColor=F7DF1E">

## Certificates
- 멋쟁이사자처럼 12기 수료증

![E004BE34-8512-4C8C-8558-789192F5E148_1_105_c](https://github.com/user-attachments/assets/9291cd32-b363-4939-89c4-f9b0bc775fb7)
- 멋쟁이사자처럼 13기 부회장 임명장

![C76D151E-933B-4EC7-80DC-24AC08957A3E_1_105_c](https://github.com/user-attachments/assets/45ce3347-83f9-40b6-934e-863bba1cec0c)
- 멋쟁이사자처럼 12기 4호선톤 우수상장

![2024 4호선톤 우수상(누구)_page-0001](https://github.com/user-attachments/assets/8fe6a1cc-4578-4f26-a7a3-24b2548540e3)

