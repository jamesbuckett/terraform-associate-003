# [Associate Tutorial List (003)](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003)


<details class="faq box"><summary>What is Infrastructure as Code with Terraform?</summary>
<p>

[What is Infrastructure as Code with Terraform?](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/infrastructure-as-code)
* Learn how infrastructure as code lets you safely build, change, and manage infrastructure. 
* Try Terraform.

</p>
</details>
<br />

<details class="faq box"><summary>Lock and Upgrade Provider Versions</summary>
<p>

[Lock and Upgrade Provider]
* Manage your provider versions using the dependency lock file. 
* Use version constraints to filter provider versions compatible with your configuration. Update your lock file to use a new provider version.

</p>
</details>
<br />

<details class="faq box"><summary>Build Infrastructure</summary>
<p>

[Build Infrastructure]
* Authenticate to AWS and create an EC2 instance under the AWS free tier. 
* Write and validate Terraform configuration, initialize a configuration directory, and plan and apply a configuration to create infrastructure.

</p>
</details>
<br />

<details class="faq box"><summary>Change Infrastructure</summary>
<p>

[Change Infrastructure]
* Modify EC2-instance configuration to use a different Ubuntu version. 
* Plan and apply the changes to re-provision a new instance that reflects the new configuration. 
* Learn how Terraform handles infrastructure change management.

</p>
</details>
<br />

<details class="faq box"><summary>Destroy Infrastructure</summary>
<p>

[Destroy Infrastructure]
* Destroy the AWS EC2 instance you created in the previous tutorials. 
* Evaluate the plan and confirm the destruction.

</p>
</details>
<br />

<details class="faq box"><summary>Store Remote State</summary>
<p>

[Store Remote State]
* Configure Terraform to store state in Terraform Cloud. 
* Add a remote state block directly to configuration or set an environment variable to load remote state configuration when Terraform initializes.

</p>
</details>
<br />

<details class="faq box"><summary>Initialize Terraform Configuration</summary>
<p>

[Initialize Terraform Configuration]
* Learn what Terraform does when you run `terraform init` in a working directory. 
* Initialize the backend, install providers, download modules, and explore the lock file and .terraform directory.

</p>
</details>
<br />

<details class="faq box"><summary>Create a Terraform Plan</summary>
<p>

[Create a Terraform Plan]
* Learn how Terraform constructs an execution plan. 
* Export a plan with the -out flag, review the plan contents, and apply a saved plan.

</p>
</details>
<br />

<details class="faq box"><summary>Apply Terraform Configuration</summary>
<p>

[Apply Terraform Configuration]
* Learn how Terraform applies configuration to change your infrastructure. 
* Provision a Docker container, introduce an apply error, note how Terraform handles errors, and perform basic troubleshooting.

</p>
</details>
<br />

<details class="faq box"><summary>Manage Terraform Versions</summary>
<p>

[Manage Terraform Versions]
* Update an existing configuration to work with a newer version of Terraform. 
* Use the required_version setting to pin the Terraform versions for your projects. 
* Manage different versions of Terraform across your team.

</p>
</details>
<br />

<details class="faq box"><summary>Customize Terraform Configuration with Variables</summary>
<p>

[Customize Terraform Configuration with Variables]
* Customize infrastructure for a web application with Terraform. 
* In this tutorial, you will use Terraform input variables, including lists, maps, strings, and booleans, to make the configuration for your infrastructure more flexible.

</p>
</details>
<br />

<details class="faq box"><summary>Protect Sensitive Input Variables</summary>
<p>

[Protect Sensitive Input Variables]
* Protect sensitive values from accidental exposure using Terraform sensitive input variables. 
* Provision a web application with Terraform, and mark input variables as sensitive to restrict when Terraform prints them out to the console.

</p>
</details>
<br />

<details class="faq box"><summary>Output Data from Terraform</summary>
<p>

