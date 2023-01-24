A fork of [electron-react-boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate) with three separate renderer windows. Each window is functional both in development and in the packaged app.

<br>

I am following the example of [this repo](https://github.com/jp887/electron-react-boilerplate) which serves the same purpose but starts from an earlier version of electron-react-boilerplate. Compared to that repo, a few additional steps are needed to create the present template, most notably involving the HtmlWebpackPlugin plugin in webpack.config.renderer.dev.ts and webpack.config.renderer.prod.ts files. See [commit history](https://github.com/wds4/electron-react-boilerplate-multiple-windows/commits) for the steps.

## Install

Clone the repo and install dependencies:

```bash
git clone --depth 1 --branch main https://github.com/wds4/electron-react-boilerplate-multiple-windows.git your-project-name
cd your-project-name
npm install
```

## Starting Development

Start the app in the `dev` environment:

```bash
npm start
```

## Packaging for Production

To package apps for the local platform:

```bash
npm run package
```

## License

MIT © [Electron React Boilerplate](https://github.com/electron-react-boilerplate)
