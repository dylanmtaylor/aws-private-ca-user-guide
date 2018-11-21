# AWS Certificate Manager Private Certificate Authority User Guide

-----
*****Copyright &copy; 2018 Amazon Web Services, Inc. and/or its affiliates. All rights reserved.*****

-----
Amazon's trademarks and trade dress may not be used in 
     connection with any product or service that is not Amazon's, 
     in any manner that is likely to cause confusion among customers, 
     or in any manner that disparages or discredits Amazon. All other 
     trademarks not owned by Amazon are the property of their respective
     owners, who may or may not be affiliated with, connected to, or 
     sponsored by Amazon.

-----
## Contents
+ [What Is ACM PCA?](PcaWelcome.md)
   + [Concepts](PcaConcepts.md)
   + [Regions](PcaRegions.md)
   + [Services Integrated with AWS Certificate Manager Private Certificate Authority](PcaIntegratedServices.md)
   + [Limits](PcaLimits.md)
   + [Private Certificate Authority Security](PcaSecurity.md)
   + [Best Practices](PcaBestPractices.md)
   + [Supported CloudWatch Metrics](PcaCloudWatch.md)
   + [Pricing](PcaPricing.md)
+ [Setting Up](PcaSetup.md)
   + [Install the AWS Command Line Interface (Optional)](PcaInstallCLI.md)
   + [Create an IAM Administrator](PcaIamAdmin.md)
   + [Set Up a Certificate Authority](PcaOnPremises.md)
+ [Getting Started](PcaGetStarted.md)
   + [Step 1: Create a Private Certificate Authority](PcaCreateCa.md)
   + [Step 2: Get a Certificate Signing Request (CSR)](PcaGetCsr.md)
   + [Step 3: Sign Your Private CA Certificate](PcaSignCert.md)
   + [Step 4: Import Your Private CA Certificate into ACM PCA](PcaImportCaCert.md)
+ [Using Your Private Certificate Authority (CA)](PcaUsing.md)
   + [Create a Certificate Revocation List (CRL)](PcaUsingCrl.md)
   + [Issue a Private Certificate](PcaIssueCert.md)
   + [Revoke a Private Certificate](PcaRevokeCert.md)
   + [Retrieve a Private Certificate](PcaGetCert.md)
   + [Retrieve a Certificate Authority (CA) Certificate](PcaGetCACert.md)
   + [Update Your Private CA](PCAUpdateCA.md)
   + [Delete Your Private CA](PCADeleteCA.md)
   + [Restore Your Private CA](PCARestoreCA.md)
   + [Create an Audit Report for Your Private CA](PcaAuditReport.md)
   + [Add Tags to your Private Certificate Authority](PcaCaTagging.md)
+ [Using CloudTrail](PcaCtIntro.md)
   + [Creating a Certificate Authority](CT-CreateCA.md)
   + [Creating an Audit Report](CT-CreateAuditReport.md)
   + [Deleting a Certificate Authority](CT-DeleteCA.md)
   + [Restoring a Certificate Authority](CT-RestoreCA.md)
   + [Describing a Certificate Authority](CT-DescribeCA.md)
   + [Retrieving a Certificate Authority Certificate](CT-GetCACertificate.md)
   + [Retrieving the Certificate Authority Signing Request](CT-GetCACsr.md)
   + [Retrieving a Certificate](CT-GetCertificate.md)
   + [Importing a Certificate Authority Certificate](CT-ImportCACertificate.md)
   + [Issuing a Certificate](CT-IssueCertificate.md)
   + [Listing Certificate Authorities](CT-ListCAs.md)
   + [Listing Tags](CT-ListTags.md)
   + [Revoking a Certificate](CT-RevokeCertificate.md)
   + [Tagging Private Certificate Authorities](CT-TagPCA.md)
   + [Updating a Certificate Authority](CT-UpdateCA.md)
   + [Removing Tags from a Private Certificate Authority](CT-UntagPCA.md)
+ [Using the ACM PCA API](PcaApiIntro.md)
   + [CreateCertificateAuthority](JavaApi-CreatePrivateCertificateAuthority.md)
   + [CreateCertificateAuthorityAuditReport](JavaApi-CreateCertificateAuthorityAuditReport.md)
   + [DeleteCertificateAuthority](JavaApi-DeleteCertificateAuthority.md)
   + [DescribeCertificateAuthority](JavaApi-DescribeCertificateAuthority.md)
   + [DescribeCertificateAuthorityAuditReport](JavaApi-DescribeCertificateAuthorityAuditReport.md)
   + [GetCertificate](JavaApi-GetCertificate.md)
   + [GetCertificateAuthorityCertificate](JavaApi-GetCACertificate.md)
   + [GetCertificateAuthorityCsr](JavaApi-GetCertificateAuthorityCsr.md)
   + [ImportCertificateAuthorityCertificate](JavaApi-ImportCertificateAuthorityCertificate.md)
   + [IssueCertificate](JavaApi-IssueCertificate.md)
   + [ListCertificateAuthorities](JavaApi-ListCertificateAuthorities.md)
   + [ListTags](JavaApi-ListTags.md)
   + [RestoreCertificateAuthority](JavaApi-RestoreCertificateAuthority.md)
   + [RevokeCertificate](JavaApi-RevokeCertificate.md)
   + [TagCertificateAuthorities](JavaApi-TagPCA.md)
   + [UntagCertificateAuthority](JavaApi-UnTagPCA.md)
   + [UpdateCertificateAuthority](JavaApi-UpdateCertificateAuthority.md)
+ [Troubleshooting](PcaTsIntro.md)
   + [Troubleshoot Creating and Signing a Private CA Certificate](PcaTsSignCsr.md)
+ [Authentication and Access](auth-toplevel.md)
   + [Managing Access to Your Private Certificate Authority.](auth-overview.md)
   + [Customer Managed Policies](auth-custmanagedpolicies.md)
   + [Inline Policies](auth-inlinepolicies.md)
   + [ACM PCA API Permissions: Actions and Resources Reference](auth-apipermissions.md)
+ [Document History](doc-history.md)