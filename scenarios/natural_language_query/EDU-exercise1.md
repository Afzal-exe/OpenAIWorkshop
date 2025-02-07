# Exercise 1: Getting Started with Azure OpenAI

In this exercise, you will create a deployment and model in Azure OpenAI studio which you will be using in further exercises.

## Lab Objectives

- Task 1: Deploy Azure OpenAI Model
   
### Task 1: Deploy Azure OpenAI Model

1. In the **Azure portal**, search for **OpenAI** and select **Azure OpenAI**.

   ![](images/OpenAI-search1.png)

1. On **Azure AI Services | Azure OpenAI** blade, select **openai-<inject key="DeploymentID" enableCopy="false"/>**

   ![](images/OpenAI-service.png)

1. In the Azure OpenAI resource pane, click on **Go to Azure AI Foundry portal** it will navigate to **Azure AI Foundry | Azure OpenAI Service**.

   ![](images/EDU1.png)

1. In the **Azure AI Foundry**, select **Deployments** under Management and verify that two models with the corresponding **Deployment names** of **gptmodel** and **demomodel** are present and the capacity of the model is set to **15K TPM**.

   ![](images/OpenAI-deployments.png)

1. Naviagte back to [Azure portal](http://portal.azure.com/), search and select **Azure OpenAI**, from the **Azure AI Services | Azure OpenAI pane**, select the **OpenAI-<inject key="Deployment ID" enableCopy="false"/>**.

1. On **openai-<inject key="DeploymentID" enableCopy="false"/>** blade, select **Keys and Endpoint (1)** under **Resource Management**. Select **Show Keys (2)** Copy **Key 1 (3)** and the **Endpoint (4)** by clicking on copy to clipboard and paste it into a text editor such as Notepad for later use. 

   ![](images/openaikeys1new.png)

## Summary

In this exercise, you explored about a model and deployment in OpenAI Foundry to get started with OpenAI resource. You will be using the copied Key and Endpoint to get hands-on experience with Azure OpenAI Playground in further exercises.

### You have successfully completed the lab!
