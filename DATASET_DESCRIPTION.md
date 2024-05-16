"# Dataset Description" 

This document provides an overview of the dataset utilized in the analysis, including column names, field names, datatypes and descriptions.


## Data Dictionary

| Column Name 						| Field Name 						| Data Type 	| Description                      					|
|-------------------------------------------------------|-------------------------------------------------------|---------------|-----------------------------------------------------------------------|
| id          						| ID         						| integer   	| Unique identifier for each case raised				|
| requester_id       					| Requeter id    					| integer   	| Unique identifier of customer who raised a case			|
| group							| Group							| string	| Internal Team name           						|
| status						| Status						| string    	| Current status of case                    				|
| priority 						| Priority   						| string  	| 									|
| via          						| Via       						| string	| Method of case raised to specified group				|
| created_at       					| Created at    					| datetime 	| Date and time at which the case was raised				|
| updated_at						| Updated at						| datetime  	| Date and time at which the case received the last update		|
| assigned_at						| Assigned at						| datetime   	| Date and time at which the case was assigned to the internal group	|
| initially_assigned_at					| Initially assigned at					| datetime  	| 									|
| solved_at          					| Solved at         					| datetime   	| Date and time at which the case was marked as solved			|
| resolution_time       				| Resolution time   					| integer	| Time in minutes taken for resolving the case				|
| satisfaction_score					| Satisfaction score 					| string   	| Score given by the customer for the case (1-5, Offered)          	|
| reopens 						| Reopens 						| integer    	| Number of times case was reopened                   			|
| replies						| Replies      						| integer	| Number of replies received for the case				|
| first_reply_time_in_minutes_within_business_hours	| First reply time in minutes within business hours     | integer	|									|
| first_resolution_time_in_minutes     			| First resolution time in minutes    			| integer	|									|
| first_resolution_time_in_minutes_within_business_hours| First resolution time in minutes within business hours| integer	| Unique identifier for each case raised				|
| full_resolution_time_in_minutes      			| Full resolution time in minutes   			| integer	|									|
| full_resolution_time_in_minutes_within_business_hours	| Full resolution time in minutes within business hours	| integer	|           								|
| requester_wait_time_in_minutes			| Requester wait time in minutes			| integer	|                   							|
| requester_wait_time_in_minutes_within_business_hours	| Requester wait time in minutes within business hours	| integer	|									|
| manual_tagging_of_categories				| Manual tagging of categories [list]     		| string  	| String that represents the categorization of the case			|

## Preview of CSV File

Id,Requester id,Group,Status,Priority,Via,Created at,Updated at,Assigned at,Initially assigned at,Solved at,Resolution time,Satisfaction Score,Reopens,Replies,First reply time in minutes within business hours,First resolution time in minutes,First resolution time in minutes within business hours,Full resolution time in minutes,Full resolution time in minutes within business hours,Requester wait time in minutes,Requester wait time in minutes within business hours,Manual Tagging of Categories [list]
297732,1.03006E+13,Support,Solved,Low,Mail,08-04-2023 20:52,14-06-2023 16:30,09-04-2023 10:28,09-04-2023 10:28,14-06-2023 16:30,1604,Offered,11,11,173,12975,6488,96218,47978,17853,8516,Is my treatment covered (IMTC)
311457,1.04202E+13,Reimbursement Claims,Closed,Low,Mail,24-04-2023 19:32,15-06-2023 16:37,25-04-2023 10:18,25-04-2023 10:18,26-05-2023 16:26,765,10,10,1527,2984,1527,45893,22853,30113,15139,-
329907,1.09916E+13,Support,Solved,Low,Mail,16-05-2023 17:43,30-05-2023 14:56,16-05-2023 18:18,16-05-2023 18:18,30-05-2023 14:56,333,4,10,11,61,1563,843,19993,9913,7115,3335,Claims
301553,1.03762E+13,Support,Solved,Low,Mail,13-04-2023 11:03,15-06-2023 20:55,13-04-2023 13:04,13-04-2023 13:04,15-06-2023 20:55,1522,Offered,9,9,381,2888,1448,91313,45953,18221,9401,Claims
310966,7.30286E+12,Support,Closed,Low,Mail,24-04-2023 13:21,08-06-2023 18:37,27-04-2023 14:48,24-04-2023 13:48,19-05-2023 18:25,605,4,9,9,37,37,37,36304,17739,7427,4008,Claims
327745,1.09435E+13,Support,Solved,Low,Mail,14-05-2023 11:54,07-06-2023 17:55,14-05-2023 12:53,14-05-2023 12:53,07-06-2023 17:55,582,1,9,6,62,411,411,34921,17641,3708,2088,Claims
295978,6.76388E+12,Onboardings,Closed,Low,Mail,06-04-2023 14:46,31-05-2023 06:09,06-04-2023 14:58,06-04-2023 14:58,02-05-2023 12:23,622,8,8,4070,5832,2952,37297,18577,9779,4739,-
296254,1.02649E+13,Support,Closed,Low,Mail,06-04-2023 18:02,03-06-2023 06:08,06-04-2023 18:13,06-04-2023 18:13,05-05-2023 12:17,690,Offered,8,10,67,5456,2576,41415,20535,13311,6831,Claims
305159,1.04499E+13,Support,Solved,Low,Mail,17-04-2023 18:05,07-06-2023 19:58,18-04-2023 08:51,18-04-2023 08:51,07-06-2023 19:58,1226,4,8,10,356,11038,5278,73553,36833,19107,9027,Claims
317147,9.96297E+12,Support,Closed,Low,Internal,Communication,02-05-2023 10:55,07-06-2023 10:35,02-05-2023 11:22,02-05-2023 11:22,18-05-2023 09:36,383,Offered,8,7,221,42,42,22961,11441,7367,3047-
