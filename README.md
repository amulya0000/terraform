                                                        TERRAFORM NOTES

•	Terraform is an open-source infrastructure as code software tool created by HashiCorp. In simple terms, it allows you to define and manage your infrastructure as code, meaning you can write code to describe the infrastructure you want (like servers, databases, and networking components) and then use that code to automatically create and manage those resources in a consistent and repeatable way. This makes it easier to provision and manage infrastructure compared to manually setting up and configuring each component.  

•	Infrastructure as Code (IaC) is a method of managing and building computer infrastructures, such as servers, databases, networks, and storage, using code instead of manual procedures. Instead of individually setting up each part of your infrastructure through a user interface, you write code that defines everything you need. Storing this code on platforms like GitHub or GitLab allows for version control and collaboration with others. This approach enables quick and scalable deployments, as well as easy recreation of your infrastructure in case of any problems. By using IaC, you can speed up your application scaling and deployment processes significantly.  





	Terraform has gained popularity due to several reasons:

•	Declarative Configuration: Terraform allows users to define their infrastructure in a declarative configuration language, making it easier to understand and maintain compared to procedural scripts.

•	Multi-Cloud Support: It supports multiple cloud providers such as AWS, Azure, Google Cloud, and others, enabling users to manage diverse infrastructures using a single tool.

•	Infrastructure as Code (IaC): Terraform follows the IaC paradigm, allowing users to manage and provision infrastructure in a predictable and repeatable manner. This reduces manual errors and ensures consistency.

•	Module Reusability: Terraform's modular approach allows users to create reusable infrastructure components, promoting code reusability and maintainability.

•	Community and Ecosystem: Terraform has a large and active community, offering extensive documentation, modules, and support, making it easier for users to get started and address challenges.

•	Integration and Extensibility: It integrates well with other tools and has a robust plugin system, enabling users to extend its functionality to meet their specific requirements.

•	These factors contribute to Terraform's popularity as a versatile and efficient infrastructure provisioning tool.  


What are providers in terraform?

1. Providers: Providers in Terraform are plugins that interface with different infrastructure platforms. They allow you to define and manage resources within those platforms using Terraform. You can configure providers in your Terraform code to specify the authentication details, regions, and other settings specific to the platform you are working with.

What are Resources in Terraform?

1. Resources: Resources in Terraform represent the infrastructure objects you want to manage. They are defined using resource blocks and specify the desired state of the resource and its configuration. Each resource type has its own set of attributes that define the properties, settings, and relationships of the resource. When you apply your Terraform configuration, Terraform compares the desired state with the current state of the resources and takes actions to create, update, or delete resources as needed.

By understanding providers and resources, you can effectively leverage Terraform to provision and manage infrastructure resources across different platforms, following the infrastructure as code approach.

LOCAL VARIABLES:
1.  Local variables are declared using "locals" block
2.  Local variables are accessible within themodule/configuration where they are declared

 In Terraform, input variables are used to define parameters that can be customized when running Terraform modules or configurations. These variables allow users to input values at runtime, enabling flexibility and customization.

1. **Customization**: Input variables enable users to customize the behavior of their Terraform modules or configurations by providing values at runtime.
  
2. **Flexibility**: They provide flexibility by allowing users to input different values for variables, such as IP addresses, instance sizes, or resource names, without modifying the core infrastructure code.
Variable block attributes:

Attributes Of Variables:
 1. **Name**: The identifier used to reference the variable.
2. **Type**: The kind of data the variable can hold (e.g., integer, string, boolean).
3. **Value**: The actual data stored in the variable.
4. **Scope**: The part of the program where the variable can be accessed.
5. **Lifetime**: The duration for which the variable holds its value.
6. **Accessibility**: The rules governing the visibility and availability of the variable to other parts of the program.
7. **Mutability**: Whether the value of the variable can be changed after it's initially set.
       
