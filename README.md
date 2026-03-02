<h1>Amazon Machine Image (AMI)</h1>
<ul><li> It is a component of EC2 which is used to create an excat copy of the an instance.</li>
<li>It will copy OS, software and cloned app.</li></ul>
<h2>Ways to create AMI:</h2>
<ul>
<li> From the existing EC2 instance: This is the most common way of creating the image. Launch the instance,
configure it with desired software and settings, then create an image out of it.</li>
<li> From a snapshot: You can create an AMI directly from an EBS snapshot. This is useful for creating a new AMI
from a backup of an existing volume.</li>
<li> From the AWS marketplace: You can find and subscribe to a pre-built AMIS created by AWS or by third-party
vendors. These often comes with licensed software and are ready to use.</li>
<li> From community AMI: Other users can create and share their AMIs with the public.</li>
  </ul>
<h2>Uses of AMI:</h2>
<ul>
<li> Backup and disaster management: An AMI acts as a form of backup for your EC2 instance.</li>
<li> Scalability: When you need to scale up or down your application, you can use a pre-configured AMI to
launch new instances.</li>
  <li>Speed: They significantly speed up the deployment process.</li>
  <li> Rollback option: Since we can keep multiple AMIS for the single application, each representing a different version,
you can effectively "Roll back" to any of those version.
</li>
</ul>
<h2>Steps for creating an AMI:</h2>
<ul>
  <li>Create an instance and select ubuntu as a platform.</li>
 <li>log in to the instance and install nginx.</li>
<li>Create one image from existing EC2 instance and another image from the snapshot.</li>
<li> In the main instance deploy the clone the static-website-example name and deploy.</li>
<li> In the first image, clone the first image and deploy.</li>
<li>In the second image (from the snapshot) clone the second image  and deploy.</li>
</ul>
