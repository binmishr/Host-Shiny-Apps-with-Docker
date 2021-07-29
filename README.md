# Host-Shiny-Apps-with-Docker

 A very basic setup to host your Shiny apps with Docker over HTTPS using your custom domain.

But why dockerize Shiny apps in the first place? Let's see what Shiny and Docker have in common. Shiny "makes it easy to build interactive web apps straight from R", while Docker is the "de facto standard to build and share containerized apps – from desktop, to the cloud". Their intersection is the web and web applications belong to the web.

This post walks you through a very basic setup on your own virtual machine. In the end, you'll have a dockerized setup serving Shiny apps over HTTPS on your own domain, very similar to the one where we used Caddy to securely host apps on Shiny Server. But here you'll see how to achieve the same with Docker.

The codeset is attached in the .docx file in this repository.
