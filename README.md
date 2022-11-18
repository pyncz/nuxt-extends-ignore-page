# Workaround how to ignore some resources of the apps you're extending from

You can simply add unwanted pages, components etc into the `.nuxtignore` file of your main app:

```bash
# .nuxignore
sub-app/pages/to-ignore.vue
```

[See docs](https://nuxt.com/docs/guide/directory-structure/nuxtignore#nuxt-ignore-file).