[Output Data from Terraform]
* Output data about infrastructure with Terraform outputs. 
* Provision a web application with Terraform, and use output values to export data about your application's infrastructure. 
* Hide sensitive output values.

</p>
</details>
<br />

<details class="faq box"><summary>Query Data Sources</summary>
<p>

[Query Data Sources]
* Use a data source to configure an EC2 instance with an appropriate AMI for the current region. 
* Use a remote state data source to share data between Terraform projects and to support multiple availability zones.

</p>
</details>
<br />

<details class="faq box"><summary>Create Resource Dependencies</summary>
<p>

[Create Resource Dependencies]
* Create an implicit dependency between an EC2 instance and its Elastic IP using variable interpolation. 
* Create explicit dependencies on an S3 Bucket and SQS Queue with depends_on. 
* Learn how Terraform creates independent resources in parallel.

</p>
</details>
<br />

<details class="faq box"><summary>Perform Dynamic Operations with Functions</summary>
<p>

[Perform Dynamic Operations with Functions]
* Use templatefile and lookup functions to generate dynamic user data for an EC2 instance and find a region-specific AMI.

</p>
</details>
<br />

<details class="faq box"><summary>Create Dynamic Expressions</summary>
<p>

[Create Dynamic Expressions]
* Make your Terraform configurations more dynamic and reusable with expressions. 
* Use locals to assign expressions to variables for reuse, conditionals to declare if/then scenarios, and the splat expression to return attributes from complex value types.

</p>
</details>
<br />

<details class="faq box"><summary>Modules Overview</summary>
<p>

[Modules Overview]
* Read about how Terraform modules make configuration easier to organize, understand, reuse, and share. 
* Learn about the directory structure of a module, and how to call them.

</p>
</details>
<br />

<details class="faq box"><summary>Use Registry Modules in Configuration</summary>
<p>

[Use Registry Modules in Configuration]
* Use modules from the public Terraform Registry to define an Amazon VPC containing two EC2 instances. 
* Select module and root input and output variables, install the modules, and apply the configuration.

</p>
</details>
<br />

<details class="faq box"><summary>Build and Use a Local Module</summary>
<p>

[Build and Use a Local Module]
* Write a local module to create an Amazon S3 bucket hosting a static website. 
* Create a module directory, write the module configuration, variables, and outputs, and call the module from a root configuration.

</p>
</details>
<br />

<details class="faq box"><summary>Refactor Monolithic Terraform Configuration</summary>
<p>

[Refactor Monolithic Terraform Configuration]
* Deploy development and production versions of an S3-hosted static website. 
* Separate their configuration into files, directories, and workspaces, and explore the architectural trade-offs of each approach.

</p>
</details>
<br />

<details class="faq box"><summary>Module Creation - Recommended Pattern</summary>
<p>

[Module Creation - Recommended Pattern]
* Learn the architectural recommendations for module creation distilled from engagements with large enterprises using Terraform. 
* Use Terraform module best practices to scope, build, improve and consume Terraform modules.

</p>
</details>
<br />

<details class="faq box"><summary>Manage Resources in Terraform State</summary>
<p>

[Manage Resources in Terraform State]
* Create an EC2 instance and security group, and move a resource to another state file. 
* Remove, replace, and re-import resources to manage state and reconcile drift in your infrastructure.

</p>
</details>
<br />

<details class="faq box"><summary>Import Terraform Configuration</summary>
<p>

[Import Terraform Configuration]
* Import existing infrastructure into Terraform. 
* In this tutorial, you will use Terraform import to manage an existing Docker container and learn important considerations to keep in mind when importing infrastructure into Terraform.

</p>
</details>
<br />

<details class="faq box"><summary>Target Resources</summary>
<p>

[Target Resources]
* Apply changes to an AWS S3 bucket and bucket objects using resource targeting. 
* Target individual resources, modules, and collections of resources to change or destroy. 
* Explore how Terraform handles upstream and downstream dependencies.

