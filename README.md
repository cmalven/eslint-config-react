# Malven Co. ESLint Config for React 
Malven Co. Javascript coding standards for React projects using [ESLint](http://eslint.org)

---

## How to Use

```
npm i -D eslint @malven/eslint-config-react  eslint-plugin-react
```

### In your global or project-specific .eslintrc

```json
// in .eslintrc

{
  "extends": ["@malven/react"],
  "settings": {
    "react": {
      "version": "latest"
    }
  }
}
```
