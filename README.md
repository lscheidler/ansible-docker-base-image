# Create new base image for debian stretch

```
sudo ansible-playbook create_base_image.yml -e distribution=stretch
```

# Create new base image for debian stretch and force apt update

```
sudo ansible-playbook create_base_image.yml -e distribution=stretch -e force=true
```

# License

The playbook is available as open source under the terms of the [Apache 2.0 License](http://opensource.org/licenses/Apache-2.0).
