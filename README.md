

# avalanche_hypersdk_project
Custom Virtual Machine Development with Avalanche HyperSDK
## Overview
Welcome to the project submission for the Custom Virtual Machine Development with HyperSDK! In this project, I have successfully designed and developed a custom blockchain solution using the HyperSDK. This custom virtual machine allows users to mint and transfer tokens, providing tailored functionality to meet specific use cases.

## Project Summary
The aim of this project was to create a custom virtual machine (VM) using the HyperSDK to enable users to mint and transfer tokens. By utilizing the HyperSDK's capabilities, I gained full control over the blockchain's rules and functionality, ensuring that the resulting solution is perfectly suited to the needs of my startup.

## Table of Contents
Project Steps
Functionalities Implemented
Tools and Technologies
Usage
Contributors
License

## Project Steps
Here's a summary of the key steps I took to complete the project:

Cloning Initial Repository: I began by cloning the provided initial repository, which laid the foundation for creating the custom virtual machine.

Normalizing Dependencies: To ensure smooth development, I used the go mod tidy command to normalize all project dependencies.

Configuring Project Constants: In the consts/consts.go file, I configured essential project constants required for the custom virtual machine.

Registering Actions: I registered the Create_Asset and Mint_Asset actions within the registry/registry.go file. This step was crucial for enabling token creation and minting.

Running the Custom VM Locally: By following provided instructions, I set up my local environment to run the custom virtual machine. Utilizing scripts and ensuring GO was on my path, I successfully launched the custom subnet.

Interacting with the Custom VM: I engaged with the custom HyperChain by testing token creation and minting functionalities. The provided demos and repository examples were instrumental in this step.

Closing the Local Avalanche Network: After completing my testing, I responsibly closed the local Avalanche network using the killall avalanche-network-runner command.

## Functionalities Implemented
Throughout the project, I achieved the following functionalities:

Configured project constants to customize the custom VM according to my startup's specific needs.
Registered custom actions (Create_Asset and Mint_Asset) to enable users to create and mint tokens.
Successfully set up and ran the custom VM locally, demonstrating the minting and transferring of tokens.
Interacted with the custom HyperChain through provided demos and repository examples.
Tools and Technologies
The project was completed using the following tools and technologies:

GO programming language
HyperSDK
Remix online IDE
Provided scripts and demos
## Usage
To experience the functionality of the custom virtual machine and interact with the custom HyperChain, follow these steps:

Clone the Repository: Start by cloning the project repository to your local machine.

Normalize Dependencies: Run go mod tidy inside the project folder to ensure all dependencies are properly set up.

Configure Constants: Open the consts/consts.go file and configure the project constants to match your specific use case.

Register Actions: In the registry/registry.go file, register additional actions if needed for your use case.

Run the Custom VM: Utilize provided scripts and follow instructions to set up and run the custom VM locally.

Interact and Test: Use provided demos or interact with the custom HyperChain to test token creation, minting, and other functionalities.

Close the Network: After testing, close the local Avalanche network using the killall avalanche-network-runner command.

## Contributors
This project was created by codeWithNoob

## License
This project is licensed under the BSD License.
