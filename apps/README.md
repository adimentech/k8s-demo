Install fluxv2

`export GITHUB_TOKEN=<YOUR_TOKEN>`

`flux bootstrap github --owner=adimentech --repository=k8s-demo --path=flux --branch=master --components-extra=image-reflector-controller,image-automation-controller`