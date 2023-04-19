# nextjs-tailwind-storybook-with-ci-cd (Status: :construction: WIP)

This repository is built to provide a ready-to-go template for the projects that are using the following tech stacks:

1. NextJS
2. Tailwind
3. Storybook
4. Jest
5. React Testing Library
6. Eslint
7. Prettier

This template will provide the full setup under the hood and will save a big portion of your time. You have to just create your new repo using this template.

## Package Versions

Following versions were installed when this template was built.

| Package Name              |       Version |
| :------------------------ | ------------: |
| NodeJS                    | **`16.10.0`** |
| NextJS                    |  **`13.3.0`** |
| react                     |  **`18.2.0`** |
| react-dom                 |  **`18.2.0`** |
| tailwindcss               |   **`3.3.1`** |
| postcss                   |  **`8.4.21`** |
| jest                      |  **`29.5.0`** |
| jest-environment-jsdom    |  **`29.5.0`** |
| @testing-library/jest-dom |  **`5.16.5`** |
| @testing-library/react    |  **`14.0.0`** |
| eslint                    |  **`8.38.0`** |
| eslint-config-next        |  **`13.3.0`** |
| eslint-config-prettier    |   **`8.8.0`** |
| prettier                  |   **`2.8.7`** |
| storybook                 |   **`7.0.5`** |

## Avaialable Commands

There are some commands preadded to this template. These commands will help to execute basic tasks.

1. Following command will start the dev server at port `3000` and we can visit the site at **http://localhost:6006**.

   ```
   yarn dev
   ```

2. Following command will create a production build of the site.

   ```
   yarn build
   ```

3. Following command will start a server at port `3000` with the production build (created using `yarn build`) and we can visit the site at **http://localhost:3000**.

   ```
   yarn start
   ```

4. Following command will check any linting issue according to the eslint rules set in the `.eslintrc.json` file.

   ```
   yarn lint
   ```

5. Following command will execute all the unit tests (file with `*.test.jsx`, `*.test.tsx`, `*.test.js` or `*.test.ts` extention) and check whether all the tests pass or not.

   ```
   yarn test
   ```

6. Following command will execute unit tests (file with `*.test.jsx`, `*.test.tsx`, `*.test.js` or `*.test.ts` extention) and check whether all the tests pass or not in the real-time.

   ```
   yarn test:watch
   ```

7. Following command will start the storybook server at port 6006 and we can visit the story at **http://localhost:6006**.

   ```
   yarn storybook
   ```

8. Following command will create a static web application capable of being served by any web server. For more info please visit [**Publish Storybook**](https://storybook.js.org/docs/react/sharing/publish-storybook).

   ```
   yarn build-storybook
   ```
