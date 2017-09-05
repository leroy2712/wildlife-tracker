# wildlife-tracker
A wildlife tracker App

Allows administrators to add animals to their system and rangers to log whenever they sight an animal and where they've seen it

#DATABASE

CREATE DATABASE wildlife_tracker;
CREATE TABLE animals (id serial PRIMARY KEY, name varchar);
CREATE TABLE endangered_animals (id serial PRIMARY KEY, name varchar, age varchar, health varchar);
CREATE TABLE sightings (id serial PRIMARY KEY, animal_id int, location varchar, ranger_name varchar);
