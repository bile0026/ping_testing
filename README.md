# ping_testing

Test connectivity from devices to a list of IP's/hostnames.

Either alter the `hosts_to_ping` in the default vars, or add extra vars with a list of IP's hostnames to ping and trace.

By default `trace_type` is set to traceroute, but can be set to tracepath.

Fill in smtp variables if you want a report emailed:
```
# for email reports
email_report: false
smtp_server: mail.example.com
to_address: jondoe@example.com
from_address: ansible@example.com
```
