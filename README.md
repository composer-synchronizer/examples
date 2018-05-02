# Examples
In this repository there are examples of configuration that is delivered
directly with the package (local-configuration) and configuration
that is stored remotely (remote-configuration) in [Github repository](https://github.com/composer-synchronizer/packages).

The configuration is mostly the same. Different could be in the following
- Project type => sets which project type you use
- Paths placeholders => different for each project type
- Configuration sections => depends on the project type

**Local configuration**

In this example configuration is stored in the composer-synchronizer directory directly in the package repository.
From this directory, the configuration is copied into the target project directory.
Directories like src and tests are just dummy directories.

**Remote configuration**

Is stored in the following structure
`<package name>/<version>/<versioned project type>` => `some/package/1.0/nette2` and is downloaded if the local configuration wasn't found.
