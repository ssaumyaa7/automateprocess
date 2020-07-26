# automateprocess
Project Outline

Mlops Task 2

Create container image that’s has Jenkins installed using docker file.

When we launch this image, it should automatically starts Jenkins service in the container.

Create a Job chain of Job 1, Job 2, Job 3 & Job 4 using build pipeline plugin in Jenkins

Job1 : Pull the Github repo automatically when some developers push repo to Github.

Job 2 : By looking at the code or program file, Jenkins should automatically start the respective language interpreter install image container to deploy code ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )

Job 3 : Test your app if it is working or not.

Job 4 : if app is not working , then send email to developer with error messages.

Create One extra Job, Job 5 for monitor : If container where app is running fails due to any reason then this job should automatically start the container again.

Project Link : https://www.thesocialcomment.com/ssaumyaa7/blog-editor?edit=true&pid=5f1dab59a561f35485d3ce94
