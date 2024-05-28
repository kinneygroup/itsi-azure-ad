## Summary
The ITSI Content Pack for Azure Active Directory (AzureAD) from Kinney Group is a comprehensive solution designed to monitor and ensure the health, security, and performance of Azure Active Directory services. It provides critical insights into Azure AD operations, enabling IT professionals to maintain secure and efficient access to applications within the Microsoft 365 ecosystem. This content pack is an invaluable resource for organizations leveraging Azure AD to streamline their identity management and access control.

- **Holistic Health Monitoring**: Ensures the overall health and performance of Azure AD, including service availability and security posture.
- **Operational Insights**: Delivers actionable intelligence on user and administrative activities, login patterns, and application access anomalies.
- **Proactive Issue Resolution**: Facilitates early detection and troubleshooting of service interruptions, performance degradation, and security risks.

This ITSI Content Pack is open source and available for community collaboration and enhancement on [GitHub](https://www.github.com/kinneygroup).

## Details
The ITSI Content Pack for AzureAD provides a suite of services, KPIs, and relationships designed to monitor the intricate components of Azure Active Directory. It is tailored to address common challenges faced by IT administrators, such as detecting service interruptions, monitoring user and administrative activities, and ensuring optimal performance of identity management services.

For detailed installation instructions, please refer to the [Kinney Group documentation](https://docs.atlas.kinneygroup.com/docs/intro).

### Services
The content pack includes several services, each with a specific focus:

- **Azure Active Directory Health**: The central service for monitoring Azure AD, encompassing all aspects of functionality, including availability and performance.
- **Azure AD Availability**: Focuses on the operational status of Azure AD, tracking service interruptions and recovery processes.
- **Azure AD Performance**: Monitors performance metrics related to user, role, login, group, directory, and application administration activities.
- **User Administration**: Targets user management activities, such as user additions, license changes, and password resets.
- **Role Administration**: Tracks role management activities, including role member additions and removals.
- **Login Activity**: Monitors login patterns and authentication methods to detect security breaches and operational inefficiencies.
- **Group Administration**: Monitors group-related administrative actions such as group additions and removals.
- **Directory Administration**: Tracks directory-related activities, including domain authentication and password policy changes.
- **Application Administration**: Monitors application-related administrative actions, such as service principal management.

### KPIs
Key Performance Indicators (KPIs) are used to measure the effectiveness of each service:

- **Service Interruption Count**: Tracks the number of service interruptions detected.
- **Restoration Time**: Measures the average time taken to restore service after an interruption.
- **Service Degradation Events**: Monitors the number of events where service performance is below acceptable thresholds.
- **User Sign-ins**: Counts the number of successful user sign-ins.
- **Logon Errors**: Tracks the number of failed login attempts.
- **Risky Login Events**: Monitors login attempts that have been flagged as risky.
- **User Additions**: Counts the number of users added to Azure AD.
- **License Changes**: Tracks changes made to user licenses.
- **Password Resets**: Monitors the frequency of user password resets.
- **Role Member Additions**: Counts the number of times users are added to roles.
- **Role Member Removals**: Tracks the number of times users are removed from roles.
- **Failed Login Attempts**: Counts the number of unsuccessful login attempts.
- **Authentication Method Usage**: Monitors the usage of different authentication methods.
- **Abnormal Login Patterns**: Detects login patterns that deviate from the norm, indicating potential security issues.
- **Group Additions**: Counts the number of groups added to Azure AD.
- **Group Removals**: Tracks the number of groups removed from Azure AD.
- **Domain Authentication Changes**: Monitors changes to domain authentication settings.
- **Password Policy Updates**: Tracks updates to password policies.
- **Service Principal Changes**: Monitors changes to service principal configurations.
- **Application Access Anomalies**: Detects unusual patterns in application access that may indicate security issues.

### Relationships
The services within this content pack are designed to work in concert, providing a comprehensive view of Azure AD's health and performance. For example, the Azure Active Directory Health service relies on the data provided by the Azure AD Availability and Azure AD Performance services to offer a complete picture of the directory's status.

## Installation

### Installation Prerequisites:
- Splunk IT Service Intelligence (ITSI)
- Access to Azure AD data sources
- Familiarity with Splunk and ITSI

For a step-by-step guide on installing ITSI content packs, please visit the [Kinney Group documentation](https://docs.atlas.kinneygroup.com/docs/intro).

The content pack can be found on our [GitHub repository](https://www.github.com/kinneygroup), which includes a detailed README for setup instructions.

For additional information on installing content packs into ITSI, refer to the [Splunk documentation](https://docs.splunk.com/Documentation/ITSI).

## Troubleshooting

If you encounter any issues during the installation or usage of this content pack, please consult the following resources:

- [Kinney Group Documentation](https://docs.atlas.kinneygroup.com/docs/intro)
- [GitHub Repository and README](https://www.github.com/kinneygroup)
- For direct assistance, email [support@kinneygroup.com](mailto:support@kinneygroup.com)

## Contact

For further support or inquiries, please contact us via email at [support@kinneygroup.com](mailto:support@kinneygroup.com).

## Version History

| Version | Date       | Description                                      |
|---------|------------|--------------------------------------------------|
| 1.0.0   | 2023-04-01 | Initial release of the AzureAD ITSI Content Pack |
