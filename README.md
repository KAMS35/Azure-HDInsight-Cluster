# Azure HDInsight Cluster

This is Prompt 2 and will contain the following:
* Creating an HDInsight cluster
* Submitting a PySpark script using Jupyter
* Transferring results to a blob storage
* Deleting the HDInsight cluster

## 1] Creating a HDInsight Cluster
1. Select "HDInsight" in the section "Intelligence + analytics" as given in the screenshot below. ![Select HDI](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/1.select%20HDInsight%20cluster.png)You can either select "Quick Create" or "Custom" option based on your requirements. The quick creat option can also be pulled up by a search on the Azure portal. ![Quick Create](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/1.a.quick%20create.png)

2. Enter the basic details such as, the Cluster name, Choose Cluster Type as 'Spark', Login username, Password for the cluster and the Secure shell. You can choose the existing resource group or creat a new one in this step. ![Basics](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/2.%20enter%20details.png) 

3. Once you configure all the basic details as required, Click "Next".  ![Basics2](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/3.%20basics%20details.png)

4. In the Storage settings, choose an existing storage account or create a new storage account and click "Next". ![Storage](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/4.%20storage%20details.png)

5. Similarly, configure the Application settings and the Cluster Size(here, two worker nodes) as per the requirements and review them in this "Cluster Summary" section. Finally click on "Create". ![Cluster Summary](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/5.%20summary%20of%20details.png)

## 2] Deploying a job in HDInsight using Spark
1. Now the HDInsight Cluster will be deployed into the running stage and can be monitored from the dashboard. ![Deploying](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/6.%20Deploying%20HDInsight.png)  ![Running](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/7.%20HDI%20running.png)

2. You can view the number of cores that has been employed for this job by this comparison chart. Here, we have a total of 60 crores for this free-subscription out of which, 24 cores are used for this cluster. ![Cores](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/8.%20cores.png) 

3. You can also view the statistics of the performance and usage by different jobs by the help of Ambari. ![charts](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/9.%20charts.png)

## 3] Results
The implementation of Predictive analysis for a sample data was attempted on the food data. (https://kamatchidevisubramanian.azurehdinsight.net/jupyter/notebooks/PySpark/Spark%20Machine%20Learning%20-%20Predictive%20analysis%20on%20food%20inspection%20data.ipynb)

The overview of the jobs and the activity log is peresented here.
![Overview](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/10.%20results.png)

![Activity log](https://raw.githubusercontent.com/KAMS35/Azure-HDInsight-Cluster/master/screenshots/11.%20activity%20log.png)

## 4] Deleting the HDInsight CLuster
To delete the cluster, simply click on the delete button and enter the name of the cluster in the box. The process might take a while and be sure to save the results before deleting the cluster. 


 
