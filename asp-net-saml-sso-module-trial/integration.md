##Steps to register miniorangesamlsso module into your application.

* Open web.config file and paste the below configuration inside the **Configuration** element.

	<system.webServer>
    <modules>
      <add name="APIFilter" type="miniorangesamlsso.APIFilter" preCondition="managedHandler"/>
    </modules>
  </system.webServer>
  
* Save the configuration.
* You are done with the module registration for your application.