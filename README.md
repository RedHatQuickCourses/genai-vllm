## vLLM on OpenShift AI Course

Welcome to the vLLM on OpenShift AI course! This repository contains the instructional materials and lab exercises for deploying and managing large language models (LLMs) with vLLM on the Red Hat OpenShift AI platform. This course is designed for AI platform engineers and consultants who are focused on delivering AI incubator projects and production-ready services.

The content is authored in AsciiDoc and organized using Antora to create a user-friendly and interactive learning experience on our website.

-----

## Course Overview

This course provides a comprehensive guide to leveraging vLLM for efficient LLM serving on OpenShift AI. You will learn the core concepts of vLLM, including its key features like PagedAttention and continuous batching, and how these translate to significant performance improvements and cost savings in your AI/ML workloads.

Through a combination of theoretical lessons and hands-on labs, you will gain practical experience in deploying and managing LLMs on OpenShift AI using vLLM.

-----

## Target Audience

  * **AI Platform Engineers:** Professionals responsible for building and maintaining the infrastructure for AI/ML model deployment and serving.
  * **AI/ML Consultants:** Consultants working with customers to design and implement AI solutions, from proof-of-concept to production.

-----

## Learning Objectives

Upon completion of this course, you will be able to:

  * Understand the architecture and core features of vLLM.
  * Articulate the benefits of using vLLM for LLM inference, such as increased throughput and reduced latency.
  * Deploy and configure the vLLM serving runtime on OpenShift AI.
  * Serve various open-source LLMs using the vLLM server.
  * Interact with deployed LLMs through an OpenAI-compatible API.
  * Performance test LLM services effectively on OpenShift AI using GuideLLM

-----

## Course Structure

The course materials are organized into modules, each covering a specific aspect of using vLLM on OpenShift AI. The content is structured for a seamless learning path, from foundational concepts to advanced deployment strategies.

All course documentation is written in AsciiDoc and built into a static website using Antora.

### To build the documentation locally:

1.  Clone this repository:
    ```bash
    git clone <repository-url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3.  Ensure you have Node.js and Antora installed. If not, follow the instructions on the [Antora website](https://antora.org/).
4.  Build the site:
    ```bash
    antora antora-playbook.yml
    ```
5.  The generated documentation will be in the `build/site` directory.

-----

## Labs

The hands-on labs are a crucial component of this course. You will find detailed instructions and all necessary files within the `genai-apps repository` for the respective modules. These labs will guide you through the practical steps of deploying and interacting with LLMs using vLLM on an OpenShift AI environment.

-----

## Contributing

We welcome contributions to improve this course\! If you find any issues, have suggestions for improvements, or would like to add new content, please feel free to open an issue or submit a pull request.

-----

We hope you find this course valuable in your journey to mastering LLM deployment with vLLM on OpenShift AI. Let's get started\!