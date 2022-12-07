- [About](#org0385e62)
- [Images](#org80ddf13)
- [Schematic](#org8a12fff)
- [PCB](#orgb3217d2)
- [Bill of Materials](#orgea48c19)
- [Development](#org66e61d9)

    <!-- This file is generated automatically from .metadata.org -->
    <!-- File edits may be overwritten! -->


<a id="org0385e62"></a>

# About

```markdown
- Name: project_name
- Description: Project documentation.
- Version: 0.1.0
- Release Date: 2022-12-07
- Creation Date: 2023-01-01
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/repository_name
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2022 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
```


<a id="org80ddf13"></a>

# Images


<a id="org8a12fff"></a>

# Schematic


<a id="orgb3217d2"></a>

# PCB


<a id="orgea48c19"></a>

# Bill of Materials

|    |
|--- |
|  |


<a id="org66e61d9"></a>

# Development

1.  Install Guix.

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)

1.  Clone repository.

```sh
git clone https://github.com/janelia-kicad/repository_name
cd repository_name
```

1.  Open project in KiCad

```sh
make project-edits
exit
```

. Open .metadata.org.

```sh
make metadata-edits
```

1.  Modify project specific variables.

```sh
make metadata
```