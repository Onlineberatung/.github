# Contribution Guideline

## What do I need to know to help?
If you don't feel ready to make a code contribution yet, no problem! You can also check out documentation issues. Or even create own issues.

If you are interested in making a code contribution and would like to learn more about the technologies that we use check out the list below:

* [Java](https://openjdk.java.net/)
* [Docker](https://docs.docker.com/)
* [Maven](https://maven.apache.org/guides/index.html)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Swagger](https://swagger.io/)
* [Rocketchat](https://docs.rocket.chat/)
* [MongoDB](https://docs.mongodb.com/) with [Nosqlclient](https://www.nosqlclient.com/docs/user_manual.html)
* [OpenLDAP](https://www.openldap.org/)
* [Keycloak](https://www.keycloak.org/documentation)
* [MariaDB](https://mariadb.com/kb/en/documentation/) with [Adminer](https://www.adminer.org/en/)
* [nginx](https://docs.nginx.com/)
* [HTML](https://developer.mozilla.org/de/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/de/docs/Web/CSS) with [Sass](https://sass-lang.com/documentation)
* [JavaScript](https://developer.mozilla.org/de/docs/Web/JavaScript)
* [Typescript](https://www.typescriptlang.org/docs/handbook/basic-types.html)
* [React](https://reactjs.org/)
* [Biotope](https://boilerplate.biotope.sh/)

## How do I make a contribution?
Never made an open source contribution before? Wondering how contributions work in the in our project? Here's a quick rundown:

1. Find an issue that you are interested in addressing or a feature that you would like to add.
2. Fork the repository associated with the issue to your local GitHub organization. This means that you will have a copy of the repository under your-GitHub-username/repository-name.
3. Clone the repository to your local machine using git clone https://github.com/CaritasDeutschland/repository-name.git.
5. Setup the environment locally, following the guidelines in our [wiki](https://github.com/CaritasDeutschland/.github/wiki).
4. Create a new branch for your fix using git checkout -b branch-name-here. In our [wiki](#) you can find the naming conventions for branches.
5. Make the appropriate changes for the issue you are trying to address or the feature that you want to add.
6. Use git add insert-paths-of-changed-files-here to add the file contents of the changed files to the "snapshot" git uses to manage the state of the project, also known as the index.
7. Use git commit -m "Insert a short message of the changes made here" to store the contents of the index with a descriptive message.
8. Push the changes to the remote repository using git push origin branch-name-here.
9. Submit a pull request to the upstream repository - it will automatically use our [pull request template](pull_request_template.md) where you can link any issues via #issue-number and further explain your submitted changes.
10. It's OK if your pull request is not perfect (no pull request is), the reviewer will be able to help you fix any problems and improve it!
11. Wait for the pull request to be reviewed by a maintainer.
12. Make changes to the pull request if the reviewing maintainer recommends them.
13. Celebrate your success after your pull request is merged! 🥳

## Where can I go for help?
If you need help, you can ask questions on our mailing list.

## What does the Code of Conduct mean for me? 
Our [Code of Conduct](CODE_OF_CONDUCT.md) means that you are responsible for treating everyone on the project with respect and courtesy regardless of their identity. If you are the victim of any inappropriate behavior or comments as described in our Code of Conduct, we are here for you and will do the best to ensure that the abuser is reprimanded appropriately, per our code.
