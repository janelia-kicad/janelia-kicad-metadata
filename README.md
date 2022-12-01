- [About](#org6baad4f)
- [Images](#orgfee6c30)
- [Schematic](#org08aa2d4)
- [PCB](#org08a816b)
- [Bill of Materials](#org349160b)
- [Development](#orgab3630e)

    <!-- This file is generated automatically from .metadata.org -->
    <!-- File edits may be overwritten! -->


<a id="org6baad4f"></a>

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


<a id="orgfee6c30"></a>

# Images


<a id="org08aa2d4"></a>

# Schematic


<a id="org08a816b"></a>

# PCB


<a id="org349160b"></a>

# Bill of Materials

|    |
|--- |
|  |


<a id="orgab3630e"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Clone Repository

```sh
git clone https://github.com/janelia-kicad/repository_name
cd repository_name
```


## Edit .metadata.org

```sh
make metadata-edits
```


## Tangle .metadata.org

```sh
make metadata
```


## Edit files

```sh
make file-edits
exit
```