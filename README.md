STEPS TAKEN TO HOST THE WEBSITE ON S3 BUCKET
1. After logging into my AWS account, I created an s3 bucket giving it a universially unique name "jethro-static-website-bucket"
2. I enabled public access by unchecking the "Block All Public Access" box, while creating the s3 bucket 
3. I then uploaded the website files and folders which includes: assets, images and error folders. Also the license, readme and index.html files to the s3 bucket
4. I enabled static website hosting in the s3 properties 
5. I edited the s3 bucket permission policy to allow public read get object for the s3 object
6. I saved the settings and copied the bucket website endpoint through which the bucket could be accessed
Thank you

