### [DockerHub Repo Deployment](https://hub.docker.com/repository/docker/jayr4/is218_final/general)

Through this course I learned many different things. One of the most important things I believe is creating an actual application with good practices. For example, I learned about using python and creating a virtual environment to download dependencies and creating tests with pytest. While pytest is mostly for Python. I still learned about the idea of pytest and how its important. It probably exists in other languages too and it's just a matter of learning how to use it with that language. These were the main skills utilized to build project 1, the basic CLI calculator. This project was very important. Although it wasn't a website/web application the skills are still transferable such as the tests and utilizing github with clear branches & commits to show what you did. This is especially important when working together to reduce not have code conflicts and allow division of work.

After this project other things I learned were working with Docker and github workflows. I learned how to use it and why it's used. For example, Docker helps containerize code allowing it to be run without worry about the OS or dependencies. Docker can help automate the process of downloading all this and just directly running the application as it runs it in an isolated environment. Additionally, I learned how to use workflows which not only can be used to automatically push to Dockerhub, but also allow for better team collaboration. If you set up automated test cases, you can have team members do some work and not merge it if it breaks some test cases. This makes sure their code doesn't break the existing program. It's more important with huge teams as it can serve as a way to give instant feedback.

In this project along with the previous homeworks that built on it, I also learned new things like how to work on big projects that I didn't make. I learned how to find bugs and correct them and even build upon the code to add new features utilizing what was already given. This process is very important as many times you aren't the only one working on a project and still have to debug it or add to it. On top of this, I also gained insight on working with API's and creating a user management system. This also helped see how tests are used in actual programs to make sure everything functions via the workflow pipeline.

In this project I added additional User Management Features:
  - Created a profile endpoint to allow logged in users to see their information. 
    - **Relevant Commits:** https://github.com/Jhr-4/IS218_Final/commit/e16009afb8b28fc0b254f9b8b4c807bc66a084a2
  - Added an update profile endpoint to allow logged in users to update their information. 
    - **Relevant Commits:** https://github.com/Jhr-4/IS218_Final/commit/19426d4d744e0d908e5d56238490ee680a8ac9db, 
  - Allowed Admins/Managers to update the is_professional status of users. 
    - **Relevent Commits:** https://github.com/Jhr-4/IS218_Final/commit/0b011eb9adcb75152f0930618e05dcc8dc3bce91,  
  - Integrated the mail system to notify the users if their status gets updated to is professional. 
    - **Relevant Commits:** https://github.com/Jhr-4/IS218_Final/commit/45aa31391017e8fa70cb88ab7672acb84f6e36e9, https://github.com/Jhr-4/IS218_Final/commit/40f735863311827709ed2b8f44c76a97ec7590b3
  - Made it easier to see what users can get a professional status upgrade via a list endpoint. 
    - **Relevant Commits:** https://github.com/Jhr-4/IS218_Final/commit/d6dc4a896ef9f32e34c52f6adc4697a202eaae98

Additionally, I created tests to test for these new functionalities: 
  - Testing all 4 new created api endpoints for unauthorized & authorized cases (8 - list non professionals, update professional status, get profile, update profile)
  - Testing the schemas that were added (2 - valid professional status request data, valid update profile)
  - Testing services that were added (3 - update status valid & invalid test, valid listing non professional users)
  - Testing the mail systems professional status notification (1 - valid email test with professional_status_upgraded template)
  
  - **Relevant Commits** https://github.com/Jhr-4/IS218_Final/commit/c214a3f29581c0f70a4eb347ad4dea1a295ace61, https://github.com/Jhr-4/IS218_Final/commit/1d727b8a39cc913249020c51331b1e6172480a9b, https://github.com/Jhr-4/IS218_Final/commit/8d7bb6fc118f6850ff28589ec682d539f3360b19, https://github.com/Jhr-4/IS218_Final/commit/8b6f411876e4df7cd4291394fc330e89f92e87d8, https://github.com/Jhr-4/IS218_Final/commit/d434e8a962fb0a5254863d4520baeee7b17b146d