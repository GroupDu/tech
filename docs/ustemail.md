## Before

First, send an email to ITSC to explain your purpose and get ``Tenant ID`` and ``Application ID``.

## Config

We take Manjaro Linux as an example.

- Install Evolution and its ews plugin: ``sudo pacman -S evolution evolution-ews``
- Open Evolution
- Click ``Edit - Preferecnces - Add email account``
- Input your email address: ``xxx@connect.ust.hk``, then click ``Next``
- Choose ``Server type`` as ``Exchange Web Services``, then input the ``Host Url``: <https://outlook.office365.com/EWS/Exchange.asmx>
- Then choose the authentication type as ``OAuth2``, and input the ``Tenant ID`` and ``Application ID``
- Click ``Next`` until ``Apply``, and it will prompts a CAS authentication window, just authenticate with your Duo Mobile App.
- Done.
