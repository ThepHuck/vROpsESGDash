# VMware Carbon Transparency ESG Dashboard

VMware's Office of the CTO (OCTO) created this vROps dashboard to show the carbon footprint of your environment.  This dashboard was demo'd in the VMware OCTO Sustainability booth at VMware Explore 2022.

[Click HERE for a demo video of the dashboard](https://www.youtube.com/watch?v=Uqe1zpoXXs8)

## Installation

###### Super Metrics
Import the VMware-Carbon-Transparency-Supermetrics.json:
1. Left side navigation pane -> Configure -> Super Metrics
   - Click the three dot menu and select Import
     - Browse to the json file and select "Overwrite existing Super Metric"
     - You may have to enable the Super Metric in a policy to collect data.  To enable the super metric, edit the Super Metric, navigate to Policies, and select the policy to enable the Super Metric.  Once enabled, you'll have to wait for a polling interval for the dashboard to display data.

###### Views
Import the VMware-Carbon-Transparency-Views.zip:
1. Left side navigation pane -> Visualize -> Views
   - Click Manage under the Views pane, then the three dot menu and select Import
     - Browse to the zip file and select "Overwrite existing View"

###### Dashboard
Import the VMware-Carbon-Transparency-Dashboard.zip:
1. Left side navigation pane -> Visualize -> Dashboards
   - Click Manage under the Dashboards pane, then the three dot menu and select Import
     - Browse to the zip file and select "Overwrite"
