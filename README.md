# treasure_cloud_config_repo
spring cloud config repository


The HTTP service has resources in the form:

/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties

Also,different profiles configuration can concentrate on single yml(or properties).
