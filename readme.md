# Notes

## ESlint install
```
npm i eslint -D
```

Add lint task in your `package.json` file:

```json
{
  ...
  "scripts": {
    "lint": "eslint"
  },
  ...
}
```

Run the init command: 
```
npm run lint -- --init
```

Now change your `lint` task in your `package.json`:

```json
{
  ...
  "scripts": {
    "lint": "eslint ./src --fix"
  },
  ...
}
```