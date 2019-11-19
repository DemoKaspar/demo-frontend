# Humanitec demo frontend

## Overview

This is a simple frontend that displays a list of products and lets you add more. Together with the [demo backend](https://github.com/walhall-tutorials/demo-backend), its purpose is to demonstrate how to deploy a simple app on the [Humanitec internal developer platform](https://humanitec.com).

The frontend consists of a client package and a server package. The client package is a React app and is served from `/`. The server package handles API requests from the client on the `/api` endpoint.

This frontend is **pre-configured** to work with Walhall. All you have to do is fork it into your **organization account,** add it to your Walhall app, and click **Deploy.** No changes to the code are necessary.

## Environment variables

The frontend accepts two configuration variables:

-  `DEMO_BACKEND_SERVER`: used to find the demo backend. It defaults to `http://backenddemo-service:8080`.
-  `PORT`: the port number the server should be exposed on. It defaults to `8080`.

Note that these variables are **pre-configured** to work in Walhall; you do not need to specify them in the config map or in the secrets.