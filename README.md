
# Convert a WordPress website that is running on an Amazon EC2 instance into a static website hosted on Amazon S3.
 ## Task.1
 
 In this task, you perform the initial configuration of WordPress and create a blog post.
 

 ![Screenshot (52)](https://github.com/user-attachments/assets/77cd1ba6-9a81-4348-8bdd-4979f3d8efff)



 
 ![Screenshot (51)](https://github.com/user-attachments/assets/65f88b46-5459-4a48-8c22-646064bd4761)

 
 ## Task.2
 Create an Amazon S3 bucket and configure it for static website hosting. This makes the bucket accessible on the Internet via a URL.
 
 ![Screenshot (53)](https://github.com/user-attachments/assets/8d249384-97f2-470d-8702-629994921a2b)


 ![Screenshot (50)](https://github.com/user-attachments/assets/4a514700-d39b-4956-bf95-7c40d2346543)

 ## Task.3
 Use the wp-static utility to generate a static copy of  WordPress website as HTML pages. These pages will contain a copy of the entire website and can be used without the WordPress server.

 ![Screenshot (47)](https://github.com/user-attachments/assets/04ebe458-7ad9-4171-9e24-da24fef4a8ad)

 ## Task.4
 In this task, Use the AWS Command Line Interface (AWS CLI) to copy the static pages you generated in the previous task to Amazon S3. Then able to access the website even when the WordPress web server is turned off.
 
  ## Task.5
  Now that is created a static version of  website and have uploaded changes, we may want to simplify this operation in the future. In this task, We create a script to update the static files with any changes from  WordPress and upload the changes Amazon S3 to replace running each command manually.

  ![Screenshot (49)](https://github.com/user-attachments/assets/61bc8dac-773e-4bff-ab40-198198a275f0)

