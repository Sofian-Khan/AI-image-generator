# OpenAI Image Generator

This is a simple image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.

2. Open your web browser and go to `http://localhost:<port_number>` (replace `<port_number>` with the port number you specified in the `.env` file).

3. Enter a prompt and select an image size.

4. Click the "Generate Image" button.

5. The generated image will be displayed below the form.

## Project Structure

- `app.js`: Entry point of the application, sets up the Express server and middleware.
- `routes/openaiRoutes.js`: Defines the API routes for the OpenAI functionality.
- `controllers/openaiController.js`: Contains the logic for generating the image using the OpenAI API.
- `public`: Static folder for serving HTML, CSS, and client-side JavaScript files.

## Dependencies

- `express`: Web framework for Node.js.
- `dotenv`: Loads environment variables from a `.env` file.
- `openai`: Official OpenAI API library for Node.js.

