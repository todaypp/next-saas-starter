# Next Saas Starter

<!-- markdownlint-disable MD033 -->
<br/>
<p align="center">

  <a href="https://github.com/Blazity/next-saas-starter" >
    <img src="https://i.imgur.com/jmc2Q1w.png" alt="Logo"  width="49%">
  </a>
   <a href="https://github.com/Blazity/next-saas-starter">
    <img src="https://i.imgur.com/CxkjHhi.png" alt="Logo" width="49%">
  </a>

  <h3 align="center">✨ Free Next.js marketing website template for SaaS startups ✨</h3>

  <p align="center">
    Everything you need to build a great landing page / marketing website for your startup. Great SEO metrics, Green WebVitals, 🚀 Performance, Clean & Pragmatic Codebase out of the box.
    <br/>
    <br/>
    <a href="https://next-saas-starter-ashy.vercel.app/">View Demo</a>
    .
    <a href="https://github.com/Blazity/next-saas-starter/issues">Report Bug</a>
    .
    <a href="https://github.com/Blazity/next-saas-starter/issues">Request Feature</a>
  </p>
</p>

<div align="center">

![Contributors](https://img.shields.io/github/contributors/Blazity/next-saas-starter?color=dark-green) ![Issues](https://img.shields.io/github/issues/Blazity/next-saas-starter) ![License](https://img.shields.io/github/license/Blazity/next-saas-starter)

</div>

<p align="center"><b>Created with :heart:  at Blazity </b></p>
<p align="center"><a href="https://blazity.com/">Blazity</a> is a group of Next.js/Jamstack/Headless experts. Contact us at <a href="mailto:contact@blazity.com">contact@blazity.com</a> if you’d like to talk about your project or just to have a chat with us :grin:</p>
<!-- markdownlint-enable MD033 -->

## Table Of Contents

- [🤩 Features](#-features)
- [🚀 Getting Started](#-getting-started)
- [One click deploy](#one-click-deploy)
- [🧰 Built With](#-built-with)
- [🤲🏻 Contributing](#-contributing)
  - [Creating A Pull Request](#creating-a-pull-request)
- [😎 Acknowledgements](#-acknowledgements)
- [✨ Contributors](#-contributors)
- [📝 License](#-license)

## 🤩 Features

- ⚡ **Next.js** - React framework for static rendering
- 🤩 **Best SEO setup** - Meta Tags, JSON-LD and Open Graph Tags
- ✅ **Optimized for Web Vitals**
- 📜 **Blog with MDX**
- 📫 **Mailchimp Integration** - for newsletters
- 🗳 **Sendgrid Integration** - for sending emails
- 🌃 **Dark mode** - and customizable themes!
- 🧽 **No UI library** - just styled components, so you don't have to learn any new syntax
- 🖱 **One click deployment** - with Vercel or any other serverless deployment environment
- 🔍 **Eslint** - with Next.js's recommended settings and imports sorting rule
- 🕯 **Prettier**

## 🚀 Getting Started

- Click `Use the template` or [this link](https://github.com/Blazity/next-saas-starter/generate)
- Setup your [sendgrid](https://sendgrid.com/) API key and add it to environment variables (`SENDGRID_API_KEY` - `.env.local`)
- Adjust the template to your needs (and checkout `env.ts` file)
- Deploy the project on [Vercel](https://vercel.com/) **don't forget to add env variables**

```sh
# run the dev mode
$ yarn dev

# run the prod mode
yarn start

# build the app
yarn build
```

- [env-cmd](https://www.npmjs.com/package/env-cmd) provides environment variables of multiple environments to the scripts of [package.json](./package.json).
- It can be used in combination with [cross-env](https://www.npmjs.com/package/cross-env).
- Below is an example of [.env-cmdrc](.env-cmdrc) (property names are shortened to simplify it on the script)

```json
{
  "c": {
    "APP_NAME": "next-saas-starter",
    "ENV": "common"
  },
  "a": {
    "ANALYZE": true,
    "ENV": "analyze"
  },
  "d": {
    "BACKEND_PORT": "4000",
    "ENV": "development",
    "PORT": "3000"
  },
  "t": {
    "BACKEND_PORT": "4100",
    "ENV": "test",
    "PORT": "3100"
  },
  "ci": {
    "BACKEND_PORT": "4200",
    "CI": true,
    "PORT": "3200"
  },
  "p": {
    "BACKEND_PORT": "4300",
    "ENV": "production",
    "PORT": "3300"
  }
}
```

## One click deploy

Clone the repository and one-click deploy to Vercel for free!

[![Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/Blazity/next-saas-starter)

Clone the repository and one-click deploy to Netlify for free!

[![Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Blazity/next-saas-starter)

## 🧰 Built With

- Statically generated pages with [**Next.js**](https://github.com/vercel/next.js)
- [Styled components](https://github.com/styled-components/styled-components/)
- [MDX](https://github.com/mdx-js/mdx)
- [TypeScript](https://github.com/Microsoft/TypeScript)

## 🤲🏻 Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

- If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/Blazity/next-saas-starter/issues/new) to discuss it, or directly create a pull request after you edit the _README.md_ file with necessary changes.
- Create individual PR for each suggestion.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 😎 Acknowledgements

Big thanks to authors of these libraries:

- <https://github.com/neg4n/next-api-og-image> - generating open graph images
- <https://github.com/blazity/nextjs-color-mode> - non-flickering dark mode
- <https://github.com/Brew-Brew/css-in-js-media> - a convenient way of creating media queries

## ✨ Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable MD033 -->
<table>
  <tr>
    <td align="center"><a href="https://bstefanski.com/"><img src="https://avatars.githubusercontent.com/u/28964599?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Bart Stefanski</b></sub></a><br /><a href="https://github.com/Blazity/next-saas-starter/commits?author=bmstefanski" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/ilasota"><img src="https://avatars.githubusercontent.com/u/34578189?v=4?s=64" width="64px;" alt=""/><br /><sub><b>Igor Lasota</b></sub></a><br /><a href="https://github.com/Blazity/next-saas-starter/commits?author=ilasota" title="Code">💻</a></td>
  </tr>
</table>
<!-- markdownlint-enable MD033 -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## 📝 License

Distributed under the MIT License. See [LICENSE](https://github.com/Blazity/next-saas-starter/blob/main/LICENSE.md) for more information.
