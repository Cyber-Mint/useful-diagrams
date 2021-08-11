# Introduction

This repository is a collection of some useful diagrams utilised by Tech Teams.  This is not a comprehensive catalog but we have found that we do tend to use the majority of the diagram types listed here.

Where possible we tend to prefer diagrams that live close to our code and even preferably in the form of code.  This aligns with the **Cyber-Mint** philosophy of `everything-as-code` and allows us to apply version control to our documentation (kept in markdown) and then apply the same philosophy to the diagrams especially when created in [plantuml](https://plantuml.com/).

## Developer Hints

For the developer who uses [VSCode](https://code.visualstudio.com/Download) there are good plugins for working with and previewing `plantuml` format files. Use Ctl-P to access the VSCode command pallet and install with:
```
ext install plantuml
``` 

This repository makes extensive use of `plantuml` and assuming you have the docker dependencies installed you may find the following docker image useful.

```
docker run -d -p 8888:8080 plantuml/plantuml-server:jetty
```

Open your browser on `localhost:8888` to access your very own local plantuml server.

[[Home](./README.md)] [[Next >> Generic Diagrams](./generic.md)]
<br>

---
&copy; Copyright 2021, Cyber-Mint (Pty) Ltd, and distributed under the MIT License.