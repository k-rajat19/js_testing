<p>
    <a href="https://www.npmjs.com/package/js_testing">
        <img src="https://img.shields.io/npm/v/js_testing?style=flat-square" alt="npm version" />
    </a>
    <img src="https://img.shields.io/npm/l/color-calendar?style=flat-square" alt="license" />
</p>

- [About](#about)
- [Usage](#usage)
- [How it works](#works)


<a id="about"></a>
# About
- `js_testing` is a JavaScript testing framework based on [jest](https://github.com/facebook/jest) architecture.
- It is build using some of `jest` packages.

<br/>I've decided to make this project to understand how `jest` internally works. 
<br/> Thanks to [Christoph Nakazawa](https://github.com/cpojer) for explaining the `jest` architecture as it helps me to make this project and to contribute in `jest` as well.

<a id="usage"></a>
# Usage
Note : Make sure you have installed node version 14+
#### Installation

```bash
yarn add js_testing
```
Or
```bash
npm i js_testing
```

Add the following section to your `package.json`:
```json
{
  "scripts": {
    "test": "js_testing"
  }
}
```

And all set !  now you can  write basic tests and to run those test - run `yarn test` or if you are using npm then `npm test`.
<br/>You can able to use all [Matchers](https://jestjs.io/docs/using-matchers) and even [Mock Functions](https://jestjs.io/docs/mock-functions) of `jest`!

![2021-12-08-00-13-26 (2)](https://user-images.githubusercontent.com/81867225/145091743-c0685be1-8417-451c-869e-c9b05df60c6c.gif)



# How it Works
<a id="works"></a>
In the below diagram i try to explaining how this packages works.Obviously it doesn't contains all things it gives you a very basic idea that how all this works.
![arch1](https://user-images.githubusercontent.com/81867225/145719394-a958a086-d993-4e6f-a1ad-b180983d5c87.png)

As you can see it consist of several jest core packages. 
You can read more about the use of these packages [here](https://github.com/facebook/jest/tree/main/packages).

