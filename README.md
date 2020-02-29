About libdb
===========

Home: http://www.oracle.com/technology/software/products/berkeley-db/index.html

Package license: AGPL-3.0

Feedstock license: BSD 3-Clause

Summary: The Berkeley DB embedded database system.



Current build status
====================


<table><tr>
    <td>Appveyor</td>
    <td>
      <a href="https://ci.appveyor.com/project/cryoem/libdb-feedstock/branch/master">
        <img alt="windows" src="https://img.shields.io/appveyor/ci/cryoem/libdb-feedstock/master.svg?label=Windows">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/cryoem/feedstock-builds/_build/latest?definitionId=blank&branchName=master">
            <img src="https://dev.azure.com/cryoem/feedstock-builds/_apis/build/status/libdb-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>win_c_compilervs2015cxx_compilervs2015vc14</td>
              <td>
                <a href="https://dev.azure.com/cryoem/feedstock-builds/_build/latest?definitionId=blank&branchName=master">
                  <img src="https://dev.azure.com/cryoem/feedstock-builds/_apis/build/status/libdb-feedstock?branchName=master&jobName=win&configuration=win_c_compilervs2015cxx_compilervs2015vc14" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>
      <img src="https://img.shields.io/badge/linux-disabled-lightgrey.svg" alt="linux disabled">
    </td>
  </tr>
  <tr>
    <td>OSX</td>
    <td>
      <img src="https://img.shields.io/badge/OSX-disabled-lightgrey.svg" alt="OSX disabled">
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libdb-green.svg)](https://anaconda.org/cryoem/libdb) | [![Conda Downloads](https://img.shields.io/conda/dn/cryoem/libdb.svg)](https://anaconda.org/cryoem/libdb) | [![Conda Version](https://img.shields.io/conda/vn/cryoem/libdb.svg)](https://anaconda.org/cryoem/libdb) | [![Conda Platforms](https://img.shields.io/conda/pn/cryoem/libdb.svg)](https://anaconda.org/cryoem/libdb) |

Installing libdb
================

Installing `libdb` from the `cryoem` channel can be achieved by adding `cryoem` to your channels with:

```
conda config --add channels cryoem
```

Once the `cryoem` channel has been enabled, `libdb` can be installed with:

```
conda install libdb
```

It is possible to list all of the versions of `libdb` available on your platform with:

```
conda search libdb --channel cryoem
```




Updating libdb-feedstock
========================

If you would like to improve the libdb recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`cryoem` channel, whereupon the built conda packages will be available for
everybody to install and use from the `cryoem` channel.
Note that all branches in the cryoem/libdb-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@ocefpaf](https://github.com/ocefpaf/)
* [@scopatz](https://github.com/scopatz/)

