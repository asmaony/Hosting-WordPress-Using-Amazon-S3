
# Convert a WordPress website that is running on an Amazon EC2 instance into a static website hosted on Amazon S3.
 ## Task.1
 
 In this task, you perform the initial configuration of WordPress and create a blog post.
 
 ## Task.2
 Create an Amazon S3 bucket and configure it for static website hosting. This makes the bucket accessible on the Internet via a URL.
 ## task.3
 Use the wp-static utility to generate a static copy of  WordPress website as HTML pages. These pages will contain a copy of the entire website and can be used without the WordPress server.
 ## Task.4
 In this task, Use the AWS Command Line Interface (AWS CLI) to copy the static pages you generated in the previous task to Amazon S3. Then able to access the website even when the WordPress web server is turned 
  off.  
  ## Task.5
  Now that is created a static version of  website and have uploaded changes, we may want to simplify this operation in the future. In this task, We create a script to update the static files with any changes from 
   WordPress and upload the changes Amazon S3 to replace running each command manually.
