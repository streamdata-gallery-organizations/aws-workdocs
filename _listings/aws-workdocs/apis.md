---
name: AWS WorkDocs
x-slug: aws-workdocs
description: Amazon WorkDocs is a fully managed, secure enterprise storage and sharing
  service with strong administrative controls and feedback capabilities that improve
  user productivity.Users can comment on files, send them to others for feedback,
  and upload new versions without having to resort to emailing multiple versions of
  their files as attachments. Users can take advantage of these capabilities wherever
  they are, using the device of their choice, including PCs, Macs, tablets and phones.
  Amazon WorkDocs offers IT administrators the option of integrating with existing
  corporate directories, flexible sharing policies and control of the location where
  data is stored. Customers can get started using Amazon WorkDocs with a 30-day free
  trial providing 1 TB of storage per user for up to 50 users.Amazon WorkDocs offers
  an Administrative SDK, currently in public preview. The Administrative SDK allows
  you to integrate your applications with Amazon WorkDocs by performing content and
  permissions updates, and managing users, programmatically. You can sign-up for the
  public preview here.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS WorkDocs
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/apis.md
specificationVersion: "0.14"
apis:
- name: AWS WorkDocs API Abort Document Version Upload
  x-api-slug: aws-workdocs-api
  description: Aborts the upload of the specified document version that was previously
    initiated by.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=AbortDocumentVersionUpload
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionabortdocumentversionupload-get-openapi.md
- name: AWS WorkDocs API Activate User
  x-api-slug: aws-workdocs-api
  description: Activates the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=ActivateUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionactivateuser-get-openapi.md
- name: AWS WorkDocs API Add Resource Permissions
  x-api-slug: aws-workdocs-api
  description: Creates a set of permissions for the specified folder or document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=AddResourcePermissions
  tags: Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionaddresourcepermissions-get-openapi.md
- name: AWS WorkDocs API Create Folder
  x-api-slug: aws-workdocs-api
  description: Creates a folder with the specified name and parent folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=CreateFolder
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actioncreatefolder-get-openapi.md
- name: AWS WorkDocs API Create Notification Subscription
  x-api-slug: aws-workdocs-api
  description: Configure WorkDocs to use Amazon SNS notifications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=CreateNotificationSubscription
  tags: Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actioncreatenotificationsubscription-get-openapi.md
- name: AWS WorkDocs API Create User
  x-api-slug: aws-workdocs-api
  description: Creates a user in a Simple AD or Microsoft AD directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=CreateUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actioncreateuser-get-openapi.md
- name: AWS WorkDocs API Deactivate User
  x-api-slug: aws-workdocs-api
  description: Deactivates the specified user, which revokes the user's access to
    Amazon WorkDocs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DeactivateUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondeactivateuser-get-openapi.md
- name: AWS WorkDocs API Delete Document
  x-api-slug: aws-workdocs-api
  description: Permanently deletes the specified document and its associated metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DeleteDocument
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondeletedocument-get-openapi.md
- name: AWS WorkDocs API Delete Folder
  x-api-slug: aws-workdocs-api
  description: Permanently deletes the specified folder and its contents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DeleteFolder
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondeletefolder-get-openapi.md
- name: AWS WorkDocs API Delete Folder Contents
  x-api-slug: aws-workdocs-api
  description: Deletes the contents of the specified folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DeleteFolderContents
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondeletefoldercontents-get-openapi.md
- name: AWS WorkDocs API Delete Notification Subscription
  x-api-slug: aws-workdocs-api
  description: Deletes the specified subscription from the specified organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DeleteNotificationSubscription
  tags: Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondeletenotificationsubscription-get-openapi.md
- name: AWS WorkDocs API Delete User
  x-api-slug: aws-workdocs-api
  description: Deletes the specified user from a Simple AD or Microsoft AD directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DeleteUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondeleteuser-get-openapi.md
- name: AWS WorkDocs API Describe Document Versions
  x-api-slug: aws-workdocs-api
  description: Retrieves the document versions for the specified document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DescribeDocumentVersions
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondescribedocumentversions-get-openapi.md
- name: AWS WorkDocs API Describe Folder Contents
  x-api-slug: aws-workdocs-api
  description: Describes the contents of the specified folder, including its documents
    and sub-folders.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DescribeFolderContents
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondescribefoldercontents-get-openapi.md
- name: AWS WorkDocs API Describe Notification Subscriptions
  x-api-slug: aws-workdocs-api
  description: Lists the specified notification subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DescribeNotificationSubscriptions
  tags: Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondescribenotificationsubscriptions-get-openapi.md
