# 🎵 Final Project Module 2 - Music Streaming APIs analysis 

This project was developed by **Marta Gamarra**, **Ariana Papantonio**, **Macarena Peña**, **Fiona Sánchez** and **Yolanda Serrano**  as part of the **Data Analytics Bootcamp** at **Adalab**.

The goal of this project was to practice data extraction from multiple public **APIs**, clean and transform the data, design a relational database structure, and analyze music consumption patterns in the digital era.  
We focused on building **ETL** processes, creating a database in **MySQL**, and generating insights based on queries about song and artist popularity.

---

## 📌 Project Overview

**MusicStream: Analyzing Song Popularity in the Digital Era** is an initiative focused on studying the popularity of songs and albums on the fictional platform _MusicStream_.  
By leveraging advanced data extraction and analysis techniques, the project aims to answer key questions about music consumption trends in the digital world.

---

## 🎯 Project Objective

The main goal is to identify the most popular songs and albums on _MusicStream_, using multiple external data sources, such as:

- **Spotify API**: To gather detailed information about songs, albums, and artists.
- **MusicBrainz API**: To complement metadata about tracks and albums.
- **Last.fm API**: To collect additional data on popularity and musical trends.

All the extracted data was stored in a relational **MySQL** database, where we performed queries to extract key insights about music popularity.

---

## 🛠️ Technologies Used

For the development of this project, we used the following tools and technologies:

- **Programming Language**: Python
- **Database**: MySQL
- **APIs**: Spotify, MusicBrainz, and Last.fm
- **Development Environment**: Visual Studio Code
- **Data Analysis and Transformation**: Python libraries such as Pandas and SQLAlchemy

---

## 🔍 Project Structure

The project is organized as follows:

- `consultas/`: Contains the results of the SQL queries in JSON format.
- `data/`: Stores the extracted dataframes.
- `notebooks/`: Includes Jupyter Notebooks for data extraction from each API.
- `migraciones_SQL/`: Contains SQL scripts for table structure creation, migration scripts to transfer data from Python to SQL, table information in JSON format, and the overall database structure.
- `README.md`: Provides an overview and documentation of the project.

---

## 🧩 Installation and Execution

1. **Clone the repository**

   ```bash
   git clone https://github.com/ArianaPapantonio/Final_project_module_2.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd Final_project_module_2
   ```

3. **Install the required dependencies**

   Make sure you have Python and MySQL installed on your system.  
   Then, install the necessary Python libraries listed in the Jupyter Notebooks inside the `notebooks/` and `migraciones_SQL/` folders.

4. **Configure API access**

   Sign up on Spotify, MusicBrainz, and Last.fm to obtain API keys.  
   Create a `.env` file in the root directory of the project and add your credentials.

5. **Run the project**

   - Run the Jupyter Notebooks in the `notebooks/` folder to extract data from the APIs.  
   - Create the SQL tables using the script in `migraciones_SQL/Creación_tablas_SQL.sql`.  
   - Run `Migración_python_SQL` to transfer data from Python into the MySQL database.  
   - Use the `Consultas_SQL` file to clean the data and run the analysis queries.

---

## 📊 Analysis Performed

Using SQL queries and Python analysis, we were able to:

- Identify the genre with the highest average number of plays  
- Find the artists with the most listeners by genre, and their similar artists  
- Count the number of artists by genre and discover the most common ones  
- List the five least listened-to artists  
- Determine the countries with the most artists  
- Reveal which artists released the most songs per genre

These are just a few of the insights we explored — feel free to run your own queries and expand on the analysis! 🎉
