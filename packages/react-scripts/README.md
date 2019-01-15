# @teip/react-scripts

This is a fork of the official react scripts containing only a simple addition: The `@teip/loader` for GraphQL files (`.gql`/`.graphql`). This allows for the use of create-react-app with [Teip](https://github.com/hendrikniemann/teip).

## Usage

If you want to create a new app with this version of react-scripts:

```
create-react-app --scripts-version=@teip/react-scripts myapp
```

If you want to add `@teip/loader` to your React app:

```
yarn remove react-scripts
yarn add @teip/react-scripts
```
