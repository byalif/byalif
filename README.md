# I'll create a README.md file based on the user's information

readme_content = """
# 👋 Hi, I'm Alif Rahi

### Full Stack Software Developer | Queens, NY

📧 alifrahi22@gmail.com | 📱 +1 347-863-0546 | [Portfolio](https://portfoliobyalif.netlify.app) | [GitHub](https://github.com/byalif)

---

## 🧑‍💻 About Me

With 1.5+ years of industry experience as a Full Stack Software Developer, I specialize in web application development through all phases of the Software Development Life Cycle (SDLC) including analysis, design, coding, testing, and implementation. I have hands-on experience with a range of technologies and frameworks, particularly in AWS, Spring Boot, and React. My passion lies in creating efficient, scalable, and user-friendly applications.

---

## 💼 Work Experience

**Argoprep Ed. Tech**  
_Full Stack Software Engineer_  
_November 2023 – November 2024_  
- Developed and optimized high-performing Spring Boot microservices that support over 1 million students and educators, with REST API endpoints engineered to handle peak loads of up to 5 million requests daily.
- Created a data ingestion service utilizing Redis and batch processing to manage real-time requests from thousands of concurrent users, reducing database load by 40% during peak hours.
- Deployed and streamlined distributed backend services on AWS (EKS, S3), improving system uptime to 99.9% and reducing infrastructure costs by 25%.
- Utilized CI/CD pipelines with Jenkins for code quality checks and automated testing.

**Software Engineer Intern**  
_September 2022 – August 2023_  
- Implemented quiz feature with ReactJS and Node.js, following design mockups from Figma.
- Collaborated using Jira and Git for project management and code review.

**CUNY Tech Prep**  
_Software Developer_  
_September 2022 – August 2023_  
- Developed hands-on projects using React, Node + Express, and PostgreSQL with Agile practices and CI/CD.

---

## 📚 Education

**Bachelor of Arts in Computer Science**  
_CUNY Queens College, Queens, NY_  
_2018 - 2023_

---

## 🔧 Skills

**Front-end:** JavaScript, React.js, HTML, CSS, React-Native, Next.js, TailwindCSS, Jest, Figma, Android  
**Back-end:** Java, Spring Boot, Python, MySQL, MVC, Node.js, Express, MongoDB, C/C++  
**DevOps:** Linux, Bash/Shell Scripting, AWS, Git, Docker, Kubernetes, Jenkins, CI/CD, Jira, Maven, Terraform  
**Certifications:** AWS Certified Developer Associate (Exp. 2027)

---

## 🚀 Projects

### **[Trending Video Forecasting Tool](https://github.com/byalif/Trending-Video-Forecasts)**  
Built a distributed forecasting system to predict trending 'type beats' on YouTube by performing real-time machine learning analysis on time-series datasets.
- Designed an LSTM model to forecast hourly trends and trained it on weighted engagement metrics (views, likes, comments).  
- Automated data pipeline using cron jobs and Python scripts for data cleaning and preprocessing.

### **[Fitness Coaching Platform](https://github.com/byalif/sousa-front)**  
Developed a fitness coaching platform using Spring Boot microservices and React.js.
- Integrated Kafka for asynchronous task management and deployed microservices on AWS EKS.
- Automated deployment on AWS EKS with CI/CD pipeline using Jenkins and ArgoCD.

### **[Picogram](https://66ed8fd9686ce703f3d3f191--ephemeral-cocada-1cf45c.netlify.app)**  
A photo-sharing platform built with isolated Docker containers and deployed on AWS Elastic Beanstalk.

---

Feel free to reach out if you have any questions or would like to collaborate on a project!
"""

# Saving the content to README.md
with open("/mnt/data/README.md", "w") as f:
    f.write(readme_content)

"/mnt/data/README.md"
