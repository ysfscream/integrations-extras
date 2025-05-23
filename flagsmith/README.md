# Agent Check: Flagsmith

## Overview

[Flagsmith][1] facilitates feature management across web, mobile, and server side applications. The Datadog Flagsmith integration enables you to view information about flag changes directly within Datadog.

Flagsmith provides the following integrations with Datadog:

### Events integration

All flag change events are sent to Datadog. These events are tagged with the environment they were changed in.

### Dashboard widget

Flagsmith's dashboard widget lets you view your Flagsmith Flags and Audit Logs directly in Datadog.

## Setup

In the [Flagsmith Dashboard][2], select the Integrations Menu and then add the Datadog Integration. Enter your [Datadog API Key][3]. For Base URL, enter `https://api.datadoghq.com` if you are using the US Datadog site, or `https://api.datadoghq.eu` if you are using the EU Datadog site.

### Flagsmith Dashboard widget

1. On the [Flagsmith integration tile](/integrations/flagsmith), make sure the integration is installed.
1. Make sure you are logged into Flagsmith with the account you want to see in Datadog.
1. In Datadog, navigate to an existing dashboard or create a new one.
1. Press the **Add Widgets** button to expose the widget drawer.
1. Search for **Flagsmith** to find the Flagsmith widget in the **Apps** section of the widget drawer.
1. Select the **Flagsmith widget icon** to add it to your dashboard and open the **Flagsmith editor** modal. You can choose to add either the Flag or Audit log viewer widget.
1. Select the Flagsmith Organisation, Project and Environment you want to add to your dashboard.
1. Once selected, copy and paste the **Project ID** and **Environment ID** into Datadog.
1. Select the page size and, optionally, a widget title and Flagsmith Tag to filter on.
1. Click **Save** to finish configuring the dashboard widget.

## Data Collected

### Metrics

The Flagsmith integration does not include any metrics.

### Service Checks

The Flagsmith integration does not include any service checks.

### Events

All Flagsmith events are sent to the Datadog event stream.

## Troubleshooting

Need help? See the [Flagsmith documentation][4] or contact [Datadog Support][5].

[1]: https://www.flagsmith.com/
[2]: https://app.flagsmith.com/
[3]: /organization-settings/api-keys
[4]: https://docs.flagsmith.com/integrations/datadog/
[5]: https://docs.datadoghq.com/help/
