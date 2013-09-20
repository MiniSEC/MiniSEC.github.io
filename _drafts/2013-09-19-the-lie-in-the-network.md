---
layout: post
category : 
tagline: "Truth hurts."
tags : [Simplicity]
image : /assets/img/House-No-Lies-house-md-561420_1680_1050.jpg
image1 : /assets/img/EinsteinSimple.jpg
image2 : /assets/img/typicalstructure.gif
image3 : 
---

{% include JB/setup %}

>Above all, don't lie to yourself. The man who lies to himself and listens to his own lie comes to a point that he cannot distinguish the truth within him, or around him, and so loses all respect for himself and for others. And having no respect he ceases to love.<br>
> -- <cite>Fyodor Dostoyevsky</cite><br>

I cannot lie any more, I cannot pretend that the SANS 20(http://www.sans.org/critical-security-controls/guidelines.php) will save us.  I can no longer pretend that VLAN's segment the network. I can no longer pretend that network protocols that function at Layer2 are anything other then the greatest threat to a secure network that currently exists. I can no longer say that network firewalls do anything but create a false idea of a secure "internal" network. I can not stand by any longer and watch the traditional and start-up security vendors sell band-aid's for issues that need surgery. 

The whole IT industry covers a lie, a lie it just cant admit. We keep telling that lie every time we build a "best practices" network. When we accept the lies, we ignore the underlying fundamental flaws.

Perpetuating the lie that the network should be responsible for anything other then moving bits from point A to point B is bad engineering. It breeds a false sense of security and moves the responsibility of defence from where it should be. Do you expect the road to protect your house? The only thing you expect the road to do is ensure the safe and orderly movement of vehicles. Like a gated community the only place the network is responsible for defence is at the "border". Checking the traffic at the gate. THAT IS ALL, the rest is up to the system owner and the application.

Office networks, datacenter networks, it doesn't matter, as an industry we have built solutions that do what is "cool" and not what is needed. As an Industry we forgot the KISS rule. 

![If you cant explain it simply, you don't understand it well enough.]({{page.image1}})

"Networking Best Practices" have failed. Those standards build unmaintainable networks that have no place in the modern computing world. BYOD, cloud, remote workers, are all tearing down the crumbling wall of segmentation and control. The whole IT industry started down a bad road way back in 1984-85 at the dawn of the Ethernet age, we compounded it by buying into the lie of firewalls, and VLANS and we continue it everyday that we build to current "best practices". Networks need to be simplified. Isolated ports that require L3 connectivity, 802.1x to control physical connectivity, high capacity aggregation switches, full speed tap's and BGP between aggregation points are all that is required. Why aren't networks ALWAYS as simple as: ![Simple!]({{page.image2}})

Why? Becasue we make them harder.

We've all heard the quote about two roads diverging, lets take that less travelled one, lets build something that is truly sustainable, truly resilient, truly simple! Remove the unnecessary, and place the responsibility where it belongs. Security cannot be bolted on it must be built in, and that will require changes in how we think about the entire stack, but it STARTS with the network.

In the next post, I intend to break this down more, but for now lets keep it SIMPLE.
