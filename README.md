How to deploy your own app by using Harness
You can integrate your own microservice application into this tutorial by following the steps outlined below:

Utilize the same delegate that you deployed as part of this tutorial. Alternatively, deploy a new delegate, but remember to use a newly created delegate identifier when creating connectors.

If you intend to use a private Git repository that hosts your Kustomize files, create a Harness secret containing the Git personal access token (PAT). Subsequently, create a new Git connector using this secret.

Create a Kubernetes connector if you plan to deploy your applications in a new Kubernetes environment. Make sure to update the infrastructure definition to reference this newly created Kubernetes connector.

Once you complete all the aforementioned steps, create a new Harness service that leverages Kustomize for deploying applications.

Lastly, establish a new deployment pipeline and select the newly created infrastructure definition and service. Choose a deployment strategy that aligns with your microservice application's deployment needs.
