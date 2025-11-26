# KLayout Productivity Suite

The *KLayout Productivity Suite* is a set of plugins to boost your layout productivity developed by the [**Department for Integrated Circuits (ICD), Johannes Kepler University (JKU)**](https://iic.jku.at).

This add-on is a meta-package, that can be installed in KLayout's Package Manager. It will then automatically install all the plugins as `dependencies` in the `grain.xml`.

In alphabetical order:

   * https://github.com/iic-jku/klayout-align-tool
   * https://github.com/iic-jku/klayout-auto-backup
   * https://github.com/iic-jku/klayout-layer-shortcuts
   * https://github.com/iic-jku/klayout-library-manager
   * https://github.com/iic-jku/klayout-move-tool
   * https://github.com/iic-jku/klayout-pin-tool
   * https://github.com/iic-jku/klayout-plugin-utils (this is a utility library used by multiple of the plugins)

Check out the [documentation](https://iic-jku.github.io/klayout-productivity-suite/) for more information.

## Licensing

This repo is a meta-package, really containing only the documentation and a `grain.xml` with the list of dependencies.

Please note that while the documentation is licensed under Apache 2.0 license, the plugins are published under the GNU General Public License 3.0.
