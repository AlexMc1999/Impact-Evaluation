Impact Evaluation

Project Background
With the introduction of a new CRM system, the business has faced issues of identifying potential prospecting activities, potential star customers and a lack of precision when it comes to marketing.
The current way of identifying these prospects and customers, is to go into a long list of schools and check each area individually, or the users are expected to have extensive knowledge on the areas that they are trying to target for prospecting or for good case studies. On a national level this is unattainable and unsustainable going forward, to gain the most effective results an automatically updated dashboard will need to be created and uploaded into the CRM.
A lack of visibility has had a considerable impact on the business, as marketing and prospecting activities are made considerably more complicated and less specific. This goes against industry standards as Accounts Based Marketing (ABM), requires the identification of ideal customers to become representatives for the brand, and allows the personalisation of marketing materials to prospects where personalised marketing can be tailored to the specific characteristics of the customers (Pophal, 2023).
Many pain points for users are that they struggle to find usable information that helps implement the strategy adopted by the business, therefore the longer this persists the growth in the need for a visual representation of this data also grows as the market is limited and relatively small. This means that any advantage over competition is needed to help develop an increase in market share therefore utilising ABM is a necessity that the company needs to address (Melitz and Ottaviano, 2008). This is why the introduction of an automated and easily understandable dashboard was proposed. The dashboard will allow many of the issues faced by both managers and team members to be reduced/nullified completely, as Orloyskyi and Kopp (2020) state in their research that business need to have visual access to the data they produce to see success in an ever-competitive market.
Project Summary – Solving the Business Problem
This will be solved by introducing the automated dashboards, these will be made with a User-Centred-Design (UCD) focus in mind to allow for the best functioning dashboards to be implemented. UCD focuses on the end users requirements, involving users in the design process, simplification, and ease of navigation based on the level of competency that the users have with using the program (Rajenen and Rajenen, 2022). These points are furthered by the reports produced by both Alhamdi et al. (2022) and Altendeitering et al. (2024) as they argue the need for users to be able to understand both the visualisations of the dashboard and how to function the different aspects of the dashboard, such as filtering and navigation. This meant that working alongside users was necessary in making sure that the dashboards were navigable and understandable.
The implementation of the described dashboards will be done by identifying current needs of the Sales and Support Manager in discovery meetings, feedback presentations and workshops, and dashboard requirements document. With these helping inform the contents of the dashboard, a data processing process will follow the method of Extract, Load and Transform (E-LT) this is because of understanding the limitations of user knowledge surrounding SQL transformation techniques, as well as, access to SQL being limited within the company. With this knowledge on both capabilities and resources, using an E-LT process was the most effective way to process data as it allows the reduction of integration with database administration (Freudenreich et al., 2013). This is important for this project as the restrictions to access on the SQL database and changing aspects of each dataset involved is very limited and often takes more time to complete.
The Project Outline
Data Infrastructure and Tools
Within this project different tools were used to develop the automated dashboards. These tools were SQL Server Management System (SSMS), PowerBI Desktop, and PowerBI Online environment. 
SSMS was used to Extract, refresh, and input new data values into the data visualisations. Using SSMS allowed connections between the online datasets and PowerBI to be established and regular data refreshes to be performed. This allowed the creation of automated dashboards to be created and their impact the business in a positive way. The use of SSMS allowed for secure transfer of data between platforms, with the use of credentials allowing the use of the data to managed, maintaining a high level of security between programs.
 PowerBI desktop allowed the data to be loaded from SSMS and transformed with the use of Power Query tools. Doing this allowed data to be transformed in a manageable manner without impacting other dashboards that used data from SSMS. It also allowed data visualisations to be created, allowing the interactive dashboard to be created. Once these were created the dashboards were published to the online environment. To mitigate any potential information risks the data was secured via SSMS, and to engage with the dashboards in this state permissions were set on the folder allowing certain people access to the work in progress files.
PowerBI Online Environment allowed automated connections and data refreshes to be prepared. It also allowed the dashboard to be embedded into the CRM’s dashboard portfolio to allow users to access and use the dashboard via the online CRM. This allowed for regularly updated information to be easily accessed and used by company stakeholders. This part of the pipeline was controlled by our external CRM provider and there was sensitive data and processes, therefore information and access to these areas was limited. Access to the portal was limited as potentially confidential information from both internal and external sources were stored on there, keeping in line with the Data Protection Act (2018)
Data Engineering 
Within the project ELT was used as the data had to be transformed at a  specific point to not conflict with other dashboards and visualisations being used off the same datasets. Therefore, choosing to perform data transformations like data merges (School types merged into one), data reformatting, and data aggregation, doing these in Power Query allowed the information to be tailored to specific needs of the users, and allowed for more data management processes to occur as it was being performed in an environment the user was most familiar with. Understanding the businesses capabilities helped plan for this in the project (Alam et al. 2010).
A visualisation to help showcase the ELT process that has been taken to make the dashboard.
 
Within the dashboard, to allow for functional filters and deeper insights to be gathered, a relational database was created within the PowerBI field mapping function. This allowed filters to work across datasets, sales consultants to be attributed to the areas they work with, and informative data to be provided at the bottom of the dashboard in the table. This was added as this allowed the key users to gain the full usability of the dashboard and allowed them to gain actionable insights from the data. 

The relationship connections that were established to allow for many of the dashboards functionalities.
 
Within PowerBI the usage of DAX allowed for specific measures to be created such as the market share. Due to the way this was set up, whenever a data refresh is performed the market share will change, this will also be available across filters. This could have only been currently performed in PowerBI due to the limitations in both techkonlogy and knowledge surrounding the measures. The usage of the average functionality on the visualisation allows this to be turn into an accurate market share percentage.
The DAX Formula to create the market share visualisation.
 







