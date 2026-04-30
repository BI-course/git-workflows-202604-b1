# Research on Star Schema
# Introduction
A data warehouse is a system that stores and analyzes large amount of data in an organization. Organizations use them for Business Intelligence, reporting and decision making. Example of data stored can be customer trends, sales history and revenue analysis. A data warehouse combines data from multiple databases known as data Marts, transforms the data then loads them into a data warehouse through the ETL process data is cleansed, standardizes and loaded into the data warehouse for analysis. To organize data effectively for the analytical process a data warehouse uses various schemas such as star schema, snowfake schema , galaxy schema etc. Among all the schemas star schema is the most widely used because of its simplicity and its suitability for multidimensional analysis. My research will mainly focus on star schemas structure, components, and significance in Business Intelligence.
# Literature Review
Star schema as the most widely adopted schema design in data warehousing and Business Intelligence. Immon established that the data warehouse wa subjected orinted, non volatile aand subject oriented and after which he provided dimensional schema designs and that is how star schema was later developed. Kimball's dimensional modeling approach introduced the star schema as a design pattern for analytical environments bacause it reduces query complexity and delivers faster results that normal relational models.
# Theoretical Framework
The star schema is a multidimensional model which organizes data as a cube where each axis represents a business dimension such as Product, Time, or Region. In a star schema the cube is implemented relationally through a central table called a fact table and it stores quantitative measures and references each surrounding dimension table and all tables are connected via a foreign key hence forming a star shaped structure. Dimension tables in the star schema are flat and wide structures so that it reduces the number of joins needed in analytical queries.

# Empirical Framework

Empirical evidence from both industry practice and academic research demonstrate that the star schema is duperior for analytical query performance instead of using normalized query designs in the Business intelligence environment. The advantsge of a star schema is from its denormalized dimension tables which minimize costly join operations and deliver faster query response times when accessed through BI tools such as Microsoft Power BI and Tableau.

# Conceptual framework
The star schema is built around two core components a central fact table and a set of surrounding dimension tables which are connected by foreign key hence giving the shema the characteristic of a start shaped. The fact table stores quantitative business metrics such as revenue, quantity sold, and discount. Each row represents one business event at the defined grain and holds foreign keys referencing each dimension table. Because dimension tables are kept flat and denormalized, SQL queries against a star schema require only a single join between the fact table and any dimension table, making queries straightforward for both BI tools and business analysts. 



