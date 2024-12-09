# Assignment 3, Collecting Data, MA Digital Humanities

# Gustave Courbet Corpus

## Corpus Overview

This repository contains a curated dataset of 31 paintings by Gustave Courbet. Courbet, a famous artist of the Realist movement, is well-known for
his depictions of everyday life, nature, and portraits that challenge traditional norms and embrace the authenticity of his subjects. Those paintings belong to the permanent collection of European paintings
department in the Metropolitan Museum. 
The dataset is designed for art historical analysis, machine learning, or educational purposes, showcasing Courbet's contributions to 19th-century Realism across themes like portraits, landscapes, nudes, and 
still lifes.

## Corpus Description
The dataset includes 31 artworks spanning various themes, genres, and techniques, showcasing Courbet's artistic versatility. The works range from stunning landscapes and intimate portraits to vibrant still lifes 
and expressive figure studies.
Each entry includes:

`Title`: The name of the painting.
`Artist`: Confirmed as Gustave Courbet for all entries.
`Image URL`: A direct link to the artwork’s image from The Met's collection.

## Included Paintings- Data scraped

`Source`: The Metropolitan Museum of Art's online collection [www.metmuseum.org].

**Portraits**:
Louis Gueymard (1822–1880) as Robert le Diable
Jo, La Belle Irlandaise
Madame Auguste Cuoq (Mathilde Desportes, 1827–1910)
Alphonse Promayet (1822–1872)
Portrait of a Man
Madame Frederic Breyer (Fanny Hélène Van Bruyssel, 1830–1894)

**Landscapes and Nature**:
The Source of the Loue
A Brook in the Forest
View of Ornans
River and Rocks
The Sea
The Hidden Brook
A Brook in a Clearing
(possibly "Brook, Valley of Fontcouverte; Study")

**Genre and Animal Studies**:
After the Hunt
Hunting Dogs with Dead Hare
The Fishing Boat

**Nudes and Figures**:
Young Ladies of the Village
The Woman in the Waves
The Young Bather
Study of a Nude Man
Nude with Flowering Branch
Woman in a Riding Habit (L'Amazone)

**Still Life**:
Apples
Spring Flowers

**Seascapes**:
Marine: The Waterspout
The Calm Sea

## File Formats 

The corpus is available in the following formats:

**Annotated Corpus File (.csv)**: Includes all the scraped data informations, including columns for Title, Artist and Image URL.

| CSV Column Names   | Description                                       |
|--------------------|---------------------------------------------------| 
| 'Title'            | Title of the painting                             |
| 'Artist'           | Artist's name, (here Gustave Courbet)             |
| 'Image URL'        | The URL for each painting's visual representation |

## Terms and Conditions
This dataset adheres to The Metropolitan Museum of Art's Open Access Policy, which permits the use of metadata and public domain images under the Creative Commons Zero (CC0) license.

The following points summarize the applicable usage rights:

**Open Access Works (OA)**:

The dataset includes image URLs of paintings marked with the Open Access (OA) icon.
These works are in the public domain or released under a Creative Commons Zero (CC0) license, allowing unrestricted use for any purpose, including commercial applications.

**Citation Requirements**:

When using the data, users must cite the source: The Metropolitan Museum of Art and include the URL www.metmuseum.org. This attribution does not imply endorsement by the museum.

**Restricted Use Materials**:

While this dataset does not include restricted-use materials, it is important to note that non-OA works are subject to copyright and may only be used for personal, educational, or fair use as defined under U.S. copyright law.

**Prohibited Activities**:

Commercial publication, distribution, or unauthorized modification of restricted materials is strictly prohibited.
Users must not remove copyright or attribution notices associated with the data or images.
For further details, refer to The Met's full Terms and Conditions [https://www.metmuseum.org/policies/terms-and-conditions].

## Code and Processing
The Jupyter Notebook TheMetMuseum_GustaveCourbet.ipynb includes all steps used to create the dataset:

`Web Scraping`: Extracted painting titles, artist name, and image URLs.
`Output`: Saved the final dataset as a CSV file.

## Creator 
This dataset was created and curated by Theodora-Stavroula Korma on behalf of the course Collecting Data, for the MA Digital Humanities. 

**Contact Information**:
email: t.s.korma@student.rug.nl

## Usage
This dataset is provided for educational purposes, intended to support the 2nd assignment for the course **Collecting Data**, of 1b semester of MA Digital Humanities. 






