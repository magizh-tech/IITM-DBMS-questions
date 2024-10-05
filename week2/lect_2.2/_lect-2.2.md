https://youtu.be/D8e1-apWxo8

Here are some questions and answers covering the concepts from the video on relational algebra:

### Questions and Answers:

1. **What is relational algebra in databases?**
   - Relational algebra is a procedural query language that provides a set of operations to manipulate and retrieve data from relational databases. It is foundational for SQL and database theory.

2. **What are the fundamental operations of relational algebra?**
   - The basic operations include **selection** (σ), **projection** (π), **union** (U), **set difference** (−), **Cartesian product** (×), and **rename** (ρ).

3. **What is the selection operation, and how is it used?**
   - The selection operation (σ) retrieves rows from a relation that satisfy a given condition. For example, `σ(age > 30)(Employee)` filters employees older than 30.

4. **How does the projection operation work?**
   - The projection operation (π) retrieves specific columns from a relation. For example, `π(name, age)(Employee)` would return only the name and age columns from the Employee table.

5. **What is the Cartesian product in relational algebra?**
   - The Cartesian product (×) combines all possible pairs of rows from two relations. It is typically followed by a selection to retrieve meaningful data.
   Eg: `R × S` combines every row in R with every row in S. Assume R has m rows and S has n rows, the result will have m * n rows.

6. **What is the union operation in relational algebra?**
   - The union (U) combines two relations with the same attributes, returning all distinct rows present in either relation.

7. **How is the set difference operation used in relational algebra?**
   - Set difference (−) returns rows that exist in one relation but not in another, assuming both relations have the same structure.
   Eg: `R - S` returns all rows in R that are not in S.

8. **What is the purpose of the rename operation in relational algebra?**
   - The rename operation (ρ) assigns a new name to a relation, often used when relations are combined to avoid ambiguity.

9. **What are the extended operations in relational algebra?**
   - Extended operations include **joins** (like natural join and theta join), **division**, and **aggregation**. These help handle more complex queries, such as matching rows across multiple tables.
