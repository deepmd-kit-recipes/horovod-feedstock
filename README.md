About horovod
=============

Home: https://github.com/horovod/horovod

Package license: Apache-2.0

Feedstock license: [BSD-3-Clause](https://github.com/deepmd-kit-recipes/horovod-feedstock/blob/master/LICENSE.txt)

Summary: Distributed training framework for TensorFlow, Keras, PyTorch, and Apache MXNet.

Development: https://github.com/horovod/horovod

Documentation: https://github.com/horovod/horovod

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_cuda_compiler_version10.2python3.10.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_version10.2python3.10._" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_cuda_compiler_version10.2python3.8.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_version10.2python3.8._" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_cuda_compiler_version10.2python3.9.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_version10.2python3.9._" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_cuda_compiler_version11.6python3.10.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_version11.6python3.10._" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_cuda_compiler_version11.6python3.8.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_version11.6python3.8._" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_cuda_compiler_version11.6python3.9.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_version11.6python3.9._" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_cuda_compiler_versionNonepython3.10.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_versionNonepython3.10._" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_cuda_compiler_versionNonepython3.8.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_versionNonepython3.8._" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_cuda_compiler_versionNonepython3.9.</td>
              <td>
                <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/horovod-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_versionNonepython3.9._" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-horovod-green.svg)](https://anaconda.org/deepmodeling/horovod) | [![Conda Downloads](https://img.shields.io/conda/dn/deepmodeling/horovod.svg)](https://anaconda.org/deepmodeling/horovod) | [![Conda Version](https://img.shields.io/conda/vn/deepmodeling/horovod.svg)](https://anaconda.org/deepmodeling/horovod) | [![Conda Platforms](https://img.shields.io/conda/pn/deepmodeling/horovod.svg)](https://anaconda.org/deepmodeling/horovod) |

Installing horovod
==================

Installing `horovod` from the `deepmodeling` channel can be achieved by adding `deepmodeling` to your channels with:

```
conda config --add channels deepmodeling
conda config --set channel_priority strict
```

Once the `deepmodeling` channel has been enabled, `horovod` can be installed with `conda`:

```
conda install horovod
```

or with `mamba`:

```
mamba install horovod
```

It is possible to list all of the versions of `horovod` available on your platform with `conda`:

```
conda search horovod --channel deepmodeling
```

or with `mamba`:

```
mamba search horovod --channel deepmodeling
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search horovod --channel deepmodeling

# List packages depending on `horovod`:
mamba repoquery whoneeds horovod --channel deepmodeling

# List dependencies of `horovod`:
mamba repoquery depends horovod --channel deepmodeling
```




Updating horovod-feedstock
==========================

If you would like to improve the horovod recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`deepmodeling` channel, whereupon the built conda packages will be available for
everybody to install and use from the `deepmodeling` channel.
Note that all branches in the deepmd-kit-recipes/horovod-feedstock are
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

* [@njzjz](https://github.com/njzjz/)

