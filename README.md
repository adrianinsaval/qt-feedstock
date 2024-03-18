About qt-feedstock
==================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/qt-feedstock/blob/main/LICENSE.txt)

Home: http://qt-project.org

Package license: LGPL-3.0-only

Summary: Qt is a cross-platform application and UI framework.

Development: https://github.com/qtproject

Documentation: http://doc.qt.io/

Qt helps you create connected devices, UIs & applications that run
anywhere on any device, on any operating system at any time.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-qt-green.svg)](https://anaconda.org/freecad/qt) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/qt.svg)](https://anaconda.org/freecad/qt) | [![Conda Version](https://img.shields.io/conda/vn/freecad/qt.svg)](https://anaconda.org/freecad/qt) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/qt.svg)](https://anaconda.org/freecad/qt) |

Installing qt
=============

Installing `qt` from the `freecad/label/dev` channel can be achieved by adding `freecad/label/dev` to your channels with:

```
conda config --add channels freecad/label/dev
conda config --set channel_priority strict
```

Once the `freecad/label/dev` channel has been enabled, `qt` can be installed with `conda`:

```
conda install qt
```

or with `mamba`:

```
mamba install qt
```

It is possible to list all of the versions of `qt` available on your platform with `conda`:

```
conda search qt --channel freecad/label/dev
```

or with `mamba`:

```
mamba search qt --channel freecad/label/dev
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search qt --channel freecad/label/dev

# List packages depending on `qt`:
mamba repoquery whoneeds qt --channel freecad/label/dev

# List dependencies of `qt`:
mamba repoquery depends qt --channel freecad/label/dev
```




Updating qt-feedstock
=====================

If you would like to improve the qt recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/qt-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/qt-main](https://github.com/conda-forge/qt-main/)

