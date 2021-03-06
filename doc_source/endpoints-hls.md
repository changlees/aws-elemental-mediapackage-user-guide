# Creating an HLS Endpoint<a name="endpoints-hls"></a>

Create an endpoint that formats content for devices that support Apple HLS\.

**To create an Apple HLS endpoint \(console\)**

1. Access the channel that the endpoint will be associated with, as described in [Viewing Channel Details](channels-view.md)\.

1. On the details page for the channel, choose either **Add and edit endpoint** or **Add endpoints** if there are no existing endpoints\.

1. Complete the fields as described in the following topics:
   + [New Endpoint Fields](endpoints-hls-new.md)
   + [Packager Settings Fields](endpoints-hls-packager.md)
   + [Encryption Fields](endpoints-hls-encryption.md)
   + [Access Control Fields](endpoints-hls-access-control.md)
   + [Streams to Include Fields](endpoints-hls-include-streams.md)

1. Choose **Save endpoints**\.

   If you enabled Amazon CloudFront distribution creation from the AWS Elemental MediaPackage console and this is your first endpoint on the channel, MediaPackage adds an origin to the distribution\. You can view the CloudFront CDN URL and endpoint information in the endpoints section of the channel's details page\.

   The endpoint is active and can deliver content as soon as requests are sent to its URL endpoints\. AWS Elemental MediaPackage scales resources up and down to allow the right amount of capacity for your traffic\.