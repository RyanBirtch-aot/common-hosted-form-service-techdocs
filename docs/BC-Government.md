[Home](.) > [CHEFS Components](CHEFS-Components) > [Form Builder Components](Form-Builder-Components) > **BC Government**
***

* [File Upload](#file-upload)
* [Business Name Search](#business-name-search)
* [BC Address](#bc-address)

![image](images/bc-gov.png)

## File Upload
**[Back to top](#top)**

With the CHEFS form builder, you have access to the 'File Upload' component, which enables you to attach files or documents to the form while submitting it. The maximum file size that can be uploaded using this component is 25MB, and all the files submitted through the form are securely stored in a designated Object storage space.

![File Upload Component](images/file-upload-1.png)

> **Note**: The max size per file for upload is 25MB.


### Configuration options

- Multiple files
- Add a label describing the Type of file you want people to upload (eg: 'resume' or 'cover letter')
- File Pattern - we encourage you to enter a list of the allowed file extensions. (For example: `.docx, .doc, .pdf`)

> **Note**: File Uploads are limited to forms that use IDIR or BCeID access. This is for security reasons. We’re looking into ways we can allow file uploads on public forms in a future release.

### File Storage

Files uploaded via a CHEFS form are saved to a designated space in **Object storage**. The Object Storage Service is for Ministry and Greater Public Sector clients to store data as objects using standard protocols including S3, NFS, and HTTP. It provides a scalable, secure, fully managed object storage platform with high availability and enterprise features.

## Business Name Search
**[Back to top](#top)**

The "Business Name Search" auto-complete feature is a useful component that allows you to quickly find organizations by their name, business number, or BC Registries ID. The auto-complete feature helps save time and effort by eliminating the need to type out the full name or number of the organization you are searching for. Instead, you can select the suggested match from the drop-down list and find the organization you are looking for in seconds.

![Business name search](images/bc-business.png)

## BC Address
**[Back to top](#top)**

The BC Address auto-complete component is a preconfigured feature designed to help you quickly find BC addresses. As you enter your query, the tool generates a drop-down list of suggested matches, allowing you to easily select an option and save time and effort that would have been spent typing out the complete address.

This is a preconfigured component. Please note that users can only change the 'Params' details as indicated in the following image. Please visit this link for more information: [Geocoder Developer Toolkit](https://bcgov.github.io/ols-devkit/examples/address_autocomplete.html)

![image](images/bc-address.png)

![image](images/bc-address-preview.png)


**[Back to top](#top)**

***
- [Basic Layout](Basic-Layout)
- [Basic Fields](Basic-Fields)
- [Advanced Layout](Advanced-Layout)
- [Advanced Fields](Advanced-Fields)
- [Advanced Data](Advanced-Data)
- **BC Government**