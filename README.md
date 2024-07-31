# NextJS Tutorial

Tutorial video: https://www.youtube.com/watch?v=ZVnjOPwW4ZA

## Getting Started

Open up the command prompt, cd to your project folder, and run:

```cmd
npx create-next-app@13.4
```

Give the new folder a name like "next-app" and then select all of the default settings.

Go to the new folder:
```cmd
cd next-app
```

To start a local server, run:
```cmd
npm run dev
```

Create a new folder called users and a new file called page.tsx.

In the new file use the following shortcut and press enter for boilerplate code:
```tsx
rafce
```

## Client Side Rendering vs Server Side Rendering

Client Side Rendering:
<li>Large bundles - the larger the bundle, the more memory we need (Resource Intensive)</li>
<li>No SEO - search engine bots, or machines tha browse and index are windows, can't view our content since that can't execute JS code, therefore they can't render our components like a web browser</li>
<li>Less secure - API keys will be exposed</li>

Server Side Rendering:
<li>Smaller bundles</li>
<li>Resource Efficient</li>
<li>SEO - Since rendering is done on the server and we send content to the client, search engine bots can view and index our pages</li>
<li>More secure</li>

While we default to Server Components, they cannot:
<li>Listen to browser events</li>
<li>Access brosswer APIs</li>
<li>Maintain state</li>
<li>Use effects</li>
