docker_build('goke', './app', 
    dockerfile='app/Dockerfile'
    #only=["cmd","config","static","templates"]    
)
docker_compose('docker-compose.yml')

# load('ext://helm_resource', 'helm_resource', 'helm_repo')
# helm_repo('bitnami', 'https://charts.bitnami.com/bitnami')
# helm_resource('mysql', 'bitnami/mysql')

# # k8s_yaml(helm('./charts/my-chart'))
# yaml = helm(
#   'chart',
#   # The release name, equivalent to helm --name
#   name='goke',
#   # The namespace to install in, equivalent to helm --namespace
#   namespace='goke',
#   # The values file to substitute into the chart.
#   # values=['./path/to/chart/dir/values-dev.yaml'],
#   # Values to set from the command-line
#   # set=['service.port=1234', 'ingress.enabled=true']
#   )
# k8s_yaml(yaml)

# k8s_yaml('deployments/kubernetes.yaml')
# k8s_resource('example-go', port_forwards=8000)

# k8s_resource(
#     'example-go', 
#     port_forwards=8000, 
#     resource_deps=['deploy'])

# Records the current time, then kicks off a server update.
# Normally, you would let Tilt do deploys automatically, but this
# # shows you how to set up a custom workflow that measures it.
# local_resource(
#     'deploy',
#     './record-start-time.sh',
# )