Data Visualisation 
 

The use of relevant dashboards is becoming imperative to many organisations, as the amount of data produced is growing at an exponential rate (Saha, 2020). As this growth has became ever more present, the need to interpret and understand complex and abundant data has seen the importance of data visualisation equally grow in importance. This is stated by Orloyskyi and Kopp (2020), as they identify the importance for small businesses to always have visual access to their data. 
This led to the dashboard being designed to be very user friendly, with key visuals that were interactable with the use of buttons and the map feature. The dashboard was also able to filter on many aspects like Location, School Characteristic, and Sales Consultant Areas. This allowed users to drill down to view potential prospects and current customers to make actionable insights based on key characteristics of the school. This allowed the sales team to identify possible schools that fit similar characteristics as customers in the area. Doing this allows the sales team to achieve account-based marketing by creating similarities between prospects and customers (Pophal, 2023). 
Filtered view on  local authority, showing use case for consultant,
 







Further drilldown using the Laso Button on the map.
 










The dashboard also allowed the marketing team to produce campaigns with specific messaging, as well as see the effects of this visually as enquiries and pilots of the company were visible on the map via filtering. Showcasing successful campaigns visually, which was not available before (Berinato , 2023).
 
Results
The dashboard allowed the creation of a new “partner” schools to be identified, these are customers who are good users in particular areas that can help boost the number of referrals to the business. This was able to be achieved by identifying high users within a low using geographical area.  This led to an increase in referrals from 5 per quarter to 15 per quarter. The strength of these leads is considerably higher than other leads for example the average win rate for all leads is 8% for referrals it is 32%. With the increase in referrals trusted enquiries can be prioritised and the company can gain customers quicker.
The dashboard allowed the marketing team to identify key that needed specific marketing techniques based on the market share and spread of customers and prospects in the area. They utilised the characteristics to provide further context in marketing materials, allowing them to put out targeted marketing campaigns to a wider audience. This was not possible before, due to the data being lost in the CRM and a lack of understanding on how to compare this data between areas and Local Authorities (Berinato , 2023) (Altendeitering et al. 2024) . 
Recommendations for the future
The project would benefit from assigning clustering methods based on the customers and the size of packages they purchased. Then looking at common characteristics within these groups and creating marketing clusters. This can then be added as a selection filter to help the marketing team gain insights into the areas and plan the most effective approach to marketing based on our existing clusters (Lui and Ong, 2008).
The Sales Team requested a new feature to be added, this being the potential value for the customers. This would benefit from a potential lead scoring system to be applied to the prospects based on the likelihood of them purchasing due to their characteristics like Size, Funding Status, EAL and Pupil premium %. This would be carried out using logistic regression on historic enquiries, using their characteristics as the potential variables that influence the likelihood of the product being purchased.









Bibliography
Alam, M., Gale, A., Brown, M. and Khan, A.I., 2010. The importance of human skills in project management professional development. International Journal of Managing Projects in Business, 3(3), pp.495-516.
Alhamadi, M., Alghamdi, O., Clinch, S., & Vigo, M. (2022, October). Data Quality, Mismatched Expectations, and Moving Requirements: The Challenges of User-Centred Dashboard Design. In Nordic Human-Computer Interaction Conference (pp. 1-14).
Altendeitering, M., Fraunhofer, I. S. S. T., & Guggenberger, T. M. (2024). Data Quality Tools: Towards a Software Reference Architecture.
Berinato, S., 2023. Good Charts, Updated and Expanded: The HBR Guide to Making Smarter, More Persuasive Data Visualizations. Harvard Business Press.
Data Protection Act 20118, c. 12.  Available at : https://www.legislation.gov.uk/ukpga/2018/12/contents/enacted (Accessed: 1 April 2023)
Freudenreich, T., Furtado, P., Koncilia, C., Thiele, M., Waas, F., & Wrembel, R. (2013). An on-demand ELT architecture for real-time BI. In Enabling Real-Time Business Intelligence: 6th International Workshop, BIRTE 2012, Held at the 38th International Conference on Very Large Databases, VLDB 2012, Istanbul, Turkey, August 27, 2012, Revised Selected Papers 6 (pp. 50-59). Springer Berlin Heidelberg.
Liu, H.H. and Ong, C.S., 2008. Variable selection in clustering for marketing segmentation using genetic algorithms. Expert systems with applications, 34(1), pp.502-510.
Melitz, M.J. and Ottaviano, G.I., 2008. Market size, trade, and productivity. The review of economic studies, 75(1), pp.295-316.
Orlovskyi, D.L. and Kopp, A.M., 2020. A business intelligence dashboard design approach to improve data analytics and decision making. CEUR Workshop Proceedings.
Pophal, L., 2023. Account-Based Marketing Refines Its Focus: Individual buyers will continue to replace larger accounts as marketing targets. CRM Magazine, 27(5), pp.20-24.
Rajanen, D., & Rajanen, M. (2022). Student-centred design of learning dashboards. EDULEARN22 Proceedings.
Saha, D. (2020). ‘How The World Became Data-Driven, And What’s Next’, Forbes, Available at: https://www.forbes.com/sites/googlecloud/2020/05/20/how-the-world-became-data-driven-and-whats-next/ (Accessed: 26 March 2024).
Stadler, J.G., Donlon, K., Siewert, J.D., Franken, T. and Lewis, N.E., 2016. Improving the efficiency and ease of healthcare analysis through use of data visualization dashboards. Big data, 4(2), pp.129-135.
