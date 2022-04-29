About my-conda-pkg
==================

Home: 

Package license: 

Feedstock license: [BSD-3-Clause](https://github.com/phreed/my-conda-pkg-feedstock/blob/master/LICENSE.txt)

Summary: See the [history](HISTORY.adoc) for a description about the process for building this sample.

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-my--conda--pkg-green.svg)](https://anaconda.org/mesomorph/my-conda-pkg) | [![Conda Downloads](https://img.shields.io/conda/dn/mesomorph/my-conda-pkg.svg)](https://anaconda.org/mesomorph/my-conda-pkg) | [![Conda Version](https://img.shields.io/conda/vn/mesomorph/my-conda-pkg.svg)](https://anaconda.org/mesomorph/my-conda-pkg) | [![Conda Platforms](https://img.shields.io/conda/pn/mesomorph/my-conda-pkg.svg)](https://anaconda.org/mesomorph/my-conda-pkg) |

Installing my-conda-pkg
=======================

Installing `my-conda-pkg` from the `mesomorph` channel can be achieved by adding `mesomorph` to your channels with:

```
conda config --add channels mesomorph
conda config --set channel_priority strict
```

Once the `mesomorph` channel has been enabled, `my-conda-pkg` can be installed with `conda`:

```
conda install my-conda-pkg
```

or with `mamba`:

```
mamba install my-conda-pkg
```

It is possible to list all of the versions of `my-conda-pkg` available on your platform with `conda`:

```
conda search my-conda-pkg --channel mesomorph
```

or with `mamba`:

```
mamba search my-conda-pkg --channel mesomorph
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search my-conda-pkg --channel mesomorph

# List packages depending on `my-conda-pkg`:
mamba repoquery whoneeds my-conda-pkg --channel mesomorph

# List dependencies of `my-conda-pkg`:
mamba repoquery depends my-conda-pkg --channel mesomorph
```




Updating my-conda-pkg-feedstock
===============================

If you would like to improve the my-conda-pkg recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`mesomorph` channel, whereupon the built conda packages will be available for
everybody to install and use from the `mesomorph` channel.
Note that all branches in the phreed/my-conda-pkg-feedstock are
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


