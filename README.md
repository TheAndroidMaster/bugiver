Bugiver is a simple website that iterates through everyone that you are following on GitHub and selects a random issue in a completely random repository in a language of your choice. I have designed it as my personal "I have nothing to do" button that gives me something to do in a possibly futile attempt to encourage myself to contribute to more repositories than I create.

## Stuff

1. Upon pressing the "Sign In" button, users are redirected to [/auth](./auth/index.html) where the authentication happens.
2. The application's private API key is stored in a heroku application running [HenrikJoreteg/github-secret-keeper](https://github.com/HenrikJoreteg/github-secret-keeper).
3. Upon getting a result, users are redirected to the main page, where a lot of stuff happens.
4. Potential issue candidates are added to a map, and a separate map of languages and labels are formed to allow users to filter them.
5. An issue is selected at random, one more API request is sent, and the resulting issue data is displayed.

## Contributing

Contributions are accepted. See [CONTRIBUTING.md](./.github/CONTRIBUTING.md) for more information.
