# CKAN Extensions Monitor

This is a monitor that twice a week runs the test suite of main CKAN extensions against master.

## Status

- ![ckanext-dcat](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-dcat/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-dcat.yml)
- ![ckanext-geoview](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-geoview/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-geoview.yml)
- ![ckanext-harvest](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-harvest/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-harvest.yml)
- ![ckanext-issues](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-issues/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-issues.yml)
- ![ckanext-pages](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-pages/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-pages.yml)
- ![ckanext-pdfview](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-pdfview/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-pdfview.yml)
- ![ckanext-saml2auth](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-saml2auth/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-saml2auth.yml)
- ![ckanext-scheming](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-scheming/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-scheming.yml)
- ![ckanext-sitesearch](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-sitesearch/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-sitesearch.yml)
- ![ckanext-xloader](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-xloader/badge.svg) - [Run](https://github.com/pdelboca/ckan-extensions-monitor/actions/workflows/.ckanext-xloader.yml)


## Notes

The main goal is to keep track if the most common CKAN extensions are running agains CKAN's master. This can be use to easily detect breaking changes on CKAN core.

Tests are run At 12:00am on Tuesday and Thursday (`0 0 * * 2,4`) to have a fresh run before CKAN's Tech meetings.

## Contributing

To add a new extension just submit a PR with a specific workflow for the extension. You can take a look at [at this commit](542e0b27e659b93415b157ca013d302d4209db16) for reference on how to create a workflow.
