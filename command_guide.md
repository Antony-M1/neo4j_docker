# Guide
This section contains how to use and commands will be there for `neo4j` the language is `openCypher query language`

# Commands

<details>
  <summary>CREATE</summary>

  Create a New `Node`

  ```python
  CREATE(Krish:Person{name:'Krish Naik', born:1989})
  ```

 ![image](https://github.com/user-attachments/assets/c93f696e-446f-4e7e-804d-48e525e3dd4c)


</details>

<details>
  <summary>Create Relationship</summary>

```python
MATCH(Robert:Person{name: "Robert Downey Jr"}), (ironman:Movie{title: "Iron Man"}) CREATE(Robert)-[:ACTED_IN]->(ironman);
```
Example 2
```python
MATCH(kenau_n1:Person{name: "Keanu Reeves"}), (matrix_n2:Movie{title: "The Matrix"}) CREATE(kenau_n1)-[:ACTED_IN]->(matrix_n2)
```
`kenau_n1` & `matrix_n2` just a temporary node to mention in the `CREATE` keyword
</details>

<details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>

<details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>
