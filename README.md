# oci-openproject

This is Terraform module that deploys OpenSource on Oracle Cloud Infrastructure (OCI).

# About

Deploy an open-source project management software solution to enable your teams to collaborate effectively, while leveraging the infrastructure benefits of Oracle Cloud Infrastructure (OCI).

The OpenProject Community edition is the leading open-source project management software that provides regular updates and new releases for free, released under the GNU General Public License. OpenProject is a powerful open-source project management software that offers several advantages, including:

* Collaboration: OpenProject allows teams to collaborate effectively on projects by providing a centralized platform where they can share information, track progress, and work together on tasks.
* Customization: OpenProject is highly customizable and can be tailored to suit the needs of individual teams or organizations. Users can choose from a range of plugins and add-ons to enhance the functionality of the software.
* Transparency: OpenProject offers transparency by providing real-time updates on the status of projects, including progress, deadlines, and budget. This makes it easy for project managers to stay on top of their projects and make informed decisions.
* Integration: OpenProject integrates seamlessly with other tools and services, such as GitHub, Slack, and Google Drive. This enables teams to work more efficiently and reduces the need for manual data entry.
* Security: OpenProject offers robust security features, including role-based access control and encryption. This ensures that sensitive data is protected from unauthorized access.

# Architecture

You can deploy OpenProject in a single-node configuration, or as part of a multi-node, highly-available configuration. The Terraform code found in GitHub is compatible with both single-node and multi-node configurations. For a production-grade, highly-available architecture, refer to the following diagram, which illustrates a multi-node scenario.

[![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg)](https://cloud.oracle.com/resourcemanager/stacks/create?zipUrl=[https://github.com/raphaelsteixeira/oci-openproject/archive/refs/heads/main.zip](https://github.com/raphaelsteixeira/oci-openproject/archive/refs/heads/main.zip))
