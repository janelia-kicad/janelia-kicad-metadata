- [About](#org2af1626)
- [Images](#orgd54087c)
- [Schematic](#org9c35788)
- [PCB](#orgac861f5)
- [Bill of Materials](#org2320c0c)
- [Development](#orga1c53ae)

    <!-- This file is generated automatically from .metadata.org -->
    <!-- File edits may be overwritten! -->


<a id="org2af1626"></a>

# About

```markdown
- Name: project_name
- Description: Project documentation.
- Version: 0.1.0
- Date: 2022-11-30
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/repository_name
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2022 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
```


<a id="orgd54087c"></a>

# Images


<a id="org9c35788"></a>

# Schematic


<a id="orgac861f5"></a>

# PCB


<a id="org2320c0c"></a>

# Bill of Materials

|    |
|--- |
|  |


<a id="orga1c53ae"></a>

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