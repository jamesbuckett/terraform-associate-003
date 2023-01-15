# [Associate Tutorial List (003)](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003)


<details class="faq box"><summary>[What is Infrastructure as Code with Terraform?](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/infrastructure-as-code)</summary>
<p>
* Learn how infrastructure as code lets you safely build, change, and manage infrastructure. 
* Try Terraform.
</p>
</details>
<br />

<details class="faq box"><summary>[Lock and Upgrade Provider Versions](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/provider-versioning)</summary>
<p>
* Manage your provider versions using the dependency lock file. 
* Use version constraints to filter provider versions compatible with your configuration. Update your lock file to use a new provider version.
</p>
</details>
<br />

<details class="faq box"><summary>[Build Infrastructure](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/aws-build)</summary>
<p>
* Authenticate to AWS and create an EC2 instance under the AWS free tier. 
* Write and validate Terraform configuration, initialize a configuration directory, and plan and apply a configuration to create infrastructure.
</p>
</details>
<br />

<details class="faq box"><summary>[Change Infrastructure](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/aws-change)</summary>
<p>
* Modify EC2-instance configuration to use a different Ubuntu version. 
* Plan and apply the changes to re-provision a new instance that reflects the new configuration. 
* Learn how Terraform handles infrastructure change management.
</p>
</details>
<br />

<details class="faq box"><summary>[Destroy Infrastructure](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/aws-destroy)</summary>
<p>
* Destroy the AWS EC2 instance you created in the previous tutorials. 
* Evaluate the plan and confirm the destruction.
</p>
</details>
<br />

<details class="faq box"><summary>[Store Remote State](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/aws-remote)</summary>
<p>
* Configure Terraform to store state in Terraform Cloud. 
* Add a remote state block directly to configuration or set an environment variable to load remote state configuration when Terraform initializes.
</p>
</details>
<br />

<details class="faq box"><summary>[Initialize Terraform Configuration](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/init)</summary>
<p>
* Learn what Terraform does when you run `terraform init` in a working directory. 
* Initialize the backend, install providers, download modules, and explore the lock file and .terraform directory.
</p>
</details>
<br />

<details class="faq box"><summary>[Create a Terraform Plan](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/plan)</summary>
<p>
* Learn how Terraform constructs an execution plan. 
* Export a plan with the -out flag, review the plan contents, and apply a saved plan.
</p>
</details>
<br />

<details class="faq box"><summary>[Apply Terraform Configuration](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/apply)</summary>
<p>
* Learn how Terraform applies configuration to change your infrastructure. 
* Provision a Docker container, introduce an apply error, note how Terraform handles errors, and perform basic troubleshooting.
</p>
</details>
<br />

<details class="faq box"><summary>[Manage Terraform Versions](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/versions)</summary>
<p>
* Update an existing configuration to work with a newer version of Terraform. 
* Use the required_version setting to pin the Terraform versions for your projects. 
* Manage different versions of Terraform across your team.
</p>
</details>
<br />

<details class="faq box"><summary>[Customize Terraform Configuration with Variables](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/variables)</summary>
<p>
* Customize infrastructure for a web application with Terraform. 
* In this tutorial, you will use Terraform input variables, including lists, maps, strings, and booleans, to make the configuration for your infrastructure more flexible.
</p>
</details>
<br />

<details class="faq box"><summary>[Protect Sensitive Input Variables](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/sensitive-variables)</summary>
<p>
* Protect sensitive values from accidental exposure using Terraform sensitive input variables. Provision a web application with Terraform, and mark input variables as sensitive to restrict when Terraform prints them out to the console.
</p>
</details>
<br />

<details class="faq box"><summary>[Output Data from Terraform](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/outputs)</summary>
<p>
* Output data about infrastructure with Terraform outputs. 
* Provision a web application with Terraform, and use output values to export data about your application's infrastructure. 
* Hide sensitive output values.
</p>
</details>
<br />

<details class="faq box"><summary>[Query Data Sources](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/data-sources)</summary>
<p>
* Use a data source to configure an EC2 instance with an appropriate AMI for the current region. 
* Use a remote state data source to share data between Terraform projects and to support multiple availability zones.
</p>
</details>
<br />

<details class="faq box"><summary>[Create Resource Dependencies](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/dependencies)</summary>
<p>
* Create an implicit dependency between an EC2 instance and its Elastic IP using variable interpolation. 
* Create explicit dependencies on an S3 Bucket and SQS Queue with depends_on. 
* Learn how Terraform creates independent resources in parallel.
</p>
</details>
<br />

<details class="faq box"><summary>[Perform Dynamic Operations with Functions](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/functions)</summary>
<p>
* Use templatefile and lookup functions to generate dynamic user data for an EC2 instance and find a region-specific AMI.
</p>
</details>
<br />

<details class="faq box"><summary>[Create Dynamic Expressions](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/expressions)</summary>
<p>
* Make your Terraform configurations more dynamic and reusable with expressions. 
* Use locals to assign expressions to variables for reuse, conditionals to declare if/then scenarios, and the splat expression to return attributes from complex value types.
</p>
</details>
<br />

<details class="faq box"><summary>[Modules Overview](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/module)</summary>
<p>
* Read about how Terraform modules make configuration easier to organize, understand, reuse, and share. 
* Learn about the directory structure of a module, and how to call them.
</p>
</details>
<br />

<details class="faq box"><summary>[Use Registry Modules in Configuration](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/module-use)</summary>
<p>
* Use modules from the public Terraform Registry to define an Amazon VPC containing two EC2 instances. 
* Select module and root input and output variables, install the modules, and apply the configuration.
</p>
</details>
<br />

