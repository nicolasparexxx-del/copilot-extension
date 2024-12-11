<h1 align="center">
  <a href="https://github.com/apps/arm">
    <img height=350 alt="Arm GitHub Copilot Extension - Banner" src="https://capsule-render.vercel.app/api?type=waving&height=300&color=0:0091bd,100:002b49&text=Arm%20GitHub%20Copilot%20extension&section=header&fontSize=50&fontColor=FFF&animation=fadeIn&stroke=FCFCFC&strokeWidth=1&desc=Designed%20to%20help%20cloud%20software%20developers%20%20%20%20%20%20%20%20%20build%20better%20code%20on%20Arm%20servers,%20faster.&descSize=20"></img></a>
  </a>
</h1>
<p align="center">
  This repository enables feedback and communication about the <strong>Arm GitHub Copilot</strong> extension. It is actively updated and easy to get started.
</p>


<p align="center">
<a href="#introduction">Introduction</a> &nbsp;&bull;&nbsp;
<a href="#installation">Installation</a> &nbsp;&bull;&nbsp;
<a href="#why-use-arm-is-it-different-than-standard-github-copilot">Value</a> &nbsp;&bull;&nbsp;
<a href="#what-can-i-use-arm-for">Example Usage</a> &nbsp;&bull;&nbsp;  
<a href="#additional-information">Additional Information</a>
</p>



# Introduction
<div align="center">
<img src="https://github.com/user-attachments/assets/e53dfccc-492b-4f72-b6c3-e014440f63e4" alt="Example use-cases">
</div>


The Arm extension provides tips, best-practice, and code examples to develop better code on Arm-based servers. All Arm-cloud developers, from beginners to experts, can benefit from using this integration. Obtain expert advice for developing on these servers and beyond:
- AWS Graviton
- GCP Axion
- Azure Cobolt
- Oracle AmpereOne


## Installation
It is free and easy to start. Make sure you (1) have a GitHub Copilot license, (2) install the Arm extension from the GitHub Marketplace, and (3) call `@arm` from your GitHub Copilot chat on GitHub or your favorite code editor. The first time you call `@arm` you will have to authorize the extension by clicking through a few screens. Then start using `@arm` as much as you'd like.

  
## Why use @arm? Is it different than standard GitHub Copilot?
Our extension adds Arm-specific depth to GitHub Copilot in two primary ways. First, by ensuring responses are specific to the Arm-architecture. Calling `@arm` will ensure any tips, best-practice, and code snippets have the Arm architecture in mind. Default Copilot responses may provide information not-applicable to Arm-based cloud development.

Second, by ensuring responses consist of the most relevant and up-to-date information in an ever-evolving industry. The `@arm` extension is built on a constantly updated RAG database of high-quality source material containing the most recent best-practices & code examples for Arm servers. Default Copilot responses may not reference the most up-to-date information possible.


## What can I use @arm for?
The current scope for the `@arm` extension is to assist Arm-based cloud developers in three specific areas: Migration, Optimization, and CI/CD pipelines. It also handles basic coding advice for Arm-based servers.


### Migration
Port your project to the Arm architecture faster by asking about general best-practices, software compatibility, even how to migrate intrinsics to Arm. Examples:
```
@arm What is the best methodology for me to migrate my web service to Azure?
```
```
@arm Does Hyperscan and Snort3 work on Graviton4? What versions should I use?
```
```
@arm What is the Arm equivalent of the _mm_add_epi8 intrinsic?
```

### Optimization
Get the best price performance for your project by asking about general best-practices, application-level tips, and how to take advantage of specific Arm architecture features. Examples:
```
@arm Explain how to optimize my app's performance with BOLT?
```
```
@arm Help me improve memory alignment in my C data structures.
```
```
@arm How do I check if my Arm server supports LSE? I want to leverage it for my Rust app.
```

### CI/CD
Learn to create an end-to-end tested & supported Arm-based project by asking about general best-practices, container management, and your specific pipeline setup. Examples:
```
@arm How should I set up a multi-architecture CI pipeline in GitHub Actions?
```
```
@arm How do I build multi-architecture Docker images?
```
```
@arm How can I automate the deployment of an Arm virtual machine on GCP with Terraform?
```

### Getting Started on Arm servers
Get straightforward, simple approaches to building the best apps on Arm servers starting from the basics. Example:
```
@arm I am trying to compile C++ code for the Arm architecture. Which compiler should I use?
```


-----

## Additional Information

### What information do you store?
We think transparency is essential when it comes to AI products. Our `@arm` extension respects your privacy. We do not sell your data to third parties. We do log conversations for the purposes of product improvement only, with all Personally Identifiable Information (such as your GitHub username) removed. For more details view our privacy policy and EULA. 


### The future of the @arm extension
We continue to update and expand the scope of the `@arm` GitHub Copilot extension. Any updates will be communicated here in this repository. If you have thoughts about what `@arm` should help with, any data sources `@arm` should be prioritizing, or otherwise please file an issue on the @arm Issue Tracker. Your feedback is appreciated, and helps us shape the future of this extension and beyond!


### Learn more about the Arm Developer ecosystem
- Join the [Arm Developer Program](https://www.arm.com/resources/developer-program) to talk other like-minded developers and Arm Experts about software development.

<img src="https://github.com/user-attachments/assets/815df7e8-8b2d-4430-9b7b-3621fc5eb9e0" alt="Arm Copilot Extension">
