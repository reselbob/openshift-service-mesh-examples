# openshift-service-mesh-examples

**UNDER CONSTRUCTION**

Get the URL to the application route by way of the service mesh

```
oc -n istio-system get route istio-ingressgateway -o jsonpath='{.spec.host}'  && echo \n
```
