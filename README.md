# Installation of Eksctl in Windows

https://docs.aws.amazon.com/emr/latest/EMR-on-EKS-DevelopmentGuide/setting-up-eksctl.html

1) Firstly we have to install chocolatey

```
https://chocolatey.org/install#individual

```

![alt text](image.png)

After Installing Chocolately through poweshelll in windows cross check it 

```
choco
```

![alt text](image-1.png)

2) Installing Eksctl

https://docs.aws.amazon.com/emr/latest/EMR-on-EKS-DevelopmentGuide/setting-up-eksctl.html

![alt text](image-2.png)

```
chocolatey install -y eksctl
```

![alt text](image-3.png)

```
chocolatey upgrade -y eksctl
```

![alt text](image-4.png)

3) Check the ekctl vresion

```
eksctl version
```

![img_1.png](img_1.png)