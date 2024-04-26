# Full Stack Apps on AWS Project

You have been hired as a software engineer to develop an application that will help the FBI find missing people.  The application will upload images to the FBI cloud database hosted in AWS. This will allow the FBI to run facial recognition software on the images to detect a match. You will be developing a NodeJS server and deploying it on AWS Elastic Beanstalk. 
You will build upon the application we've developed during the lessons in this course. You'll complete a REST API endpoint in a backend service that processes incoming image URLs.

URL Image: [Filtered Image Processing](http://image-process-app-dev.us-east-1.elasticbeanstalk.com/filteredimage/?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg)
`http://image-process-app-dev.us-east-1.elasticbeanstalk.com/filteredimage/?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg`

## Steps:
### 1. Create elatic beanstalk app and enviroment
![Create-EB](./deployment_screenshot/init_elaticbeanstalk.png)

### 2. Test filtered image
![Test-filtered-image](./deployment_screenshot/test_filtered_image.png)

### 3. Test invalid image url
![Test-invalid-image](./deployment_screenshot/test_invalid_image.png)

## License

[License](LICENSE.txt)
