The repository contains the SQL files used for creating the relational database models. The following procedure was applied to initialize the databases with data obtained from the plWordNet version 2.3 (available at http://nlp.pwr.wroc.pl/plwordnet/download/?lang=pl):

1.  A user called 'plwn' with password 'plwn' should be created in MySQL database. 
	  He should have full access privileges on databases plwn_basic and plwn_mod.
	
2.	SQL scripts sql/plwn_basic_norel.sql and sql/plwn_mod_norel.sql should be executed to create the required schemas.

3.	Both databases (plwn_basic and plwn_mod) should be loaded with data.
			
4. 	SQL scripts sql/plwn_basic_relations.sql and sql/plwn_mod_relations.sql should be executed to add referential constraints and   indexes to the tables. This should be done after p. 3 has completed.


The repository contains also the description of the simple and complex queries included in file queries.txt.
