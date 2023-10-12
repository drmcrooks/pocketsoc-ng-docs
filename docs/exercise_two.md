# Exercise 2

In this exercise, we'll setup the OpenSearch Dashboards interface. If you're familiar with OpenSearch Dashboards then feel free to skip ahead, otherwise follow these steps - this is a fresh installation.

1. Log in using the credentials on the front page
![OpenSearch Dashboards login](images/dashboards_1.png)
2. Select "Explore on my own" (Zeek will provide the data!)
![OpenSearch Dashboards explore](images/dashboards_2.png)
3. Dismiss the "new Dashboards" notice
![OpenSearch Dashboards dismiss](images/dashboards_3.png)
4. Confirm "private tenant"
![OpenSearch Dashboards private](images/dashboards_4.png)
5. You should see this view
![OpenSearch Dashboards view](images/dashboards_5.png)
6. Click the three bar menu in the top left and select “Discover”
![OpenSearch Dashboards discover](images/dashboards_6.png)
7. Now we need to create an *index pattern* to select which records to display. Click on “Create index pattern”
![OpenSearch Dashboards index](images/dashboards_7.png)
8. You should see something like the following, with `opensearch-logstash-zeek-2023.10.12`
![OpenSearch Dashboards records](images/dashboards_8.png)
9. Enter `opensearch-logstash-zeek-*` (this will match multiple days): Next step.
![OpenSearch Dashboards enter](images/dashboards_9.png)
10. Select @timestamp in the Time field
![OpenSearch Dashboards timestamp](images/dashboards_10.png)
11. You should see something like this
![OpenSearch Dashboards pattern](images/dashboards_11.png)
12. From the menu select Discover again: at the top left of the window you’ll see “Select a datasource” : choose the index pattern you just created
![OpenSearch Dashboards datasource](images/dashboards_12.png)
131. You should see some data: time to explore!
![OpenSearch Dashboards data](images/dashboards_13.png)








