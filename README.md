# kustomization-examples

This repository is for demonstrating the capabilities of kustomize.

### Repo Layout

/examples  
    /basic - trivial examples of basic usage, 1:1 with kustomize subcommands  
    /use-cases - more complex examples of common use cases  

Each example kustomization contains a /build folder, which contains the result of `kustomize build [EXAMPLE]`, or `kubectl apply -k [EXAMPLE] -o yaml`.
