# Sagemaker-Studio-mods

Customization based on AWS supplied LCC to support the Idle shutdown of apps. 

Ref : https://github.com/aws-samples/sagemaker-studio-auto-shutdown-extension

The repo has the extracted tar to make it accessible from within the private deployment of Studio, without the additional artefacts of the source library.

The accompanying LCC script will be modified to perform the git clone from this repo to avoid the use of "wget" and associated installations that would need whitelisting in the firewall.
