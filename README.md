# Arm Copilot Extension

Welcome to the Arm extension to GitHub Copilot. The goal of this tool is to make it faster for anyone to develop better code on Arm-based servers. Wheather you're a seasoned cloud architect or a beginner to the Arm architecture, developing on AWS Graviton, GCP Axion, Azure Cobolt, or Oracle AmpereOne, asking `@arm` will make your coding easier.

## How is @arm different than standard GitHub Copilot?
First, by ensuring responses are specific to the Arm-architecture. Calling `@arm` will ensure any tips, best-practice, and code snippets have the Arm architecture in mind. Default Copilot responses may provide information not-applicable to Arm-based cloud development.

Second, by ensuring responses consist of the most relevent and up-to-date information in an ever-evolving industry. The `@arm` extension is built on a constantly updated RAG database of high-quality source material containing the most recent best-practices & code examples for Arm servers. Default Copilot responses may not reference the most up-to-date information possible.

  
## What can I use @arm for?
The current scope for the `@arm` extension is to assist Arm-based cloud developers in three specific areas:
1. **Migration:**
    - Intrinsic-porting questions: `@arm What is the Arm equivalent of the _mm_add_epi8 intrinsic?`
    - Compatibility checking:  `@arm Does Hyperscan and Snort3 work on Graviton4? What versions should I use?`
    - General best-practice advice: `@arm What is the best methodology for me to migrate my web service to Azure?`
3. **Optimizaiton:**
    - General best-practice advice: `@arm Explain how to optimize my app's performance with BOLT?`
    - App-level advice: `@arm Help me improve memory alignment in my C data structures.`
    - Hardware-level optimizations: `@arm How do I check if my Arm server supports LSE? I want to leverage it for my Rust app.`
4. **CI/CD:**
    - General best-practice advice: `@arm `
    - Multi-architecture advice: `@arm `
    - 
    - GCP cloud stuff

Our extension also excels at helping with basic advice, such as `@arm I am trying to compile C++ code for the Arm architecture. Which compiler should I use?`



