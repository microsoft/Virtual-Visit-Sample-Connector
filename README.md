# Virtual Visit Sample Connector

## Scenario

A very common healthcare scenario for providers as well as payors is creating an on-demand virtual visit. The Teams platform Microsoft has a Virtual Appointment capability available through the Microsoft Graph that extends the *onlineMeeting* to include enhancements like a mobile-browser join (without requiring a custom communication service or download like the Teams app), an enhanced waiting room, and additional reporting/analytics for virtual appointments. Additionally, meetings can be associated to meeting ID's from 3rd party scheduling systems directly within the virtual appointment definition.

Unfortunately, at this time there is not a published Connector for these API calls, so building a solution requires some additional steps and skills to either manually call the Graph API or build a custom connector.

## Solution

This repository includes a sample OpenAPI (Swagger) definition which can be imported through the Power Platform maker portal and used to test out the capabilities. While creating a custom connector is not overly complex, it can be helpful to learn from an example instead of starting from a completely "blank page".

[Virtual Visit OpenAPI definition](./Virtual-Visit.swagger.json)

As of this release, the virtualAppointment capabilities are in [public preview](https://docs.microsoft.com/en-us/graph/versioning-and-support#beta-version), which is reflected in the OpenAPI definition.

## Deployment



## Background

The Microsoft Graph is the gateway to data and intelligence in Microsoft 365 includes many capabilities that are useful when building apps, including low-code applications using Logic Apps and the Power Platform. There are hundreds of Microsoft Connectors that make use of these services, while many more capabilities are available just out of sight.

Custom connectors can provide a purpose-driven experience, standardizing how low-code developers interact with both well-known or custom APIs, improving time to value and reducing technology risk.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
