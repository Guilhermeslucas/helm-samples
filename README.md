# helm-samples
Repo to store some helpful helm charts

# Installing helm client

Helm is separeted between two main components: helm client and tiller. Tiller is basically the helm server that stays inside a Kubernetes cluster. It's the component that
the helm client talks with. So, Helm client must be installed on a local machine and tiller will stay on the cluster.

First, lets install the helm binary. Find the corresponding binay to your OS in this [link](https://github.com/helm/helm/releases).
Download it, and extract like this:

``` shell
tar -zxvf <name_of_the_tar_file>
```

After doing that, you'll have a binary. Move this binary to the ```bin``` folder like this:

``` shell
mv <binary_name> /usr/bin/helm
```

Type ```helm``` in order to test it.

# Creating a chart


# Deploying a chart

