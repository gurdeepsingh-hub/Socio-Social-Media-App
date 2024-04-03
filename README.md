# Socio

Socio is a simple social media application built using React, Redux, and Node.js. The application allows users to create an account, log in, and post messages that can be seen by other users.

## Installation

You can install Socio by following these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/gurdeepsingh-hub/socio.git
   ```
2. Move into the project directory:
   ```bash
   cd socio
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file in the root of the project and add the following:
   ```makefile
   REACT_APP_API_URL=http://localhost:5000/api
   ```
5. Start the server:
   ```bash
   npm start
   ```

The application will be accessible at [http://localhost:3000](http://localhost:3000).

## Building

Socio is built using React and Redux for the frontend, and Node.js and Express for the backend. The frontend and backend are served separately.

The frontend can be built for production using the following command:

```bash
npm run build
```

The built files will be available in the `build` directory.

The backend can be built for production using the following command:

```bash
npm run build:server
```

The built files will be available in the `build` directory.

### Editing OAuth Configuration

If you've cloned this repository and plan to use OAuth authentication with Google, you'll need to add the `oauth_config.json` file with your own OAuth credentials. Follow these instructions to update the file:

1. create the `oauth_config.json` file in the root directory of the project.

2. Replace the existing values with your own OAuth credentials obtained from the Google Developer Console.

3. Save the changes to the file.

Once you've created the `oauth_config.json` file with your credentials, you'll be able to use OAuth authentication with Google in your application. Make sure to keep your credentials secure and never expose them publicly.

## Testing

Socio uses Jest for unit testing and Cypress for end-to-end testing.

To run the unit tests:

```bash
npm test
```

To run the end-to-end tests:

```bash
npm run cypress:open
```

## Contributing

We welcome contributions to Socio! If you have an idea for a new feature or have found a bug, please open an issue. If you have a fix or improvement, please submit a pull request.

## License

Socio is released under the MIT License.

## Contact

For any questions or concerns, please contact us at contact@example.com.

## Authors and Contributors

Gurdeep Singh [(gurdeepsingh-hub)](https://github.com/gurdeepsingh-hub)
