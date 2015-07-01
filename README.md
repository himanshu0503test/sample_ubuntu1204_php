Sample PHP
===============

This sample helps you create a shippable.yml file for your PHP project on Shippable. Please refer to our [language specific documentation on PHP](http://docs.shippable.com/languages/#php) for more details.

### Build Image

The sample uses a php specific build image that's available for public use:
[shippableimages/ubuntu1204_php](https://registry.hub.docker.com/u/shippableimages/ubuntu1204_php)  ([Dockerfile](https://github.com/shippableImages/ubuntu1204_php/blob/master/Dockerfile)).

To set your build image in Shippable:
- Login to [Shippable](https://www.shippable.com) 
- Navigate to your project page by clicking on the project link
- Click on **Settings** and choose the following option:

`Pull Image from : shippableimages/ubuntu1204_php`

For more details on project settings, you can refer our docs on  [Build and Project Settings](http://docs.shippable.com/project_settings).
