# ADFS Logs

You will find here examples of different ADFS sign-ins and their associated events. The list of all possible events, their structure and description can be found here: [ADFS Help](https://adfshelp.microsoft.com/AdfsEventViewer/GetAdfsEventList).

Here are the available scenarios:

➡️ [Extranet - Form Based Authentication - Failure with Smart Lockout](/Extranet%20-%20FBA%20-%20Failure%20with%20Smart%20Lockout.md)
An external user (meaning the request goes through a WAP server) is failing to authenticate using Form Based Authentication and the Smart Account Lockout feature is enabled.

➡️ [Extranet - Exchange Active Sync - Failure](/Extranet%20-%20EAS%20-%20Failure.md)
An external user is failing to authenticate using an Exchange Active Sync client.

➡️ [Extranet - Exchange Active Sync - Success](/Extranet%20-%20EAS%20-%20Success.md)
An external user is successfully authenticating using an Exchange Active Sync client.

➡️ [Intranet - Form Based Authentication - Failure](/Intranet%20-%20FBA%20-%20Failure.md)
An internal user is failing to authenticate using Form Based Authentication.

➡️ [Intranet - Form Based Authentication - Success](/Intranet%20-%20FBA%20-%20Success.md)
An internal user is successfully authenticating using Form Based Authentication.

➡️ [Intranet - Windows Integrated Authentication - Failure](/Intranet%20-%20WIA%20-%20Failure.md)
An internal user is failing to authenticate using Windows Integrated Authentication (meaning Kerberos or NTLM in the browser).

➡️ [Intranet - Windows Integrated Authentication - Success](/Intranet%20-%20WIA%20-%20Success.md)
An internal user is successfully authenticating using Form Based Authentication.

➡️ [Intranet - Hybrid Azure AD Join - Success](/Intranet%20-%20Hybrid%20Azure%20AD%20Join%20-%20Success.md)
A device is successfully getting a token on the windowstransport endpoint (part of the Hybrid Azure AD Join process in a federated environment).

## 📃 Additional  Resources

- To enable the audit on ADFS servers: https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/troubleshooting/ad-fs-tshoot-logging#security-auditing
