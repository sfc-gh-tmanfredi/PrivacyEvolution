# Privacy Evolution Demo Setup

## This demo  requires 2 Snowflake accounts: One acting as the Provider, another acting as Consumer
## Download the *.csv and *.ipynb files from this repo and execute the following steps:

(From Snowsight on Provider account)
1. Under the Data tab in the left menu, Click Databases
2. Click database PRIVACYEVOLUTION and schema GLOBALSALES
3. In the upper right, click the Create dropdown and select Table then From File
4. Drag your *.CSV (customer_provider.csv) to the center of the screen and drop. You can alternatively click Browse and locate your file
5. On the Load Data into Table screen, go to the bottom. Keep "Create New Table" selected. Enter "customer" under the Name field and click Next. This will take you to a panel that lists all columnms. Leave all default values as-is and click Load.
6. You should see a message that 500 rows were successfully loaded.
7. Create a Notebook
- Projects->Notebooks
- Click the dropdown next to +Notebook on the upper right. Then click "Import .ipynb"
- Import the notebook file ProviderDemo.ipynb that was downloaded from this repo

8. Repeat steps 1-6 on the Consumer account using the file customer_consumer.CSV in step 4
9. Repeat step 7 on the Consumer account using the notebook file ConsumerDemo.ipynb
