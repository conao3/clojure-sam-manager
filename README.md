# clojure-sam-manager

A Clojure-based manager for AWS Serverless Application Model (SAM) with Nix integration.

## Overview

clojure-sam-manager provides a streamlined approach to managing AWS SAM applications. SAM extends AWS CloudFormation with serverless-specific syntax, making it easier to define Lambda functions, API Gateway endpoints, and other serverless resources.

This project leverages Nix for reproducible builds and dependency management, ensuring consistent deployments across different environments.

## Features

- SAM template management and validation
- Nix-based reproducible build environment
- CloudFormation stack operations
- Lambda function deployment workflows

## Prerequisites

- [Nix](https://nixos.org/) package manager
- AWS credentials configured
- [AWS SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/install-sam-cli.html) (optional, for local testing)

## Getting Started

Clone the repository:

```bash
git clone https://github.com/conao3/clojure-sam-manager.git
cd clojure-sam-manager
```

## Related Technologies

- [AWS SAM](https://aws.amazon.com/serverless/sam/) - Serverless Application Model
- [AWS CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastructure as Code
- [Nix](https://nixos.org/) - Reproducible builds and package management

## License

This project is open source. See the repository for license details.
