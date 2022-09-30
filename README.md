# CKAN Extensions Monitor

This is a monitor that twice a week runs the test suite of main CKAN extensions against master.

### Status

- ![ckanext-sitesearch](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-sitesearch/badge.svg)
- ![ckanext-xloader](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-xloader/badge.svg)
- ![ckanext-pages](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-pages/badge.svg)
- ![ckanext-issues](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-issues/badge.svg)
- ![ckanext-harvest](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-harvest/badge.svg)
- ![ckanext-dcat](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-dcat/badge.svg)
- ![ckanext-geoview](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-geoview/badge.svg)
- ![ckanext-scheming](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-scheming/badge.svg)
- ![ckanext-saml2auth](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-saml2auth/badge.svg)


### Notes

The main goal is to keep track if the most common CKAN extensions are running agains CKAN's master. This can be use to easily detect breaking changes on CKAN core.

Tests are run At 12:00am on Tuesday and Thursday (`0 0 * * 2,4`) to have a fresh run before CKAN's Tech meetings.
