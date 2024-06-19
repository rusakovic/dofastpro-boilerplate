# DoFastPro
![image](https://github.com/rusakovic/dofastpro-boilerplate/assets/17801144/a3f2829a-7989-4535-8c44-41407acbdff9)


## Overview

DoFastPro is a self-hosted NextJS + Supabase boilerplate with Stripe payment integration. It offers a robust, cost-effective alternative to platforms like Vercel, Supabase, AWS, and Netlify, which can incur unexpected charges due to coding mistakes or DDoS attacks. By hosting on your own server, you can avoid these pitfalls and control your costs effectively.

## Website

Check all features and docs at [dofastpro.com](https://dofastpro.com)

## Why DoFastPro?
To avoid such situations:
![image](https://github.com/rusakovic/dofastpro-boilerplate/assets/17801144/bfc06ffe-894b-4b8f-847a-115b387e9a14)


## Features

- **NextJS**: Version 14.2
- **Supabase**: Self-hosted database and authentication
- **Stripe**: Payment integration with API version 2024-04-10
- **Dark Mode**: Built-in support
- **Cost Efficiency**: Avoid unexpected charges from cloud providers

## Running the App

To run the DoFastPro application, follow these steps:

1. **Clone the Repository**:

```sh
git clone https://github.com/rusakovic/dofastpro.git

cd dofastpro
```

2. **Install Dependencies**:
   To have independent node-modules for each app, run:

```sh
pnpm install --shared-workspace-lockfile=false
```

3. **Configure .env files for each app**:

- apps/web/.env [Docs](https://dofastpro.com/docs/web/env)
- apps/supabase/.env [Docs](https://dofastpro.com/docs/supabase/env)

Check docs for more info.

4. **Start the Apps**:

4.1 Start supabase

```sh
pnpm run dev:supabase
```

4.2 Start web

```sh
pnpm run dev:web
```

## Why Use DoFastPro?

- **Cost Control**: Avoid unexpected charges from cloud providers.
- **Scalability**: Host on your own server with predictable costs.
- **Flexibility**: Full control over your infrastructure and deployment.

## Contact

For more information or support, reach out via:

- **Twitter**: [@maxrusakovic](https://twitter.com/maxrusakovic)
- **LinkedIn**: [Max Rusakovic](https://linkedin.com/in/rusakovic)
- **GitHub**: [rusakovic](https://github.com/rusakovic)
- **Email**: [max@dofastpro.com](mailto:max@dofastpro.com)

## Other Projects

- **[DoFastDocs.com](https://dofastdocs.com)**: NextJS boilerplate for documentation.
- **[LikeRemote.com](https://likeremote.com)**: The largest database of remote jobs.
