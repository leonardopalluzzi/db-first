# db first

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## table name: 'cars'

## table columns:
- id: INT / BIGINT - PRIMARY KEY - UNIQUE - AUTO_INCREMENT
- name: VARCHAR(255) - NOTNULL
- model: VARCHAR(255) - NOTNULL
- price: DECIMAL(4, 2) - NULL
- cover: VARCHAR(255) - DEFAULT(VARCHAR(placeholder.png))
- production_year: DATE - NULL
- registration_year: DATE - NOTNULL
- color: VARCHAR(255) - NULL
- paint_type: VARCHAR(255) - NULL
- km - MEDIUMINT(16.777.215) - NOTNULL
- gear_type: VARCHAR(10) - NOTNULL
- gear_number: TINYINT - NOTNULL
- empty-weight: SMALLINT - NOTNULL
- emission_class: VARCHAR(50) - NOTNULL
- fuel_type: CHAR(10) - NOTNULL
- consumption: VARCHAR(10) - NULL
- horse_power: TINYINT - NULL
- kw: TINYINT - NULL
- displacement: SMALLINT - NULL
- cilinders: TINYINT - NULL
- conditions: VARCHAR(100) - NOTNULL
- previous_owners: TINYINT - NULL
- description: TEXT(1200) - NULL
- body: VARCHAR(10) - NOTNULL
- traction: VARCHAR(10) - NULL
- seats: TINYINT - NULL
- doors: TINYINT - NULL
- warranty: TINYINT(0 o 1) - DEFAULT(1)