# NUS-OracleAAPL_Hackathon
This is a modified repository of the Redbull ML Demo from  Oracle. All sections *should* work except for the Django deployment. 

## Developer Journey Map

View each notebook in numeric order:

- 01_0.Formule1_Data_Collection.ipynb
- 01_1.Weather_Data_Collection.ipynb
- 01_2.Qualifying_Data_Collection.ipynb
- 02.Data_Preparation_merging.ipynb
- 03.f1_analysis_EDA.ipynb
- 04.ML_Modelling.ipynb
- 05.ML_Model_Serving.ipynb

## Starting The Web Application

To see the results of the lab, you'll need to start the web server using Terminal.

1. In the menu at the top of the page, select **File->New->Terminal**.
2. Enter the following commands, hitting return after each one (feel free to copy and paste)

        cd /home/opc/redbull-analytics-hol/beginners/web
        source /home/opc/redbullenv/bin/activate
        python3 app.py
3. Open a web browser to the public IP of your Jupyter Lab, but use port 8443 instead of port 8888:

        https://xxx.xxx.xxx.xxx:8443

    The Public IP is the one at which you're currently accessing Jupyter Lab, which we copied from the Running Instances step above.

---

# Additional Resources 
- https://www.youtube.com/watch?v=n4-Azr8xLQE
