# To-Mount-AWS-S3-Bucket-On-Amazon-EC2-Linux-using-Shell-Script
How To Mount AWS S3 Bucket On Amazon EC2 Linux Using S3FS with a single shell script

In this project , i am going to mount AWS S3 Bucket on Amazon EC2 Linux (using s3fs) with the help of a single script file.</br>
But before that we have some prerequisite to be done : </br>
🥇 Create an EC2 Linux (I have used Ubuntu in this demo) instance.</br>
🥈 Create an IAM user for s3fs and attach AmazonS3fullaccess policy ; create user ; create access keys for CLI.</br>
🥉 Go to S3 service and create a new bucket .</br>
Also, connect to your EC2 Linux and Go to your home directory and create a new directory . This Directory we are going to sync and connect with our S3 bucket.</br>
Now... keep these values handy with you :
Access key ,secret key , bucket name , region name , directory name , absolute path of directory .
Just Pull the script from my github and execute it from home directory of EC2 linux instance . Fstab entry is also done with script for permanent mounting.</br>