- name: AWS WorkDocs API Describe Resource Permissions
  x-api-slug: aws-workdocs-api
  description: Describes the permissions of a specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DescribeResourcePermissions
  tags: Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondescriberesourcepermissions-get-openapi.md
- name: AWS WorkDocs API Describe Users
  x-api-slug: aws-workdocs-api
  description: Describes the specified users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=DescribeUsers
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiondescribeusers-get-openapi.md
- name: AWS WorkDocs API Get Document
  x-api-slug: aws-workdocs-api
  description: Retrieves the specified document object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=GetDocument
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiongetdocument-get-openapi.md
- name: AWS WorkDocs API Get Document Path
  x-api-slug: aws-workdocs-api
  description: Retrieves the path information (the hierarchy from the root folder)
    for the requested document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=GetDocumentPath
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiongetdocumentpath-get-openapi.md
- name: AWS WorkDocs API Get Document Version
  x-api-slug: aws-workdocs-api
  description: Retrieves version metadata for the specified document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=GetDocumentVersion
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiongetdocumentversion-get-openapi.md
- name: AWS WorkDocs API Get Folder
  x-api-slug: aws-workdocs-api
  description: Retrieves the metadata of the specified folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=GetFolder
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiongetfolder-get-openapi.md
- name: AWS WorkDocs API Get Folder Path
  x-api-slug: aws-workdocs-api
  description: Retrieves the path information (the hierarchy from the root folder)
    for the specified folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=GetFolderPath
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actiongetfolderpath-get-openapi.md
- name: AWS WorkDocs API Initiate Document Version Upload
  x-api-slug: aws-workdocs-api
  description: Creates a new document object and version object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=InitiateDocumentVersionUpload
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actioninitiatedocumentversionupload-get-openapi.md
- name: AWS WorkDocs API Remove All Resource Permissions
  x-api-slug: aws-workdocs-api
  description: Removes all the permissions from the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=RemoveAllResourcePermissions
  tags: Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionremoveallresourcepermissions-get-openapi.md
- name: AWS WorkDocs API Remove Resource Permission
  x-api-slug: aws-workdocs-api
  description: Removes the permission for the specified principal from the specified
    resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=RemoveResourcePermission
  tags: Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionremoveresourcepermission-get-openapi.md
- name: AWS WorkDocs API Update Document
  x-api-slug: aws-workdocs-api
  description: Updates the specified attributes of the specified document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=UpdateDocument
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionupdatedocument-get-openapi.md
- name: AWS WorkDocs API Update Document Version
  x-api-slug: aws-workdocs-api
  description: Changes the status of the document version to ACTIVE.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=UpdateDocumentVersion
  tags: Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionupdatedocumentversion-get-openapi.md
- name: AWS WorkDocs API Update Folder
  x-api-slug: aws-workdocs-api
  description: Updates the specified attributes of the specified folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=UpdateFolder
  tags: Folders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionupdatefolder-get-openapi.md
- name: AWS WorkDocs API Update User
  x-api-slug: aws-workdocs-api
  description: "Updates the specified attributes of the specified user, and grants
    or revokes \n      administrative privileges to the Amazon WorkDocs site."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: ://///?Action=UpdateUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/actionupdateuser-get-openapi.md
- name: AWS WorkDocs API
  x-api-slug: aws-workdocs-api
  description: Amazon WorkDocs is a fully managed, secure enterprise storage and sharing
    service with strong administrative controls and feedback capabilities that improve
    user productivity.Users can comment on files, send them to others for feedback,
    and upload new versions without having to resort to emailing multiple versions
    of their files as attachments. Users can take advantage of these capabilities
    wherever they are, using the device of their choice, including PCs, Macs, tablets
    and phones. Amazon WorkDocs offers IT administrators the option of integrating
    with existing corporate directories, flexible sharing policies and control of
    the location where data is stored. Customers can get started using Amazon WorkDocs
    with a 30-day free trial providing 1 TB of storage per user for up to 50 users.Amazon
    WorkDocs offers an Administrative SDK, currently in public preview. The Administrative
    SDK allows you to integrate your applications with Amazon WorkDocs by performing
    content and permissions updates, and managing users, programmatically. You can
    sign-up for the public preview here.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkDocs.png
  humanURL: https://aws.amazon.com/workdocs/
  baseURL: :///
  tags: AWS WorkDocs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-workdocs/master/_listings/aws-workdocs/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/workdocs/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/workdocs/faqs/
- type: x-forum
  url: https://aws.amazon.com/workdocs/resources/#forum
- type: x-pricing
  url: https://aws.amazon.com/workdocs/pricing/
- type: x-sdk
  url: https://aws.amazon.com/workdocs/developers/
- type: x-website
  url: https://aws.amazon.com/workdocs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---