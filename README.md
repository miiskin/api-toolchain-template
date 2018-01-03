# Develop a Cloud Foundry app with GitHub.com

This toolchain template is made for building and deploying the miiskin server api to a Bluemix environment.

This repository is PUBLIC, since otherwise it cannot be used by Bluemix, so there is no (and should not be any) environment variables or other sensitive information in this project.

You can create a new toolchain based on this template by clicking **Create toolchain**. You need to fill in the required information at creation time (e.g. hostnames, and number of instances). After creation, you also need to add the environment variables e.g.

    cf set-env $CF_APP_TMP conf_common_EnvironmentName test-env

and many more like the above, should be inserted into "Setup enviroment properties" script in the deploy stage.

[![Deploy To Bluemix](https://console.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/miiskin/api-toolchain-template)

For more information about toolchains, see [Custom toolchains in one click with IBM Bluemix DevOps Services](https://developer.ibm.com/devops-services/2016/06/16/open-toolchain-with-ibm-bluemix-devops-services/).
