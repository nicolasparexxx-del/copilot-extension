<h1 align="center">
  <a href="https://github.com/apps/arm">
    <img src="https://github.com/user-attachments/assets/f049b752-0a7e-4fdd-a63e-ed90f8c28f03" alt="Arm Copilot Extension">
  </a>
</h1>
<p align="center">
  This repository enables feedback and communication about the <strong>Arm GitHub Copilot</strong> extension. It is actively updated and easy to get started.
</p>

<p align="center">
<a href="#test">Introduction</a> &nbsp;&bull;&nbsp;
<a href="#test">Installation</a> &nbsp;&bull;&nbsp;
<a href="#test">Usage</a> &nbsp;&bull;&nbsp;
<a href="#test">Documentation</a> &nbsp;&bull;&nbsp;
<a href="#test">Issue?</a>
</p>



# Introduction
The Arm extension provides tips, best-practice, and code examples to develop better code on Arm-based servers. All Arm-cloud developers, from beginners to experts, can benefit from using this integration. Obtain expert advice for developing on these servers and beyond:
- AWS Graviton
- GCP Axion
- Azure Cobolt
- Oracle AmpereOne

## Why use @arm? Is it different than standard GitHub Copilot?
Our extension adds Arm-specific depth to GitHub Copilot in two primary ways. First, by ensuring responses are specific to the Arm-architecture. Calling `@arm` will ensure any tips, best-practice, and code snippets have the Arm architecture in mind. Default Copilot responses may provide information not-applicable to Arm-based cloud development.

Second, by ensuring responses consist of the most relevant and up-to-date information in an ever-evolving industry. The `@arm` extension is built on a constantly updated RAG database of high-quality source material containing the most recent best-practices & code examples for Arm servers. Default Copilot responses may not reference the most up-to-date information possible.

  
## What can I use @arm for?
The current scope for the `@arm` extension is to assist Arm-based cloud developers in three specific areas:
1. **Migration:** Port your project to the Arm architecture faster by asking questions like -
    - General best-practice: `@arm What is the best methodology for me to migrate my web service to Azure?`
    - Software compatibility:  `@arm Does Hyperscan and Snort3 work on Graviton4? What versions should I use?`
    - Intrinsic swapping: `@arm What is the Arm equivalent of the _mm_add_epi8 intrinsic?`   
2. **Optimization:** Get the best price performance for your project by asking questions like -
    - General best-practice: `@arm Explain how to optimize my app's performance with BOLT?`
    - Application-level: `@arm Help me improve memory alignment in my C data structures.`
    - Hardware-level: `@arm How do I check if my Arm server supports LSE? I want to leverage it for my Rust app.`
3. **CI/CD:** Learn to create an end-to-end supported Arm-based project by asking questions like - 
    - General best-practice: `@arm How should I set up a multi-architecture CI pipeline in GitHub Actions?`
    - Container management: `@arm How do I build multi-architecture Docker images?`
    - Specific situations: `@arm How can I automate the deployment of an Arm virtual machine on GCP with Terraform?`


Migration:
```
`@arm What is the best methodology for me to migrate my web service to Azure?
```
```
`@arm Does Hyperscan and Snort3 work on Graviton4? What versions should I use?
```
```
`@arm What is the Arm equivalent of the _mm_add_epi8 intrinsic?
```

Our extension also excels at helping with basic advice, such as `@arm I am trying to compile C++ code for the Arm architecture. Which compiler should I use?`


## How can I get access to @arm? Is it free?
It is free and easy to start. Make sure you (1) have a GitHub Copilot license, (2) install the Arm extension from the GitHub Marketplace, and (3) call `@arm` from your GitHub Copilot chat on GitHub or your favorite code editor. The first time you call `@arm` you will have to authorize the extension by clicking through a few screens. Then start using `@arm` as much as you'd like!

-----


### What information do you store?
We think transparency is essential when it comes to AI products. Our `@arm` extension respects your privacy. We do not sell your data to third parties. We do log conversations for the purposes of product improvement only, with all Personally Identifiable Information (such as your GitHub username) removed. For more details view our privacy policy and EULA. 


### The future of the @arm extension
We continue to update and expand the scope of the `@arm` GitHub Copilot extension. Any updates will be communicated here in this repository. If you have thoughts about what `@arm` should help with, any data sources `@arm` should be prioritizing, or otherwise please file an issue on the @arm Issue Tracker. Your feedback is appreciated, and helps us shape the future of this extension and beyond!

We are excited to see what you build!

### Learn more about the Arm Developer ecosystem
- Join the Arm Developer Program to talk other like-minded developers and Arm Experts about software development. 
