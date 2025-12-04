# KLayout Productivity Suite

[![Quarto Publish](https://github.com/iic-jku/klayout-productivity-suite/actions/workflows/publish-quarto-github-pages.yml/badge.svg?branch=main)](https://github.com/iic-jku/klayout-productivity-suite/actions/workflows/publish-quarto-github-pages.yml)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17822159.svg)](https://doi.org/10.5281/zenodo.17822159)

The *KLayout Productivity Suite* is a collection of plugins developed by the [**Department for Integrated Circuits (ICD), Johannes Kepler University (JKU)**](https://iic.jku.at) to enhance your layout design productivity.

**For more details, see the [documentation](https://iic-jku.github.io/klayout-productivity-suite/).**

This add-on acts as a meta-package that can be installed in KLayout's Package Manager. Once installed, it automatically pulls in all the plugins as `dependencies` through the `grain.xml`.

## Plugins

Included plugins (alphabetically):

   * https://github.com/iic-jku/klayout-align-tool
   * https://github.com/iic-jku/klayout-auto-backup
   * https://github.com/iic-jku/klayout-layer-shortcuts
   * https://github.com/iic-jku/klayout-library-manager
   * https://github.com/iic-jku/klayout-move-tool
   * https://github.com/iic-jku/klayout-pin-tool
   * https://github.com/iic-jku/klayout-plugin-utils – a utility library used by several of the plugins

## Acknowledgements

This project is funded by the JKU/SAL [IWS Lab](https://research.jku.at/de/projects/jku-lit-sal-intelligent-wireless-systems-lab-iws-lab/), a collaboration of [Johannes Kepler University](https://jku.at) and [Silicon Austria Labs](https://silicon-austria-labs.com).

<p align="center">
  <img src="figures/funding/iic-jku.svg" alt="Johannes Kepler University: Institute for Integrated Circuits and Quantum Computing" width="300"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="figures/funding/silicon-austria-labs-logo.svg" alt="Silicon Austria Labs" width="300"/>
</p>

## Licensing

Please note that the documentation is licensed under Apache 2.0 License, while the plugins themselves are published under the GNU General Public License 3.0.
