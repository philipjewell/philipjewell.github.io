---
id: 196
title: First WordPress Plugin
date: 2016-02-10T05:21:06+00:00
author: philipjewell
layout: post
guid: http://philipjewell.com/?p=196
permalink: /blog/first-plugin
image: http://philipjewell.com/wp-content/uploads/2016/02/banner-772x250.jpg
categories:
  - Banners
  - Featured
---
As of recently, I have developed my first WordPress plugin..

Working in the hosting industry and understanding the importance of SSL&#8217;s and showing your visitors that you have a secure site is huge. You&#8217;ll notice that in ecommerce sites especially that they will have the words &#8220;Secured&#8221; and or &#8220;Verified&#8221; to ensure confidence in the person entering their information into the site.

Most of these badges of seals that websites sport have little the no weight at all. Often, they are just a simple jpg or png image that anyone could have saved and uploaded onto their site.

The plugin our developed uses PHP in order to actually gather the active information on the secure protocol of the website like your browser would in order to provide accurate information. By displaying the actual certificate issuer and the valid certificate dates, this can ensure the visitor a little more than a simple image.

By clicking on the badge/bar my plugin provides, it links you to a very widely trusted 3rd party service called SSL Shopper which also displays the certificate&#8217;s information.

When a user does not have a certificate for the domain name the plugin is installed under, it provides them a link to a provider which offers SSL certificates for free like <a href="https://www.startssl.com/" target="_blank">StartSSL.com</a>. Sites like those and <a href="https://letsencrypt.org/" target="_blank">LetsEncrypt.org</a> have been trying to make the web a better, more secure place by offering these certificates for free. Considering products like this can be found for $50-$70 through other providers, makes this a huge deal for those who are trying to get their website up and running. This goes without mentioning that Google has publicly stated they would increase the rankings of those sites that are encrypted with SSL certificates (<a href="https://googlewebmastercentral.blogspot.com/2014/08/https-as-ranking-signal.html" target="_blank">source</a>).

If you are using WordPress to manage your website and are interested in such a plugin, please feel free to take a look at <https://wordpress.org/plugins/ssl-verification-badge/>

Keep in mind, I am constantly making updates and adjustments.  


<div class="github-widget" data-repo="philipjewell/ssl-verification-badge">
</div>