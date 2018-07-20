# Kubernetes deployment for Open vSwitch based network plugin monitoring

This is a simple Kuberentes deployment which installs the Prometheus with the Open vSwitch statistics exporter, and sets up the monitoring server to automatically read the available nodes from Kubernetes API and add them to scrape targets. Use this along with our OVS based network plugin.

To set up simply add the deployment by:

``kubectl apply –f ovs-monitoring.yml``
