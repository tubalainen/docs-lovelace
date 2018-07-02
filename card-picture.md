### Picture

A very simple card that allows you to set an image to use for navigation to various paths in your interface. 

![picture-sample](https://user-images.githubusercontent.com/1444314/42169623-44e76f06-7de2-11e8-96ca-9cbefca25df8.png)

**Options**

| Name | Type | Default | Description
| ---- | ---- | ------- | -----------
| type | string | **Required** | `picture-entity`
| image | string | **Required**| URL of an image.
| navigate_path | string | Optional | Path of URL to navigate to

**Examples**

Basic example:

```yaml
- type: picture
  image: /local/exit.jpg
  navigate_path: /lovelace/arsaboo
```

> Check the view setup on how to setup custom ids