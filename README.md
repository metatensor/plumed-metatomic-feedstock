About plumed-metatomic-feedstock
================================

Feedstock license: [BSD-3-Clause](https://github.com/metatensor/plumed-metatomic-feedstock/blob/main/LICENSE.txt)

Home: http://www.plumed.org/

Package license: LGPL-3.0-only

Summary: Free energy calculations in molecular systems

Development: https://github.com/plumed/plumed2

Documentation: https://docs.metatensor.org/latest/atomistic/engines/plumed.html

PLUMED is an open source library for free energy calculations in molecular
systems which works together with some of the most popular molecular
dynamics engines. This version enables the metatomic integration.


Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/metatensor/plumed-metatomic-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/metatensor/plumed-metatomic-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-plumed--metatomic-green.svg)](https://anaconda.org/metatensor/plumed-metatomic) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/plumed-metatomic.svg)](https://anaconda.org/metatensor/plumed-metatomic) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/plumed-metatomic.svg)](https://anaconda.org/metatensor/plumed-metatomic) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/plumed-metatomic.svg)](https://anaconda.org/metatensor/plumed-metatomic) |

Installing plumed-metatomic
===========================

Installing `plumed-metatomic` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install plumed-metatomic
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install plumed-metatomic
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add plumed-metatomic
# for installing globally
pixi global install plumed-metatomic
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `plumed-metatomic` available on your platform:

<details>
<summary>With conda</summary>

```
conda search plumed-metatomic --channel metatensor
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search plumed-metatomic --channel metatensor
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search plumed-metatomic --channel metatensor
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search plumed-metatomic --channel metatensor

# List packages depending on `plumed-metatomic`:
mamba repoquery whoneeds plumed-metatomic --channel metatensor

# List dependencies of `plumed-metatomic`:
mamba repoquery depends plumed-metatomic --channel metatensor
```

</details>




Updating plumed-metatomic-feedstock
===================================

If you would like to improve the plumed-metatomic recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the metatensor/plumed-metatomic-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@HaoZeke](https://github.com/HaoZeke/)
* [@Luthaf](https://github.com/Luthaf/)

