# Entity-Relationship (ER) Models
This repository contains logical and normalized data models for e-commerce and service applications, using Chen and Crow’s Foot notations to ensure data integrity, scalability, and alignment with business rules

## 🧩 Main Artifacts

- 👉 [Context Diagram (Chen notation)](https://github.com/edmnikolaeva/ER/blob/main/%D0%95R_%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F_%D1%87%D0%B5%D0%BD.jpg)
- 👉 [Context Diagram (Crow’s Foot / Martin notation) + Validation](https://github.com/edmnikolaeva/ER/blob/main/%D0%95R_%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F_crow's_foot_%D0%B2%D0%B0%D0%BB%D0%B8%D0%B4%D0%B0%D1%86%D0%B8%D1%8F.jpg)  
- 👉 [Normalization (0NF → 3NF)](https://github.com/edmnikolaeva/ER/blob/main/ER_%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F_%D0%BD%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F_%D0%B4%D0%BE_3%D0%9D%D0%A4.jpg)
- 👉 [Physical Data Model](https://github.com/edmnikolaeva/ER/blob/main/ER_физическая.jpg)

---

<table>
<tr>
<td>

## 👕 Clothing E-commerce Application

### Diagrams
1. [Context Diagram (Chen notation)](https://github.com/edmnikolaeva/ER/blob/main/%D0%95R_%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F_%D1%87%D0%B5%D0%BD.jpg)
2. [Context Diagram (Crow’s Foot / Martin notation) + Validation](https://github.com/edmnikolaeva/ER/blob/main/%D0%95R_%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F_crow's_foot_%D0%B2%D0%B0%D0%BB%D0%B8%D0%B4%D0%B0%D1%86%D0%B8%D1%8F.jpg)
3. [Normalization (0NF → 3NF)](https://github.com/edmnikolaeva/ER/blob/main/ER_%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F_%D0%BD%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F_%D0%B4%D0%BE_3%D0%9D%D0%A4.jpg)
---
### Business Context
- **Domain:** single-brand outdoor clothing & gear online store
- **Purpose:** validate and structure the data model to ensure correct handling of products, users, orders, and payments in the web application
- **Value:** ensures data integrity, supports developers and DB architects
- **Related Artifact:** [Data Vocabulary Sample](https://github.com/edmnikolaeva/ER/blob/main/data_vocabulary_sample.pdf)

</td>
<td width="220">
<img src="https://github.com/edmnikolaeva/ER/blob/main/er_sample.png" 
     alt="Visual Anchor — Main Screen Prototype" 
     width="200"/>
</td>
</tr>
</table>

---

<table>
<tr>
<td>

## 🎵 Music Service

### Diagram
- 👉 [Physical Data Model](https://github.com/edmnikolaeva/ER/blob/main/ER_физическая.jpg)
- Implements many-to-many relationships (e.g., User ↔ Track via Likes, Track ↔ Genre, User ↔ Playlist → Playlist ↔ Track) with proper keys and constraints for scalable storage and fast retrieval
---
### Business Context
- **Domain:** simple music streaming service 
- **Purpose:** physical data model capturing core entities and relationships for user-driven music discovery and engagement
- **Goal**: ensure efficient querying for personalized playlists, genre-based recommendations, like-based popularity, and user favorites tracking
- **Value:** ensures a clear and consistent data structure for building streaming functionality, user engagement features, and playlist management 

</td>
<td width="220">
<img src="https://github.com/edmnikolaeva/ER/blob/main/ER_физическая.jpg" 
     alt="Visual Anchor — Main Screen Prototype" 
     width="200"/>
</td>
</tr>
</table>

 
