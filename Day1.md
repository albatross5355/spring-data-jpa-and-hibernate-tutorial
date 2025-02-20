### Understanding Object Relationa Persistence
 Hibernate, an open
 source ORM service implementation, and Spring Data, an umbrella project from the
 Spring family whose purpose is to unify and facilitate access to different kinds of per
sistence stores, including relational database systems and NoSQL databases.
This chapter explains
 why you need tools like Hibernate and Spring Data and specifications such as the
 Jakarta Persistence API (JPA).

1.1
 What is persistence?
 Most applications require persistent data. Persistence is one of the fundamental con
cepts in application development. If an information system didn’t preserve data when
 it was powered off, the system would be of little practical use. Object persistence means
 individual objects can outlive the application process; they can be saved to a data store
 and be re-created at a later point in time. When we talk about persistence in Java, we’re
 generally talking about mapping and storing object instances in a database using SQL.
 1.1.1 Relational databases
