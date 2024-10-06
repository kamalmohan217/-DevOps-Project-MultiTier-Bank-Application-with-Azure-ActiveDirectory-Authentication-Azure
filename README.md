# DevOps-Project-MultiTier-Bank-Application-with-Azure-ActiveDirectory-Authentication-Azure

Architecture diagram for the project is as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/bed90419-1c25-44d4-8c65-f824aa9e8ff4)

In this project for Authentication of Azure DevOps Pipeline, SonarQube and Azure Artifact Feed I have used Azure Active Directory (Azure AD) as shown in the screenshots attached nelow.

Connect your Azure DevOps Organisation with Azure Entra as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/3e677023-e920-4677-a887-31112c8f663a)

To integrate SonarQube with Azure Active Directory (Azure Entra ID) follow the steps as shown in the screenshot attached below.

Install the plugin for Azure Active Directory in SonarQube as shown in the screenshot shown below.

![image](https://github.com/user-attachments/assets/0e49f7a8-de4f-4d72-b7ed-945450fafaa1)
![image](https://github.com/user-attachments/assets/536a85ff-6bd9-403a-ab5f-9711d9fd4a9b)

Create App Registration as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/9ce23c33-0e56-48a9-a181-e6554a1a78c6)
![image](https://github.com/user-attachments/assets/42cd0ff9-9c01-4eeb-90fa-919ae9191ae1)
![image](https://github.com/user-attachments/assets/dff4e0b9-e9db-44fe-9fc7-f72822060db7)

Configure Server Base URL as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/b095f7a9-5d6a-4d5f-930b-a143ad7ac87a)

Further configuration in SonarQube plugin for Azure Active Directory as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/3e052df9-6dce-431f-8dc7-0fb68198adfb)
![image](https://github.com/user-attachments/assets/dddbef51-330e-4dee-999a-b303778c0fd4)
![image](https://github.com/user-attachments/assets/1941d703-5639-45a4-81e2-37dbfacc235c)

Finally we can Access the SonarQube as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/399b1c4a-45ca-4cff-a47b-ebdc77393269)
![image](https://github.com/user-attachments/assets/e4f24821-984c-4f66-b61f-abf078445255)

Provided Administrative privilege as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/60371973-2e1d-43f9-abb9-e3ad6fb12b7f)
![image](https://github.com/user-attachments/assets/082d51f5-6b95-4afb-ba5c-e1fd5c349035)

Integrate Azure Artifact Feed with Azure Entra ID as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/a7ce6cd0-9737-4e85-a081-f2eb293868c6)



```
The bankapp-auth secrets for kubernetes can be created using the command below

kubectl create secret docker-registry bankapp-auth --docker-server=https://bankappcontainer24registry.azurecr.io --docker-username=bankappcontainer24registry --docker-password=qXXXXXXXXXXXXXXXXrCHXXXXXXXXXXXXXXXXV0zXXXXXXXXXXXX7 -n bankapp
```
<br><br/>
<br><br/>
```
OpenJDK Docker Image is depricated so in this project eclipse-temurin docker image has been used as a base image in the Dockerfile. 
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Source Code:-  https://github.com/kamalmohan217/Bank-App.git
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://github.com/Goldencat98/Bank-App.git
```
