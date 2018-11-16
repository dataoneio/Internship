
# Software Engineering Intern - Back-End

DataOne Innovation Labs interview challenge for Software Engineering Intern - Back-End Candidate

This repository contains an intro challange for software engineers who want to join [DataOne Innovation Labs](http://dataone.io).

### So you want to prove you're worthy to join DataOne? Awesome!

## Task 1

Design API endpoints for Client Management Application for a restaurant business. 

- Your project should use Maven

- Implement designed endpoints using Spring Boot framework. Documentation can be found here - https://spring.io/projects/spring-boot

- Implement test cases of these endpoints using Mockito or JUnit

- Test cases should include unit test case for each implemented endpoint and cover both positive and negative scenario

- Make sure all your test cases are passing before submitting the task

- Organize your code according to framework guidelines

- Must provide readme file with instructions to execute the project (It should work on any linux based machine) 

- Create a zip file for this project and send us the google drive/dropbox link when you're done. 

## Task 2



Implement a simple web service that allows one to interact with two web-browsers link, Google Chrome and Mozilla Firefox.

The interaction has four components

- Start: Starting a web-browser process with a given URL.
- Stop: Killing the web-browser process
- Cleanup: Delete all the browsing session information such as history, cache, cookies, downloads, saved passwords, etc.
- Get URL: Get the current active tab URL. Assume it has exactly one window.
- Using Selenium or any tool or library that relies on Web driver protocol to solve this problem is not allowed.

Your web service should accept commands in the form of restful URLs i.e.,

- http://<server>/start?browser=chrome&url=http://example.com should start Google Chrome and open http://example.com in the same. ( Similarly for Firefox)
  
- http://<server>/geturl?browser=<browser> should get the current active tab URL for the given browser
- http://<server>/stop?browser=<browser> should stop the given browser if it is running
- http://<server>/cleanup?browser=<browser> should clean up the browsing session for the given browser if has been stopped.
 
- Create a zip file for this project and send us the google drive/dropbox link when you're done. 
  
You need to complete any of the above two tasks. Both would be Best if you want to give a shot.




Feel free to ask questions. 

![Good Luck!](http://i.imgur.com/DHxjAeQ.jpg)


#### Thanks for your time, we look forward to hearing from you!
- The [DataOne Innovation Labs team](https://dataone.io)

