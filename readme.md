# SC-400: Microsoft Information Protection Administrator

This project is a work in progress while I study and take notes for the SC-400 Exam.

# Disclaimer

Do not rely on these notes to pass the exam. It's advised to use Microsoft's study guide for the exam: https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4Mr80


## Skills measured as of February 1, 2023

### Audience profile

The Microsoft information protection administrator plans and implements controls that meet organizational information protection and governance requirements by using Microsoft 365 information protection services. This person is responsible for translating information protection requirements and controls into technical implementation.

They assist information technology (IT) personnel, business application owners, human resources and legal stakeholders in implementing technology solutions that support the policies and controls necessary to sufficiently address regulatory requirements for their organization. They also work with the security and governance leadership, such as a chief compliance officer, chief data officer, and security officer, to evaluate the full breadth of associated enterprise risk and partner to develop those policies.

This person defines applicable requirements and evaluates IT processes and operations against those policies and controls. They are responsible for creating policies and rules for content classification, data loss prevention, governance, and protection.

---

# Exam Objectives

## <a href="https://github.com/oliverbebber/SC-400-Study-Notes/blob/main/1.%20Implement%20information%20protection.md#implement-information-protection">Implement information protection (35–40%)</a>

### Create and manage sensitive information types

- Plan for sensitive information types
- Select a sensitive information type based on an organization's requirements
- Create and manage custom sensitive information types
- Create custom sensitive information types with exact data match
- Implement document fingerprinting
- Create and use a keyword dictionary

### Create and manage trainable classifiers

- Identify when to use trainable classifiers
- Design and create a trainable classifier
- Test a trainable classifier
- Retrain a classifier

### Implement and manage sensitivity labels

- Design and implement roles and permissions for administering sensitivity labels
- Design and create sensitivity labels
- Configure and manage sensitivity label policies
- Apply sensitivity labels to Microsoft Teams, Microsoft 365 groups, Microsoft Power BI, and Microsoft SharePoint sites
- Configure and publish auto-labelling policies
- Monitor data classification and label usage by using label analytics tools such as Content explorer and Activity explorer
- Apply bulk classification to on-premises data by using the AIP unified labelling scanner
- Manage protection settings and marking for applied sensitivity labels
- Administer reporting, tracking, and access of sensitivity labels and protected content
- Create or extend existing sensitivity labels to Microsoft Purview

### Design and implement encryption for email messages

- Design an email encryption solution based on methods available in Microsoft 365
- Implement Microsoft Purview Message Encryption
- Implement Microsoft Purview Advanced Message Encryption

## <a href="https://github.com/oliverbebber/SC-400-Study-Notes/blob/main/2.%20Implement%20data%20loss%20prevention.md#implement-data-loss-prevention">Implement data loss prevention (30–35%)</a>

### Create and configure data loss prevention (DLP) policies

- Recommend a DLP solution for an organization
- Configure permissions for DLP
- Create, test, and tune DLP policies
- Configure DLP for policy and rule precedence
- Configure DLP policies for Microsoft Exchange Online, Microsoft SharePoint Online, Microsoft OneDrive, Microsoft Teams, Microsoft Power BI, and on-premises repositories
- Configure DLP policies for use in Microsoft Defender for Cloud Apps
- Configure file policies in Microsoft Defender for Cloud Apps to use DLP policies

### Implement and monitor Microsoft Endpoint DLP

- Create and maintain DLP policies for endpoints
- Configure endpoint DLP settings
- Specify a deployment method for device onboarding
- Identify endpoint requirements for device onboarding
- Monitor endpoint activities
- Implement Microsoft Purview Extension

### Analyze and respond to data loss prevention policies and activities

- Analyze data loss prevention reports
- Analyze data loss prevention activities by using Activity explorer
- Remediate data loss prevention policy violations in the Microsoft Purview compliance portal
- Remediate data loss prevention violations in Microsoft Defender for Cloud Apps

## <a href="https://github.com/oliverbebber/SC-400-Study-Notes/blob/main/3.%20Implement%20information%20governance.md#implement-information-governance">Implement information governance (25–30%)</a>

### Retain and delete data by using retention labels

- Plan for information retention and disposition by using retention labels
- Create retention labels
- Configure and manage adaptive scopes
- Configure and publish retention label policies
- Configure and publish auto-apply label policies

### Manage data retention in Microsoft 365

- Create and apply retention policies for Microsoft SharePoint Online and OneDrive
- Create and apply retention policies for Microsoft Teams
- Configure preservation locks
- Recover retained content in Microsoft 365
- Implement retention policies and tags in Microsoft Exchange Online
- Apply mailbox holds in Microsoft Exchange Online
- Implement Microsoft Exchange Online archiving policies

### Implement records management in Microsoft 365

- Plan for records management
- Configure labels for records management
- Manage retention requirements with a file plan
- Configure automatic retention using file plan descriptors
- Classify records using retention labels and policies
- Implement in-place records management in Microsoft SharePoint Online
- Manage event-based retention
- Manage disposition of records


# References

- https://learn.microsoft.com/en-us/certifications/exams/sc-400
- https://learn.microsoft.com/en-us/training/paths/implement-information-protection/
- https://learn.microsoft.com/en-us/training/paths/implement-data-loss-prevention/
- https://learn.microsoft.com/en-us/training/paths/implement-information-governance/