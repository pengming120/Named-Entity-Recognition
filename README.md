# Named-Entity-Recognition

Named entities are phrases that contain the names of persons, organizations, geo-locations, companies, facilities etc.

For example:\
U.N. official **Ekeus(person)** heads for **Baghdad(geo-location)**.

The task of **WNUT-2016** concerns named entity recognition. We will concentrate on 10 fine-grained NER categories: **person, geo-location, company, facility, product, music artist, movie, sports team, tv show** and **other**. Dataset was extracted from tweets in English language.The named entity tags have format **B-TYPE, I-TYPE, O**. The first word of the entity will have tag **B-TYPE. I-TYPE** means that the word is inside an entity of type TYPE. A word with tag **O** is not part of any entities.
