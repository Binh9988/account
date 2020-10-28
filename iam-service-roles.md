---

copyright:

  years: 2019

lastupdated: "2020-10-28"

keywords: service iam roles, service iam actions, account management roles, iam roles

subcollection: account

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:faq: data-hd-content-type='faq'}
{:note: .note}

# IAM roles and actions
{: #iam-service-roles-actions}

It is important to understand how to effectively assign access for users to work with products and take specific account management actions within your account to follow the principle of least privilege and minimize the number of policies that you have to manage. The following tables provide information about the access roles and the actions mapped to each by the {{site.data.keyword.cloud}} services. 
{: shortdesc}

The following tables provide data from the individual Identity and access enabled services that are available from the {{site.data.keyword.cloud_notm}} catalog as well as the available account management services that enable you to assign others the ability to work with users, access groups, support cases, and more in the account. If you don't see a platform roles or service roles table, then that means that particular service doesn't use those types of roles.

Each service has custom actions that they define and map to platform and service roles that you can use to assign access by creating an Identity and Access Management (IAM) access policy. If you are trying to assign access and an existing role doesn't fit your needs, you can create a [custom role](/docs/account?topic=account-custom-roles) combining any number of actions available for a given service.

For more information about assigning access for each service, check out the documentation for the service that you're using.

<!-- Everything is deleted after this line. -->
## Actifio GO
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `actifio-go` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 1. Platform roles - Actifio GO" caption-side="top"}
{: #platform-roles-table1}
{: tab-title="Platform roles"}
{: tab-group="actifio-go"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `actifio-go.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 1. Service actions - Actifio GO" caption-side="top"}
{: #actions-table1}
{: tab-title="Actions"}
{: tab-group="actifio-go"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Analytics Engine
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `ibmanalyticsengine` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 2. Platform roles - Analytics Engine" caption-side="top"}
{: #platform-roles-table2}
{: tab-title="Platform roles"}
{: tab-group="ibmanalyticsengine"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 2. Service roles - Analytics Engine" caption-side="top"}
{: #service-roles-table2}
{: tab-title="Service roles"}
{: tab-group="ibmanalyticsengine"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `ibmae.cluster.createlogconfig` |  | Administrator, Editor, Manager, Writer |
| `ibmae.cluster.customize` |  | Administrator, Editor, Manager, Writer |
| `ibmae.cluster.deletelogconfig` |  | Administrator, Editor, Manager, Writer |
| `ibmae.cluster.read` |  | Administrator, Editor, Manager, Operator, Reader, Viewer, Writer |
| `ibmae.cluster.resize` |  | Administrator, Editor, Manager, Writer |
| `ibmae.cluster.resetpassword` |  | Administrator, Manager |
| `ibmae.cluster.updatePrivateEndpointWhitelist` |  | Administrator, Editor, Manager, Writer |
| `ibmae.cluster.viewpassword` |  | Administrator, Editor, Manager, Writer |
{: caption="Table 2. Service actions - Analytics Engine" caption-side="top"}
{: #actions-table2}
{: tab-title="Actions"}
{: tab-group="ibmanalyticsengine"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Annotator for Clinical Data
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `wh-acd` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 3. Platform roles - Annotator for Clinical Data" caption-side="top"}
{: #platform-roles-table3}
{: tab-title="Platform roles"}
{: tab-group="wh-acd"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 3. Service roles - Annotator for Clinical Data" caption-side="top"}
{: #service-roles-table3}
{: tab-title="Service roles"}
{: tab-group="wh-acd"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `wh-acd.dashboard.view` | View Dashboard | Administrator, Editor, Operator |
| `GET /wh-acd` | ACD Dev Deadbolt API GET | Manager, Reader, Writer |
| `PUT /wh-acd` | ACD Dev Deadbolt API PUT | Manager, Writer |
| `POST /wh-acd` | ACD Dev Deadbolt API POST | Manager, Writer |
| `DELETE /wh-acd` | ACD Dev Deadbolt API DELETE | Manager |
| `wh-acd.cartridge.manage` | Cartridge manage | Manager, Writer |
| `wh-acd.flows.manage` | Manage flows | Manager, Writer |
| `wh-acd.profiles.manage` | Manage profiles | Manager, Writer |
| `wh-acd.analyze` | Analyze | Manager, Reader, Writer |
{: caption="Table 3. Service actions - Annotator for Clinical Data" caption-side="top"}
{: #actions-table3}
{: tab-title="Actions"}
{: tab-group="wh-acd"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## API Connect
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `apiconnect` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 4. Platform roles - API Connect" caption-side="top"}
{: #platform-roles-table4}
{: tab-title="Platform roles"}
{: tab-group="apiconnect"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 4. Service roles - API Connect" caption-side="top"}
{: #service-roles-table4}
{: tab-title="Service roles"}
{: tab-group="apiconnect"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `apiconnect.instance.view` | apiconnect.instance.view | Administrator, Editor, Manager, Operator, Reader, Viewer, Writer |
| `apiconnect.instance.admin` | apiconnect.instance.admin | Administrator |
| `apiconnect.admin.manage` | Enables API Connect administrators to create provider orgs, manage gateways, and adjust other settings for the environment. | Administrator, Editor, Manager |
| `apiconnect.instance.api-admin` | apiconnect.instance.api-admin | Editor, Manager |
| `apiconnect.instance.develop` | apiconnect.instance.develop | Writer |
| `apiconnect.instance.manage-community` | apiconnect.instance.manage-community | Operator |
{: caption="Table 4. Service actions - API Connect" caption-side="top"}
{: #actions-table4}
{: tab-title="Actions"}
{: tab-group="apiconnect"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## API Gateway
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `api-gateway` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 5. Platform roles - API Gateway" caption-side="top"}
{: #platform-roles-table5}
{: tab-title="Platform roles"}
{: tab-group="api-gateway"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 5. Service roles - API Gateway" caption-side="top"}
{: #service-roles-table5}
{: tab-title="Service roles"}
{: tab-group="api-gateway"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `api-gateway.dashboard.view` |  | Administrator, Editor, Operator |
| `api-gateway.api.view` |  | Manager, Reader, Writer |
| `api-gateway.api.create` |  | Manager, Writer |
| `api-gateway.api.edit` |  | Manager, Writer |
| `api-gateway.api.delete` |  | Manager, Writer |
| `api-gateway.api.share` |  | Manager |
{: caption="Table 5. Service actions - API Gateway" caption-side="top"}
{: #actions-table5}
{: tab-title="Actions"}
{: tab-group="api-gateway"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## App ID
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `appid` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 6. Service roles - App ID" caption-side="top"}
{: #service-roles-table6}
{: tab-title="Service roles"}
{: tab-group="appid"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `appid.mgmt.set.sender.details.cd` | Set the sender details for emails sent to Cloud Directory users. | Manager, Writer |
| `appid.mgmt.get.sender.details.cd` | View the sender details for the emails sent to Cloud Directory users. | Manager, Reader, Writer |
| `appid.mgmt.set.redirect.uris` | Add or update post-authentication redirect URIs. | Manager, Writer |
| `appid.mgmt.get.redirect.uris` | View the post-authentication redirect URIs that are currently configured. | Manager, Reader, Writer |
| `appid.mgmt.set.idps` | Configure the identity provider options that a user has at sign in. | Manager, Writer |
| `appid.mgmt.get.idps` | View the current identity provider options that a user has when they sign in. | Manager, Reader, Writer |
| `appid.mgmt.get.recent.activities` | View recent authentication activity for an application. | Manager, Reader, Writer |
| `appid.mgmt.get.ui.config` | View the current Login Widget configuration including the color and logo. | Manager, Reader, Writer |
| `appid.mgmt.set.ui.config` | Configure the appearance of the Login Widget including the color and logo. | Manager, Writer |
| `appid.mgmt.get.user.profile.config` | Get user information from your app configuration. | Manager, Reader, Writer |
| `appid.mgmt.set.user.profile.config` | Update a user profile with the information from your app. | Manager, Writer |
| `appid.mgmt.get.cd.users` | View Cloud Directory users and their data. | Manager, Reader, Writer |
| `appid.mgmt.add.cd.user` | Create a Cloud Directory user | Manager, Writer |
| `appid.mgmt.set.cd.user` | Update a Cloud Directory user's information. | Manager, Writer |
| `appid.mgmt.delete.cd.user` | Delete a user from Cloud Directory. | Manager, Writer |
| `appid.mgmt.get.email.template` | Get your current email template configuration. | Manager, Reader, Writer |
| `appid.mgmt.update.email.template` | Update your email template configuration | Manager, Writer |
| `appid.mgmt.delete.email.template` | Delete an email template configuration. | Manager, Writer |
| `appid.mgmt.get.saml.metadata` | Get the metadata that is used to link your SAML provider. | Manager, Reader, Writer |
| `appid.mgmt.resend.notification.cd` | Resend an email to a Cloud Directory user. | Manager, Writer |
| `appid.mgmt.get.tokens.configuration` | View the current configuration of your tokens. | Manager, Reader, Writer |
| `appid.mgmt.set.tokens.configuration` | Configure the access, identity, and refresh tokens. | Manager, Writer |
| `appid.mgmt.cd.sign.up` | Start the sign up process for a new Cloud Directory user. | Manager, Writer |
| `appid.mgmt.cd.sign.up.result` | View the result of a new user sign up. | Manager, Writer |
| `appid.mgmt.cd.forgot.password` | Start the forgot password email flow for a Cloud Directory user. | Manager, Writer |
| `appid.mgmt.cd.forgot.password.result` | View whether the forgot password email was successfully sent. | Manager, Writer |
| `appid.mgmt.cd.change.password` | Start the change password email flow for a Cloud Directory user. | Manager, Writer |
| `appid.mgmt.get.cd.actions.urls` | View the action URLs that are configured for Cloud Directory. | Manager, Reader, Writer |
| `appid.mgmt.get.cd.action.url` | Get a single action URI that is configured for Cloud Directory. | Manager, Reader, Writer |
| `appid.mgmt.update.cd.action.url` | Update an action URI that is configured for Cloud Directory. | Manager, Writer |
| `appid.mgmt.del.cd.action.url` | Delete an action URI that is configured for Cloud Directory. | Manager, Writer |
| `appid.mgmt.get.cd.password.policy` | View the Cloud Directory password policy configuration in regex form | Manager, Reader, Writer |
| `appid.mgmt.update.cd.password.policy` | Update a Cloud Directory password policy in regex. | Manager, Writer |
| `appid.mgmt.delete.profile` | Delete a user profile from App ID. | Manager, Writer |
| `appid.mgmt.get.profile` | View a user profile. | Manager, Reader, Writer |
| `appid.mgmt.update.profile` | Update a user's profile. | Manager, Writer |
| `appid.mgmt.get.profiles` | Search all of your user profiles and get a count of any anonymous users. | Manager, Reader, Writer |
| `appid.mgmt.revoke.refresh.token` | Revoke a user's refresh token. | Manager, Writer |
| `appid.mgmt.nominate.user` | Create a profile for a future user. | Manager, Writer |
| `appid.mgmt.update.cd.get.email.dispatcher` | View the email provider configuration. | Manager, Reader, Writer |
| `appid.mgmt.update.cd.set.email.dispatcher` | Configure or update an email provider. | Manager, Writer |
| `appid.mgmt.update.cd.post.email.dispatcher.test` | Test the email provider configuration. | Manager, Writer |
| `appid.mgmt.add.application` | Register a new application with App ID. | Manager, Writer |
| `appid.mgmt.delete.application` | Delete an application that is registered with App ID | Manager, Writer |
| `appid.mgmt.update.application` | Update an application that is registered with App ID. | Manager, Writer |
| `appid.mgmt.get.applications` | View all of the apps that are registered with your instance of App ID. | Manager, Reader, Writer |
| `appid.mgmt.get.application` | View a specific application that is registered with App ID. | Manager, Reader, Writer |
| `appid.mgmt.export.cd.users` | Export Cloud Directory users and their information as a JSON object. | Manager |
| `appid.mgmt.import.cd.users` | Import the Cloud Directory users and their information that was exported from another instance of the service. | Manager |
| `appid.mgmt.get.capture.runtime.activity` | Get the auditing status of the tenant as a JSON object. | Manager, Reader, Writer |
| `appid.mgmt.update.capture.runtime.activity` | Update the auditing status. | Manager, Writer |
| `appid.mgmt.get.mfa.channels` | Get a list of all of the configured MFA channels. | Manager, Reader, Writer |
| `appid.mgmt.get.mfa.channel` | Get an MFA channel. | Manager, Reader, Writer |
| `appid.mgmt.update.mfa.channel` | Update an MFA channel. | Manager, Writer |
| `appid.mgmt.update.mfa.config` | Update an MFA configuration. | Manager, Writer |
| `appid.mgmt.get.mfa.config` | View the current MFA configuration. | Manager, Reader, Writer |
| `appid.mgmt.get.advanced.password.management` | View the current advanced password policy configuration. | Manager, Reader, Writer |
| `appid.mgmt.set.advanced.password.management` | Configure advanced password policies. | Manager, Writer |
| `appid.mgmt.get.sso.config` | Get the Cloud Directory SSO configuration. | Manager, Reader, Writer |
| `appid.mgmt.update.sso.config` | Update the Cloud Directory SSO configuration. | Manager, Writer |
| `appid.mgmt.post.sso.logout` | Initiate SSO logout for Cloud Directory. | Manager, Writer |
| `appid.mgmt.cd.post.sms.dispatcher.test` | Test the MFA configuration for SMS. | Manager, Writer |
| `appid.mgmt.remove.cd.user` | Delete Cloud Directory users and their profile. | Manager, Writer |
| `appid.mgmt.get.cd.userinfo` | Get a Cloud Directory user and their information. | Manager, Reader, Writer |
| `appid.mgmt.get.cd.rate.config` | Get the rate limite configuration. | Manager, Reader, Writer |
| `appid.mgmt.update.cd.rate.config` | Update the rate limit configuration. | Manager, Writer |
| `appid.mgmt.import.profiles` | Import user profiles that have been exported from another instance of App ID. | Manager |
| `appid.mgmt.export.profiles` | Export user profiles. | Manager |
| `appid.mgmt.add.scope` | Add a scope to an application. | Manager, Writer |
| `appid.mgmt.get.scopes` | Get the scopes that are associated with an application. | Manager, Reader, Writer |
| `appid.mgmt.delete.scope` | Delete a scope that is associated with an application. | Manager, Writer |
| `appid.mgmt.add.role` | Create a role. | Manager, Writer |
| `appid.mgmt.get.role` | Get a role that is associated with a scope. | Manager, Reader, Writer |
| `appid.mgmt.update.role` | Update a role. | Manager, Writer |
| `appid.mgmt.delete.role` | Delete a role. | Manager, Writer |
| `appid.mgmt.get.user.roles` | View the roles that are assigned to a specific user. | Manager, Reader, Writer |
| `appid.mgmt.update.user.roles` | Update a user's associated roles. | Manager, Writer |
| `appid.mgmt.get.webhook.config` | Get a registered extension's configuration. | Manager, Reader, Writer |
| `appid.mgmt.update.webhook.config` | Update a registered extensions configuration. | Manager, Writer |
| `appid.mgmt.update.webhook.active` | Update the status of a registered extension's configuration. | Manager, Writer |
| `appid.mgmt.test.webhook.config` | Test the configuration for a registered extension. | Manager, Writer |
| `appid.mgmt.del.totp.channel` | appid-mgmt-del-totp-channel | Manager, Writer |
| `appid.mgmt.get.application.roles` | Get application roles | Manager, Reader, Writer |
| `appid.mgmt.update.application.roles` | Update application roles | Manager, Writer |
{: caption="Table 6. Service actions - App ID" caption-side="top"}
{: #actions-table6}
{: tab-title="Actions"}
{: tab-group="appid"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Auto Scale for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.instance-group` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 7. Platform roles - Auto Scale for VPC" caption-side="top"}
{: #platform-roles-table7}
{: tab-title="Platform roles"}
{: tab-group="is.instance-group"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.instance-group.instance-group.read` | Read an Instance Group | Administrator, Editor, Operator, Viewer |
| `is.instance-group.instance-group.create` | Create an Instance Group | Administrator, Editor |
| `is.instance-group.instance-group.update` | Update an Instance Group | Administrator, Editor |
| `is.instance-group.instance-group.delete` | Delete an Instance Group | Administrator, Editor |
| `is.instance-group.instance-group.list` | List Instance Groups | Administrator, Editor, Operator, Viewer |
{: caption="Table 7. Service actions - Auto Scale for VPC" caption-side="top"}
{: #actions-table7}
{: tab-title="Actions"}
{: tab-group="is.instance-group"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Billing
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `billing` for the service name.

No supported roles.
## Block Storage for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.volume` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 9. Platform roles - Block Storage for VPC" caption-side="top"}
{: #platform-roles-table9}
{: tab-title="Platform roles"}
{: tab-group="is.volume"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.volume.profile.view` |  | Administrator, Editor, Operator, Viewer |
| `is.volume.volume.create` |  | Administrator, Editor |
| `is.volume.volume.list` |  | Administrator, Editor, Operator, Viewer |
| `is.volume.volume.read` |  | Administrator, Editor, Operator, Viewer |
| `is.volume.volume.update` |  | Administrator, Editor |
| `is.volume.volume.delete` |  | Administrator, Editor |
{: caption="Table 9. Service actions - Block Storage for VPC" caption-side="top"}
{: #actions-table9}
{: tab-title="Actions"}
{: tab-group="is.volume"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Blockchain Platform
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `blockchain` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 10. Service roles - Blockchain Platform" caption-side="top"}
{: #service-roles-table10}
{: tab-title="Service roles"}
{: tab-group="blockchain"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `blockchain.components.create` | Can create (provision) Orderes/CAs/Peers | Manager |
| `blockchain.components.remove` | Can remove imported Orderes/CAs/Peers | Manager, Writer |
| `blockchain.components.import` | Can import external Orderes/CAs/Peers | Manager, Writer |
| `blockchain.components.export` | Can export any Orderes/CAs/Peers | Manager, Reader, Writer |
| `blockchain.optools.restart` | Can restart the UI server | Manager |
| `blockchain.optools.logs` | Can change logging settings of the UI | Manager |
| `blockchain.optools.view` | Can view the UI & logs as well as run any GET api | Manager, Reader, Writer |
| `blockchain.notifications.manage` | Can add/remove UI notifications | Manager, Writer |
| `blockchain.components.delete` | Can remove provisioned Orderes/CAs/Peers | Manager |
| `blockchain.signaturecollection.manage` | Can add/remove signature collections | Manager, Writer |
| `blockchain.optools.settings` | Can change UI settings | Manager |
| `blockchain.components.manage` | Can manage admin certs on Peers/Orderers as well as enroll ids on CAs | Manager, Writer |
| `blockchain.instance.link` | Can associate an IBM Blockchain Platform service instance with a cluster | Manager |
| `blockchain.instance.view` | Can get the status of the an IBM Blockchain Platform service instance | Manager, Reader, Writer |
| `blockchain.optools.redeploy` | Can redeploy an IBM Blockchain Platform service instance | Manager |
{: caption="Table 10. Service actions - Blockchain Platform" caption-side="top"}
{: #actions-table10}
{: tab-title="Actions"}
{: tab-group="blockchain"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Catalog Management
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `globalcatalog-collection` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
{: row-headers}
{: caption="Table 11. Platform roles - Catalog Management" caption-side="top"}
{: #platform-roles-table11}
{: tab-title="Platform roles"}
{: tab-group="globalcatalog-collection"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| IBMOperation | (Internal) - IBM Use only |
| Publisher | You can publish offerings that are approved by IBM and that are in a private catalog to which you're assigned the viewer role. |
{: row-headers}
{: caption="Table 11. Service roles - Catalog Management" caption-side="top"}
{: #service-roles-table11}
{: tab-title="Service roles"}
{: tab-group="globalcatalog-collection"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `globalcatalog-collection.instance.promote` | Publish item to public, assuming also has viewer access. | Administrator, Publisher |
| `globalcatalog-collection.operation.approve` | This action approves the publishing of items to public. Only IBM can use this action. | Publisher |
| `globalcatalog-collection.account.manage` | This action manages account level settings, e.g. Hiding the public catalog from the account members. | Administrator |
| `globalcatalog-collection.support.janitor` | (Internal) Janitor support | IBMOperation |
| `globalcatalog-collection.support.approveibm` | (Internal) - Approve publishing to IBM only | IBMOperation |
| `globalcatalog-collection.support.approvepublic` | (Internal) Approve publishing to public | IBMOperation |
| `globalcatalog-collection.support.approveshare` | (Internal) Approve publishing to Shared | IBMOperation |
{: caption="Table 11. Service actions - Catalog Management" caption-side="top"}
{: #actions-table11}
{: tab-title="Actions"}
{: tab-group="globalcatalog-collection"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Certificate Manager
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `cloudcerts` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Service Configuration Reader | The ability to read services configuration for Governance management. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 12. Service roles - Certificate Manager" caption-side="top"}
{: #service-roles-table12}
{: tab-title="Service roles"}
{: tab-group="cloudcerts"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `cloudcerts.certificate.import` | Re/Import a certificate and its private key. | Manager |
| `cloudcerts.certificate.delete` | Delete a certificate | Manager |
| `cloudcerts.certificate.read` | Retrieve a certificate, its private key, and its intermediate certificate if present | Manager, Writer |
| `cloudcerts.certificate.update` | Update the name and description of a certificate | Manager, Writer |
| `cloudcerts.certificates.list` | Retrieve a list of all certificates and their associated metadata or perform a search for certificates | Manager, Reader, Writer |
| `cloudcerts.notifications.publickey` | Retrieve the public key for Callback URL notifications | Manager, Reader, Writer |
| `cloudcerts.certificate.order` | Order/Renew a certificate | Manager |
| `cloudcerts.certificate-metadata.read` | Retrieve the metadata of a certificate | Manager, Reader, Writer |
| `cloudcerts.notifications-channel.update` | Update the endpoint or state of a notification channel | Manager |
| `cloudcerts.notifications-channel.list` | Retrieve all notification channels | Manager, Reader, Writer |
| `cloudcerts.notifications-channel.delete` | Delete a notification channel | Manager |
| `cloudcerts.notifications-channel.test` | Test a notification channel | Manager, Reader, Writer |
| `cloudcerts.notifications-channel.create` | Create a new notification channel. | Manager |
| `cloudcerts.config.read` | Read configuration information | Service Configuration Reader |
{: caption="Table 12. Service actions - Certificate Manager" caption-side="top"}
{: #actions-table12}
{: tab-title="Actions"}
{: tab-group="cloudcerts"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Cloud Foundry Enterprise Environment
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `cfaas` for the service name.

No supported roles.
## CloudAMQP
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `cldamqp` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
{: row-headers}
{: caption="Table 14. Platform roles - CloudAMQP" caption-side="top"}
{: #platform-roles-table14}
{: tab-title="Platform roles"}
{: tab-group="cldamqp"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `cldamqp.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 14. Service actions - CloudAMQP" caption-side="top"}
{: #actions-table14}
{: tab-title="Actions"}
{: tab-group="cldamqp"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Cloudant
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `cloudantnosqldb` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 15. Platform roles - Cloudant" caption-side="top"}
{: #platform-roles-table15}
{: tab-title="Platform roles"}
{: tab-group="cloudantnosqldb"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Checkpointer | As a Checkpointer, you have permissions to write _local documents enabling checkpoint writes. checkpoints are local documents optionally creaded during replicaton recording their state. |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Monitor | As a Monitor, you have permissions to get information about specified databases, list databases, monitor indexing and replication, view data volume usage and view provisioned and current throughput. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 15. Service roles - Cloudant" caption-side="top"}
{: #service-roles-table15}
{: tab-title="Service roles"}
{: tab-group="cloudantnosqldb"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `cloudantnosqldb.db.any` | Perform any database action | Manager |
| `cloudantnosqldb.activity-tracker-event-types.read` | Access list of configured activity tracker event types for a service instance | Administrator, Editor, Manager, Operator, Reader, Viewer, Writer |
| `cloudantnosqldb.activity-tracker-event-types.write` | Update list of configured activity tracker event types for a service instance | Administrator, Manager, Operator |
| `cloudantnosqldb.sapi.lastactivity` | Access last activity time for account | Manager |
| `cloudantnosqldb.sapi.usercors` | Update CORS settings for a service instance | Manager |
| `cloudantnosqldb.sapi.apikeys` | Generate Cloudant API keys for a service instance | Manager |
| `cloudantnosqldb.sapi.userccmdiagnostics` | Access current and maximum allowed throughput values | Manager |
| `cloudantnosqldb.sapi.supportattachments` | View attachments on support tickets for user | Manager |
| `cloudantnosqldb.sapi.supporttickets` | View support tickets for user | Manager |
| `cloudantnosqldb.sapi.userinfo` | Retrieve basic user infomation for this user | Administrator, Editor, Manager, Operator, Viewer |
| `cloudantnosqldb.users-database-info.read` | Read _users database info | Manager |
| `cloudantnosqldb.users-database.create` | Create users databases | Manager |
| `cloudantnosqldb.users-database.delete` | Delete users databases | Manager |
| `cloudantnosqldb.users.read` | Read from users databases | Manager |
| `cloudantnosqldb.users.write` | Write to users databases | Manager |
| `cloudantnosqldb.database.create` | Create databases | Manager |
| `cloudantnosqldb.database.delete` | Delete databases | Manager |
| `cloudantnosqldb.sapi.userplan` | Retrieve and update instance plan settings | Administrator, Editor, Manager, Operator, Viewer |
| `cloudantnosqldb.sapi.usage-data-volume` | View instance data usage | Administrator, Editor, Manager, Monitor, Operator, Viewer |
| `cloudantnosqldb.sapi.usage-requests` | View instance requests usage | Manager |
| `cloudantnosqldb.account-active-tasks.read` | View active tasks for instance | Manager, Monitor |
| `cloudantnosqldb.sapi.db-security` | Allow update of database security | Manager |
| `cloudantnosqldb.session.write` | Write _session endpoint | Manager, Reader, Writer |
| `cloudantnosqldb.session.read` | Read _session endpoint | Manager, Reader, Writer |
| `cloudantnosqldb.session.delete` | Delete _session endpoint | Manager, Reader, Writer |
| `cloudantnosqldb.iam-session.write` | Write _iam_session endpoint | Manager, Reader, Writer |
| `cloudantnosqldb.iam-session.read` | Read _iam_session endpoint | Manager, Reader, Writer |
| `cloudantnosqldb.iam-session.delete` | Delete _iam_session endpoint | Manager, Reader, Writer |
| `cloudantnosqldb.account-db-updates.read` | Read db_updates feed | Manager, Reader, Writer |
| `cloudantnosqldb.any-document.read` | Read any documents in a normal database | Manager, Reader, Writer |
| `cloudantnosqldb.database-info.read` | Read /db/ database info | Manager, Monitor, Reader, Writer |
| `cloudantnosqldb.account-dbs-info.read` | Read _dbs_info endpoint | Manager, Monitor, Reader, Writer |
| `cloudantnosqldb.replicator-database-info.read` | Read _replicator database info | Manager |
| `cloudantnosqldb.replicator-database.create` | Create _replicator databases | Manager |
| `cloudantnosqldb.replicator-database.delete` | Delete _replicator databases | Manager |
| `cloudantnosqldb.replication.write` | Write to _replicator databases | Manager |
| `cloudantnosqldb.replication.read` | Read from _replicator databases | Manager |
| `cloudantnosqldb.replication-scheduler.read` | Read from replication _scheduler endpoints | Manager, Monitor |
| `cloudantnosqldb.account-up.read` | View _up | Manager, Monitor |
| `cloudantnosqldb.account-uuids.read` | Generate doc ID UUIDs | Manager, Writer |
| `cloudantnosqldb.data-document.write` | Create, update and delete normal documents in a database | Manager, Writer |
| `cloudantnosqldb.local-document.write` | Write _local documents | Checkpointer, Manager, Writer |
| `cloudantnosqldb.design-document.write` | Write _design documents | Manager |
| `cloudantnosqldb.cluster-membership.read` | View cluster membership | Manager |
| `cloudantnosqldb.database-security.read` | Read database security definitions | Manager |
| `cloudantnosqldb.database-security.write` | Write database security definitions | Manager |
| `cloudantnosqldb.database-shards.read` | View database shard metadata | Manager, Monitor |
| `cloudantnosqldb.capacity-throughput.read` | Read current provisioned throughput | Administrator, Editor, Manager, Monitor, Operator, Viewer |
| `cloudantnosqldb.capacity-throughput.write` | Update provisioned throughput capacity | Administrator, Editor, Manager |
| `cloudantnosqldb.current-throughput.read` | Read current request throughput | Manager, Monitor |
| `cloudantnosqldb.limits-throughput.read` | Read throughput limits for current Plan | Manager |
| `cloudantnosqldb.account-all-dbs.read` | List all databases | Manager, Monitor, Reader, Writer |
| `cloudantnosqldb.account-deleted-dbs.list` | List deleted databases | Manager, Monitor |
| `cloudantnosqldb.account-deleted-dbs.restore` | Restore deleted database | Manager |
| `cloudantnosqldb.account-deleted-dbs.delete` | Delete deleted database | Manager |
| `cloudantnosqldb.account-meta-info.read` | View account metadata | Manager, Monitor, Reader, Writer |
| `cloudantnosqldb.database-ensure-full-commit.execute` | Call _ensure_full_commit endpoint | Manager, Writer |
| `cloudantnosqldb.account-search-analyze.execute` | Call _search_analyze endpoint | Manager, Reader, Writer |
| `cloudantnosqldb.couchdbextension-instance.read` | View metadata of an Extension for Apache CouchDB instance | Manager |
| `cloudantnosqldb.couchdbextension-instance.write` | Make changes to an Extension for Apache CouchDB instance | Manager |
{: caption="Table 15. Service actions - Cloudant" caption-side="top"}
{: #actions-table15}
{: tab-title="Actions"}
{: tab-group="cloudantnosqldb"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Code Engine
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `codeengine` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 16. Platform roles - Code Engine" caption-side="top"}
{: #platform-roles-table16}
{: tab-title="Platform roles"}
{: tab-group="codeengine"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 16. Service roles - Code Engine" caption-side="top"}
{: #service-roles-table16}
{: tab-title="Service roles"}
{: tab-group="codeengine"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `codeengine.dashboard.view` | View Dashboard | Administrator, Editor, Operator |
| `codeengine.tenant.read` | View project details | Manager, Reader, Writer |
| `codeengine.tenant.entities.create` | Create project contents, such as applications, job definitions, and jobs | Manager, Writer |
| `codeengine.tenant.entities.update` | Modify existing items already contained by a project, such as applications, jobs, or job definitions.  This does not include the ability to create or delete these items. | Manager, Writer |
| `codeengine.tenant.entities.delete` | Delete existing items from within a project | Manager, Writer |
| `codeengine.tenant.entities.read` | List and view existing items within a project | Manager, Reader, Writer |
{: caption="Table 16. Service actions - Code Engine" caption-side="top"}
{: #actions-table16}
{: tab-title="Actions"}
{: tab-group="codeengine"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Compare and Comply
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `compare-comply` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 17. Platform roles - Compare and Comply" caption-side="top"}
{: #platform-roles-table17}
{: tab-title="Platform roles"}
{: tab-group="compare-comply"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 17. Service roles - Compare and Comply" caption-side="top"}
{: #service-roles-table17}
{: tab-title="Service roles"}
{: tab-group="compare-comply"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `compare-comply.dashboard.view` |  | Administrator, Editor, Operator |
| `GET /compare-comply` |  | Manager, Reader, Writer |
| `POST /compare-comply` |  | Manager, Reader, Writer |
| `PUT /compare-comply` |  | Manager, Reader, Writer |
| `DELETE /compare-comply` |  | Manager, Reader, Writer |
{: caption="Table 17. Service actions - Compare and Comply" caption-side="top"}
{: #actions-table17}
{: tab-title="Actions"}
{: tab-group="compare-comply"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Consult with IBM Garage
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `consult-with-icg-wes` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 18. Platform roles - Consult with IBM Garage" caption-side="top"}
{: #platform-roles-table18}
{: tab-title="Platform roles"}
{: tab-group="consult-with-icg-wes"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 18. Service roles - Consult with IBM Garage" caption-side="top"}
{: #service-roles-table18}
{: tab-title="Service roles"}
{: tab-group="consult-with-icg-wes"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `consult-with-icg-wes.dashboard.view` | The ability to view your provisioned Consult with IBM Garage services in the dashboard. | Administrator, Editor, Manager, Operator, Reader, Viewer, Writer |
{: caption="Table 18. Service actions - Consult with IBM Garage" caption-side="top"}
{: #actions-table18}
{: tab-title="Actions"}
{: tab-group="consult-with-icg-wes"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Container Registry
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `container-registry` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
{: row-headers}
{: caption="Table 19. Platform roles - Container Registry" caption-side="top"}
{: #platform-roles-table19}
{: tab-title="Platform roles"}
{: tab-group="container-registry"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Service Configuration Reader | The ability to read services configuration for Governance management. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 19. Service roles - Container Registry" caption-side="top"}
{: #service-roles-table19}
{: tab-title="Service roles"}
{: tab-group="container-registry"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `container-registry.exemption.manager` | Create an exemption for a security issue. Delete an exemption for a security issue. | Manager |
| `container-registry.image.push` | Push a container image. Sign a container image. Import IBM software that is downloaded from IBM Passport Advantage Online. Restore a deleted container image from the trash. Create a new container image that refers to a source image. | Manager, Writer |
| `container-registry.image.pull` | Pull a container image. Inspect the signature for a container image. Create a new image that refers to a source image. | Manager, Reader, Writer |
| `container-registry.namespace.create` | Add a namespace. | Manager |
| `container-registry.namespace.delete` | Remove a namespace. | Manager |
| `container-registry.image.delete` | Delete one or more container images. Remove a tag, or tags, from each specified container image in IBM Cloud Container Registry. Delete the signature for a container image. Clean up your namespaces by retaining only images that meet your criteria. Set a policy to clean up your namespaces by retaining only container images that meet your criteria. | Manager, Writer |
| `container-registry.namespace.list` | List your namespaces. | Manager, Reader |
| `container-registry.image.list` | List your container images. Display the container images that are in the trash. | Manager, Reader, Service Configuration Reader |
| `container-registry.image.vulnerabilities` | View a vulnerability assessment report for your container image. | Manager, Reader, Service Configuration Reader |
| `container-registry.image.inspect` | Display details about a specific container image. | Manager, Reader |
| `container-registry.image.build` | Build a container image. | Manager, Writer |
| `container-registry.quota.get` | Display your current quotas for traffic and storage, and usage information against those quotas. | Manager, Reader, Writer |
| `container-registry.quota.set` | Modify the specified quota. | Manager |
| `container-registry.plan.get` | Display your pricing plan. | Manager |
| `container-registry.plan.set` | Upgrade to the standard plan. | Manager |
| `container-registry.registrytoken.get` | Retrieve the specified token from the registry. | Administrator |
| `container-registry.registrytoken.delete` | Remove one or more specified tokens. | Administrator |
| `container-registry.registrytoken.bulkdelete` | Delete multiple registry tokens. | Administrator |
| `container-registry.registrytoken.list` | Display all tokens that exist for your IBM Cloud account. | Administrator |
| `container-registry.auth.set` | Enable IAM policy enforcement. | Manager |
| `container-registry.retention.analyze` | Clean up your namespaces by retaining only container images that meet your criteria. Set a policy to clean up your namespaces by retaining only container images that meet your criteria. | Manager, Reader |
| `container-registry.retention.get` | Get an image retention policy. | Manager, Reader |
| `container-registry.retention.set` | Set a policy to clean up your namespaces by retaining only container images that meet your criteria. | Manager, Writer |
| `container-registry.retention.list` | List the image retention policies for your account. | Manager, Reader |
| `container-registry.exemption.list` | List your exemptions for security issues.  List the types of security issues that you can exempt. | Manager, Reader |
| `container-registry.resource.discover` | Action used by GHoST to discover registry resources |  |
| `container-registry.settings.get` | Get Account Settings, such as whether platform metrics are enabled | Manager, Reader, Writer |
| `container-registry.settings.set` | Set Account Settings, such as whether platform metrics are enabled | Manager |
{: caption="Table 19. Service actions - Container Registry" caption-side="top"}
{: #actions-table19}
{: tab-title="Actions"}
{: tab-group="container-registry"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Continuous Delivery
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `continuous-delivery` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can modify the Authorized Users list. |
| Editor | As an editor, you can create, view, update, change the plan for, and delete instances of the Continuous Delivery service. |
| Operator | As an operator, you can view instances of the Continuous Delivery service. |
{: row-headers}
{: caption="Table 20. Platform roles - Continuous Delivery" caption-side="top"}
{: #platform-roles-table20}
{: tab-title="Platform roles"}
{: tab-group="continuous-delivery"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 20. Service roles - Continuous Delivery" caption-side="top"}
{: #service-roles-table20}
{: tab-title="Service roles"}
{: tab-group="continuous-delivery"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `continuous-delivery.dashboard.view` | View instances of the Continuous Delivery service. | Administrator, Editor, Operator |
| `continuous-delivery.instance.add-auth-users` | Add entries to the Authorized Users list on the Manage tab of a Continuous Delivery service instance. | Administrator, Manager, Writer |
| `continuous-delivery.instance.remove-auth-users` | Remove entries from the Authorized Users list on the Manage tab of a Continuous Delivery service instance. | Administrator, Manager, Writer |
| `continuous-delivery.instance.config-auth-users` | Configure authorized users. | Administrator, Manager |
{: caption="Table 20. Service actions - Continuous Delivery" caption-side="top"}
{: #actions-table20}
{: tab-title="Actions"}
{: tab-group="continuous-delivery"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Db2
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `dashdb-for-transactions` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 21. Platform roles - Db2" caption-side="top"}
{: #platform-roles-table21}
{: tab-title="Platform roles"}
{: tab-group="dashdb-for-transactions"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
{: row-headers}
{: caption="Table 21. Service roles - Db2" caption-side="top"}
{: #service-roles-table21}
{: tab-title="Service roles"}
{: tab-group="dashdb-for-transactions"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `dashdb-for-transactions.console.access` | Allows users to view the Db2 Console. | Manager |
| `dashdb-for-transactions.console.manage-users` | Allows management of users for database access such as creating new users or assign and IAM user or service id to a database user. | Administrator, Manager |
| `dashdb-for-transactions.console.monitor` | Allows viewing of metrics and information that allow you to understand the resources your database is using or workload it is running. | Administrator, Editor, Operator, Viewer |
| `dashdb-for-transactions.console.scale` | scale operation | Administrator, Editor, Operator |
| `dashdb-for-transactions.console.backup` | backup operation | Administrator, Editor, Operator |
| `dashdb-for-transactions.console.restore` | restore operation | Administrator, Editor, Operator |
| `dashdb-for-transactions.console.settings` | set configuration | Administrator, Editor, Operator |
| `dashdb-for-transactions.console.view-settings` | view database settings | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployables` | Read Deployables | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/regions` | Read discover available regions | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/tasks/:task_id` | Read a Task | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/backups/:backup_id` | Read a backup | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployments/:deployment_id` | Read a Deployment | Administrator, Editor, Operator, Viewer |
| `PATCH /v4/:platform/deployments/:deployment_id` | Update a Deployment | Administrator, Editor, Operator |
| `GET /v4/:platform/deployables/:deployable_id/groups` | Read deployable group | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployments/:deployment_id/point_in_time_recovery_data` | Read all deployment point-in-time-recovery data | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployments/:deployment_id/tasks` | Read all deployment tasks | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployments/:deployment_id/backups` | Read all deployment backups | Administrator, Editor, Operator, Viewer |
| `POST /v4/:platform/deployments/:deployment_id/backups` | Create an on-demand backup | Administrator, Editor, Operator |
| `GET /v4/:platform/deployments/:deployment_id/remotes` | Read all deployment remotes | Administrator, Editor, Operator, Viewer |
| `DELETE /v4/:platform/deployments/:deployment_id/management/database_connections` | Kill all database connections | Administrator, Editor, Operator |
| `PATCH /v4/:platform/deployments/:deployment_id/configuration` | Update deployment configuration | Administrator, Editor, Operator |
| `GET /v4/:platform/deployments/:deployment_id/configuration` | Get deployment configuration | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployments/:deployment_id/configuration/schema` | Read deployment configuration schema | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployments/:deployment_id/groups` | Read Groups | Administrator, Editor, Operator, Viewer |
| `PATCH /v4/:platform/deployments/:deployment_id/groups/:group_id` | Update a group | Administrator, Editor, Operator |
| `POST /v4/:platform/deployments/:deployment_id/users` | Create a Db2 database user | Administrator, Editor, Operator |
| `GET /v4/:platform/deployments/:deployment_id/users/:user_id` | Read a Db2 database user | Administrator, Editor, Operator, Viewer |
| `PATCH /v4/:platform/deployments/:deployment_id/users/:user_id` | Update a Db2 database user | Administrator, Editor, Operator |
| `DELETE /v4/:platform/deployments/:deployment_id/users/:user_id` | Remove a Db2 database user | Administrator, Editor, Operator |
| `GET /v4/:platform/deployments/:deployment_id/groups/:group_id/autoscaling` | Read autoscaling configuration | Administrator, Editor, Operator, Viewer |
| `PATCH /v4/:platform/deployments/:deployment_id/groups/:group_id/autoscaling` | Update autoscaling configuration | Administrator, Editor, Operator |
| `GET /v4/:platform/deployments/:deployment_id/users/:user_id/connections` | Read deployment user connections | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployments/:deployment_id/users/:user_id/connections/:endpoint_type` | Read deployment user connections | Administrator, Editor, Operator, Viewer |
| `POST /v4/:platform/deployments/:deployment_id/users/:user_id/connections` | Create deployment user connection | Administrator, Editor, Operator, Viewer |
| `POST /v4/:platform/deployments/:deployment_id/users/:user_id/connections/:endpoint_type` | Create deployment user connection | Administrator, Editor, Operator, Viewer |
| `GET /v4/:platform/deployments/:deployment_id/whitelists/ip_addresses` | Read whitelisted IP addresses | Administrator, Editor, Operator, Viewer |
| `POST /v4/:platform/deployments/:deployment_id/whitelists/ip_addresses` | Create whitelisted IP addresses | Administrator, Editor, Operator |
| `DELETE /v4/:platform/deployments/:deployment_id/whitelists/ip_addresses/:ip_address_id` | Remove a whitelisted IP address | Administrator, Editor, Operator |
| `PUT /v4/:platform/deployments/:deployment_id/whitelists/ip_addresses` | Bulk add whitelist IP addresses | Administrator, Editor, Operator |
| `GET /2017-12/:platform/tasks/:task_id` | Read a task | Administrator, Editor, Operator, Viewer |
| `GET /2017-12/:platform/backups/:backup_id` | Read a backup | Administrator, Editor, Operator, Viewer |
| `GET /2017-12/:platform/deployments/:deployment_id` | Read a deployment | Administrator, Editor, Operator, Viewer |
| `DELETE /2017-12/:platform/deployments/:deployment_id` | Remove a deployment | Administrator, Editor, Operator |
| `GET /2017-12/:platform/deployments/:deployment_id/tasks` | Read all deployment tasks | Administrator, Editor, Operator, Viewer |
| `GET /2017-12/:platform/deployments/:deployment_id/backups` | Read all deployment backups | Administrator, Editor, Operator, Viewer |
| `POST /2017-12/:platform/clusters/:cluster_id/deployments` | Create a deployment | Administrator, Editor, Operator |
| `POST /v4/:platform/deployments/:deployment_id/inplace_restores` | Perform in place database restore | Administrator, Editor, Operator |
| `PATCH /v4/:platform/deployments/:deployment_id/groups/member` | Update scaling member configuration | Administrator, Editor, Operator |
| `PATCH /v4/:platform/deployments/:deployment_id/users/:user_id/adminpassword` | Update admin password | Administrator, Editor, Operator |
| `PATCH /v4/:platform/deployments/:deployment_id/users/:user_id/locked` | Update user locked state | Administrator, Editor, Operator |
| `POST /v4/:platform/deployments/:deployment_id/describe_updates` | Get db updates | Administrator, Editor, Operator, Viewer |
| `POST /v4/:platform/deployments/:deployment_id/db_updates` | Create db update | Administrator, Editor, Operator |
| `PATCH /v4/:platform/deployments/:deployment_id/users/:user_id/password` | Update password | Administrator, Editor, Operator |
| `PATCH /v4/:platform/deployments/:deployment_id/billable` | Set billable annotation to true | Administrator, Editor, Operator |
| `PATCH /v4/:platform/deployments/:deployment_id/migrated` | Set migration flag to false | Administrator, Editor, Operator |
| `GET /v4/:platform/deployments/:deployment_id/check_updates` | Check deployment for available updates | Administrator, Editor, Operator, Viewer |
{: caption="Table 21. Service actions - Db2" caption-side="top"}
{: #actions-table21}
{: tab-title="Actions"}
{: tab-group="dashdb-for-transactions"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Db2 Warehouse
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `dashdb` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 22. Service roles - Db2 Warehouse" caption-side="top"}
{: #service-roles-table22}
{: tab-title="Service roles"}
{: tab-group="dashdb"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `dashdb.console.access` |  | Manager, Writer |
{: caption="Table 22. Service actions - Db2 Warehouse" caption-side="top"}
{: #actions-table22}
{: tab-title="Actions"}
{: tab-group="dashdb"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Direct Link
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `directlink` for the service name.

No supported roles.
## Direct Link Connect
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `directlink.connect` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 24. Platform roles - Direct Link Connect" caption-side="top"}
{: #platform-roles-table24}
{: tab-title="Platform roles"}
{: tab-group="directlink.connect"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `directlink.connect.view` | View | Administrator, Editor, Operator, Viewer |
| `directlink.connect.edit` | Edit | Administrator, Editor |
{: caption="Table 24. Service actions - Direct Link Connect" caption-side="top"}
{: #actions-table24}
{: tab-title="Actions"}
{: tab-group="directlink.connect"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Direct Link Dedicated
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `directlink.dedicated` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 25. Platform roles - Direct Link Dedicated" caption-side="top"}
{: #platform-roles-table25}
{: tab-title="Platform roles"}
{: tab-group="directlink.dedicated"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `directlink.dedicated.view` | View | Administrator, Editor, Operator, Viewer |
| `directlink.dedicated.edit` | Edit | Administrator, Editor |
{: caption="Table 25. Service actions - Direct Link Dedicated" caption-side="top"}
{: #actions-table25}
{: tab-title="Actions"}
{: tab-group="directlink.dedicated"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Discovery
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `discovery` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 26. Service roles - Discovery" caption-side="top"}
{: #service-roles-table26}
{: tab-title="Service roles"}
{: tab-group="discovery"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `PUT /discovery` | Update existing resources | Manager, Writer |
| `POST /discovery` | Create new resources | Manager, Writer |
| `DELETE /discovery` | Delete resources | Manager, Writer |
| `PATCH /discovery` | Make partial update to resources | Manager, Writer |
| `GET /discovery` | Retrieve resources | Manager, Reader, Writer |
{: caption="Table 26. Service actions - Discovery" caption-side="top"}
{: #actions-table26}
{: tab-title="Actions"}
{: tab-group="discovery"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## DNS Services
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `dns-svcs` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 27. Platform roles - DNS Services" caption-side="top"}
{: #platform-roles-table27}
{: tab-title="Platform roles"}
{: tab-group="dns-svcs"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 27. Service roles - DNS Services" caption-side="top"}
{: #service-roles-table27}
{: tab-title="Service roles"}
{: tab-group="dns-svcs"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `dns-svcs.dashboard.view` |  | Administrator, Editor, Operator |
| `dns-svcs.zones.read` |  | Manager, Reader, Writer |
| `dns-svcs.zones.update` |  | Manager, Writer |
| `dns-svcs.zones.manage` |  | Manager |
| `dns-svcs.resource-records.manage` |  | Manager |
| `dns-svcs.resource-records.update` |  | Manager, Writer |
| `dns-svcs.resource-records.read` |  | Manager, Reader, Writer |
| `dns-svcs.acls.manage` |  | Manager |
| `dns-svcs.acls.update` |  | Manager, Writer |
| `dns-svcs.acls.read` |  | Manager, Reader, Writer |
| `dns-svcs.permitted-networks.manage` |  | Manager |
| `dns-svcs.permitted-networks.update` |  | Manager, Writer |
| `dns-svcs.permitted-networks.read` |  | Manager, Reader, Writer |
{: caption="Table 27. Service actions - DNS Services" caption-side="top"}
{: #actions-table27}
{: tab-title="Actions"}
{: tab-group="dns-svcs"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## ElephantSQL
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `esql` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
{: row-headers}
{: caption="Table 28. Platform roles - ElephantSQL" caption-side="top"}
{: #platform-roles-table28}
{: tab-title="Platform roles"}
{: tab-group="esql"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `esql.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 28. Service actions - ElephantSQL" caption-side="top"}
{: #actions-table28}
{: tab-title="Actions"}
{: tab-group="esql"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Enterprise
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `enterprise` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrators can update the enterprise, create accounts and account groups, move accounts between account groups, import existing accounts, and view usage reports. |
| Editor | Editors can update the enterprise, create accounts and account groups, view usage reports, and import accounts. |
| Operator | Operators can view the enterprise, account groups, and accounts. |
| Viewer | Viewers can view the enterprise, account groups, and accounts. |
{: row-headers}
{: caption="Table 29. Platform roles - Enterprise" caption-side="top"}
{: #platform-roles-table29}
{: tab-title="Platform roles"}
{: tab-group="enterprise"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Usage Report Viewer | Usage report viewers can view the usage reports for the entire enterprise, an account group and its accounts, or a specific account. |
{: row-headers}
{: caption="Table 29. Service roles - Enterprise" caption-side="top"}
{: #service-roles-table29}
{: tab-title="Service roles"}
{: tab-group="enterprise"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `enterprise.enterprise.create` |  | Administrator |
| `enterprise.enterprise.update` |  | Administrator, Editor |
| `enterprise.enterprise.retrieve` |  | Administrator, Editor, Operator, Usage Report Viewer, Viewer |
| `enterprise.enterprise.import` |  | Administrator, Editor |
| `enterprise.enterprise.system-update` |  |  |
| `enterprise.enterprise.retrieve-usage-report` |  | Administrator, Editor, Usage Report Viewer |
| `enterprise.enterprise.attach-config-rules` |  | Administrator |
| `enterprise.enterprise.detach-config-rules` |  | Administrator |
| `enterprise.enterprise.update-config-rules` |  | Administrator |
| `enterprise.account-group.create` |  | Administrator, Editor |
| `enterprise.account-group.update` |  | Administrator, Editor |
| `enterprise.account-group.retrieve` |  | Administrator, Editor, Operator, Usage Report Viewer, Viewer |
| `enterprise.account-group.retrieve-usage-report` |  | Administrator, Editor, Usage Report Viewer |
| `enterprise.account-group.attach-config-rules` |  | Administrator |
| `enterprise.account-group.detach-config-rules` |  | Administrator |
| `enterprise.account-group.update-config-rules` |  | Administrator |
| `enterprise.account.create` |  | Administrator, Editor |
| `enterprise.account.update` |  | Administrator, Editor |
| `enterprise.account.move` |  | Administrator |
| `enterprise.account.retrieve` |  | Administrator, Editor, Operator, Usage Report Viewer, Viewer |
| `enterprise.account.retrieve-usage-report` |  | Administrator, Editor, Usage Report Viewer |
| `enterprise.account.attach-config-rules` |  | Administrator |
| `enterprise.account.detach-config-rules` |  | Administrator |
| `enterprise.account.update-config-rules` |  | Administrator |
{: caption="Table 29. Service actions - Enterprise" caption-side="top"}
{: #actions-table29}
{: tab-title="Actions"}
{: tab-group="enterprise"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Event Streams
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `messagehub` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 30. Service roles - Event Streams" caption-side="top"}
{: #service-roles-table30}
{: tab-title="Service roles"}
{: tab-group="messagehub"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `messagehub.topic.read` | Allow an app to read messages from all topics, or if applied to a named topic, then just that single topic. | Manager, Reader, Writer |
| `messagehub.topic.write` | Allow an app to write messages to all topics, or if applied to a named topic, then just that single topic. | Manager, Writer |
| `messagehub.topic.manage` | Allow an app or user to create or delete topic. If applied to a named topic, then only topics of that name can be created or deleted. | Manager |
| `messagehub.cluster.read` | Allow an app to connect to a service instance and read its state, including listing consumer groups, topics and offsets and describing consumer groups, topics and broker configurations. | Manager, Reader, Writer |
| `messagehub.group.read` | Allow an app to join and commit offsets in a consumer group. | Manager, Reader, Writer |
| `messagehub.group.manage` | Allow an app or user to delete a Consumer Group. If applied to a group ID, then only the consumer group with that ID can be deleted. | Manager |
| `messagehub.txnid.write` | Allow an app to produce messages transactionally. | Manager, Writer |
| `messagehub.schema.read` | Read a schema/schema version | Manager, Reader, Writer |
| `messagehub.schema.write` | Create a schema/schema version | Manager, Writer |
| `messagehub.schema.manage` | Delete a schema/schema version | Manager |
| `messagehub.cluster.manage` | Manage the configuration of an Event Streams instance | Manager |
{: caption="Table 30. Service actions - Event Streams" caption-side="top"}
{: #actions-table30}
{: tab-title="Actions"}
{: tab-group="messagehub"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Floating IP for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.floating-ip` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 31. Platform roles - Floating IP for VPC" caption-side="top"}
{: #platform-roles-table31}
{: tab-title="Platform roles"}
{: tab-group="is.floating-ip"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.floating-ip.floating-ip.create` |  | Administrator, Editor |
| `is.floating-ip.floating-ip.delete` |  | Administrator, Editor |
| `is.floating-ip.floating-ip.update` |  | Administrator, Editor |
| `is.floating-ip.floating-ip.operate` |  | Administrator, Editor, Operator |
| `is.floating-ip.floating-ip.read` |  | Administrator, Editor, Operator, Viewer |
| `is.floating-ip.floating-ip.list` |  | Administrator, Editor, Operator, Viewer |
{: caption="Table 31. Service actions - Floating IP for VPC" caption-side="top"}
{: #actions-table31}
{: tab-title="Actions"}
{: tab-group="is.floating-ip"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Flow Logs for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.flow-log-collector` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 32. Platform roles - Flow Logs for VPC" caption-side="top"}
{: #platform-roles-table32}
{: tab-title="Platform roles"}
{: tab-group="is.flow-log-collector"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.flow-log-collector.flow-log-collector.read` | As an administrator, an editor, an operator or a viewer, you can view the details of a flow log collector | Administrator, Editor, Operator, Viewer |
| `is.flow-log-collector.flow-log-collector.update` | As an administrator or an editor, you can update a flow log collector | Administrator, Editor |
| `is.flow-log-collector.flow-log-collector.operate` | As an administrator, an editor or an operator, you can operate on a flow log collector | Administrator, Editor, Operator |
| `is.flow-log-collector.flow-log-collector.create` | As an administrator or an editor, you can create a flow log collector | Administrator, Editor |
| `is.flow-log-collector.flow-log-collector.delete` | As an administrator or an editor, you can delete a flow log collector | Administrator, Editor |
| `is.flow-log-collector.flow-log-collector.list` | List Flow Log Collectors | Administrator, Editor, Operator, Viewer |
{: caption="Table 32. Service actions - Flow Logs for VPC" caption-side="top"}
{: #actions-table32}
{: tab-title="Actions"}
{: tab-group="is.flow-log-collector"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Functions
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `functions` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 33. Service roles - Functions" caption-side="top"}
{: #service-roles-table33}
{: tab-title="Service roles"}
{: tab-group="functions"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `functions.namespaces.read` |  | Manager, Reader, Writer |
| `functions.namespaces.delete` |  | Manager |
| `functions.namespaces.update` |  | Manager |
| `functions.entities.create` |  | Manager, Writer |
| `functions.entities.update` |  | Manager, Writer |
| `functions.entities.delete` |  | Manager, Writer |
| `functions.entities.read` |  | Manager, Reader, Writer |
| `functions.entities.activate` |  | Manager, Reader, Writer |
{: caption="Table 33. Service actions - Functions" caption-side="top"}
{: #actions-table33}
{: tab-title="Actions"}
{: tab-group="functions"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Global Resource Catalog
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `globalcatalog` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrators can change object metadata or visibility for private services added to the account and can restrict the visibility of a public service. |
| Editor | Editors can change object metadata, but can?t change visibility for private services added to the account. |
| Operator | Operators can view private services added to the account. |
| Viewer | Viewers can view private services added to the account. |
{: row-headers}
{: caption="Table 34. Platform roles - Global Resource Catalog" caption-side="top"}
{: #platform-roles-table34}
{: tab-title="Platform roles"}
{: tab-group="globalcatalog"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `globalcatalog.is.admin` | Is Admin | Administrator |
| `globalcatalog.is.editor` | Is Editor | Editor |
| `globalcatalog.is.viewer` | Is Viewer | Operator, Viewer |
{: caption="Table 34. Service actions - Global Resource Catalog" caption-side="top"}
{: #actions-table34}
{: tab-title="Actions"}
{: tab-group="globalcatalog"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Globalization Pipeline
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `g11n-pipeline` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 35. Platform roles - Globalization Pipeline" caption-side="top"}
{: #platform-roles-table35}
{: tab-title="Platform roles"}
{: tab-group="g11n-pipeline"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 35. Service roles - Globalization Pipeline" caption-side="top"}
{: #service-roles-table35}
{: tab-title="Service roles"}
{: tab-group="g11n-pipeline"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `g11n-pipeline.dashboard.view` |  | Administrator, Editor, Operator |
| `g11n-pipeline.user.create-user` |  | Manager |
| `g11n-pipeline.document.delete-document` |  | Manager |
| `g11n-pipeline.document-translation-request.create-translation-request` |  | Manager |
| `g11n-pipeline.bundle.update-resource-entry-info` |  | Manager, Writer |
| `g11n-pipeline.translation-request.get-translation-requests` |  | Manager, Writer |
| `g11n-pipeline.document.create-document` |  | Manager |
| `g11n-pipeline.bundle.get-resource-strings` |  | Manager, Reader, Writer |
| `g11n-pipeline.xliff-document.update-documents-with-xliff` |  | Manager, Writer |
| `g11n-pipeline.user.update-user` |  | Manager |
| `g11n-pipeline.bundle.update-resource-entries` |  | Manager, Writer |
| `g11n-pipeline.translation-request.get-tr-resource-entry-info` |  | Manager, Writer |
| `g11n-pipeline.xliff.update-bundles-with-xliff` |  | Manager, Writer |
| `g11n-pipeline.bundle.upload-resource-entries` |  | Manager |
| `g11n-pipeline.document.get-document-list` |  | Manager, Writer |
| `g11n-pipeline.document-translation-request.get-tr-document-segment-info` |  | Manager, Writer |
| `g11n-pipeline.xliff.get-xliff-from-tr` |  | Manager, Writer |
| `g11n-pipeline.document-translation-request.update-translation-request` |  | Manager |
| `g11n-pipeline.document-translation-request.get-document-translation-request` |  | Manager, Writer |
| `g11n-pipeline.config.put-translation-config` |  | Manager |
| `g11n-pipeline.xliff-document.get-xliff-from-document-tr` |  | Manager, Writer |
| `g11n-pipeline.user.get-users` |  | Manager |
| `g11n-pipeline.config.put-mt-service-binding` |  | Manager |
| `g11n-pipeline.translation-request.update-translation-request` |  | Manager |
| `g11n-pipeline.document-translation-request.get-document-translation-requests` |  | Manager, Writer |
| `g11n-pipeline.user.get-user` |  | Manager, Writer |
| `g11n-pipeline.document-translation-request.get-tr-document-segments` |  | Manager, Writer |
| `g11n-pipeline.translation-request.get-tr-resource-entries` |  | Manager, Writer |
| `g11n-pipeline.document-translation-request.delete-document-translation-request` |  | Manager |
| `g11n-pipeline.bundle.delete-bundle` |  | Manager |
| `g11n-pipeline.bundle.get-resource-entry-info` |  | Manager, Writer |
| `g11n-pipeline.bundle.get-bundle-list` |  | Manager, Writer |
| `g11n-pipeline.bundle.create-bundle` |  | Manager |
| `g11n-pipeline.bundle.get-bundle-info` |  | Manager, Reader, Writer |
| `g11n-pipeline.bundle.update-bundle` |  | Manager |
| `g11n-pipeline.translation-request.get-tr-bundle-info` |  | Manager, Writer |
| `g11n-pipeline.config.get-all-mt-service-bindings` |  | Manager |
| `g11n-pipeline.service-instance.get-service-instance-info` |  | Manager, Writer |
| `g11n-pipeline.xliff.get-xliff-from-bundles` |  | Manager, Writer |
| `g11n-pipeline.config.delete-mt-service-binding` |  | Manager |
| `g11n-pipeline.config.get-translation-config` |  | Manager |
| `g11n-pipeline.user.delete-user` |  | Manager |
| `g11n-pipeline.document-translation-request.get-tr-document-info` |  | Manager, Writer |
| `g11n-pipeline.config.get-mt-service-binding` |  | Manager |
| `g11n-pipeline.config.delete-translation-config` |  | Manager |
| `g11n-pipeline.xliff-document.get-xliff-from-documents` |  | Manager, Writer |
| `g11n-pipeline.config.get-all-translation-configs` |  | Manager, Writer |
| `g11n-pipeline.translation-request.delete-translation-request` |  | Manager |
| `g11n-pipeline.translation-request.get-translation-request` |  | Manager, Writer |
| `g11n-pipeline.translation-request.create-translation-request` |  | Manager |
| `g11n-pipeline.bundle.get-bundle-info-full` |  | Manager, Writer |
| `g11n-pipeline.bundle.get-bundle-list-all` |  | Manager |
| `g11n-pipeline.bundle.get-resource-strings-all` |  | Manager, Writer |
| `g11n-pipeline.user.get-user-all` |  | Manager |
| `g11n-pipeline.bundle.update-resource-strings-src` |  | Manager |
| `g11n-pipeline.bundle.update-resource-entry-info-src` |  | Manager |
| `g11n-pipeline.document.get-document-content` |  | Manager, Reader, Writer |
| `g11n-pipeline.document.get-document-meta-data` |  | Manager, Reader, Writer |
| `g11n-pipeline.document.get-document-meta-data-full` |  | Manager, Writer |
| `g11n-pipeline.document.get-document-segments` |  | Manager, Writer |
| `g11n-pipeline.document.update-document-meta-data` |  | Manager |
| `g11n-pipeline.document.get-segment-info` |  | Manager, Writer |
| `g11n-pipeline.document.upload-document-content` |  | Manager |
| `g11n-pipeline.document.update-segment-translation` |  | Manager, Writer |
{: caption="Table 35. Service actions - Globalization Pipeline" caption-side="top"}
{: #actions-table35}
{: tab-title="Actions"}
{: tab-group="g11n-pipeline"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## HPCaaS from Rescale
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `hpcaas-from-rescale-prod` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
{: row-headers}
{: caption="Table 36. Platform roles - HPCaaS from Rescale" caption-side="top"}
{: #platform-roles-table36}
{: tab-title="Platform roles"}
{: tab-group="hpcaas-from-rescale-prod"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `hpcaas-from-rescale-prod.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 36. Service actions - HPCaaS from Rescale" caption-side="top"}
{: #actions-table36}
{: tab-title="Actions"}
{: tab-group="hpcaas-from-rescale-prod"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Hyper Protect Crypto Services
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `hs-crypto` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 37. Platform roles - Hyper Protect Crypto Services" caption-side="top"}
{: #platform-roles-table37}
{: tab-title="Platform roles"}
{: tab-group="hs-crypto"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Reader Plus | As a reader plus, you can perform read-only actions within the service such as viewing service-specific resources. You can also access key material of standard keys. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 37. Service roles - Hyper Protect Crypto Services" caption-side="top"}
{: #service-roles-table37}
{: tab-title="Service roles"}
{: tab-group="hs-crypto"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `hs-crypto.crypto.decrypt` | hs-crypto.crypto.decrypt | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.derivekey` | hs-crypto.crypto.derivekey | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.digest` | hs-crypto.crypto.digest | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.digestkey` | hs-crypto.crypto.digestkey | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.encrypt` | hs-crypto.crypto.encrypt | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.generatekey` | hs-crypto.crypto.generatekey | Manager, Writer |
| `hs-crypto.crypto.generatekeypair` | hs-crypto.crypto.generatekeypair | Manager, Writer |
| `hs-crypto.crypto.generaterandom` | hs-crypto.crypto.generaterandom | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.getattributevalue` | hs-crypto.crypto.getattributevalue | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.getmechanisminfo` | hs-crypto.crypto.getmechanisminfo | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.getmechanismlist` | hs-crypto.crypto.getmechanismlist | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.rewrapkeyblob` | hs-crypto.crypto.rewrapkeyblob | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.setattributevalue` | hs-crypto.crypto.setattributevalue | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.sign` | hs-crypto.crypto.sign | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.unwrapkey` | hs-crypto.crypto.unwrapkey | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.verify` | hs-crypto.crypto.verify | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.crypto.wrapkey` | hs-crypto.crypto.wrapkey | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.keystore.createkeystore` | hs-crypto.keystore.createkeystore | Manager |
| `hs-crypto.keystore.deletekey` | hs-crypto.keystore.deletekey | Manager, Writer |
| `hs-crypto.keystore.deletekeystore` | hs-crypto.keystore.deletekeystore | Manager |
| `hs-crypto.keystore.listkeysbyattributes` | hs-crypto.keystore.listkeysbyattributes | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.keystore.listkeysbyids` | hs-crypto.keystore.listkeysbyids | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.keystore.listkeystoresbyattributes` | hs-crypto.keystore.listkeystoresbyattributes | Manager |
| `hs-crypto.keystore.listkeystoresbyids` | hs-crypto.keystore.listkeystoresbyids | Manager |
| `hs-crypto.keystore.storenewkey` | hs-crypto.keystore.storenewkey | Manager, Writer |
| `hs-crypto.keystore.updatekey` | hs-crypto.keystore.updatekey | Manager, Writer |
| `hs-crypto.dashboard.view` | View the dashboard | Administrator, Editor, Operator |
| `hs-crypto.instances.read` | Get Instance API endpoint info | Administrator, Editor, Manager, Reader, Reader Plus, Viewer, Writer |
| `hs-crypto.secrets.list` | Retrieve a list of encryption keys. | Administrator, Editor, Manager, Reader, Reader Plus, Viewer, Writer |
| `hs-crypto.secrets.wrap` | Retrieve a list of encryption keys. | Administrator, Editor, Manager, Reader, Reader Plus, Viewer, Writer |
| `hs-crypto.secrets.unwrap` | Unwrap an encryption key. | Administrator, Editor, Manager, Reader, Reader Plus, Viewer, Writer |
| `hs-crypto.secrets.create` | Create an encryption key. | Administrator, Editor, Manager, Writer |
| `hs-crypto.secrets.read` | Retrieve an encryption key. | Administrator, Editor, Manager, Reader Plus, Writer |
| `hs-crypto.secrets.delete` | Delete an encryption key. | Administrator, Manager |
| `hs-crypto.secrets.rotate` | Rotate an encryption key. | Administrator, Editor, Manager, Writer |
| `hs-crypto.instances.manage` | Manage instance via TKE. | Administrator, Manager |
| `hs-crypto.ep11.use` | Use the GREP11 Interface for Hyper Protect Crypto Services | Administrator, Editor, Manager, Reader, Reader Plus, Viewer, Writer |
| `hs-crypto.importtoken.create` | Allow creation of secure import tokens | Manager, Writer |
| `hs-crypto.importtoken.read` | Allow retrieval of secure import tokens | Manager, Writer |
| `hs-crypto.policies.read` | Retrieve policies for an encryption key | Manager |
| `hs-crypto.policies.write` | Set policies for an encryption key | Manager |
| `hs-crypto.instancepolicies.read` | Retrieve instance level policies | Manager |
| `hs-crypto.instancepolicies.write` | Add or update instance level policies | Manager |
| `hs-crypto.secrets.setkeyfordeletion` | Set or prepare an encryption key for deletion | Manager, Writer |
| `hs-crypto.secrets.unsetkeyfordeletion` | Unset an encryption key for deletion | Manager, Writer |
| `hs-crypto.secrets.readmetadata` | Retrieve the details of an encryption key | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.secrets.rewrap` | Rewrap an encryption key | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.registrations.list` | Retrieve a list of registrations | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.secrets.listkeyversions` | Retrieve a list of versions that are associated with an encryption key | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.registrations.listforkey` | Retrieve a list of registrations for a given encryption key | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.registrations.deactivate` | Move a suspended registration to the deactivated state | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.registrations.create` | Create a registration between an encryption key and a cloud resource | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.registrations.write` | Replace an existing registration | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.registrations.merge` | Update the details of an existing registration | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.registrations.delete` | Delete a registration | Manager, Reader, Reader Plus, Writer |
| `hs-crypto.secrets.disable` | Disable operations for an encryption key | Manager |
| `hs-crypto.secrets.enable` | Enable operations for an encryption key | Manager |
| `hs-crypto.secrets.restore` | Restore a previously deleted encryption key | Manager |
| `hs-crypto.secrets.eventack` | Acknowledge a key lifecycle event | Manager, Reader, Reader Plus, Writer |
{: caption="Table 37. Service actions - Hyper Protect Crypto Services" caption-side="top"}
{: #actions-table37}
{: tab-title="Actions"}
{: tab-group="hs-crypto"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Hyper Protect DBaaS for MongoDB
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `hyperp-dbaas-mongodb` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 38. Service roles - Hyper Protect DBaaS for MongoDB" caption-side="top"}
{: #service-roles-table38}
{: tab-title="Service roles"}
{: tab-group="hyperp-dbaas-mongodb"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `hyperp-dbaas-mongodb.clusters.read` | Get the detailed information about a database cluster | Manager, Reader, Writer |
| `hyperp-dbaas-mongodb.logging.enable` | Enable sending database logs and audit logs to the user's service instance of IBM Log Analysis with LogDNA | Manager, Writer |
| `hyperp-dbaas-mongodb.monitoring.enable` | Enable sending database metrics to a user-specified organization and space in the IBM Cloud Monitoring service | Manager, Writer |
| `hyperp-dbaas-mongodb.users.list` | List all database users | Manager, Reader, Writer |
| `hyperp-dbaas-mongodb.users.read` | Get the detailed information about a database user | Manager, Reader, Writer |
| `hyperp-dbaas-mongodb.databases.list` | List all databases | Manager, Reader, Writer |
| `hyperp-dbaas-mongodb.logs.list` | List database log files and audit log files | Manager, Reader, Writer |
| `hyperp-dbaas-mongodb.logs.read` | Download a database log file or an audit log file | Manager |
| `hyperp-dbaas-mongodb.clusters.tasks.list` | List the tasks running or recently run on a cluster | Manager, Reader, Writer |
| `hyperp-dbaas-mongodb.clusters.tasks.read` | Get the detailed information about a task | Manager, Reader, Writer |
| `hyperp-dbaas-mongodb.clusters.configuration.update` | Update the database configuration of your cluster | Manager |
| `hyperp-dbaas-mongodb.clusters.configuration.read` | Show the database configuration of your cluster | Manager, Reader, Writer |
{: caption="Table 38. Service actions - Hyper Protect DBaaS for MongoDB" caption-side="top"}
{: #actions-table38}
{: tab-title="Actions"}
{: tab-group="hyperp-dbaas-mongodb"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Hyper Protect DBaaS for PostgreSQL
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `hyperp-dbaas-postgresql` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 39. Service roles - Hyper Protect DBaaS for PostgreSQL" caption-side="top"}
{: #service-roles-table39}
{: tab-title="Service roles"}
{: tab-group="hyperp-dbaas-postgresql"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `hyperp-dbaas-postgresql.clusters.read` | Get the detailed information about a database cluster | Manager, Reader, Writer |
| `hyperp-dbaas-postgresql.logging.enable` | Enable sending database logs and audit logs to the user's service instance of IBM Log Analysis with LogDNA | Manager, Writer |
| `hyperp-dbaas-postgresql.monitoring.enable` | Enable sending database metrics to a user-specified organization and space in the IBM Cloud Monitoring service | Manager, Writer |
| `hyperp-dbaas-postgresql.users.list` | List all database users | Manager, Reader, Writer |
| `hyperp-dbaas-postgresql.users.read` | Get the detailed information about a database user | Manager, Reader, Writer |
| `hyperp-dbaas-postgresql.databases.list` | List all databases | Manager, Reader, Writer |
| `hyperp-dbaas-postgresql.logs.list` | List database log files and audit log files | Manager, Reader, Writer |
| `hyperp-dbaas-postgresql.logs.read` | Download a database log file or an audit log file | Manager |
| `hyperp-dbaas-postgresql.clusters.tasks.list` | List the tasks running or recently run on a cluster | Manager, Reader, Writer |
| `hyperp-dbaas-postgresql.clusters.tasks.read` | Get the detailed information about a task | Manager, Reader, Writer |
| `hyperp-dbaas-postgresql.clusters.configuration.update` | Update the database configuration of your cluster | Manager |
| `hyperp-dbaas-postgresql.clusters.configuration.read` | Show the database configuration of your cluster | Manager, Reader, Writer |
{: caption="Table 39. Service actions - Hyper Protect DBaaS for PostgreSQL" caption-side="top"}
{: #actions-table39}
{: tab-title="Actions"}
{: tab-group="hyperp-dbaas-postgresql"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Hyper Protect Virtual Server
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `hpvs` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 40. Platform roles - Hyper Protect Virtual Server" caption-side="top"}
{: #platform-roles-table40}
{: tab-title="Platform roles"}
{: tab-group="hpvs"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 40. Service roles - Hyper Protect Virtual Server" caption-side="top"}
{: #service-roles-table40}
{: tab-title="Service roles"}
{: tab-group="hpvs"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `hpvs.dashboard.view` | Can view the dashboard | Administrator, Editor, Manager, Operator, Reader, Writer |
{: caption="Table 40. Service actions - Hyper Protect Virtual Server" caption-side="top"}
{: #actions-table40}
{: tab-title="Actions"}
{: tab-group="hpvs"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IAM Access Groups Service
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `iam-groups` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can view, create, edit, and delete access groups including adding or removing users from the groups. You can also assign access to the group and manage access for others to work with access groups. |
| Editor | As an editor, you can view, create, edit, and delete access groups including adding or removing users from the groups. |
| Viewer | As a viewer, you can view access groups and its members. |
{: row-headers}
{: caption="Table 41. Platform roles - IAM Access Groups Service" caption-side="top"}
{: #platform-roles-table41}
{: tab-title="Platform roles"}
{: tab-group="iam-groups"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Service Configuration Reader | The ability to read services configuration for Governance management. |
{: row-headers}
{: caption="Table 41. Service roles - IAM Access Groups Service" caption-side="top"}
{: #service-roles-table41}
{: tab-title="Service roles"}
{: tab-group="iam-groups"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `iam-groups.groups.create` | Create an access group | Administrator, Editor |
| `iam-groups.groups.read` | Get an access group | Administrator, Editor, Viewer |
| `iam-groups.groups.update` | Update an access group | Administrator, Editor |
| `iam-groups.groups.delete` | Delete an access group | Administrator, Editor |
| `iam-groups.groups.list` | List access groups | Administrator, Editor, Viewer |
| `iam-groups.members.add` | Add members to an access group | Administrator, Editor |
| `iam-groups.members.read` | Check membership in an access group | Administrator, Editor, Viewer |
| `iam-groups.members.delete` | Delete member from an access group | Administrator, Editor |
| `iam-groups.members.list` | List access group members | Administrator, Editor, Viewer |
| `iam-groups.rules.create` | Create rule for an access group | Administrator, Editor |
| `iam-groups.rules.read` | Get an access group rule | Administrator, Editor, Viewer |
| `iam-groups.rules.update` | Update an access group rule | Administrator, Editor |
| `iam-groups.rules.delete` | Delete an access group rule | Administrator, Editor |
| `iam-groups.rules.list` | List access group rules | Administrator, Editor, Viewer |
| `iam-groups.groups.audit` | View access groups audit data | Administrator, Editor, Viewer |
| `iam-groups.account-settings.read` | View access groups account settings | Administrator, Editor, Viewer |
| `iam-groups.account-settings.update` | Update access groups account settings | Administrator |
{: caption="Table 41. Service actions - IAM Access Groups Service" caption-side="top"}
{: #actions-table41}
{: tab-title="Actions"}
{: tab-group="iam-groups"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IAM Identity Service
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `iam-identity` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | An Administrator can view, update and delete service IDs and API keys. |
| Editor | An Editor can view and update service IDs and API keys. |
| Operator | An Operator can view, update and delete service IDs and API keys. |
| Viewer | A Viewer can view service IDs and API keys. |
{: row-headers}
{: caption="Table 42. Platform roles - IAM Identity Service" caption-side="top"}
{: #platform-roles-table42}
{: tab-title="Platform roles"}
{: tab-group="iam-identity"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Service ID creator | Can create service IDs when the account setting to restrict service ID creation is enabled |
| User API key creator | Can create API keys when the account setting to restrict API key creation is enabled. |
{: row-headers}
{: caption="Table 42. Service roles - IAM Identity Service" caption-side="top"}
{: #service-roles-table42}
{: tab-title="Service roles"}
{: tab-group="iam-identity"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `iam-identity.user-apikey.create` | Ability to create IBM Cloud API keys associated with a user identity. | User API key creator |
| `iam-identity.serviceid.get` | Get the details of an existing service ID. | Administrator, Editor, Operator, Viewer |
| `iam-identity.serviceid.create` | Create a new service ID. | Service ID creator |
| `iam-identity.serviceid.update` | Update the details of an existing service ID. | Administrator, Editor, Operator |
| `iam-identity.serviceid.delete` | Delete a service ID. | Administrator, Operator |
| `iam-identity.apikey.manage` | actiondescription.iam-identity.apikey.manage | Administrator |
| `iam-identity.apikey.get` | Get the details of an existing API key. | Administrator, Editor, Operator |
| `iam-identity.apikey.list` | List API keys based on properties. | Administrator, Editor, Operator |
| `iam-identity.apikey.create` | Create a new API key. | Administrator, Operator |
| `iam-identity.apikey.update` | Update the details of an existing API key. | Administrator, Editor, Operator |
| `iam-identity.apikey.delete` | Delete an API key. | Administrator, Operator |
| `iam-identity.idp.get` | actiondescription.iam-identity.idp.get | Administrator, Editor, Operator |
| `iam-identity.idp.list` | actiondescription.iam-identity.idp.list | Administrator, Editor, Operator |
| `iam-identity.idp.create` | actiondescription.iam-identity.idp.create | Administrator, Operator |
| `iam-identity.idp.update` | actiondescription.iam-identity.idp.update | Administrator, Editor, Operator |
| `iam-identity.idp.delete` | actiondescription.iam-identity.idp.delete | Administrator, Operator |
| `iam-identity.idp.test` | actiondescription.iam-identity.idp.test | Administrator, Editor, Operator |
| `iam-identity.account.get` | actiondescription.iam-identity.account.get | Administrator, Editor, Operator, Viewer |
| `iam-identity.account.create` | actiondescription.iam-identity.account.create | Administrator, Operator |
| `iam-identity.account.update` | actiondescription.iam-identity.account.update | Administrator, Editor, Operator |
| `iam-identity.account.enable_idp` | actiondescription.iam-identity.account.enable_idp | Administrator, Editor, Operator |
| `iam-identity.account.disable_idp` | actiondescription.iam-identity.account.disable_idp | Administrator, Editor, Operator |
| `iam-identity.account.delete` | actiondescription.iam-identity.account.delete | Administrator, Operator |
{: caption="Table 42. Service actions - IAM Identity Service" caption-side="top"}
{: #actions-table42}
{: tab-title="Actions"}
{: tab-group="iam-identity"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IBM Cloud Activity Tracker with LogDNA
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `logdnaat` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
{: row-headers}
{: caption="Table 43. Platform roles - IBM Cloud Activity Tracker with LogDNA" caption-side="top"}
{: #platform-roles-table43}
{: tab-title="Platform roles"}
{: tab-group="logdnaat"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you can manage resources, configure views, dashboards and alerts, export data, search, filter, and view all data. |
| Reader | As a reader, you can perform read-only actions such as monitor data through views and dashboards. |
| Standard member | As a member, you can configure views, dashboards and alerts, export data, search, filter, and view all data. |
{: row-headers}
{: caption="Table 43. Service roles - IBM Cloud Activity Tracker with LogDNA" caption-side="top"}
{: #service-roles-table43}
{: tab-title="Service roles"}
{: tab-group="logdnaat"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `logdnaat.dashboard.view` | View LogDNA Dashboard | Administrator, Manager, Reader, Standard member |
| `logdnaat.dashboard.read` | Access LogDNA dashboard without any edit permission | Reader |
| `logdnaat.dashboard.member` | Access LogDNA dashboard with limited edit capabilities | Standard member |
| `logdnaat.dashboard.manage` | Access and manage LogDNA dashboard without any limitation | Administrator, Manager |
{: caption="Table 43. Service actions - IBM Cloud Activity Tracker with LogDNA" caption-side="top"}
{: #actions-table43}
{: tab-title="Actions"}
{: tab-group="logdnaat"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IBM Cloud Data Shield
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `data-shield` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 44. Platform roles - IBM Cloud Data Shield" caption-side="top"}
{: #platform-roles-table44}
{: tab-title="Platform roles"}
{: tab-group="data-shield"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `data-shield.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 44. Service actions - IBM Cloud Data Shield" caption-side="top"}
{: #actions-table44}
{: tab-title="Actions"}
{: tab-group="data-shield"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IBM Cloud Monitoring with Sysdig
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `sysdig-monitor` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
{: row-headers}
{: caption="Table 45. Platform roles - IBM Cloud Monitoring with Sysdig" caption-side="top"}
{: #platform-roles-table45}
{: tab-title="Platform roles"}
{: tab-group="sysdig-monitor"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 45. Service roles - IBM Cloud Monitoring with Sysdig" caption-side="top"}
{: #service-roles-table45}
{: tab-title="Service roles"}
{: tab-group="sysdig-monitor"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `sysdig-monitor.launch.user` |  | Administrator, Manager, Writer |
| `sysdig-monitor.launch.admin` |  | Administrator, Manager |
| `sysdig-monitor.launch.viewer` |  | Administrator, Manager, Reader, Writer |
{: caption="Table 45. Service actions - IBM Cloud Monitoring with Sysdig" caption-side="top"}
{: #actions-table45}
{: tab-title="Actions"}
{: tab-group="sysdig-monitor"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IBM Cloud Satellite
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `satellite` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 46. Platform roles - IBM Cloud Satellite" caption-side="top"}
{: #platform-roles-table46}
{: tab-title="Platform roles"}
{: tab-group="satellite"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Deployer | This role allow the user to deploy satellite-config managed contents to managed clusters |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 46. Service roles - IBM Cloud Satellite" caption-side="top"}
{: #service-roles-table46}
{: tab-title="Service roles"}
{: tab-group="satellite"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `satellite.dashboard.view` |  | Administrator, Editor, Operator |
| `satellite.config-configuration.create` | create configuration for the satellite config. You can create one or more configurations for your org. | Administrator, Manager |
| `satellite.config-configuration.read` | list all the configurations for your org, or get details about one configuration | Manager, Reader |
| `satellite.config-configuration.update` | updates fields in configuration | Manager, Writer |
| `satellite.config-configuration.delete` | delete a configuration | Administrator, Manager |
| `satellite.config-configuration.manageversion` | change your configuration version | Manager, Writer |
| `satellite.config-subscription.create` | create a subscription for a configuration | Deployer, Manager |
| `satellite.config-subscription.read` | read subscriptions for your org | Deployer, Manager, Reader |
| `satellite.config-subscription.update` | update subscription name and other relevant fields | Deployer, Manager |
| `satellite.config-subscription.delete` | delete a subscription | Deployer, Manager |
| `satellite.config-subscription.setversion` | set the configuration version on this subscription | Deployer, Manager |
| `satellite.config-cluster.attach` | attach cluster to a cluster group | Administrator, Manager |
| `satellite.config-cluster.read` | read cluster list for for an org or details about a given cluster | Administrator, Manager, Reader |
| `satellite.link.create` | Create Link instance for the Satellite Location.  | Administrator |
| `satellite.config-organization.read` | allow to access the organization info | Administrator, Deployer, Manager, Reader |
| `satellite.config-organization.manage` | allow to read the org_key for an organization | Manager |
| `satellite.resource.get` | read resource under a cluster or from a cluster group | Administrator, Manager, Reader |
| `satellite.api.globalaccess` | global access satellite api for special users | Administrator, Manager |
| `satellite.config-cluster.register` | register cluster to the satellite config | Administrator, Manager |
| `satellite.config-cluster.detach` | detach cluster | Administrator, Manager |
| `satellite.config-clustergroup.read` | read cluster group for all its resources | Administrator, Manager, Reader |
| `satellite.config-clustergroup.manage` | create or delete a cluster group | Administrator, Manager |
| `satellite.location.create` | create satellite location to be added to the existing locations | Administrator |
| `satellite.location.read` | read satellite location | Administrator, Editor, Operator, Viewer |
| `satellite.location.update` | edit an existing satellite location information | Administrator, Editor, Operator |
| `satellite.location.delete` | delete a satellite location belonged to you | Administrator, Operator |
| `satellite.config-clustergroup.setversion` | set the configuration version on this cluster group | Administrator, Deployer, Manager |
| `satellite.resource.servicelevelread` | Service level read of resources | Administrator, Manager |
| `satellite.link.get` | Get configuration and status of a Link instance. | Administrator, Editor, Operator, Viewer |
| `satellite.link.delete` | Delete a Link instance of a Satellite Location.  | Administrator, Operator |
| `satellite.link-endpoints.list` | List all Link Endpoints of a Satellite Location. | Administrator, Editor, Operator, Viewer |
| `satellite.link-endpoint.create` | Create a Link Endpoint with specified configuration. | Administrator, Editor, Operator |
| `satellite.link-endpoint.get` | Get configuration and status of a Link Endpoint. | Administrator, Editor, Operator, Viewer |
| `satellite.link-endpoint.update` | Modify configuration of a Link Endpoint. | Administrator, Editor, Operator |
| `satellite.link-endpoint.delete` | Delete a Link Endpoint. | Administrator, Editor, Operator |
| `satellite.link-endpoint-certs.get` | Get certificate/key of a Link Endpoint. | Administrator, Editor, Operator |
| `satellite.link-endpoint-certs.upload` | Upload certificate/key for a Link Endpoint. | Administrator, Editor, Operator |
| `satellite.link-endpoint-certs.delete` | Delete certificate/key of a Link Endpoint. | Administrator, Editor, Operator |
| `satellite.link-endpoint-certs.generate` | Generate self-signed certificate/key for a Link Endpoint. | Administrator, Editor, Operator |
| `satellite.link-sources.list` | List all ACL Sources of a Link instance. | Administrator, Editor, Manager, Operator, Reader, Viewer, Writer |
| `satellite.link-source.create` | Create a ACL Source for a Link instance. | Administrator, Editor, Manager, Operator, Writer |
| `satellite.link-source.delete` | Delete a ACL Source of a Link instance. | Administrator, Editor, Manager, Operator, Writer |
| `satellite.link-endpoint-sources.list` | List ACL Sources used by a Link Endpoint.  | Administrator, Editor, Operator, Viewer |
| `satellite.link-endpoint-sources.update` | Update ACL Sources enable/disable state of a Link Endpoint. | Administrator, Editor, Operator |
| `satellite.link-source.update` | Modify IP address/subnets list of a ACL Source configured for the specified Link instance. | Administrator, Editor, Manager, Operator, Writer |
| `satellite.config-cluster.update` | Update cluster registration | Manager |
{: caption="Table 46. Service actions - IBM Cloud Satellite" caption-side="top"}
{: #actions-table46}
{: tab-title="Actions"}
{: tab-group="satellite"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IBM Cloud Shell
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `cloudshell` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
{: row-headers}
{: caption="Table 47. Platform roles - IBM Cloud Shell" caption-side="top"}
{: #platform-roles-table47}
{: tab-title="Platform roles"}
{: tab-group="cloudshell"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `cloudshell.account-settings.update` | Update cloud shell account setting | Administrator |
{: caption="Table 47. Service actions - IBM Cloud Shell" caption-side="top"}
{: #actions-table47}
{: tab-title="Actions"}
{: tab-group="cloudshell"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IBM Cognos Dashboard Embedded
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `dynamic-dashboard-embedded` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Reader | Reader |
| Writer | Writer |
{: row-headers}
{: caption="Table 48. Service roles - IBM Cognos Dashboard Embedded" caption-side="top"}
{: #service-roles-table48}
{: tab-title="Service roles"}
{: tab-group="dynamic-dashboard-embedded"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `dynamic-dashboard-embedded.instances.write` |  | Manager, Reader, Writer |
{: caption="Table 48. Service actions - IBM Cognos Dashboard Embedded" caption-side="top"}
{: #actions-table48}
{: tab-title="Actions"}
{: tab-group="dynamic-dashboard-embedded"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## IBM Log Analysis with LogDNA
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `logdna` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
{: row-headers}
{: caption="Table 49. Platform roles - IBM Log Analysis with LogDNA" caption-side="top"}
{: #platform-roles-table49}
{: tab-title="Platform roles"}
{: tab-group="logdna"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you can manage resources, configure views, dashboards and alerts, export data, search, filter, and view all data. |
| Reader | As a reader, you can perform read-only actions such as monitor data through views and dashboards. |
| Standard Member | As a member, you can configure views, dashboards and alerts, export data, search, filter, and view all data. |
{: row-headers}
{: caption="Table 49. Service roles - IBM Log Analysis with LogDNA" caption-side="top"}
{: #service-roles-table49}
{: tab-title="Service roles"}
{: tab-group="logdna"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `logdna.dashboard.view` | View LogDNA Dashboard | Administrator, Manager, Reader, Standard Member |
| `logdna.dashboard.read` | Access LogDNA dashboard without any edit permission | Reader |
| `logdna.dashboard.member` | Access LogDNA dashboard with limited edit capabilities | Standard Member |
| `logdna.dashboard.manage` | Access and manage LogDNA dashboard without any limitation | Administrator, Manager |
{: caption="Table 49. Service actions - IBM Log Analysis with LogDNA" caption-side="top"}
{: #actions-table49}
{: tab-title="Actions"}
{: tab-group="logdna"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Image Service for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.image` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 50. Platform roles - Image Service for VPC" caption-side="top"}
{: #platform-roles-table50}
{: tab-title="Platform roles"}
{: tab-group="is.image"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.image.image.list` |  | Administrator, Editor, Operator, Viewer |
| `is.image.image.read` |  | Administrator, Editor, Operator, Viewer |
| `is.image.image.create` |  | Administrator, Editor |
| `is.image.image.update` |  | Administrator, Editor |
| `is.image.image.delete` |  | Administrator, Editor |
| `is.image.image.provision` |  | Administrator, Editor, Operator |
| `is.image.image.operate` | Operate on Custom Images | Administrator, Editor, Operator |
{: caption="Table 50. Service actions - Image Service for VPC" caption-side="top"}
{: #actions-table50}
{: tab-title="Actions"}
{: tab-group="is.image"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Internet of Things Platform
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `iotf-service` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 51. Platform roles - Internet of Things Platform" caption-side="top"}
{: #platform-roles-table51}
{: tab-title="Platform roles"}
{: tab-group="iotf-service"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `iotf-service.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 51. Service actions - Internet of Things Platform" caption-side="top"}
{: #actions-table51}
{: tab-title="Actions"}
{: tab-group="iotf-service"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Internet Services
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `internet-svcs` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Service Configuration Reader | The ability to read services configuration for Governance management. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 52. Service roles - Internet Services" caption-side="top"}
{: #service-roles-table52}
{: tab-title="Service roles"}
{: tab-group="internet-svcs"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `internet-svcs.zones.read` | View all zone settings but can't modify them. | Manager, Reader, Service Configuration Reader, Writer |
| `internet-svcs.zones.update` | Modify all zone settings but can't create or delete them. | Manager, Writer |
| `internet-svcs.zones.manage` | View, Modify, Create, and Delete all zone settings. | Manager |
| `internet-svcs.reliability.read` | View all Reliability settings but can't modify them. | Manager, Reader, Service Configuration Reader, Writer |
| `internet-svcs.reliability.update` | Modify all Reliability settings except for pools and monitors. | Manager, Writer |
| `internet-svcs.reliability.manage` | View, Modify, Create, and Delete all Reliability settings except for pools and monitors. | Manager |
| `internet-svcs.security.read` | View all Security settings except for instance level firewall rules. | Manager, Reader, Service Configuration Reader, Writer |
| `internet-svcs.security.update` | Modify all Security settings except for instance level firewall rules. | Manager, Writer |
| `internet-svcs.security.manage` | View, Modify, Create, and Delete all Security settings except for instance level firewall rules. | Manager |
| `internet-svcs.performance.read` | View all Performance settings but can't modify them. | Manager, Reader, Service Configuration Reader, Writer |
| `internet-svcs.performance.update` | Modify all Performance settings but cannot create or delete. | Manager, Writer |
| `internet-svcs.performance.manage` | View, Modify, Create, and Delete all Performance settings. | Manager |
{: caption="Table 52. Service actions - Internet Services" caption-side="top"}
{: #actions-table52}
{: tab-title="Actions"}
{: tab-group="internet-svcs"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Key Protect
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `kms` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| ReaderPlus | As a reader plus, you can perform read-only actions within Key Protect such as viewing service-specific resources. You can also access key material for standard keys. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 53. Service roles - Key Protect" caption-side="top"}
{: #service-roles-table53}
{: tab-title="Service roles"}
{: tab-group="kms"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `kms.secrets.create` | Create an encryption key. | Manager, Writer |
| `kms.secrets.read` | Retrieve an encryption key. | Manager, ReaderPlus, Writer |
| `kms.secrets.list` | Retrieve a list of encryption keys. | Manager, Reader, ReaderPlus, Writer |
| `kms.secrets.delete` | Delete an encryption key. | Manager |
| `kms.secrets.wrap` | Wrap an encryption key. | Manager, Reader, ReaderPlus, Writer |
| `kms.secrets.unwrap` | Unwrap an encryption key. | Manager, Reader, ReaderPlus, Writer |
| `kms.secrets.rotate` | Rotate an encryption key. | Manager, Writer |
| `kms.lockers.read` | Read lockers | Manager, Writer |
| `kms.lockers.create` | Create lockers | Manager, Writer |
| `kms.lockers.list` | List lockers | Manager, Writer |
| `kms.policies.read` | Retrieve policies for an encryption key. | Manager |
| `kms.policies.write` | Set policies for an encryption key. | Manager |
| `kms.secrets.rewrap` | Rewrap an encryption key. | Manager, Reader, ReaderPlus, Writer |
| `kms.importtoken.read` | Retrieve an import token. | Manager, Writer |
| `kms.importtoken.create` | Create an import token. | Manager, Writer |
| `kms.registrations.list` | Retrieve a list of registrations. | Manager, Reader, ReaderPlus, Writer |
| `kms.registrations.listforkey` | Retrieve a list of registrations for a given encryption key. | Manager, Reader, ReaderPlus, Writer |
| `kms.registrations.delete` | Delete a registration. | Manager, Reader, ReaderPlus, Writer |
| `kms.registrations.merge` | Update the details of an existing registration. | Manager, Reader, ReaderPlus, Writer |
| `kms.registrations.write` | Replace an existing registration. | Manager, Reader, ReaderPlus, Writer |
| `kms.registrations.create` | Create a registration between an encryption key and a cloud resource. | Manager, Reader, ReaderPlus, Writer |
| `kms.registrations.deactivate` | Move a suspended registration to the deactivated state | Manager, Reader, ReaderPlus, Writer |
| `kms.instancepolicies.read` | Retrieve instance level policies. | Manager |
| `kms.instancepolicies.write` | Add or update instance level policies. | Manager |
| `kms.secrets.setkeyfordeletion` | Set or prepare an encryption key for deletion. | Manager, Writer |
| `kms.secrets.unsetkeyfordeletion` | Unset an encryption key for deletion. | Manager, Writer |
| `kms.secrets.readmetadata` | Retrieve the details of an encryption key. | Manager, Reader, ReaderPlus, Writer |
| `kms.secrets.listkeyversions` | Retrieve a list of versions that are associated with an encryption key. | Manager, Reader, ReaderPlus, Writer |
| `kms.keyversions.list` | Retrieve a list of versions that are associated with an encryption key. | Manager, Reader, ReaderPlus, Writer |
| `kms.secrets.restore` | Restore a previously deleted encryption key. | Manager |
| `kms.secrets.disable` | Disable operations for an encryption key. | Manager |
| `kms.secrets.enable` | Enable operations for an encryption key. | Manager |
| `kms.secrets.eventack` | Acknowledge a key lifecycle event | Manager, Reader, ReaderPlus, Writer |
| `kms.instance.readipwhitelistport` | Retrieve port associated with instance level ip whitelist policy. | Manager |
| `kms.instance.readallowedipport` | Retrieve port associated with instance level allowed IP policy. | Manager |
| `kms.secrets.sync` | Initiate a manual data synchronization request to the associated resources of a key. | Manager, Writer |
{: caption="Table 53. Service actions - Key Protect" caption-side="top"}
{: #actions-table53}
{: tab-title="Actions"}
{: tab-group="kms"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Knowledge Studio
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `knowledge-studio` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 54. Platform roles - Knowledge Studio" caption-side="top"}
{: #platform-roles-table54}
{: tab-title="Platform roles"}
{: tab-group="knowledge-studio"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 54. Service roles - Knowledge Studio" caption-side="top"}
{: #service-roles-table54}
{: tab-title="Service roles"}
{: tab-group="knowledge-studio"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `knowledge-studio.dashboard.view` |  | Administrator, Editor, Manager, Reader, Viewer, Writer |
{: caption="Table 54. Service actions - Knowledge Studio" caption-side="top"}
{: #actions-table54}
{: tab-title="Actions"}
{: tab-group="knowledge-studio"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Kubernetes Service
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `containers-kubernetes` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 55. Platform roles - Kubernetes Service" caption-side="top"}
{: #platform-roles-table55}
{: tab-title="Platform roles"}
{: tab-group="containers-kubernetes"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 55. Service roles - Kubernetes Service" caption-side="top"}
{: #service-roles-table55}
{: tab-title="Service roles"}
{: tab-group="containers-kubernetes"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `containers-kubernetes.cluster.create` | Users such as cluster or account administrators can create and delete clusters or set up cluster-wide features like service endpoints or managed add-ons. | Administrator |
| `containers-kubernetes.cluster.read` | Users such as auditors or billing can see cluster details but not modify the infrastructure. | Administrator, Editor, Operator, Viewer |
| `containers-kubernetes.cluster.operate` | Users such as reliability or DevOps engineers can add worker nodes and troubleshoot infrastructure such as reloading a worker node. They cannot create, delete, change credentials, or set up cluster-wide features. | Administrator, Operator |
| `containers-kubernetes.cluster.update` | Users such as developers can bind service, work with Ingress resources, and set up log forwarding for their apps but cannot modify the infrastructure. | Administrator, Editor |
| `containers-kubernetes.kube.read` | Users get read access to most Kubernetes resources in the namespace, but not to certain resources like roles, role bindings, or secrets. Corresponds to the RBAC view cluster role, which can be scoped to a namespace. | Reader |
| `containers-kubernetes.kube.write` | Users get read and write access to most Kubernetes resources in the namespace, but not to certain resources like roles or role bindings. Corresponds to the RBAC edit cluster role, which can be scoped to a namespace. | Writer |
| `containers-kubernetes.kube.manage` | When scoped to one namespace: Users can read and write to all Kubernetes resources in the namespace, but not to objects that apply across namespaces, the namespace resource quota, or the namespace itself. Corresponds to the RBAC admin cluster role to that namespace. When scoped to all namespaces in the cluster (by leaving the previous namespace field empty): Users can read and write to all Kubernetes resources in all namespaces in the cluster and work with objects that apply across namespaces, like top pods, top nodes, or creating an Ingress resource to make apps publicly available. Corresponds to the RBAC cluster-admin cluster role. | Manager |
{: caption="Table 55. Service actions - Kubernetes Service" caption-side="top"}
{: #actions-table55}
{: tab-title="Actions"}
{: tab-group="containers-kubernetes"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Language Translator
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `language-translator` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 56. Service roles - Language Translator" caption-side="top"}
{: #service-roles-table56}
{: tab-title="Service roles"}
{: tab-group="language-translator"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `GET /language-translator` |  | Manager, Reader, Writer |
| `POST /language-translator` |  | Manager, Reader, Writer |
| `DELETE /language-translator` |  | Manager, Writer |
{: caption="Table 56. Service actions - Language Translator" caption-side="top"}
{: #actions-table56}
{: tab-title="Actions"}
{: tab-group="language-translator"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## License and Entitlement
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `entitlement` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
{: row-headers}
{: caption="Table 57. Platform roles - License and Entitlement" caption-side="top"}
{: #platform-roles-table57}
{: tab-title="Platform roles"}
{: tab-group="entitlement"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `entitlement.entitlement.write` |  | Administrator, Editor |
| `entitlement.entitlement.write-admin` |  | Administrator |
{: caption="Table 57. Service actions - License and Entitlement" caption-side="top"}
{: #actions-table57}
{: tab-title="Actions"}
{: tab-group="entitlement"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Load Balancer for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.load-balancer` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 58. Platform roles - Load Balancer for VPC" caption-side="top"}
{: #platform-roles-table58}
{: tab-title="Platform roles"}
{: tab-group="is.load-balancer"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.load-balancer.load-balancer.view` |  | Administrator, Editor, Viewer |
| `is.load-balancer.load-balancer.manage` |  | Administrator, Editor |
{: caption="Table 58. Service actions - Load Balancer for VPC" caption-side="top"}
{: #actions-table58}
{: tab-title="Actions"}
{: tab-group="is.load-balancer"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Machine Learning
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `pm-20` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
{: row-headers}
{: caption="Table 59. Platform roles - Machine Learning" caption-side="top"}
{: #platform-roles-table59}
{: tab-title="Platform roles"}
{: tab-group="pm-20"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Writer | As a writer, you can perform all actions on the WML instance this role is being assigned. |
{: row-headers}
{: caption="Table 59. Service roles - Machine Learning" caption-side="top"}
{: #service-roles-table59}
{: tab-title="Service roles"}
{: tab-group="pm-20"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `pm-20.instances.admin` |  | Administrator |
| `pm-20.instances.write` |  | Editor, Manager, Writer |
{: caption="Table 59. Service actions - Machine Learning" caption-side="top"}
{: #actions-table59}
{: tab-title="Actions"}
{: tab-group="pm-20"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Mass Data Migration
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `mass-data-migration` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 60. Platform roles - Mass Data Migration" caption-side="top"}
{: #platform-roles-table60}
{: tab-title="Platform roles"}
{: tab-group="mass-data-migration"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 60. Service roles - Mass Data Migration" caption-side="top"}
{: #service-roles-table60}
{: tab-title="Service roles"}
{: tab-group="mass-data-migration"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `mass-data-migration.dashboard.view` |  | Administrator, Editor, Operator |
| `mass-data-migration.order.place` | Can place order | Manager, Writer |
{: caption="Table 60. Service actions - Mass Data Migration" caption-side="top"}
{: #actions-table60}
{: tab-title="Actions"}
{: tab-group="mass-data-migration"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Mobile Foundation
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `mobile-foundation` for the service name.

No supported roles.
## Monitoring
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `monitoring` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
| Viewer | Viewer |
{: row-headers}
{: caption="Table 62. Platform roles - Monitoring" caption-side="top"}
{: #platform-roles-table62}
{: tab-title="Platform roles"}
{: tab-group="monitoring"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `monitoring.domain.write` |  | Administrator, Editor, Operator |
| `monitoring.domain.render` |  | Administrator, Editor, Operator, Viewer |
| `monitoring.domain.find` |  | Administrator, Editor, Operator, Viewer |
| `monitoring.domain.alarm_write` |  | Administrator, Editor |
| `monitoring.domain.alarm_read` |  | Administrator, Editor, Viewer |
| `monitoring.domain.notify_write` |  | Administrator, Editor |
| `monitoring.domain.notify_read` |  | Administrator, Editor, Viewer |
| `monitoring.domain.dashboard_write` |  | Administrator, Editor, Operator |
| `monitoring.domain.dashboard_read` |  | Administrator, Editor, Viewer |
| `monitoring.domain.uptime_write` |  | Administrator, Editor |
| `monitoring.domain.uptime_read` |  | Administrator, Editor, Viewer |
{: caption="Table 62. Service actions - Monitoring" caption-side="top"}
{: #actions-table62}
{: tab-title="Actions"}
{: tab-group="monitoring"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## MQ
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `mqcloud` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 63. Platform roles - MQ" caption-side="top"}
{: #platform-roles-table63}
{: tab-title="Platform roles"}
{: tab-group="mqcloud"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 63. Service roles - MQ" caption-side="top"}
{: #service-roles-table63}
{: tab-title="Service roles"}
{: tab-group="mqcloud"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `mqcloud.instance.use` | Accessing an MQ on Cloud service instance | Administrator, Editor, Manager, Viewer, Writer |
{: caption="Table 63. Service actions - MQ" caption-side="top"}
{: #actions-table63}
{: tab-title="Actions"}
{: tab-group="mqcloud"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Natural Language Classifier
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `natural-language-classifier` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Viewer | Viewer |
{: row-headers}
{: caption="Table 64. Platform roles - Natural Language Classifier" caption-side="top"}
{: #platform-roles-table64}
{: tab-title="Platform roles"}
{: tab-group="natural-language-classifier"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Reader | Reader |
| Writer | Writer |
{: row-headers}
{: caption="Table 64. Service roles - Natural Language Classifier" caption-side="top"}
{: #service-roles-table64}
{: tab-title="Service roles"}
{: tab-group="natural-language-classifier"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `GET /natural-language-classifier` |  | Administrator, Editor, Manager, Reader, Viewer, Writer |
| `POST /natural-language-classifier` |  | Administrator, Editor, Manager, Reader, Viewer, Writer |
| `DELETE /natural-language-classifier` |  | Administrator, Editor, Manager, Reader, Viewer, Writer |
{: caption="Table 64. Service actions - Natural Language Classifier" caption-side="top"}
{: #actions-table64}
{: tab-title="Actions"}
{: tab-group="natural-language-classifier"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Natural Language Understanding
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `natural-language-understanding` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
{: row-headers}
{: caption="Table 65. Platform roles - Natural Language Understanding" caption-side="top"}
{: #platform-roles-table65}
{: tab-title="Platform roles"}
{: tab-group="natural-language-understanding"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Reader | Reader |
| Writer | Writer |
{: row-headers}
{: caption="Table 65. Service roles - Natural Language Understanding" caption-side="top"}
{: #service-roles-table65}
{: tab-title="Service roles"}
{: tab-group="natural-language-understanding"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `natural-language-understanding.dashboard.view` |  | Administrator, Editor, Operator |
| `GET /natural-language-understanding` |  | Manager, Reader, Writer |
| `POST /natural-language-understanding` |  | Manager, Reader, Writer |
| `DELETE /natural-language-understanding` |  | Manager, Reader, Writer |
{: caption="Table 65. Service actions - Natural Language Understanding" caption-side="top"}
{: #actions-table65}
{: tab-title="Actions"}
{: tab-group="natural-language-understanding"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Network ACL
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.network-acl` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 66. Platform roles - Network ACL" caption-side="top"}
{: #platform-roles-table66}
{: tab-title="Platform roles"}
{: tab-group="is.network-acl"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.network-acl.network-acl.read` |  | Administrator, Editor, Operator, Viewer |
| `is.network-acl.network-acl.create` |  | Administrator, Editor |
| `is.network-acl.network-acl.update` |  | Administrator, Editor |
| `is.network-acl.network-acl.delete` |  | Administrator, Editor |
| `is.network-acl.network-acl.list` |  | Administrator, Editor, Operator, Viewer |
| `is.network-acl.network-acl.operate` |  | Administrator, Editor, Operator |
{: caption="Table 66. Service actions - Network ACL" caption-side="top"}
{: #actions-table66}
{: tab-title="Actions"}
{: tab-group="is.network-acl"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Personality Insights
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `personality-insights` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
{: row-headers}
{: caption="Table 67. Platform roles - Personality Insights" caption-side="top"}
{: #platform-roles-table67}
{: tab-title="Platform roles"}
{: tab-group="personality-insights"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Reader | Reader |
| Writer | Writer |
{: row-headers}
{: caption="Table 67. Service roles - Personality Insights" caption-side="top"}
{: #service-roles-table67}
{: tab-title="Service roles"}
{: tab-group="personality-insights"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `personality-insights.dashboard.view` |  | Administrator, Editor, Operator |
| `GET /personality-insights` |  | Manager, Reader, Writer |
| `POST /personality-insights` |  | Manager, Reader, Writer |
{: caption="Table 67. Service actions - Personality Insights" caption-side="top"}
{: #actions-table67}
{: tab-title="Actions"}
{: tab-group="personality-insights"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Portworx Enterprise
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `portworx` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 68. Platform roles - Portworx Enterprise" caption-side="top"}
{: #platform-roles-table68}
{: tab-title="Platform roles"}
{: tab-group="portworx"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `portworx.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 68. Service actions - Portworx Enterprise" caption-side="top"}
{: #actions-table68}
{: tab-title="Actions"}
{: tab-group="portworx"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Power Systems Virtual Server
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `power-iaas` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
{: row-headers}
{: caption="Table 69. Service roles - Power Systems Virtual Server" caption-side="top"}
{: #service-roles-table69}
{: tab-title="Service roles"}
{: tab-group="power-iaas"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `power-iaas.dashboard.view` |  | Manager, Reader |
| `power-iaas.cloud-instance.modify` |  | Manager |
| `power-iaas.cloud-instance.read` |  | Manager, Reader |
{: caption="Table 69. Service actions - Power Systems Virtual Server" caption-side="top"}
{: #actions-table69}
{: tab-title="Actions"}
{: tab-group="power-iaas"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## PowerAI
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `power-ai` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
{: row-headers}
{: caption="Table 70. Platform roles - PowerAI" caption-side="top"}
{: #platform-roles-table70}
{: tab-title="Platform roles"}
{: tab-group="power-ai"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `power-ai.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 70. Service actions - PowerAI" caption-side="top"}
{: #actions-table70}
{: tab-title="Actions"}
{: tab-group="power-ai"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Public Gateway for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.public-gateway` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 71. Platform roles - Public Gateway for VPC" caption-side="top"}
{: #platform-roles-table71}
{: tab-title="Platform roles"}
{: tab-group="is.public-gateway"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.public-gateway.public-gateway.read` |  | Administrator, Editor, Operator, Viewer |
| `is.public-gateway.public-gateway.create` |  | Administrator, Editor |
| `is.public-gateway.public-gateway.update` |  | Administrator, Editor |
| `is.public-gateway.public-gateway.delete` |  | Administrator, Editor |
| `is.public-gateway.public-gateway.list` |  | Administrator, Editor, Operator, Viewer |
| `is.public-gateway.public-gateway.operate` |  | Administrator, Editor, Operator |
{: caption="Table 71. Service actions - Public Gateway for VPC" caption-side="top"}
{: #actions-table71}
{: tab-title="Actions"}
{: tab-group="is.public-gateway"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Push Notifications
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `imfpush` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
{: row-headers}
{: caption="Table 72. Platform roles - Push Notifications" caption-side="top"}
{: #platform-roles-table72}
{: tab-title="Platform roles"}
{: tab-group="imfpush"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 72. Service roles - Push Notifications" caption-side="top"}
{: #service-roles-table72}
{: tab-title="Service roles"}
{: tab-group="imfpush"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `imfpush.dashboard.view` |  | Administrator, Editor |
| `imfpush.application.list` |  | Manager, Reader, Writer |
| `imfpush.application.delete` |  | Manager |
| `imfpush.device.list` |  | Manager, Reader, Writer |
| `imfpush.application.update` |  | Manager |
| `imfpush.device.create` |  | Manager, Writer |
| `imfpush.device.update` |  | Manager, Writer |
| `imfpush.device.delete` |  | Manager |
| `imfpush.messages.send` |  | Manager, Writer |
| `imfpush.messages.send` |  | Manager, Writer |
| `imfpush.messages.delete` |  | Manager |
| `imfpush.messages.list` |  | Manager, Reader, Writer |
| `imfpush.subscriptions.create` |  | Manager, Writer |
| `imfpush.subscriptions.delete` |  | Manager |
| `imfpush.subscriptions.list` |  | Manager, Reader, Writer |
| `imfpush.tags.create` |  | Manager, Writer |
| `imfpush.tags.update` |  | Manager, Writer |
| `imfpush.tags.delete` |  | Manager |
| `imfpush.tags.list` |  | Manager, Reader, Writer |
| `imfpush.webhooks.create` |  | Manager, Writer |
| `imfpush.webhooks.update` |  | Manager, Writer |
| `imfpush.webhooks.delete` |  | Manager |
| `imfpush.webhooks.list` |  | Manager, Reader, Writer |
| `imfpush.status.update` |  | Manager, Writer |
| `imfpush.channels.create` | Channel creation | Manager, Writer |
| `imfpush.channels.update` | Channel update | Manager, Writer |
| `imfpush.channels.delete` | Channel delete | Manager |
| `imfpush.channels.list` | Channels list | Manager, Reader, Writer |
| `imfpush.channelgroups.create` | Channelgroup create | Manager, Writer |
| `imfpush.channelgroups.update` | Channelgroup update | Manager, Writer |
| `imfpush.channelgroups.delete` | Channelgroup delete | Manager |
| `imfpush.channelgroups.list` | Channelgroup list | Manager, Reader, Writer |
{: caption="Table 72. Service actions - Push Notifications" caption-side="top"}
{: #actions-table72}
{: tab-title="Actions"}
{: tab-group="imfpush"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Raxak Protect
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `raxak-protect` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 73. Platform roles - Raxak Protect" caption-side="top"}
{: #platform-roles-table73}
{: tab-title="Platform roles"}
{: tab-group="raxak-protect"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `raxak-protect.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 73. Service actions - Raxak Protect" caption-side="top"}
{: #actions-table73}
{: tab-title="Actions"}
{: tab-group="raxak-protect"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Role management
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `iam-access-management` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrators can create, edit, update, and delete custom roles. |
| Editor | Editors can edit and update custom roles. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 74. Platform roles - Role management" caption-side="top"}
{: #platform-roles-table74}
{: tab-title="Platform roles"}
{: tab-group="iam-access-management"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `iam-access-management.customRole.create` | The ability to create custom roles. | Administrator |
| `iam-access-management.customRole.update` | The ability to edit and update custom roles. | Administrator, Editor |
| `iam-access-management.customRole.delete` | The ability to delete a custom role. | Administrator |
{: caption="Table 74. Service actions - Role management" caption-side="top"}
{: #actions-table74}
{: tab-title="Actions"}
{: tab-group="iam-access-management"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Schematics
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `schematics` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 75. Platform roles - Schematics" caption-side="top"}
{: #platform-roles-table75}
{: tab-title="Platform roles"}
{: tab-group="schematics"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Service Configuration Reader | The ability to read services configuration for Governance management. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 75. Service roles - Schematics" caption-side="top"}
{: #service-roles-table75}
{: tab-title="Service roles"}
{: tab-group="schematics"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `schematics.workspace.create` |  | Manager |
| `schematics.workspace.update` |  | Manager, Writer |
| `schematics.workspace.delete` |  | Manager |
| `schematics.workspace.read` | Read workspace details | Manager, Reader, Writer |
| `schematics.presets.create` | Create new presets for the Account | Manager |
| `schematics.presets.update` | Update the preset values | Manager, Writer |
| `schematics.presets.delete` | Delete the preset from Account | Manager |
| `schematics.presets.read` | Read the preset variable, value and metadata | Manager, Reader, Writer |
| `schematics.action.create` | Create an Action definition | Manager |
| `schematics.action.update` | Update the Action definition | Manager, Writer |
| `schematics.action.read` | Read the Action definition | Manager, Reader, Writer |
| `schematics.action.delete` | Delete the Action definition | Manager |
| `schematics.settings-kms.discover` | Discover KMS instances for Schematics settings | Administrator |
| `schematics.settings-kms.read` | Read the Schematics KMS settings | Administrator, Editor, Manager, Operator, Reader, Service Configuration Reader, Viewer, Writer |
| `schematics.settings-kms.update` | Update the Schematics KMS settings | Administrator |
{: caption="Table 75. Service actions - Schematics" caption-side="top"}
{: #actions-table75}
{: tab-title="Actions"}
{: tab-group="schematics"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Secrets Manager
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `secrets-manager` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 76. Platform roles - Secrets Manager" caption-side="top"}
{: #platform-roles-table76}
{: tab-title="Platform roles"}
{: tab-group="secrets-manager"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 76. Service roles - Secrets Manager" caption-side="top"}
{: #service-roles-table76}
{: tab-title="Service roles"}
{: tab-group="secrets-manager"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `secrets-manager.dashboard.view` | View the Secrets Manager dashboard. | Administrator, Editor, Operator |
| `secrets-manager.secret-group.create` | Create secret groups to organize your secrets for access control. | Manager |
| `secrets-manager.secret-group.update` | Update a secret group. | Manager |
| `secrets-manager.secret-group.delete` | Delete a secret group. | Manager |
| `secrets-manager.secret-group.read` | View the details of a secret group. | Manager, Reader, Writer |
| `secrets-manager.secret-groups.list` | List the secret groups in your instance. | Manager, Reader, Writer |
| `secrets-manager.secret.create` | Create a secret. | Manager, Writer |
| `secrets-manager.secret.import` | Import a secret. | Manager, Writer |
| `secrets-manager.secret.read` | View the details of a secret. | Manager, Writer |
| `secrets-manager.secret.delete` | Delete a secret. | Manager |
| `secrets-manager.secrets.list` | List the secrets in your instance. | Manager, Reader, Writer |
| `secrets-manager.secret.rotate` | Rotate a secret. | Manager, Writer |
| `secrets-manager.secret-metadata.update` | Update a secret. | Manager, Writer |
| `secrets-manager.secret-metadata.read` | View the metadata of a secret. | Manager, Reader, Writer |
| `secrets-manager.secret-policies.set` | Set secret policies. | Manager |
| `secrets-manager.secret-policies.get` | Get secret policies. | Manager |
| `secrets-manager.secret-engine-config.set` | Set secret engine configuration. | Manager |
| `secrets-manager.secret-engine-config.get` | Get secret engine configuration. | Manager |
| `secrets-manager.endpoints.view` | Get service instance endpoints. | Manager, Reader, Writer |
{: caption="Table 76. Service actions - Secrets Manager" caption-side="top"}
{: #actions-table76}
{: tab-title="Actions"}
{: tab-group="secrets-manager"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Security Advisor
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `security-advisor` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 77. Platform roles - Security Advisor" caption-side="top"}
{: #platform-roles-table77}
{: tab-title="Platform roles"}
{: tab-group="security-advisor"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 77. Service roles - Security Advisor" caption-side="top"}
{: #service-roles-table77}
{: tab-title="Service roles"}
{: tab-group="security-advisor"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `security-advisor.dashboard.view` |  | Administrator, Editor, Operator |
| `security-advisor.findings.read` |  | Manager, Reader, Writer |
| `security-advisor.findings.write` |  | Manager, Writer |
| `security-advisor.findings.delete` |  | Manager |
| `security-advisor.findings.update` |  | Manager, Writer |
| `security-advisor.metadata.read` |  | Manager, Reader, Writer |
| `security-advisor.metadata.delete` |  | Manager |
| `security-advisor.metadata.write` |  | Manager |
| `security-advisor.metadata.update` |  | Manager |
| `security-advisor.data.post` |  | Manager, Writer |
| `security-advisor.data.get` |  | Manager, Reader, Writer |
| `security-advisor.analytics.post` |  | Manager, Writer |
| `security-advisor.custom-solution.read` |  | Manager, Reader, Writer |
| `security-advisor.custom-solution.write` |  | Manager |
| `security-advisor.custom-solution.update` |  | Manager |
| `security-advisor.custom-solution.delete` |  | Manager |
| `security-advisor.partner-solution.read` |  | Manager, Reader, Writer |
| `security-advisor.partner-solution.write` |  | Manager |
| `security-advisor.partner-solution.update` |  | Manager |
| `security-advisor.partner-solution.delete` |  | Manager |
| `security-advisor.network-insights.enable` |  | Manager |
| `security-advisor.network-insights.disable` |  | Manager |
| `security-advisor.activity-insights.enable` |  | Manager |
| `security-advisor.activity-insights.disable` |  | Manager |
| `security-advisor.insights-cos.create` |  | Manager |
| `security-advisor.notification-channels.read` |  | Manager, Reader, Writer |
| `security-advisor.notification-channels.create` |  | Manager |
| `security-advisor.notification-channels.delete` |  | Manager |
| `security-advisor.notification-channels.update` |  | Manager |
| `security-advisor.accounts.list` |  | Reader |
| `security-advisor.config-insights.scan` | Invoke Config Advisor Scan | Manager |
| `security-advisor.insights.read` | Fetch  the list of supported insights | Manager, Reader, Writer |
| `security-advisor.network-insights-cos.create` | Add cos bucket details for insights | Manager |
| `security-advisor.activity-insights-cos.create` | Add cos bucket details for activity insights | Manager |
| `security-advisor.network-insights-cos.delete` | Delete cos bucket details for network insights | Manager |
| `security-advisor.activity-insights-cos.delete` | Delete cos bucket details for activity insights | Manager |
{: caption="Table 77. Service actions - Security Advisor" caption-side="top"}
{: #actions-table77}
{: tab-title="Actions"}
{: tab-group="security-advisor"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Security and Compliance Center
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `compliance` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 78. Platform roles - Security and Compliance Center" caption-side="top"}
{: #platform-roles-table78}
{: tab-title="Platform roles"}
{: tab-group="compliance"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| ResultsSubmitter | As a results submitter, you can post compliance and security assessment results. |
| ServiceEditor | Edit configuration governance services |
| ServiceProvider | As a service provider, you can access compliance and security  |
{: row-headers}
{: caption="Table 78. Service roles - Security and Compliance Center" caption-side="top"}
{: #service-roles-table78}
{: tab-title="Service roles"}
{: tab-group="compliance"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `compliance.dashboard.view` |  | Administrator, Editor, Operator |
| `compliance.controls.create` | Use this role to create  compliance catalog | Administrator, Editor |
| `compliance.controls.read` | Use this role to view compliance catalog | Administrator, Editor, Operator, Viewer |
| `compliance.controls.update` | Use this role to edit  compliance catalog | Administrator, Editor |
| `compliance.controls.delete` | Delete Cloud compliance control | Administrator, Editor |
| `compliance.profiles.create` | Use this role to create  compliance profile | Administrator, Editor |
| `compliance.profiles.read` | Use this role to view compliance profile | Administrator, Editor, Viewer |
| `compliance.profiles.update` | Use this role to edit  compliance profile | Administrator, Editor |
| `compliance.profiles.delete` | Use this role to delete  compliance profile | Administrator, Editor |
| `compliance.targets.create` | Use this role to create  compliance resource definition | Administrator, Editor |
| `compliance.targets.read` | Use this role to view compliance resource definition | Administrator, Editor, Operator, Viewer |
| `compliance.targets.update` | Use this role to edit  compliance resource definition | Administrator, Editor |
| `compliance.targets.delete` | Use this role to delete  compliance resource definition | Administrator, Editor |
| `compliance.results.read` | Use this role to view compliance and security assessment results | Administrator, Editor, Operator, Viewer |
| `compliance.results.delete` | Use this role to delete compliance and security assessment results | Administrator, Editor |
| `compliance.results.create` | Use this role to create compliance and security assessment results | Administrator, ResultsSubmitter |
| `compliance.config-state.create` | Publish config state | ServiceProvider |
| `compliance.configuration-governance.attachments-create` | Create configuration governance attachments | Administrator, Editor |
| `compliance.configuration-governance.attachments-delete` | Delete configuration governance attachments | Administrator, Editor |
| `compliance.configuration-governance.attachments-read` | Read configuration governance attachments | Administrator, Editor, Operator, Viewer |
| `compliance.configuration-governance.attachments-update` | Update configuration governance attachments | Administrator, Editor |
| `compliance.configuration-governance.config-ready` | configuration governance config ready | ServiceProvider |
| `compliance.configuration-governance.config-state-create` | Create configuration governance config state | Administrator, Editor, ServiceProvider |
| `compliance.configuration-governance.config-state-delete` | Delete configuration governance config state | Administrator, Editor |
| `compliance.configuration-governance.config-state-read` | Read configuration governance config state | Administrator, Editor, Operator, Viewer |
| `compliance.configuration-governance.config-state-update` | Update configuration governance config state | Administrator, Editor |
| `compliance.configuration-governance.results-create` | Create configuration governance results | Administrator, Editor |
| `compliance.configuration-governance.results-delete` | Delete configuration governance results | Administrator, Editor |
| `compliance.configuration-governance.results-read` | Read configuration governance results | Administrator, Editor, Operator, Viewer |
| `compliance.configuration-governance.results-update` | Update configuration governance results | Administrator, Editor |
| `compliance.configuration-governance.rules-create` | Create configuration governance rules | Administrator, Editor |
| `compliance.configuration-governance.rules-delete` | Delete configuration governance rules | Administrator, Editor |
| `compliance.configuration-governance.rules-eval` | Evaluate configuration governance rules | ServiceProvider |
| `compliance.configuration-governance.rules-read` | Read configuration governance rules | Administrator, Editor, Operator, Viewer |
| `compliance.configuration-governance.rules-update` | Update configuration governance rules | Administrator, Editor |
| `compliance.configuration-governance.services-create` | Create configuration governance services | Administrator, Editor, ServiceEditor |
| `compliance.configuration-governance.services-delete` | Delete configuration governance services | Administrator, Editor, ServiceEditor |
| `compliance.configuration-governance.services-update` | Update configuration governance services | Administrator, Editor, ServiceEditor |
| `compliance.posture-management.collectors-create` | Use this role create compliance collector | Administrator, Editor |
| `compliance.posture-management.collectors-delete` | Use this role to delete compliance collector | Administrator, Editor |
| `compliance.posture-management.collectors-read` | Use this role to read compliance collector | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.collectors-update` | Use this role to update compliance collector | Administrator, Editor |
| `compliance.posture-management.controls-create` | Use this role to create  compliance catalog | Administrator, Editor |
| `compliance.posture-management.controls-delete` | Delete Cloud compliance control | Administrator, Editor |
| `compliance.posture-management.controls-read` | Use this role to view compliance catalog | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.controls-update` | Use this role to edit  compliance catalog | Administrator, Editor |
| `compliance.posture-management.credentials-create` | Use this role to Create compliance credential | Administrator, Editor |
| `compliance.posture-management.credentials-delete` | Use this role to delete compliance credential | Administrator, Editor |
| `compliance.posture-management.credentials-read` | Use this role to read compliance credential | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.credentials-update` | Use this role to update compliance credential | Administrator, Editor |
| `compliance.posture-management.credentialsmap-create` | Use this role to create compliance credentialmap | Administrator, Editor |
| `compliance.posture-management.credentialsmap-delete` | Use this role to delete compliance credentialmap | Administrator, Editor |
| `compliance.posture-management.credentialsmap-read` | Use this role to read compliance credentialmap | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.credentialsmap-update` | Use this role to update compliance credentialmap | Administrator, Editor |
| `compliance.posture-management.dashboard-view` | Use this role to view Compliance Dashboard | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.events-create` | This role is used to create event logs | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.events-view` | Use this role to view event log | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.profiles-create` | Use this role to create compliance template | Administrator, Editor |
| `compliance.posture-management.profiles-delete` | Use this role to delete compliance template  | Administrator, Editor |
| `compliance.posture-management.profiles-read` | Use this role to read compliance.template | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.profiles-update` | Use this roe to update compliance template | Administrator, Editor |
| `compliance.posture-management.scopes-create` | Use this role to create compliance schema | Administrator, Editor |
| `compliance.posture-management.scopes-delete` | Use this role to delete compliance scope | Administrator, Editor |
| `compliance.posture-management.scopes-read` | Use this role to read compliance schema | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.scopes-update` | Use this role to edit the compliance scope | Administrator, Editor |
| `compliance.posture-management.tags-create` | Use this for tags | Administrator, Editor, Operator |
| `compliance.posture-management.tags-delete` | Delete tag | Administrator, Editor, Operator |
| `compliance.posture-management.tags-read` | Read tags | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.tags-update` | Update tags | Administrator, Editor, Operator |
| `compliance.posture-management.tenants-create` | Use this role to create compliance tenant | Administrator, Editor |
| `compliance.posture-management.tenants-delete` | Use this role to delete compliance tenant | Administrator, Editor |
| `compliance.posture-management.tenants-read` | Use this role to read compliance tenant | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.tenants-update` | Use this role to update compliance tenant | Administrator, Editor |
| `compliance.posture-management.validations-create` | Use this role to create compliance validation | Administrator, Editor |
| `compliance.posture-management.validations-delete` | Use this roles to delete compliance validation  | Administrator, Editor |
| `compliance.posture-management.validations-read` | Use this role to read compliance validation | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.validations-update` | Use this role to update compliance validation | Administrator, Editor |
| `compliance.posture-management.values-create` | Use this role to create compliance policy | Administrator, Editor |
| `compliance.posture-management.values-read` | Use this role to read compliance policy | Administrator, Editor, Operator, Viewer |
| `compliance.posture-management.values-update` | Use this role to update compliance policy | Administrator, Editor |
{: caption="Table 78. Service actions - Security and Compliance Center" caption-side="top"}
{: #actions-table78}
{: tab-title="Actions"}
{: tab-group="compliance"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Security Group for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.security-group` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 79. Platform roles - Security Group for VPC" caption-side="top"}
{: #platform-roles-table79}
{: tab-title="Platform roles"}
{: tab-group="is.security-group"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.security-group.security-group.create` |  | Administrator, Editor |
| `is.security-group.security-group.read` |  | Administrator, Editor, Operator, Viewer |
| `is.security-group.security-group.update` |  | Administrator, Editor |
| `is.security-group.security-group.delete` |  | Administrator, Editor |
| `is.security-group.security-group.operate` |  | Administrator, Editor, Operator |
{: caption="Table 79. Service actions - Security Group for VPC" caption-side="top"}
{: #actions-table79}
{: tab-title="Actions"}
{: tab-group="is.security-group"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Skytap On IBM Cloud
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `skytap` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 80. Platform roles - Skytap On IBM Cloud" caption-side="top"}
{: #platform-roles-table80}
{: tab-title="Platform roles"}
{: tab-group="skytap"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `skytap.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 80. Service actions - Skytap On IBM Cloud" caption-side="top"}
{: #actions-table80}
{: tab-title="Actions"}
{: tab-group="skytap"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Speech to Text
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `speech-to-text` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 81. Platform roles - Speech to Text" caption-side="top"}
{: #platform-roles-table81}
{: tab-title="Platform roles"}
{: tab-group="speech-to-text"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 81. Service roles - Speech to Text" caption-side="top"}
{: #service-roles-table81}
{: tab-title="Service roles"}
{: tab-group="speech-to-text"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `speech-to-text.dashboard.view` |  | Administrator, Editor, Operator |
| `GET /speech-to-text` |  | Manager, Reader, Writer |
| `POST /speech-to-text` |  | Manager, Writer |
| `DELETE /speech-to-text` |  | Manager, Writer |
| `HEAD /speech-to-text` |  | Manager, Reader, Writer |
| `PUT /speech-to-text` |  | Manager, Writer |
{: caption="Table 81. Service actions - Speech to Text" caption-side="top"}
{: #actions-table81}
{: tab-title="Actions"}
{: tab-group="speech-to-text"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## SQL Query
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `sql-query` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 82. Service roles - SQL Query" caption-side="top"}
{: #service-roles-table82}
{: tab-title="Service roles"}
{: tab-group="sql-query"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `sql-query.api.submit` | Submit SQL jobs that read and write data, including catalog metadata , such as table definitions. | Manager, Writer |
| `sql-query.api.getalljobs` | Retrieve a list of recent job submissions and their outcome status. | Manager, Reader, Writer |
| `sql-query.api.getjobinfo` | Retrieve the detailed status of a job based on provided jobid. | Manager, Reader, Writer |
| `sql-query.api.managecatalog` | Manage the catalog and indexes. For example, submit DDL statements to create, alter and drop tables, views and indexes. | Manager |
| `sql-query.api.readcatalog` | Introspect the catalog. For example, list the definitions of tables, views and indexes. | Manager, Reader, Writer |
{: caption="Table 82. Service actions - SQL Query" caption-side="top"}
{: #actions-table82}
{: tab-title="Actions"}
{: tab-group="sql-query"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## SSH Key for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.key` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 83. Platform roles - SSH Key for VPC" caption-side="top"}
{: #platform-roles-table83}
{: tab-title="Platform roles"}
{: tab-group="is.key"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.key.key.list` |  | Administrator, Editor, Operator, Viewer |
| `is.key.key.create` |  | Administrator, Editor |
| `is.key.key.delete` |  | Administrator, Editor |
| `is.key.key.read` |  | Administrator, Editor, Operator, Viewer |
| `is.key.key.update` |  | Administrator, Editor |
| `is.key.artifactattachment.create` |  | Administrator, Editor |
| `is.key.artifactattachment.update` |  | Administrator, Editor |
| `is.key.artifactattachment.delete` |  | Administrator, Editor |
| `is.key.userdata.list` |  | Administrator, Editor, Operator |
| `is.key.userdata.create` |  | Administrator, Editor |
| `is.key.userdata.delete` |  | Administrator, Editor |
| `is.key.userdata.read` |  | Administrator, Editor, Operator, Viewer |
| `is.key.artifactattachment.read` |  | Administrator, Editor, Operator, Viewer |
| `is.key.key.operate` | Operate on Key | Administrator, Editor, Operator |
{: caption="Table 83. Service actions - SSH Key for VPC" caption-side="top"}
{: #actions-table83}
{: tab-title="Actions"}
{: tab-group="is.key"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Streaming Analytics
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `streaming-analytics` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Writer | Writer |
{: row-headers}
{: caption="Table 84. Service roles - Streaming Analytics" caption-side="top"}
{: #service-roles-table84}
{: tab-title="Service roles"}
{: tab-group="streaming-analytics"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `streaming-analytics.instances.query` |  | Manager |
| `streaming-analytics.instances.read` |  | Manager, Writer |
| `streaming-analytics.instances.update` |  | Manager |
| `streaming-analytics.instances.start` |  | Manager, Writer |
| `streaming-analytics.jobs.query` |  | Manager, Writer |
| `streaming-analytics.jobs.create` |  | Manager, Writer |
| `streaming-analytics.jobs.read` |  | Manager, Writer |
| `streaming-analytics.jobs.delete` |  | Manager, Writer |
| `streaming-analytics.builds.query` |  | Manager, Writer |
| `streaming-analytics.builds.create` |  | Manager, Writer |
| `streaming-analytics.builds.read` |  | Manager, Writer |
| `streaming-analytics.builds.delete` |  | Manager, Writer |
| `streaming-analytics.artifacts.query` |  | Manager, Writer |
| `streaming-analytics.artifacts.read` |  | Manager, Writer |
| `streaming-analytics.artifacts.download` |  | Manager, Writer |
{: caption="Table 84. Service actions - Streaming Analytics" caption-side="top"}
{: #actions-table84}
{: tab-title="Actions"}
{: tab-group="streaming-analytics"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Subnet
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.subnet` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 85. Platform roles - Subnet" caption-side="top"}
{: #platform-roles-table85}
{: tab-title="Platform roles"}
{: tab-group="is.subnet"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.subnet.subnet.create` |  | Administrator, Editor |
| `is.subnet.subnet.read` |  | Administrator, Editor, Operator, Viewer |
| `is.subnet.subnet.update` |  | Administrator, Editor |
| `is.subnet.subnet.delete` |  | Administrator, Editor |
| `is.subnet.subnet.list` |  | Administrator, Editor, Operator, Viewer |
| `is.subnet.subnet.operate` |  | Administrator, Editor, Operator |
{: caption="Table 85. Service actions - Subnet" caption-side="top"}
{: #actions-table85}
{: tab-title="Actions"}
{: tab-group="is.subnet"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Support Center
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `support` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | View, search, create, and update support cases |
| Editor | View, search, create, and update support cases |
| Viewer | View and search support cases |
{: row-headers}
{: caption="Table 86. Platform roles - Support Center" caption-side="top"}
{: #platform-roles-table86}
{: tab-title="Platform roles"}
{: tab-group="support"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `support.case.create` |  | Administrator, Editor |
| `support.case.update` |  | Administrator, Editor |
| `support.case.read` |  | Administrator, Editor, Viewer |
| `support.case.list` |  | Administrator, Editor, Viewer |
{: caption="Table 86. Service actions - Support Center" caption-side="top"}
{: #actions-table86}
{: tab-title="Actions"}
{: tab-group="support"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Text to Speech
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `text-to-speech` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
{: row-headers}
{: caption="Table 87. Platform roles - Text to Speech" caption-side="top"}
{: #platform-roles-table87}
{: tab-title="Platform roles"}
{: tab-group="text-to-speech"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Reader | Reader |
| Writer | Writer |
{: row-headers}
{: caption="Table 87. Service roles - Text to Speech" caption-side="top"}
{: #service-roles-table87}
{: tab-title="Service roles"}
{: tab-group="text-to-speech"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `text-to-speech.dashboard.view` |  | Administrator, Editor, Operator |
| `GET /text-to-speech` |  | Manager, Reader, Writer |
| `POST /text-to-speech` |  | Manager, Writer |
| `DELETE /text-to-speech` |  | Manager, Writer |
| `HEAD /text-to-speech` |  | Manager, Reader, Writer |
| `PUT /text-to-speech` |  | Manager, Writer |
{: caption="Table 87. Service actions - Text to Speech" caption-side="top"}
{: #actions-table87}
{: tab-title="Actions"}
{: tab-group="text-to-speech"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Tone Analyzer
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `tone-analyzer` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
| Editor | Editor |
| Operator | Operator |
{: row-headers}
{: caption="Table 88. Platform roles - Tone Analyzer" caption-side="top"}
{: #platform-roles-table88}
{: tab-title="Platform roles"}
{: tab-group="tone-analyzer"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Reader | Reader |
| Writer | Writer |
{: row-headers}
{: caption="Table 88. Service roles - Tone Analyzer" caption-side="top"}
{: #service-roles-table88}
{: tab-title="Service roles"}
{: tab-group="tone-analyzer"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `tone-analyzer.dashboard.view` |  | Administrator, Editor, Operator |
| `GET /tone-analyzer` |  | Manager, Reader, Writer |
| `POST /tone-analyzer` |  | Manager, Reader, Writer |
{: caption="Table 88. Service actions - Tone Analyzer" caption-side="top"}
{: #actions-table88}
{: tab-title="Actions"}
{: tab-group="tone-analyzer"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Toolchain
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `toolchain` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 89. Platform roles - Toolchain" caption-side="top"}
{: #platform-roles-table89}
{: tab-title="Platform roles"}
{: tab-group="toolchain"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `toolchain.dashboard.view` | View instances of the Toolchain service. | Administrator, Editor, Operator |
| `toolchain.instance.read-properties` | Read toolchain properties. | Administrator, Editor, Viewer |
| `toolchain.instance.update-properties` | Update toolchain properties. | Administrator, Editor |
| `toolchain.instance.create-bindings` | Add a tool integration to a toolchain within a resource group. | Administrator, Editor |
| `toolchain.instance.delete-bindings` | Remove a tool integration from a toolchain within a resource group. | Administrator, Editor |
| `toolchain.instance.list-bindings` | View the tool integrations that are contained in a toolchain within a resource group. | Administrator, Editor, Viewer |
{: caption="Table 89. Service actions - Toolchain" caption-side="top"}
{: #actions-table89}
{: tab-title="Actions"}
{: tab-group="toolchain"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Transit Gateway
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `transit` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
{: row-headers}
{: caption="Table 90. Service roles - Transit Gateway" caption-side="top"}
{: #service-roles-table90}
{: tab-title="Service roles"}
{: tab-group="transit"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `transit.transit.manage` | Transit service manager | Manager |
{: caption="Table 90. Service actions - Transit Gateway" caption-side="top"}
{: #actions-table90}
{: tab-title="Actions"}
{: tab-group="transit"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Transit Gateway
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `transit` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
{: row-headers}
{: caption="Table 91. Service roles - Transit Gateway" caption-side="top"}
{: #service-roles-table91}
{: tab-title="Service roles"}
{: tab-group="transit"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `transit.transit.manage` | Transit service manager | Manager |
{: caption="Table 91. Service actions - Transit Gateway" caption-side="top"}
{: #actions-table91}
{: tab-title="Actions"}
{: tab-group="transit"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## User Management
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `user-management` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can view, invite, and update users. You can also view and update user profile settings. |
| Editor | As an editor, you can view, invite, and update users. You can also view and update profile settings. |
| Operator | As an operator, you can view users in the account and view profile settings. |
| Viewer | As a viewer, you can view users in the account and view profile settings. |
{: row-headers}
{: caption="Table 92. Platform roles - User Management" caption-side="top"}
{: #platform-roles-table92}
{: tab-title="Platform roles"}
{: tab-group="user-management"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `user-management.email.retrieve` |  |  |
| `user-management.user.create` | Add a user to the account | Administrator, Editor |
| `user-management.user.update` | Update a user in the account | Administrator, Editor |
| `user-management.user.system-update` |  |  |
| `user-management.user.state-change` | Change the state of a user in the account | Administrator, Editor |
| `user-management.user.system-state-change` |  |  |
| `user-management.user.register` |  |  |
| `user-management.user.verify` |  |  |
| `user-management.user.delete` | Remove a user from the account | Administrator, Editor |
| `user-management.user.retrieve` | Retrieve users from the account | Administrator, Editor, Operator, Viewer |
| `user-management.invitation-email.create` | Resend email invitation | Administrator, Editor |
| `user-management.preference.update` | Update user preferences | Administrator, Editor |
| `user-management.preference.retrieve` | Retrieve user preferences | Administrator, Editor, Operator, Viewer |
| `user-management.user-linkage.create` |  |  |
| `user-management.user-linkage.update` |  |  |
| `user-management.user-linkage.delete` |  |  |
| `user-management.user-linkage.retrieve` | Retrieve user linkages | Administrator, Editor, Operator, Viewer |
| `user-management.user-setting.update` | Update user settings | Administrator, Editor |
| `user-management.user-setting.retrieve` | Retrieve user settings | Administrator, Editor, Operator, Viewer |
{: caption="Table 92. Service actions - User Management" caption-side="top"}
{: #actions-table92}
{: tab-title="Actions"}
{: tab-group="user-management"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Virtual Private Cloud
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.vpc` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 93. Platform roles - Virtual Private Cloud" caption-side="top"}
{: #platform-roles-table93}
{: tab-title="Platform roles"}
{: tab-group="is.vpc"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.vpc.vpc.read` | View a Virtual Private Cloud (VPC) | Administrator, Editor, Operator, Viewer |
| `is.vpc.vpc.create` | Create a Virtual Private Cloud (VPC) | Administrator, Editor |
| `is.vpc.vpc.delete` | Delete a Virtual Private Cloud (VPC) | Administrator, Editor |
| `is.vpc.vpc.update` | Update a Virtual Private Cloud (VPC) | Administrator, Editor |
| `is.vpc.vpc.list` | List Virtual Private Clouds (VPC) | Administrator, Editor, Operator, Viewer |
| `is.vpc.vpc.operate` | Operate a Virtual Private Clouds (VPC) | Administrator, Editor, Operator |
{: caption="Table 93. Service actions - Virtual Private Cloud" caption-side="top"}
{: #actions-table93}
{: tab-title="Actions"}
{: tab-group="is.vpc"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Virtual Server for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.instance` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 94. Platform roles - Virtual Server for VPC" caption-side="top"}
{: #platform-roles-table94}
{: tab-title="Platform roles"}
{: tab-group="is.instance"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| IP Spoofing Operator | As the IP spoofing operator, you can enable or disable the IP spoofing check on virtual server instances. This role should only be granted if necessary.  |
{: row-headers}
{: caption="Table 94. Service roles - Virtual Server for VPC" caption-side="top"}
{: #service-roles-table94}
{: tab-title="Service roles"}
{: tab-group="is.instance"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.instance.instance.list` |  | Administrator, Editor, Operator, Viewer |
| `is.instance.instance.create` |  | Administrator, Editor |
| `is.instance.instance.read` |  | Administrator, Editor, Operator, Viewer |
| `is.instance.instance.update` |  | Administrator, Editor |
| `is.instance.instance.delete` |  | Administrator, Editor |
| `is.instance.instance.operate` | As an administrator, an editor or an operator, you can operate on a virtual server instance | Administrator, Editor, Operator |
| `is.instance.instance-template.read` | View an Instance Template  | Administrator, Editor, Operator, Viewer |
| `is.instance.instance-template.create` | Create an Instance Template | Administrator, Editor |
| `is.instance.instance-template.update` | Update an Instance Template | Administrator, Editor |
| `is.instance.instance-template.delete` | Delete an Instance Template | Administrator, Editor |
| `is.instance.instance.ip-spoofing` | IP spoofing control for Virtual Server Instance | IP Spoofing Operator |
{: caption="Table 94. Service actions - Virtual Server for VPC" caption-side="top"}
{: #actions-table94}
{: tab-title="Actions"}
{: tab-group="is.instance"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Visual Recognition
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `watson-vision-combined` for the service name.

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Reader | Reader |
| Writer | Writer |
{: row-headers}
{: caption="Table 95. Service roles - Visual Recognition" caption-side="top"}
{: #service-roles-table95}
{: tab-title="Service roles"}
{: tab-group="watson-vision-combined"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `GET /watson-vision-combined` |  | Manager, Reader, Writer |
| `POST /watson-vision-combined` |  | Manager, Writer |
| `DELETE /watson-vision-combined` |  | Manager, Writer |
{: caption="Table 95. Service actions - Visual Recognition" caption-side="top"}
{: #actions-table95}
{: tab-title="Actions"}
{: tab-group="watson-vision-combined"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## VMware Solutions
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `vmware-solutions` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 96. Platform roles - VMware Solutions" caption-side="top"}
{: #platform-roles-table96}
{: tab-title="Platform roles"}
{: tab-group="vmware-solutions"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `vmware-solutions.instances.create` | Create IBM Cloud for VMware Solutions instances | Administrator |
| `vmware-solutions.instances.delete` | Delete IBM Cloud for VMware Solutions instances | Administrator |
| `vmware-solutions.instances.view` | List or view IBM Cloud for VMware Solutions instances | Administrator, Editor, Operator, Viewer |
| `vmware-solutions.instances.update` | Update IBM Cloud for VMware Solutions instances | Administrator, Editor |
| `vmware-solutions.account.update` | Update account settings for IBM Cloud for VMware Solutions | Administrator |
{: caption="Table 96. Service actions - VMware Solutions" caption-side="top"}
{: #actions-table96}
{: tab-title="Actions"}
{: tab-group="vmware-solutions"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Voice Agent with Watson
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `voiceagent` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 97. Platform roles - Voice Agent with Watson" caption-side="top"}
{: #platform-roles-table97}
{: tab-title="Platform roles"}
{: tab-group="voiceagent"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 97. Service roles - Voice Agent with Watson" caption-side="top"}
{: #service-roles-table97}
{: tab-title="Service roles"}
{: tab-group="voiceagent"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `voiceagent.agent.manage` | Manage all aspects of a Voice Agent with Watson instance. | Manager, Reader, Writer |
| `voiceagent.agent.view` | View configurations for all agents of a Voice Agent with Watson instance. | Reader |
| `voiceagent.usage.view` | View usage for all agents of a Voice Agent with Watson instance. | Reader |
| `voiceagent.log.view` | View all failure logs for all agents of a Voice Agent with Watson instance. | Reader |
| `voiceagent.sms.send` | Use the SMS gateway API to send SMS messages for a Voice Agent with Watson instance. | Administrator, Editor, Manager, Operator, Writer |
| `voiceagent.voice.inbound` | Authenticate inbound calls for a Voice Agent with Watson instance using SIPS. | Manager, Writer |
| `voiceagent.voice.outbound` | Use the outbound calling API to start outbound calls for a Voice Agent with Watson instance. | Manager, Writer |
{: caption="Table 97. Service actions - Voice Agent with Watson" caption-side="top"}
{: #actions-table97}
{: tab-title="Actions"}
{: tab-group="voiceagent"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## VPC Infrastructure Services
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is` for the service name.

No supported roles.
## VPC+ Cloud Migration
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `migrationtool-from-wanclds` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 99. Platform roles - VPC+ Cloud Migration" caption-side="top"}
{: #platform-roles-table99}
{: tab-title="Platform roles"}
{: tab-group="migrationtool-from-wanclds"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Service Configuration Reader | The ability to read services configuration for Governance management. |
{: row-headers}
{: caption="Table 99. Service roles - VPC+ Cloud Migration" caption-side="top"}
{: #service-roles-table99}
{: tab-title="Service roles"}
{: tab-group="migrationtool-from-wanclds"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `migrationtool-from-wanclds.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 99. Service actions - VPC+ Cloud Migration" caption-side="top"}
{: #actions-table99}
{: tab-title="Actions"}
{: tab-group="migrationtool-from-wanclds"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## VPN for VPC
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `is.vpn` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 100. Platform roles - VPN for VPC" caption-side="top"}
{: #platform-roles-table100}
{: tab-title="Platform roles"}
{: tab-group="is.vpn"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `is.vpn.vpn.create` |  | Administrator, Editor |
| `is.vpn.vpn.update` |  | Administrator, Editor |
| `is.vpn.vpn.delete` |  | Administrator, Editor |
| `is.vpn.vpn.read` |  | Administrator, Editor, Operator, Viewer |
| `is.vpn.vpn.list` |  | Administrator, Editor, Operator, Viewer |
| `is.vpn.dashboard.view` |  | Administrator, Editor, Operator, Viewer |
{: caption="Table 100. Service actions - VPN for VPC" caption-side="top"}
{: #actions-table100}
{: tab-title="Actions"}
{: tab-group="is.vpn"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Watson Assistant
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `conversation` for the service name.

| Role | Description |
| ----- | :----- |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 101. Platform roles - Watson Assistant" caption-side="top"}
{: #platform-roles-table101}
{: tab-title="Platform roles"}
{: tab-group="conversation"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | As a manager, you have permissions beyond the writer role to complete privileged actions as defined by the service. In addition, you can create and edit service-specific resources. |
| Reader | As a reader, you can perform read-only actions within a service such as viewing service-specific resources. |
| Writer | As a writer, you have permissions beyond the reader role, including creating and editing service-specific resources. |
{: row-headers}
{: caption="Table 101. Service roles - Watson Assistant" caption-side="top"}
{: #service-roles-table101}
{: tab-title="Service roles"}
{: tab-group="conversation"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `GET /conversation` | Can use API endpoints to extract data from skills and assistants | Manager, Reader, Writer |
| `POST /conversation` | Can use API endpoints to create data & to use the message endpoint | Manager, Reader, Writer |
| `DELETE /conversation` | Can use API endpoints to delete data from skills and assistant | Manager, Reader, Writer |
| `PATCH /conversation` | Can use API endpoint to modify data from skills and assistant | Manager, Reader, Writer |
| `PUT /conversation` | Can use API endpoint to modify data from skills and assistant | Manager, Reader, Writer |
| `conversation.assistant.legacy` | Can perform authoring methods for a workspace through v1 APIs. | Manager |
| `conversation.skill.write` | Can rename, edit, or delete a skill. | Manager, Writer |
| `conversation.skill.read` | Can open and view a skill. | Manager, Reader, Writer |
| `conversation.assistant.write` | Can rename, edit, or delete an assistant. | Manager, Writer |
| `conversation.assistant.read` | Can open and view an assistant. | Manager, Reader, Writer |
| `conversation.logs.read` | Can view skill analytics and access user conversation logs. | Manager |
| `conversation.assistant.list` | Can list assistant or skill | Manager, Reader, Viewer, Writer |
| `conversation.assistant.default` | Default access for Assistant | Manager, Reader, Viewer, Writer |
{: caption="Table 101. Service actions - Watson Assistant" caption-side="top"}
{: #actions-table101}
{: tab-title="Actions"}
{: tab-group="conversation"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Watson Knowledge Catalog
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `datacatalog` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | Administrator |
{: row-headers}
{: caption="Table 102. Platform roles - Watson Knowledge Catalog" caption-side="top"}
{: #platform-roles-table102}
{: tab-title="Platform roles"}
{: tab-group="datacatalog"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Role | Description |
| ----- | :----- |
| Manager | Manager |
| Writer | Writer |
{: row-headers}
{: caption="Table 102. Service roles - Watson Knowledge Catalog" caption-side="top"}
{: #service-roles-table102}
{: tab-title="Service roles"}
{: tab-group="datacatalog"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the service role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `datacatalog` |  | Administrator |
| `datacatalog.catalog.create` |  | Administrator, Manager, Writer |
{: caption="Table 102. Service actions - Watson Knowledge Catalog" caption-side="top"}
{: #actions-table102}
{: tab-title="Actions"}
{: tab-group="datacatalog"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Watson OpenScale
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `aiopenscale` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
| Viewer | As a viewer, you can view service instances, but you can't modify them. |
{: row-headers}
{: caption="Table 103. Platform roles - Watson OpenScale" caption-side="top"}
{: #platform-roles-table103}
{: tab-title="Platform roles"}
{: tab-group="aiopenscale"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `aiopenscale.dashboard.view` |  | Administrator, Editor, Operator, Viewer |
{: caption="Table 103. Service actions - Watson OpenScale" caption-side="top"}
{: #actions-table103}
{: tab-title="Actions"}
{: tab-group="aiopenscale"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}

## Watson Studio
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `data-science-experience` for the service name.

No supported roles.
## WebSphere Application Server
Review the available platform and service roles available and the actions mapped to each to help you assign access. If you're using the CLI or API to assign access, use `websphereappsvr` for the service name.

| Role | Description |
| ----- | :----- |
| Administrator | As an administrator, you can perform all platform actions based on the resource this role is being assigned, including assigning access policies to other users. |
| Editor | As an editor, you can perform all platform actions except for managing the account and assigning access policies. |
| Operator | As an operator, you can perform platform actions required to configure and operate service instances, such as viewing a service's dashboard. |
{: row-headers}
{: caption="Table 105. Platform roles - WebSphere Application Server" caption-side="top"}
{: #platform-roles-table105}
{: tab-title="Platform roles"}
{: tab-group="websphereappsvr"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the platform role name and the column headers identify the specific information available about each role."}

| Action | Description | Roles |
| ----- | :----- | :----- |
| `websphereappsvr.dashboard.view` |  | Administrator, Editor, Operator |
{: caption="Table 105. Service actions - WebSphere Application Server" caption-side="top"}
{: #actions-table105}
{: tab-title="Actions"}
{: tab-group="websphereappsvr"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table provides the available actions for the service, descriptions of each, and the roles that each action are mapped to."}
