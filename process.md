# Modern Development Process

In the past, we used `create-react-app` to develop our React applications, but things have changed, and we are now using **Vite** to set up our development environment.

### Why create-react-app is Not Ideal

While **create-react-app** has served developers well in the past, it comes with some limitations:

1. **Build Performance**: The build times in create-react-app can be slower, especially as applications grow. `Vite` leverages native ES modules, leading to faster build and refresh times.

2. **Configuration Flexibility**: create-react-app abstracts many configurations, which can make it harder to customize the setup for specific needs. `Vite` provides a more flexible configuration, allowing developers to fine-tune their development environment.

3. **Development Server**: The development server in create-react-app can be less efficient. `Vite` offers hot *module replacement* (HMR) that is faster and more reliable, enhancing the developer experience.

4. **Outdated Dependencies**: As time passes, create-react-app's underlying tooling may lag behind newer technologies, whereas `Vite` is designed to stay up-to-date with the latest developments in the `JavaScript` ecosystem.

### Vite

For this guide, we will use **Yarn** as our package manager.

### What is Yarn?

**Yarn** is a package manager for `JavaScript` that helps manage project dependencies. It was created to address some limitations of `npm`, particularly in terms of *speed* and *reliability*. `Yarn` offers several advantages:

- **Speed**: `Yarn` caches every package it downloads, which means subsequent installs are faster.
  
- **Deterministic Installs**: `Yarn` uses a lock file to ensure that the same dependencies are installed in the same version across different environments, reducing inconsistencies.

- **Workspaces**: `Yarn` supports workspaces, which allow you to manage multiple packages within a single repository more easily, making it ideal for monorepo setups.

Now, let’s set up your environment using `Vite`:

1. Run the command:

   ```bash
   yarn create vite app
   ```

2. Choose the library you want to use. In our case, we are using **React**.
   - Other options include:
   
        ```bash
        Vanilla
        Vue
        Preact
        Lit
        Svelte
        Solid
        Qwik
        ```
3. Select how you want to continue with your development, either using **JavaScript** or **TypeScript**.

4. `cd` into the `app` folder:

   ```bash
   cd app
   ```

5. Run `yarn` to install packages that come along with `Vite`:

   ```bash
   yarn
   ```
6. Run the application:

   ```bash
   yarn dev
   ```

And that’s all you need to begin your development process!

### Conclusion

By switching to `Vite`, you can benefit from a faster and more efficient development environment. With `Yarn` as a powerful package manager, you can easily manage dependencies and ensure consistent installs across your projects. This modern setup not only enhances productivity but also positions you well for the future of web development. Embrace `Vite` and `Yarn` to streamline your workflow and take full advantage of the latest advancements in the `React` ecosystem!
