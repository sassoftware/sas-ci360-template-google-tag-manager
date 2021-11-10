# SAS Customer Intelligence 360 - Google Community Template

## Table of Contents

* <a href="#overview">Overview</a>
* <a href="#prerequisites">Prerequisites</a>
* <a href="#installation">Installation</a>
* <a href="#getting-started">Getting Started</a>
* <a href="#contributing">Contributing</a>
* <a href="#license">License</a>
* <a href="#resources">Additional Resources</a>

## Overview

Google Tag Manager allows deploying marketing and other javascript easily across your website. With this template we employ the use of Google Tag Manager's Community Templates in order to easily deploy javascript actions for Customer Intelligence 360.

### Prerequisites

Users of this must already own a Google Tag Manager (GTM) account and a Software License for Customer Intelligence 360. The CI360 Tag must already be deployed on your website. Instructions can be found [here](https://go.documentation.sas.com/doc/en/cintcdc/production.a/cintag/ing-sastag-config.htm).

### Installation

1. Navigate and login to [Google Tag Manager](https://tagmanager.google.com/) using your browser
2. Navigate to your desired account for your web property
3. Navigate to *Templates* by clicking on the left
4. Click on Search Gallery
5. Search for Customer Intelligence 360 by SAS and select it
6. Click on Add to workspace, and add again to agree to the permissions

Alternatively, if the listing is unavailable in the community template gallery you can install manually using the following steps:

1. Download the latest template.tpl file in this repository
2. Navigate and login to [Google Tag Manager](https://tagmanager.google.com/) using your browser
3. Navigate to your desired account for your web property
4. Navigate to *Templates* by clicking on the left

## Getting Started

To get started you must first install the latest CI360 tag into CI360, please see the latest instructions in the CI360 documentation [here](https://go.documentation.sas.com/doc/en/cintcdc/production.a/cintag/ing-sastag-config.htm)

**Setting up a tag to collect data:**

1. (Optional for Custom Events) Create a custom event in the CI360 User Interface. 

*Note: Please note the API key for the Custom Event*

2. **Navigate** and **login** to [Google Tag Manager](https://tagmanager.google.com/) using your browser
3. Choose the web property you want
4. Click **Tags** on the left and then **New** on the right of the screen
5. Choose **Customer Intelligence 360** from the list in the tag configuration
6. Choose your desired **Event Name** from the dropdown list
7. Enter the details, for each event type the details will be different. Be sure to fill out all relavent information. If you are implementing a custom event, please use the API key from step 1 here)
8. In the Advanced Settings sections you can choose the **Tag Firing Priority**, this can be useful when many tags are firing using the same trigger or on page load, be sure to prioritize loading your CI360 tag before firing any secondary tags
9. Choose the **Trigger** for the Tag (this can be page load, clicking on a button, waiting after 15 seconds of load, etc.)
10. Test your rule


## Contributing

> We welcome your contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to submit contributions to this project. 

## License

> This project is licensed under the [Apache 2.0 License](LICENSE).

## Additional Resources

* [SAS Customer Intelligence 360 Documentation](https://go.documentation.sas.com/doc/en/cintcdc/production.a/cintwlcm/home.htm)
* [SAS Customer Intelligence 360 Product Page](https://www.sas.com/en_us/solutions/customer-intelligence.html)
* [SAS Communities](https://communities.sas.com/)
* [SAS App Central](https://cloud.sas.com/appcentral)