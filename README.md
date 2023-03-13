<p align="center">
  <img alt="Evilginx2 Logo" src="https://raw.githubusercontent.com/kgretzky/evilginx2/master/media/img/evilginx2-logo-512.png" height="160" />
  <p align="center">
    <img alt="Evilginx2 Title" src="https://raw.githubusercontent.com/kgretzky/evilginx2/master/media/img/evilginx2-title-black-512.png" height="60" />
  </p>
</p>

Collections of evilginx2's phishlets, as used in upcoming training `Phishing Operations` by Archonlabs Training.

## About Evilginx2 

**evilginx2** is a man-in-the-middle attack framework used for phishing login credentials along with session cookies, which in turn allows to bypass 2-factor authentication protection.

Evilginx2 is a standalone application which implements its own HTTP and DNS server, making it extremely easy to setup and use.

## About Phishlets

Phishlets are the configuration files in **YAML** syntax for proxying a legitimate website into a phishing websites.

## Disclaimer

Evilginx2 as well as phishlets in this repository should be used only in legitimate penetration testing or red teaming assignments with written permission from to-be-phished parties. We shall not hold any responsibilities for any activities when using this repository.

Each phishlets is created by their respective owner.

## Usage

Copy the `phishlets` directory into evilginx2's phishlets. 

## Phishlets Development

Phishlet contribution is always welcomed.

Some tips when developing new phishlet:
- always use debug mode in evilginx2 during testing.
- javascript injection can fix a lot of issues and make life easier during phishing engagements.