</p>
</details>
<br />

<details class="faq box"><summary>Manage Resource Drift</summary>
<p>

[Manage Resource Drift]
* Create an AWS instance and security group. 
* Manually change the instance to create drift in your Terraform state file. 
* Reconcile your state drift and import your resources while avoiding downtime.

</p>
</details>
<br />

<details class="faq box"><summary>Use Refresh-Only Mode to Sync Terraform State</summary>
<p>

[Use Refresh-Only Mode to Sync Terraform State]
* Use refresh-only plans and applies to update Terraform state to match real-world infrastructure. 
* Understand the implicit refresh behavior in Terraform plan and apply operations.

</p>
</details>
<br />

<details class="faq box"><summary>Troubleshoot Terraform</summary>
<p>

[Troubleshoot Terraform]
* Interpret and fix a Terraform configuration with common configuration language errors and deploy an EC2 instance with security groups in AWS. 
* Learn best practices for logging application errors and reporting bugs.

</p>
</details>
<br />

<details class="faq box"><summary>Inject Secrets into Terraform Using the Vault Provider</summary>
<p>

[Inject Secrets into Terraform Using the Vault Provider]
* Configure the AWS Secrets Engine to manage IAM credentials in Vault through Terraform. 
* Then use the short-lived, Vault-generated, dynamic secrets to provision EC2 instances.

</p>
</details>
<br />

<details class="faq box"><summary>Log in to Terraform Cloud from the CLI</summary>
<p>

[Log in to Terraform Cloud from the CLI]
* Log into Terraform Cloud or Enterprise with the Terraform CLI to migrate state, trigger remote runs, and interact with Terraform Cloud.

</p>
</details>
<br />

<details class="faq box"><summary>Migrate State to Terraform Cloud</summary>
<p>

[Migrate State to Terraform Cloud]
* Migrate a state file to Terraform Cloud for secure storage and easy collaboration.

</p>
</details>
<br />

<details class="faq box"><summary>What is Terraform Cloud - Intro and Sign Up</summary>
<p>

[What is Terraform Cloud - Intro and Sign Up]
* Sign up for Terraform Cloud, which provides free remote state storage, a stable run environment, version control system (VCS) driven plans and applies, a collaborative web GUI, and more. 
* Create your first organization.

</p>
</details>
<br />

<details class="faq box"><summary>Create a Credentials Variable Set</summary>
<p>

[Create a Credentials Variable Set]
* Create a variable set for your AWS IAM credentials that you can reuse across workspaces. 
* Apply the variable set to a workspace.

</p>
</details>
<br />

<details class="faq box"><summary>Create a Workspace</summary>
<p>

[Create a Workspace]
* Create a CLI-driven Terraform Cloud workspace. Update configuration to enable integration with Terraform Cloud.

</p>
</details>
<br />

<details class="faq box"><summary>Create Infrastructure</summary>
<p>

[Create Infrastructure]
* Set EC2 instance attributes using Terraform Cloud workspace variables. 
* Create the instance by planning and applying a run in Terraform Cloud.

</p>
</details>
<br />

<details class="faq box"><summary>Change Infrastructure</summary>
<p>

[Change Infrastructure]
* Use command line input variables to modify infrastructure managed by Terraform Cloud. 
* Review workspace contents and interface.

</p>
</details>
<br />

<details class="faq box"><summary>Use VCS-Driven Workflow</summary>
<p>

[Use VCS-Driven Workflow]
* Update a workspace to use the version control system-driven workflow with GitHub. 
* Queue a speculative plan by opening a pull request.

</p>
</details>
<br />

<details class="faq box"><summary>Destroy Resources and Workspaces</summary>
<p>

[Destroy Resources and Workspaces]
* Destroy the resources in a Terraform Cloud workspace, and delete the workspace via the web UI.

</p>
</details>
<br />

*End of Section*
