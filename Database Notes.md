# Database Notes

Created: Jan 16, 2021 12:18 PM
Working On Now: No

Notes

[Formula symbols ](https://www.notion.so/Formula-symbols-d2b3cb2615bd4b7ca31163119e21378a)

[Questions](https://www.notion.so/Questions-2250a78393a749c8a3a8d3b41e79b2c0)

[to anki](https://www.notion.so/to-anki-7115ffdf61f44011ac680c09de0b16ae)

- Aggregation

    The result of an aggregate function (sum, count, average, minimum, maximum, etc.) applied to a bag of values. 

- Business Intelligence

    A set of methods and tools for interactive data analysis used primarily by business administrative staff to understand and analyze business performance in order to obtain useful information to support unstructured decision making. The term intelligence is used with the meaning of investigating to ﬁnd out some.thing interesting, like in Intelligence Service. The business intelligence methods and tools are of the following types: 

    – Reports. Reporting is considered the basic level of decision support.

    – Multidimensional data analysis. Data analysis is usually accomplished inter.actively with some kind of data analysis tool.

    – Exploratory data analysis. This data analysis technique is very different from reports and multidimensional analysis: it uses what is called a discovery tech.nique of useful data models with data mining algorithms.

- Computerized Information System

    A subset of an information system that use a variety of technologies to process information. Conformed Dimension A dimension shared by several fact tables.

- Constellation schema

    The relational schema of a data warehouse with several fact tables that share dimensional tables.

- Cube

    A multidimensional cube model (data cube) represent facts with n dimensions by points (a cell) in an n-dimensional space. The cells of the cube contain data measures and the edges of the cube represent the data dimensions. Although a cube implies only 3 dimensions in geometry, a data cube may repre.sent any number of dimensions. Some vendors provide OLAP servers that implement the fact table as a data cube using a specialized data structure. Such implementations are referred to as MOLAP (Multidimensional OLAP). 

- Cuboid

    Let us assume that each dimension domain is extended with an additional value “.”. This value has the intuitive meaning “all”, and it represents summarization along the dimension in which it appears, called cuboid. A cube can be extended with new “borders” made of cells containing the value of aggregate functions. The extended cube is a generalization of a cross-tabulation, which is 2-dimensional, to n dimensions. To speed up data analysis, commercial data cube systems precompute all or some of the cuboids and store them as materialized views of the data cube. 

- Data, Information, Knowledge

    Data is the representation of certain facts that a computer records, stores and processes. Data, or a condensed form of them, become information when are in.terpreted in a certain context. Information becomes knowledge when it provides insight upon which the recipient, on the base of his experience, competence, and attitude, can make informed and effective decisions and take proper actions. 

- What is a data model in case of db?

    A data model is a set of abstraction mechanisms, with associated operators and implicit
    integrity constraints, used to define a database schema.

- What is ODM?

    object data model (ODM), with abstraction mechanisms to model the user’s conceptualization of the application domain, naturally and directly

    The basic abstraction mechanisms of an object data model (ODM) are: object, type, class, relationship, inheritance, type hierarchies, and class hierarchies.

- What is an **object** in ODM?

    An object is the computer representation of certain facts about an entity of the observed world. An object is a software entity which has an internal state (instance variables) and it is equipped with a set of local operations (methods) to manipulate that state. The request to an object to execute an operation is called a message, to which the object can reply. The structure of an object state is modeled by a set of variables (or attributes) which can have values of arbitrary complexity, including other objects which become components of the object. When the state of an object can only be accessed and modified through operations associated to that object, we say that the object is a data abstraction or that it encapsulate its state.

    Finally, each object is distinct from all other objects and has an identity that persists over time, independently of changes to the value of its state, e.g., if X and Y are identifiers bound to objects of type T, X will be equal to Y if they are bound to the same object. For instance, the object representing the person John is different from any other object representing another person, but will remain the same even if his address or some other attribute changes.

- What is an **object type** in ODM?

    An object is an instance of a type defined with a generative type constuctor, i.e. each object type definition produces a new type, which is different from any other previously defined types. An object type describes the state fields and the implementation of methods of its possible instances. An object type definition introduces a constructor of its instances, and so an object can be constructed only after its object type definition has been given.

    In the object programming context this approach to objects is called class-based since the description of objects is called a class; we prefer the term “type” since we will use “class” with a different meaning according to the database tradition.

    The signature $**\Downarrow\tau$** of an object type $\tau$ is the set of label-type pairs of the messages which can be sent to its instances.
    Each object is a value of a certain type and objects of the same type have the same properties, i.e. they have the same structure and the same operations, specified by the type definition. The operations (the methods) to manipulate the state are specified by giving a specific implementation (concrete behavior), but in the following they will not be considered because are beyond the scope of this notes.
    The type mechanism makes it possible to create many objects of the same type using an appropriate constructor.
    The following example shows a graphical representation of an object type.1

    ![Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-17_at_09.39.11.png](Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-17_at_09.39.11.png)

- Data Mart

    A database that has the same characteristics of a data warehouse, but it is focused on a single measurable business process to analyze, and so it has only one fact.

- Data Mining

    An exploratory data analysis technique to discovery useful data models with spe.cialized algorithms.

- Data Warehouse

    A decision support database with historical, nonvolatile data, pulled together pri.marily from operational business systems, structured and tuned to facilitate anal.ysis of the performance of key business processes, worthy of improvement. 

    The ﬁrst and still now the most widely cited deﬁnition of data warehouse was provided by William Inmon in 1990: “A data warehouse is a subject-oriented, integrated, nonvolatile, and time-varying collection of data in support of man.agement’s decisions.” 

    A fundamental axiom of the data warehouse is that data is both read-only and non-volatile. As the amount of data within the data warehouse grows, the value of the data increases, allowing a user to perform longer-term analyses of the data. Whereas the operational data is generally real-time or near real-time, data within the data warehouse is historical, since the data warehouse is used primarily for reporting and analyzing relatively large volumes of historical data in an effort to decide what to do in the future.

- Data Warehousing

    The process used to organize data in a data warehouse and then allow users to analyze them with business intelligence tools.

- Data Warehouse Management System (DWMS)

    A specialized software for creating and managing large amount of nonvolatile data efﬁciently and allowing it to be analyzed with OLAP queries. There are three broad directions that have been taken to develop this specialized systems: Rela.tional OLAP (ROLAP), Multidimensional OLAP (MOLAP), Column-Oriented OLAP.

- DSS, Decision Support System

    A software system used to support decision-making processes within an organi.zation. While an operational system is for performing the business, a decision support systems is for analyzing the business.

- Dice

    An operator to selects a subcube of a given cube with a selection on two or more dimensions. The operator does not make aggregations on the data cube. 

- Slice

    An operator to selects a cross section that cut across a cube with a selection on one dimension. The result is a subcube, and so the operator does not make aggregations on a data cube. 

- Dimensional Data Model

    A data model that represents measurements of a process and the independent variables that may affect that process. In a dimensional model, data are orga.nized into multiple dimensions and each dimension contains multiple levels of abstraction deﬁned by concept hierarchies. This organization provides the users with the ﬂexibility to view data from different perspectives. 

- Dimensional Fact Model (DFM)

    A conceptual dimensional data model. 

- Dimension

    One of the perspectives that can be used to analyze the data in a data warehouse.

- Dimensional Table

    The table of a relational database which contains the data for one of the dimen.sions. The dimensional attributes describe individual characteristics of a dimen.sion. The dimension table has a primary key (usually a surrogate one) which is used to connect it to the fact table. The dimension tables in a star schema are intentionally de-normalized. 

- DOLAP (Desktop OLAP)

    A system which manage on a personal computer small amount of data extracted from a multidimensional OLAP server, a DW or an operational DBMS. 

- ERP (Enterprise Resource Planning)

    The meaning of the acronym ERP does not explain the purpose of these systems, which is not the enterprise resource planning, but the integration of business pro.cesses in a single software system that can meet all the information requirements of the company using a centralized database . 

- ETL (Extract, Transform, Load)

    A set of back-end data staging steps that are used to 

    (1) obtain data from operational sources (i.e. the extraction step), 

    (2) cleanse and prepare data for import into the data warehouse (i.e. the transformation step), and 

    (3) actually importing the transformed data into the data warehouse (i.e. the loading step). 

- Fact

    A collection of related data items, consisting of measures and context data. Each fact typically represent a business item, a business transaction, or an event that can be used in analyzing the business or key business processes. The most useful data items are indeed numeric and often additive. 

    In the library, examples of relationships between entities can be the fact that a bibliographic description refers to a book, or more than one book if more than one copy of the same book
    exists, or the fact that the user Smith has borrowed a copy of a particular book.

- Fact Table

    The table of a relational database which contains the individual facts being stored in the data warehouse. There are two types of ﬁelds in a fact table: 

    a) The ﬁelds storing the foreign keys which connect each particular fact to the appropriate value in each dimension; 

    b) The ﬁelds storing the individual fact measures, such as number, amount, or price. 

    The granularity of the fact table is one of the most signiﬁcant design decisions in creating a data warehouse. The facts should be as detailed as possible to allow for the data to be viewed from the greatest number of perspectives. 

- Granularity

    The level of detail of the facts stored in a data warehouse, and so the meaning of a single record in a fact table. 

- Hierarchy

    Dimensional attributes can be arranged into one or more logical structures to analyze data at various levels of detail. For example, the hierarchy among the attributes City and Region of the dimen.sion Location, states that each city belongs to one region and a region generally contains several cities. The multidimensional analysis usually exploits the hier.archy among the dimensional attributes to perform aggregations of the measures at various levels of detail along the dimensions of the data warehouse. For exam.ple, a typical hierarchy is the dimension of time to analyze the facts by year, by quarter, by month or by day. 

- HOLAP (Hybrid On Line Analytical Processing)

    A combined use of Relational OLAP (ROLAP) and Multidimensional OLAP (MOLAP). 

- Information System

    A system whose purpose is to store, process, and communicate information. 

- Key Business Process

    A business process that can be clearly deﬁned, is measurable, and is worthy of improvement. 

- Measure

    A numerical property of a fact useful for evaluating the performance of the pro.cesses to be analyzed. 

- Materialized View

    The results of a query stored and automatically used to facilitate the execution of other more complex queries.

- Metadata

    It is referred to as being the data about data, which deﬁnes all aspects of the data contained in a data warehouse including where it originally comes from, its type, what transformations it has been subjected to, where it has been used and what it means from a business perspective. 

- MOLAP (Multidimensional On Line Analytical Processing)

    OLAP systems that store cuboids in a specialized data structures. 

- OLAP (On Line Analytical Processing)

    A category of database software systems that primarily involves aggregating large amounts of data from a data warehouse. The term was introduced to distin.guish the activities of data analysis from daily activities on business data orga.nized in databases. 

- OLAP Client

    A system that provides interactive tools for multi-dimensional analysis. 

- OLAP Server

    A system that provides a vision of data to be analyzed as a cube. 

- OLTP (On Line Transaction Processing)

    A category of database software systems that typically involves processing trans.actions in real time. 

- Operational Systems

    A transaction processing systems to process operational data. 

- ROLAP

    (Relational On Line Analytical Processing) An OLAP system that store data and materialized views in a relational DBMS. 

- Drill-down

    An operator to have an aggregated view of the data to a higher level of detail in two ways: by moving down along a dimensional hierarchy level or by adding a dimension of analysis. 

- Roll-up

    The operator performs aggregation on a data cube, either climbing up a concept hierarchy for a dimension or by dimension reduction. 

- Schema

    The deﬁnition of the logical structure of a database or a data warehouse. 

    To construct a conceptual model of an information system we define the schema, a collection of time-invariant definitions which model respectively 

    (a) the structure of admissible data, as well as integrity constraints, 

    (b) the procedural knowledge (intensional aspects). The creative part of conceptual modeling is deciding what collection of entities, relationships, and constraints to include in the schema to model the observed reality.

- Star Schema

    The relational schema of a data warehouse with 

    (1) a large central table (fact table) containing the bulk of the data without redundancy, and

     (2) a set of smaller attendant tables (dimension tables), one for each dimension.

- Snowﬂake Schema

    A variant of the star schema, where some dimension tables are normalized, thereby further splitting the data into additional tables. 

- Model

    A model is used for explicative or descriptive purposes (descriptive models), 

    to predict actions and events (predictive models),

    or to provide recommended courses of actions (normative models).

- Symbolic model

    A symbolic model is a subjective formal representation of ideas and knowledge about some aspects of the real world (domain of discourse), designed to serve an explicit purpose.

- What are three fundamental aspects of symbolic model

    Three fundamental aspects of symbolic model definition must be underlined:
    1. A model is a representation of only some aspects of the real world to serve a purpose of some kind.
    2. The representation is given by a formal language.
    3. The model is the result of an interpretation process which depends on the knowledge possessed by the designer about the portion of the real world modeled.

- What do Descriptive models do?

    A model is used for explicative or descriptive purposes (descriptive models), 

- What do Predictive models do?

    to predict actions and events (predictive models),

- What do Normative models do?

    to provide recommended courses of actions (normative models).

- What do we need to conside when we are making models?

    When constructing a computerized information system, the reality to be modeled is generally considered with respect to: concrete knowledge, abstract knowledge, procedural knowledge, dynamics, and communications.

- What is an entity in db?

    An entity is anything for which certain facts should be recorded, independently of the existence of other entities.

    Examples of properties in a library are the user’s name and address. The difference between a property and an entity results from a different interpretation of the represented fact in the
    model: properties are facts which are of interest only because they describe other facts which are considered as entities.

    Entities with the same properties are said to have the same type and they are classified into the same collection (called also entity set). For instance, John, Mary, and Ann may be classified into the collection Persons based on the fact that they have the same properties and represent humans

    .
    Collection of entities with the same type are certainly an important aspect of the knowledge
    about the reality to be modeled, but much more information is carried by facts which establish
    associations among entities.

- What is an property of an entity in db?

    A property is a fact about an entity which is not meaningful in itself, but only because it describes an entity of interest.

    Examples of properties in a library are the user’s name and address. The difference between
    a property and an entity results from a different interpretation of the represented fact in the
    model: properties are facts which are of interest only because they describe other facts which
    are considered as entities.

    Entities with the same properties are said to have the same type and they are classified into
    the same collection (called also entity set). For instance, John, Mary, and Ann may be classified into the collection Persons based on the fact that they have the same properties and represent humans

    .
    Collection of entities with the same type are certainly an important aspect of the knowledge
    about the reality to be modeled, but much more information is carried by facts which establish
    associations among entities.

- What is an relation in db?

    A relationship is a fact which correlates independent entities. As with entities, a collection of similar relationships is called relationship set.

- What is an relationship set in db?

    A relationship is a fact which correlates independent entities. As with entities, a collection of similar relationships is called relationship set.

    In the library, examples of relationships between entities can be the fact that a bibliographic description refers to a book, or more than one book if more than one copy of the same book
    exists, or the fact that the user Smith has borrowed a copy of a particular book.

- What do structural constraints or properties mean in db?

    Relationships usually have certain constraints that limit the possible correlated entities. The
    most important ones are the so called structural constraints or properties:

    – Cardinality, one or many, to specify how many entities of one collection may be associated with entities of another collection.
    – Partecipation, total or partial, to specify whether an entity of one collection can have entities of another collection associated to it.

- What do Cardinality mean in db?

    – Cardinality, one or many, to specify **how many entities** of one collection may be associated with entities of another collection.

- What do Partecipation mean in db?

    – Partecipation, total or partial, **to specify whether** an entity of one collection can have entities of another collection associated to it.

- What are the types of relationships we have in db?

    one-to-many or 1:N

    For example, a book is borrowed by at most one person, but a person can borrow several
    books (the relationship is said to be one-to-many or 1:N).

    many-to-many or N:M

    In contrast, the relationship Appears In between authors and bibliographic descriptions, in which an author has written several books and a book has been written by several authors, is said to be many-to-many or N:M.

    total or partial

    A book must be related to a bibliographic description (total), but a bibliographic description may not be related to a library book (partial).

- What does relationship 1:N mean in db?

    For example, a book is borrowed by at most one person, but a person can borrow several
    books (the relationship is said to be one-to-many or 1:N).

- What does relationship one-to-many mean in db?

    For example, a book is borrowed by at most one person, but a person can borrow several
    books (the relationship is said to be one-to-many or 1:N).

- What does N:M relationship mean in db?

    In contrast, the relationship Appears In between authors and bibliographic descriptions, in which an author has written several books and a book has been written by several authors, is said to be many-to-many or N:M.

- What does many-to-many relationship mean in db?

    In contrast, the relationship Appears In between authors and bibliographic descriptions, in which an author has written several books and a book has been written by several authors, is said to be many-to-many or N:M.

- What does partial relationship mean in db?

    A book must be related to a bibliographic description (total), but a bibliographic description may not be related to a library book (partial).

- What does total relationship mean in db?

    A book must be related to a bibliographic description (total), but a bibliographic description may not be related to a library book (partial).

- What do Concrete knowledge mean in db?

    Concrete knowledge concerns specific facts known of the system to be represented. Adopting a simplified point of view, we will assume that the reality consists of entities, with certain characteristics or properties, and of relationships between the entities, which evolve over time.

    Basicaly having the data as well as the metadata.

- What do Abstract knowledge mean in db?

    Abstract knowledge concerns general facts which impose restrictions on the admissible values of the concrete knowledge and on the way in which the values of the concrete knowledge can evolve in time, or expresses rules to derive new information (integrity constraints).

    It sets the rules of how information will be put in the future

    In the library, examples of abstract knowledge are 

    (a) the user properties Name, and Address, which must have values of type string, whereas the BirthDate property will have values of type date, 

    (b) a book can be borrowed for two weeks, and two one-week extensions are allowed, if the extension is performed before the due data, 

    (c) any person may have on loan at most five books at any time; the title of a book cannot be changed 

    (d) the age of a person is computed as the difference between the current year and the year of birth.

- What does Procedural knowledge mean in db?

    Procedural knowledge concerns the elementary actions (or operations) in the application environment which are applied to concrete knowledge to cause changes. It must be understood that concrete knowledge is about the structure of the entities and procedural knowledge is about their behavior. Moreover, while abstract knowledge imposes restrictions on possible values of concrete knowledge, procedural knowledge imposes restrictions on the possible ways in which concrete knowledge can be used or modified.
    Examples of elementary actions for a university student are: **enroll, graduate, change ad
    dress, and change telephone number**.

- What does dynamics concerns in realtion to db?

    Dynamics concerns how concrete and procedural knowledge can be used to model complex activities in the application environment.

    Dynamics regards changes in the reality triggered by events and accomplished by standard procedures. 

    An example of such a procedure in a university situation is: when a professor moves to another university, then stop salary; exclude the professor from mailing lists (usually more than one); for each course held by the professor, start procedure to assign new professor; for each commission of which the professor was a member, start procedure for new nominations; etc.

- What does communications concerns in realtion to db?

    communications concern how information is entered in the information system and is
    exchanged among members of the organization.

- **Normalization of Database what does it mean?**

    Database Normalization is a technique of organizing the data in the database. Normalization is a systematic approach of decomposing tables to **eliminate data redundancy**(repetition) and undesirable characteristics like Insertion, Update and Deletion Anomalies. It is a multi-step process that puts data into tabular form, removing duplicated data from the relation tables.

    Normalization is used for mainly two purposes,

    - Eliminating redundant(useless) data.
    - Ensuring data dependencies make sense i.e data is logically stored.

    [1NF, 2NF, 3NF and BCNF in Database Normalization | Studytonight](https://www.studytonight.com/dbms/database-normalization.php)

- What does decomposing tables mean in dbms?

- What is Insertion Anomaly in dbms?

    Suppose for a new admission, until and unless a student opts for a branch, data of the student cannot be inserted, or else we will have to set the branch information as **NULL**.

    Also, if we have to insert data of 100 students of same branch, then the branch information will be repeated for all those 100 students.

    These scenarios are nothing but **Insertion anomalies**.

- What is data redundancy in dbms?

    Repetition of data 

- Problems created by data redundancy in dbms?
    - Insertion Anomaly
    - Deletion anomaly
    - Updation anomaly
- What is Updation Anomaly in dbms?

    What if Mr. X leaves the college? or is no longer the HOD of computer science department? In that case all the student records will have to be updated, and if by mistake we miss any record, it will lead to data inconsistency. This is Updation anomaly.

- What is Deletion Anomaly in dbms?

    In our **Student** table, two different informations are kept together, Student information and Branch information. Hence, at the end of the academic year, if student records are deleted, we will also lose the branch information. This is Deletion anomaly.

- What is First Normal Form (1NF)?

    The 1st(First) Normal Form which is more like the Step 1 of the Normalization process. The 1st Normal form expects you to design your table in such a way that it can easily be extended and it is easier for you to retrieve data from it whenever required.

    - **Rule 1: Single Valued Attributes**
    - **Rule 2: Attribute Domain should not change**
    - **Rule 3: Unique name for Attributes/Columns**
    - **Rule 4: Order doesn't matters**

- What are the **Rules for First Normal Form** in dbms?

    The first normal form expects you to follow a few simple rules while designing your database, and they are:

    ### **Rule 1: Single Valued Attributes**

    Each column of your table should be single valued which means they should not contain multiple values. We will explain this with help of an example later, let's see the other rules for now.

    each cell should have one value so it cannot be like (vba,java)

    ---

    ### **Rule 2: Attribute Domain should not change**

    This is more of a "Common Sense" rule. In each column the values stored must be of the same kind or type.

    **For example:** If you have a column `dob` to save date of births of a set of people, then you cannot or you must not save 'names' of some of them in that column along with 'date of birth' of others in that column. It should hold only 'date of birth' for all the records/rows.

    one column should have same type of values

    ---

    ### **Rule 3: Unique name for Attributes/Columns**

    This rule expects that each column in a table should have a unique name. This is to avoid confusion at the time of retrieving data or performing any other operation on the stored data.

    If one or more columns have same name, then the DBMS system will be left confused.

    Make unique name for the columns

    ---

    ### **Rule 4: Order doesn't matters**

    This rule says that the order in which you store the data in your table doesn't matter.

    order of the data is not important

    ---

- **What is** Second Normal(2NF) **Form?**

    For a table to be in the Second Normal Form, it must satisfy two conditions:

    1. The table should be in the First Normal Form.
    2. There should be no Partial Dependency.
- What is Dependency in dbms?

    Hence we can say a Primary Key for a table is the column or a group of columns(composite key) which can uniquely identify each record in the table.

    It means you can a column by using which we can fecth the data of the row easly

- What is Partial Dependency in dbms?

    Partial Dependency, where an attribute in a table depends on only a part of the primary key and not on the whole key.

    when we have a primary key which is a combination of two primary keys in this situation we have some attributes which are not complitly dependent on the whole key.

    ![Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-20_at_15.24.48.png](Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-20_at_15.24.48.png)

    ![Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-20_at_15.25.14.png](Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-20_at_15.25.14.png)

    ![Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-20_at_15.25.45.png](Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-20_at_15.25.45.png)

    ^^ this is partial dependency

- **What is** Third Normal Form (3NF) **Form?**

    Third Normal Form is an upgrade to Second Normal Form. 

    - When a table is in the Second Normal Form and
    - has no transitive dependency, then it is in the Third Normal Form.
- What is transitive dependency in dbms?

    Transitive Dependency. When a non-prime attribute depends on other non-prime attributes rather than depending upon the prime attributes or primary key.

    When a non primary key is dependet on another non primary key.

    ![Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-20_at_15.28.28.png](Database%20Notes%20ad9705b2eaa147cfade9fb3ad940f374/Screenshot_2021-01-20_at_15.28.28.png)

- What is the Advantage of removing Transitive Dependency **in dbms?**

    The advantage of removing transitive dependency is,

    - Amount of data duplication is reduced.
    - Data integrity achieved.
- What is data integrity in dbms?

    Data integrity refers to the accuracy and consistency (validity) of data over its lifecycle.

    For example, a user could accidentally try to enter a phone number into a date field. If the system enforces data integrity, it will prevent the user from making these mistakes.

- **What is** Boyce-Codd Normal Form (BCNF)?

    Boyce-Codd Normal Form or BCNF is an extension to the third normal form, and is also known as 3.5 Normal Form.

    [Boyce-Codd Normal Form (BCNF)](https://www.studytonight.com/dbms/boyce-codd-normal-form.php)