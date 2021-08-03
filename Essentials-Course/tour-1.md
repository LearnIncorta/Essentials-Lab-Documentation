#Creating a Data Source
Now that you are signed in as the **myAdmin** user, you are ready to create a new Data Source, ds_AdvWorks.


- In the Navigation bar, select **Data**. 
- In the Actions bar, select **+New**. 
- In the Choose a Data Source dialog, in Search for Data Source Types, enter My.
- In Databases, select **MySQL**.
- In the New Data Sourcedialog, specify the following Data Source properties:
  - Data Source Name = ds_AdvWorks
  - Username = incorta
  - Password = Incorta#1
- Connection String = jdbc:mysql://127.0.0.1:3306/adventureworks
- To test, select Test Connection, verify the successful connection, and then select Ok.

##Share the Data Source
In Incorta, sharing controls permission access to an object such as a Data Source.  The following animations details how to share the resource with two groups: grp_Admins and grp_Developers. The direct instruction follows below.

- In  Data, in External Data Sources, select **ds_AdvWorks** row.
  - For the row, select the **Sharing** icon.
- In the Share dialog, in With, for Search names, emails, and groups, first enter grp, then select **grp_Admins**.
- To open the Permissions menu, select the **Permission icon (Eye)**.
- In the menu, select **Can Edit**.
- To commit these changes, select **Share**.
- In Search names, emails, and groups, first enter grp, then select** grp_Developers**,
- To open the Permissions menu, select the **Permission icon (Pen)**.
- In the menu,  select Can **View**.
- To commit these changes, select **Share**.
- To close the Share dialog, select **Close**.
