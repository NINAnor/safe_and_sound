# safe_and_sound
Safe and sound is a pilot project to assess the potential of developing a standard for Passive Acoustic Monitoring metadata based on [Camtrap DP](https://github.com/inbo/camtrapdp).

# Collection of use-cases
Safe and sound must take into account the diversity of PAM use and users.
PAM is applied differently across mediums (air, water, soil) and realms (terrestrial, subterranean, marine and freshwater). In each realm, various recorders/sensors are used (microphone, geophone, hydrophone). Besides, the method applied and habits to analyse the data vary (protocol for the data collection, algorithm, manual/automatic processing) due to the different constraints of each medium.

The two main aspects of PAM are bioacoustics and ecoacoustics. Bioacoustics focus on the sound produced by a single species. It aims to describe the library of sound associated with the behavior of the organism studied. Ecoacoustics take the soundscape in its whole, looking at the species composition, and including non-biological sounds (geophony and anthrophony).
Therefore, the datasets from bioacoustics and ecoacoustics are structured in different ways. Bioacoustics datasets are often fragmented into shorter sequences containing the sound events of interest. Ecoacoustics datasets are generally continuous recording over day, month or year.

From the people collecting data in the field, to the final report, professionals with different competences handle the data. They all have different needs, resources, skills (technicians, software and hardware developers, data scientists, computer scientists, biologist, ecologist). The metadata that circulates among them should be understandable. Furthermore, at several steps of the data processing, this information must be both human and computer readable.

# Suggest changes in Camtrap DP tables
Camtrap DP is organised in three core tables: Project meatadata, Deployment table, and Media table.
Some fields can be kept as they are. Other needs changes:
- rename term
- adapt description
- replace fields by comparable information
- add new fields
- remove non suitable fields


This work is carried out under the auspices of the Boring Fund 2024 with funding from WILDLABS and Arm Ltd.
