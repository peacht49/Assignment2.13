# Assignment2.13 


Serverless Framework vs Terraform

1. What type of infrastructure and application deployments are each tool best suited for?
Event driven architectures are best used with serverless framework as they scale with demand and thus more cost effective. 
For use cases that require granular control on infrastructure management or management of multi-cloud infrastructure, terraform can be used as well as provide state management for collaboration and versioning

2. How do their primary objectives differ?
Serverless frameworks aims to simplify deployment of applications and make it easier for developers to focus on writing code
Terraform aims to manage full stack infrastructure and also make mutli-cloud deployments easier for a business
3. How do they differ in terms of learning curve and ease of use for developers or DevOps teams?

Learning curve
Developers will have an easier time with serverless frameworks while devops teams might need more as they might manage more cloud platforms
Developers might have a steeper learning curve for terrraform due to a different syntax and underlying infrastructure while devops engineers might find terraform familiar

Ease of use
Terraform might need more time for initial setup and getting used to while serverless has setup pretty much automated

4. What are the differences in how each tool handles state tracking and deployment changes?
Serverless does not manage state of infrastructure as the goal is to abstract complexity and offload management to the cloud infrastructure. Deployment is declarative

Terraform 
Provides state tracking via the state file, deployment changes are often compared via diffs  - infrastructure deployed are often immutable

5. In what scenarios would you recommend using Serverless Framework over Terraform, and vice versa?
Serverless gives a faster deployment, best in an event driven use case or when infrastructure management needs to be minimal.

Terraform allows us to manage full or multi-cloud infrastructure

6. Are there scenarios where using both together might be beneficial?
CI/CD pipeline can include both frameworks or in cases where migration is happening 