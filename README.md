# Crossref Content Registration Action

This GitHub Action uses the [Crossref Depoitor API](https://www.crossref.org/documentation/register-maintain-records/direct-deposit-xml/https-post/) to register content.

### Required environment variables

* `CROSSREF_USERNAME_WITH_ROLE` - Crossref member username
* `CROSSREF_PASSWORD` - Crossref member password
* `CROSSREF_DEPOSITOR_NAME` - Name of the organization registering the DOIs.
* `CROSSREF_DEPOSITOR_EMAIL` - e-mail address to which batch success and/or error messages are sent.
* `CROSSREF_REGISTRANT` - The organization responsible for the information being registered.

