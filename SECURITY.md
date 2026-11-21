# Security and Public Repository Rules

Do not commit customer or prospect names, contact details, customer domains, real email content, commercial values, renewal dates, churn data, internal notes, production field names, report identifiers, tenant or environment identifiers, connection references, distribution lists, credentials, production workflow exports, run history or generated production reports.

Use placeholders and completely synthetic examples only.

## Reporting a concern

If confidential information is committed accidentally:

1. Remove public access if possible.
2. Notify the repository owner and the organisation's security or privacy contact.
3. Revoke exposed credentials or tokens immediately.
4. Remove the information from Git history rather than only deleting the latest version.
5. Review forks, releases, actions logs and cached artefacts for further exposure.

Do not open a public issue containing the exposed information.
