# helm-library-demo

libchart project contains the Helm library chart    
development project contains the Helm application chart
staging project contains the Helm application chart

## Commands
helm package libchart/    
helm dependency update development/ </br>
helm dependency update staging/ </br>
helm template nginx ./development -f development/application/nginx.yaml
