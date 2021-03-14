HW8 - Ravi

DOCKER 

5 pts Your dockerfile. Please provide a link to this file rather than a screen capture.
	
	https://github.com/rsharm18/spring-petclinic/blob/master/Dockerfile
	
5 pts Your running docker instance as shown by a ps command. 
	
	![Screen Capture #1](images/docker_ps.png)

5 pts Your browser accessing the main page of the website from your local container. 
	
	![Screen Capture #1](images/main-page1.png)

DOCKER COMPOSE - MYSQL ONLY 

5 pts The output from the docker-compose up command. 
	
	![Screen Capture #1](images/docker-compose-mysql.png)

5 pts Your browser accessing the “Veterinarians” page of the website from your local container when you run the application from the host system. 

	![Screen Capture #1](images/main-page2.png)

5 pts A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL. 

	![Screen Capture #1](images/strack-trace.png)

DOCKER COMPOSE - APP SERVER AND MYSQL 

5 pts Your updated docker-compose.yml file containing the application server, built from your local Dockerfile, and the existing MySQL configuration. Please provide a link to this file rather than a screen capture.
	
	https://github.com/rsharm18/spring-petclinic/blob/master/docker-compose.yml
	
5 pts Your updated application-mysql.properties file containing the URL change for the database server. Please provide a link to this file rather than a screen capture. 
	
	https://github.com/rsharm18/spring-petclinic/blob/master/src/main/resources/application-mysql.properties
	
5 pts The output from the docker-compose up command. 

	![Screen Capture #1](images/docker-compose-app-mysql.png)
	
5 pts Your browser accessing the “Veterinarians” page of the website from your local container.

	![Screen Capture #1](images/main-page3.png)




================= END =======================

Hw6

1. (5 pts) Your Github account showing that is has been forked from the depaulcdm/springpetclinic repository.
	 ![Screen Capture #1](images/1_githb_forked.png)
	
2. (5 pts) Your Travis CI dashboard showing a successful first build.
	 ![Screen Capture #1](images/2_travis_success_build.png)
	
3. (5 pts) The section of the POM file showing the coordinates after you’ve changed them.
	 ![Screen Capture #1](images/3_pom_co0rdinate_updates.png)
	
4. (5 pts) Your Travis CI dashboard showing a successful build after your change of the group ID.
	 ![Screen Capture #1](images/4_travis_success_build.png)

5. (5 pts) The section of the POM file showing the coordinates after you’ve commented them out.
	 ![Screen Capture #1](images/5_pom_commented_mvn_coordinates.png)

6. (5 pts) Your Travis CI dashboard showing the unsuccessful build after the breaking change.
	 ![Screen Capture #1](images/6_travis_error_build.png)

7. (5 pts) Your Github repository with the readme.md file selected showing the build failed status after the Travis CI build fails.
	 ![Screen Capture #1](images/7_github_build_status.png)

8. (5 pts) The section of the POM file showing the coordinates after you’ve fixed them.
	 ![Screen Capture #1](images/8_pom_Uncommented_mvn_coordinates.png)

9. (5 pts) Your Travis CI dashboard showing the successful build after the breaking change has been fixed.
	 ![Screen Capture #1](images/9_travis_success_after_update.png)

10. (5 pts) Your Github repository with the readme.md file selected showing the build success status after the Travis CI build has recovered.
	 ![Screen Capture #1](images/10_git_readme_build_status_success.png)
