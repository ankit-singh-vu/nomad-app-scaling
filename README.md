# Horizontal Application Scaling Demo

Instructions available at [HashiCorp Learn][learn_horizontal_app_scaling].

[learn_horizontal_app_scaling]: https://learn.hashicorp.com/tutorials/nomad/autoscaler-vagrant-demo?in=nomad/autoscaler



---not required (only for view grafana)
nomad job run loki.nomad
nomad job run grafana.nomad

--- required
nomad job run traefik.nomad
nomad job run prometheus.nomad
nomad job run autoscaler.nomad
nomad job run webapp.nomad