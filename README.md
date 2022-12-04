# msmtp-fail2ban

The SMTP client configuration files for fail2ban are located in this repository.

To use - copy files from the `action.d` directory to the directory of configuration files **fail2ban** `/etc/fail2ban/action.d`.

To use the email sending service, configure the `.msmtprc` file in your user's home directory. More detailed documentation is available on the [official website](https://marlam.de/msmtp/msmtp.html) of the **msmtp** client.

Set as the default client for sending emails in **fail2ban** settings:

```conf
mta = msmtp
```
