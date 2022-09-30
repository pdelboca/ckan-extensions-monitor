# CKAN Extensions Monitor

This is a monitor that periodically executes test of main CKAN extensions against master.

The main goal is to keep track if the most common CKAN extensions are running agains CKAN's master. This can be use to easily detect breaking changes on CKAN core.

Tests are run At 12:00am on Tuesday and Thursday (`0 0 * * 2,4`) to have a fresh run before CKAN's Tech meetings.

### Extensions

- ![ckanext-sitesearch](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-sitesearch/badge.svg)
- ![ckanext-xloader](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-xloader/badge.svg)
- ![ckanext-pages](https://github.com/pdelboca/ckan-extensions-monitor/workflows/ckanext-pages/badge.svg)
