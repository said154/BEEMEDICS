# **BEEMEDICS** 
## Final Project Specifications

__- What is the problem you are trying to solve?__
__- Who is your target audience?__
__- What are your specific goals?__

The healthcare industry is facing a huge shortage of suitable staff. Especially in big metropolis cities as Amsterdam it is hard to find the right staff.

With almost a million working people in the healthcare sector, the healhcare sectors is one of the biggest employers of the Netherlands. In 2017 the half of all the employers active in the healthcare sector was facing a shortage of capable employees. This is an overwhelming number, and it can be intimidating for employers which can lead to making rushed descisions to fill the vacancies.


**This is why employers should use BEEMEDICS**

I am going to build a web application to make it very easy for employers active in the healthcare sector to find capable freelance employees.

This web application will act as a connector between employers and freelance healthcare proffesionals. Both parties will be able to create an account on the application.

Employers will have the functionality of placing new vacancies on the platform and changing them whenever they want.

The freelancers will have the functionality to respond on the vacancies that are placed on the application. Freelancers will only be able to apply to vacancies that are matched to their profile. The matching will be done by looking at the skills, education and certificates of the freelancer and the skills, education and certificates that are mentioned in the vacancy.

When an employee finds a suitable match he can accept the freelancer. After this step the two paties can start a converstion. 

_What is your business model? Where is your revenue coming from?__

The business model will operate under the principle of being completely free for the freelancer. freelancers can use the search functionality and browse and apply to all the different vacancies. 

If a company is interested then we will offer trial period of for free. During this trial period the company is allowed to add 4 free vacancies. 

After this we will charge a hourly fee of €3 per hour worked by the freelancer.  

__What are the costs of your business?__

Here is a breakdown of the team that we would need to eventually hire to make
this business work:

#### Full Stack Developers

- The application will need to be very user friendly and presentable, but it is
important that all of the information is being stored and processed correctly
in the back end. If we wish to try new features and ideas in the future then
these developers will be essential in order to implement them. The developers
will also be responsible for website maintenance, in order to make sure that
the site is functional.

#### Market Research and Sales Reps

- Sales reps will be responsible for going to various busnisses active in the healthcare sector face to face meetings with the managers responsible to gauge interest in the idea. We would hope that as word spreads of our application that businesses will contact us as they want to join the platform.

#### Advertising

- For the launch of the product it will be critical to ensure that freelancers and businesses are made aware of its existence. This can be achieved through the use of social media such as Twitter, Facebook, Instagram etc.

#### Website Accuracy

- It is important that all of the information on the website is correct and up to date (to avoid potential customer disappointment).

#### Customer Service

- As the number of website users grow, it is likely that we will receive more and more questions and emails. A customer service team will be necessary to handle all of this.

#### Market research:

__- Who is your current competition?__
__- How is your product different from currently available competitors?__
__- What is the current supply / demand for your product?__

At the moment there are multiple recruitment agecies active in this field. But most of the recruitment agencies charge large fees and only are active in longer term contracts.

At the moment there is no other application that is as user friendly and easy to use ase BEEMEDICS. We believe that by keeping our idea as easy as possible for employers and freelancers we can distinguish ourself from the competitors.
We should set realistic goals and try to stick to them.

As previously discussed, there is an incredibly large potential customer base because of the shortage of employees and after conducting more thorough market research, we
can try to better determine the demand for the product.

#### Technical Specifications:
What data will you need to store? How will it be organized? Describe each
table, its columns, and its relationships with other tables.

     Table 'Business'

This will be a list of all the businesses and the jobs that they have placed on the platform.

The columns will be:
- Unique indentifier (each company will be assigned a unique Id with a serial primary key)
- Company (the different companies)
- Job titel (the day of the week)
- Job requirements (This are the requirements the freelancer has to meet with their skills)

company id| company   | job titel   | Job requirements |
----------|-----------|-------------|------------------|
1         | company   | job titel   | Job requirements |                                   2         | company   | job titel   | Job requirements | 
3         | company   | job titel   | Job requirements |

     Table 'Freelancers'

This will be a list of all the freelancers and their skills and certificates. 

The columns will be:
- Unique indentifier (each company will be assigned a unique Id with a serial primary key)
- Company (the different companies)
- Job titel (the day of the week)
- Job requirements (This are the requirements the freelancer has to meet with their skills)

freelancer id| freelancer   | skills   | education/ certificates  |
-------------|--------------|----------|--------------------------|
1            | freelancer   | skills   | education/ certificates  |                    2            | freelancer   | skills   | education/ certificates  | 
3            | freelancer   | skills   | education/ certificates  |

    Table 'Match'

This will be a list of all the freelancers who meet the requirements set by the employers.

The columns will be:
- Companies will be matched with freelancers if the skills/education/certificates meet the requirements of the company.

Match id | freelancer id | freelancer id  |
---------|-------------- |----------------|
1        |               |                |                                                 2        |               |                |  
3        |               |                | 


## **ROUTES**

### Home
This will be the first page the user sees.

### Over ons
This page will go into more depth to explain who we are, why people should try our site and why businesses should subscribe
to our site.

### Login
This page allows a business of freelancers to login to their account.

### Registreer
This page allows a business or freelancers to sign up for an account.

### Profile
When a business or freelancer logs into their account they will be brought to the profile page, and from here they can navigate to creating/ apply to an offer or view all of their existing offers.

### Opdrachten
This page will display all the vacancies in our database.



## Milestones/ Timeline 

#### Saturday
-Finish wireframe 

#### Sunday
-Start working on the Homepage

#### Monday
- Finish Homepage
- Finish over ons page

#### Tuesday
- Finish login page
- Finish registreer page

#### Wendnesday 
- Create profile page for businesses 

#### Thursday
- Create opdrachten page, that renders opdrachten

#### Friday
- If there any bugs then solve these
- Deploy on Huroku


