## Open Educational Resource (OER)

# Evidence-based facies model: tropical carbonate platforms

Target audience: Undergraduate students.

Assumed knowledge: types of sedimentary rocks, most common minerals, Dunham classification of carbonate rocks.

Discipline: Earth sciences, geosciences.

This module is a class developed for the 1st year of Bachelors of Geosciences with a planned duration of 3 h. It uses publicly available [high-resolution thin sections made from modern sediments from the Bahamas](https://commons.wikimedia.org/wiki/Category:Geozentrum_Nordbayern) and Landsat images available via Google Maps or Google Earth, but including hand specimens and physical thin sections from tropical carbonate rocks is recommended. The goal of the module is to create a facies model and reflect on what a *model* means in the context of depositional environment.

### Usage

This repository provides a [detailed written instruction for students](Instructions.md), a short [presentation](html/Presentation.html) that may accompany it, additional [information on the thin sections](Thin_sections_solutions.md), and a [grading rubric](Grading_rubric.md).

#### File formats and editing

Text and presentation files are provided as [Quarto](https://quarto.org/) files. This is an open source publishing format based on markdown. Quarto files can be edited using text editors and IDEs such as R Studio and rendered to any format: `docx`, `pdf`, `html`. You can preview the contents of the OER directly on GitHub in files with `.md` extension and `.html` files are provided in the `html` folder.

If you would like to edit the OER and export it e.g. to Word or PDF, you can do it in three ways.

1.  Edit the files in the `html` folder, e.g. in Word.

2.  Edit and render Quarto files

    First, clone the repository.

    -   Open the file in R Studio, set the following line to your preferred format, e.g.:

    ```         
    format: pdf
    ```

    And click `Render`.

    -   Change the line as above using any text editor and use Quarto CLI to render it:

    ```         
    quarto render
    ```

The presentation is prepared in [Reveal.js](https://quarto.org/docs/presentations/revealjs/), which is also supported by the Quarto format and can be rendered as above, but the `format` is already set and will be rendered to `.html`.

### How to contribute

If you would like to contribute to this OER, please see [CONTRIBUTING.md](CONTRIBUTING.md).

### License

Please see [LICENSE.md](LICENSE.md)

### Author

**Emilia Jarochowska**\
Utrecht University\
email: e.b.jarochowska [at] uu.nl\
Web page: [www.uu.nl/staff/EBJarochowska](https://www.uu.nl/staff/EBJarochowska)\
ORCID: [0000-0001-8937-9405](https://orcid.org/0000-0001-8937-9405)

### Copyright

Copyright 2023 Utrecht University
