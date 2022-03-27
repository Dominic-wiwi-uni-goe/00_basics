# 00_basics
This chapter summarizes some basics which may be required for the seminar. However, further reading is recommended:

- Matuzak, Benjamin (2020): Einstieg in Data Science mit R: Datenanalyse und Statistik ohne Vorkenntnisse. ISBN: 978-3836278928

#### (1) Installing packages from CRAN
How you can install a package will depend on where it is located. So, for publicly available packages, this means to what repository it belongs. The most common way is to use the CRAN repository, then you just need the name of the package and use the command install.packages("package"). We take the example of installing 'readxl' which can be used to import Microsoft Excel files.

```
install.packages("readxl")
```

Or install the development version from GitHub:

```
install.packages("devtools")
devtools::install_github("tidyverse/readxl")
```
