# Installation

## Pre-read: <a href="pre-read" id="pre-read"></a>

* Know the basics of Kubernetes: [https://www.youtube.com/watch?v=PH-2FfFD2PU\&t=3s](https://www.youtube.com/watch?v=PH-2FfFD2PU\&t=3s)
* Know the [basics of kubectl](https://www.tutorialspoint.com/kubernetes/kubernetes_kubectl_commands.htm) commands
* Know kubernetes manifests: [https://www.youtube.com/watch?v=ohSUtEfDefc](https://www.youtube.com/watch?v=ohSUtEfDefc)
* Know how to manage env values, secrets of any service deployed in kubernetes [https://www.youtube.com/watch?v=OW244LxB4oI](https://www.youtube.com/watch?v=OW244LxB4oI)
* Know how to port forward to a pod running inside k8s cluster and work locally [https://www.youtube.com/watch?v=TT3nd5n5Yus](https://www.youtube.com/watch?v=TT3nd5n5Yus)
* Know sops to secure your keys/creds: [https://www.youtube.com/watch?v=DWzJ87KbwxA](https://www.youtube.com/watch?v=DWzJ87KbwxA)

## 1. Choose the Cloud <a href="v-1-choose-the-cloud" id="v-1-choose-the-cloud"></a>

Choose you cloud and follow the Instruction to setup a Kubernetes cluster before moving on to the Deployment.

{% content-ref url="on-aws.md" %}
[on-aws.md](on-aws.md)
{% endcontent-ref %}

## 2. Deployment <a href="2-deploy-digit" id="2-deploy-digit"></a>

{% content-ref url="ifix-deployment-1.md" %}
[ifix-deployment-1.md](ifix-deployment-1.md)
{% endcontent-ref %}

{% content-ref url="broken-reference" %}
[Broken link](broken-reference)
{% endcontent-ref %}

## 3. Destroy the Cluster <a href="5-destroy-the-cluster" id="5-destroy-the-cluster"></a>

Finally, cleanup the cluster Setup if you wish, using the following command. This will delete the entire cluster and other cloud resources that were provisioned for the DIGIT Setup.

```
cd DIGIT-DevOps/infra-as-code/terraform/my-digit-eks
terraformdestroy​
```

## Conclusion: <a href="conclusion" id="conclusion"></a>

All Done, we have successfully Created infra on Cloud, Deployed Digit in the cluster.
