# Assignment 3, Collecting Data, MA Digital Humanities

# Gustave Courbet Corpus

## Corpus Overview

This repository contains a curated dataset of 30 paintings by Gustave Courbet. Courbet, a famous artist of the Realist movement, is well-known for
his depictions of everyday life, nature, and portraits that challenge traditional norms and embrace the authenticity of his subjects. Those paintings belong to the permanent collection of European paintings
department in the Metropolitan Museum. 
The dataset is designed for art historical analysis, machine learning, or educational purposes, showcasing Courbet's contributions to 19th-century Realism across themes like portraits, landscapes, nudes, and 
still lifes.

## Corpus Description
The dataset includes 30 artworks spanning various themes, genres, and techniques, showcasing Courbet's artistic versatility. The works range from stunning landscapes and intimate portraits to vibrant still lifes 
and expressive figure studies.
Each entry includes:

`Title`: The name of the painting.

`Artist`: Confirmed as Gustave Courbet for all entries.

`Image URL`: A direct link to the artwork’s image from The Met's collection.

## Included Paintings- Data scraped

`Source`: The Metropolitan Museum of Art's online collection [www.metmuseum.org].

**Portraits**: Louis Gueymard (1822–1880) as Robert le Diable // Jo, La Belle Irlandaise // Madame Auguste Cuoq (Mathilde Desportes, 1827–1910) // Alphonse Promayet (1822–1872) // Portrait of a Man // Madame Frederic Breyer (Fanny Hélène Van Bruyssel, 1830–1894) // Monsieur Suisse // Self-Portrait

**Landscapes and Nature**: The Source of the Loue // A Brook in the Forest // View of Ornans // River and Rocks // The Sea // The Hidden Brook // A Brook in a Clearing (possibly "Brook, Valley of Fontcouverte; Study") // The Source of the Loue // The Deer

**Genre and Animal Studies**: After the Hunt // Hunting Dogs with Dead Hare // The Fishing Boat // The Homecoming

**Nudes and Figures**: Young Ladies of the Village // The Woman in the Waves // The Young Bather // Nude with Flowering Branch // Woman in a Riding Habit (L'Amazone) // Woman with a Parrot

**Historical or Political Themes**: Young Communards in Prison (Les Fédérés à la Conciergerie)

**Seascapes**: Marine: The Waterspout // The Calm Sea

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

**Understanding CC0, Open Access, and Their Combined Benefits**:

`Creative Commons Zero (CC0)`: Content under the CC0 license is released into the public domain, allowing anyone to use, modify, and share it without restrictions or attribution requirements.

`Open Access (OA)`: Open Access content is freely available to the public, removing paywalls or access barriers, and is often used for scholarly or cultural works.

`CC0 and OA`: When content is both CC0 and OA, it is not only freely accessible to everyone but also free from copyright restrictions, enabling unrestricted use, sharing, and modification.

## Code and Processing
The Jupyter Notebook TheMetMuseum_GustaveCourbet_Final_fixed.ipynb includes all steps used to create the dataset:

`Web Scraping`: Extracted painting titles, artist name, and image URLs from the Met's online collection.
`Output`: Saved the final dataset as a CSV file.

In this project, BeautifulSoup, a Python library for parsing HTML and XML documents, was used to scrape and clean the data. This tool enabled the efficient extraction of key information from the Met's online collection, including artwork titles, artist name, and image URLs. Requests was utilized to send HTTP requests and retrieve the web pages of individual artworks, while pandas was employed to organize and structure the collected data into a manageable format for further processing. After extracting the necessary details, the data was saved into a CSV file, ensuring it could be easily accessed for analysis and review. These tools facilitated the process of gathering, cleaning, and storing the data from the Met's collection.

## Explanation of the Analysis [bar chart]
The bar chart shows how Gustave Courbet's artworks in the Met Museum collection are distributed across different categories.

**Most Represented Categories**:

The `Portraits` and `Landscapes and Nature` categories have the largest number of artworks, which isn't surprising because Courbet is well-known for his skill in portraying both people and natural scenes. This tells us that these themes were central to his work and are also prioritized by the museum's collection.

**Underrepresented Categories**:

The `Still Life` category has no works in this dataset, which could mean that Courbet didn't create many still lifes or that they are not part of this particular collection.
Similarly, there are only a few `Seascapes`, despite Courbet's known interest in landscapes. This could indicate that seascapes were a smaller part of his overall body of work.

**Moderately Represented Themes**:

`Nudes and Figures` and `Genre and Animal Studies` have a fair number of works, showing that Courbet explored a range of themes beyond portraits and landscapes.

**Why It's Interesting**:

This analysis gives us a snapshot of Courbet's artistic focus and the museum's collection choices. It helps us see where Courbet concentrated his efforts—on people and nature—while also sparking curiosity about why some categories are less represented.

## Creator 
This dataset was created and curated by Theodora-Stavroula Korma on behalf of the course Collecting Data, for the MA Digital Humanities. 

**Contact Information**:
email: t.s.korma@student.rug.nl

## Usage
This dataset is provided for educational purposes, intended to support the final individual assignment for the course **Collecting Data**, of 1b semester of MA Digital Humanities. 






