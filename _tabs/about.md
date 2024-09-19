---
# the default layout is 'page'
title: About
icon: fas fa-info-circle
order: 4
liquid: true
---

![banner](/assets/img/about/akash.jpg)

👋 Hello, I'm Akash Jadhav, an accomplished Software Engineer with a solid foundation in the field of Information Technology. I have a passion for delving deep into technology, understanding it at its core, and leveraging that knowledge to create innovative solutions. My commitment to excellence is evident in my contributions to open-source projects, detailed in [this blog post](/posts/open-source-contributions).

🚀 As a software craftsman, I pride myself on implementing best practices and adhering to idiomatics of programming language. I prioritize writing maintainable, clean code that not only meets current project needs but also stands the test of time. My aim is to deliver solutions that not only solve problems but also elevate the overall quality of the codebase.

🌐 Ready to embark on this tech journey with me? Let's dive in! For collaboration or any queries, feel free to reach out to me.

- Email: [akash.jadhav.cse@gmail.com](mailto:akash.jadhav.cse@gmail.com)
- Resume: [Explore my professional background here](/assets/misc/Resume.pdf)

## Skills

{% capture programming_languages %}
- C#
- TypeScript
- JavaScript
{% endcapture %}

{% capture web_frameworks %}
- Asp.net
- Express.js
- NestJS
- Fastify
{% endcapture %}

{% capture databases %}
- SQL (MySQL, PostgreSQL, MS SQL Server)
- NoSQL (MongoDb)
{% endcapture %}

{% capture orm_tools %}
- Entity Framework
- Dapper
- Sequelize
- Mongoose
- Prisma
{% endcapture %}

{% capture tools %}
- Git
{% endcapture %}

<details>
<summary>Programming Languages</summary>

{{ programming_languages | markdownify }}
</details>

<details>
<summary>Web Frameworks</summary>

{{ web_frameworks | markdownify }}
</details>

<details>
<summary>Databases</summary>

{{ databases | markdownify }}
</details>

<details>
<summary>ORM Tools</summary>

{{ orm_tools | markdownify }}
</details>

<details>
<summary>Tools</summary>

{{ tools | markdownify }}
</details>
