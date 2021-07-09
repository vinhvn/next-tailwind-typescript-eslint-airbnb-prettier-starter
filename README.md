# Tailwind CSS + TypeScript + Eslint + Airbnb + Prettier + Next.js Starter

A lightweight boilerplate to get up and running with Tailwind CSS, TypeScript, Eslint w/ Airbnb config and Prettier set up with Next.js.

## 🔍 Preview

![Preview](https://s.vincentnguyen.ca/UnsecularisedFirstgenerationMidge.png)

## 🔧 Usage

### 1. Clone Repo

You can generate your own repo from this template by using [this link](https://github.com/vinhvn/next-tailwind-typescript-eslint-airbnb-prettier-starter/generate).

From there, you can clone your own repo and modify it however you like.

If you would rather clone this repo, go to the command line and run:

```bash
git clone https://github.com/vinhvn/next-tailwind-typescript-eslint-airbnb-prettier-starter <your-project-name>
cd <your-project-name>
```

### 2. Install Dependencies

```bash
yarn # npm i
```

### 3. Run Development Environment

```bash
yarn dev # npm run dev
```

### Test Production Environment

I also included a `stage` script that will build and start a production server. You can run it with:

```bash
yarn stage # npm run stage
```

Alternatively you can run:

```bash
yarn build # npm run build
yarn start # npm start
```

## 📝 Important Notes

* Be sure to update the `package.json` to include your own information for the project you're working on.
* Purge CSS will only run in production, so use either `build` or `stage` to run it and minimize your CSS file size. You can also modify the `postcss.config.js` file to enable Purge CSS in development.

## 🔖 Contributions

Thank you to kyrelldixon and his [amazing starter](https://github.com/kyrelldixon/next-tailwind-typescript-starter) that I used as a template.
