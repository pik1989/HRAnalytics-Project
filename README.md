# HR-Analytics

HR Analytics, as the name suggests is the tool for HR to suggest the top 10 jobs from the dataset based on the skills of the person. There are two versions of this tool. In the First version, I have used pyreparser for extracting the skills from the resume and the second version is manually providing the skills as the input. Both have there UI based on their input type. The dataset is created via scrapping of the glassdoor website using selenium and beautiful soup, around 1923 jobs are extracted. And for matching the job description and the skills, I have used the NLP algorithm which is based on n-grams, tf-idf, and KNN is used for finding the best jobs for the person. At last deployed both the version using Flask and rendering is done using simple html templates.

Version 1: (Input is the resume)
Version 2: (Skills is entered manually)
 
# Introduction:
The basic idea behind this HR analytics tool is to provide ease to people for finding the best jobs based on their skills that the person mentioned in their resume in the first version or the skills inputted manually in the second version. 
It’s very difficult for everyone to find out jobs, internship etc. on the basics of skills they have. Everyone to spend a lot of time to search jobs on various job posting sites like glassdoor, indeed, internshala, etc. checking each and every posting in the list with having applying some filters to it but it consume very much time because when we have to check each and every time that the job posting we are going to apply, Is we are worthy to apply to this job? Sometimes, we are not having the skills that are mentioned in the job description.
So, as I mentioned the basic idea. We are suggesting the job on the basics of the skills of the person. It has many benefits that we have not to check each and every posting of jobs so it consumes less time. Just we have to provide the input, i.e., the skills and output, i.e., the suggested jobs will be shown on the UI or on the local host.



