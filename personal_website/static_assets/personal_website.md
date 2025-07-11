## Technical Requirements
 create your own personal website.


#-----------------#-------------------------#-----------------------#----------------#

## Scenario
 You want to uplaod your CV/Resume for making it available to recuirters easily.

 **<u>Functional Requirements</u>**

  1. Ability to create, edit, and update the content of the CV, includinig sections for personal iinformation, education,work experience, skills and projects.

  2. Support for non-text content such as images.

  3. Accessible on any browser over the internet.

  4. Ability to generate insights based on website data.



**<u>Non-Functional Requirements</u>**

  1. Low latency - fast page load time
  2. High Availability -Available when accessed
  3. Ease of maintainability - easy process to update and patch the website
  4. Low cost - Cheap pay-as-you-go services




 #------------------------------#-----------------------#

## Architecture

### Static website architecture diagram


![alt text](https://github.com/Apurva14A/aws-cloud-projects/blob/3a0526b4f0ff83467ba64df605ccacc0401fdce5/personal_website/static_assets/images/image.png)




## AWS Services


## Coding the Solution

- Keep you static files (HTML, CSS, JS) at your workspace for uploading it to S3 bucket.

 - Publishing the website make it globally available.
   1. Create a **S3 Bucket** with unique name and leave **Block all Public access** option checked.
   
  ![alt text] https://github.com/Apurva14A/aws-cloud-projects/blob/95bd49cd5bdb3174701aa852cd0e354686d644ac/personal_website/static_assets/images/s3_bucket.png
     
  
  - Now go to newly created S3 bucket and upload your static file into the bucket.
  - 


## Future Work


## Summary 