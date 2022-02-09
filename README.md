# This powers shitposting.pictures

It uses an S3 bucket kept securely behind a CloudFront distribution to store screenshots (I populate it with [Dropshare](https://dropshare.app/). 

I manually registered shitposting.pictures as a domain for this. Then, Pulumi handles the rest via the code contained in this repo. Ideally it'll help others do things with a bit less ClickOps.
