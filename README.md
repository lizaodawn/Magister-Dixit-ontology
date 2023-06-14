Daniel Oltean, Agni Vourtsi, and Dawn Zhuang, Linked Open Data in manuscript collections: An ontology for Magister Dixit dataset

This project focuses on Magister Dixit collection, a group of manuscripts containing students’ notes from the Old University of Leuven, available at: https://github.com/KULeuvenDigitalisering/Magister-Dixit-Collection-Dataset. To describe this dataset, we build an ontology based on Erlangen Conceptual Reference Model (ECRM, http://erlangen-crm.org/current-version) and Erlangen Functional Requirements for Bibliographic Records object-oriented (EFRBRoo, http://erlangen-crm.org/efrbroo) models.

Our model aims to provide a framework for the manuscripts' collection through three main concepts: 
-	manifestation singleton = physical object (efrbroo:F4_Manifestation_Singleton);
-	creation event (F28_Expression_Creation);
-	expression = intellectual content (efrbroo:F2_Expression). 

The links between the first concept and the other two are assured by two properties that define the physical object in terms of:
-	event/process of creation of (efrbroo:R18i_was_created_by);
-	content (efrbroo:R42_is_representative_manifestation_singleton_for). 

We included short descriptions of ontology's main classes and properties via rdfs:comment. 

We also implemented one instance (Magister_Dixit_3 = Abdij van Berne Heeswijk Ms. K1) to illustrate the use of all the classes and properties designed.
