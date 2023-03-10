# ROMPortfolio_CV-RafaelOrozco

Welcome to this repository where you will learn how to design a professional portfolio using Dash, a Python framework for building analytical web applications. In this tutorial, we will guide you through the steps required to create a stunning portfolio that showcases your skills and expertise.

We will also cover the deployment process of your portfolio to Google Cloud, allowing you to share your work with the world.

This tutorial assumes some knowledge of Python and web development, but we have provided detailed explanations and code examples to make it accessible for beginners as well. So whether you are a seasoned developer or just starting out, this tutorial will help you take your portfolio to the next level.

Let's get started!

You can use my template and change it for your information

To make the deployment:

Buid your app first:
```
gcloud builds submit --tag gcr.io/{APP_ID}/{NAME_DEPLOY} --project={APP_ID}
```
The, deploy your app to Google Cloud

```
gcloud run deploy --image gcr.io/{APP_ID}/{NAME_DEPLOY} --platform=managed --project={APP_ID} --allow-unauthenticated
```

