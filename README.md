# DeepMirror

Add all the TDC ADME dataset to ChEMBL Postgres DB and make it accessible to the ML Team.

---

## Quick Start

1. Download the repository.
2. Add your DB credentials to the ```aws_database.ini``` file.
3. Open the ```ChEMBL_Task1.ipynb``` in jupyter notebook or google colab. (Note: If you are using colab; please upload all the other files on cloud)
4. Follow the instructions in the notebook and execute query to fetch the data.
5. You can also access the DB with ```pgAdmin``` using you credentials.

---

## Some issues to know

1. The DB is hosted on AWS Cloud on a ```FreeTier``` package. 
2. This task is just for demostration purpose and at times fetching the data could be slow depending the query complexity.
3. Please be mindful when executing the query; using ```LIMIT``` to fetch data can help.
4. Additional information can be found for ```ChEMBL```: https://www.ebi.ac.uk/chembl/ & ```Therapeutics Data Commons(TDC)```: https://tdcommons.ai/single_pred_tasks/adme/
5. If there is any other issue or doubt; please reach out to me at saurabhhebbalkar@gmail.com
