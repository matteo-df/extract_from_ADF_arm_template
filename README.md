# Extract Pipelines from a complete ARM Template of Azure Data Factory

Starting from a full ARM Template exported from Azure Data Factory, it is possbile to extract only the useful parts related to the pipelines of interests.

It is required to only indicate the names of the main pipelines and the names of the Private Endpoints (if used): any additional pipeline invoked from the main pipelines and all the dependencies (linked services, datasets, integration runtimes ecc..) are automatically detected and mantained in the ARM Template.