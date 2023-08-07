# How to Add Google Analytics to a Nextra Website

This demo site shows how to add Google Analytics to a [Nextra](https://nextra.site) website.

## Usage

1. Fork this repo.

2. Clone your forked copy.

3. Run `npm install` to install the predefined dependencies.

4. Deploy the site to Vercel.

5. [Create a Google Analytics 4 property](https://support.google.com/analytics/answer/9304153) for the site.

6. Create a `.env.local` file in the project's root directory.

7. Add `NEXT_PUBLIC_GA_ID=G-xxxxxxxxxx` to the `.env.local` file. (**Note:** Please replace `G-xxxxxxxxxx` with your Google Analytics measurement id.)

8. Add your Google Analytics measurement id to your [Vercel environment variables](https://vercel.com/docs/concepts/projects/environment-variables?utm_source=next-site&utm_medium=docs&utm_campaign=next-website).

9. Once you've deployed all updates to Vercel, navigate to various pages of your live site.

10. Verify that the gtag works from your site's Google Analytics account.

## License

This project is licensed under the MIT License.
