# PDFreactor template for Platform.sh

<p align="center"><a href="https://console.platform.sh/projects/create-project/?template=https://github.com/vrobert78/platformsh-pdfreactor/blob/master/template-definition.yaml" target="_blank" title="Deploy with Platform.sh"><img src="https://platform.sh/images/deploy/deploy-button-lg-blue.svg"></a></p>

This project provides a starter kit for PDFreactor projects hosted on Platform.sh.

PDFreactor documentation: https://www.pdfreactor.com/support/#documentation

Env variables configuration:

| var name               | Description        | sensitive | runtime | buildtime |
|------------------------|--------------------|-----------|---------|-----------|
|PDFREACTOR_LICENSEKEY   | PDFreactor license | true | false | true |
|PDFREACTOR_APIKEYS      | API KEYS separated by a comma | true | true | false |
|PDFREACTOR_ADMINKEY     | ADMIN KEY to access /service/monitor/server?adminKey= | true | true | false |
|PDFREACTOR_THREADS      | threadPoolSize aka the max number of concurrent threads (should be sized in relation with the count of VCPUS) | false | true | false |
|PDFREACTOR_MEMORY       | max memory for the Java Xmx parameter | false | true | false |
