# GitHub-fabric-cicd-sample to operationalize fabric-cicd to work with Microsoft Fabric and GitHub Actions
Contains a GitHub workflow which can be used operationalize [fabric-cicd](https://github.com/microsoft/fabric-cicd) to work with Microsoft Fabric and GitHub Actions. Based on a blog post I published that shows how to [operationalize fabric-cicd to work with Microsoft Fabric and GitHub Actions](https://www.kevinrchant.com/2025/04/11/operationalize-fabric-cicd-to-work-with-microsoft-fabric-and-github-actions/).

This repository caters for the scenario where all the values are constant.

You can find the workflow in the [/.github/workflows subfolder](/.github/workflows). In the workflow there are comments about what variables are required.

All of the samples of Fabric items provided in the worskpace folder are from the [original fabric-cicd repository](https://github.com/microsoft/fabric-cicd). However, I do recommend testing with your own items stored in a repository that is the backend for a workspace configured with Microsoft Fabric Git integration.

In addition, you can sutomize the ["parameter.yml" file](/workspace/parameter.yml) to suit your requirements.

This repository is provided "as is" based on the [MIT license](https://opensource.org/licenses/MIT). Basically, I am not responsible for your use of it.
