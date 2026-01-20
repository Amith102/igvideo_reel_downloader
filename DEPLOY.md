# How to Update Your Website

Your website is set up for **Continuous Deployment** with Vercel. This means you don't need to manually "upload" files. The site updates automatically whenever you push code to GitHub.

## The Process

1.  **Make Changes**: Edit your code locally on your computer.
2.  **Save & Commit**:
    ```bash
    git add .
    git commit -m "Describe your changes here"
    ```
3.  **Push to GitHub**:
    ```bash
    git push origin main
    ```
4.  **Done!**: Vercel detects the new code on GitHub and automatically builds and deploys your website.

## Checking Status

-   Go to your [Vercel Dashboard](https://vercel.com/dashboard).
-   Select your project (`igvideo_reel_downloader`).
-   You will see the "Deployment" status (Building, Ready, or Error).
-   Once "Ready", your changes are live on the web!

## Troubleshooting

If your site doesn't update:
1.  Check your terminal for errors when pushing.
2.  Check the Vercel dashboard for build errors (Logs).
