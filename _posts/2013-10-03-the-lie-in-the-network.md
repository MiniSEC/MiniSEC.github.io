---
layout: post
category : 
tagline: "Truth hurts."
tags : [Simplicity]
image : /assets/img/House-No-Lies-house-md-561420_1680_1050.jpg
image1 : /assets/img/EinsteinSimple.jpg
image2 : /assets/img/typicalstructure.gif
image3 : /assets/img/servicestack.png
---

{% include JB/setup %}

>Above all, don't lie to yourself. The man who lies to himself and listens to his own lie comes to a point that he cannot distinguish the truth within him, or around him, and so loses all respect for himself and for others. And having no respect he ceases to love.<br>
> -- <cite>Fyodor Dostoyevsky</cite><br>

I cannot lie any more or pretend that the SANS 20(http://www.sans.org/critical-security-controls/guidelines.php) will save us.  I can no longer pretend that VLAN's segment the network. I can no longer pretend that network protocols that function at Layer2 are anything other then the greatest threat to a secure network that currently exists. I can no longer say that network firewalls do anything but create a concentration point of failure and false sense of security. I can not stand by any longer and watch the traditional and start-up security vendors sell band-aid's for issues that need surgery. The whole IT industry covers a lie, a lie it just cant admit. We keep telling that lie every time we build a "best practices" network. When we accept the lies, we ignore the underlying fundamental flaws.

"Networking Best Practices" have failed. Those standards build unmaintainable networks that have no place in the modern computing world. those standards perpetuate the "many ways to skin a cat" idea.  BYOD, cloud, remote workers, are all tearing down the crumbling walls of segmentation and control. The IT industry started down a bad road way back in 1984-85 at the dawn of the Ethernet age, we compounded it by buying into the lie of firewalls and VLANS, we continue it everyday that we build to current "best practices". Networks need to be simplified. Isolated ports that require L3 connectivity, 802.1x to control physical connectivity, high capacity aggregation switches, full speed tap's and BGP between aggregation points are all that is required. Why aren't networks ALWAYS simple.

The big lie is that the network should be responsible for anything other then moving bits from point A to point B. Its bad engineering. It breeds a false sense of security and moves the responsibility of defence from where it should be. Do you expect the road to protect your house? The only thing you expect the road to do is ensure the safe and orderly movement of vehicles. Like a gated community the only place the enterprise or data center network is responsible for defence is at the "border". Checking the traffic at the gate. THAT IS ALL, the rest is up to the system owner and the application. Office networks, datacenter networks, it doesn't matter, as an industry we have built solutions that is more then and not what is NEEDED. As an Industry we forgot the KISS rule. ![If you cant explain it simply, you don't understand it well enough.]({{page.image1}})

No matter the industry, no matter the market sector (with few exceptions), why do we think that "this company" is solving some special problem with the network? The special problems exist in Layer 7, in the software we deploy. Stopping the lie means that, as an industry, we accept that no network is special.  Face it; the software that you run might change from company to company, but it all works over IPv4/6. What makes your network a special snowflake? be honest. what is so special about your network?

Why add complexity? Complexity is RISK...

>“Complexity is the path to the Dark Side. Complexity leads to Misconfiguration. Misconfiguration leads to Vulnerability. Vulnerability leads to Compromise.” <br>
> -- <cite> Rev REB </cite><br>

We've all heard the quote about two roads diverging, lets take that less travelled one, lets build something that is truly sustainable, truly resilient, truly SIMPLE! Remove the unnecessary; place the responsibility where it belongs. Security cannot be bolted on it must be built in, and that will require changes in how we think about the entire stack, but it STARTS with the network.

In the next post, I intend to break this down more, but for now lets keep it SIMPLE.