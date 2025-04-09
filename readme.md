## README

This is a small project to built with blazor and tailwindcss.

To run the project,

-   Install Node.js from [https://nodejs.org/en/download](https://nodejs.org/en/download)
-   open one terminal
    -   Run `npm i`
    -   Run `npx tailwindcss -i ./wwwroot/css/tailwind.css -o ./wwwroot/css/app.css --watch`
-   Open another terminal and Run `dotnet watch`

NOTE: Ensure both terminals are running and for any tailwindcss changes you add to your razor pages, app.css will include the class/utility from tailwind's library.
