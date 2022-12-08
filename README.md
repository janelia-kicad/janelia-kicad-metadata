- [About](#org138cd1c)
- [Images](#org55d04ae)
- [Schematic](#org356b82d)
- [PCB](#org51fa021)
- [Bill of Materials](#org0c6aa3b)
- [Development](#orgc015faa)

    <!-- This file is generated automatically from .metadata.org -->
    <!-- File edits may be overwritten! -->


<a id="org138cd1c"></a>

# About

```markdown
- Name: project_name
- Description: Project documentation.
- Version: 0.1.0
- Release Date: 2022-12-08
- Creation Date: 2023-01-01
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/repository_name
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2022 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
```


<a id="org55d04ae"></a>

# Images


<a id="org356b82d"></a>

# Schematic


<a id="org51fa021"></a>

# PCB


<a id="org0c6aa3b"></a>

# Bill of Materials

|    |
|--- |
|  |


<a id="orgc015faa"></a>

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