<details class="faq box"><summary>[Build and Use a Local Module](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/module-create)</summary>
<p>
* Write a local module to create an Amazon S3 bucket hosting a static website. 
* Create a module directory, write the module configuration, variables, and outputs, and call the module from a root configuration.
</p>
</details>
<br />

<details class="faq box"><summary>[Refactor Monolithic Terraform Configuration](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/organize-configuration)</summary>
<p>
* Deploy development and production versions of an S3-hosted static website. 
* Separate their configuration into files, directories, and workspaces, and explore the architectural trade-offs of each approach.
</p>
</details>
<br />

<details class="faq box"><summary>[Module Creation - Recommended Pattern](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/pattern-module-creation)</summary>
<p>
* Learn the architectural recommendations for module creation distilled from engagements with large enterprises using Terraform. 
* Use Terraform module best practices to scope, build, improve and consume Terraform modules.
</p>
</details>
<br />

<details class="faq box"><summary>[Manage Resources in Terraform State](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/state-cli)</summary>
<p>
* Create an EC2 instance and security group, and move a resource to another state file. 
* Remove, replace, and re-import resources to manage state and reconcile drift in your infrastructure.
</p>
</details>
<br />

<details class="faq box"><summary>[Import Terraform Configuration](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/state-import)</summary>
<p>
* Import existing infrastructure into Terraform. 
* In this tutorial, you will use Terraform import to manage an existing Docker container and learn important considerations to keep in mind when importing infrastructure into Terraform.
</p>
</details>
<br />

<details class="faq box"><summary>[Target Resources](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/resource-targeting)</summary>
<p>
* Apply changes to an AWS S3 bucket and bucket objects using resource targeting. 
* Target individual resources, modules, and collections of resources to change or destroy. 
* Explore how Terraform handles upstream and downstream dependencies.
</p>
</details>
<br />

<details class="faq box"><summary>[Manage Resource Drift](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/resource-drift)</summary>
<p>
* Create an AWS instance and security group. 
* Manually change the instance to create drift in your Terraform state file. 
* Reconcile your state drift and import your resources while avoiding downtime.
</p>
</details>
<br />

<details class="faq box"><summary>[Use Refresh-Only Mode to Sync Terraform State](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/refresh)</summary>
<p>
* Use refresh-only plans and applies to update Terraform state to match real-world infrastructure. 
* Understand the implicit refresh behavior in Terraform plan and apply operations.
</p>
</details>
<br />

<details class="faq box"><summary>[Troubleshoot Terraform](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/troubleshooting-workflow)</summary>
<p>
* Interpret and fix a Terraform configuration with common configuration language errors and deploy an EC2 instance with security groups in AWS. 
* Learn best practices for logging application errors and reporting bugs.
</p>
</details>
<br />

<details class="faq box"><summary>[Inject Secrets into Terraform Using the Vault Provider](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/secrets-vault)</summary>
<p>
* Configure the AWS Secrets Engine to manage IAM credentials in Vault through Terraform. 
* Then use the short-lived, Vault-generated, dynamic secrets to provision EC2 instances.
</p>
</details>
<br />

<details class="faq box"><summary>[Log in to Terraform Cloud from the CLI](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-login)</summary>
<p>
* Log into Terraform Cloud or Enterprise with the Terraform CLI to migrate state, trigger remote runs, and interact with Terraform Cloud.
</p>
</details>
<br />

<details class="faq box"><summary>[Migrate State to Terraform Cloud](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-migrate)</summary>
<p>
* Migrate a state file to Terraform Cloud for secure storage and easy collaboration.
</p>
</details>
<br />

<details class="faq box"><summary>[What is Terraform Cloud - Intro and Sign Up](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-sign-up)</summary>
<p>
* Sign up for Terraform Cloud, which provides free remote state storage, a stable run environment, version control system (VCS) driven plans and applies, a collaborative web GUI, and more. Create your first organization.
</p>
</details>
<br />

<details class="faq box"><summary>[Create a Credentials Variable Set](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-create-variable-set)</summary>
<p>
* Create a variable set for your AWS IAM credentials that you can reuse across workspaces. 
* Apply the variable set to a workspace.
</p>
</details>
<br />

<details class="faq box"><summary>[Create a Workspace](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-workspace-create)</summary>
<p>
* Create a CLI-driven Terraform Cloud workspace. Update configuration to enable integration with Terraform Cloud.
</p>
</details>
<br />

<details class="faq box"><summary>[Create Infrastructure](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-workspace-configure)</summary>
<p>
* Set EC2 instance attributes using Terraform Cloud workspace variables. 
* Create the instance by planning and applying a run in Terraform Cloud.
</p>
</details>
<br />

<details class="faq box"><summary>[Change Infrastructure](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-change)</summary>
<p>
* Use command line input variables to modify infrastructure managed by Terraform Cloud. 
* Review workspace contents and interface.
</p>
</details>
<br />

<details class="faq box"><summary>[Use VCS-Driven Workflow](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-vcs-change)</summary>
<p>
* Update a workspace to use the version control system-driven workflow with GitHub. 
* Queue a speculative plan by opening a pull request.
</p>
</details>
<br />

<details class="faq box"><summary>[Destroy Resources and Workspaces](https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/cloud-destroy)</summary>
<p>
* Destroy the resources in a Terraform Cloud workspace, and delete the workspace via the web UI.
</p>
</details>
<br />

*End of Section*
