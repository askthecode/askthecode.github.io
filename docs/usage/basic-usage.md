---
label: Basic Usage
icon: "file"
order: 100
---

# Basic Usage

!!!warning Warning
The screenshots provided in this guide are based on an older version of the AskTheCode plugin. The actual response from the plugin might differ (and hopefully be better) in the latest versions.
!!!

The AskTheCode plugin is designed to assist developers in analyzing GitHub repositories. By integrating with ChatGPT, users can ask questions directly related to the content and structure of a given repository. This documentation will guide you through the basic usage of the plugin.

---

## Prerequisites

- A GitHub repository URL you wish to analyze.
- AskTheCode plugin installed

---

## Steps for Basic Usage

1. **Provide the Repository Link:**  
   Start by providing the GitHub repository URL to the AskTheCode plugin.

2. **Ask Questions:**  
   With the repository URL provided, you can now ask specific questions related to the repository. For instance, if you want to know about the purpose or details of a particular project, simply ask.

3. **Interact and Analyze:**  
   Based on the responses from the plugin, you can continue to interact with ChatGPT to get deeper insights, explanations, or even code suggestions related to the repository.

---

## Sample: LangChain

If you're curious about a particular GitHub repository and want to get general information or insights, the AskTheCode plugin can be invaluable. Let's take the "LangChain" repository as an example.

**Input the following prompt:**  

```prompt
https://github.com/langchain-ai/langchain  
What is LangChain?
```

In a barebone ChatGPT, without any plugins, it might not know anything about "LangChain".

![](/resources/usage/basic-usage/no-plugin-installed.png)

However, with the AskTheCode plugin, ChatGPT can directly fetch and analyze the information from the provided GitHub repository and answer the question.

![](/resources/usage/basic-usage/plugin-installed.png)

---

## Tips

- Ensure that the repository URL is correct and accessible.
- Be specific in your questions to get more accurate and relevant answers.
- Familiarize yourself with the repository's structure to ask more targeted questions.

---

## Step-by-Step Guide

To help you get started with the AskTheCode plugin, here is a step-by-step guide on how to use it effectively:

### Step 1: Install the Plugin

1. **Visit the Plugin Store**  
   Navigate to the Plugin Store in your ChatGPT interface.
   ![](/resources/getting-started/installation/open-plugin-store.png)

2. **Search for AskTheCode**  
   In the Plugin Store, search for the "AskTheCode" plugin.
   ![](/resources/getting-started/installation/search-for-plugin.png)

3. **Install the Plugin**  
   Click on the "Install" button to add the AskTheCode plugin to your ChatGPT.

### Step 2: Authenticate with AskTheCode

After installing the plugin, you need to authenticate to start using it. There are two authentication methods available:

#### Passwordless Login via Email

1. **Select Passwordless Login**  
   Choose the passwordless login option when prompted.
   
2. **Enter Your Email**  
   Provide your email address to receive a login link.
   
3. **Check Your Email**  
   Open the email from AskTheCode and click on the login link to authenticate.

#### GitHub OAuth Authentication

1. **Select GitHub OAuth**  
   Choose the GitHub OAuth authentication method when prompted.
   
2. **Authorize AskTheCode**  
   You will be redirected to GitHub to authorize the AskTheCode plugin. Click "Authorize" to grant access.
   
3. **Complete Authentication**  
   After authorizing, you will be redirected back to ChatGPT, and the plugin will be connected to your GitHub account.

### Step 3: Start Using AskTheCode

Once authenticated, you can start using the AskTheCode plugin to interact with your GitHub repositories. Simply provide the repository URL and ask questions or request actions related to the repository.

### Sample Prompts and Expected Responses

Here are some sample prompts and the expected responses when using the AskTheCode plugin:

#### Sample Prompt 1: Repository Overview

**Prompt:**  
```prompt
https://github.com/langchain-ai/langchain  
Can you provide an overview of this repository?
```

**Expected Response:**  
The AskTheCode plugin will fetch and analyze the repository, providing a detailed overview of its purpose, key features, and main components.

#### Sample Prompt 2: File Content

**Prompt:**  
```prompt
https://github.com/langchain-ai/langchain  
Can you show me the content of the README.md file?
```

**Expected Response:**  
The AskTheCode plugin will retrieve the content of the README.md file from the specified repository and display it in the chat.

#### Sample Prompt 3: Branch Management

**Prompt:**  
```prompt
https://github.com/langchain-ai/langchain  
Can you list all the branches in this repository?
```

**Expected Response:**  
The AskTheCode plugin will list all the branches available in the specified repository.

#### Sample Prompt 4: Commit History

**Prompt:**  
```prompt
https://github.com/langchain-ai/langchain  
Can you show me the commit history for the main branch?
```

**Expected Response:**  
The AskTheCode plugin will retrieve and display the commit history for the main branch of the specified repository.

---

By following this step-by-step guide and using the sample prompts, you can effectively utilize the AskTheCode plugin to analyze and interact with your GitHub repositories. Happy coding!
