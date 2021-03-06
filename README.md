# Google Compute Engine Plugin for Jenkins
The Google Compute Engine (GCE) Plugin allows you to use GCE virtual machines (VMs) with Jenkins to execute build tasks. GCE VMs provision quickly, are destroyed by Jenkins when idle, and offer Preemptible VMs that run at a much lower price than regular VMs.

## Documentation
Please see the [Google Compute Engine Plugin](https://wiki.jenkins.io/display/JENKINS/Google+Compute+Engine+Plugin) wiki for complete documentation.

## Installation
1. View the plugin from [here](https://github.com/KMK-ONLINE/google-compute-engine-plugin/releases). And download the .hpi plugin
1. Go to **Manage Jenkins** then **Manage Plugins**.
1. In the Plugin Manager, click the **Advanced** tab and then **Choose File** under the **Upload Plugin** section.
1. Choose the Jenkins plugin file downloaded in Step 1.
1. Click the **Upload** button.
1. Actually it need to restart jenkins master after install

## How to Compile + Running Test
mvn clean package
