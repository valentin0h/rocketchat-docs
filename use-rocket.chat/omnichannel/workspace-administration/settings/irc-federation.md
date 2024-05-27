---
description: Connect to other IRC servers
---

# IRC Federation

{% hint style="warning" %}
IRC Federation is in beta. Use on a production system is not recommended at this time.
{% endhint %}

IRC Federation allows your server to connect to other IRC servers.

Internet Relay Chat (IRC) is a text-based group communication tool. Users join uniquely named channels, or rooms, for open discussion. IRC also supports private messages between individual users and file-sharing capabilities. This package integrates these layers of functionality with Rocket.Chat.

After configuring, you are able to communicate directly from your Rocket.Chat to any external IRC server.

To access this setting, go to **Administration** > **Workspace** > **Settings** > **IRC Federation**.

* **Enabled**: When enabled, provides settings for IRC Federation integration.
* **Protocol**: This lets you set the protocol your IRC server uses. example `RFC2813`.
* **Host**: The host on which your IRC is running on, for example `irc.rocket.chat`
* **Port**: The port to bind to on the IRC host server.
* **Name**: What to name your IRC server as.
* **Description**: Description of your IRC server.
* **Local Password**: Set the local password if existing.
* **Peer Password**: Lets you specify the peer password.

{% hint style="info" %}
After configuring, hit **Save Changes** and **Restart** your server.
{% endhint %}
