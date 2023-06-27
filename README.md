# VMware Carbon Emissions Explorer ESG Dashboard

VMware's Office of the CTO (OCTO) created this vROps dashboard to show the carbon footprint of your environment.  This dashboard was demo'd in the VMware OCTO Sustainability booth at VMware Explore 2022.

[Click HERE for a demo video of the dashboard](https://www.youtube.com/watch?v=Uqe1zpoXXs8)

## Installation

### Super Metrics
Import the VMware-Carbon-Emissions-Explorer-Supermetrics.json:
1. Left side navigation pane -> Configure -> Super Metrics
![Super Metrics](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/Super-Metrics.jpg?raw=true)
   - Click the three dot menu and select Import
     
     ![Super Metrics Menu](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/import-Super-Metrics-menu.jpg?raw=true)
     - Browse to the json file and select "Overwrite existing Super Metric"
![Super Metrics Menu](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/import-Super-Metrics.jpg?raw=true)
     - You may have to enable the Super Metric in a policy to collect data.
     - To enable the super metric, edit the Super Metric, navigate to Policies, and select the policy to enable the Super Metric.
![Edit Metrics Policy](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/edit-super-metrics.jpg?raw=true)

       ![Edit Metrics Policy](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/enable-policy-super-metric-2.jpg?raw=true)

     - You can verify the Super Metrics imported successfully by searching "carbon" and "cluster"
![Verify Metrics Policy](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/carbon-super-metrics.jpg?raw=true)

       ![Verify Metrics Policy](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/cluster-super-metric.jpg?raw=true)

     - You can verify the Policies enabled for the Super Metrics by navigating to it
![Verify Metrics Policy](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/policies-super-metrics.jpg?raw=true)

     - Once enabled, you'll have to wait for a polling interval for the dashboard to display data.

### Views
Import the VMware-Carbon-Emissions-Explorer-Views.zip:
1. Left side navigation pane -> Visualize -> Views
   - Click Manage under the Views pane, then the three dot menu and select Import
![Manage Views](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/manage-views.jpg?raw=true)
     - Browse to the zip file and select "Overwrite existing View"
![Import Views](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/import-views.jpg?raw=true)

     - Verify the Views were imported by searching "carbon"
![Verify Views](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/carbon-views.jpg?raw=true)

### Dashboard
Import the VMware-Carbon-Emissions-Explorer-Dashboard.zip:
1. Left side navigation pane -> Visualize -> Dashboards
   - Click Manage under the Dashboards pane, then the three dot menu and select Import
![Manage Dashboard](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/import-dashboard.jpg?raw=true)
     - Browse to the zip file and select "Overwrite"
![Import Dashboard](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/import-dashboard-3.jpg?raw=true)

     - After the Dashboard is imported, you can locate it by searching the Dashboards section
![Import Dashboard](https://github.com/ThepHuck/vROpsESGDash/blob/main/installation-screenshots/view-dashboard.jpg?raw=true)

### Notes
 - If you navigate to the Dashboard and every widget is blank, stating select a resource or view, please wait at least 10 minutes for the collection cycles to complete.
