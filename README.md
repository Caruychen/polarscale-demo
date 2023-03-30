# Polarscale

This respository contains the client and server code for the polarscale web application.

## Client

Built on top of a react framework, the project structure is fairly simple. Instructions for setting up the project can be found at this [README](https://github.com/Caruychen/polarscale-demo/blob/main/client/README.md)

## Server

Technically, the backend uses serverless functions deployed on Supabase. Supabase edge functions run on deno, so we avoid using npm package installs. 

A detailed guide on getting serverless functions running on Supabase can be found here: https://supabase.com/docs/guides/functions/quickstart
