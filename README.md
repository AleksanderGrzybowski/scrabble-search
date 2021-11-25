## SmsAlerts

This is a small Ruby app, that I created for searching Polish Scrabble words. It's a showcase of single-file Kuberetes applications, that do not use any custom image - everything is reprovisioned on every restart. That makes it very convenient for ad-hoc deployments.

To try it out, deploy as usual with `kubectl apply -f <filename.yml>` and go to the address defined in Ingress. 
