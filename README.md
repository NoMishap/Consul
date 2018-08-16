# ConsulNoMishap
consul configuration and script for NoMishap project

## Install metricbeat to monitor consul vm performance

```bash
curl -L -O https://artifacts.elastic.co/downloads/beats/metricbeat/metricbeat-6.3.2-amd64.deb
sudo dpkg -i metricbeat-6.3.2-amd64.deb
```

mod file in /etc/metricbeat/metricbeat.yml changing host elasticsearch target