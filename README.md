# ReEnroller

Download: [ReEnroller](./releases/download/current/ReEnroller.zip)

A tool to migrate data granularly between Jamf Pro servers

![alt text](./blob/master/ReEnroller/images/ReEnroller.png "ReEnroller")


Easily migrate a computer from one Jamf server to another.  Use ReEnroller to build a package to take a macOS device enrolled in one Jamf server and enroll it into another.
* Ability to add (and then remove) a profile to the package.  This can help maintain a WiFi connection while migrating.
* Machine attempts to fail back to original server if enrollment in the new server fails.
* Specify the number of attempts and interval between attempts for enrolling in the new server.
* Can also be used for initial enrollments.
* Enroll into a specific site.
* Can automatically create a policy to verify enrollment in the new server.
* Select a policy to run after a successful enrollment.
* Deploy the package with policy or push it to an individual machine from within the app.

**Be sure to view the help for detailed usage instructions.

Thanks @fauxserve for coming up with the idea and initial bash version.