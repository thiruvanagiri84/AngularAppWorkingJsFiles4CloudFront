Endpoint deployed in Ec2 with IP

http://18.216.103.153/organizations/1001/admins

But in the angularappwithoutip we call the url without IP like this

/organizations/1001/admins

This will work only when we configure CloudFront service of AWS.

Permanent fix would be to use CloudFront service of AWS, which will enable 2 different hosts to be behaving as a single host.