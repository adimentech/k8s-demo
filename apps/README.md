Install fluxv2

`export GITHUB_TOKEN=<YOUR_TOKEN>`

`flux bootstrap github --owner=adimentech --repository=k8s-demo --path=apps --branch=master --components-extra=image-reflector-controller,image-automation-controller --timeout 15m`