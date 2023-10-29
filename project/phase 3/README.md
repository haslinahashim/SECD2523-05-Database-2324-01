# Project Phase 3
## Semester 1 2023/2024

- [P3 Guidelines](#p3-guidelines)
- [P3 Database Logical Design](#p3-database-logical-design)
- [P3 Rubrics](#p3-rubrics)
  - [1. Reporting](#1-reporting)
    - [A. Overall](#a-overall-2)
    - [B. Database Logical Design – ERD & Normalization](#bdatabase-logical-design--erd--normalization-6)
    - [C. Interface](#cinterface-2)
  - [2. Demonstrations](#2demonstrations-10)


<table>
  <tr>
    <td>Subject</td>
    <td>Subject	:	Database (SECD2523)</td>
  </tr><tr>
    <td>Section</td>
    <td></td>
  </tr><tr>
    <td>Task</td>
    <td>Phase 3 (P3) – Database Logical Design & SQL (20%)/td>
  </tr><tr>
    <td>Due</td>
    <td>WEEK 14 (07 Jan – 13 Jan 24)</td>
  </tr>
</table>

---

## P3 Guidelines

<table>
  <tr>
    <th>No</th>
    <th>Task</th>
    <th>Deliverables (Items in Database)</th>
  </tr>
  <tr>
    <td>1.</td>
    <td>
      <ul>
        <li>Transform the conceptual ERD in P2 into logical ERD. (e.g.: by removing non-relational features e.g.: *:* relationships, complex relationships, etc.)</li>
        <li>Derive relations schema from the logical ERD produced above.</li>
        <li>Perform normalization up till BCNF (if-any) to these relations.</li>
        <li>Draw the final logical ERD.</li>
        <li>Update the data dictionary based on the normalized relations produced from above.</li>
        <li>Validate logical ERD with the system’s transaction requirements using interface design.</li>
    </td>
    <td>
      A report containing the following:
      <ul>
        <li>Logical ERD (global data model)</li>
        <li>Relational database schemas (normalized table)</li>
        <li>Data dictionary for the normalized logical design</li>
        <li>Interface design (mapped to the proposed SQL statement)</li>
        <li>Proposed SQL statement (refer to rubric)</li>
      </ul>
        Demonstration:
          <ul>
            <li>Individual demonstration for SQL statement.</li>
          </ul>
    </td>
  </tr>
</table>



 ---

## P3 Database Logical Design
Prepare a Database conceptual design as below:

- 1.0	Introduction
- 2.0	Overview of project
- 3.0	Database conceptual design
  - 3.1	Updated business rule
  - 3.2	Conceptual ERD
- 4.0	DB logical design
  - 4.1	Logical ERD
  - 4.2	Updated Data Dictionary
  - 4.3	Normalization 
- 5.0	Relational DB Schemas (after normalization)
- 6.0	SQL Statements (DDL & DML)
- 7.0	Summary

---

## P3 Rubrics
### 1. Reporting
#### A. Overall (2%)
<table>
  <tr>
    <th>Criteria</th>
    <th>High (4)</th>
    <th>Average (3)</th>
    <th>Low (2)</th>
    <th>Unsatisfied (1)</th>
  </tr>
  <tr>
    <td>Document the whole process of designing the ERD</td>
    <td>Documented ALL reports on the construction of the database design. Shows FULL understanding of the requirements based on the case study.</td>
    <td>Documented MAJOR reports on the construction of the database design. Shows a GOOD understanding of the requirements based on the case study.</td>
    <td>Documented MINIMAL reports on the construction of the database design. Shows MINIMAL understanding of the requirements based on the case study.</td>
    <td>LITTLE evidence that the documents are based on the given case study.</td>
  </tr>
  <tr>
    <td>SQL documentation</td>
    <td>The student provides THOROUGH documentation for their SQL code, including comments explaining the purpose of the code, any complex logic, and the structure of the database.</td>
    <td>The student provides ADEQUATE documentation for their SQL code, but it may lack some details or clarity in explaining complex logic</td>
    <td>The student provides MINIMAL documentation for their SQL code, making it challenging to understand the purpose and logic</td>
    <td>The student provides NO documentation for their SQL code, making it nearly impossible to understand the purpose and logic</td>
  </tr>
</table>

#### B.	Database Logical Design – ERD & Normalization (6%)
<table>
  <tr>
    <th>Criteria</th>
    <th>High (4)</th>
    <th>Average (3)</th>
    <th>Low (2)</th>
    <th>Unsatisfied (1)</th>
  </tr>
  <tr>
    <td>Follow the instructions to draw the logical ERD and derive the relations</td>
    <td>COMPLETE understanding of how to draw ERD and derive relations</td>
    <td>Exhibits a GOOD understanding of how to draw ERD and derive relations</td>
    <td>Exhibits MINIMAL understanding of how to draw ERD and derive relations.</td>
    <td>UNABLE to follow the instructions on how to draw ERD and fails to derive relations.</td>
  </tr>
  <tr>
    <td>Identifies all the basic concepts in normalization (relational schema)</td>
    <td>COMPLETE understanding of the basic concepts in ERD</td>
    <td>Exhibit a GOOD understanding of the basic concepts in ERD.</td>
    <td>Exhibit a MINIMAL understanding of the basic concepts in ERD.</td>
    <td>UNABLE to show understanding of the basic concepts of ERD.</td>
  </tr>
  <tr>
    <td>Represents the dependency diagram (and relational schema) based on the given case study</td>
    <td>COMPLETELY and ACCURATELY use of names, definitions in entities, and attributes - table name is appropriately used in regard to its data elements</td>
    <td>Some MINOR inaccurate use of names, definition in entities and attributes - FEW table name is not clear in regard to its data elements</td>
    <td>INACCURATE the use of names, definitions in entities, and attributes - table name DID NOT correlate with its data elements</td>
    <td>WRONG the use of names, definitions in entities and attributes. Shows NO understanding in identifying the tables based on the case study.</td>
  </tr>
  <tr>
    <td>Differentiates the keys in the dependency diagram</td>
    <td>COMPLETE understanding of the dependencies and normal-form levels</td>
    <td>Exhibit a GOOD understanding of the dependencies and normal-form levels</td>
    <td>Exhibit a MINIMAL understanding of the dependencies and normal-form levels</td>
    <td>UNABLE to differentiate the dependencies and normal-form levels</td>
  </tr>
  <tr>
    <td>Label the necessary transitive and partial dependencies</td>
    <td>Correctly choose ALL of the PKs and FKs, with regard to the naming convention</td>
    <td>Correctly choose MOST of the PKs and FKs, in regard to the naming convention.</td>
    <td>INCORRECTLY choose the PKs and FKs.</td>
    <td>WRONGLY choose the PKs and FKs.</td>
  </tr>
  <tr>
    <td>Illustrates the normalization steps - from 1NF --> 2 NF --> 3NF -->BCNF (if applicable)</td>
    <td>A COMPLETE populated the tables with CORRECT data elements as outlined in the ERD design.</td>
    <td>Populated the tables with ALL data elements as outlined in the ERD design - with MINIMAL errors.</td>
    <td>Populated the tables with MINIMAL data elements as outlined in the ERD design - with MINIMAL errors.</td>
    <td>Populated the tables with MINIMAL data elements as outlined in the ERD design - with NUMEROUS errors.</td>
  </tr>
</table>

#### C.	Interface (2%)
<table>
  <tr>
    <th>Criteria</th>
    <th>High (4)</th>
    <th>Average (3)</th>
    <th>Low (2)</th>
    <th>Unsatisfied (1)</th>
  </tr>
  <tr>
    <td>Appropriateness to target user </td>
    <td>Prototype uses terms and symbols APPROPRIATE to target user. Look and feel APPROPRIATE to the target user. <br><br> Usability APPROPRIATE to target user. 
    </td>
      <td>Prototype designed for a WELL-DEFINED target user.
      <br><br>
        Usability is APPROPRIATE to the target user. 
  </td>
  <td>Prototype designed WITHOUT well-defined target user in mind.
      <br><br>
      SOME usability is NOT appropriate for the target user. 
  </td>
  <td>Prototype designed WITHOUT well-defined target user in mind.
      <br><br>
      MOST usability is NOT appropriate for the target user.
  </td>
    </tr>
    <tr>
      <td>Prototype's Interaction Usability </td>
      <td>The user interface uses a SIMPLE and NATURAL interaction style. 
      <br><br>
      INTUITIVE, EASY to learn and use.</td>
      <td>The user interface uses a SIMPLE interaction style. 
      <br><br>
      EASY to use once you learn it. 
      </td>
      <td>SOME user interface is COMPLICATED and HARD to use. </td>
      <td>HARD to figure out how to even get started using the prototype. </td>
    </tr>
    <tr>
      <td>Mapping SQL statements to the appropriate functions</td>
      <td>Demonstrates an EXCEPTIONAL ability to map SQL statements to appropriate functions, showing MASTERY in this skill.
      <br><br>
      CONSISTENTLY and INNOVATIVELY maps SQL statements to appropriate functions, optimizing performance and accuracy.
      </td>
      <td>CONSISTENTLY and ACCURATELY maps SQL statements to the appropriate functions.
      <br><br>
      CONSISTENTLY maps SQL statements to appropriate functions.
      </td>
          <td>ABLE to map SQL statements to APPROPRIATE functions but still needs IMPROVEMENT.
      <br><br>
      INCONSISTENTLY maps SQL statements to appropriate functions.
      </td>
          <td>Demonstrates a BASIC understanding of SQL statements and functions but STRUGGLES to map them effectively.
      <br><br>
      UNABLE to efficiently map SQL statements to appropriate functions.
  </td>
  </tr>
</table>

### 2.	Demonstrations (10%) 
### SQL (DDL+DML)

<table>
  <tr>
    <th>Criteria</th>
    <th>High (4)</th>
    <th>Average (3)</th>
    <th>Low (2)</th>
    <th>Unsatisfied (1)</th>
  </tr>
  <tr>
    <td>Appropriateness and Accuracy of Design </td>
    <td>The student has created an EXCELLENT Database design that includes ALL or the 
MAJORITY (above 90%) of the following 
characteristics: 
      <ul>
        <li>•	At least 20 records have been added to the Database </li>
<li>Appropriate Queries that include at LEAST 
FIVE (5) DML skills</li>
<li>Appropriate Report structure </li>
</li>
      </ul>
</td>
    <td>The student has created a GOOD Database design that includes MOST (above 50%) of the following characteristics: 
    <ul>
      <li>At least 20 records have been added to the Database </li>
      <li>Appropriate Queries that include at LEAST FIVE (5) DML skills</li>
      <li>Appropriate Report structure</li>
</li>
    </ul>
    </td>
    <td>The student has created an ACCEPTABLE Database design that includes SOME of the following characteristics: 
    <ul>
      <li>At least 20 records have been added to the Database </li>
      <li>Appropriate Queries that include at LEAST FIVE (5) DML skills</li>
      <li>Appropriate Report structure </li>
    </ul>
      OR
      <br><br>
      there are misconceptions/mistakes within the data, query, or reports that significantly alter their appropriateness of them.
    </td>
    <td>The student has created a SIMPLISTIC Database design that includes some of the following characteristics either superficially or is missing major components. The database is NOT suitable for the intended purpose.: 
    <ul>
      <li>At least 20 records have been added to the Database </li>
      <li>Appropriate Queries that include at LEAST TWO DML skills </li>
      <li>Appropriate Report structure including.</li>
    </ul>
</td>
  </tr>
</table>
