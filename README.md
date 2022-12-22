# starwars
This project is done with the following considerations:
1. API Data Extraction from https://swapi.dev/
2. Data Transformation
3. Dummy load to PostgreSQL database

The 2 tables to be created are as follow:

<h3>dim_film </h3>

<table style="width:100%">
  <tr>
    <th>Field Name</th>
    <th>Field Type</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>id</td>
    <td>Integer</td>
    <td>Pkey of table (based on url)</td>
  </tr>
  <tr>
    <td>title</td>
    <td>String</td>
    <td>-</td>
  </tr>
  <tr>
    <td>episode_id</td>
    <td>Integer</td>
    <td>-</td>
  </tr>
    <tr>
    <td>opening_crawl</td>
    <td>String</td>
    <td>-</td>
  </tr>
    <tr>
    <td>director</td>
    <td>String</td>
    <td>-</td>
  </tr>
    <tr>
    <td>producer</td>
    <td>String</td>
    <td>-</td>
  </tr>
    <tr>
    <td>character_count</td>
    <td>Integer</td>
    <td>Distinct count of people in the file</td>
  </tr>
  <tr>
    <td>planet_count</td>
    <td>Integer</td>
    <td>Distinct count of planet in the file</td>
  </tr>
    <tr>
    <td>starship_count</td>
    <td>Integer</td>
    <td>Distinct count of starship in the file</td>
  </tr>
      <tr>
    <td>vehicle_count</td>
    <td>Integer</td>
    <td>Distinct count of vehicle in the file</td>
  </tr>
        <tr>
    <td>species_count</td>
    <td>Integer</td>
    <td>Distinct count of species in the file</td>
  </tr>
         <tr>
    <td>release_date</td>
    <td>Date</td>
    <td>-</td>
  </tr>
         <tr>
    <td>created</td>
    <td>Datetime</td>
    <td>-</td>
  </tr>
           <tr>
    <td>edited</td>
    <td>Datetime</td>
    <td>-</td>
  </tr>
  
</table>
  
<h3>dim_people </h3>

<table style="width:100%">
  <tr>
    <th>Field Name</th>
    <th>Field Type</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>id</td>
    <td>Integer</td>
    <td>Pkey of table (based on url)</td>
  </tr>
  <tr>
    <td>name</td>
    <td>String</td>
    <td>-</td>
  </tr>
  <tr>
    <td>height</td>
    <td>Integer</td>
    <td>-</td>
  </tr>
    <tr>
    <td>mass</td>
    <td>Integer</td>
    <td>-</td>
  </tr>
    <tr>
    <td>hair_color</td>
    <td>String</td>
    <td>-</td>
  </tr>
    <tr>
    <td>skin_color</td>
    <td>String</td>
    <td>-</td>
  </tr>
    <tr>
    <td>eye_color</td>
    <td>String</td>
    <td>-</td>
  </tr>
  <tr>
    <td>birth_year</td>
    <td>String</td>
    <td>-</td>
  </tr>
    <tr>
    <td>gender</td>
    <td>String</td>
    <td>-</td>
  </tr>
      <tr>
    <td>homeworld</td>
    <td>String</td>
    <td>String version of the homeworld</td>
  </tr>
        <tr>
    <td>species_count</td>
    <td>Integer</td>
    <td>Distinct count of species in the file</td>
  </tr>
         <tr>
    <td>vehicle_count</td>
    <td>Integer</td>
    <td>Distinct count of vehicle in the file</td>
  </tr>
         <tr>
    <td>starship_count</td>
    <td>Integer</td>
    <td>Distinct count of starship in the file</td>
  </tr>
         <tr>
    <td>created</td>
    <td>Datetime</td>
    <td>-</td>
  </tr>
           <tr>
    <td>edited</td>
    <td>Datetime</td>
    <td>-</td>
  </tr>
  
</table>
 
