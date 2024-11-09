# Instagram-User-Analytics-by-using-MY-SQL

Contents1) Project description
2) Analysis- Marketing depertment
3) Analysis- Investor metrics depertment
4)Approach
5) Insights
Project description
The project is basically based on tracking the users engagement with Instagram. There are various 
teams like digital marketing,development and product teams who track this records so that they can 
utilize this information for launching a new marketing campaign or adding new features to build for 
an app which will be beneficial for their business. So, here I am working with product team of 
instragram,we are supposed to provide a detailed report for the Marketing and Investor metrics 
department. this analysis will help them make a decision based on different metrics and insights.
Analysis- Marketing depertment
Marketing team wants to launch some Campaign ,So we have to provide some details about 
instragram users.
• Rewarding most loyal users -5 oldest users of the instagram from the database provided
• Remind inactive users to start posting -the user who have never been posted a single
 photo on instragram 
• Declaring contest winner -identify the winner, who gets most likes on a single photo of 
 the contest and provide their details to the team.
• Hashtag researching - identify and suggest the top 5 most commonly used hashtags on 
 the platform 
• Launch ad campaign - what day of the week do most users register on?
OutputsRewarding the most loyal users- top 5 oldest users
 id Username created_at
80 Darby_Herzog 06-05-2016 00:14
67 Emilio_Bernier52 06-05-2016 13:04
63 Elenor88 08-05-2016 01:30
95 Nicole71 09-05-2016 17:30
38 Jordyn.Jacobson2 14-05-2016 07:56
Remind Inactive users to start postingWe have found a list of 26 people with their user id who have never posted a single photo on 
Instagram. they'll be receiving promotional emails to post their 1st photo.
 id Username
5 Aniya_Hackett
83 Bartholome.Bernhard
91 Bethany20
80 Darby_Herzog
45 David.Osinski47
54 Duane60
90 Esmeralda.Mraz57
81 Esther.Zulauf61
68 Franco_Keebler64
74 Hulda.Macejkovic
14 Jaclyn81
76 Janelle.Nikolaus81
89 Jessyca_West
57 Julien_Schmidt
7 Kasandra_Homenick
75 Leslie67
53 Linnea59
24 Maxwell.Halvorson
41 Mckenna17
66 Mike.Auer39
49 Morgan.Kassulke
71 Nia_Haag
36 Ollie_Ledner37
34 Pearl7
21 Rocio33
25 Tierra.Trantow
Declaring contest winner
In the contest, the user with the most likes on a single picture won
photo_id Username like_user
 145 Zack_Kemmer93 48
# Hashtag Researching-Top 5 hashtags that are most frequently used on 
Instagram
tag_name num_tags
smile 59
beach 42
party 39
fun 38
concert 24
Launch AD campaign -Registrants are most active on this day of the week

The best time to schedule an 
advertisement campaign is on 
Thursday and Sunday 
Investor MetricsUser Engagement: 
Provide how many times does average user posts on Instagram. Also, 
provide the total number of photos on Instagram/total number of users
Bots & Fake Accounts:
14 14
13
16
15
12
16
MONDAY TUESDAY WEDNESDAYTHURSDAY FRIDAY SATURDAY SUNDAY
 THURSDAY-16 SUNDAY-16
users (bots) who have liked every single photo on the site which is not 
possible for any normal user. 
User Engagement
74 Active users who have posted at least once. 
100 Total users (as per the data) 257 Total posts made. 
Total Photos/Total users = 257/100 = 2.57 
Based on the results, there are - so the average will be 257/74 = 3.47
Based on the data we can say that an average user posts 3-4 times.
Bots & Fake Accounts
The users who have liked every single photo on the site will be 
considered as bots.We have 13 such users based on the data who have 
liked all 257 posts, user-Id for the same are specified below
user_id num_like
21 257
71 257
5 257
66 257
41 257
14 257
57 257
24 257
76 257
75 257
54 257
91 257
36 257
ApproachFor this project, I have used My SQL to extract the required data from 
the given database using the Join function, subqueries, Aggregation, 
where condition, Group by, Distinct and other functions required. 
keeping the Primary key and foreign key in consideration provided all 
the reports asked by the marketing department and Investor metrics 
department.
InsightsThrough this project, I gained valuable insights into how business and 
data analysts work with real-time data to drive data-informed decisions. 
This experience significantly enhanced my understanding of the analysis 
process and how to generate insights that support effective decisionmaking.I also developed a clear perspective on the role of analytics in 
helping companies gain a deeper understanding of their customers. This 
understanding enables companies to optimize marketing efforts, 
enhance their products, and improve overall customer experience. 
Analytics provides the quantitative data needed for companies to make 
informed decisions and refine their services continuously.For instance, I 
learned how platforms like Instagram leverage analytics to understand 
user behavior, tailor content, and optimize engagement. By utilizing 
data strategically, Instagram improves user experience and drives 
business growth—demonstrating the impact of analytics in today's 
business environment.
