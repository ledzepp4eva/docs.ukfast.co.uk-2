# Removing a domain from DDoSX<sup>®</sup>

If you want to remove a domain from DDoSX<sup>®</sup> then follow these steps:

1. Login to [MyUKFast](https://my.ukfast.co.uk) and go to the `DDoSX` section under `Products and Services`.
2. Click the delete icon next to the domain in question
3. You'll be asked to re-enter your MyUKFast password to confirm you wish to go ahead and delete the domain.
4. Your domain will now be disconnected from the DDoSX<sup>®</sup> network.  You can reconnect your domain at any time until the billing period expires.
5. You should use [SafeDNS](/domains/safedns/index) to point your domain records back to your own server or firewall, so that traffic to the domain is no longer being routed via the UKFast DDoSX<sup>®</sup> network.


<h4><b>CLI:</b></h4>
```bash
ans ddosx domain delete mydomain.example --summary "example of removing a domain" --description "example of remove a domain for the docs page
```

```eval_rst
.. warning::

   If you don't point your domain records back to your own server or firewall, your domain will go offline when the domain's DDoSX\ :sup:`®` billing period expires.

```

```eval_rst
   .. title:: Removing A Domain From DDoSX
   .. meta::
      :title: Removing A Domain From DDoSX | UKFast Documentation
      :description: Help with removing a domain from DDoSX
      :keywords: domain, ddos, ddos protection, anti-ddos
```
