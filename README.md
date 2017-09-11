
# Danta Main Reactor Project

Danta is the agnostic multi-platform templating engine. enables developers and IT teams to use technologies they already know, expediting the creation and leveraging of reusable technical assets.

Danta Main Reactor Project is the super project for all Danta projects.  It uses git submodules to embed all Danta projects and also includes a maven project to build all submodules. 

## Documentation

### Danta Main Reactor

  * Clone this project and all submodules: `git clone git@github.com:DantaFramework/MainReactor.git --recursive`
  * Build all submodules
    * By default, the common modules will be built: `mvn clean install`
    * You can also include the AEM modules: `mvn clean install -Pwith-aem`
    * Or the Jahia modules: `mvn clean install -Pwith-jahia`
    * Or both: `mvn clean install -Pwith-aem,with-jahia`

### Official documentation

 * Read our [official documentation](http://danta.tikaltechnologies.io/docs) for more information.
 * Read about [Git Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) and refer to the [git-submodule documentation](https://git-scm.com/docs/git-submodule)

## License

Read [License](LICENSE) for more licensing information.

## Contribute

Read [here](CONTRIBUTING.md) for more information.

## Credit

Special thanks to Jose Alvarez, who named Danta for the powerful ancient Mayan pyramid, La Danta. 
La Danta is the largest pyramid in El Mirador—the biggest Mayan city found in Petén, Guatemala.
