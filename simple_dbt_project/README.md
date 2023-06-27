
Commands to run the data pipeline:

- dbt seed
- dbt run
- dbt test

I've used the raw data files as seeds to keep things simple. Ideally, these would be already loaded into your data warehouse and that would be your "source".

The general project idea, raw data files and most of the original code can be found here: [https://github.com/josephmachado/simple_dbt_project.git](https://github.com/josephmachado/simple_dbt_project.git), but you will need to modify the models and schema.yml files to work with the raw data. The tutorial that goes along with this project can be found here: [https://www.youtube.com/watch?v=gtZ8h8Aynmw](https://www.youtube.com/watch?v=gtZ8h8Aynmw).
