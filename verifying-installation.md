# Verifying your installation


So far you have requested in your self-service console a working environment to author process and policies. Now we will verify the environment and the tools available to you. Earlier we saw that Red Hat Process Automation Manager has authoring tools both for developers as well as subject domain experts.

![Collaboration Tools]({% image_path collaboration_tools.png %}){:width="600px"}

For business experts, the platform provides the Business Central console, a web-based business workbench with capabilities to manage the full lifecycle of your automation assets.

## Business Central

1- Go to your Openshift console tab. Go to step 2 if you're already logged in. If you're not yet logged in, or have been logged out, login using the same credentials as before:
- user: `developer`{{copy}}
- password: `developer`{{copy}}

![OpenShift Console]({% image_path openshift-console.png %}){:width="600px"}

2- Once logged in you should see your project or workspace called Credit Card Dispute

![Credit Card Dispute Project]({% image_path credit-card-dispute-project.png %}){:width="600px"}

3- Click on your project to see the components.

![Business Central Detail]({% image_path business-central-detail.png %}){:width="600px"}

You will see listed 2 components the `cc-dispute-kieserver` and the `cc-dispute-rhpamcentr`. All you need to know is that the first one is for execution of your automation assets and the latter for authoring of your automation assets.
At this point we are interested on the authoring environment.

4- Select the `cc-dispute-rhpamcentr` deployment and look at the details of the component.

![Business Central Route]({% image_path business-central-route.png %}){:width="600px"}

5- In the network segment you have the information of the location of your console. Click on the link that to the right that says `Route to external traffic` and in a new window the login page for your business central should open.
Use the credentials:
- user: `developer`{{copy}}
- password: `developer`{{copy}}

And you should see the console as follows:

![Business Central Console]({% image_path business-central-console.png %}){:width="600px"}
