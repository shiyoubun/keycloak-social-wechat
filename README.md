# keycloak-social-wechat

To install the social wechat one has to:

* Add the jar to the Keycloak server:
  * `$ cp target/keycloak-social-wechat-*.jar _KEYCLOAK_HOME_/providers/`

* Add three templates to the Keycloak server:
  * `$ cp templates/realm-identity-provider-wechat.html _KEYCLOAK_HOME_/themes/base/admin/resources/partials`
  * `$ cp templates/realm-identity-provider-wechat-ext.html _KEYCLOAK_HOME_/themes/base/admin/resources/partials`
  