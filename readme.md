Tabella auto usate di un concessionario

Nome Tabella:       
Used_Cars

Colonne Tabella:    
    - id                   |    BIGINT          |   PK  AI
    
    - car_company          |    VARCHAR(30)     |   NOTNULL
    - model_number         |    CHAR(20)        |   NOTNULL 
    - sub_model_number     |    VARCHAR(20)     |   NULL
    - seller               |    VARCHAR(100)    |   NOTNULL
    - seller_info          |    TEXT            |   NULL
    - price                |    DECIMAL(7,2)    |   DEFAULT(0)
    - age                  |    CHAR(2)         |   NULL
    - color                |    VARCHAR(20)     |   NULL
    - weight               |    DECIMAL(8,2)    |   
    - cylinders            |    INTEGER(5)      |   NULL
    - service_history      |    TEXT            |   NULL
