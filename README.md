# System name - SmartPath

![SmartPath Logo](./images/logo.png)

Members - Alexander Brenes, Franco Rojas, Jeremmy Aguilar and Randy Baeza Ramírez


## Description:
SmartPath is an innovative AI-driven assistant that revolutionizes employee training and real-time assistance by capturing, replicating, and guiding users through complex workflows in any application. By recording voice commands and on-screen actions, SmartPath builds a dynamic knowledge base, enabling real-time, step-by-step assistance, whether adding a bank account, canceling a subscription, or navigating enterprise software like SAP.

**Key Strengths:**

- **Voice and Action-Based Recording:** Users can easily capture workflows using voice commands and on-screen actions.

- **AI-Powered Knowledge Base:** Converts recordings into step-by-step guides that the system can learn, replicate, and explain.

- **Real-Time Assistance:** Detects when a user needs help and offers instant, contextual guidance within the app they're using.

- **Cross-Platform Compatibility:** Works on Windows, macOS, iOS, Android, and major browsers (Chrome, Firefox, Safari). Integrates with 3rd-party apps (banks, ERPs, Netflix, SAP, etc.).

## Stack: write down the final stack to be use decided for the group

## Frontend design specifications

### Authentication platform - Amazon Cognito

We chose **Amazon Cognito** as our authentication platform because it seamlessly integrates with our existing AWS infrastructure while meeting all our requirements. Amazon Cognito is compatible with our frontend in React and ensures quick implementation, including pre-built and customizable login screens. The platform fully covers our needs: email/password authentication, API access for backend integration, multi-factor authentication (MFA), and a sandbox environment for testing.

We've implemented the following login screens using Amazon Cognito to demonstrate the potential UI for our final application.

**Login screen to enter username**
![Login](./images/login.png)

**Login screen to enter password**
![Login - password](./images/loginPassword.png)

**Sign up screen**
![SignUp](./images/SignUp.png)

**MFA screen**
![MFA](./images/mfa.png)

<br>

The login screens were fully customized via AWS Console, using Cognito's built-in UI customization options like those shown in the following image.

![Customization Cognito](./images/customizationCognito.png)
