# KCF Cloud Infrastructure Engineer Work Sample
Being a company founded on the values of __Smarts, Grit, and Drive__, it's in our DNA to automate as much as we can and deploy as often as possible in order to allow for rapid development, innovation, and reduce human error. KCF Technologies relies on many internal service for its mainly cloud based infrastructure. Your role on the Development Operations Team will invole:  

* Understanding how all the pieces that comprise the infrastructure fit together
* Knowing how best to maintain and secure that infrastructure
* Automating provisioning, testing, and maintenance as much as possible
* Measuring and monitoring system fitness
* Delivering services that other engineering teams can utilize in support of their development efforts
* Communicating well with the rest of the team and the wider technical community

Please select only one (1) assignment to attempt and solve for the work sample. You do **not** have to complete both solution to be accepted as a candidate. 

# Our Technical Values
We highly value:

* __pragmatic solutions__ with an eye toward future, incremental improvements
* __careful attention__ to detail
* __testing__ before deployment
* __communicating intent__ through code, commits, and documentation

# Assignment #1
The cloud infrastructure team at KCF Technologies is moving towards a more microservice based infrastructure. To that end, we'd like you to deploy the Wheel of Misfortune application using Kubernetes or Nomad. This sample application is used as a tool to teach on-call duties, responsibilities, and training that a cross section of Operations, Reliability, and Software engineers participate in.  

Your task is to use a local (single-node) Kubernetes cluster or dev mode Nomad to deploy the [Wheel of Misfortune](https://github.com/twstewart42/wheel-of-misfortune.git) application via HTTPS.

* Example of the application running: https://wom.sdbuild.kcftech.com/  
* Code for the application: https://github.com/twstewart42/wheel-of-misfortune.git   
* Docker container for the application: `public.ecr.aws/t8l7j5s8/wom`   
* Expected Time: 1-2 hours  

## Deliverables
The final output of your work should include:
* The necessary configurations that enable us to deploy the Wheel of Misfortune served via HTTPS on Kubernetes or Nomad.
* A README that includes:
  * An overview of your solution
  * Instructions for deploying the application to the local Kubernetes cluster or dev mode Nomad
  * Any additional thoughts or considerations on what you would do differently for production use deployment

# Assignment #2
The sample application Wheel of Misfortune is used as a tool to teach on-call duties, responsibilities, and training that a cross section of Operations, Reliability, and Software engineers participate in. Your task is to provide a solution using an Infrastructure as Code tool of your choosing (Terraform, CDK, Pulumi, Cloud Formation, something else) which will deploy the Wheel of Misfortune website onto ANY cloud provider/hosting platform of your choice. 

* Example of the application running: https://wom.sdbuild.kcftech.com/
* Code for the application: https://github.com/twstewart42/wheel-of-misfortune.git
* Expected Time: 1-2 hours
* You do __not__ have to have a live example/spend any money to put together the code that should do this work.
* You do __not__ have to deploy this as a containerized solution within your cloud, all hosting options are available to you.
* It is up to you to provide written justification for the methods and technologies you implement for this solution.

## Deliverables
The final output of your work should include:
* The necessary Infrastructure as Code Configurations that enable us to deploy the Wheel of Misfortune served via HTTPS on a public cloud provider.
* A README that includes:
  * An overview of your IaC solution
  * Instructions for deploying the application to the cloud
  * Any additional thoughts or considerations on what you would do differently for production use deployment
  * Include the solution within the original project bundle as seen in the "Solution Format" section.

# Solution Format  
Please do not post your solution to public Git repositories like GitHub or Gitlab. Instead please work locally:

1. `mkdir solution && cd solution`
2. `git init`
3. `touch README.md`
4. `git commit -m "Initial commit"`
5. < ...hack, hack, hack... >
6. `cd ..` && `tar czf solution.tgz solution`

Your commits should clearly communicate your intent and choices made while completing the task. 

Please reply to the work sample assignment email with your attached solution and if you have any questions pertaining to this assignment.  
