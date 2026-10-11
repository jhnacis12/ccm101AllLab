
---

# 4. `reflection.md`

The activity specifically requires **250–350 words** and asks 5 questions. :chatgpt-content-reference{index="4"}

Copy this:

```markdown
# Mission Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job easier because it allows multiple containers and their configurations to be defined in one file. Instead of manually typing many commands for each container, the engineer can use Docker Compose to deploy the entire application stack. This makes the deployment more organized, repeatable, and easier to manage.

One important thing I learned in this mission is that YAML is very sensitive to indentation. If I use incorrect indentation or a Tab instead of spaces, Docker Compose may not be able to understand the configuration. This can result in a YAML parser error and prevent the containers from being deployed. I experienced this during the activity, which helped me understand why correct formatting is important when working with configuration files.

Environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` are used to provide configuration information to the containers. They allow the Nextcloud application to know which database credentials and database name should be used to connect to MariaDB.

It was interesting to see a complete cloud storage application such as Nextcloud being deployed in only a few minutes. Instead of installing everything manually, Docker Compose handled the deployment of the application and database containers. Seeing the containers running made the concept of containerized cloud applications easier for me to understand.

Since Mission 1, my understanding of Cloud Computing has improved. I now understand that cloud computing is not only about using online storage or applications. It also involves infrastructure, containers, deployment, automation, and managing services. This mission helped me understand how Infrastructure as Code can make cloud deployment faster, more organized, and easier to reproduce.
