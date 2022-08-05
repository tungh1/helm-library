# helm-library-demo

libchart project contains the Helm library chart </br>    
development project contains the Helm application chart </br>

## Commands
helm package libchart/    
helm dependency update development/ </br>
helm template nginx ./development -f development/application/nginx.yaml
