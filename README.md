# WordPress Code Test

The Carrot Engineering team **appreciates you** and the time you are investing in our code challenge. For brevity, our project consists of a preconfigured WordPress development environment.

After finishing one or more of the following tasks, please submit a pull request with your finished work.

## Getting Started

1. Install [Docker CE](https://docs.docker.com/v17.09/docker-for-mac/install/)
2. Run `docker compose up`
3. Open [localhost:8000](localhost:8000)
4. The admin username is `carrot` and password `password`

Before you get started you may notice that the theme is not functioning properly. Please debug the issue and get the theme to enqueue properly before starting the next task.
Please keep this section of the test under 30 minutes.
Ensure that you are using git properly, we will be grading your commits and commit messages.
Choose one of the following tasks below.

## Tasks

### Task #1 Design

Real Estate agents love our fresh look on web design.
Work within the twentytwentyone theme to design a Real Estate landing page.
Since this is a landing page feel free to exclude the header and footer.
We will not be grading on the header or footer section since it takes time to properly style those sections.
Please keep your work under 2 hours.

### Task #2 Plugin Development

Make a plugin that adds a x to each blog post. @Joseph can you make this better?

### Task #3 Gutenberg Development

Use your creativity to create a custom block that real estate agents would love.
Use npm to create a custom Gutenberg block. This can be a plugin or built directly on the theme (dealers choice).
We are looking for knowledge of npm, the ablity to create a custom Gutenberg block, and creativity.
Please keep your work under 3 hours.

When you are completed with either challenge please export your database and include it in the db folder.
quick cli commnd to export a mysql database.

docker exec wordpress-code-test_db_1 /usr/bin/mysqldump -u wordpress --password=wordpress --no-tablespaces wordpress > ./db/test_dump.sql

## License

Copyright © Carrot Inc., 2021
