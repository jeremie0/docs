---
title: Login
default: true
description: This tutorial demonstrates how to add user login to your application with Auth0
---

<%= include('../../../_includes/_package', {
  org: 'auth0-community',
  repo: 'auth0-ember-samples',
  path: '01-Login'
}) %>

<%= include('../../../_includes/_callback_url') %>

If you are following along with the downloadable sample projects for this tutorial directly, the **Callback URL** should be set to

```bash
http://localhost:4200
```

<%= include('../_includes/_install_auth0js') %>

<%= include('_includes/_centralized_login') %>