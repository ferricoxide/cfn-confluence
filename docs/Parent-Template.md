### Parent Template

The function of this template is to provide an "Easy" button for deploying a Confluence Server service. The provided template invokes the EC2, EFS, Security Group, S3, IAM, RDS, and ELB templates. Upon completion of this template's running, an ELB-fronted Confluence Server service will be up and ready for initial configuration.

A wide variety of "parent" templates may be needed to deal with the particulars of a given deployment (e.g., environments where permissions for creating IAM roles are separate from those for creating EC2s). This parent is meant as an example suitable for environments where the invoking-user has full provisioning-rights within an AWS account.
