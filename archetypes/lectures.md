+++
title = "{{ replace .File.ContentBaseName "-" " " | title }}"
outputs = ["Reveal"]
draft = true
[reveal_hugo]
margin = 0.2
+++

## {{ replace .File.ContentBaseName "-" " " | title }}

- First point

{{ `{{% note %}}` }}

- Instructor notes for this slide.

{{ `{{%/ note %}}` }}

---

## Next slide

- Point
