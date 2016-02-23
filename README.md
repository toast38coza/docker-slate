# Documentation

Slate style documentation for MicroServices. 

* Read the full writeup: [Document your API with Slate and Docker](http://blog.toast38coza.me/document-your-api-with-slate-and-docker/)

## To run the installation: 

**Run the docs**

```
docker-compose up
```

You should now be able to see it on: `http://docker-machine-ip:4567`

**Apply local changes**

To apply local changes you've made to the markdown, you will need to restart the service:

```
docker-compose restart
```

et wala. Documentation

**Related links:** 

* [Slate documentation](https://github.com/tripit/slate)
