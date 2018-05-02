# Examples
In this repository there is an example of configuration that is delivered
directly with the package (local-configuration) and configuration
that is stored remotely (remote-configuration) in [Github repository](https://github.com/composer-synchronizer/packages).

The configuration is mostly the same. Different could be in the following
- Project type => sets which project type you use
- Paths placeholders => different for each project type
- Configuration sections => depends on the project type

**Local configuration**
Local package has the configuration stored in the composer-synchronizer directory.
From this directory, the configuration is copied into the target project directory.
The directories like src and tests are just dummy repositories.

**Remote configuration**
Is stored in the following structure
`<package name>/<version>/<versioned project type>` => `some/package/1.0/nette2`
