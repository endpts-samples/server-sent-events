# Server-Sent Events with Node.js

This sample demonstrates how to use Server-Sent Events (SSE) to stream events from a Node.js server to the browser.

Check out the complete blog post on [blog.endpts.io/server-sent-events-with-nodejs](https://blog.endpts.io/server-sent-events-with-nodejs)

## Local Development

> **NOTE:** Node 18.x or greater is required

To get started locally, install the dependencies and start the dev server:

```bash
npm install && npm run dev
```

With the development server running, you can fire up your browser and visit [localhost:3000](http://localhost:3000) and stream the events from the `/events` endpoint.

Alternatively, you can call the `/events` endpoint directly from your terminal:

```bash
curl --no-buffer http://localhost:3000/events
```

## Deploying to endpts.io

Deploy your project to the cloud with [endpts.io](https://dashboard.endpts.io) ([Deployment documentation](https://docs.endpts.io/core-concepts/deployments)).
