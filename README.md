# Pushed images to ACR with different tags and then deleted images from a specific repository.

## Prerequisites for the Pipeline:
1. Create a VM (Windows or Ubuntu)
   
2. Configure the agent.
   
3. Install Docker and Azure CLI on the VM.
   
4. Set up an ACR (Azure Container Registry) connection for Docker.

5.Assign the AcrPush and AcrDelete roles to the agent (VM) in Azure Container Registry (ACR)."

       AcrPush: This role allows pushing images to the registry.
       AcrDelete: This role allows deleting images from the registry.
   
6. Set up a service connection for Azure CLI to delete Docker images from the ACR repository.
