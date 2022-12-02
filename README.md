- [About](#org7a20fb4)
- [Images](#orgd7f9738)
- [Schematic](#org68b7873)
- [PCB](#org0fafdf0)
- [Bill of Materials](#org774cd0a)
- [Development](#org3d853d9)

    <!-- This file is generated automatically from .metadata.org -->
    <!-- File edits may be overwritten! -->


<a id="org7a20fb4"></a>

# About

```markdown
- Name: project_name
- Description: Project documentation.
- Version: 0.1.0
- Date: 2023-01-01
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/repository_name
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2023 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
```


<a id="orgd7f9738"></a>

# Images


<a id="org68b7873"></a>

# Schematic


<a id="org0fafdf0"></a>

# PCB


<a id="org774cd0a"></a>

# Bill of Materials

|    |
|--- |
|  |


<a id="org3d853d9"></a>

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