# Summary
### Managing files stored on AWS S3 with Boto3

<p>
This project demonstrates file management on AWS Simple Storage Service (S3). Several basic functions like upload or download are explained. The functionality is extended with a newly created helper package by me. This is a work in progress. 
</p>

<p> 
It relies heavily on the  
<a href = https://boto3.amazonaws.com/v1/documentation/api/latest/index.html target=_blank> 
Boto3 documentation.</a> <br> 
According to the doc: 
</p> 

<p> 
“You use the AWS SDK for Python (Boto3) to create, configure, and manage AWS services, such as Amazon Elastic Compute Cloud (Amazon EC2) and Amazon Simple Storage Service (Amazon S3). The SDK provides an object-oriented API as well as low-level access to AWS services.” 
</p> 

<p>This project creates an  

### S3_helpers_pckg 

<p> 
The package stores a class with useful helper functions, mostly manipulating the dicts of responses.<br> 
The functions are mostly self defined, but other functions for example from Github and the doc are integrated.<br> 
In this case credits are given.<br> 
The pckg is a work in progress. 

</p> 

<p>Several topics are examined here. <br> 
For example:</p> 
<ul> 
<li>Creating buckets, lists, sessions.</li> 
<li>Uploading and downloading files.</li> 
<li>Listing contents.</li> 
<li>Deleting buckets.</li> 
<li>Getting names and metadata</li> 
<li>Using Access Control Lists for security</li> 
<li>Presigned URL's for security</li>     
<li>Pandas data frames and csv downloads from S3</li>   
<li>Reading an streaming csv object into a Pandas data frame</li> 
</ul> 


<p> 
The credentials are secured with a <a href="www.dotenv.org/docs" target=_blank> 
dotenv.</a>
</p> 
 