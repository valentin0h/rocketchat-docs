# Zapier

{% hint style="warning" %}
![](<../../../../.gitbook/assets/Deprecated (1).png>)Zapier integration has been deprecated from Rocket.Chat `6.0.`

You can install the Zapier app from Marketplace to avoid disruptions.
{% endhint %}

[Zapier](https://zapier.com/zapbook/RocketChat/) lets you connect Rocket.Chat to hundreds of other web services. Automated connections called Zaps, set up in minutes with no coding, can automate your day-to-day tasks and build workflows between apps that otherwise wouldn't be possible.

Before you get started, there are a few things that you have to check.

{% hint style="info" %}
* You are required to have a Rocket.Chat server accessible publicly
* A user with the **`impersonate user`** permission to be used for authentication.
* Zapier OAuth is configured by default at `Admin -> oAuth Apps -> Zapier`
{% endhint %}

* Log in or create a new [Zapier account](https://zapier.com)
* From your Zapier dashboard, click on **My Apps** then click on **Add Connection.**

![](<../../../../.gitbook/assets/image (1221).png>)

* Search for Rocket.Chat and choose it in the popup that shows

![](<../../../../.gitbook/assets/image (69).png>)

* A new window will open. Fill in your workspace url(_keep the trailing slash_) and continue

![](<../../../../.gitbook/assets/image (1237).png>)

* You are then redirected to your workspace to authenticate. Authenticate with any user having the `impersonate user` permission

![](<../../../../.gitbook/assets/image (897).png>)

* Accept all the privileges needed and **Authorize**

![](<../../../../.gitbook/assets/image (793).png>)

* Your new connection is ready to be used with [other Zapier apps](https://zapier.com/apps/rocketchat/integrations)
* You can test the connection by clicking on the 3 dots by the side as seen below

![](<../../../../.gitbook/assets/image (120).png>)

Once that is done you can start creating an automation! Use a pre-made Zap or create your own with the Zap Editor. Creating a Zap requires no coding knowledge and you'll be walked step-by-step through the setup.

Each Zap has one app as the **Trigger**, where your information comes from and which causes one or more **Actions** in other apps, where your data gets sent automatically.
