# AWS Get Signed CloudFront URL #

This plugin provides a function to generate a signed URL to enable private content to be served through Amazon CloudFront. A CloudFront
key pair has to be created to configure the plugin and the CloudFront distribution configured appropriately. 
Full details of this process can be found in the 
[AWS documentation](http://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/PrivateContent.html)

Use AWSSignedURL::get_signed_URL( $resource ) in your code to retrieve a signed AWS CloudFront URL, where $resource is the full URL
to the resource for which you need a signed URL.

This plugin was forked from the "AWS Signed URL Plugin" from Orca Studios: https://github.com/ocastastudios/wordpress-aws-signed-url

