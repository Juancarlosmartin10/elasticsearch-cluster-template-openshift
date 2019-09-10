# elasticsearch-cluster-template-openshift

# Set securityContext
      runAsUser: 1000120000 on Openshfit Deployment config
      
# Set vm.max_map_count variable on machine where cointainer will run.
      sudo sysctl -w vm.max_map_count=262144
