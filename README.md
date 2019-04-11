##WS client integration with Elytron client example

###This example demonstrates how WS client can use username, password and SSL context from wildfly-config.xml

* Please clone the following repositories:

[jbossws-spi](https://github.com/wildfly-security-incubator/jbossws-spi/tree/WS_client_Elytron_integration)
[wildfly-elytron](https://github.com/wildfly-security-incubator/wildfly-elytron/tree/WS_client_Elytron_integration)
[jbossws-common](https://github.com/wildfly-security-incubator/jbossws-common)

and make sure you are on the **WS_client_Elytron_integration** branch.
* Install all these repositories (in this order) with 
``
mvn clean install
``

* Follow the [helloworld-mutual-ssl quickstart](https://github.com/wildfly/quickstart/tree/master/helloworld-mutual-ssl) (configure mutual ssl on your server and deploy this quickstart).

* Configure path to keystore and truststore in this project's wildfly-config.xml accordingly.

* Run tests in Client.java.
