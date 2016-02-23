# chef-workspace
This cookbook is used to prepare the environment we need for development. The receipe **app** will be used to construct all app folders we need to run.
```bash
$ cd chef-repo
$ chef-client --local-mode --runlist 'recipe[app]'
```

How to create this cookbook from scratch
```bash
$ sudo dpkg -i chefdk_0.10.0-1_amd64.deb
$ mkdir chef-repo; cd chef-repo
$ chef generate cookbook app
```
